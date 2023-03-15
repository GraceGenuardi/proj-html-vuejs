<template>
  <Header />
  <Sales />
  <Courses/>
  <Main/>
  <Popular/>
  <Start/>
  <Future/>
  
  
  
</template>

<script>
  import Header from './components/Header.vue';
  import Sales from './components/Sales.vue';
  import Courses from './components/Courses.vue';
  import Main from './components/Main.vue';
  import Popular from './components/Popular.vue';
  import Start from './components/Start.vue';
  import Future from './components/Future.vue';
  
  export default {
    components: {
      Header,
      Sales,
      Courses,
      Main,
      Popular,
      Start,
      Future
    }
  }
</script>

<style lang="scss" >
@use './style/general.scss';
</style>
