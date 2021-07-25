<template lang="pug">
#app.app
  //- Preview
  Header
  Services.mb-5
  Nosotros.mb-5
  Footer
</template>

<script>
import Preview from '@/components/Preview.vue'
import Header from '@/components/Header.vue'
import Services from '@/components/Services.vue'
import Nosotros from '@/components/Nosotros.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Preview,
    Header,
    Services,
    Nosotros, 
    Footer
    
  }
}
</script>

<style lang="sass" scoped >
.app
  position: relative
</style>
