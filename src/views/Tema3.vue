<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Requisitos para la implementación

    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-lg-5.mb-4.mb-lg-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La implementación efectiva de las Buenas Prácticas Agrícolas (BPA) en el cultivo de plátano requiere el cumplimiento de una serie de requisitos esenciales. Esta sección aborda los aspectos clave que deben considerarse durante las fases de planificación e implementación, incluyendo las condiciones de las instalaciones, la calidad del agua, las características del suelo, el manejo responsable de los agroquímicos y las estrategias de protección ambiental. Para cada uno de estos elementos, se presentarán las consideraciones necesarias que contribuyen a la sostenibilidad y eficiencia del proceso productivo, asegurando un equilibrio entre rentabilidad y cuidado del entorno.

    Separador

    #t_3_1(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 3.1 Instalaciones

    p.mb-4 Contar con instalaciones adecuadas permite optimizar las operaciones de recepción, lavado, secado y almacenamiento, garantizando condiciones higiénicas y seguras. A continuación, se describen los aspectos clave de cada una de estas áreas, resaltando los requisitos estructurales y funcionales necesarios para un manejo eficiente del cultivo.

    .row.align-items-center.mb-4.mb-lg-5
      .d-none.d-lg-block.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema3/2.svg', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-lg-9
        TabsA.mb-5.banana-tabs-a
          .tarjeta.bg-color-terciario.p-4.h-100.banana-tabs-a__tarjeta(titulo="Zona de recepción")
            h4 Zona de recepción de racimos
            p La zona donde se ubica el cultivo de plátano debe contar con instalaciones adecuadas para la recepción de los racimos cosechados. El área destinada a este proceso debe tener una altura suficiente que evite el contacto de los racimos con el suelo una vez colgados, garantizando así su integridad y calidad.

          .tarjeta.bg-color-terciario.p-4.h-100.banana-tabs-a__tarjeta(titulo="Tanques de lavado")
            h4 Tanques de lavado
            p Los tanques de lavado del producto deben estar diseñados con una altura ergonómica que facilite el trabajo del operario, asegurando comodidad y eficiencia en la limpieza. Además, deben estar construidos con materiales resistentes, de fácil mantenimiento y aptos para una limpieza frecuente que cumpla con los estándares de inocuidad. 

          .tarjeta.bg-color-terciario.p-4.h-100.banana-tabs-a__tarjeta(titulo="Zona de secado")
            h4 Zona de secado
            p La zona de secado debe ubicarse inmediatamente después del tanque de lavado, permitiendo una transición fluida en el proceso.

          .tarjeta.bg-color-terciario.p-4.h-100.banana-tabs-a__tarjeta(titulo="Almacenamiento")
            h4 Área de almacenamiento de cajas
            p Por su parte, el área destinada al almacenamiento de las cajas con el producto debe contar con una cubierta que impida la exposición directa a los rayos solares. Además, los pisos de este espacio deben estar elaborados con materiales que faciliten la limpieza y desinfección, asegurando condiciones higiénicas óptimas.

    h3(data-aos='zoom-in-right').mb-4
      span.banana-title.banana-title--1 Almacenaje de los insumos agrícolas

    p.mb-4 Las zonas destinadas al almacenamiento de insumos deben cumplir con las siguientes características:

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.factores-slider
      .d-none.d-xl-block.col-xl-4
        figure
          img.mb-4.mb-xl-0(src='@/assets/curso/temas/tema3/3.png', alt='Ilustración decorativa')(data-aos="fade-up")
  
      .col-xl-8.mb-3.mb-lg-0
        SlyderF(columnas="col-md-6 col-lg-4")
          .tarjeta.tarjeta--secundario-s5.p-4.rounded-3  
            h3.factores-slider__number 01
            p.mb-0 Los plaguicidas deben almacenarse por separado de los bioinsumos y fertilizantes para evitar contaminación y posibles reacciones químicas no deseadas.

          .tarjeta.tarjeta--secundario-s5.p-4.rounded-3  
            h3.factores-slider__number 02
            p Los insumos no deben ubicarse cerca de viviendas, áreas de almacenamiento de alimentos ni fuentes de agua, reduciendo así riesgos de contaminación y afectaciones a la salud.

          .tarjeta.tarjeta--secundario-s5.p-4.rounded-3  
            h3.factores-slider__number 03
            p Los insumos en canecas o sacos deben colocarse sobre estibas para prevenir contaminación, daños por humedad, roturas o contacto con el suelo.

          .tarjeta.tarjeta--secundario-s5.p-4.rounded-3  
            h3.factores-slider__number 04
            p.mb-0 Las áreas de almacenamiento deben señalizarse con letreros visibles en la entrada y mantenerse limpias, secas, bajo llave y con acceso exclusivo al personal autorizado.

          .tarjeta.tarjeta--secundario-s5.p-4.rounded-3  
            h3.factores-slider__number 05
            p Las zonas de almacenamiento deben contar con avisos que prohíban comer, beber o fumar y exijan el uso de protección. Además, el personal debe estar capacitado para emergencias.

          .tarjeta.tarjeta--secundario-s5.p-4.rounded-3  
            h3.factores-slider__number 06
            p Se debe evitar el ingreso de animales como perros, gatos, aves y roedores a las instalaciones de almacenamiento para prevenir contaminación y daños en los insumos.

    h3(data-aos='zoom-in-right').mb-4
      span.banana-title.banana-title--1 Áreas de instalaciones sanitarias 

    p.mb-4.mb-lg-5 La finca platanera debe contar con instalaciones sanitarias adecuadas para hombres y mujeres, asegurando su correcto mantenimiento, limpieza y desinfección periódica. Estos espacios son fundamentales para preservar la higiene y prevenir enfermedades en los trabajadores. Además, la zona donde se ubican los baños debe estar equipada con lavamanos funcionales y duchas, promoviendo prácticas de aseo personal que contribuyan a la seguridad y bienestar del equipo de trabajo. Asimismo, es recomendable que los sanitarios estén debidamente señalizados y cuenten con suministro constante de agua y productos de limpieza.
    
    h3(data-aos='zoom-in-right').mb-4
      span.banana-title.banana-title--1 Equipos, utensilios y herramientas 
      
    p Entre los equipos y herramientas esenciales para la producción de plátano se incluyen:

    h4(data-aos='zoom-in-right').mb-4
      span.banana-title.banana-title--2 Equipos y herramientas

    .row.justify-content-center.align-items-stretch.mb-4.mb-lg-5
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/4.png', alt='Guadaña')(data-aos="zoom-in")
          .square-card__text
            h4 Guadaña 
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/5.png', alt='Cuchillo')(data-aos="zoom-in")
          .square-card__text
            h4 Cuchillos
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/6.png', alt='Machete')(data-aos="zoom-in")
          .square-card__text
            h4 Machetes
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/7.png', alt='Tijeras')(data-aos="zoom-in")
          .square-card__text
            h4 Tijeras 
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/8.png', alt='Azadones')(data-aos="zoom-in")
          .square-card__text
            h4 Azadones 
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/9.png', alt='Bomba de aspersión')(data-aos="zoom-in")
          .square-card__text
            h4 Bomba de aspersión 
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/10.png', alt='Tractores')(data-aos="zoom-in")
          .square-card__text
            h4 Tractores 
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/10.png', alt='Carros transportadores')(data-aos="zoom-in")
          .square-card__text
            h4 Carros transportadores 
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/10.png', alt='Balanzas')(data-aos="zoom-in")
          .square-card__text
            h4 Balanzas
      .col-lg-12.col-xl-5.pb-3
        .square-card.bg-color-acento-contenido.h-100.mb-3
          p Cada uno de estos implementos cumple una función específica en el proceso agrícola, desde la preparación del terreno y el manejo del cultivo hasta la cosecha y el transporte del producto. Su correcto uso y mantenimiento no solo optimiza la eficiencia en las labores diarias, sino que también garantiza la seguridad de los trabajadores y la calidad del producto final.

    .row.justify-content-center
      .col-xl-10
        h5(data-aos='zoom-in-right').mb-4 Recomendaciones a tener en cuenta 
        p El correcto manejo de herramientas y equipos en la producción agrícola es esencial para garantizar la seguridad de los trabajadores, la eficiencia en las labores y la inocuidad de los productos. A continuación, se presentan algunas recomendaciones para su uso adecuado:


    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-lg-10.col-xl-8
        h5(data-aos='zoom-in-right').mb-4 Mantenimiento y calibración
        p El mantenimiento y la calibración de los equipos son procesos esenciales para garantizar la eficiencia y precisión en las actividades agrícolas. Estas acciones, además de prolongar la vida útil de los equipos, también previenen fallos operativos que pueden afectar la productividad. Para su correcta ejecución, es fundamental considerar variables como la humedad relativa, la temperatura y los flujos de aire, ya que estos factores pueden influir en la calidad del producto final. Adicionalmente, establecer un plan de mantenimiento periódico y llevar registros detallados contribuye a optimizar los procesos y reducir riesgos en la producción.
      .col-md-6.col-lg-2
        figure
          img(src='@/assets/curso/temas/tema3/16.png', alt='Gajos de plátanos')(data-aos="fade-up")

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .order-1.order-lg-0.col-md-6.col-lg-2
        figure
          img(src='@/assets/curso/temas/tema3/17.svg', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-lg-10.col-xl-8
        h5(data-aos='zoom-in-right').mb-4 Peligros y controles de los equipos, utensilios y herramientas
        p El uso de equipos, utensilios y herramientas en la producción de plátano implica riesgos que pueden afectar tanto la calidad del producto como la seguridad de los trabajadores. Una gestión inadecuada de estos elementos puede generar contaminación, errores en los procesos y afectaciones en la inocuidad del cultivo. Para minimizar estos peligros, es fundamental establecer controles que garanticen la correcta higienización, almacenamiento y mantenimiento de los equipos. La siguiente tabla presenta los principales riesgos asociados y las medidas preventivas recomendadas para su control.

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-xl-10
        .titulo-sexto.color-acento-contenido.mb-3
            h5 Tabla 1.
            span <em>Peligros y controles de los equipos, utensilios y herramientas.</em>
        .tabla-peligros.mb-4
          table.text-center
            thead
              tr
                th Peligro
                th Control
            tbody
              tr
                td Contaminación del producto (plátano) por herramientas mal higienizadas.
                td Higienizar muy bien los equipos y herramientas al finalizar cada proceso.
              tr
                td Contaminación cruzada por mal almacenamiento entre productos para fertilizar.
                td Almacenar separadamente los fertilizantes de los insumos para evitar la contaminación entre productos.
              tr
                td Mala lectura de los equipos por la inadecuada calibración.
                td Realizar mantenimiento preventivo a los equipos para evitar malas lecturas y la descomposición de estos.

    Separador
    
    #t_3_2(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 3.2 Instalaciones Materias primas e insumos agrícolas
      
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-lg-5.mb-4.mb-lg-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/18.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las materias primas e insumos agrícolas son fundamentales para garantizar un cultivo eficiente y seguro. En las plantaciones de plátano, el agua es un recurso esencial utilizado en la higiene de herramientas, la preparación de mezclas de agroquímicos y el lavado de instalaciones durante las etapas de cosecha y poscosecha. Para evitar riesgos de contaminación, es indispensable que el agua empleada esté libre de microorganismos patógenos de origen fecal y sustancias químicas perjudiciales, como metales pesados (plomo), jabones y detergentes. Garantizar su calidad contribuye a la seguridad del cultivo, la inocuidad del producto y la sostenibilidad del proceso productivo.

    Separador

    #t_3_2(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 3.3 Recomendaciones para tener en cuenta en el uso del agua

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .d-none.d-xl-block.col-lg-1
        figure
          img(src='@/assets/curso/temas/tema3/19.svg', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-lg-11
        p El agua es un recurso esencial en la agricultura, ya que influye directamente en el crecimiento y desarrollo de los cultivos. Su uso adecuado garantiza la productividad, y además, contribuye a la sostenibilidad del ecosistema agrícola.
        p.mb-3.mb-xl-0 En este contexto, la irrigación es fundamental, al permitir el suministro controlado de agua a las plantas, asegurando que reciban la cantidad necesaria para su óptimo desarrollo. Para mejorar la eficiencia en su uso y evitar desperdicios, se deben considerar las siguientes recomendaciones:


      .mt-5.custom-slider
        SlyderF(columnas="col-lg-6 col-xl-4")
          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--6
            h3.text-center.mt-5 Calidad del agua
            p.mb-0.text-center El agua utilizada en las labores de riego y poscosecha debe cumplir con estándares mínimos de calidad, considerando parámetros como pH, dureza y conductividad. Es recomendable documentar los resultados de estas pruebas para su uso en evaluaciones posteriores.

          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--7
            h3.text-center.mt-5 Procedencia
            p.text-center Conocer la fuente del agua utilizada en la unidad productiva es esencial para evaluar su calidad y prevenir posibles contaminaciones.

          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--8
            h3.text-center.mt-5 Agua potable
            p.text-center Se debe emplear agua potable en todas las etapas de la cadena agroalimentaria, incluyendo la cosecha y la poscosecha.

          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--9
            h3.text-center.mt-5 Verificación por operarios
            p.mb-0.text-center Los trabajadores encargados del cultivo deben asegurarse de la sanidad del agua proveniente de ríos, nacederos y acueductos municipales, verificando su aptitud para el riego y otras aplicaciones agrícolas.

          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--10
            h3.text-center.mt-5 Almacenamiento en tanque
            p.text-center Los tanques de almacenamiento de agua deben mantenerse limpios y contar con la protección necesaria para evitar la contaminación por agentes químicos, físicos o biológicos.

          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--11
            h3.text-center.mt-5 Prevención de contaminación
            p.text-center Es fundamental lavar periódicamente los tanques de almacenamiento para evitar la proliferación de microorganismos y algas. Además, los equipos y utensilios utilizados en las labores agrícolas deben limpiarse con agua potable.

          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--12
            h3.text-center.mt-5 Control de cloro
            p.text-center Se debe monitorear el cloro residual en distintos puntos de abastecimiento y en los tanques de almacenamiento. Este control puede realizarse mediante un sistema de cloración para garantizar los niveles adecuados.

          .tarjeta.tarjeta--acento-contenido-claro.p-4.rounded-5.custom-slider__tarjeta.custom-slider__tarjeta--13
            h3.text-center.mt-5 Niveles de cloro
            p.text-center La concentración de cloro residual en la red de distribución debe mantenerse entre 0,3 y 0,5 partes por millón (ppm). En ningún caso debe descender por debajo de 0,1 ppm, ya que esto comprometería la calidad sanitaria del agua.

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-xl-10
        h3(data-aos='zoom-in-right').mb-4
          span.banana-title.banana-title--1 Peligros y controles en el uso del agua

        p Para garantizar la calidad del agua utilizada en las actividades agrícolas, es fundamental identificar los posibles riesgos asociados a su manejo y almacenamiento. La contaminación del agua puede afectar tanto el desarrollo del cultivo como la inocuidad del producto final, por lo que es necesario implementar medidas de control que reduzcan estos peligros. A continuación, se presenta una tabla con los principales riesgos relacionados con el uso del agua y las estrategias para mitigarlos.

        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 2.
          span <em>Peligros y controles en el uso del agua.</em>

        .tabla-peligros.mb-4
          table.text-center
            thead(style="background-color: #7D9FFB;color: white;")
              tr
                th Peligro
                th Control
            tbody
              tr
                td Contaminación del agua almacenada por mala limpieza en los tanques.
                td Lavar los tanques mínimos una vez al mes.
              tr
                td Contaminación microbiana por bajo valor de cloro residual en el agua.
                td Hacer muestreo en la red de abastecimiento para ver si hay alguna falla en la tubería.
              tr
                td Contaminación microbiológica en los racimos de plátano por uso de agua no potable en la poscosecha.
                td Usar en lo posible agua potable para evitar contaminación en el producto.

    Separador





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
