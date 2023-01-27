<template>
   <section id="Testimonial">
    <div class="position-relative d-flex align-items-center justify-content-center">
        <h2 class="display-2 text-uppercase text-black">Testimonials</h2>
      </div>
      <div class="container1">
        <div v-for="item2 in testimonial" :key="item2" class="card-col">
        <div class="card row justify-content-center">
          <div class="card border-warning col-12 col-sm-2 col-md-3 m-1">
            <img :src="item2.image" class="card-img-top picture" alt="testimonialPics">
            <div class="card-body">
              <h5 class="card-title"><b>{{ item2.spokePerson }}</b></h5>
              <p class="card-text"><i><em>{{ item2.word }}</em></i></p>
            </div>
          </div>
        </div>
      </div>
      </div>
   </section>
</template>

<script>
export default {
  name: 'TestimonialComponent',
  data () {
    return {
      testimonial: [{
        image: 'https://i.postimg.cc/9Xn3dzKr/Joel-Mukanya.jpg',
        spokePerson: 'Joel Mukanya',
        word: 'Mkhuseli is a very creative, well-behaved student, he enjoys working with his classmates and does well working on his project. He has learned many new tricks on web development and bootstrap 5. I am quite happy with the effort he puts into his work. I recommend him as a Developer.'
      },
      {
        image: 'https://i.postimg.cc/Vvs5tgGr/image.jpg',
        spokePerson: 'Athenkosi Freddie',
        word: ' is a amazing person with a great sense of humor, a passion for creativity & is always hungry for greatness,never afraid to take risk & is willing to give a person a hand when needed. He is absolutely amazing.'
      },
      {
        image: 'https://i.postimg.cc/W4bPMNyv/DSC-3568.jpg',
        spokePerson: 'John-Bruce Noad',
        word: 'Mkhuseli has a great sense of humour, but is also serious and hardworking when it comes to his work. He has the ability to focus deeply on whatever tasks he finds before him. All in all, he is a great person to be around'
      },
      {
        image: 'https://i.postimg.cc/g0hqcdRP/Candice.jpg',
        spokePerson: 'Candice Amon',
        word: 'Comes across very firm and very focused. Does not allow his circumstances to hold him back. He strives to always give his best and be the best. His hardworking and goal driven and always willing to do extra learning to master any task presented with.'
      },
      {
        image: 'https://i.postimg.cc/V6MFPdfL/image.jpg',
        spokePerson: 'Buhle Qampi',
        word: "Mkhuseli's code is presentable and coherent. His coding skills are improving each and everyday. He has a bright future ahead"
      },
      {
        image: 'https://i.postimg.cc/MHt4SpSN/IMG-3573.jpg',
        spokePerson: 'Timothy Jennike',
        word: "Mkhuseli is one of the most hardworking people I know and he can accomplish anything he puts his mind to. He also isn't afraid to ask for help when he doesn't understand something, which makes him perfect for the work environment"
      }
      ]
    }
  }
}
</script>
<style scoped>
.container1{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-column-gap: 1em;
  margin-left: -2%;
  margin-right: -2%;
  overflow-x: hidden;
}
.card-body{
    background: goldenrod;
}
.card-body p {
    font-weight: 700;
    color: black;
}
.card{
  width: 26rem;
  height: 38rem;
  margin-bottom: 8rem;
}
#Testimonial{
  background: lightgoldenrodyellow;
}
/* ================================================Responsiveness============================================================== */
@media screen and (max-width: 900px) {
  .container1{
    display: grid;
    grid-template-columns: 1fr 1fr;
  }

}
@media screen and (max-width: 800px) {
  .container1{
    display: grid;
    grid-template-columns: 1fr;
  }

}
</style>
