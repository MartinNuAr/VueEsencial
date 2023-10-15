<template>
  <div class="container text-center">
    <div class="row">
        <div class="col">
            <p>Última acción: {{accion}}</p>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <button 
                class="btn btn-primary" 
                v-on:click="accion = 'Click'" 
                v-on:mouseover="accion = 'Mouseover'"
            >o</button>
            <input 
                type="text" 
                @keypress="accion = 'Keypress'"
                @keypress.enter="accion = 'Keypress (Enter)'"
            />
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'OptionComponent3',
    data(){
        return {
            accion: 'Ninguna'
        }
    }
}
</script>

<style>

</style>