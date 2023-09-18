<template>
  <div>
    <h1> {{ album.titulo }}</h1>
    <h2> {{ album.autor }}</h2>
  </div>
</template>

<script>
export default {
    name: 'SegundoComponente',
    data (){
        return {
            album: {
                titulo: 'God\'s Dream',
                autor: 'Ringo Deathstarr'
            }
        }
    }
}
</script>

<style>

</style>