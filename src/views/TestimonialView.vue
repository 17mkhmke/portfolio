<template lang="">
  <TestimonialComponent/>
</template>

<script>
import TestimonialComponent from '@/components/TestimonialComponent.vue'
export default {
  components: {
    TestimonialComponent
  }
}
</script>
<style>
.card-body{
    background: goldenrod;
}
.card-body p {
    font-weight: 700;
    color: black;
}
.container1{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-column-gap: 1em;
  margin-left: -2%;
  margin-right: -2%;
}
.card{
  width: 26rem;
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
