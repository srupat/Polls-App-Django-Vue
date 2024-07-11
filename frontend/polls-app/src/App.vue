<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" />

    <div class="wrapper">
      <HelloWorld msg="Welcome to your own Polls App!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/details">Details</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
  .logo{
    width: 50px;
    height:50px;
  }
</style>
