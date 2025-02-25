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
              img(src='@/assets/curso/temas/tema3/11.png', alt='Carros transportadores')(data-aos="zoom-in")
          .square-card__text
            h4 Carros transportadores 
      .col-md-6.col-lg-4.col-xl-3
        .square-card.bg-color-terciario-t20
          .square-card__img
            figure
              img(src='@/assets/curso/temas/tema3/12.png', alt='Balanzas')(data-aos="zoom-in")
          .square-card__text
            h4 Balanzas
      .col-lg-12.col-xl-5.pb-3
        .square-card.bg-color-acento-contenido.h-100.mb-3
          p Cada uno de estos implementos cumple una función específica en el proceso agrícola, desde la preparación del terreno y el manejo del cultivo hasta la cosecha y el transporte del producto. Su correcto uso y mantenimiento no solo optimiza la eficiencia en las labores diarias, sino que también garantiza la seguridad de los trabajadores y la calidad del producto final.

    .row.justify-content-center.align-items-center.mb-4
      .col-xl-10
        h5(data-aos='zoom-in-right').mb-4 Recomendaciones a tener en cuenta 
        p El correcto manejo de herramientas y equipos en la producción agrícola es esencial para garantizar la seguridad de los trabajadores, la eficiencia en las labores y la inocuidad de los productos. A continuación, se presentan algunas recomendaciones para su uso adecuado:

    .row.justify-content-center.align-items-stretch.mb-4.mb-lg-5
      .col-sm-6.col-lg-3.mb-3.mb-lg-0
        .tarjeta--boton.p-4.h-100(data-aos="flip-left")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema3/13.svg', alt='Ilustración decorativa')

          p.text-center.mb-0 Los equipos y herramientas deben ser de materiales resistentes, seguros para los trabajadores y garantizar la inocuidad de los productos durante su uso.

      .col-sm-6.col-lg-3.mb-3.mb-lg-0
        .tarjeta--boton.p-4.h-100(data-aos="flip-left")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema3/14.svg', alt='Ilustración decorativa')

          p.text-center.mb-0 Es fundamental realizar mantenimiento preventivo a equipos como termómetros, altímetros y aspersores para asegurar su correcto funcionamiento y prolongar su vida útil.

      .col-sm-6.col-lg-3.mb-3.mb-sm-0
        .tarjeta--boton.p-4.h-100(data-aos="flip-left")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema3/15.svg', alt='Ilustración decorativa')

          p.text-center.mb-0 Se deben llevar registros detallados de limpieza y desinfección de herramientas, especificando el desinfectante utilizado, su concentración y la persona responsable del procedimiento.

      .col-sm-6.col-lg-3
        .tarjeta--boton.p-4.h-100(data-aos="flip-left")
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/tema3/50.svg', alt='Ilustración decorativa')

          p.text-center.mb-0 Después de cada uso, todos los equipos, utensilios y herramientas deben ser higienizados para prevenir la contaminación y garantizar condiciones óptimas de trabajo.

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

    #t_3_3(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
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

    #t_3_4(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 3.4 Suelos

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-lg-9
        p El manejo adecuado del suelo es fundamental para garantizar la productividad y sostenibilidad del cultivo de plátano. La conservación de sus características físicas, químicas y biológicas permite optimizar el crecimiento de la planta y evitar problemas como la erosión y la saturación por el uso excesivo de fertilizantes.
        p Los suelos ideales para el cultivo de plátano deben ser oscuros, de textura media y suelta, facilitando la penetración de las raíces y el desarrollo de la planta. Además, es esencial que presenten una porosidad entre el 45 % y el 60 %, lo que contribuye a un adecuado drenaje y retención de nutrientes.

      .d-none.d-lg-block.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema3/28.png', alt='Ilustración decorativa')(data-aos="fade-up")

    .row.justify-content-center.align-items-center
      .col-xl-10
        h3(data-aos='zoom-in-right').mb-4
          span.banana-title.banana-title--1 Propiedades químicas del suelo

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .d-none.d-lg-block.col-lg-3.col-xl-2
        figure
          img(src='@/assets/curso/temas/tema3/29.svg', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-lg-7.col-xl-8
        p.mb-0 El pH óptimo para el cultivo de plátano debe situarse entre 5,5 y 7,2. Niveles por debajo de este rango pueden afectar negativamente el desarrollo de la planta. Asimismo, se requiere un suelo fértil, rico en macro y microelementos esenciales para el crecimiento y la producción del cultivo.

    .row.justify-content-center.align-items-center
      .col-xl-10
        h3(data-aos='zoom-in-right').mb-4
          span.banana-title.banana-title--1 Buenas prácticas en el manejo del suelo

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .d-none.d-lg-block.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema3/30.png', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-lg-7.check-list.bg-color-terciario-t10.rounded-4.p-4
        ul.mb-1
          li
            span Los suelos donde se siembre plátano deben estar libres de plagas.
        ul.mb-1
          li
            span Revisar los períodos de cuarentena del terreno que haya tenido moko, antes de sembrar de nuevo plátano.
        ul.mb-1
          li
            span Los suelos donde se siembra plátano deben ser sueltos, con alto contenido de materia orgánica y con buen drenaje.
        ul.mb-1
          li
            span Evitar que haya inundaciones donde está establecido el cultivo, puesto que la acumulación de agua destruye las raíces funcionales.
        ul.mb-1
          li
            span En los suelos donde se encuentra el cultivo de plátano es aconsejable que se realicen coberturas para evitar la pérdida de nutrientes por aguas de escorrentías.

    .row.justify-content-center.align-items-center
      .col-xl-10
        h3(data-aos='zoom-in-right').mb-4
          span.banana-title.banana-title--1 Peligros y controles de los suelos

        p El uso inadecuado del suelo puede comprometer su fertilidad y afectar el rendimiento del cultivo. A continuación, se presentan algunos de los principales riesgos y las estrategias recomendadas para su control.

        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 3.
          span <em>Peligros y controles en el uso del agua.</em>
        .tabla-peligros.mb-4
          table.text-center
            thead
              tr
                th Peligros
                th Controles
            tbody
              tr
                td Suelos pobres que no aporten los nutrientes que necesita el cultivo.
                td Realizar análisis de suelos antes de establecer el cultivo.
              tr
                td Suelos erosionados y poco fértiles por mal uso de la maquinaria.
                td Fertilizar los suelos con materia orgánica bien compostada.
              tr
                td 
                td Hacer un buen manejo del suelo utilizando técnicas agrícolas que no alteren las propiedades físicas y químicas de este recurso.

    Separador

    #t_3_5(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 3.5 Semillas

    p Las semillas desempeñan un papel indispensable en el cultivo de plátano, ya que de su calidad depende la productividad y el éxito de la cosecha. La selección adecuada de semillas contribuye al desarrollo vigoroso de la plantación y a la obtención de frutos sanos. Para ello, es de gran importancia considerar diversos aspectos en su adquisición y manejo, garantizando así un inicio adecuado del proceso de cultivo. A continuación, se presentan algunas recomendaciones:

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.factores-slider
      .d-none.d-xl-block.col-xl-5
        figure
          img(src='@/assets/curso/temas/tema3/31.png', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-xl-7.bg-platanos-image.p-4.rounded-3
        SlyderF().bg-white.p-3.rounded-3
          .tarjeta.p-3.rounded-3.d-flex
            .row.align-items-center
              .col-3.d-none.d-md-block
                figure
                  img.width-110(src='@/assets/curso/temas/tema3/32.svg', alt='Ilustración decorativa')(data-aos="fade-up")
              .col-md-9
                h3.factores-slider__number.color-acento-contenido Juventud y vigor
                p.mb-0 Se recomienda emplear semillas jóvenes y vigorosas, cuya procedencia y características fenotípicas sean óptimas.

          .tarjeta.p-3.rounded-3.d-flex  
            .row.align-items-center
              .col-3.d-none.d-md-block
                figure
                  img.width-110(src='@/assets/curso/temas/tema3/33.svg', alt='Ilustración decorativa')(data-aos="fade-up")
              .col-md-9
                h3.factores-slider__number.color-acento-contenido Extracción cuidadosa
                p.mb-0 No se deben descartar las semillas provenientes de plantaciones ubicadas en laderas, pero su extracción debe realizarse con herramientas bien afiladas para evitar daños en el material vegetal.

          .tarjeta.p-3.rounded-3.d-flex  
            .row.align-items-center
              .col-3.d-none.d-md-block
                figure
                  img.width-110(src='@/assets/curso/temas/tema3/34.svg', alt='Ilustración decorativa')(data-aos="fade-up")
              .col-md-9
                h3.factores-slider__number.color-acento-contenido Condiciones de los colinos
                p.mb-0 Los colinos de plátano seleccionados deben contar con al menos tres hojas funcionales en forma de espada.

          .tarjeta.p-3.rounded-3.d-flex  
            .row.align-items-center
              .col-3.d-none.d-md-block
                figure
                  img.width-110(src='@/assets/curso/temas/tema3/35.svg', alt='Ilustración decorativa')(data-aos="fade-up")
              .col-md-9
                h3.factores-slider__number.color-acento-contenido Prevención de plagas y enfermedades
                p.mb-0 Durante la manipulación de semillas, es crucial evitar la propagación de plagas y enfermedades. Para ello, se debe limpiar cuidadosamente el material vegetal, eliminando tierra y partes dañadas.

          .tarjeta.p-3.rounded-3.d-flex  
            .row.align-items-center
              .col-3.d-none.d-md-block
                figure
                  img.width-110(src='@/assets/curso/temas/tema3/36.svg', alt='Ilustración decorativa')(data-aos="fade-up")
              .col-md-9
                h3.factores-slider__number.color-acento-contenido Preservación del rizoma
                p.mb-0 No es aconsejable dividir el rizoma para obtener varias semillas, ya que esto debilita las reservas de la planta y la expone al ataque de parásitos.

          .tarjeta.p-3.rounded-3.d-flex  
            .row.align-items-center
              .col-3.d-none.d-md-block
                figure
                  img.width-110(src='@/assets/curso/temas/tema3/37.svg', alt='Ilustración decorativa')(data-aos="fade-up")
              .col-md-9
                h3.factores-slider__number.color-acento-contenido Tratamiento sanitario
                p.mb-0 Las semillas deben estar en óptimas condiciones sanitarias y someterse a un tratamiento con desinfectantes aptos para alimentos.

          .tarjeta.p-3.rounded-3.d-flex  
            .row.align-items-center
              .col-3.d-none.d-md-block
                figure
                  img.width-110(src='@/assets/curso/temas/tema3/38.svg', alt='Ilustración decorativa')(data-aos="fade-up")
              .col-md-9
                h3.factores-slider__number.color-acento-contenido Protección contra patógenos
                p.mb-0 Se recomienda sumergir las semillas en agua caliente por un tiempo breve y aplicar fungicidas e insecticidas para reducir el riesgo de plagas y enfermedades.
        
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-xl-10
        h3(data-aos='zoom-in-right').mb-4
          span.banana-title.banana-title--1 Peligros y controles de las semillas

        p El uso de semillas de baja calidad o con manejo inadecuado, puede comprometer la producción del cultivo, facilitando la propagación de enfermedades y reduciendo el rendimiento. Para mitigar estos riesgos, se deben adoptar medidas preventivas que aseguren la sanidad y viabilidad del material vegetal. La siguiente tabla presenta los principales peligros asociados al uso de semillas y las estrategias de control recomendadas.

        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 4.
          span <em>Peligros y controles de las semillas.</em>

        .tabla-peligros.mb-4
          table.text-center
            thead(style="background-color: #7D9FFB;color: white;")
              tr
                th Peligros
                th Controles
            tbody
              tr
                td Semillas de mala calidad que pueden afectar la producción de plátano.
                td La semilla debe ser adquirida de un proveedor confiable que realice todos los parámetros de calidad requeridos.
              tr
                td La semilla se puede contaminar si no se realiza la adecuación correspondiente.
                td Desinfectar los equipos utilizados en la extracción de los colinos y cada vez que se utilicen los implementos se deben lavar para que no haya contaminación cruzada de semilla a semilla.

    Separador

    #t_3_6(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 3.6 Agroquímicos

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .d-none.d-xl-block.col-xl-2
        figure
          img(src='@/assets/curso/temas/tema3/40.svg', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-xl-8
        p El uso de agroquímicos en el cultivo de plátano es una práctica de gran importancia para el control de enfermedades e insectos, pero su manejo inadecuado puede representar riesgos significativos para la salud de los trabajadores, el medio ambiente y la calidad del producto. Por ello, es indispensable que su aplicación se realice de manera responsable, siguiendo estrictamente las normativas establecidas y adoptando medidas de seguridad que minimicen los posibles efectos adversos.

        h4(data-aos='zoom-in-right').mb-4
          span.banana-title.banana-title--2 Recomendaciones para tener en cuenta en el uso de agroquímicos

        p Para garantizar una aplicación segura y eficaz de los agroquímicos en el cultivo, se deben considerar las siguientes recomendaciones:
        
    SlyderA(tipo="b").custom-slider-a-b.rounded-4.mb-4.mb-lg-5
      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          p Los agroquímicos para utilizar deben estar en los envases originales y con la etiqueta en muy buen estado, para que se puedan leer las especificaciones de cada producto con el fin de que no haya errores en su aplicación al cultivo.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema3/41.png', alt='female-gardener-spraying-insecticide-plant')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          p Los agroquímicos no deben estar vencidos y deben estar autorizados por las autoridades competentes, para Colombia es el Instituto Colombiano Agropecuario (ICA) el que otorga el certificado a este tipo de productos.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema3/42.png', alt='female-botanist-examining-plant-sample-quality-control-inspection-greenhouse')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          p El lugar destinado para el almacenamiento de agroquímicos debe estar lejos del sitio donde se clasifica y se alista el producto. El lugar de almacenamiento de plaguicidas debe ser seguro y de acceso restringido a particulares.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema3/43.png', alt='young-selectionist')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          p Es importante rotar los agroquímicos almacenados y siempre utilizar el que está por vencerse. El uso de los agroquímicos debe ser racional, siempre con miras en proteger los operarios que los manipulan y medio ambiente como la flora y la fauna.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema3/44.png', alt='closeup-biologist-spraying-potted-flowers-with-nutritional-fertilizes-plant-nursery')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          p Los equipos para aplicar los agroquímicos deben estar en buen estado y bien calibrados, se deben aplicar las dosis recomendadas por los agrónomos y técnicos agropecuarios.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema3/45.png', alt='researcher-takes-water-test-tube-sitting-greenhouse')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          p.mb-0 En las unidades productivas se debe contar con un botiquín para atender intoxicaciones por plaguicidas o sustancias peligrosas. Los operarios del predio deben contar con los equipos de protección adecuados (respirador, cascos, guantes y overol) para la manipulación de estos productos, según lo establecido por la normatividad vigente.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema3/46.png', alt='female-gardener-spraying-insecticide-plant')

    h3(data-aos='zoom-in-right').mb-4
      span.banana-title.banana-title--1 Peligros, controles y acciones correctivas en el uso de agroquímicos

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .d-none.d-lg-block.col-lg-3.col-xl-2
        figure
          img(src='@/assets/curso/temas/tema3/47.svg', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-lg-7.col-xl-10
        p.mb-0 El uso inadecuado de agroquímicos puede generar diversos riesgos, desde la contaminación del agua hasta la presencia de residuos químicos en el producto final. Para mitigar estos peligros, es fundamental implementar controles preventivos y acciones correctivas que garanticen un manejo seguro de estos productos. La siguiente tabla presenta los principales peligros identificados y las estrategias recomendadas para su control y corrección.

    .row.justify-content-center.align-items-center
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 3.
          span <em>Peligros y controles en el uso del agua.</em>
        .tabla-peligros.mb-4
          table.text-center
            thead
              tr
                th Peligros
                th Controles
                th Acciones correctivas
            tbody
              tr
                td Suelos pobres que no aporten los nutrientes que necesita el cultivo.<br><br>Usar sobredosis o subdosis de agroquímicos y pesticidas.<br><br>Que haya contaminación química en el plátano por mal uso de los plaguicidas en la producción.<br><br>Usar productos químicos vencidos en el cultivo de plátano puede poner en riesgo la salud del consumidor final.
                td Realizar pruebas fisicoquímicas al agua para garantizar que sea segura para el cultivo.<br><br>Realizar un control de los agroquímicos almacenados descartando los que están vencidos y dando prioridad de uso a los próximos a vencer.<br><br>Almacenar	los productos químicos en lugares seguros, destinado sólo para ese fin.
                td Disponer de otras fuentes de suministro de agua en caso de contaminación de las existentes.<br><br>Calibrar equipos y utilizar adecuadamente las boquillas de las máquinas fumigadoras.<br><br>Descartar los productos vencidos.<br><br>Realizar un control de calidad de los productos químicos antes de su uso.	Descartar el plátano contaminado.
       
    Separador

    #t_3_7(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 3.7 Abonos orgánicos
    
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .d-none.d-lg-block.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema3/48.svg', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-lg-9
        p El uso de abonos orgánicos en el cultivo de plátano, como la gallinaza y el lombricompuesto, contribuye a mejorar la fertilidad del suelo y la productividad del cultivo. Sin embargo, para garantizar la inocuidad del producto final, es fundamental que estos abonos estén libres de contaminación por metales pesados y otras sustancias que puedan comprometer la calidad del plátano.
        p Para reducir el riesgo de contaminación microbiana en los abonos orgánicos, se deben considerar las siguientes recomendaciones:

    
    .row.justify-content-center.align-items-center
      .col-lg-9
        AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--acento-contenido-a10")
          .row(titulo="Verificación del registro ICA")
            p Al adquirir abonos orgánicos, es imprescindible asegurarse de que cuenten con el registro del Instituto Colombiano Agropecuario (ICA), lo que certifica su calidad y seguridad para el uso agrícola.

          .row(titulo="Proceso de elaboración adecuado")
            p Se debe exigir que los fertilizantes orgánicos hayan pasado por un proceso de compostaje completo, garantizando su estabilidad y eficacia para el cultivo de plátano.

          .row(titulo="Evitar el uso de estiércoles frescos")
            p Los estiércoles sin tratamiento contienen una alta carga microbiana que puede afectar la sanidad del cultivo. Por ello, deben someterse a un proceso adecuado de compostaje antes de su aplicación.

          .row(titulo="Almacenamiento seguro")
            .col-md-6
              p Los abonos orgánicos deben resguardarse en un área separada de la unidad productiva para prevenir la contaminación cruzada con el cultivo.

          .row(titulo="Control de calidad en producción propia")
            .col-md-6
              p Si los abonos orgánicos se elaboran dentro del predio, es necesario llevar un registro detallado del proceso de transformación y realizar pruebas microbiológicas que confirmen la ausencia de patógenos como Salmonella, Escherichia coli y Enterobacter

      .d-none.d-lg-block.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema3/49.png', alt='Manos recolectando arena')(data-aos="fade-up")

    .m-footer

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
