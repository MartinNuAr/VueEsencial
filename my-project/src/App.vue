<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <NavBar />
      </div>
      <div class="row">
        <h1>Prueba Bootstrap</h1>
      </div>
      <div class="row">
        <button type="button" class="btn btn-primary">Primary</button>
        <button type="button" class="btn btn-secondary">Secondary</button>
        <button type="button" class="btn btn-success">Success</button>
        <button type="button" class="btn btn-danger">Danger</button>
        <button type="button" class="btn btn-warning">Warning</button>
        <button type="button" class="btn btn-info">Info</button>
        <button type="button" class="btn btn-light">Light</button>
        <button type="button" class="btn btn-dark">Dark</button>
        <button type="button" class="btn btn-link">Link</button>
      </div>
      <MuchoTexto />
      <p class="texto">Los perritos son bonitos</p>
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
