<template>
  <Cabecalho/>
  <Corpo :key="posG"/>
</template>

<script>
  import Corpo from './components/corpo.vue'
  import Cabecalho from './components/cabecalho.vue'

  const posG = ['Arquitetura de Soluções (em andamento)','Inteligência Artificial']

  export default {
    name: 'App',
    components: {
      Corpo,
      Cabecalho
    },
    data () {
      return {
        posG
      }
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
