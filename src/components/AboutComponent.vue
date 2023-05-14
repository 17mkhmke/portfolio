<template>
 <section class="container-fluid py-5" id="AboutMe">
      <div class="container">
        <div class="position-relative d-flex align-items-center justify-content-center">
          <h1 class="display-2 text-uppercase">About</h1>
        </div>
        <div class="row align-items-center">
          <div class="col-lg-5 pb-lg-0">
            <img class="img-fluid rounded" src="https://i.postimg.cc/qBWPr1p0/Me.jpg" alt="About_me" loading="lazy">
          </div>
          <div class="col-lg-7">
            <p class="text about-text">I was born in KwaZulu-Natal, I moved to Eastern Cape in a beautiful village called
              Lusikisiki in 2006 and by 2009 I moved to
              Cape Town in a township called Philippi where I was searching for greener pastures in education and that
              is where I stumbled into <span>coding</span>.<br><br>
              I am a young professional who is striving towards a successful career in software and web
              development. A career which is based on strong quality coding. I am able to
              adapt proficiently in pressuring positions
              and produce an expected work ethic. I can provide clean code which lead to responsive
              website. A responsive website makes your website accessible to all users, regardless of their devices</p>
            <div class="row mb-3 info-text">
              <div class="col-sm-6 py-2">
                <h6><b>Date of Birth: </b><span class="text-secondary">21-02-2001</span></h6>
              </div>
            <div class="row mb-3">
              <div class="col-sm-6 py-2">
                <h6><b>Hobbies:</b> <span class="text-secondary">Boardgames, upskilling and Gym</span></h6>
              </div>
            <div class="row mb-3">
              <div class="col-sm-6 py-2">
                <h6><b>Sports: </b><span class="text-secondary">Waterpolo, Soccer</span></h6>
              </div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>
</template>
<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Mouse+Memoirs&family=Quicksand:wght@500&display=swap');
  #AboutMe{
  background: #FDEEE3;
  color:  #08233B;
  font-family: 'Mouse Memoirs', sans-serif;
}
h1{
  font-family: 'Mouse Memoirs', sans-serif;
  font-size: 80px;
  color:  #08233B;
}
p{
  font-size: 25px;
  margin: auto;
}
h6{
  font-size: larger;
}
  .about-text {
    text-align: left;
  }
.info-text{
  text-align: left;
  }
img{
  width: 430px;
  margin-bottom: 50px;
}
</style>
