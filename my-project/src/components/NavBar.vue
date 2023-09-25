<template>
    <ul class="nav">
        <li class="nav-item">
            <a class="nav-link" v-bind:class="{ active: mostrarActivo }" href="#">Active</a>
        </li>
        <li class="nav-item">
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
            mostrarActivo: true
        }
    }
}
</script>

<style>

</style>