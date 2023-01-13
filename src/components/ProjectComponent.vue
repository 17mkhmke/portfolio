<template>
  <section id="Projects">
    <div class="position-relative d-flex align-items-center justify-content-center">
          <h2 class="display-2 text-uppercase text-black">My Projects</h2>
        </div>
    <div class="container-fluid" id="carousel">
      <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000" v-for="item3 in project1"
            :key="item3">
            <img :src="item3.image" alt="ProjectPic" class="img-fluid w-25 m-auto" loading="lazy">
            <h3 class="mt-3 text-black"> {{ item3.projectName }}</h3>
            <p class="text-black">{{ item3.description }}</p>
            <form :action="item3.gitHub" method="get" target="_blank"><button class="project-btn">GitHub</button></form><br>
              <a :href="item3.netlify"><button>Hosting</button></a>
          </div>
          <div class="carousel-item" data-bs-interval="10000" v-for="item3 in project" :key="item3">
            <img :src="item3.image" alt="projectPic" class="img-fluid w-25 m-auto" loading="lazy">
            <h3 class="mt-3 text-black">{{ item3.projectName }}</h3>
            <p class="text-black">{{ item3.description }}</p>
            <form :action="item3.gitHub" method="get" target="_blank"><button class="project-btn">GitHub</button></form><br>
              <a :href="item3.netlify"><button>Hosting</button></a>
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
        image: 'https://i.postimg.cc/zXzQc4WS/project-Game.png',
        projectName: 'TicTacToe',
        description: 'This is a tic tac toe game built with HTML5, CSS3 and JavaScript',
        gitHub: 'https://github.com/17mkhmke/TicTacToe.git',
        netlify: 'https://mkhuselitictac-game.netlify.app'
      },
      {
        image: 'https://i.postimg.cc/d05BWMLk/Project-Rest2-1.jpg',
        projectName: 'e-Commerce JS',
        description: 'This is a e-Commerce website built with HTML5, CSS3, Bootstrap5 and JavaScript',
        gitHub: 'https://github.com/17mkhmke/EOM-js',
        netlify: 'https://astonishing-blini-69f53e.netlify.app/'
      },
      {
        image: 'https://i.postimg.cc/qBWPr1p0/Me.jpg',
        projectName: 'Portfolio',
        description: 'This is a personal portfolio consist of HTML5, Bootstrap5 and CSS3',
        gitHub: 'https://github.com/17mkhmke/projectportfolio.git',
        netlify: 'https://mkhuselimkeyiya-portfolio-project.netlify.app/'
      },
      {
        image: 'https://i.postimg.cc/ZnRjX1Np/Potential-profile-fococlipping-standard.png',
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
      }
      ]
    }
  }
}
</script>
