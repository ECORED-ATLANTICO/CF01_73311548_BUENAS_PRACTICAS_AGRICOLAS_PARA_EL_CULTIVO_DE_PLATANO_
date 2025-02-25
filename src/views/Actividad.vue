<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Buenas prácticas.',
      titulo: 'Cuestionario',
      introduccion:
        '<b> Objetivo:</b> Identificar buenas prácticas del cultivo del plátano.',
      barajarPreguntas: true,
      preguntas: [
        {
          id: 1,
          texto:
            'Al cultivo de plátano se le debe realizar una serie de prácticas culturales para evitar problemas fitosanitarios.',
          imagen: require('@/assets/actividad/1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de la normativa que orienta el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 2,
          texto:
            'La planta de plátano se debe mantener libre de malezas porque estas compiten con el cultivo principal por nutrientes, agua y luz.',
          imagen: require('@/assets/actividad/2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 3,
          texto:
            'Cuando las plantas de plátano son pequeñas tienen más espacio y se puede poblar de malezas a su alrededor con facilidad.',
          imagen: require('@/assets/actividad/3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 4,
          texto:
            'Control químico: este se aplica de manera selectiva en las plataneras que son comerciales.',
          imagen: require('@/assets/actividad/3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'False',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 5,
          texto:
            'Control biológico: este se realiza utilizando insectos, hongos y/o bacterias para el control de enfermedades y plagas del cultivo.',
          imagen: require('@/assets/actividad/2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'False',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 6,
          texto:
            'El plateo es una técnica que se le realiza al plátano y consiste en mantener el plato de la planta llena de malezas.',
          imagen: require('@/assets/actividad/1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'False',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 7,
          texto:
            'Desmanche es una técnica que consiste en extraer todos los colinos que surgieron de la planta madre porque afectan su desarrollo debido a la competencia de luz, agua y nutrientes',
          imagen: require('@/assets/actividad/4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'False',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 8,
          texto:
            'Deshoje es una labor que consiste en secar las hojas, dobladas y las que se encuentran en la parte de debajo de la planta.',
          imagen: require('@/assets/actividad/4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'False',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 9,
          texto:
            'En el cultivo de plátano se hace necesario el manejo de plagas mediante mecanismos como control biológico o mecánico.',
          imagen: require('@/assets/actividad/5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'False',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 10,
          texto:
            'El proceso de cosecha en fincas plataneras está conformado por tres operaciones importantes tales como el corte de los racimos, el transporte y el empacado.',
          imagen: require('@/assets/actividad/5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'False',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento de los programas que orientan el desarrollo educativo en el país.',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo.',
        },
      ],
      mensaje_final_aprobado:
        '¡Excelente! Lo felicito, ha superado la actividad y demuestra sólidos conocimientos sobre el componente formativo.',
      mensaje_final_reprobado:
        'No ha superado la actividad. Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
