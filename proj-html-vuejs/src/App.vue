<template>
  <Header />
  <Sales />
  
  
</template>

<script>
  import Header from './components/Header.vue';
  import Sales from './components/Sales.vue';
  
  export default {
    components: {
      Header,
      Sales
    }
  }
</script>

<style lang="scss" >
@use './style/general.scss';
</style>
