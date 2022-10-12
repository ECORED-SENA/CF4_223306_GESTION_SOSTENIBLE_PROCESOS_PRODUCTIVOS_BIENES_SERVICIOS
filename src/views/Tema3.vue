<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade")
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Comunicación
    p La comunicación es la realidad que une a las personas y empresas permitiendo que se integren desde cualquier lugar del mundo, en el siguiente video se explica a detalle cada uno de los elementos que permiten hacer el proceso:  
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.mt-4.p-3.bt2
      .col-lg-2
        img(src='@/assets/curso/tema3/img1.svg', alt='Texto que describa la imagen')
      .col-lg-10
        p Estos elementos permiten que la comunicación sea una oportunidad en el diario vivir, el tema es muy amplio y se puede dividir en subgrupos para entenderla mejor: dos subgrupos importantes son lo que tienen que ver con la comunicación oral y la comunicación escrita que también se conocen como tipos de la comunicación y se describen a continuación:
    
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1  La comunicación oral 
    p Es aquella que se realiza entre dos o más personas con el uso de un lenguaje o código compartido por medio de un medio de transmisión físico que normalmente se le conoce como aire, aunque en la actualidad se puede añadir elementos de comunicación oral que se usan con frecuencia todos los días en el vivir como lo son los teléfonos y las computadores o dispositivos electrónicos.
    p En la comunicación oral la expresión juega un rol muy importante, las personas tienen dos formas de usarla:
    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header
        .row
          .col-lg-6
            h4 Espontánea
          .col-lg-6
            h4 Reflexiva
      table
        tr.colrw
          td El propósito principal del habla espontánea es promover el rápido intercambio de ideas entre las personas, pero puede haber otros.
          td La función principal de las respuestas del habla es atraer y persuadir o persuadir al oyente. La estructura del texto en sí y la estructura gramatical son más complejas que la expresión oral automática.
    
    p A continuación, se hacen recomendaciones para lograr comunicación de manera efectiva que se llama asertiva:
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    separador
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2  Comunicación de atributos ambientales
    .row
      .col-lg-8
        p La comunicación ambiental permite a los ciudadanos obtener información clave, así como aprender a consultar datos para comprender mejor lo que sucede en el medio ambiente. De esta manera, cada individuo puede decidir que recibe y que comparte con el fin de protegerse y ayudar a los demás. Los temas iniciales son de conciencia ambiental y cambio de hábitos que las nuevas generaciones entienden muy bien. El mensaje que se debe enviar es el de hacer una sociedad que sea sostenible en todo sentido.
        p La comunicación ambiental no es solo la comunicación de asuntos ambientales, la comunicación ambiental tiene como objetivo una educación ambiental, esta comunicación ambiental debe ser el tono de comunicación que tienen los negocios verdes o negocios basados en economía circular.
        p La lealtad del comprador es el proceso de crear una conexión emocional con los consumidores y alentarlos a comprar con más frecuencia o fortalecer los lazos entre los clientes y las empresas. Al brindar una experiencia de compra positiva y memorable, su empresa construye una relación de confianza, esto los alentará a volver a comprar sus productos y servicios, así como a recomendar su marca a amigos y familiares. Los siguientes son algunos de los elementos a tener en cuenta cuando hable con sus usuarios:
      .col-lg-4
        img(src='@/assets/curso/tema3/img2.png', alt='Texto que describa la imagen')
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
