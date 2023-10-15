<template>
  <div class="option-1 text-center">
    <p>Selección: {{ texto }}</p>
    <button class="btn btn-primary" v-on:click="letraElegida('A')">A</button>
    <button class="btn btn-primary" v-on:click="letraElegida('B')">B</button>
  </div>
</template>

<script>
export default {
    name: 'OptionComponent1',
    data(){
        return {
            option: 0,
            texto: ''
        }
    },
    methods: {
        sumar: function () {
            this.option += 1
        },
        letraElegida: function (letra) {
            this.texto = letra;
        }
    }
}
</script>

<style>
    .option-1{
        border: 1px solid black;
        border-radius: 5px;
        padding: 1em;
    }
</style>