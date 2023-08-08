<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Titulo texto="Mi Inicio" />
  </div>
</template>

<script>
import Titulo from '../components/Titulo.vue'

export default {
  name: 'HomeView',
  components: {
    Titulo
  }
}
</script>
