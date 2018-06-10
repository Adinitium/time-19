<template>
  <div class="background">
    <basic-header></basic-header>
<h3>Log in</h3>

<h8>
  <input type="text" placeholder="Número Usp" id="nUsp">
</h8><br><br>
<h8>
  <input type="text" placeholder="Senha" id="senha">
</h8><br><br>

<b-button class="button" type="submit" variant="danger">Entrar</b-button>

<h2>Quem somos</h2>

<h8>
  Uma iniciativa que visa atuar e integrar três frentes.
  <ul>
    <li>(cor1) Assistência Organizacional</li>
    <li>(cor1) Sistema de Recompensas</li>
    <li>(cor2) Coleta de Dados Direcionada</li>
  </ul>
</h8>

<h4>
  Assistência Organizacional
</h4><br>

<h8>Pensando em você criamos uma robusta agenda que te permitirá organizar seu dia com fluidez e praticidade. Temos como lema maximizar o seu tempo, logo propiciamos um design limpo e funcional. Nos esforçamos para que todas as funções da agenda possam ser acessadas em no máximo 3 cliques. Claro, sem abrir mão de features importantes tais como o cruzamento de agendas, a fim de facilitar marcar reuniões, e um sistema de recomendações de eventos, personalizado para o seu perfil, para seus momentos de ócio.   </h8><br>

<h4>
  Sistema de Recompensas
</h4>

<h8>Não está contente com sua nova agenda, então que tal ainda poder ganhar várias recompensas e benefícios incríveis. Tendo sempre em mente as suas preferências quanto a sua privacidade, você ainda possui a possibilidade de ocupar aqueles minutinhos esperando o circular chegar para responder a questionários que não apenas te dão nossos famigerados Cristovãos como também nos dão uma noção melhor de quem você é, nos permitindo gerar sempre recomendações cada vez melhores para o seu dia a dia. Cristovaos esses que podem ser convertidos em prêmios extraordinários em nossa seção de recompensas. </h8><br>

<h4>
  Coleta de Dados Direcionada
</h4>

<h8>Como deixar tudo isso ainda melhor? Simples, ajude mais gente enquanto faz tudo isso. Simbioticamente, criamos uma poderosa plataforma de captação de dados. Responder a questionários criados especificamente para o seu perfil (novamente, sempre tendo em mente a sua pŕivacidade, não conseguimos expressar o suficiente o quanto isto é importante para nós), acaba gerando dados de alto valor, já que são direcionados a um público já bem definido. Além de tornar essa coleta um processo muito mais prático e totalmente remoto. Ou seja, facilitamos muito a vida de pesquisadores na hora de coletar dados. 
</h8>
<br>
<br><br><br>

<h8>Ao fim, criamos uma plataforma de croudsourcing de coleta de dados funcional e recompensadora aos usuários e prática aos pesquisadores que a utilizam. Temos como objetivo facilitar ao máximo a coleta gratuita (financiados pelas pesquisas privadas) de dados para pesquisadores públicos, e que todos os frutos provindos desses dados possam se manter públicos e de livre acesso. 
</h8><br><br>
<h8>Portanto, nossas únicas condições de uso a pesquisadores, além de, novamente, não infringir os termos de privacidade de cada usuário, é que pesquisadores públicos, obtendo esses dados gratuitamente, tornem, tanto os dados, quanto suas pesquisas de livre acesso. Quer manter seus dados e sua pesquisa privada, tudo bem, acesse a plataforma como uma instituição privada e ajude a bancar pesquisas públicas enquanto ainda obtêm acesso aos seus dados.</h8><br>
</div>
</template>

<script>
import BasicHeader from '../components/BasicHeader.vue'

export default {
  components: {
    BasicHeader
  }
}
</script>

<style>
.h1, .h2, .h3, .h4, .h5, .h6, .h7, .h8 {
  color: black;
}
</style>