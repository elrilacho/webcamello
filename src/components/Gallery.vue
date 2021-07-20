<template lang="pug">
.Gallery.p-5
    //- h1.h1.mb-5.text-center.color-secundario Galería de proyectos
    .row.mb-3.justify-content-center
        .col-lg-3.mb-3
            .card.bg-dark.text-white
                img.card-img(src="../assets/muestra.jpeg")
                .card-img-overlay.justify-content-center.d-flex
                    .card-text.m-auto
                        h3.card-title.text-center.m-auto Branding para (Inserte titulo de cliente)
                        p.card-text.text-center.m-auto (lorem ipsum dolor)
        .col-lg-3.mb-3
            .card.bg-dark.text-white
                img.card-img(src="../assets/muestra.jpeg")
                .card-img-overlay.justify-content-center.d-flex
                    .card-text.m-auto
                        h3.card-title.text-center.m-auto Branding para (Inserte titulo de cliente)
                        p.card-text.text-center.m-auto (lorem ipsum dolor)
        .col-lg-3.mb-3
            .card.bg-dark.text-white
                img.card-img(src="../assets/muestra.jpeg")
                .card-img-overlay.justify-content-center.d-flex
                    .card-text.m-auto
                        h3.card-title.text-center.m-auto Branding para (Inserte titulo de cliente)
                        p.card-text.text-center.m-auto (lorem ipsum dolor)
    
</template>

<script>
export default {
    name: "Gallery"

}
</script>

<style lang="sass" scoped src="../styles/_gallery.sass">
.h1 
    font-weight: 800
</style>