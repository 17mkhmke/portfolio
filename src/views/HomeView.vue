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

.detail{
     width: 100%;
    padding: 100px 0px;
    background-color:lightyellow;

}
.detail {
    margin-right: 30%;
    margin-bottom: 50%;
}
.detail h1{
    font-size: 50px;
    color: black;
    margin-bottom: 20px;
}
span{
    color: gold;
}
.detail p{
    color:black;
    line-height: 22px;
    letter-spacing: 1px;

 }
 .detail a{
    background: black;
    padding: 10px 18px;
    text-decoration: none;
    font-weight: bold;
    color: gold;
    display: inline-block;
    margin: 30px 0;
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
