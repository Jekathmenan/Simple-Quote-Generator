<script setup>
    import {ref} from 'vue'
    const year = ref("2020")
    const href = ref("https://scrimba.com")
    year.value = new Date().getFullYear();
</script>
   
<template>
  <footer>
      Created by <a :href> <span>Professor Pickle</span></a> &copy; {{ year }}
  </footer>
</template>

<style scoped>
  footer {
    position:fixed;
    margin: 0 auto;
    bottom:0;
    text-align:center;
    color:#CCD6D9;
    padding-bottom:20px;
  }

  a {
    color:#CCD6D9;
  }

  span{
      font-family: cursive;
  }
</style>