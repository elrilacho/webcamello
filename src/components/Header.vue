<template lang="pug">
.Header 
  .titlebar.py-3
    img(src="@/assets/logotipo.svg").m-auto
  .navbar.py-3.justify-center.flex.h-auto
    ol.block.flex-wrap(class="sm:flex")
      li.mx-10.text-gray-700.font-medium.text-md
        a(href="x")
          |Home 
      li.mx-10.text-gray-700.font-medium.text-md 
        a(href="x")
          |Branding
      li.mx-10.text-gray-700.font-medium.text-md 
        a(href="x")
          |Fotografía 
      li.mx-10.text-gray-700.font-medium.text-md 
        a(href="x")
          |Modelado 3D
      li.mx-10.text-gray-700.font-medium.text-md 
        a(href="x")
          |Cotizaciones
      li.mx-10.text-gray-700.font-medium.text-md 
        a(href="x")
          |Blog




</template>

<script>
export default {
name: "Header"
}
</script>

<style lang="sass" scoped>
ol
  li 
    flex-grow: 1
    flex-wrap: wrap
    text-align: center
</style>