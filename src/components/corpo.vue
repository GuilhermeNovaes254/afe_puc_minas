
<template>
    <div id="area-conteudo">
        <div class="conteudo">
            <h2>Sobre</h2>
            <p>Profissional graduado em Geofísica pela USP, pós-graduação em inteligência artificial pela PUC, com mais de 6 anos de experiência na área de Tecnologia da Informação, atuando em start-ups no ramo de Internet das Coisas e de instrumentos de medida. Expertise em gerenciamento de dispositivos, IOT, suporte técnico, desenvolvimento de novas tecnologias. Conhecimentos em desenvolvimento e manutenção de sistemas, desenvolvimento web, banco de dados. Sólido conhecimento em elaboração de relatórios gerenciais e acompanhamento de indicadores de desempenho. Profissional altamente capacitado para trabalhar em equipe, dinâmico, com facilidade de aprendizado e de bom relacionamento interpessoal, dedicado às funções e focado em resultados. Organizado, responsável e flexível.</p>
        </div>
        <div class="conteudo">
            <h2>Pós graduação</h2>
            <ul>
                <li v-for="(pos, index) in posG" :key="index">
                    {{pos.value}}
                </li>
            </ul>
        </div>
        <div class="conteudo">
            <h2>Palavras Chave</h2>
            <p>Palavras-chave: TI, dispositivos, IOT, suporte técnico, desenvolvimento web, desenvolvimento e manutenção, banco de dados, MongoDB, SQL, HTML, Python, Javascript, relatórios gerenciais, indicadores, inteligência artificial, CRM, machine learning, NPL.</p>
        </div>
  </div>
</template>

<script >

    export default {
    name: 'CorpoItem',
    data() {
        return {
        posG: [
            { value: 'Arquitetura de Soluções (em andamento)' },
            { value: 'Inteligência Artificial' },
        ]}}
    }

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h2{
        color:black
    }
    .conteudo{
        background-color:whitesmoke
    }
    #area-conteudo{
        text-align: center;
        display:flex;
        flex-direction: column;
        margin: 0;
    }
    p,li{
        text-align: justify;
    }
</style>