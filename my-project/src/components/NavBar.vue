<template>
    <ul class="nav">
        <NavBarItem titulo="1"/>
        <NavBarItem titulo="2"/>
        <NavBarItem titulo="3"/>
        <NavBarItem titulo="4"/>
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