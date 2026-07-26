<script setup>
    import {ref} from 'vue'
    const heading = ref("Quote generator")
</script>

<template>
  <header>
      <h1>{{ heading }}</h1>
  </header>
</template>

<style scoped>
  header {
      color:#CCD6D9;
      margin-bottom:25px;
  }
</style>
