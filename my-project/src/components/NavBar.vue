<template>
    <ul class="nav">
        <NavBarItem />
        <NavBarItem />
        <NavBarItem />
        <NavBarItem />
    </ul>
</template>

<script>
import NavBarItem from './NavBarItem.vue';
export default {
    name: 'NavBar',
    components: {
        NavBarItem
    },
    data(){
        return {
            mostrarActivo: true,
        }
    }
}
</script>

<style>

</style>