<template>
  <section :style="'background-image: url('+imagem+');'" class="box_content bg_image">
    <div class="overlay"></div>
    <div class="container">
      <h2 :style="'text-align: '+textAlign">{{ title }}</h2>
      <p>{{ text }}</p>
    </div>
  </section>
</template>

<script>
  export default{
    name: "BoxContentImage",
    props:{
      title: String,
      text: String,
      textAlign: String,
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
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 2;
  }

  .bg_image{
    position: relative;
    top: 0;
    left: 0;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    z-index: 0;
    width: 100%;
    min-height: 900px;
  }
  .overlay{
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    min-height: 900px;
    z-index: 1;
    background-color: rgba(255, 255, 255, 0.96);
  }
</style>
