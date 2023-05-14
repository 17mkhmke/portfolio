<template>
  <section id="home">

    <div class="container">
  <div class="row">
    <div class="col-md-6">
      <div class="detail">
        <h1>Hi, I'm Mkhuseli <span>Mkeyiya</span></h1>
        <p> Intern Full-Stack Web Developer</p>
        <a href="https://drive.google.com/file/d/1xbvNcZRQ6X7WfcefJY5wwYmb-wv3IL_3/view?usp=sharing" target="_blank">Download CV</a>
      </div>
    </div>
    <div class="col-md-6">
      <img src="https://i.postimg.cc/g0hXpsz0/buithaituananh1902-a-man-is-sitting-coding-and-he-feels-very-ha-a19ce459-e898-417e-a25e-42da97e82c5d.png" alt="your-image-alt-text">
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

#home {
  height: 92vh;
  background-color: #FDEEE3;
  font-family: 'Mouse Memoirs', sans-serif;
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
h1{
  font-size: 80px;
  color: #08233B;
  padding-bottom: 5px;
  letter-spacing: 2px;
}
p{
  font-size: 40px;
  color: #08233B;
  padding-bottom: 10px;
}
.detail{
  margin-top: 200px;
}
img {
  margin-left: 30px;
  max-height: 92vh;
}

a {
  background-color: #08233B;
  padding: 15px;
  font-size: 25px;
  color: #FDEEE3;
  border-radius: 15px;
}
a:hover{
  color:#FA8072;
}

@media screen and (max-width: 991px) {
  h1 {
    font-size: 50px;
  }
  p {
    font-size: 30px;
  }
  .detail {
    margin-top: 100px;
  }
  img {
    margin-left: 0px;
    max-width: 100%;
  }
}

@media screen and (max-width: 767px) {
  h1 {
    font-size: 40px;
  }
  p {
    font-size: 20px;
  }
  .detail {
    margin-top: 50px;
  }
}
</style>
