<template>
    <ul class="nav">
        <NavBarItem v-bind:nav-data="{
            titulo: 'Inicio',
            url: '_blank'
        }"/>
        <NavBarItem v-bind:nav-data="{
            titulo: 'Contacto',
            url: '_blank'
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