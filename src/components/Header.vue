<template lang="pug">
.Header 
  .titlebar.py-3
    img(src="@/assets/logotipo.svg").m-auto
  .navbar.py-3.justify-center.flex.h-auto
    ol.flex
      li.mx-10.text-gray-700.font-medium.text-md
        a(href="x")
          |¿Quienes somos?
      li.mx-10.text-gray-700.font-medium.text-md 
        a(href="x")
          |Contácto




</template>

<script>
export default {
name: "Header"
}
</script>

<style lang="sass" scoped>

</style>