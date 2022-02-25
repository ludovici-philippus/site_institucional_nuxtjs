<template>
  <main>
    <BoxContent textAlign="left" title="Nossa Missão" :text="texto1"/>
    <BoxContentImage imagem="/imgs/bg.jpg" textAlign="center" title="Como trabalhamos?" :text="texto2"/>
    <BoxContent textAlign="right" title="Nossa Missão" :text="texto1"/>
  </main>
</template>

<script>
  export default{
    name: "Main",
    data(){
      return{
        texto1: `Arcu. Vestibulum porta justo placerat purus. Ut sem nunc,
                vestibulum nec, sodales vitae, vehicula eget, ipsum. Sed nec
                  tortor. Aenean malesuada. Nunc convallis, massa eu vestibulum
                  commodo, quam mauris interdum arcu, at pellentesque diam
                  metus ut nulla. Vestibulum eu dolor sit amet lacus varius
                  fermentum. Morbi dolor enim, pulvinar eget, lobortis ac,
                fringilla ac, turpis. Duis ac erat. Etiam consequat. Integer
                  sed est eu elit pellentesque dapibus. Duis venenatis magna
                  feugiat nisi. Vestibulum et turpis. Maecenas a enim.
                  Suspendisse ultricies ornare justo. Fusce sit amet nisi sed
                  arcu condimentum venenatis. Vivamus dui. Nunc accumsan, quam
                  a fermentum mattis, magna sapien iaculis.`,

        texto2: ` Nibh egestas libero, vitae pellentesque elit augue ut massa.
                  Nulla consequat erat at massa. Vivamus id mi. Morbi purus enim, dapibus a,
                  facilisis non, tincidunt at, enim. Vestibulum ante ipsum primis in faucibus
                  orci luctus et ultrices posuere cubilia Curae; Duis imperdiet eleifend arcu.
                  Cras magna ligula, consequat at, tempor non, posuere nec, libero. Vestibulum
                  vel ipsum. Praesent congue justo et nunc. Vestibulum nec felis vitae nisl
                  pharetra sollicitudin. Quisque nec arcu vel tellus tristique vestibulum.
                  Aenean vel lacus. Mauris dolor erat, commodo ut, dapibus vehicula, lobortis
                  sit amet, orci. Aliquam augue. In semper nisi nec libero. Cras magna ipsum,
                  scelerisque et.`
      }
    }
  }
</script>

<style scoped>

</style>
