<template>
  <div class="bbb">
    <h1 class="display-2 text-uppercase pt-5">Testimonials</h1>
    <div class="wrapper">
      <a href="#" class="box" v-for="(card, index) in cards" :key="index">
        <div class="single-box">
          <div class="box-content">
            <div class="sides side-1" :style="'background-image: url(' + card.image + ');'"></div>
            <div class="sides side-2">
              <div class="content">
                <h2 class="fs-3">{{ card.name }}</h2>
                <p class="p-3 fs-5">{{ card.description }}</p>
              </div>
            </div>
          </div>
        </div>
      </a>
    </div>
  </div>
</template>
<script>
/* eslint-disable */
export default{
  data() {
    return {
      cards: [
        {
          name: 'John-Bruce Noad',
          image: 'https://i.postimg.cc/W4bPMNyv/DSC-3568.jpg',
          description: 'Mkhuseli has a great sense of humour, but is also serious and hardworking when it comes to his work. He has the ability to focus deeply on whatever tasks he finds before him. All in all, he is a great person to be around'
        },
        {
          name: 'Gift Mahlangu',
          image: 'https://i.postimg.cc/13yyjNp7/nkazana.jpg',
          description: 'He is a amazing person with a great sense of humor, a passion for creativity & is always hungry for greatness,never afraid to take risk & is willing to give a person a hand when needed. He is absolutely amazing.'
        },
        {
          name: 'Joel Mukanya',
          image: 'https://i.postimg.cc/9Xn3dzKr/Joel-Mukanya.jpg',
          description: 'Mkhuseli is a very creative, well-behaved student, he enjoys working with his classmates and does well working on his project. He has learned many new tricks on web development and bootstrap 5. I am quite happy with the effort he puts into his work. I recommend him as a Developer.'
        },
        {
          name: 'Candice Amon',
          image: 'https://i.postimg.cc/g0hqcdRP/Candice.jpg',
          description: 'Comes across very firm and very focused. Does not allow his circumstances to hold him back. He strives to always give his best and be the best. His hardworking and goal driven and always willing to do extra learning to master any task presented with.'
        },
        {
          name: 'Buhle Qampi',
          image: 'https://i.postimg.cc/V6MFPdfL/image.jpg',
          description: 'His code is presentable and coherent. His coding skills are improving each and everyday. He has a bright future ahead'
        },
        {
          name: 'Timothy Jennike',
          image: 'https://i.postimg.cc/MHt4SpSN/IMG-3573.jpg',
          description: "Mkhuseli is one of the most hardworking people I know and he can accomplish anything he puts his mind to. He also isn't afraid to ask for help when he doesn't understand something, which makes him perfect for the work environment"
        }
      ]
    }
  }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Mouse+Memoirs&family=Quicksand:wght@500&display=swap');
* {
  margin: 0;
  padding: 0;
}

.bbb {
  background-color: #fdeee3;
  font-family: 'Mouse Memoirs', sans-serif;
  color: #08233B;
}

.wrapper {
  background-color: #fdeee3;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  font-family: 'Mouse Memoirs', sans-serif;
}

.box {
  margin: 50px;
  width: 300px;
  height: 300px;
  perspective: 1200px;
}

.single-box {
  width: 300px;
  height: 300px;
  perspective: 1200px;
}

.box-content {
  width: 100%;
  height: 100%;
  position: relative;
  transform-style: preserve-3d;
  transform: translateZ(-150px);
  transition: all 1s;
}

.sides {
  position: absolute;
  width: 300px;
  height: 300px;
  text-align: center;
}

.side-1 {
  transform: rotateY(0deg) translateZ(150px);
  z-index: 2;
  background-size: cover;
  background-position: center center;
}

.side-2 {
  color: #fdeee3;
  background-color: #08233B;
  transform: rotateY(90deg) translateZ(150px);
}

.box:hover .box-content {
  transform: translateZ(-150px) rotateY(-90deg);
}

.content {
  display: flex;
  justify-content: center;
  flex-direction: column;
  height: 100%;
}

.content h2 {
  font-family: 'Mouse Memoirs', sans-serif;
  color: #fdeee3;
  font-size: 25px;
}

.content p {
  font-size: 15px;
  line-height: 25px;
}

.socials {
  margin-top: 30px;
}

.socials i {
  margin: 0 15px;
}

@media (max-width: 768px) {
  .box {
    width: calc(50% - 40px);
    margin: 20px;
  }
}
@media (max-width: 576px) {
  .box {
    width: calc(100% - 40px);
    margin: 20px;
  }
}

@media (max-width: 375px) {
  .box {
    width: calc(100% - 20px);
    margin: 10px;
  }
}
</style>

