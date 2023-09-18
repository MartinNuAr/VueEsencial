<template>
  <div>
    <div v-html="album.titulo"></div>
    <div v-html="album.autor"></div>
  </div>
</template>

<script>
export default {
    name: 'SegundoComponente',
    data (){
        return {
            album: {
                titulo: '<h1>God\'s Dream</h1>',
                autor: '<h2>Ringo Deathstarr</h2>'
            }
        }
    }
}
</script>

<style>

</style>