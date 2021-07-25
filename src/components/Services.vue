<template lang="pug">
.Services
  .container.p-5
    .justify-center.px-20.py-3(class= "sm:flex sm:space-x-10")
      .img-hover.w-max.m-auto.mb-5(class= "sm:m-0")
        a(href="#")
          .img-hover__box.p-5.text-center.bg-gray-400.text-white.opacity-0.bg-opacity-80.w-min.flex(class="hover:opacity-100").rounded-xl
            .text.m-auto
              h2.text-2xl.uppercase.font-bold.mb-3 Branding 
              p La cara bonita que veran tus clientes
          .img-hover__image: img(src="@/assets/img1.jpg").rounded-xl
            
      .img-hover.w-max.m-auto.mb-5(class= "sm:m-0")
        a(href="#")
          .img-hover__box.p-5.text-center.bg-gray-400.text-white.opacity-0.bg-opacity-80.w-min.flex(class="hover:opacity-100").rounded-xl
            .text.m-auto.text-white
              h2.text-2xl.uppercase.font-bold.mb-3 Fotografía 
              p La sesión de fotos que tus productos merecen
          .img-hover__image: img(src="@/assets/img2.jpg").rounded-xl
          
      .img-hover.w-max.m-auto.mb-5(class= "sm:m-0")
        a(href="#")
            .img-hover__box.p-5.text-center.bg-gray-400.text-white.opacity-0.bg-opacity-70.w-min.flex(class="hover:opacity-100").rounded-xl
              .text.m-auto.text-white
                h2.text-2xl.uppercase.font-bold.mb-3 Modelado 3D
                p  Proyecta y nosotros moldearemos tus ideas en 3D 
            .img-hover__image: img(src="@/assets/img3.jpg").rounded-xl
                
    

  
</template>
  
<script>
export default {
name: "Services"
}
</script>

<style lang="sass" scoped>
.img-hover
  position: relative
  &__box
    p, h2
      color: white
    opacity: 0
    position: absolute
    top: 0
    left: 0
    width: 100%
    height: 100%
    transition: opacity 0.5s
      
    
</style>