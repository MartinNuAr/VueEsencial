<template>
  <div class="option-1 text-center">
    <p>Total: {{ option }}</p>
    <button class="btn btn-primary" v-on:click="sumar">Sumar 1</button>
  </div>
</template>

<script>
export default {
    name: 'OptionComponent1',
    data(){
        return {
            option: 0,
        }
    },
    methods: {
        sumar: function () {
            this.option += 1
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