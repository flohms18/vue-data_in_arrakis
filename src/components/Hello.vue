<script setup>

import Header from './Header.vue';
import Footer from './Footer.vue';
</script>

<template>
  <div class="parallax">
      <h1 class="james">DUNE</h1>
  </div>
  
</template>

<style scoped>
.james {
  font-family: "custom_dune", sans-serif;
}

.parallax {
  background-image: url("./src/assets/images/dune-wallpaper.jpeg");
  min-height: 500px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
