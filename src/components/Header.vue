<script setup>
  import Avatar from './Avatar.vue';

  defineProps ({
    title: String,
    text: String
  })
</script>

<template>
  <header class="Hero-header">
    <Avatar />
    <h1 class="Hero-title">{{ title }}</h1>
    <p class="Hero-text">{{ text }}</p>
  </header>
</template>

<style scoped>
  .Hero-header {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
    width: 100%;
  }
  .Hero-title {
    font-size: 2rem;
    font-weight: 700;
    margin-top: 0.5rem;
  }
  .Hero-text {
    text-align: center;
    font-size: 1.2rem;
    font-weight: 400;
    margin-top: 0.2rem;
    max-width: 500px;
  }
</style>