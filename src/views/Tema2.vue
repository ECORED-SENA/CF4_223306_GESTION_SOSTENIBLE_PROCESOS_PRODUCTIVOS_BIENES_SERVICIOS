<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5(data-aos="fade")
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Sellos y etiquetado sostenible  
    .row
      .col-lg-8.mt-4
        .cajon-b.color-primario.p-3.mb-5
          p.mb-0 El Sello de Sostenibilidad ha integrado progresivamente la sustentabilidad en la gestión organizacional estratégica, y su metodología ha demostrado ser útil para comprender los riesgos y beneficios de las diferentes prácticas comerciales, así como expandir esta cultura en la cadena de suministro de manera que asegura la integridad de los intercambios, también es una herramienta para ayudar a exponer las deficiencias relevantes, así como para reconocer las prácticas sostenibles de las empresas que los adquieren.
            br
            br
            | Para que una empresa reciba un sello de sostenibilidad requiere hacer el trabajo en cualquiera de las siguientes 4 categorías: origen, evolución, esencia y excelencia. La entrega del sello y su tipo se mide dependiendo del nivel de cumplimiento de los requisitos que se establecen en un cuestionario diseñado para la evaluación del grado de avance. 
      
      .col-lg-4
        img(src='@/assets/curso/tema2/img1.png', alt='Texto que describa la imagen')
    p A continuación se presenta las 4 categorías en las que están divididas el sello de sostenibilidad de Icontec, una empresa o entidad que quiera el sello deberá hacer todo el camino iniciando por el origen para llegar hasta la excelencia:
    .row.mb-5
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img2.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-4
              h4.mt-4 ORIGEN

              p Es el principio a la sostenibilidad, las entidades se comprometen y ajustan sus procesos a la sostenibilidad.
              .row.aaqws
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img3.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-4
              h4.mt-4 EVOLUCIÓN
              p.mb-5 Las entidades ya pasaron la prueba de inicio y se mantienen firmes en la creación de un modelo de negocio sostenible que sea estable.
              .row.mb-5
              .row.mb-4
              .row.aaqws
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img4.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-4
              h4.mt-4 ESENCIA
              p Luego de tener los dos primero niveles se consigue la esencia que consiste en que la entidad esté centrada en la sostenibilidad con todos los procesos medidos en su impacto.
              .row.aaqws
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img5.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-4
              h4.mt-5 EXCELENCIA
              p.mb-5 Es el nivel más alto del sello y se logra cuando las entidades están todo el tiempo buscando reducir la huella negativa que dejan en el ambiente y en el medio, por lo general son empresas de economía circular. 
              .row.aaqws
    .row.mt-4.p-3.bt2
      .col-lg-2
        img.tamq1(src='@/assets/curso/tema2/img6.svg', alt='Texto que describa la imagen')
      .col-lg-10.mt-2
        p El principio detrás de estas categorías es recopilar información sobre estándares de sostenibilidad en todo el mundo, incluido el Índice de sostenibilidad Dow Jones, ISO 26000, Pacto mundial, Iniciativa de informes globales, SR10, Sociedades BIC (colectivas y buenas), Objetivos de desarrollo sostenible, entre otros, y tema Dentro de cada uno es parte de una metodología de evaluación de cuatro frentes: orientación estratégica, económico-ética, social y ambiental (Icontec, 2022). Para postularse a un sello de sostenibilidad es necesario considerar los siguientes elementos como requisito:
    
    .row.mt-5.justify-content-center
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1. 
          span Sellos de sostenibilidad
        .tabla-b.color-acento-contenido.mb-5
          .tabla-b__header
            th.h4 Elemento 
            td.h4 <strong>Descripción</strong>
          table
            caption Nota. https://bit.ly/3QBS7Pw
            tr
              th.h5.wim Proceso de otorgamiento
              td ●	Toda la organización estará en el alcance de la certificación.
            tr
              th.h5.wim  Autoevaluación
              td ●	Plataforma de autogestión.<br>●	Mínimos de sostenibilidad.<br>●	Entrega de resultados.
            tr
              th.h5.wim  Validación y verificación
              td ●	Revisión de resultados de autoevaluación por ICONTEC.<br>●	Auditoría en sitio, remota o parcialmente remota.<br>●	Auditoría multisitio.
            tr
              th.h5.wim  Otorgamiento
              td ●	Decisión de otorgamiento.<br>●	Categorización.
    p Los sellos de sostenibilidad son un garante de beneficios para las empresas, a nivel de mercado no todas las empresas tienen estos identificativos y cada vez se harán más necesarios en busca de reducir el impacto negativo de las empresas en el ambiente; enseguida se presentan los beneficios para las empresas o entidades que los portan:
    .tarjeta.tarjeta--azul.p-4.mb-5
      SlyderA(tipo="b")
        .row.justify-content-center
          .col-lg-11.mt-5
            .row
              .col-md-4.mb-4.mb-md-0
                h4 Sostenibilidad
                p Incorporar progresivamente la sostenibilidad en la gestión estratégica de la organización.
            
              .col-md-8
                figure
                  img(src='@/assets/curso/tema2/img7.png', alt='Texto que describa la imagen')
        .row.justify-content-center
          .col-lg-11.mt-5
            .row
              .col-md-4.mb-4.mb-md-0
                h4 Riesgos y beneficios
                p Ayuda a comprender los riesgos y beneficios de las diferentes prácticas dentro de la organización.
            
              .col-md-8
                figure
                  img(src='@/assets/curso/tema2/img8.png', alt='Texto que describa la imagen')

        .row.justify-content-center
          .col-lg-11.mt-5
            .row
              .col-md-4.mb-4.mb-md-0
                h4 Cadena de valor
                p Extiende la cultura a la cadena de valor de una manera que asegura la integridad de la empresa.
            
              .col-md-8
                figure
                  img(src='@/assets/curso/tema2/img9.png', alt='Texto que describa la imagen')       
        .row.justify-content-center
          .col-lg-11.mt-5
            .row
              .col-md-4.mb-4.mb-md-0
                h4 Brechas significativas
                p Identifica brechas significativas y reconoce las prácticas de sostenibilidad de las organizaciones que lo adquieren.
            
              .col-md-8
                figure
                  img(src='@/assets/curso/tema2/za2.png', alt='Texto que describa la imagen')  
        .row.justify-content-center
          .col-lg-11.mt-5
            .row
              .col-md-4.mb-4.mb-md-0
                h4 Objetivos de Desarrollo Sostenible
                p Permite ver en qué medida los ODS (Objetivos de Desarrollo Sostenible) están incorporados en tu estrategia.
            
              .col-md-8
                figure
                  img(src='@/assets/curso/tema2/img11.png', alt='Texto que describa la imagen')   
        .row.justify-content-center
          .col-lg-11.mt-5
            .row
              .col-md-4.mb-4.mb-md-0
                h4 Resultados de evaluación
                p Tiene acceso a una plataforma de asesoramiento detallado y personalizado de los resultados de tu evaluación (Power BI).
            
              .col-md-8
                figure
                  img(src='@/assets/curso/tema2/img12.png', alt='Texto que describa la imagen')   
    .row.mt-4
      .col-lg-1
        img.tamq1(src='@/assets/curso/tema2/img13.svg', alt='Texto que describa la imagen')   
      .col-lg-11.mt-2
        p Además de Icontec que es una de las empresas que certifica los sellos en Colombia se pueden obtener sellos de calidad con otras empresas y otros tipos de sellos que cumplen con los requisitos necesarios de sostenibilidad, estos sellos son nacionales o internacionales y se presentan como una solución a la globalización logrando identificar las empresas que los cumplen. La conciencia sostenible cada vez va en aumento, esto hace que los empresarios del mundo quieran contratar cada vez más con empresas sostenibles porque saben que sus materias primas, insumos y productos elaborados están preocupados por dejar la menor huella negativa para el mundo.
    .row.mt-4.bg3.p-4.align-items-center
      .col-lg-2
        img.tam(src='@/assets/curso/tema1/i1.svg', alt='Texto que describa la imagen')
      .col-lg-8
        p.mb-0.text-white Si quiere saber más de estos sellos revise el documento que se encuentra en el material complementario con el nombre Sellos y certificaciones de sostenibilidad. Icesi (2021).
      .col-sm-auto
        a.boton.color-acento-botones(:href="('https://www.icesi.edu.co/centros-academicos/images/Centros/Kairos/Archivos/sistesis-sellos.pdf')" target="_blank")
          span Ir a enlace    
    p.mt-3 Los diferentes sellos de sostenibilidad tienen los mismos objetivos en común y todos buscan ser duraderos en el tiempo, esos objetivos son:
    .row.mb-5.justify-content-center
      .col-lg-3.mb-3.col-md-6.col-9
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img.p-2.aaw(src='@/assets/curso/tema2/1.png' alt='AvatarTop' style='width:300px')
          .tarjetas-up_card_2.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0.text-center.mb-4  Impacto ambiental
            
            p.text-center Minimizar el impacto ambiental negativo del proceso de fabricación, tanto en el sitio como en la fábrica, en el medio ambiente (incluida la protección del equilibrio del ecosistema, la reducción de contaminantes durante la producción), etc.
      .col-lg-3.mb-3.col-md-6.col-9
        .tarjetas-up
          img.p-2.aaw(src='@/assets/curso/tema2/2.png' alt='AvatarTop' style='width:300px')
          .tarjetas-up_card_2.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0.text-center.mb-4  Uso de productos
            
            p.text-center Minimizar el uso de productos que puedan dañar la salud de los consumidores, los fabricantes o el ecosistema.
      .col-lg-3.mb-3.col-md-6.col-9
        .tarjetas-up
          img.p-2.aaw(src='@/assets/curso/tema2/3.png' alt='AvatarTop' style='width:300px')
          .tarjetas-up_card_2.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0.text-center.mb-4 Productos modificados genéticamente
          
            p.text-center Minimizar el uso de productos modificados genéticamente.
      .col-lg-3.mb-3.col-md-6.col-9
        .tarjetas-up
          img.p-2.aaw(src='@/assets/curso/tema2/4.png' alt='AvatarTop' style='width:300px')
          .tarjetas-up_card_2.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0.text-center.mb-4 Respeto por los animales

          
            p.text-center Evitar dolor innecesario a los animales, respetarlos en el proceso de reproducción natural.
                
    separador
    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1  Beneficios tributarios para productos sostenibles 
    .row
      .col-lg-8
        p.mb-0 En Colombia, los productos relacionados con prácticas que ayuden a salvaguardar el medio ambiente son tenidos en cuenta para beneficios tributarios, beneficios que ayudan a las empresas directamente al ahorro de dinero; esto se prueba una vez que se acogen a los incentivos consignados en los Estatutos Tributarios que da el Ministerio de Ambiente y Desarrollo Sustentable, mediante la inversión en conjuntos o recursos que minimicen el efecto ambiental negativo en sus operaciones. El MinAmbiente (2022) en sus beneficios tributarios relata que
          span.tc01 <strong>“entre los beneficios están los descuentos y exenciones sobre impuesto de IVA y renta, y la exención de derechos arancelarios”</strong>   
          |  que sumados son una gran parte de la carga tributaria de las empresas.
        p.mt-4 De manera general se presentan los beneficios para las empresas que apliquen por sostenibilidad; sin embargo, la invitación es a que los contadores de cada empresa sean quienes estén al tanto de las novedades porque cada empresa depende de su figura jurídica legal para acceder al descuento tributario. En la siguiente tabla se presentan dichos beneficios:        
      .col-lg-4
        img(src='@/assets/curso/tema2/img14.png', alt='Texto que describa la imagen')   
    .titulo-sexto.color-acento-contenido.mt-4
      h5 Tabla 2. 
      span Beneficios tributarios de productos sostenibles
    .tabla-b.color-acento-contenido.mb-5
      .tabla-b__header.pqa
      table
        caption Nota. Adaptado de MinAmbiente (2022).
        tr
          th.h5 Equipos y elementos que no pagan IVA
          td Adquisición de equipos y elementos para sistemas de monitoreo y control ambiental, importación de equipos para reciclaje y tratamiento de basura, filtrado y tratamiento de aguas servidas, emisiones o residuos sólidos, y para otros proyectos. Los proyectos para reducir las emisiones de gases de efecto invernadero, así como los equipos para convertir vehículos a gas natural no están sujetos al IVA. El ahorro para los empresarios es del 16% del valor de la compra de equipos (Artículos 424-5 numeral 4 y 428 letras “f” e “i” del Código Tributario).
        tr
          th.h5 Deducción en la base de impuesto a la renta
          td El valor de la inversión en control y mejoramiento ambiental puede ser deducido de la base de ingresos hasta un monto que no exceda el 20% de los ingresos netos (Artículo 158-2 del Código Tributario Colombiano).
        tr
          th.h5 Rentas exentas
          td Están exentos del pago del impuesto sobre la renta, la venta de energía generada a partir de recursos eólicos, biomasa o subproductos agrícolas que reduzcan las emisiones de gases de efecto invernadero y la venta de certificados de reducción de emisiones de CO2, así como las rentas por servicios energéticos ecoturísticos (Artículos 207-2) N°1 y N°5 del Código Tributario Colombiano.
    .row.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img15.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Estos incentivos buscan promover la innovación en las empresas que ayuden a combatir contra el calentamiento global generando ganancias en el beneficio de su comercialización ya que se premia su aporte a la sociedad; es por eso que el Estado incita a una economía circular donde cada vez más empresas se sumen al cuidado del medio ambiente y generar una economía sostenible a raíz de una economía circular. El tema del medio ambiente en la actualidad es algo que se ha hecho de gran importancia, es por eso que el gobierno motiva a las grandes y medianas empresas a ser parte del cambio innovando y aportando a la economía.
        p.mt-4 Al igual que las empresas, los ciudadanos también pueden recibir beneficios por el cuidado ambiental, este es el caso de los vehículos eléctricos que en varias ciudades tienen excepción de impuestos y libertad de movilidad en caso de que la ciudad tenga restricción, en el caso de las ciudades que tienen “pico y placa”.
    separador
    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2  Ecoinnovación
    .row
      .col-lg-5
        img(src='@/assets/curso/tema2/img16.png', alt='Texto que describa la imagen')   
      .col-lg-7.mt-2
        p EcoInnovación se refiere a la innovación ambiental, como la palabra lo indica, es cualquier forma de innovación que coopere con el desarrollo sostenible, reduzca el impacto ambiental y mejore el uso de los recursos. En términos de innovación, la innovación ambiental implica la construcción de productos y procesos que reduzcan la degradación ambiental. Desde una perspectiva económica, la innovación ambiental espera que las organizaciones hagan un buen uso de los recursos naturales para mejorar la paz humana.
        p Los objetivos que se plantean en la ecoinnovación apuntan al desarrollo de nuevas ideas que se puedan implementar en la economía aprovechando al máximo los recursos naturales actuales mientras los cuidan, en este caso se pueden usar tecnologías que defiendan el sostenible. 
    p Con relación a la ecoinnovación se ha trabajado mucho en los últimos años logrando por parte de la Unión Europea establecer el Plan de Acción sobre Ecoinnovación (2011) que promulga 7 acciones básicas para estructurar las acciones a tomar de parte de las empresas y los Estados, estas 7 acciones se presentan a continuación:
    TabsA.color-acento-contenido.mb-5

      .tarjeta.color-acento-botones--borde.p-4(titulo="Política")
        .row.justify-content-center
          .col-lg-11
            .row.justify-content-center
              .col-lg-8
                h4 Política
                p La innovación ambiental debe ser un componente principal del proceso de revisión legislativa de la comunidad.
              .col-lg-4
                img(src='@/assets/curso/tema2/img17.png', alt='Texto que describa la imagen')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Proyecto")
        .row.justify-content-center
          .col-lg-11
            .row.justify-content-center
              .col-lg-8
                h4 Proyecto
                p Ayudar a que las tecnologías ambientales innovadoras pasen del laboratorio al mercado.
              .col-lg-4
                img(src='@/assets/curso/tema2/img18.png', alt='Texto que describa la imagen')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Estándares")
        .row.justify-content-center
          .col-lg-11
            .row.justify-content-center
              .col-lg-8
                h4 Estándares
                p Definición de estándares y parámetros en las áreas de tratamiento de residuos, gestión del agua o eficiencia energética.
              .col-lg-4
                img(src='@/assets/curso/tema2/img19.png', alt='Texto que describa la imagen')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Financiación")
        .row.justify-content-center
          .col-lg-11
            .row.justify-content-center
              .col-lg-8
                h4 Financiación
                p La Comisión establecerá una red de patrocinadores de la innovación medioambiental en Europa, así como mecanismos de financiación específicos para ayudar a las empresas a trabajar en I+D “verde”.
              .col-lg-4
                img(src='@/assets/curso/tema2/img20.png', alt='Texto que describa la imagen')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Cooperación")
        .row.justify-content-center
          .col-lg-11
            .row.justify-content-center
              .col-lg-8
                h4 Cooperación
                p Apoyo al establecimiento de empresas europeas en economías emergentes.
              .col-lg-4
                img(src='@/assets/curso/tema2/img21.png', alt='Texto que describa la imagen')
      .tarjeta.color-acento-botones--borde.p-4(titulo="Habilidades")
        .row.justify-content-center
          .col-lg-11
            .row.justify-content-center
              .col-lg-8
                h4 Habilidades
                p Acelere la transición a una economía circular equipando a los trabajadores del mañana con las habilidades que necesitan.
              .col-lg-4
                img(src='@/assets/curso/tema2/img22.png', alt='Texto que describa la imagen')
      .tarjeta.color-acento-botones--borde.p-4(titulo="IPE ")
        .row.justify-content-center
          .col-lg-11
            .row.justify-content-center
              .col-lg-8
                h4 IPE 
                p Innovation <i>Partnership Europe</i> son las iniciativas que reúnen a agentes públicos y privados en sectores clave donde la innovación ambiental puede ayudar a mejorar la eficiencia y la productividad.
              .col-lg-4
                img(src='@/assets/curso/tema2/img23.png', alt='Texto que describa la imagen')
    p La ecoinnovación es muy importante para la sociedad actualmente, lleva al desarrollo de nuevas fuentes de energías que buscan brindar soluciones a los problemas actuales que van deteriorando con el planeta, es por eso que hoy en día la gran mayoría de proyectos tienen que ver con el medio ambiente ya que son los que más se tienen en cuenta y son beneficiados tributariamente por el gobierno ayudando a crecer, estas ideas que contribuyen a una mejor eficiencia y productividad en los emprendedores.
    .row.mt-4.bg3.p-4.align-items-center
      .col-lg-2
        img.tam(src='@/assets/curso/tema1/i1.svg', alt='Texto que describa la imagen')
      .col-lg-8
        p.mb-0.text-white Para ampliar el tema sobre la ecoinnovación, se recomienda ver el video sobre: “Eco-Innovación.” Que se encuentra en el material complementario de este componente formativo.
      .col-sm-auto
        a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=44fzIv7nYdM')" target="_blank")
          span Ir a enlace    
    separador
    #t_2_3.titulo-segundo.color-acento-contenido
      h2 2.3  Ecodiseño
    .row
      .col-lg-8.mt-4
        p El ecodiseño se basa en integrar criterios del medio ambiente en la etapa de concepción y desarrollo de cada producto, procurando tomar medidas preventivas con el propósito de reducir los impactos del medio ambiente en las distintas etapas de su periodo de vida. 
        p El ecodiseño es una parte importante de la economía circular, un esquema que intenta prolongar el costo de los productos indefinidamente manteniéndolos en un ciclo cerrado independiente de los desechos. El ecodiseño permite el uso de materiales sostenibles para bienes en una economía circular para completar su historial de rendimiento en una nueva ubicación funcional, a diferencia de una economía lineal que se basa en la iniciación, el uso y la eliminación de la comercialización.
      .col-lg-4
        img(src='@/assets/curso/tema2/img24.png', alt='Texto que describa la imagen')
    p.mt-3 Las características que se busca tener en un producto de ecodiseño son las siguientes:
    .row.bg4
      .col-lg-11
        img(src='@/assets/curso/tema2/img25.svg', alt='Texto que describa la imagen')
    p.mt-3 Una de las características más importantes de un producto de ecodiseño es el mensaje que transmite, el cual debe ser ecológico, de tal forma que genere conciencia ambiental en el usuario, quien al hacer compra y uso de ese producto debe sentir que está salvando el mundo.
    p El ecodiseño tiene que ver con el diseño sostenible, el cual tiene su propia normativa, las normas más comunes de ecodiseño a nivel global son las siguientes:
    .row.mb-5.justify-content-center
      .col-lg-4.mb-3.col-md-8
        .tarjetas-up(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          img.aaw(src='@/assets/curso/tema2/img26.png' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0.text-center.mb-4  Cradle to Cradle (C2C)
            
            p.text-center Cradle to cradle se puede definir como el diseño y producción de productos de todo tipo de tal manera que al final de su vida, puedan ser verdaderamente reciclados (upcycled), imitando el ciclo de la naturaleza con todo reciclado o devuelto a la tierra, directa o indirectamente a través de los alimentos, como un completamente seguro y no tóxico.
      .col-lg-4.mb-3.col-md-8
        .tarjetas-up
          img.aaw(src='@/assets/curso/tema2/img27.png' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0.text-center.mb-4  ISO 14062
            
            p.text-center Gestión ambiental — Integración de los aspectos ambientales en el diseño y desarrollo de productos.
      .col-lg-4.mb-3.col-md-8
        .tarjetas-up
          img.aaw(src='@/assets/curso/tema2/img28.png' alt='AvatarTop' style='width:400px')
          .tarjetas-up_card.bg--2-claro.p-4
            .title.d-flex.align-items-center.mb-4
              span.c--4
                i.fas.fa-caret-up.fa-2x.color-primario.me-3
                i.fas.fa-caret-down.fa-2x.color-primario.me-3
              h4.mb-0.text-center.mb-4 ISO 14001
          
            p.text-center Norma de sistemas de gestión que especifica los requisitos para la formulación y mantenimiento de un SGA. Ayuda a controlar los aspectos ambientales, reducir impactos y asegurar el cumplimiento legal.
    
    p.mt-2 Estas normas son las que velan por el ecodiseño en el mercado, son las encargadas de vigilar el producto y ofrecerle garantía evaluando y acreditando el trabajo de cada empresa con los productos. Además, el ecodiseño tiene los siguientes beneficios exponenciales:
    .row.bg5.align-items-center
      .row.align-items-center
        .col-lg-9
          .row.align-items-center
            .col-lg-2.col-2
              img.mt-4.wima(src='@/assets/curso/tema2/e4.svg', alt='Texto que describa la imagen')
            .col-lg-10.col-10
              .row.cr.p-2.mt-4
                h5 Artículos de mayor calidad:
                p.mb-2 Los productos son de mejor calidad porque su desarrollo es mayor.
          .row.align-items-center
            .col-lg-2.col-2
              img.mt-4.wima(src='@/assets/curso/tema2/e1.svg', alt='Texto que describa la imagen')
            .col-lg-10.col-10
              .row.cr.p-2.mt-4
                h5 Reducción de emisiones:
                p.mb-2 El consumo durante el transporte disminuyó y, en consecuencia, las emisiones de CO2.
          .row.align-items-center
            .col-lg-2.col-2
              img.mt-4.wima(src='@/assets/curso/tema2/e2.svg', alt='Texto que describa la imagen')
            .col-lg-10.col-10
              .row.cr.p-2.mt-4
                h5 Industrias más sostenibles:
                p.mb-2 Las empresas ganan en capacidad de innovación y refuerzan su compromiso con el medio ambiente.
          .row.align-items-center
            .col-lg-2.col-2
              img.mt-4.wima(src='@/assets/curso/tema2/e3.svg', alt='Texto que describa la imagen')
            .col-lg-10.col-10
              .row.cr.p-2.mt-4
                h5 Producción más eficiente:
                p.mb-2 Favorece el ahorro de energía y requiere de menos recursos naturales y materias primas.
          .row.align-items-center
            .col-lg-2.col-2
              img.mt-4.wima(src='@/assets/curso/tema2/e4.svg', alt='Texto que describa la imagen')
            .col-lg-10.col-10
              .row.cr.p-2.mt-4
                h5 Consumidores más fáciles:
                p.mb-2 Satisface la demanda del mercado con productos más atractivos para el público cada vez más exigente.
          .row.align-items-center
            .col-lg-2.col-2
              img.mt-4.wima(src='@/assets/curso/tema2/e5.svg', alt='Texto que describa la imagen')
            .col-lg-10.col-10
              .row.cr.p-2.mt-4
                h5 Diferenciación en el mercado:
                p.mb-2 Los productos sostenibles cuentan con un valor añadido que lo distinguen de la competencia.


        .col-lg-3
          img.tamq1(src='@/assets/curso/tema2/img29.svg', alt='Texto que describa la imagen')
    .row.bg3.p-4.align-items-center
      .col-lg-2
        img.tam(src='@/assets/curso/tema1/i1.svg', alt='Texto que describa la imagen')
      .col-lg-8
        p.mb-0.text-white Para ampliar el tema sobre el ecodiseño, se recomienda ver el video sobre: “¿Qué es el ecodiseño? (2020)<br>que se encuentra en el material complementario de este componente formativo.
      .col-sm-auto
        a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=MbaZdkHTBWU')" target="_blank")
          span Ir a enlace        
    separador
    #t_2_4.titulo-segundo.color-acento-contenido
      h2 2.4  Biodegradabilidad
    .row
      .col-lg-5
        img(src='@/assets/curso/tema2/img30.png', alt='Texto que describa la imagen')

      .col-lg-7.mt-2
        p Cuando se habla de la biodegradabilidad, se refiere a la capacidad que posee un producto en sus materiales y sustancias al descomponerse formando parte de un periodo natural de la vida en la tierra con base al carbono. La biodegradación depende mucho de elementos de la naturaleza ya que aquellos productos biodegradables que se ven en el mercado hoy en día están compuestos por materiales como lo son la paja, la madera, hojas y otros elementos más que permiten que el producto tenga un ciclo en el cual después se descomponga en microorganismo ayudando así a que no aumente la contaminación en el medio ambiente.
        p La biodegradación está influenciada por la naturaleza química de la sustancia, o material que se quiere biodegradar, y por el ambiente de biodegradación. Los ambientes del compostaje y de la digestión anaeróbica favorecen un ritmo elevado de biodegradación a nivel industrial.
        .row.p-1.cg
          p Estos productos comparten siempre las mismas características al descomponerse volviendo así de forma natural a su compuesto químico principal, es ahí donde se da el fenómeno de biodegradabilidad puesto que algunos productos están hechos de compuestos químicos de muy larga vida como la mayoría de los plásticos o el icopor que son a base de polímeros. Los productos hechos en base a materiales naturales tienen vidas menos largas luego de ser desechados, por ejemplo, el cartón a base de madera.
    p.mt-4.mbn Para tener mayor claridad del impacto de los productos en el medio ambiente los investigadores han trabajado en descubrir los tiempos en los que se degrada cada uno de los materiales con los que se trabaja habitualmente la fabricación de productos, tenga en cuenta la siguiente información para la elección de la materia prima de trabajo en sus productos, esta información es basada en <i>Efimarket</i> (2017):
    .row.justify-content-center.bg6
      .col-lg-11
        .row.mt-5
        .row.mt-5
        LineaTiempoE.color-primario
          .row(titulo="4 semanas" subtitulo="Orgánicos ")
            .col-lg-5
              figure
                img(src='@/assets/curso/tema2/img31.png', alt='Texto que describa la imagen')
            .col-lg-7.mb-4.mb-lg-0.mt-4
              p Los desechos y residuos orgánicos tardan tan sólo 4 semanas en degradarse, además de servir como abono para muchas plantas. Este tiempo de descomposición es real siempre que nuestros residuos no lleven productos tóxicos o químicos.
          .row(titulo="1 año" subtitulo="Papel, cartón ")
            .col-lg-5
              figure
                img(src='@/assets/curso/tema2/img32.png', alt='Texto que describa la imagen')
            .col-lg-7.mb-4.mb-lg-0.mt-4
              p El papel y el cartón, al estar compuesto básicamente por celulosa, no supone un gran problema para la naturaleza, y su tiempo de descomposición es escaso. Además, si el ambiente es lluvioso y se encuentra en la superficie, su biodegradación se acelera. 
          .row(titulo="10 años" subtitulo="Aluminio")
            .col-lg-5
              figure
                img(src='@/assets/curso/tema2/img33.png', alt='Texto que describa la imagen')
            .col-lg-7.mb-4.mb-lg-0.mt-2
              p Son los años que tarda la naturaleza en convertir una lata de refresco o cerveza en óxido de hierro, lo cual además de ser un tiempo considerable, es peligroso. Estas latas de aluminio están recubiertas de otros materiales, como el estaño y el barniz, lo que ralentiza su biodegradación, al necesitar de mucha humedad para iniciar su proceso de descomposición.
          .row(titulo="150 años" subtitulo="Plástico")
            .col-lg-5
              figure
                img(src='@/assets/curso/tema2/img34.png', alt='Texto que describa la imagen')
            .col-lg-7.mb-4.mb-lg-0.mt-2
              p Las bolsas de plástico, fabricadas con polietileno de baja densidad, tardan más de un siglo en descomponerse totalmente. La buena noticia es que ya existen alternativas, como las bolsas de fécula de papa entre otras. Sin embargo, las botellas de plástico pueden tardar en degradarse hasta 1000 años si permanecen enterradas.
          .row(titulo="4.000 años" subtitulo="Vidrio")
            .col-lg-5
              figure
                img(src='@/assets/curso/tema2/img35.png', alt='Texto que describa la imagen')
            .col-lg-7.mb-4.mb-lg-0.mt-2
              p Para los microorganismos del suelo es muy difícil realizar su descomposición, sea cual sea las dimensiones y las formas (como botellas de vidrio, vasos, gafas de cristal, etc…). El vidrio debe ser reciclado para este fin o su huella es casi eterna.
        .row.mb-5
        .row.mb-5
        .row.mb-5
        separador
    #t_2_5.titulo-segundo.color-acento-contenido
      h2 2.5  Impacto ambiental positivo
    p El impacto ambiental positivo hace referencia a toda aquella actividad que beneficia al medio ambiente ayudando a mejorar o corregir los efectos negativos ambientales que se han generado en la actualidad. Los impactos ambientales positivos se pueden dar a través de diferentes formas naturalmente como lo son:
    .row.mb-5
      .col-md-4.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img.aqq(src='@/assets/curso/tema2/e6.svg' alt='AvatarTop')
          .tarjeta.color-primario.a1
            .p-2
              h5.text-center Reforestación 
      .col-md-4.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img.aqq(src='@/assets/curso/tema2/e7.svg' alt='AvatarTop')
          .tarjeta.color-acento-botones.a2
            .p-2
              h5.text-center Tratamiento de agua residuales
      .col-md-4.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img.aqq(src='@/assets/curso/tema2/e8.svg' alt='AvatarTop')
          .tarjeta.color-acento-contenido.a3
            .p-2
              h5.text-center Reciclaje
      .col-md-4.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img.aqq(src='@/assets/curso/tema2/e9.svg' alt='AvatarTop')
          .tarjeta.color-acento-contenido.a4
            .p-2
              h5.text-center.mb-5 Uso de energías renovables
    .row.mt-4 
      .col-lg-8
        p Cuando se hace referencia sobre el impacto de la economía en el medio ambiente se logra una visión de la economía actual, gracias a las nuevas economías que se han ido desempeñando he implementado para el cuidado del medio ambiente como lo son los productos biodegradables y la economía circular, estas innovaciones dan un impacto económico positivo al medio ambiente aportando soluciones al medio ambiente en temas de reciclaje y disminución de la contaminación.
        p La energía renovable es una de las ideas más innovadoras y perseguidas por los inversionistas que buscan hacer miles de proyectos realidad, ya que las energías renovables son las que más aportan al planeta en su cuidado puesto que busca crear energías con elementos naturales que no expongan a otros elementos esenciales de los cuales se puedan dañar, uno de estos ejemplos es el petróleo, su proceso siempre pone en peligro la tierra y las aguas por su alta tasa de crudo contamina lo que va tocando. En la actualidad, la biomasa ha tenido un gran impacto positivo con el medio ambiente al ser el competidor natural del petróleo, es por eso que se han planteado cantidades de proyectos en busca de ir reemplazando con el paso de los años, el petróleo por la biomasa.
      .col-lg-4
        img(src='@/assets/curso/tema2/img36.png' alt='AvatarTop')
      p Para que una idea de negocio tenga un buen impacto positivo en el ambiente se debe tener en cuenta lo siguiente:
    .row.bg7.mt-4.justify-content-center
      .col-lg-8
        img(src='@/assets/curso/tema2/img37.svg' alt='AvatarTop')

</template>

<script>
export default {
  name: 'Tema2',
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
.cajon-b.color-primario:before
  background-color: #E2D9FF
.tarjeta-flip.color-primario .tarjeta-flip__contenido
  background-color: #E9D6B0
.tarjeta-flip.color-primario .tarjeta-flip__img
  background-color: transparent
.tarjeta--azul
  background-color: #FCF4E4
.slyder-a__btn--sigt, .slyder-a__btn--atrs
  background-color: #8CBE9C
.slyder-a__bullets__item--active
  background-color: #EF8B53!important
  border-color: #EF8B53
.slyder-a__bullets__item
  background-color: #F8D6C0
.tabs-a__tab
  background-color: #E8E8E8
.tarjeta.color-acento-botones--borde
  background-color: #F3EDFF
  border: solid 4px #E3D8FF
.tarjeta-avatar > img
  width: 100px
.bloque-texto-g.color-secundario
  background-color:  #EF8B53
.tarjeta-avatar
  width: 250px
.tarjeta-avatar .tarjeta
  width: 300px
  @media screen and ( max-width: 992px)
    width: 200px
.tarjeta-avatar > img
  @media screen and ( max-width: 992px)
    left: 40%
</style>
