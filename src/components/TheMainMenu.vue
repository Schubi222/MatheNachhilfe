<template>
  <div class="The-Main-Menu-Wrapper">
    <router-link :to="{name:'home'}" class="Logo-Wrapper ">
      <span>
        <font-awesome-icon icon="fa-solid fa-user-ninja " class="Logo-Wrapper__logo"/>
        <font-awesome-icon icon="calculator"  class="Logo-Wrapper__logo"/>
      </span>
      <div class="Logo-Wrapper__text">Number<br> Ninjas</div>
    </router-link>
    <nav class="Main-Menu">
      <router-link to="#" class="Main-Menu__entry">Kurse</router-link>
      <router-link to="#" class="Main-Menu__entry">Über Mich</router-link>
      <router-link to="#" class="Main-Menu__entry">Placeholder</router-link>
    </nav>

    <nav class="Account">
      <div class="Account__items">Avatar</div>
      <div class="Account__items">Login</div>
      <div class="Account__items">Register</div>
      <div class="Account__items">Menu</div>
    </nav>
  </div>

</template>

<script setup lang="ts">

</script>



<style >
@import "@/assets/styles/TheMainMenu.css";
</style>