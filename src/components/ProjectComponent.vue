<template>
 <section class="container-fluid py5" id="Projects">
  <div class="position-relative d-flex align-items-center justify-content-center">
          <h2 class="display-2 text-uppercase text-black">My Projects</h2>
        </div>
        <div  id="carouselExampleIndicators" class="carousel slide h-50 w-100" data-bs-ride="false">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
              aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
              aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
              aria-label="Slide 3"></button>
          </div>
          <div class="carousel-inner w-100 h-100 text-center">
            <div v-for="item in project" :key="item" class="carousel-item active">
              <img :src="item.image" alt="projectPic">
              <h3><br>{{ item.projectName }}</h3>
              <p>{{ item.description }}</p>
              <form :action="item.gitHub" method="get" target="_blank"><button class="project-btn">GitHub</button></form>
              <a :href="item.netlify"><button>Netlify</button></a>
          </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon bg-dark" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
            data-bs-slide="next">
            <span class="carousel-control-next-icon bg-dark" aria-hidden="true"></span>
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
      project: [{
        image: 'https://i.postimg.cc/gcX3mw0j/project-Calcu.jpg',
        projectName: 'Calculator',
        description: ' A fully functional calculator made with HTML5, CSS3 and for the functionality javascript was used',
        gitHub: 'https://github.com/17mkhmke/Royalty-Calculator.git',
        netlify: 'https://chic-caramel-bb0212.netlify.app/'
      },
      {
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
      }
      ]
    }
  }
}
</script>
