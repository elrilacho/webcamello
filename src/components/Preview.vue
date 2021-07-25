<template lang="pug">
.Preview
  .p-20.items-center
    img(src="@/assets/logo.svg" style="width:600px").m-auto.mb-10
    //- h1.text-4xl.font-bold.text-bold.text-white.uppercase.text-center Camello Estudio Creativo
    h2.text-3xl.font-bold.text-white.uppercase.text-center.italic.mb-10 sítio en construcción 
    .contenedor-carga.m-auto
      .contenedor-carga__carga
</template>

<script>

export default {
name: "Preview"
}

</script>

<style lang="sass" scoped>
.contenedor-carga
  transition: all 1s ease
  z-index: 99
  height: 100px
  width: 100px
  &__carga
    border: 15px solid #ccc
    border-top-color: #FF9000  
    
    height: 100px
    width: 100px
    border-radius: 100%
    top: 0 
    left: 0 
    right: 0
    bottom: 0
    margin: auto
    animation: girar 3s linear infinite
    @keyframes girar 
      from 
        transform: rotate(0deg)  
      to 
        transform: rotate(360deg)
      
    
</style>>
