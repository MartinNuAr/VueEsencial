<template>
    <ul class="nav">
        <li class="nav-item">
            <a class="nav-link" v-bind:class="{ active: mostrarActivo }" href="#">Active</a>
        </li>
        <li class="nav-item" v-bind:style="{ backgroundColor: randomColor }">
            <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
            <a class="nav-link disabled">Disabled</a>
        </li>
    </ul>
</template>

<script>
export default {
    name: 'NavBar',
    data(){
        return {
            mostrarActivo: true,
            randomColor: '#' + Math.floor(Math.random()*6777215).toString(16)
        }
    }
}
</script>

<style>

</style>