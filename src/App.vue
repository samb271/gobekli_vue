<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="background">
    <RouterView />
  </div>
</template>

<style>
.background {
  background-color: #FFF8E8;
}

@font-face {
  font-family: "Parabole Display";
  src: local("Parabole"),
    url(./assets/fonts/Parabole/ParaboleTrial-DisplayRegular.otf);
}

@font-face {
  font-family: "Parabole Text";
  src: local("Parabole"),
    url(./assets/fonts/Parabole/ParaboleTrial-TextRegular.otf);
}
</style>