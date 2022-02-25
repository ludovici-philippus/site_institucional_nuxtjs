<template>
  <div class="logo">
    <NuxtLink to="/"><h1>Logo</h1></NuxtLink>
  </div>
</template>

<script>
  export default{
    name: "HeaderBar"
  }
</script>

<style scoped>
  a{
    text-decoration: none;
    color: white;
  }

  h1{
    display: inline-block;
  }
</style>
