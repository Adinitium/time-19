<template>
  <header>
    <hr>
      <div class="header-menu">
        <div class="menu-buttons">
          <nuxt-link to="/login"><img :src="require('@/assets/baseline_first_page_black_48dp.png')"/></nuxt-link>
        </div>
      </div>
  </header>
</template>


<script>
</script>

<style>
.header-menu {
  top: 0;
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
