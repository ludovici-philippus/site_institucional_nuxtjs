<template>
  <section class="box_content">
    <div class="container">
      <h2 :style="'text-align: '+textAlign">{{ title }}</h2>
      <p>{{ text }}</p>
    </div>
  </section>
</template>

<script>
  export default{
    name: "BoxContent",
    props:{
      title: String,
      text: String,
      textAlign: String,
      has_image: Boolean,
      imagem: String
    }
  }
</script>

<style scoped>
  .box_content{
    margin-top: 20px;
  }
  .container{
    flex-direction: column;
  }

  .bg_image{
    position: relative;
    top: 0;
    left: 0;
    background-size: cover;
    background-position: center;
  }
  .overlay{
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    height: auto;
    z-index: 1
  }
</style>
