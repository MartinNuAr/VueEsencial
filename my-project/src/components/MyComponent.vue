<template>
    <div class="MyComponent">
        <div v-for="comida in comidas">
            <strong>Platillo: </strong> {{ comida.nombre }}
            <br />
            <strong>Precio: </strong> ${{ comida.precioMXN }}
            <hr />
        </div>
    </div>    
</template>

<script>
export default {
    name: 'MyComponent',
    data (){
        return {
            comidas: [
                {nombre: 'Spaghetti', precioMXN: 50},
                {nombre: 'Sandwich', precioMXN: 30},
                {nombre: 'Sopa', precioMXN: 40},
                {nombre: 'Carne asada', precioMXN: 80}
            ]
        }
    }
}
</script>

<style>

</style>