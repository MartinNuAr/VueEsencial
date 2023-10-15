<template>
  <div class="option-1 text-center">
    <p>Opción 1 {{ option }}</p>
    <button class="btn btn-primary" v-on:click="option = 'clickeada'"></button>
  </div>
</template>

<script>
export default {
    name: 'OptionComponent1',
    data(){
        return {
            option: ''
        }
    }
}
</script>

<style>
    .option-1{
        border: 1px solid black;
        border-radius: 5px;
    }
</style>