<script setup>
import TheNavBar from './components/TheNavBar.vue';
import TheHeader from './components/TheHeader.vue';
import TheSocialBar from './components/TheSocialBar.vue';
import TheContact from './components/TheContact.vue';
import TheFooter from './components/TheFooter.vue';
import TheBubble from './components/TheBubble.vue';
</script>

<template>
<main class="main-container">
  <TheNavBar/>
  <TheHeader/>
  <TheSocialBar/>
  <TheContact/>
  <TheFooter/>
  <TheBubble/>
</main>
</template>

<style scoped>

.main-container {
  height: 100vh;  
  width: 100%;
  background-position: center;
  background-size: cover;
  position: relative;
  
  overflow: hidden;
  box-shadow: inset 0 0 500px 100px #111;
}



  
</style>
