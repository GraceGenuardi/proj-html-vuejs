<template>
  <Header />
  <Sales />
  <Courses/>
  
  
</template>

<script>
  import Header from './components/Header.vue';
  import Sales from './components/Sales.vue';
  import Courses from './components/Courses.vue';
  
  export default {
    components: {
      Header,
      Sales,
      Courses,
    }
  }
</script>

<style lang="scss" >
@use './style/general.scss';
</style>
