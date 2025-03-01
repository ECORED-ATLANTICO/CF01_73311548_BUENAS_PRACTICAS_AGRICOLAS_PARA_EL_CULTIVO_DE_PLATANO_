<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Peligros, controles y manejo de residuos líquidos

    .row.justify-content-center.align-items-center
      .col-lg-9
        p.mb-3.mb-xl-0 La producción agrícola sostenible exige una gestión responsable de los riesgos y un adecuado manejo de los residuos generados en el proceso productivo. En el cultivo del plátano, los residuos líquidos representan una fuente potencial de contaminación que puede afectar tanto la salud humana como el equilibrio ambiental. Esta sección examina los principales peligros asociados a su generación, destacando la importancia de implementar medidas preventivas y de control para mitigar su impacto. Además, se presentan estrategias orientadas a reducir la contaminación, optimizar el uso del agua y garantizar el cumplimiento de la normativa ambiental vigente.
      .col-6.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema4/1.svg', alt='Ilustración decorativa')(data-aos="fade-up")

    Separador

    #t_4_1(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 4.1	Peligros y controles de los residuos

    p El manejo inadecuado de los residuos agrícolas puede generar contaminación en los cultivos y afectar la calidad del producto final. Identificar los principales peligros y aplicar controles efectivos es fundamental para prevenir riesgos ambientales y garantizar la seguridad del proceso productivo. La siguiente tabla presenta algunos de los peligros asociados a la contaminación y las medidas de control recomendadas.
    
    .row.justify-content-center.align-items-center
      .d-none.d-xl-block.col-xl-3
        figure
          img.mb-4.mb-xl-0(src='@/assets/curso/temas/tema4/2.png', alt='Ilustración decorativa')(data-aos="fade-up")
      .col-xl-9
        .titulo-sexto.color-acento-contenido.mb-3
            h5 Tabla 6.
            span <em>Peligros y controles en el manejo de residuos.</em>

        .tabla-peligros.mb-4
          table.overflow-auto.text-center
            thead
              tr
                th Peligro
                th Control
            tbody
              tr
                td Que los fertilizantes estén mal compostados,	ocasionando contaminación al cultivo.
                td Solicitar comprobante de elaboración del producto y verificar que este tenga el registro otorgado por las autoridades competentes.
              tr
                td Que haya contaminación cruzada entre productos frescos y compostados.
                td Realizar un buen almacenamiento de los fertilizantes orgánicos.

        p.mb-0 Con el manejo ambiental se busca garantizar la sostenibilidad y competitividad en la unidad agrícola. Las etapas de proceso que puedan generar impacto ambiental deben registrarse, por esta razón, es importante diseñar medidas preventivas y de control en cuanto a los requerimientos ambientales legales.

    Separador

    #t_4_2(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 4.2 Plan de manejo ambiental

    p El manejo adecuado de los residuos líquidos y sólidos es fundamental para minimizar el impacto ambiental en la producción de plátano. Implementar estrategias de control y reducción contribuye a la sostenibilidad del cultivo y al cumplimiento de la normativa ambiental vigente.

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-xl-7
        .row.justify-content-center.align-items-center.mb-3.mb-lg-4.check-list
          h3(data-aos='zoom-in-right').my-3
            span.banana-title.banana-title--1 Manejo de residuos líquidos

          p Para reducir la generación de vertimientos líquidos y prevenir la contaminación, se deben aplicar las siguientes medidas:

          ul.mt-0
            li
              span Calcular con precisión la cantidad de agroquímicos necesaria en la preparación de mezclas, evitando excedentes que generen desechos innecesarios.
            hr.hr-continuo
          ul.mt-0
            li
              span Contar con un sistema de acueducto adecuado para el manejo de aguas residuales provenientes de baterías sanitarias.
            hr.hr-continuo
          ul.mt-0
            li
              span Prevenir la contaminación de fuentes hídricas, como ríos, pozos y canales, evitando el vertimiento de residuos de plaguicidas y otros contaminantes.
      .d-none.d-xl-block.col-xl-3
        figure
          img(src='@/assets/curso/temas/tema4/3.png', alt='Ilustración decorativa')(data-aos="fade-up")


    h3(data-aos='zoom-in-right').mb-4
      span.banana-title.banana-title--1 Manejo de residuos sólidos

    p.mb-4.mb-xl-5 El manejo adecuado de los residuos sólidos es importante para la sostenibilidad del cultivo. A continuación, se presentan algunas recomendaciones específicas:

    TabsB.color-acento-contenido.tabs-residuos
      .py-4.py-md-5(titulo="Productos vencidos" :icono="require('@/assets/curso/temas/tema4/5.svg')")
        .row.align-items-center
          .col-lg-6.col-xl-5.mb-4.mb-md-0
            p.mb-4.mb-lg-0 Deben almacenarse en estanterías exclusivas, debidamente señalizadas con un letrero de "Productos vencidos" y resguardadas bajo llave para evitar su uso indebido. 
        
          .col-lg-6.col-xl-7
            figure
              img(src='@/assets/curso/temas/tema4/10.png', alt='Productos varios')(data-aos="fade-up")
      .py-4.py-md-5(titulo="Recipientes vacíos" :icono="require('@/assets/curso/temas/tema4/6.svg')")
        .row.align-items-center
          .col-lg-6.col-xl-5.mb-4.mb-md-0
            p.mb-4.mb-lg-0 No deben reutilizarse. Es necesario perforarlos sin dañar las etiquetas para evitar su uso inapropiado.
        
          .col-lg-6.col-xl-7
            figure
              img(src='@/assets/curso/temas/tema4/11.png', alt='Productos varios')(data-aos="fade-up")
      .py-4.py-md-5(titulo="Envases de agroquímicos" :icono="require('@/assets/curso/temas/tema4/7.svg')")
        .row.align-items-center
          .col-lg-6.col-xl-5.mb-4.mb-md-0
            p.mb-4.mb-lg-0 Son considerados residuos peligrosos, no pueden desecharse como basura convencional. Deben someterse a un proceso de triple lavado antes de su disposición final.
        
          .col-lg-6.col-xl-7
            figure
              img(src='@/assets/curso/temas/tema4/12.png', alt='Productos varios')(data-aos="fade-up")
      .py-4.py-md-5(titulo="Transporte de agroquímicos" :icono="require('@/assets/curso/temas/tema4/8.svg')")
        .row.align-items-center
          .col-lg-6.col-xl-5.mb-4.mb-md-0
            p.mb-4.mb-lg-0 Se deben trasladar en sus envases originales con etiquetas visibles, evitando golpes o rupturas que puedan ocasionar derrames. Este procedimiento debe cumplir con la normativa vigente sobre el transporte de sustancias peligrosas.
        
          .col-lg-6.col-xl-7
            figure
              img(src='@/assets/curso/temas/tema4/13.png', alt='Productos varios')(data-aos="fade-up")
      .py-4.py-md-5(titulo="Derrames" :icono="require('@/assets/curso/temas/tema4/9.svg')")
        .row.align-items-center
          .col-lg-6.col-xl-5.mb-4.mb-md-0
            p.mb-4.mb-lg-0 En caso de un derrame, es fundamental consultar de inmediato la hoja de datos de seguridad del producto y seguir las instrucciones documentadas para su manejo seguro.
        
          .col-lg-6.col-xl-7
            figure
              img(src='@/assets/curso/temas/tema4/14.png', alt='Productos varios')(data-aos="fade-up")

    .m-footer

</template>

<script>
export default {
  name: 'Tema4',
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
