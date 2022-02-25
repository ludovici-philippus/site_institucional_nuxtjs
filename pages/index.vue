<template>
  <div id="root">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style>
  :root{
    --cor-1: #C33C54;
    --cor-2: #004BA8;
    --cor-3: #1B998B;
    --cor-4: #77AF9C;
    --cor-5: #EDF67D;
  }

  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-size: Verdana sans-serif
  }

  .container{
    max-width: 1100px;
    padding: 0 2%;
    margin: auto;
    display: flex;
  }
</style>
