<template lang="pug">
#app.app
  Header
  Banner.mb-5
  Gallery
  Footer

</template>

<script>
import Header from './components/Header.vue'
import Banner from './components/Banner.vue'
import Gallery from './components/Gallery.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Banner, 
    Gallery, 
    Footer
  }
}
</script>

<style lang="sass" >

</style>
