<template>
  <section class="container-fluid py5" id="Education">
 <div class="position-relative d-flex align-items-center justify-content-center">
          <h2 class="display-2 pt-5 text-uppercase text">Resume</h2>
        </div>
        <h3 class="mb-4 fs-1">Education and Experience</h3>
        <div class="container1">
        <div v-for="item in resume" :key="item" class="row2 align-items-center">
          <div class="col-lg">
            <div class="boarder-left border-black pt-2 pl-4 ml-2">
              <div class="position-relative ex-me mb-4">
                <h5 class="font-width fs-2 mb-1">{{ item.level }}</h5>
                <p class="mb-2 fs-4"><strong>{{ item.institution }}</strong> <small>{{ item.year }}</small></p>
                <p class="fs-4">{{ item.reflection }}</p>
              </div>
            </div>
          </div>
        </div>
        </div>
      <h3 class="mb-4 pt-5 fs-1">My skills</h3>
      <div class="cont">
    <div class="skillCard">
      <div class="percent" style="--clr:blue;--num:91;">
        <div class="dot"></div>
        <svg>
          <circle cx="70" cy="70" r="70"></circle>
          <circle cx="70" cy="70" r="70"></circle>
        </svg>
        <div class="number">
        <h2><i class="fa-brands fa-css3-alt"></i></h2>
        <p>CSS3</p>
      </div>
    </div>
  </div>
  <div class="skillCard">
    <div class="percent" style="--clr:orange;--num:95;">
      <div class="dot"></div>
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
      <h2><i class="fa-brands fa-html5"></i></h2>
      <p>HTML5</p>
    </div>
  </div>
</div>
<div class="skillCard">
  <div class="percent" style="--clr:yellow;--num:77;">
    <div class="dot"></div>
    <svg>
      <circle cx="70" cy="70" r="70"></circle>
      <circle cx="70" cy="70" r="70"></circle>
    </svg>
    <div class="number">
    <h2><i class="fa-brands fa-square-js"></i></h2>
    <p>JavaScript</p>
  </div>
</div>
</div>
<div class="skillCard">
  <div class="percent" style="--clr:red;--num:100;">
    <div class="dot"></div>
    <svg>
      <circle cx="70" cy="70" r="70"></circle>
      <circle cx="70" cy="70" r="70"></circle>
    </svg>
    <div class="number">
    <h2>Delphi</h2>
    <p>Delphi</p>
  </div>
</div>
</div>
<div class="skillCard">
  <div class="percent" style="--clr:purple;--num:90;">
    <div class="dot"></div>
    <svg>
      <circle cx="70" cy="70" r="70"></circle>
      <circle cx="70" cy="70" r="70"></circle>
    </svg>
    <div class="number">
    <h2><i class="fa-brands fa-bootstrap"></i></h2>
    <p>Bootstrap5</p>
  </div>
</div>
</div>
<div class="skillCard">
  <div class="percent" style="--clr:lightblue;--num:69;">
    <div class="dot"></div>
    <svg>
      <circle cx="70" cy="70" r="70"></circle>
      <circle cx="70" cy="70" r="70"></circle>
    </svg>
    <div class="number">
    <h2><i class="fa-brands fa-python"></i></h2>
    <p>Python</p>
  </div>
</div>
</div>
<div class="skillCard">
    <div class="percent" style="--clr:lightgreen;--num:95;">
      <div class="dot"></div>
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
      <h2><i class="fa-brands fa-vuejs"></i></h2>
      <p>VUE.JS</p>
    </div>
  </div>
</div>
<div class="skillCard">
    <div class="percent" style="--clr:red;--num:95;">
      <div class="dot"></div>
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
      <h2><i class="fa-solid fa-database"></i></h2>
      <p>MySQL</p>
    </div>
  </div>
</div>
<div class="skillCard">
    <div class="percent" style="--clr:lightgreen;--num:95;">
      <div class="dot"></div>
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
      <h2><i class="fa-brands fa-node-js"></i></h2>
      <p>Node.JS</p>
    </div>
  </div>
</div>
<div class="skillCard">
    <div class="percent" style="--clr:purple;--num:95;">
      <div class="dot"></div>
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
      <h2><i class="fa-brands fa-figma"></i></h2>
      <p>UI/UX Design</p>
    </div>
  </div>
</div>
<div class="skillCard">
    <div class="percent" style="--clr:lightgreen;--num:95;">
      <div class="dot"></div>
      <svg>
        <circle cx="70" cy="70" r="70"></circle>
        <circle cx="70" cy="70" r="70"></circle>
      </svg>
      <div class="number">
      <h2><i class="fa-brands fa-wordpress"></i></h2>
      <p>WordPress</p>
    </div>
  </div>
</div>
</div>
</section><br>
</template>

<script>
export default {
  name: 'ResumeComponent',
  data () {
    return {
      resume: [{
        institution: 'Mdingi J.S.S',
        level: 'Junior School',
        year: '2006 - 2008',
        reflection: 'Learned the basic behaviour of a human being and how to carry myself around other people basic form of creativity was implemented in my system.'
      },
      {
        institution: 'Masivuke Primary School',
        level: 'Primary School',
        year: '2009',
        reflection: 'Learned about the culture around the world basic logical thinking wa implemented into my system.'
      },
      {
        institution: 'Dominican Grimley School',
        level: 'Junior High',
        year: '2010 - 2016',
        reflection: 'Learned basic English through lip-reading advanced my logical thinking into more complex problems.'
      },
      {
        institution: 'Wynberg Boys High School',
        level: 'High School',
        year: '2017 - 2020',
        reflection: 'Mastered my public speaking skills and got introduced into more advanced subjects such as Information Technology'
      },
      {
        institution: 'Cilmor Cold Storage',
        level: 'Working Environment',
        year: '2021 - 2022',
        reflection: 'Mastered my computing literacy as a clerk exposed to the working environment'
      },
      {
        institution: 'Life Choices Coding Academy',
        level: 'College',
        year: '2022 - 2023',
        reflection: 'Advanced my computing and coding skills and acquired more coding languages'
      }
      ]
    }
  }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Mouse+Memoirs&family=Quicksand:wght@500&display=swap');

  #Education{
  background: #FDEEE3;
  color:  #08233B;
  font-family: 'Mouse Memoirs', sans-serif;
}

.row2{
  border:double #FA8072;
}

h2{
  color: #08233B;
}
h3{
  color: #08233B;
}
/* ===================================================Skills====================================================== */
.skills {
    display:flex;
    justify-content: center;
    align-items: center;
    min-height:100vh;
    background: lightgoldenrodyellow;

}
.cont {
    position: relative;
    display:flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 40px;

}
.container1{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-column-gap: 1em;
  margin-left: -2%;
  margin-right: -2%;
  padding-left: 50px;
  padding-right: 50px;
}
.cont .skillCard {
    position: relative;
    width: 220px;
    height: 250px;
    background: #08233B;
    display:flex;
    justify-content: center;
    align-items: center;
}
.cont .skillCard .percent {
    position: relative;
    width: 150px;
    height: 150px;

}
.cont .skillCard .percent svg{
    position: relative;
    width: 150px;
    height: 150px;
    transform:rotate(270deg)
}
.cont .skillCard .percent svg circle {
    width: 100%;
    height: 100%;
    fill: transparent;
    stroke-width: 2;
    stroke: #191919;
    transform: translate(5px,5px);
}
.cont .skillCard .percent svg circle:nth-child(2) {
    stroke:var(--clr);
    stroke-dasharray: 440;
    stroke-dashoffset: calc(440 - (440 * var(--num)) / 100);
    opacity: 0;
    animation: fadeIn 1s linear forwards;
    animation-delay: 2.5s;

}
.dot {
    position: absolute;
    inset: 5px;
    z-index: 10;
    transform: rotate(calc(3.6deg * var(--num)));
    animation: animateDot 2s linear forwards;
}
@keyframes animeDot {
    0% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(calc(33.6deg * var(--num)));
    }
}
.dot ::before{
    content: '';
    position:absolute;
    top: -5px;
    left: 50%;
    transform:translate(-50%);
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: var(--clr);
    box-shadow: 0 0 10px var(--clr), 0 0 30px var(--clr);
}
.number {
    position: absolute;
    inset: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    opacity: 0;
    animation: fadeIn 1s linear forwards;
    animation-delay: 2.5s;
}
@keyframes fadeIn {
    0%{
        opacity: 0;
    }
    100%{
        opacity: 1;
    }
}
.number h2{
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-weight: 700;
    font-size: 2.5em;

}
.number h2 span {
    font-weight: 300;
    color: white;
    font-size: 0.5em;
}
.number p {
    font-weight :300;
    font-size: 0.75em;
    line-height: 2px;
    margin-top: 5px;
    text-transform: uppercase;
    color:lightblue;
}
.picture{
  width: 25rem;
  height: 25rem;
}
</style>
