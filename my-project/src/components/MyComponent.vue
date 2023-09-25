<template>
    <div class="MyComponent">
        <button v-show="mostrar">Botón oculto</button>
    </div>    
</template>

<script>
export default {
    name: 'MyComponent',
    data (){
        return {
            mostrar: false
        }
    }
}
</script>

<style>

</style>