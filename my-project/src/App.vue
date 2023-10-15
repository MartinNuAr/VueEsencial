<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <NavBar />
      </div>
      <div class="row">
        <h1>Vue.js</h1>
      </div>
      <div class="container">
        <div class="row">
          <div class="col">
            <Option1 />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Option1 from './components/Option1.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    Option1
  }
}
</script>

<style>

</style>
