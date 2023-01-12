<template>
  <HeaderComponent/>
  <router-view/>
  <FooterComponent/>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
export default {
  components: {
    HeaderComponent,
    FooterComponent
  }

}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=PT+Serif:ital@1&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;1,100&display=swap');
#app {
  font-family: raleway;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}
/* ========================================================================NAVBAR SECTION================================================================================ */
.nav-link{
  color: white;
    margin-right: 10px;
    margin-left: 10px;
  text-transform: uppercase;
}
.nav-link{
    float:left;
}
.nav-link:hover{
    color: gold;
}
.navbar-toggler{
  color: gold;
  background: goldenrod;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
}
nav a:hover{
  color: gold;
}
nav a.router-link-exact-active {
  color: gold;
}
.logo {
  width: 5rem;
}
/* =============================================================FOOTER SECTION======================================================================================= */
footer {
    font-weight: 400;
    background-color: gold;

}
.footer{
    padding: 40px 0;
    background-color: goldenrod;
}
footer p{
    color: black;
}
.footer .social {
    text-align: center;
    padding-bottom: 25px;
    color: #4b4c4d;

}
.footer .social a {
    font-size: 24px;
    color: inherit;
    border: 1px solid black;
    width: 40px;
    height: 40px;
    line-height: 38px;
    display: inline-block;
    text-align: center;
    border-radius: 50%;
    margin: 0 8px;
    opacity:0.75 ;

}
.footer .social a:hover{
    opacity: 0.9;
}

</style>
