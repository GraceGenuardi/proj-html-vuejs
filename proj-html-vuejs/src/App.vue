<template>
  <Header />
  <Sales />
  <Courses/>
  <Main/>
  <Popular/>
  <Start/>
  
  
  
</template>

<script>
  import Header from './components/Header.vue';
  import Sales from './components/Sales.vue';
  import Courses from './components/Courses.vue';
  import Main from './components/Main.vue';
  import Popular from './components/Popular.vue';
  import Start from './components/Start.vue';
  
  export default {
    components: {
      Header,
      Sales,
      Courses,
      Main,
      Popular,
      Start
    }
  }
</script>

<style lang="scss" >
@use './style/general.scss';
</style>
