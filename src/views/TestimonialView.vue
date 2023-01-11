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
.container{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-column-gap: 1em;
}
.card{
  width: 26rem;
}
</style>
