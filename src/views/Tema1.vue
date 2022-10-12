<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade")
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Modelo de negocio en la implementación de la economía circular
    p Un modelo de negocio es una herramienta de proyecto previo al trabajo, que permite tener un concepto claro de los alcances de una empresa en un determinado proyecto conociendo su viabilidad tal como se explica a continuación:
    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema1/img1.svg', alt='Texto que describa la imagen')
      .tarjeta.color-acento-botones.p-3(x="21.5%" y="32.5%" numero="+")
        .titulo-sexto.color-acento-contenido
          h5 ¿Cada cuánto se venderá?
        p Se establece la modalidad de ventas logrando establecer si se le vende a cliente por detalle o a cliente por mayor y cada cuanto se hace eso (B2B, B2C).
      .tarjeta.color-acento-botones.p-3(x="38%" y="24.5%" numero="+")
        .titulo-sexto.color-acento-contenido
          h5 ¿Qué se debe mejorar?
        p El modelo de negocio entiende la mejora continua como la oportunidad de avanzar rápidamente en el mercado y establece un plan para trabajar en ello.
      
      .tarjeta.color-acento-botones.p-3(x="90%" y="26%" numero="+")
        .titulo-sexto.color-acento-contenido
          h5 ¿A quién se le vende?
        p Define el cliente objetivo dejando claro el segmento de mercado a trabajar por parte de una empresa.
      .tarjeta.color-acento-botones.p-3(x="69%" y="56.5%" numero="+")
        .titulo-sexto.color-acento-contenido
          h5 ¿Cómo generar ventas?
        p Las ventas son el resultados de una planeación que debe ser detallada con proyecciones establecidas.
      .tarjeta.color-acento-botones.p-3(x="31%" y="64.5%" numero="+")
        .titulo-sexto.color-acento-contenido
          h5 ¿Cómo generar recursos?
        p Las empresas no viven solo de las ventas, el modelo de negocio apoya directamente la generación de recursos para los diferentes movimientos empresariales.
    .row.mt-4
      .col-lg-4
        img(src='@/assets/curso/tema1/img2.png', alt='Texto que describa la imagen')
      .col-lg-8
        p.mb-0 El modelo de negocio permite ver los alcances de la empresa y evita que se hagan inversiones erróneas salvaguardando los intereses de la empresa, esta es una herramienta de investigación que permite saber ¿quién es la empresa? y ¿quién es el usuario? en la realidad de un mercado. Esta herramienta es tan amplia que se divide en varios tipos de modelos de negocio, para este efecto y componente formativo se trabajará con el          
          span.tc1 <strong>modelo de negocio circular.</strong>   
          |  En pocas palabras, los modelos de negocio representan el conjunto de ideas, estrategias y principios con el cual las organizaciones generan valor.  
        
        p.mb-0 En Colombia se viene trabajando el sustento de la economía con este tipo de modelos como lo dice MinAmbiente (2020)  
          span.tc1 <strong>“la economía circular abre oportunidades para un abanico de nuevos modelos de negocio a partir de innovaciones tecnológicas, servicios de desmaterialización y productos nuevos que aumentan las posibilidades de nuevos ciclos de transformación en sistemas industriales” </strong>   
          |  por ende los emprendimientos nacionales y las empresas ven grandes oportunidades en este medio. Un modelo de negocio circular se fundamenta en el análisis y desarrollo, a partir de su concepción, de cada una de las probables recirculaciones de elementos y materiales y la reducción o supresión de residuos, durante todo el periodo de vida del producto.      
    p.mt-2 Para entender mejor el concepto de modelo de negocio se realiza la siguiente gráfica que explica lo que es un modelo de negocio circular:
    .titulo-sexto.color-acento-contenido
      h5 Figura 1.  
      span Modelo de negocio en la economía circular
    img(src='@/assets/curso/tema1/img3.svg', alt='Texto que describa la imagen')
    figcaption Nota. Tomada de Guía rápida para diseñar modelos de negocio circulares de Alba, Á. (2021). 
    .row.mt-4
      .col-lg-8.mt-4
        p La economía circular, así como la innovación es algo que se debe encontrar en el ADN de las empresas, estas dos herramientas permiten a las empresas ser competentes. La circularidad es uno de los factores importantes en la innovación de los planes estratégicos empresariales pensar a futuro porque son negocios que reciclan los materiales para volver a transformarlos, esa es la circularidad o ciclo.
        p La economía circular busca reciclar los materiales ayudando a la descontaminación que se presenta en la actualidad, es por ello, que este modelo llama la atención de las empresas, y así el deseo de implementarla en sus negocios, y así ayudar a conservar el medio ambiente de una forma innovadora donde el material primo vuelva a ser reutilizado para seguir generando nuevos productos. En la actualidad, la economía circular es implementada a nivel mundial siendo aceptada con un buen agrado por los consumidores, los cuales le dan el visto bueno a este método económico con el cual se ofrece una solución que aporta  a la disminución del calentamiento global. A manera de ejemplo, puede revisar a continuación varios tipos de negocios circulares:
      .col-lg-4
        img(src='@/assets/curso/tema1/img3.png', alt='Texto que describa la imagen')
    .row.mt-4.bg1.justify-content-center
      .col-lg-10
        ImagenInfografica.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema1/img4.svg', alt='Texto que describa la imagen')
          .tarjeta.color-acento-botones.p-3(x="29.5%" y="22.5%" numero="+")
            .titulo-sexto.color-acento-contenido
              h5 Suministros circulares
            p.mb-0 Se basa en el aporte de suministros que sean completamente renovables, reciclables o biodegradables y que, por tanto, ayudan a mantener la circularidad de los procesos y sistemas de consumo.
            p Su propuesta de valor reside en la sustitución de combustibles fósiles o de materiales críticos o escasos.
          .tarjeta.color-acento-botones.p-3(x="36.5%" y="46.5%" numero="+")
            .titulo-sexto.color-acento-contenido
              h5 Recuperación de recursos
            p Es hacer más rentable la obtención de ciertos materiales a partir de los residuos que directamente de la minería tradicional. Por ejemplo: usar piezas de elementos funcionales de productos que no funcionan, por ejemplo, una batería de teléfono en un teléfono que no funciona.
          .tarjeta.color-acento-botones.p-3(x="50%" y="54%" numero="+")
            .titulo-sexto.color-acento-contenido
              h5 Extensión de la vida del producto
            p La idea es hacer productos que no sean desechables, que sean útiles en al menos un periodo de tiempo prudente. Por ejemplo: cambiar las bolsas de un solo uso por bolsas de varios usos.
          .tarjeta.color-acento-botones.p-3(x="63.5%" y="46.5%" numero="+")
            .titulo-sexto.color-acento-contenido
              h5 Compartir plataformas
            p También llamado consumo colaborativo, consiste en usar la tecnología para aumentar el uso de todo tipo de bienes. En ellas, el propietario ofrece a otros usuarios el uso de aquello que está en su poder a cambio de una compensación económica o comprar licencias entre varios usuarios o un camión entre varias empresas.
          .tarjeta.color-acento-botones.p-3(x="70.5%" y="22.5%" numero="+")
            .titulo-sexto.color-acento-contenido
              h5 Producto como servicio
            p.mb-0 Muy similar al anterior, la diferencia está en que es la marca o el fabricante quien ofrece la posibilidad a sus clientes de, en lugar de comprar, pagar por el uso del producto.
            p El usuario deja de ser propietario y pasa a “alquilar” el producto en cuestión.
    .row.mt-4.bg2.p-4.align-items-center
      .col-lg-2
        img.tam(src='@/assets/curso/tema1/i1.svg', alt='Texto que describa la imagen')
      .col-lg-8
        p.mb-0 Para ampliar el tema sobre el Modelo de negoció en la implementación de la economía circular, se recomienda ver el video sobre: <i>“La Economía circular en la empresa y nuevas modelos de negocio”</i> que se encuentra relacionado en el material complementario.
    
    separador
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1  Portafolio de iniciativas de economía circular
    p Un portafolio de iniciativas, es un conjunto de ideas agrupadas y presentadas de una forma ordenada      con la información completa y necesaria para que el inversor pueda ver lo que se pretende realizar. En este caso un portafolio de iniciativas de economía circular es una estrategia que muestra las mejores ideas en la ejecución del plan que hace circular el modelo de negocio de la empresa, la tarea de este portafolio es mostrar las mejores opciones y estrategias para cumplir con el objetivo principal. A continuación, se presenta el portafolio de economía circular como recurso básico de trabajo:
    img(src='@/assets/curso/tema1/img5.svg', alt='Texto que describa la imagen')
    figcaption Infografía realizada con base en Ceiba (2020).
    p.mt-4 Se busca que los portafolios de la economía circular sean innovadores con el fin de experimentar nuevos proyectos en el ámbito internacional ofreciendo un intercambio de experiencias y nuevos conocimientos a la economía, es por eso por lo que entre más innovador sea el portafolio más va a llamar la atención de las empresas se recomienda que cuente con las siguientes características:   
    SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-botones.p-4.mt-5
        .row.justify-content-center.mb-3.mt-5
          .col-6
            img.mtn(src='@/assets/curso/tema1/i2.svg' alt='AvatarTop')
        .row.justify-content-center
          .col-lg-8.aqw
            h4.text-center.mt-2 Identificación
        p.text-center.mt-4.mb-5 Se debe mostrar con claridad de donde es el portafolio.
      .tarjeta.color-acento-botones.p-4.mt-5
        .row.justify-content-center.mb-3.mt-5
          .col-6
            img.mtn(src='@/assets/curso/tema1/i3.svg' alt='AvatarTop')
        .row.justify-content-center
          .col-lg-8.aqw
            h4.text-center.mt-2 Categorización
        p.text-center.mt-4.mb-5 Presenta el material ordenado y jerarquizado.
      .tarjeta.color-acento-botones.p-4.mt-5
        .row.justify-content-center.mb-3.mt-5
          .col-6
            img.mtn(src='@/assets/curso/tema1/i4.svg' alt='AvatarTop')
        .row.justify-content-center
          .col-lg-8.aqw
            h4.text-center.mt-2 Evaluación
        p.text-center.mt-4.mb-5 El portafolio está todo el tiempo en evaluación constante.
      .tarjeta.color-acento-botones.p-4.mt-5
        .row.justify-content-center.mb-3.mt-5
          .col-6
            img.mtn(src='@/assets/curso/tema1/i5.svg' alt='AvatarTop')
        .row.justify-content-center
          .col-lg-8.aqw
            h4.text-center.mt-2 Selección
        p.text-center.mt-4.mb-5 Permite seleccionar los productos o servicios que trabaja la empresa.
      .tarjeta.color-acento-botones.p-4.mt-5
        .row.justify-content-center.mb-3.mt-5
          .col-6
            img.mtn(src='@/assets/curso/tema1/i6.svg' alt='AvatarTop')
        .row.justify-content-center
          .col-lg-8.aqw
            h4.text-center.mt-2 Priorización
        p.text-center.mt-4.mb-5 Da relevancia a los productos o servicios que mejor trabaja la empresa con relación a la circularidad.
      .tarjeta.color-acento-botones.p-4.mt-5
        .row.justify-content-center.mb-3.mt-5
          .col-6
            img.mtn(src='@/assets/curso/tema1/i7.svg' alt='AvatarTop')
        .row.justify-content-center
          .col-lg-8.aqw
            h4.text-center.mt-2 Balanceo
        p.text-center.mt-4.mb-5 Muestra el balance de la empresa con el medio social y medio ambiente.
      .tarjeta.color-acento-botones.p-4.mt-5
        .row.justify-content-center.mb-3.mt-5
          .col-6
            img.mtn(src='@/assets/curso/tema1/i8.svg' alt='AvatarTop')
        .row.justify-content-center
          .col-lg-8.aqw
            h4.text-center.mt-2 Autorización
        p.text-center.mt-4.mb-5 Permite autorizar a la empresa para trabajar en economía circular.
    .row.mt-4
      .col-lg-1
        img(src='@/assets/curso/tema1/ico.svg' alt='AvatarTop')
      .col-lg-11
        p Cada portafolio tiene un objetivo y debe ser identificado, evaluado, clasificado para luego ser priorizado. Luego de conocer con claridad el fin del portafolio la empresa dictamina el portafolio más indicado para invertir, el portafolio escogido debe contar con las mejores formas de cumplir los objetivos y así no tener pérdidas financieras o de tiempo en su desarrollo.
        p Los objetivos estratégicos surgen de la misión y visión que la organización tiene predeterminada. El logro de estos objetivos mueve a la organización de su estado actual al ideal para dar inicio al desarrollo de su planificación estratégica.
    separador
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2  Fondos de inversión de impacto social
    p.mb-0 Una inversión de impacto es el concepto usado en todo el mundo, para referirse a inversiones llevadas a cabo a fin de crear efecto social y medioambiental positivo, medible junto con retorno financiero, contribuyendo al desarrollo social y protección de medio ambiente. Además de abordar problemas como lo que refiere Ship2BFundation (2021) 
      span.tc1 <strong>“la inversión de impacto aborda problemas ambientales y sociales diferentes como la agricultura sostenible, vivienda asequible, salud asequible y accesible, desafíos del cambio climático y otros temas importantes que mejoren la calidad de vida entre la población”.</strong>   
      |  Este tipo de inversión está potenciando las ganas de los inversores por proyectos innovadores de alto impacto.
    .row.justify-content-center.mt-5
      .col-lg-10        
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img6.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La inversión de impacto también es una ganancia financiera ya que los costos sociales van de la mano con los beneficios financieros. Una indagación de un rendimiento financiero no califica una inversión social en una donación caritativa o una donación no reembolsable. Lo que distingue a la inversión social de la inversión tradicional es que la rentabilidad financiera está estrechamente relacionada con el desempeño social y depende del logro de los objetivos sociales: específicamente, los inversores solo recibirán productividad y rentabilidad financiera si esto se logra a eso se le puede llamar mínimo impacto social.
    p.mt-4 El impacto social debe ser medido y convertido en métricas financieras, las inversiones de impacto deben perseguir impactos que sean medibles en su proyección como se muestra en la siguiente infografía:
    .row.justify-content-center.mt-4
      .col-lg-10
        img(src='@/assets/curso/tema1/img7.svg', alt='Texto que describa la imagen')
        figcaption Imagen realizada en base a Bustamante (2016).
    .row.mt-5
      .col-lg-8
        p Las inversiones de impacto son atractivas para las empresas no solo porque buscan generar retornos financieros, sino que también por el impacto ambiental y social positivo. Estas inversiones tienen un fin transformador y se diferencian por que busca generar un cambio positivo, también evita los impactos negativos de la inversión en relación al medio ambiente y a la sostenibilidad, en Colombia como lo cuenta Daniel Uribe de AFE las empresas son cada vez más amigas de esta inversión ya que existen diferentes tipos de actores, cada uno con motivaciones, expectativas y enfoques distintos, que se articulan para crear iniciativas enfocadas a la inversión de impacto. En Colombia son 32 actores en todo el ecosistema de inversión de impacto, de estos, el 10% son fundaciones. De igual forma se tienen diversos mecanismos para ejecutar la inversión de impacto, fondos de inversión, fondos de inversión de impacto, estrategias de Blended Finance y bonos de impacto social, entre otros (2018).
      .col-lg-4 
        img(src='@/assets/curso/tema1/img8.png', alt='Texto que describa la imagen')
    p Por otro lado, las empresas mediante este tipo de inversiones buscan mejorar la relación entre la rentabilidad y el riego ya que mediante una correcta gestión de las características que se presentan en la siguiente infografía, se puede lograr sostenibilidad: 
    img(src='@/assets/curso/tema1/img9.svg', alt='Texto que describa la imagen')

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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

<style lang="sass">
.tarjeta.color-acento-botones
  background-color: #E2D9FF
.tarjeta.color-acento-botones *
  color: #12263F
.titulo-sexto.color-acento-contenido
  border-left-color:  #12263F
.tarjeta.color-acento-botones
  background-color: #FAEBCD
.bloque-texto-g.color-secundario
  background-color: #E2D9FF
</style>
