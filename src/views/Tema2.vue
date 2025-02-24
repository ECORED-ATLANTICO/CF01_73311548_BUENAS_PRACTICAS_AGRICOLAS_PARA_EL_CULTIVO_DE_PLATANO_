<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Implementación de las BPA
  
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5
      .col-lg-5.col-xl-3
        p La adopción efectiva de las Buenas Prácticas Agrícolas (BPA) en el cultivo de plátano exige una planificación meticulosa y una ejecución precisa de cada etapa del proceso. Esta implementación debe analizarse como una decisión estratégica para el productor, evaluando tanto sus beneficios como sus desafíos.
      .col-lg-7.col-xl-5.check-list.bg-color-terciario-t10.p-4.rounded-4.order-1.order-lg-0.mb-4.mb-lg-0
        p.mb-3 Entre las principales ventajas se destacan:
        ul.mt-0
          li
            span El acceso a nuevos mercados.
        ul.mt-0
          li
            span La mejora en la eficiencia productiva.
        ul.mt-0
          li
            span La reducción de riesgos fitosanitario.
        ul.mt-0.mb-3
          li
            span El fortalecimiento de la sostenibilidad ambiental. 
        p.mb-0 No obstante, también implica retos importantes, como:
      .d-none.d-xl-block.col-xl-4
          figure
            img.mb-4.mb-lg-0(src='@/assets/curso/temas/tema2/1.png', alt='Mujer cargando gajo de plátano')(data-aos="fade-up")

    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.retos-items.mb-4.mb-lg-5
      .col-md-6.col-lg-4.col-xl-3.mb-5.mb-xl-0
        .retos-items__card.retos-items__card--1.bg-color-acento-contenido
          p.mb-0 Los costos iniciales de implementación.
      .col-md-6.col-lg-4.col-xl-3.mb-5.mb-xl-0
        .retos-items__card.retos-items__card--2.bg-color-acento-contenido
          p.mb-0 La necesidad de capacitación.
      .col-md-10.col-lg-6.col-xl-4
        .retos-items__card.retos-items__card--3.bg-color-acento-contenido
          p.mb-0 La adopción de cambios culturales en la producción agrícola.

      .col-xl-10.mt-5
        p Para garantizar una implementación estructurada, es fundamental realizar un mapeo detallado de la finca, lo que permitirá identificar zonas de cultivo, fuentes de agua, áreas de almacenamiento y rutas de transporte. Asimismo, es clave reconocer y cumplir con los estándares establecidos por entes certificadores, tales como el Instituto Colombiano Agropecuario (ICA) y el ICONTEC, que regulan y certifican el cumplimiento de las BPA en el país.

    Separador

    #t_2_1(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 2.1 Ventajas y desventajas de la implementación de las BPA

    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-lg-5.mb-4.mb-lg-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/5.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La decisión de implementar Buenas Prácticas Agrícolas (BPA) en el cultivo del plátano requiere una evaluación cuidadosa de sus implicaciones. Es fundamental evaluar tanto las ventajas como las desventajas, considerando factores económicos, de mercado, logísticos y culturales que influyen en la toma de decisiones. Comprender estos aspectos permitirá determinar el impacto a largo plazo de la implementación de las BPA, en la rentabilidad, y sostenibilidad del cultivo.

    h4(data-aos='zoom-in-right').mb-4
      span.banana-title.banana-title--2 Ventajas
    
    .row.justify-content-center.align-items-center.mb-3.mb-lg-4.platano-timeline
      .col-lg-9
        LineaTiempoD.color-secundario.mt-3
          .row(numero="1" titulo="Acceso a mercados exigentes")
            .mb-4.mb-lg-0
              p La implementación de BPA facilita la exportación a mercados que requieren altos estándares de calidad e inocuidad, lo que abre nuevas oportunidades comerciales y mejora los precios de venta. Cada vez más países exigen estas certificaciones para permitir la comercialización de productos agrícolas.

          .row(numero="2" titulo="Mejor gestión y toma de decisiones")
            .mb-4.mb-lg-0
              p La adopción de sistemas de registro y trazabilidad permite recopilar información detallada sobre el negocio. Esto facilita la integración con otros actores de la cadena productiva y permite una toma de decisiones más fundamentada.
              
          .row(numero="3" titulo="Optimización de la gestión agrícola")
            .mb-4.mb-lg-0
            p La implementación de BPA mejora la administración de la finca, optimizando el control de personal, insumos e infraestructura. Además, incrementa la competitividad al reducir costos relacionados con desperdicios, tiempos muertos y pérdidas de insumos.

          .row(numero="4" titulo="Menos intermediarios en la comercialización")
            .mb-4.mb-lg-0
            p Al cumplir con estándares de calidad e inocuidad, los productores pueden acceder directamente a supermercados y empresas exportadoras, reduciendo la dependencia de intermediarios y mejorando los márgenes de ganancia.

          .row(numero="5" titulo="Mayor compromiso del personal")
            .mb-4.mb-lg-0
            p La profesionalización del trabajo agrícola dignifica la labor del trabajador, aumentando su motivación y fomentando la especialización en las diferentes etapas de producción.

          .row(numero="6" titulo="Mejora de la imagen empresarial")
            .mb-4.mb-lg-0
            p Las BPA fortalecen la reputación de la empresa ante clientes y consumidores, generando confianza y abriendo nuevas oportunidades de negocio.

          .row(numero="6" titulo="Impacto positivo en las comunidades locales")
            .mb-4.mb-lg-0
            p La implementación de BPA puede promover la inclusión de comunidades aledañas en los mercados locales y regionales, impulsando el desarrollo económico de la zona.

      .col-6.col-lg-3.mt-3.align-content-center
        figure
          img(data-aos="fade-up")(src='@/assets/curso/temas/tema2/6.png', alt='Mujer recolectando plátanos')

       
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

<style lang="sass"></style>
