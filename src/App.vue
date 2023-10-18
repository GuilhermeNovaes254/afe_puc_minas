<template>
  <Cabecalho/>
  <Corpo/>
</template>

<script>
  import Corpo from './components/corpo.vue'
  import Cabecalho from './components/cabecalho.vue'

  export default {
    name: 'App',
    components: {
      Corpo,
      Cabecalho
    }
  }
</script>


<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin: 0px; 
  }
</style>
