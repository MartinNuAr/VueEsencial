<template>
    <div class="MyComponent">
        <button v-if="mostrar == 1">Botón 1</button>
        <button v-else-if="mostrar == 2">Botón 2</button>
        <button v-else>Botón genérico</button>
    </div>    
</template>

<script>
export default {
    name: 'MyComponent',
    data (){
        return {
            mostrar: 3
        }
    }
}
</script>

<style>

</style>