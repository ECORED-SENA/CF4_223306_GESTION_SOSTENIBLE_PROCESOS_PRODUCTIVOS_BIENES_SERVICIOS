<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5(data-aos="fade")
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.mt-4 La economía circular avanza por su dinamismo y por eso se vuelve relevante en el ciclo económico global como lo puede ver en el video que se presenta a continuación:
    figure.mb-5
      .video(data-aos="slide-up")
        iframe(width="560" height="315" src="https://www.youtube.com/embed/DH0pkZGuyPg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
