<template lang="pug">
.Banner
    .banner-principal.p-5.justify-content-center.d-flex
        .titulo-boton
            h1.mb-5.color-secundario ¡LE CAMELLAMOS A TU MARCA!
            button.btn.boton-principal.m-auto.d-block Ver proyectos
</template>

<script>
export default {
name: 'Banner'
}
</script>

<style lang="sass" scoped>
.Banner
h1
    font-size: 60px
h1, h2
    font-weight: bold
    margin: auto
    display: block
    text-align: center
.banner-principal
    height: auto
    width: auto
    background-size: cover
.titulo-boton
    margin: auto
.boton-principal
    background-color: #FF9000
    font-size: 20px
    color: white
    font-weight: 500

</style>