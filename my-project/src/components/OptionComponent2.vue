<template>
  <div class="container text-center">
    <div class="row">
        <p>Texto ({{ textInput }}):</p>
    </div>
    <div class="row">
        <div class="col">
            <input type="text" v-model="textInput" />
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