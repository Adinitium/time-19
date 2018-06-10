<template>
  <header>
    <hr>
      <div class="header-menu">
        <div class="menu-buttons">
          <b-button-group>
          <b-button variant="outline-danger" size="sm" @click="menu" class=""><img :src="require('@/assets/baseline_menu_black_48dp.png')"/></b-button>
          <b-button variant="outline-danger" size="sm" @click="home" class=""><img :src="require('@/assets/baseline_home_black_48dp.png')"/></b-button>
          <b-button variant="outline-danger" size="sm" @click="questionario" class=""><img :src="require('@/assets/baseline_check_black_48dp.png')"/></b-button>
          <b-button variant="outline-danger" size="sm" @click="busca" class=""><img :src="require('@/assets/baseline_search_black_48dp.png')"/></b-button>
         </b-button-group>
        </div>
      </div>
  </header>
</template>

<script>
</script>

<style>
.header-menu {
  margin-top: -3.1em;
  height: 3em;
  text-align: left;
  display: flex;
  flex-direction: column;
  background-color: #2286c3
}

.background {
  background-color: #e6ffff
}

.b-button-sm {
  width: 1em;
}

.img {
  height: 1em;
}

</style>
