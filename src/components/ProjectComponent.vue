<template>
  <section id="Projects">
    <div class="position-relative d-flex align-items-center justify-content-center">
          <h1 class="display-2 text-uppercase mt-5">Projects</h1>
        </div>
          <div class="container-fluid" id="carousel">
      <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000" v-for="item3 in project1"
            :key="item3">
            <img :src="item3.image" alt="ProjectPic" class="pic" loading="lazy">
            <h3 class="mt-3"> {{ item3.projectName }}</h3>
            <p class="text">{{ item3.description }}</p>
            <form :action="item3.gitHub" method="get" target="_blank"><button class="project-btn">GitHub</button></form>
              <a :href="item3.netlify"><button class="project-btn">Hosting</button></a>
          </div>
          <div class="carousel-item" data-bs-interval="10000" v-for="item3 in project" :key="item3">
            <img :src="item3.image" alt="projectPic" class="pic" loading="lazy">
            <h3 class="mt-3">{{ item3.projectName }}</h3>
            <p class="text">{{ item3.description }}</p>
            <form :action="item3.gitHub" method="get" target="_blank"><button class="project-btn">GitHub</button></form>
              <a :href="item3.netlify"><button class="project-btn">Hosting</button></a>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectComponent',
  data () {
    return {
      project1: [{
        image: 'https://i.postimg.cc/gcX3mw0j/project-Calcu.jpg',
        projectName: 'Calculator',
        description: ' A fully functional calculator made with HTML5, CSS3 and for the functionality javascript was used',
        gitHub: 'https://github.com/17mkhmke/Royalty-Calculator.git',
        netlify: 'https://chic-caramel-bb0212.netlify.app/'
      }],
      project: [{
        image: 'https://i.postimg.cc/ydw8yXsk/Screenshot-2023-05-16-125119.png',
        projectName: 'Full-stack e-commerce',
        description: 'This is a e-commerce website which I went all out in it consists VueJS, NodeJS and mySQL',
        gitHub: 'https://github.com/17mkhmke/stratweni_mobile_foods.git',
        netlify: 'https://estratwenimobilefoods-94c46.web.app/'
      },
      {
        image: 'https://i.postimg.cc/yYrbJLBz/Screenshot-2023-05-16-103935.png',
        projectName: 'e-Commerce JS',
        description: 'This is a e-Commerce website built with HTML5, CSS3, Bootstrap5 and JavaScript',
        gitHub: 'https://github.com/17mkhmke/EOMP_Ecommerce.git',
        netlify: 'https://e-commerce-by-mkhuseli-mkeyiya.netlify.app/'
      },
      {
        image: 'https://i.postimg.cc/qBWPr1p0/Me.jpg',
        projectName: 'Portfolio',
        description: 'This is a personal portfolio consist of HTML5, Bootstrap5 and CSS3',
        gitHub: 'https://github.com/17mkhmke/projectportfolio.git',
        netlify: 'https://mkhuselimkeyiya-portfolio-project.netlify.app/'
      },
      {
        image: 'https://i.postimg.cc/sfGQ4gGL/Final-Logo2-1.png',
        projectName: 'Portfolio VUE',
        description: 'This is a personal portfolio with VUE JS',
        gitHub: 'https://github.com/17mkhmke/vue_portfolio.git',
        netlify: 'https://vueportfolio-40dbf.web.app'
      },
      {
        image: 'https://i.postimg.cc/Jzx6ZFzY/Lavish-Logo-Turquoise-Gold-an-Blue-Gradient.webp',
        projectName: 'e-Commerce VUE',
        description: 'This is a e-Commerce website with VUE JS',
        gitHub: 'https://github.com/17mkhmke/vue_Exercise3.git',
        netlify: 'https://e-commercevue.web.app'
      },
      {
        image: 'https://i.postimg.cc/v84rPgmL/Screenshot-2023-05-16-120656.png',
        projectName: 'To-Do List',
        description: 'It is a to do list  app which consist of HTML, CSS, JavaScript and Bootstrap',
        gitHub: 'https://github.com/17mkhmke/To-Do-List.git',
        netlify: 'https://super-profiterole-c5d115.netlify.app'
      },
      {
        image: 'https://i.postimg.cc/jdkgqZ9N/Investments.png',
        projectName: 'Budget App',
        description: 'it is a budget app made with VueJS that calculates your income and expenses',
        gitHub: 'https://github.com/17mkhmke/budgetprototype',
        netlify: 'https://budget-prototype-f7b85.web.app/'
      }
      ]
    }
  }
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Mouse+Memoirs&family=Quicksand:wght@500&display=swap');

#Projects{
  background-color: #FDEEE3;
    font-family: 'Mouse Memoirs', sans-serif;
    color: #08233B;
}
h1{
  font-size: 80px;
}

.pic{
  width: 300px;
  height: 300px;
  border-radius: 50px;
}
.text{
  font-size: larger;
}

.project-btn{
  background:  #08233B;
text-decoration: none;
color: #FDEEE3;
border-radius: 5px;
margin-bottom: 10px;
padding: 5px;
}
</style>
