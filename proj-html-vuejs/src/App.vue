<template>
  <Header />
  <Sales />
  <Courses/>
  <Main/>
  <Popular/>
  
  
  
</template>

<script>
  import Header from './components/Header.vue';
  import Sales from './components/Sales.vue';
  import Courses from './components/Courses.vue';
  import Main from './components/Main.vue';
  import Popular from './components/Popular.vue';
  
  export default {
    components: {
      Header,
      Sales,
      Courses,
      Main,
      Popular,
    }
  }
</script>

<style lang="scss" >
@use './style/general.scss';
</style>
