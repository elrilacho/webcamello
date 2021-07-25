<template lang="pug">
.Footer 
  .footer-bar.titlebar
    .container.px-5.py-2
      .flex.justify-between.text-gray-600
        p Camello Estudio Creativo 2021
        p.text-gray-500.font-medium.hidden(class="lg:block") Le camellamos a tu marca
        .iconos
          a(href="https://www.behance.net/camelloestudio" target="_blank")
            i.fab.fa-behance.fa-lg.mx-1(class="hover:text-gray-800")
          a(href="https://www.instagram.com/camelloestudio/?hl=es-la" target="_blank")
            i.fab.fa-instagram.fa-lg.mx-1(class="hover:text-gray-800")
            
</template>

<script>
export default {
name: "Footer"
}
</script>

<style lang="sass" scoped>

</style>