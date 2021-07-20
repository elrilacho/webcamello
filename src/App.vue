<template lang="pug">
#app.app
  NavBar
  Banner.mb-5
  Gallery
  Footer.align-items-end.d-block

</template>

<script>
import NavBar from './components/Nav_bar.vue'
import Banner from './components/Banner.vue'
import Gallery from './components/Gallery.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Banner, 
    Gallery, 
    Footer
  }
}
</script>

<style lang="sass" scoped >

</style>
