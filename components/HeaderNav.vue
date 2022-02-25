<template>
  <nav>
    <ul>
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/quem-somos">Quem Somos</NuxtLink></li>
      <li><NuxtLink to="/contato">Contato</NuxtLink></li>
    </ul>
  </nav>
</template>

<script>
  export default{
    name: "HeaderNav"
  }
</script>

<style scoped>
  ul{
    list-style: none;
    margin-top: 8px;
  }

  li{
    display: inline-block;
    margin-right: 4px;
    font-size: 20px;
  }

  a{
    text-decoration: none;
    color: var(--cor-2);
    font-weight: bold;
  }

  a:hover{
    text-decoration: underline;
  }
</style>
