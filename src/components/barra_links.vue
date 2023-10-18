
<template>
  <div class="links">
    <a href="https://www.linkedin.com/in/guilherme-novaes/">Perfil<div id="thediv" /> </a>
    <a href="https://www.linkedin.com/company/grupo-santander-brasil/mycompany/verification/">Empregador<div id="thediv" /> </a>
    <a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/">Referência Estudo<div id="thediv" />Formação</a>
  </div>
</template>

<script>


export default {
  name: 'BarraItens'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.links {
    background-color: rgb(3, 8, 132);
    display: flex;
    flex-direction: row;
    align-content: center;
    justify-content: space-around;
}
a{
    color:white;
}
</style>