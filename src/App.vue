<template>
  <div id="app">
    <NavComp />
    <router-view />
    <!-- <img alt="Vue logo" src="../src/assets/model-x.avif"> -->
  </div>
  <!-- <div>
    <SignIn />
  </div> -->
  <!-- <div>
    <SignIn />
  </div> -->
  <!-- <div>
    <SignIn />
  </div> -->
</template>

<script setup>
import NavComp from '@/components/NavComp.vue'
import SignIn from './components/SignIn.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

@media (max-width: 768px) {
  #app {
    font-size: 14px;
    /* Example responsive font size */
  }
}
</style>
