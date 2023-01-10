
import ContactComponent from '@/components/ContactComponent.vue';

<template>
  <ContactComponent/>
</template>
<script>
import ContactComponent from '@/components/ContactComponent.vue'
export default {
  components: {
    ContactComponent
  }
}
</script>
<style>
.head{
    background-color: black;
    background-size: 100% 100%;
}
.card-bodyContact{
    background-color: lightgoldenrodyellow;
}
.btn {
background: black;
padding: 10px 18px;
text-decoration: none;
font-weight: bold;
color: gold;
display: inline-block;
margin: 30px 0;
border-radius: 5px;
}
.btn {
    background-color:black;
    border: 2px solid black;
    cursor: pointer;
}
.btn:hover{
    color: gold;
    background: black;
    transform: scale(1.1);
    border: 2px solid black;
}
input {
    box-shadow: goldenrod;

}
</style>
