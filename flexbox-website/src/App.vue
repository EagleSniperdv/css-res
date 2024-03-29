<script setup>
import NavBar from './components/NavBar.vue'
import TheHeader from './components/TheHeader.vue';
import TheAbout from './components/TheAbout.vue'
import TheService from './components/TheService.vue'
import TheContact from './components/TheContact.vue'
import TheFooter from './components/TheFooter.vue'
</script>

<template>
  <main id="Main1">
    <NavBar/>
    <TheHeader/>
    <TheAbout/>
    <TheService/>
    <TheContact/>
    <TheFooter/>
    <i class="fas fa-mail-bulk fa-3x"></i>
  </main>
  
</template>

<style scoped>
#Main1{
    height: 100vh;
    background-image: url("../public/vite.svg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    text-shadow: 1px 1px 1px #333;
    color: #fff
}
</style>
