<template>
  <div class="home">
    <div class="background-image"></div>
    <div class="content">
      <h1>This is the Home Page</h1>
      <div>Hola logo inicio</div>
    </div>
    <img alt="Vue logo" src="../assets/model-y.webp">
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style scoped>
.home {
  position: relative;
  min-height: 100vh;
  overflow: hidden;
}

.background-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  height: 200vh;
  background-image: url("../assets/netflixfondo.jpg");
  background-size: cover;
  background-position: center;
  transform: translate3d(0, 0, 0);
  z-index: -1;
}

.content {
  position: relative;
  z-index: 1;
  text-align: center;
  padding: 20px;
  color: white;
}

/* Estilos responsivos */
@media (max-width: 768px) {
  .background-image {
    height: 300vh;
    /* Ajusta la altura para un efecto de parallax más notorio en pantallas pequeñas */
  }
}
</style>
