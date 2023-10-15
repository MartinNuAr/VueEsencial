<template>
    <ul class="nav">
        <!-- eslint-disable-next-line -->
        <NavBarItem v-bind:nav-data="item" v-for="item in navItems"/>
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
            navItems: [
                {
                    titulo: 'Inicio',
                    url: 'https://vuejs.org/'
                },
                {
                    titulo: 'Contactos',
                    url: 'https://vuejs.org/'
                }
            ]
        }
    }
}
</script>

<style>

</style>