<script setup>

defineProps({
  msg: String,
})

</script>

<template>


  <h1>{{ msg }}</h1>
  
  <section id="Parent">
    
    <h2>props of parent flex cont</h2>
    <div class="flexbox-container">
      <div class="flexbox_item">item-1</div>
      <div class="flexbox_item">item-2</div>
      <div class="flexbox_item">item-3</div>
      <div class="flexbox_item">item-4</div>
      <div class="flexbox_item">item-5</div>
      <div class="flexbox_item">item-6</div>
    </div>
  </section>
  <section id="children">
    <h2>props of children flex cont</h2>
    <div class="flexbox-container">
      <div class="flexbox_item">item-1</div>
      <div class="flexbox_item">item-2</div>
      <div class="flexbox_item">item-3</div>
      <div class="flexbox_item">item-4</div>
      <div class="flexbox_item">item-5</div>
      <div class="flexbox_item">item-6</div>
    </div>
  </section>

  
</template>

<style scoped>
  
</style>
