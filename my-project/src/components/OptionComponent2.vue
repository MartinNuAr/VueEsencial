<template>
  <div class="container">
    <div class="row">
        <div class="col">
            <p>Texto:</p>
        </div>
        <div class="col">
            <input type="text" v-bind:value="textInput" />
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'OptionComponent2',
    data(){
        return {
            textInput: ':D'
        }
    }
}
</script>

<style>

</style>