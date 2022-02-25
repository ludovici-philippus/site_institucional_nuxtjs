<template>
  <header>
    <div class="container">
      <HeaderBar/>
      <HeaderNav/>
    </div>
  </header>
</template>

<script>
  export default{
    name: "Header"
  }
</script>

<style scoped>
  header{
    background-color: var(--cor-3);
    padding: 20px 0;
  }

  .container{
    justify-content: space-between;
  }
</style>
