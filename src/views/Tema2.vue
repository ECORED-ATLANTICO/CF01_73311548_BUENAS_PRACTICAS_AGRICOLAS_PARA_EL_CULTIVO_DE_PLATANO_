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

    .row.justify-content-center.align-items-center.retos-items
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

    h4(data-aos='zoom-in-right').mb-3
      span.banana-title.banana-title--2 Ventajas
    
    .row.justify-content-center.align-items-center.mb-4.mb-lg-5.platano-timeline
      .col-lg-9
        LineaTiempoD.color-secundario.mt-3.mb-4.mb-lg-0
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

      .col-6.col-lg-3.align-content-center
        figure
          img(data-aos="fade-up")(src='@/assets/curso/temas/tema2/6.png', alt='Mujer recolectando plátanos')

    h4(data-aos='zoom-in-right').mb-3
      span.banana-title.banana-title--2 Desventajas

    .row.justify-content-center.align-items-center.platano-timeline
      .col-10.col-lg-5.align-content-center
        figure
          img.mb-4.mb-lg-0(data-aos="fade-up")(src='@/assets/curso/temas/tema2/7.png', alt='Mujer recolectando plátanos')

      .col-lg-7
        LineaTiempoD.color-secundario.mt-3
          .row(numero="1" titulo="Altos costos iniciales")
            .mb-4.mb-lg-0
              p La adopción de BPA requiere una inversión considerable en certificación, infraestructura y adecuación de procesos.

          .row(numero="2" titulo="Renovación anual de la certificación")
            .mb-4.mb-lg-0
              p La certificación de BPA tiene una vigencia de un año, por lo que es necesario renovarla periódicamente, lo que representa costos recurrentes.
              
          .row(numero="3" titulo="Cambio cultural y adaptación del personal")
            .mb-4.mb-lg-0
              p La implementación exige compromiso y capacitación por parte de los trabajadores, así como nuevos hábitos de higiene y uso de registros. Este proceso puede requerir tiempo y recursos adicionales.

          .row(numero="4" titulo="Capacitación obligatoria")
            .mb-4.mb-lg-0
              p Se debe capacitar tanto a supervisores como a trabajadores en normativas, procedimientos y estándares de calidad, lo que implica una inversión adicional en formación.

          .row(numero="5" titulo="Cumplimiento estricto de normativas")
            .mb-4.mb-lg-0
              p La producción debe ajustarse a regulaciones sanitarias, ambientales y laborales, lo que exige un control riguroso y continuo.

          .row(numero="6" titulo="Largos períodos de implementación")
            .mb-4.mb-lg-0
              p Dependiendo del tipo de certificación, la adaptación a las BPA puede tomar varios meses o incluso años, retrasando la obtención de beneficios económicos inmediatos.

          .row(numero="6" titulo="Auditorías periódicas")
            .mb-4.mb-lg-0
              p Los organismos certificadores realizan inspecciones regulares para verificar el cumplimiento de las normativas. Esto puede generar estrés en los trabajadores, especialmente si no comprenden el propósito de las auditorías.
    
    Separador

    #t_2_2(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 2.2 Importancia de la implementación de las BPA

    .row.justify-content-center.align-items-center.mb-4
      .col-xl-9
        p La adopción de Buenas Prácticas Agrícolas (BPA) en un sistema de producción conlleva una serie de ventajas y desafíos que han sido previamente analizados. A partir de este análisis, se puede concluir que su implementación es fundamental para cualquier productor de alimentos que aspire a prosperar, mantenerse competitivo e incursionar en nuevos mercados con el objetivo de expandir su negocio.
        .row.p-3.bg-color-terciario-t20.rounded-4.pb-0.align-items-center.justify-content-center
          .col-8.col-lg-3
            figure
              img.mb-4.mb-lg-0(data-aos="fade-up")(src='@/assets/curso/temas/tema2/8.svg', alt='Ilustacion de acompañamiento')
          .col-lg-9
            p Si bien las desventajas están principalmente relacionadas con los costos asociados a la certificación e implementación, estos representan una inversión necesaria en la mayoría de los procesos que buscan mejorar significativamente la productividad y sostenibilidad de una empresa agrícola.
            p.mb-4.mb-lg-0 La importancia de adoptar las BPA radica en garantizar la inocuidad de los cultivos, y además, en asegurar verdaderamente que los productos sean seguros para el consumo, con condiciones sanitarias óptimas y libres de plagas y enfermedades.
      .d-none.d-xl-block.col-xl-3
        figure
          img(data-aos="fade-up")(src='@/assets/curso/temas/tema2/9.png', alt='Campesino sonriendo')

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10
        .row.bg-color-secundario-s10.p-4.rounded-4.mb-4
          .col-lg-10
            p Además, el valor del producto no solo aumenta debido a su calidad certificada, sino en muchos mercados, estas características son un requisito legal. Con el tiempo, cada vez más países y clientes exigen el cumplimiento de estas normativas, por lo que la certificación se convierte en una herramienta esencial para la permanencia y el crecimiento en el sector agrícola. Aquellos productores que no adopten las BPA perderán participación en el mercado, mientras que aquellos que sí lo hagan podrán acceder a mejores oportunidades comerciales.
          .col-lg-2
            figure
              img.width-110(data-aos="fade-up")(src='@/assets/curso/temas/tema2/10.svg', alt='Campesino sonriendo')

        h5(data-aos='zoom-in-right') A continuación, se presentan algunos elementos clave de la implementación de las BPA:

    SlyderA(tipo="b").custom-slider-a-b.rounded-4
      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          h5 Mejora en la percepción del producto
          p La implementación de Buenas Prácticas Agrícolas (BPA) en una empresa impacta directamente en la percepción del cliente sobre el producto. Un proceso bien ejecutado contribuye a mejorar las características organolépticas de los alimentos cultivados, lo que influye en la aceptación y preferencia del consumidor.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema2/11.png', alt='gajo de plátanos')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          h5 Influencia de la certificación en el consumidor
          p El impacto de las BPA en la imagen del producto va más allá de la calidad tangible. También se genera un fenómeno de sugestión psicológica, ya que una certificación en BPA otorga reconocimiento en el mercado. Cuando un cliente prueba un producto de su agrado y sabe que cuenta con esta certificación, su percepción sobre la marca y sus estándares de calidad se refuerza positivamente.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema2/12.png', alt='female-botanist-examining-plant-sample-quality-control-inspection-greenhouse')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          h5 Impacto de la certificación en la imagen empresarial
          p Existe otro efecto generado por el impacto que tiene la certificación BPA en los clientes, y corresponde a un efecto extensivo de la imagen que tienen sobre el producto y por ende en la empresa.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema2/13.png', alt='young-selectionist')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          h5 Extensión de la percepción de calidad
          p Si un cliente considera que un producto es de calidad, suele asumir que todos los productos de la empresa cumplen con los mismos estándares. Esta percepción se fortalece aún más cuando la compañía cuenta con una certificación reconocida, mejorando su reputación y posicionamiento en el mercado.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema2/20.png', alt='Imagen decorativa')

      .row.align-items-center.custom-slider-a-b__item
        .col-lg-6
          h5 Reputación regional y competitividad
          p El impacto puede extenderse incluso a nivel regional. Cuando varias empresas de una misma zona operan bajo condiciones de calidad e inocuidad y poseen certificaciones en BPA, la región en su conjunto adquiere una imagen positiva y una mayor reputación en los mercados a los que abastece.

        .d-none.d-lg-block.col-lg-6
          figure
            img(src='@/assets/curso/temas/tema2/21.png', alt='Imagen decorativa')

    Separador

    #t_2_3(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 2.3	Mapeo de la finca
    
    .row.justify-content-center.align-items-center.mb-4
      .col-10.mb-4.mb-lg-0.col-lg-4
        figure
          img(src='@/assets/curso/temas/tema2/14.png', alt='Imagen decorativa')
      .col-lg-8
        p El mapeo de la finca es una tarea fundamental que todo productor comprometido con la implementación de Buenas Prácticas Agrícolas (BPA) debe considerar con seriedad y realizar con precisión. Este proceso consiste en la elaboración de un croquis detallado del terreno, es decir, una representación gráfica que refleje tanto la extensión, como la distribución del área productiva, así como las edificaciones, caminos, fuentes de agua y demás infraestructuras presentes en la finca.
        .p-4.bg-color-acento-contenido-a5.rounded-4
          p.mb-0 Además, el mapeo debe incluir una descripción precisa de las características del suelo, identificando los distintos tipos de terreno, la presencia de desniveles o pendientes y cualquier otro factor que pueda influir en el manejo agrícola. Contar con esta información facilita la planificación, el uso eficiente de los recursos y la implementación de estrategias para la sostenibilidad y optimización del cultivo.
    p La importancia de contar con un mapa detallado de la finca radica en que permite al productor tener una visión integral de los aspectos operativos de su negocio, lo que facilita la adopción de los lineamientos de las Buenas Prácticas Agrícolas, especialmente en las áreas de planeación y control.
    p Para realizar un mapeo de finca de manera precisa y estructurada, es fundamental seguir un proceso detallado que permita recopilar y organizar la información relevante. A continuación, se describen los pasos a seguir:

    .row.justify-content-center.align-items-center
      .col-lg-10
        ImagenInfografica.time-line-info
          template(v-slot:imagen)
            figure
              img.mb-4(src='@/assets/curso/temas/tema2/15.png', alt='Imagen de ayuda')

          .tarjeta.p-4(x="26.5%" y="38%" numero="")
            p <strong>Definición de objetivos y recolección de datos:</strong> se debe definir el propósito del mapeo (planificación de siembra, drenaje, riego) y recopilar información básica como dimensiones del terreno, coordenadas, tipo de suelo y uso previo.
            .time-line-info__number
              span 01

          .tarjeta.p-4(x="52%" y="38%" numero="")
            p <strong>Delimitación de la finca:</strong> se realiza un recorrido por el perímetro utilizando GPS o cinta métrica para marcar linderos, accesos, fuentes de agua y otros puntos clave que definirán el área de cultivo.

            .time-line-info__number
              span 02

          .tarjeta.p-4(x="77.5%" y="38%" numero="")
            p <strong>Levantamiento topográfico:</strong> se miden las pendientes, la altitud y las características del terreno para identificar zonas con riesgo de erosión o problemas de drenaje, fundamentales para el diseño agronómico.
            .time-line-info__number
              span 03

          .tarjeta.p-4(x="26.5%" y="87%" numero="")
            p <strong>Identificación de recursos y uso actual del suelo:</strong> se localizan las fuentes de agua, caminos, infraestructuras existentes y la vegetación actual, permitiendo planificar el riego, el manejo del suelo y la distribución de los cultivos.
            .time-line-info__number
              span 06

          .tarjeta.p-4(x="52%" y="87%" numero="")
            p <strong>Diseño del plano base y zonificación:</strong> con la información recolectada, se elabora un plano que muestra los límites de la finca, las pendientes, las fuentes de agua y los accesos, dividiendo el terreno en zonas específicas.
            .time-line-info__number
              span 05

          .tarjeta.p-4(x="77.5%" y="87%" numero="")
            p <strong>Verificación en campo y documentación final:</strong> se verifica en terreno que el plano coincida con la realidad, se ajustan detalles si es necesario y se elabora el mapa definitivo, incluyendo leyenda, escala y coordenadas para su uso técnico.
            .time-line-info__number
              span 04

        p La siguiente imagen proporciona un ejemplo de croquis de finca, una herramienta fundamental para la implementación de las Buenas Prácticas Agrícolas (BPA). Este croquis permite visualizar la distribución espacial de los recursos y las actividades en la finca, facilitando la planificación, el control y la toma de decisiones eficientes.

        .titulo-sexto.color-acento-contenido.mb-4
          h5 Figura 2.
          span <em>Croquis de finca.</em>
        img(data-aos="fade-up")(src="@/assets/curso/temas/tema2/16.png", alt="La figura presenta la integración tres lineamientos clave, que destacan para garantizar la calidad de las Buenas Prácticas Agrícolas, como son, protección sanitaria, inocuidad de alimentos y sostenibilidad ambiental.")
        figcaption Nota. Fuente: Japan International Cooperation Agency (2011).

    Separador

    #t_2_4(data-aos='zoom-in-right').titulo-segundo.color-acento-contenido
      h3 2.4	Entes certificadores de las BPA

    .row.justify-content-center.align-items-center.mb-4
      .mb-4.mb-lg-0.col-8.col-lg-4
        figure
          img(src='@/assets/curso/temas/tema2/17.png', alt='Ilustracion de acompañamiento')

      .col-lg-5
        .p-4.bg-color-acento-contenido
          p El Instituto Colombiano Agropecuario (ICA) es la entidad estatal responsable de garantizar la sanidad en los sectores agrícola y pecuario del país. Su labor se enfoca en promover la inocuidad y la producción limpia en las empresas del agro colombiano, con el propósito de proyectarlas hacia los mercados internacionales como proveedoras de productos seguros y de alta calidad. Además, el ICA coordina e intensifica los trabajos de investigación agropecuaria a nivel nacional, al tiempo que fomenta la enseñanza y la difusión de conocimientos en este ámbito.

      .d-none.d-lg-block.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema2/18.png', alt='Imagen de acompañamiento')

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-11
        p El ICA tiene la facultad de certificar fincas o predios productores de bienes agrícolas, acreditándolos como entidades que operan bajo las Buenas Prácticas Agrícolas (BPA), conforme a lo establecido en la Resolución 4174 del 6 de noviembre de 2009.
        p Por su parte, el Instituto Colombiano de Normas Técnicas y Certificación (ICONTEC) es el organismo encargado de auditar y supervisar a las empresas que buscan certificarse en distintos ámbitos. Además de desarrollar normas aplicables a diversos sectores industriales, adopta estándares internacionales reconocidos.
      .d-none.d-lg-block.col-lg-1
        figure
          img(src='@/assets/curso/temas/tema2/19.svg', alt='Imagen de acompañamiento')

    .row.justify-content-center.align-items-center
      .col-lg-10
        .bg-icontec.p-5
          p El ICONTEC es el único organismo colombiano aprobado internacionalmente por la institución Global GAP y cuenta con la acreditación del American National Standards Institute (ANSI) de los Estados Unidos.
          p Este instituto tiene la facultad de otorgar la certificación Global GAP en Buenas Prácticas Agrícolas, lo que permite a los productores de alimentos acceder a mercados internacionales. Asimismo, el ICONTEC dispone de una normativa propia sobre BPA, incluyendo la Norma Técnica Colombiana (NTC) 5400, que reúne los lineamientos y estándares que una empresa debe seguir para implementar un sistema de Buenas Prácticas Agrícolas.

    .m-footer

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
