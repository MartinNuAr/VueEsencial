<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <NavBar />
      </div>
      <div class="row">
        <h1>Prueba Bootstrap</h1>
      </div>
      <MuchoTexto />
    </div>
  </div>
</template>

<script>
import MuchoTexto from './components/MuchoTexto.vue';
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    MuchoTexto
  }
}
</script>

<style>

</style>
