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
*,
*::after,
*::before {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
#app {
  font-family: raleway;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}
/* ========================================================================NAVBAR SECTION================================================================================ */
@import url('https://fonts.googleapis.com/css2?family=Mouse+Memoirs&family=Quicksand:wght@500&display=swap');

.navbar{
  background-color:  #08233B;
  font-family: 'Mouse Memoirs', sans-serif;
  font-size: 25px;
  letter-spacing: 1px;
}
.nav-link{
  color: #FDEEE3;
    margin-right: 10px;
    margin-left: 10px;
  text-transform: uppercase;
}
.nav-link{
    float:left;
}
.nav-link:hover{
    color:#FA8072;
}
.navbar-toggler{
  color: #FA8072;
  background: #FDEEE3;
}

.navbar-nav{
  margin-right: 50px;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
}
nav a.router-link-exact-active {
  color:#FA8072;
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
    background-color:  #08233B;
}
footer p{
    color: #FDEEE3;
}
.footer .social {
    text-align: center;
    padding-bottom: 25px;
    color: #FDEEE3;

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
