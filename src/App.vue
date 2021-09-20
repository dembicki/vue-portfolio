<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
</script>

<template>
  <Header />
  <!-- <HelloWorld msg="Hello Vue 3 + Vite" /> -->
</template>

<style>
body{
  margin:0;
  padding:0;
  box-sizing: border-box;
}

#app {
  font-family:  Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  background-color: black;
  min-height: 100vh;
}
</style>
