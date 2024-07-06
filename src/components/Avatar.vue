<script setup>
  defineProps ({
    avatar: String
  })
</script>

<template>
    <img src="../assets/avatar.jpg" alt="Iceheop Avatar">
</template>

<style scoped>
  img {
    width: 250px;
    height: 250px;
    border-radius: 100%;
  }
</style>