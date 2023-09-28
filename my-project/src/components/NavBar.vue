<template>
    <ul class="nav">
        <NavBarItem v-bind:nav-data="{
            titulo: 'Inicio',
            url: 'https://vuejs.org/'
        }"/>
        <NavBarItem v-bind:nav-data="{
            titulo: 'Contacto',
            url: 'https://vuejs.org/'
        }"/>
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