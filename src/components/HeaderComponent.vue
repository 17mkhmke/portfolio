<template>
  <nav class="navbar navbar-expand-lg bg-black sticky-top">
      <div class="container-fluid">
        <img src="https://i.postimg.cc/sfGQ4gGL/Final-Logo2-1.png" class="logo" alt="logo" loading="lazy">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                      <router-link to="/" class="nav-link active text-white">Home</router-link>
                  </li>
                  <li class="nav-item">
                      <router-link to="/about" class="nav-link text-white">About-me</router-link>
                  </li>
                  <li class="nav-item">
                      <router-link to="/projects" class="nav-link text-white">Projects</router-link>
                  </li>
                  <li class="nav-item">
                      <router-link to="/resume" class="nav-link text-white">Resume</router-link>
                  </li>
                  <li class="nav-item">
                      <router-link to="/testimonials" class="nav-link text-white">Testimonials</router-link>
                  </li>
                  <li class="nav-item">
                      <router-link to="/contact" class="nav-link text-white">Contact</router-link>
                  </li>
              </ul>
          </div>
      </div>
  </nav>
</template>

<script>
export default {
}
</script>
