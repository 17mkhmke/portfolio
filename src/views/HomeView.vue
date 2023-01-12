<template>
    <HomeComponent/>
</template>

<script>
// @ is an alias to /src
import HomeComponent from '@/components/HomeComponent.vue'
export default {
  components: {
    HomeComponent
  }
}
</script>
<style>
#home {
  background: 100% lightgoldenrodyellow;
}
.detail{
     width: 100%;
    padding: 100px 0px;;
}
/* .detail {
    margin-left: 8%;
    margin-top: 30%;
} */
.detail h1{
    font-size: 50px;
    color: black;
    margin-bottom: 20px;
}
/* .detail a {
  margin-right: 60%;
} */
span{
    color: gold;
}
.detail p{
    color:black;
    line-height: 22px;
    letter-spacing: 1px;
 }
 .detail p{
  margin-right: 50%;
  margin-top: 18%;
 }
 .detail h1{
  margin-right: 50%;
  margin-bottom: -10%;
 }
 .detail a{
    background: black;
    padding: 10px 18px;
    text-decoration: none;
    font-weight: bold;
    color: gold;
    display: inline-block;
    margin-right: 60%;
    margin-bottom: 18%;
    border-radius: 5px;
}
.images {
    width: 45%;
    height: 60%;
    position: absolute;
    bottom:0;
    right: 100px;
}
.images img {
    height: 100%;
    position: absolute;
    left: 50%;
    bottom: 0px;
    transform: translateX(-50%);
    transition: bottom is, left is;
}
.images:hover .kreeD-Shape{
    bottom: 40px;
}
.images:hover .me{
    left: 45%;
}
a:hover{
    transform: scale(1.2);
}
</style>
