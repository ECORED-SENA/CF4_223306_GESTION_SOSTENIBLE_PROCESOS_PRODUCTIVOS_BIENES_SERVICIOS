<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade")
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Tipos de programas
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 El Gobierno Nacional de Colombia ha establecido diversos programas de ahorro y uso eficiente del agua y también, de eficiencia energética con el fin de conservar los recursos naturales del país, el Estado es el mayor interesado en cuidar estos recursos porque los ciudadanos pueden contar con estos recursos sin preocupación. Los programas de ahorro establecen parámetros, métodos y modelos de gestión para las empresas y ciudadanos que propendan por el cuidado de los recursos naturales. 
    separador
    #t_4_1.titulo-segundo.color-acento-contenido
      h2 4.1  Programas de ahorro y uso eficiente del agua
    .row
      .col-lg-8
        p Las entidades encargadas de gestionar los recursos hídricos para grandes usuarios, acueductos urbanos, puentes verdes y pequeños usuarios, son responsables de entregar un programa de uso eficiente y económico para la conservación del agua según lo establece la Ley 373 en 1997, el objetivo de la ley es la de establecer actividades para asegurar la conservación y protección de los recursos hídricos.
        .cajon.color-acento-botones.p-4.mb-4
          p Un programa es un mecanismo de planificación sistemática para mantener el suministro de agua existente en un área determinada para satisfacer la demanda de agua requerida por la población de acuerdo con la situación ambiental actual. 
        p El programa de “Economía y uso efectivo del agua” incluye una serie de subprogramas que posibilitan el desarrollo de planes y estrategias con el objetivo de desarrollar protocolos para la gestión del recurso hídrico: educación ambiental, medición, aprovechamiento y reutilización de aguas pluviales y bajo consumo; también trabaja las tecnología y áreas de especial manejo, incentivos o penalizaciones. 
      .col-lg-4
        img(src='@/assets/curso/tema4/img2.png', alt='Texto que describa la imagen')
    .row.mt-4.bg3.p-4.align-items-center
      .col-lg-2
        img.tam(src='@/assets/curso/tema1/i1.svg', alt='Texto que describa la imagen')
      .col-lg-8
        p.mb-0.text-white Para ampliar el tema sobre Programas de ahorro y uso eficiente del agua, se recomienda ver el video sobre: “Ahorro y uso eficiente del Agua” que se encuentra en el material complementario de este componente formativo.
    
    .row.bg8
      .row.mt-3
        .col-lg-4
          img(src='@/assets/curso/tema4/img3.png', alt='Texto que describa la imagen')

        .col-lg-8
          p También se encuentra el PUEEA (Programa para la Eficiencia y Conservación del Agua), este documento explica el funcionamiento y la disponibilidad del recurso hídrico en el tiempo. Este programa trabaja una concesión legal de agua para una población determinada cuando se requiera. Este documento es uno de los requisitos que se deben presentar y cumplir para solicitar la prórroga de las concesiones de agua y en las decisiones de concesión requeridas. Además, todas las personas naturales o jurídicas que operen una concesión de agua deben presentar un documento PUEEA.
          p En la siguiente gráfica se puede ver la normatividad que sustenta el PUEEA en Colombia:
      .row.justify-content-center.mt-4
        .col-lg-10
          .titulo-sexto.color-acento-contenido
            h5 Tabla 2. 
            span Beneficios tributarios de productos sostenibles       
          img(src='@/assets/curso/tema4/img4.svg', alt='Texto que describa la imagen')
          figcaption Nota. https://bit.ly/3QPY8bz
    .row.mt-4
      .col-lg-7
        p Algunos otros proyectos que trabajan la regulación del recurso hídrico son los siguientes:
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.justify-content-center(titulo="Zonas de manejo especial")
            .col-md-10.mb-4.mb-md-0
              p El proyecto tiene como objetivo proteger áreas con pantanos, bosques nubosos y áreas afectadas por los acuíferos de quebradas y ríos con prioridad.
          
          .row.justify-content-center(titulo="Reducción de pérdidas")
            .col-md-10.mb-4.mb-md-0
              p Las actividades y objetivos están integrados para reducir pérdidas en el sistema de agua. Por ejemplo, cambio de tubería, mantenimiento de redes y otros.
          .row.justify-content-center(titulo="Uso de aguas lluvias y reúso de aguas")
            .col-md-10.mb-4.mb-md-0
              p Este proyecto se enfoca en implementar actividades que mejoren la recolección de agua de lluvia y fomenten la reutilización del agua en áreas residenciales y en la red de agua.
          .row.justify-content-center(titulo="Tecnologías de bajo consumo")
            .col-md-10.mb-4.mb-md-0
              p Tiene como objetivo promover e implementar acciones a favor de la implementación de dispositivos, sistemas y herramientas de bajo consumo de agua que promuevan el uso eficiente y económico del agua en la red de abastecimiento de agua terrestre Acuerdo entre usuarios.
          .row.justify-content-center(titulo="Incentivos tarifarios, tributarios y sanciones")
            .col-md-10.mb-4.mb-md-0
              p Definen herramientas que establecen lineamientos en las normas de plomería para promover el uso eficiente y económico de los recursos hídricos y evitar la infrautilización.
      
      .col-lg-5
        img(src='@/assets/curso/tema4/img5.png', alt='Texto que describa la imagen')
    p.mt-2 Además de proyectos de regulación se encuentran otros proyectos como los de disponibilidad del recurso hídrico y el ahorro y uso del recurso hídrico como se ven a continuación:
    .row.justify-content-center.mt-4
      .col-lg-10
        .row
          .col-lg-6
            img(src='@/assets/curso/tema4/img6.svg', alt='Texto que describa la imagen')
            .row.p-3.bacz
              h4 Proyecto de medición
              p Es un proyecto para realizar actividades que faciliten la medición del consumo o uso de agua en el sistema de abastecimiento de agua, con el objetivo de lograr actividades de ahorro en la red y en el hogar del consumidor. Estas son mediciones realizadas con instrumentos como micrómetros y calibres.
            
          .col-lg-6
            img(src='@/assets/curso/tema4/img7.svg', alt='Texto que describa la imagen')
            .row.p-3.bacz2
              h4 Educación ambiental
              p El objetivo de este proyecto es incluir campañas educativas, actividades y capacitación para promover el uso racional y eficiente del agua. Es un proyecto de transición para otros.
              .row.mb-5
              .row.mb-4
    separador
    #t_4_2.titulo-segundo.color-acento-contenido
      h2 4.2  Programas de eficiencia energética
    .row.mt-4.p-3.bt2
      .col-lg-2
        img(src='@/assets/curso/tema4/img8.svg', alt='Texto que describa la imagen')
      .col-lg-10.mt-4
        p Los Programas de Caracterización del Consumo de Energía y Eficiencia Energética implementados por la UPME (Unidad de Planificación Energética Mineral) tienen como objetivo promover el desarrollo de políticas públicas para mejorar el uso de los recursos y la energía, y finalmente recomendaciones sobre fuentes de energía adecuadas. Estos programas tienen varios objetivos, como se puede ver a continuación:
    .col-lg-5.mt-4.bha.p-1
      h4.mt-1 Primer balance de energía útil para Colombia (BEU) – 2018
    .row.mt-3
      .col-lg-1
        img(src='@/assets/curso/tema4/img9.svg', alt='Texto que describa la imagen')
      .col-lg-11
        p El Balance Energético Beneficioso (BEU) es un programa que mide el daño económico causado por tecnología obsoleta, prácticas ineficientes y baja volatilidad de la matriz energética nacional en 2015. Los sectores estudiados son residencial, industrial, transporte, comercial y público. En cuanto al cálculo de ineficiencias, se evalúan las características de los equipos existentes frente a la mejor tecnología disponible (BAT), tanto a nivel nacional como internacional.
    p.mt-1 El BEU determinó que las pérdidas por ineficiencia energética ascendieron a aproximadamente $6.700 millones en comparación con los equipos actualmente en uso con BAT en Colombia y $11.000 millones con BAT a nivel internacional como se puede ver en la siguiente figura:
    .row.mt-4.justify-content-center
      .col-lg-10
        img(src='@/assets/curso/tema4/img10.svg', alt='Texto que describa la imagen')
    .col-lg-6.mt-4.bha.p-1
      h4.mt-1 Proyecto de eficiencia energética industrial en Colombia 2016-2019
    .row.justify-content-center
      .col-lg-10
        .row
          .col-lg-7.mt-4
            .cajon-b.color-primario.p-3.mb-5
              p.mb-0 El Programa de Eficiencia Energética Industrial de Colombia tiene como objetivo promover el mercado de productos y servicios energéticamente eficientes mediante el fortalecimiento de los reglamentos y normas técnicas, la creación de capacidades en los Sistemas de Gestión de Energía y Calidad (SGEn) y la mejora de los procesos. En este proyecto se evaluaron 180 industrias y se capacitaron cerca de 100 técnicos de industrias ubicadas en siete regiones del país, tales como: Cundinamarca Boyacá, Santander y Norte de Santander, Egy Cafetero, Atlántico y Valle del Cauca.
                br
                br
                | Como resultado, SGEn mide y divulga un ahorro total de optimización de 1.287 TJ/año, o 87.707,42 toneladas de CO2/año, lo que contribuye al objetivo de la industria nacional de PROURE para 2017-2022 y se estima en un 5 %. En la siguiente figura se muestra el impacto de esa implementación a nivel general Colombia:
          .col-lg-5
            img(src='@/assets/curso/tema4/img11.png', alt='Texto que describa la imagen')
    .row.justify-content-center
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 4. 
          span Impacto de la implementación de Sistemas de Gestión de Energía SGEn 
        img(src='@/assets/curso/tema4/img12.svg', alt='Texto que describa la imagen')
        figcaption Nota. https://bit.ly/3c7kOoq 
    .col-lg-5.mt-4.bha.p-1
      h4.mt-1 Programa de evaluación industrial PEVI (2018-2022).
    .row.mt-4
      .col-lg-6
        p Gracias al éxito del proyecto EEI en Colombia, UNIDO/UPME ha comenzado a darle continuidad a través de una iniciativa denominada “Programa para el Desarrollo Industrial (PEVI)” que creará y promoverá oportunidades para el uso eficiente de la energía en la industria y al mismo tiempo, formar administradores universitarios en regiones específicas del país. El PEVI consta de dos fases piloto que se implementaron en 2018 y 2019. Estas fases facilitan la generación de insumos para identificar y validar metodologías, planes y mecanismos, trabajando con universidades e industria de la región.
        p Se aplicaron 21 estudios de la industria, resultando en ahorros potenciales de energía de más del 8% gracias a buenas prácticas mínimas o sin costo. Para garantizar la continuidad y mejorar las experiencias adquiridas, se establece el establecimiento de tres Centros de Evaluación de la Industria para 2020, con un enfoque en mejorar el modelo operativo y de gestión para garantizar que se creen académicos y contribuyan a las oportunidades de eficiencia energética en las industrias impactantes en el sitio.
      .col-lg-6
        img(src='@/assets/curso/tema4/img13.png', alt='Texto que describa la imagen')
    .row.bg9.justify-content-center
      p A continuación, se enuncia la normatividad que fundamenta los programas de eficiencia energética:
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 5. 
          span Normatividad que fundamenta los programas de eficiencia energética
        img(src='@/assets/curso/tema4/img14.svg', alt='Texto que describa la imagen')
    separador
    #t_4_3.titulo-segundo.color-acento-contenido
      h2 4.3  Formulación del cálculo de los indicadores de gestión
    p Los indicadores de desempeño energético son expresiones o valores que se utilizan para monitorear y controlar cambios en el desempeño energético y reducir la pérdida de energía en cualquier proceso de generación, lo que permite a cualquier organización, establecer planes estratégicos para lograr resultados a corto, mediano y largo plazo.
    p El cálculo se hace a través de las siguientes fórmulas:
    .row.bg10
      .col-lg-5
        img(src='@/assets/curso/tema4/img15.svg', alt='Texto que describa la imagen')
      .col-lg-7
        .row
          .col-lg-11.mt-4
            img(src='@/assets/curso/tema4/img16.svg', alt='Texto que describa la imagen')
    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema4/1.svg' alt='AvatarTop')

          .tarjeta.color-primario
            .p-4
              p.text-center <strong>La energía consumida:</strong> es igual a la energía aprovecha más pérdidas. Las pérdidas son las que se deben reducir con los proyectos de eficiencia energética que impulsen a maximizar el aprovechamiento. 
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema4/2.svg' alt='AvatarTop')

          .tarjeta.color-primario
            .p-4
              p.text-center <strong>El porcentaje de pérdidas:</strong>  son las pérdidas divididas entre la energía consumida. 
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema4/3.svg' alt='AvatarTop')

          .tarjeta.color-primario
            .p-4
              p.text-center <strong>La eficiencia de procesos:</strong>   es la energía aprovechada por la energía consumida, se procura garantizar la eficiencia del proceso y reducir el porcentaje de pérdidas.

</template>

<script>
export default {
  name: 'Tema4',
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
.bloque-texto-g.color-primario
  background-color: #F7DEA7
.p-3.pb-0.p-md-4.pb-md-0.mb-3.tarjeta.tarjeta--azul.acordion__activo
  background-color: #E2D9FF
.p-3.pb-0.p-md-4.pb-md-0.mb-3.tarjeta.tarjeta--azul
  background-color: #F2F2F2
.cajon-b.color-primario:before
  background-color: #E2D9FF
.tarjeta.color-primario
  background-color: #FAEBCD
.tarjeta-avatar > img
  width: 100px
</style>
