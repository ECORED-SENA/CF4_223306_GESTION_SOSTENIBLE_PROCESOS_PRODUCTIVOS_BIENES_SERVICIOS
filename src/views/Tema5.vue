<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade")
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Sistemas de costos
    .cajon-b.color-primario.p-3.mb-5
      p.mb-0 Los sistemas de costos son un grupo de técnicas y métodos para calcular el precio de las diferentes ocupaciones de la compañía, considerando el tipo de actividad se posee la siguiente categorización de los sistemas de costos:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row.justify-content-center(titulo="Sistemas de costos según el tratamiento de los costos fijos")
        .col-md-11.mb-4.mb-md-0
          .row
            .col-lg-7
              p Los sistemas de costos tienen la posibilidad de clasificar conforme el procedimiento de los precios fijos, de acuerdo con la forma de concentración de los precios y de acuerdo con el procedimiento de precios. Los sistemas de precios de acuerdo con el procedimiento de los precios fijos tienen la posibilidad de ser: sistemas de precios por absorción y sistemas de precios cambiantes.
            .col-lg-5
              img(src='@/assets/curso/tema5/img1.png' alt='AvatarTop')
      .row.justify-content-center(titulo="Sistemas de costos según la forma de concentración de los costos")
        .col-md-11.mb-4.mb-md-0
          .row
            .col-lg-7
              p Los sistemas de costos conforme con la forma de concentración de los precios tienen la posibilidad de ser: precios por directivas y precios por procesos. Los precios por directivas se emplean una vez que hay demandas especiales de consumidores. En lo que respecta, los precios por procesos se aplican una vez que la producción es repetitiva y diversificada, aunque los artículos sean uniformes entre sí.
            .col-lg-5
              img(src='@/assets/curso/tema5/img2.png' alt='AvatarTop')
      .row.justify-content-center(titulo="Sistemas de costos según el método de costos")
        .col-md-11.mb-4.mb-md-0
          .row
            .col-lg-7
              p De acuerdo con el sistema de costeo procedimental, se encuentra: el sistema de precios históricos o de producción, el sistema de precios predeterminados. Estos últimos incluyen: el sistema de precios estimados y el sistema de precios estándar.
              p Sistemas de precios históricos o resultantes, es el precio en función de los insumos reales utilizados. En los sistemas de precios históricos existen: sistemas de guía de producción, sistemas de precios de categorías, procesos y actividades.
            .col-lg-5
              img(src='@/assets/curso/tema5/img3.png' alt='AvatarTop')
    .row.mt-4.bg3.p-4.align-items-center
      .col-lg-2
        img.tam(src='@/assets/curso/tema1/i1.svg', alt='Texto que describa la imagen')
      .col-lg-8
        p.mb-0.text-white Para ampliar el tema sobre Sistema de costo, se recomienda revisar el artículo sobre: “Diseño de Sistemas de Costeo: Fundamentos Teóricos” que se encuentra en el material complementario de este componente formativo. 
    
    separador
    #t_5_1.titulo-segundo.color-acento-contenido
      h2 5.1  Análisis costo beneficio   
    .row
      .col-lg-8.mt-4
        .cajon-b.color-primario.p-3.mb-5
          p.mb-0 El costo – beneficio es un proceso por medio del cual las empresas tienen la posibilidad de examinar elecciones, sistemas, proyectos, o establecer un costo para intangibles. El modelo se hace identificando las ventajas de una acción, así como los costes asociados y restando los costes de las ventajas. Una vez hecho el ejercicio se tiene resultados útiles que se van a poder utilizar para obtener conclusiones sobre la viabilidad o conveniencia de una elección o situación. 

            br
            br
            | La investigación de costo – beneficio es la manera de tomar elecciones fundamentadas en datos más usada por las organizaciones. Tanto en medio de las novedosas como en esas más establecidas. Los principios y las diversas fases del proceso tienen la posibilidad de utilizar básicamente cualquier proceso de toma de elecciones. No importa si está referente con el comercio o de otra tipología.
      .col-lg-4
        img(src='@/assets/curso/tema5/img4.png' alt='AvatarTop')
    .row.bg11
      p El análisis de costo beneficio se puede utilizar para:
      .row
        .col-lg-5
          img(src='@/assets/curso/tema5/img5.svg' alt='AvatarTop')

        .col-lg-7
          .row.justify-content-center
            .col-lg-7.blas
              h4.text-center.mt-2 Usos del análisis costo beneficio empresarial
          ol.lista-ol--cuadro.lista-ol--separador.mt-3
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Evaluar si una inversión de capital merece la pena.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Decidir si contratar o no nuevos empleados.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Determinar si un proyecto o cambio operativo es factible.
            li 
              .lista-ol--cuadro__vineta
                span 4
              | Desarrollar un benchmarking para comparar proyectos.
            li 
              .lista-ol--cuadro__vineta
                span 5
              | Comparar una iniciativa de marketing con otra.
            li 
              .lista-ol--cuadro__vineta
                span 6
              | Priorizar las inversiones.
            li 
              .lista-ol--cuadro__vineta
                span 7
              | Establecer metas para el proyecto en sí.
        .tabla-b.color-acento-contenido.mb-5
          .tabla-b__header
            .row
              .col-lg-6
                h4 El análisis de costo beneficio trae sus ventajas como lo son:
              .col-lg-6
                h4 Pero también trae consigo ciertas desventajas las cuales son:
          table
            tr
              td Base de datos
              td Difícil predicción de todas las variables
            tr
              td Simplificación de decisiones.
              td La fiabilidad solo se basa de los datos que tengas
            tr
              td Costes y beneficios ocultos.
              td Elimina los elementos humanos
    separador          
    #t_5_2.titulo-segundo.color-acento-contenido
      h2 5.2  Tasa de retorno 
    .row.bg12.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema5/img6.png')})`}"
          )
          .bloque-texto-g__texto.p-5
            p.mb-0 La tasa de retorno conocida como tasa de rentabilidad, es la productividad que da una inversión siendo el indicador adecuado para medir la inversión, reflejando así el margen de pérdidas o beneficios obtenidos en el periodo de tiempo que se realizó la inversión. Para medir la tasa de retorno se debe aplicar la siguiente fórmula: Tasa de rentabilidad–= [(Valor final - valor inicial) / Valor inicial] x 100
        p.mt-3 En la tasa de retorno también se encuentra la tasa interna de retorno. Cuando se habla de la tasa interna de retorno se hace referencia a una tasa porcentual que indica la rentabilidad anual que genera el proyecto. Es un instrumento más que hay para lograr evaluar un plan sin perder de vista el total del proyecto.
        p Con la tasa interna de retorno se puede saber en qué momento una inversión puede ser rentable o no y es reflejada en porcentaje. Se usa especialmente cuando se tienen varias alternativas de inversión para definir con cual opción se puede quedar la empresa sin multiplicar su riesgo. 
        p La fórmula de la tasa de retorno interna es la siguiente:
        .row.mt-4
          .col-lg-8.mt-5
            .row.colorv.p-2
              h3.text-center.text-white Tasa interna de retorno.
            .row.colorv2.p-2.aling-items-center
              .col-lg-7
                h5 Donde:
                p <strong>Qn =</strong> es el flujo de caja en el periodo n.
                p <strong>N =</strong> es el número de periodos.
                p <strong>I =</strong>  es el valor de la inversión inicial.
              .col-lg-5
                img(src='@/assets/curso/tema5/1.svg' alt='AvatarTop')

          .col-lg-4
            img(src='@/assets/curso/tema5/img7.svg' alt='AvatarTop')
    separador
    #t_5_3.titulo-segundo.color-acento-contenido
      h2 5.3  Costo anual equivalente
    .row
      .col-lg-5
        img(src='@/assets/curso/tema5/img9.png' alt='AvatarTop')
      .col-lg-7
        p Este es un porcentaje que le permite comparar diferentes alternativas que ofrecen los proveedores de productos o servicios financieros. Se utiliza para evaluar proyectos de inversión y corresponde a todos los ingresos y gastos convertidos a un monto equivalente una vez al año, el mismo para cada período. El costo anual equivalente del proyecto es el costo y los ingresos.
        p Se usa para una diversidad de fines, integrado el presupuesto de capital; sin embargo, se utiliza con más frecuencia para examinar dos o más proyectos potenciales con diferentes ciclos de vida, donde los precios son la variable más importante.
        p La fórmula que se maneja es la siguiente:
        .row.colorv.p-2
          h3.text-center.text-white Costo anual equivalente       
        .row.colorv2.p-2.justify-content-center
          .col-lg-10.mt-4
            h4.text-center CAUE o BAUE = VAN * (1+i) n*i/(1-i) n*i
            h5 Donde:
            h5 i: corresponde a la tasa de intereses.
            h5 n: corresponde al número de periodos a evaluar

</template>

<script>
export default {
  name: 'Tema5',
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
.p-3.pb-0.p-md-4.pb-md-0.mb-3.tarjeta.tarjeta--azul.acordion__activo
  background-color: #E2D9FF
.p-3.pb-0.p-md-4.pb-md-0.mb-3.tarjeta.tarjeta--azul
  background-color: #F2F2F2
.bloque-texto-g__img
  left: 50%
.bloque-texto-g__texto
  right: 40%
</style>
