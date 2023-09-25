<template>
    <div class="MyComponent">
        <ul>
            <li v-for="comida in comidas">{{ comida }}</li>
        </ul>
    </div>    
</template>

<script>
export default {
    name: 'MyComponent',
    data (){
        return {
            comidas: ['Spaghetti', 'Sandwich', 'Sopa', 'Carne asada']
        }
    }
}
</script>

<style>

</style>