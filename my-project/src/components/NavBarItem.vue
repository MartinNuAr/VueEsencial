<template>
    <li class="nav-item" v-bind:style="{'backgroundColor': randomColor}">
        <a class="nav-link">{{ titulo }}</a>
    </li>
</template>

<script>
export default {
    name: 'NavBarItem',
    data(){
        return {
            randomColor: '#' + Math.floor(Math.random()*6777215).toString(16)
        }
    },
    props: {
        titulo: String
    }
}
</script>

<style>

</style>