<template lang="">
  <ProjectComponent/>
</template>
<script>
import ProjectComponent from '@/components/ProjectComponent.vue'
export default {
  components: {
    ProjectComponent
  }
}
</script>
<style>
#Projects{
    background-color: lightyellow;
    width: 100%;
    padding: 100px 0px;
    background-size: 100% 100%;
}
.title h2{
    color: black;
    font-size: 75px;
    width:1130px;
    margin: 30px auto;
    text-align: center;
}
.pic{
  width: 25rem;
  height: 25rem;
}
</style>
