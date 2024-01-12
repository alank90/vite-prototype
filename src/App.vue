<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <a href="https://vuejs.org/" target="_blank">
    <img src="./assets/logo.png" class="logo vue" alt="Vue logo" />
  </a>

  <HelloWorld msg="Vite + Vue" />

  /* Replace markup with this if using vue router
  <!-- =============== route outlet ============================================= -->
  <!-- component matched by the route will render here ========================== -->
  <router-view></router-view>
  <!-- =============== End route outlet ========================================= -->
  */
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
