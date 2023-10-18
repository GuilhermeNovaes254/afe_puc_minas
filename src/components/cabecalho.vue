
<template>
  <BarraLinks/>
  <div class="hello">
    <img alt="Logo Linkedin" src="../assets/linkedin.png" id="linkedin">
    <div id="informacoes">
        <h3>Guilherme Novaes</h3>
        <div>IT Analyst | Santander Brasil | F1RST | Pós-graduando em Arquitetura de Soluções | Pós-graduação em Inteligência Artificial| Datalover| Python</div>
    </div>
  </div>
</template>

<script>

import BarraLinks from './barra_links.vue'

export default {
  name: 'CabecalhoItem',
  components: {
    BarraLinks    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello{
      background-color: rgb(3, 8, 132);
      margin: 0;
      display: flex;
      flex-direction: row;
      
  }
  #informacoes{
      color:white;
  }
  #linkedin{
      width: 100px;
      height:100px;
      aspect-ratio: 1;
      
  }

  h3{margin:0}
</style>