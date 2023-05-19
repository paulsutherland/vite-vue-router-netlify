<script setup>

</script>

<template>
  <h1>Hello App!</h1>
  <p>
    <router-link to="/">Go to Home</router-link>
    <br>
    <router-link to="/about">Go to About</router-link>
    <br>
    <router-link to="/contact">Go to Contact</router-link>
  </p>

  <router-view></router-view>
</template>

<style scoped>

</style>
