<template>
  <header>
    <nav class="navbar navbar-expand-lg bg-black w-100 top-0 position-fixed bg-warning ">
      <div class="container-fluid">
        <img src="https://i.postimg.cc/sfGQ4gGL/Final-Logo2-1.png" class="logo" alt="logo" loading="lazy">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav m-auto bg-black bg-md-none">
            <li class="nav-item">
              <a class="nav-link" href="#Home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#AboutMe">About-Me</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Contact">
                Contact
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Testimonial">Testimonials</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Education">Education</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#Projects">Projects</a>
            </li>
          </ul>

        </div>
      </div>
    </nav>
  </header>
</template>
<style>
.nav-link{
    color: white;
    margin-right: 10px;
    margin-left: 10px;
    text-transform: uppercase;

}
.navbar-toggler {
    background-color: goldenrod;
}
.nav-link{
    float:left;
}
.nav-link:hover{
    /* transform: scale(1.2) translateX(42px); */
    scale: 1.2;
    transform: translateX(10px);

}
.nav-link:hover{
    color: gold;
}
.logo{
    width: 5rem;
}
</style>

<script>
export default {

}
</script>
