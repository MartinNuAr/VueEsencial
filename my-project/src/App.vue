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
            <OptionComponent1 class="option-container"/>
          </div>
          <div class="col">
            <OptionComponent2 class="option-container"/>
          </div>
          <div class="col">
            <OptionComponent3 class="option-container"/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import OptionComponent1 from './components/OptionComponent1.vue';
import OptionComponent2 from './components/OptionComponent2.vue';
import OptionComponent3 from './components/OptionComponent3.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    OptionComponent1,
    OptionComponent2,
    OptionComponent3
  }
}
</script>

<style>
  .option-container {
    border: 1px solid black;
    border-radius: 5px;
    padding: 1em;
  }
</style>
