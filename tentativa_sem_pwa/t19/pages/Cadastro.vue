<template>
<div class="background">
<basic-header></basic-header>

<h1>Cadastro</h1>

<h8>
  <input type="text" placeholder="Número Usp" id="nUsp">
</h8><br><br>
<h8>
  <input type="text" placeholder="E-mail" id="email">
</h8><br><br>
<h8>
  <input type="text" placeholder="Senha" id="senha">
</h8><br><br>
<h8>
  <input type="text" placeholder="Confirmar Senha" id="conSenha">
</h8><br><br>

<h2>Formulário de Permissões</h2>

<h8>
  Tendo em mente a natureza de captação de dados presente neste aplicativo e a nossa profunda preocupação com a sua privacidade, antes de prosseguirmos com sua inscrição, é necessário o preenchimento do formulário a seguir:
</h8>

<br>
<br>

<h8>
  Informações liberadas para pesquisa serão desvinculadas de quaisquer informações pessoais ou rastreáveis (e-mail, nome, número de celular, etc).
</h8>

<br>
<br>

<h8>
  Tenha em mente que nosso sistema trabalha com pesquisas direcionadas, logo limitar a privacidade de seus dados também limita a quantidade de pesquisas direcionadas a você e consequentemente dificulta um pouco a sua coleta de Cristovãos. Quanto mais estrita for a sua privacidade, menos pesquisas estarão disponíveis. (Quanto você valoriza a sua privacidade)
</h8>

<br>
<br>


<h8>
  Suas cláusulas de privacidade podem ser modificadas posteriormente a qualquer momento na secão de configurações.
</h8>

<br>
<br>

<form action="">
<input type="radio" name="vehicle" value="Bike">Concordo em liberar questionários respondidos a instituições privadas e públicas sem condições de liberação dos dados. As pesquisas públicas concluidas e os dados por ela utilizados devem ser de livre acesso. <br><br>
<input type="radio" name="vehicle" value="Car">Concordo em liberar questionários respondidos a instituições públicas e privadas desde que os dados coletados estejam disponíveis a todos. As pesquisas públicas concluidas e os dados por ela utilizados devem ser de livre acesso.<br><br>
<input type="radio" name="vehicle" value="Car">Concordo em liberar questionários respondidos a instituições privadas e públicas desde que as pesquisas concluidas e os dados coletados estejam disponíveis a todos. <br><br>
<input type="radio" name="vehicle" value="Car">Concordo em liberar questionários respondidos a instituições públicas desde que os dados coletados estejam disponíveis a todos. As pesquisas públicas concluidas e os dados por ela utilizados devem ser de livre acesso.<br><br>
<input type="radio" name="vehicle" value="Car">Estou aqui apenas pela agenda, não concordo com a liberação de meus dados sob nenhuma circunstância.
</form><br><br>

<h2>Conte-nos um pouco mais sobre você</h2>

<h8>Gostariamos de conhecer um pouco mais sobre você. Assim podemos personalizar a sua navegação e criar uma experiência única. Vai ser rapidinho. (Inserir emote feliz :) ) 
</h8><br><br>
<h8>Recomendação de eventos personalizada e a aparição apenas de pesquisas de seu interesse são alguns dos incríveis benefícios providenciados a você o usuário.</h8><br><br> 
<h8>Por outro lado, a criação de perfis (anônimos e inacessiveis em sua integra) permite que pesquisadores de todo o mundo tenham acesso a dados de alta qualidade. </h8><br><br>

<h8>Clique em cada caixa abaixo que seja de seu interesse.</h8><br><br>

<div class="interesses" id="esportes">Esportes</div>
<div class="interesses" id="tecnologia">Tecnologia</div>
<div class="interesses" id="psicologia">Psicologia</div>
<div class="interesses" id="música">Música</div>
<div class="interesses" id="saúde">Saúde</div>
<div class="interesses" id="alimentação">Alimentação</div>
<div class="interesses" id="política">Políticas</div>
<div class="interesses" id="cinema">Cinema e Tv</div>
<div class="interesses" id="teatro">Teatro</div>
<div class="interesses" id="artesplásticas">Artes Plásticas</div>
<div class="interesses" id="entretenimento">Entretenimento</div>
<div class="interesses" id="palestrasaca">Palestras Acadêmicas</div>
<div class="interesses" id="matemática">Matemática</div>
<div class="interesses" id="Bazares e Feiras">Bazares e Feiras</div>

<b-button class="button" type="submit" variant="danger">É Isto</b-button>

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