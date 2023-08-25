<template>
<!--  <div class="Background-Wrapper">-->
<!--    <div class="Background-Wrapper__Test"></div>-->
<!--  </div>-->
  <TheMainMenu/>
  <div id="App-Inner-Wrapper">
    <RouterView/>
  </div>
</template>

<script setup lang="ts">

import TheMainMenu from "@/components/TheMainMenu.vue";
</script>

<style scoped>
@import "@/assets/styles/Background.css";
</style>
