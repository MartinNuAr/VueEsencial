<template>
  <div class="container">
    <div class="row">
        <div class="col">
            <p>Texto ({{ textInput }}):</p>
            <input type="text" v-bind:value="textInput" />
        </div>
        <div class="col">
            <button class="btn btn-primary" v-on:click="textInput = 'Valor final'">Modificar</button>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'OptionComponent2',
    data(){
        return {
            textInput: 'Valor inicial'
        }
    }
}
</script>

<style>

</style>