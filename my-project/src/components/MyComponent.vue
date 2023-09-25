<template>
    <div class="MyComponent">
        {{ comidas[0] }}
        {{ comidas[1] }}
        {{ comidas[2] }}
    </div>    
</template>

<script>
export default {
    name: 'MyComponent',
    data (){
        return {
            comidas: ['Spaghetti', 'Sandwich', 'Sopa']
        }
    }
}
</script>

<style>

</style>