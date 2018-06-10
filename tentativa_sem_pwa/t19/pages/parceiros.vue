<template>
  <div class="background">
    <homepage-header></homepage-header>
<h1>Parceiros</h1>

<h8>
  Essa galera é quem faz tudo ser possível.
</h8><br><br>

<div class="parceiro" id="random">
  <h8 class="produto">Random</h8>
  <img :src="require('@/assets/hardwarelivre.png')"/> 
</div>

<div class="parceiro" id="random">
  <h8 class="produto">Random</h8>
  <img :src="require('@/assets/neu.png')"/>
</div>

<div class="parceiro" id="random">
  <h8 class="produto">Random</h8>
  <img :src="require('@/assets/uspcodelab.png')"/>
</div>

<div class="parceiro" id="random">
  <h8 class="produto">Random</h8>
  <img :src="require('@/assets/vtex.png')"/>
</div>

<div class="parceiro" id="random">
  <h8 class="produto">Random</h8>
  <img :src="require('@/assets/Udacity_logo.png')"/>
</div>


<br>
<br>
</div>
</template>

<script>
import HomepageHeader from '../components/HomepageHeader.vue'

export default {
  components: {
    HomepageHeader
  }
}
</script>