<template>
    <div class="MyComponent">
        <button v-if="mostrar">Botón oculto</button>
    </div>    
</template>

<script>
export default {
    name: 'MyComponent',
    data (){
        return {
            mostrar: true
        }
    }
}
</script>

<style>

</style>