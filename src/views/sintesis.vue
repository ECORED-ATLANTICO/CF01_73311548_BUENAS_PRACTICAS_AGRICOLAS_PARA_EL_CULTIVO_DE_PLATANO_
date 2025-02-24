<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p Las prácticas agrícolas para el cultivo del plátano son un conjunto de técnicas y métodos utilizados para cultivar, cuidar y cosechar esta planta de manera eficiente y sostenible. Estas prácticas incluyen la selección adecuada del terreno, la preparación del suelo, la siembra de hijuelos, el riego, la fertilización, el control de plagas y enfermedades, la poda y el manejo postcosecha.
    p El cultivo del plátano se refiere al proceso agrícola de sembrar, cultivar y cosechar la planta de plátano (musa spp.), que es una de las frutas más consumidas en el mundo. Este cultivo implica una serie de prácticas que incluyen la selección del terreno adecuado, la preparación del suelo, la siembra de hijuelos, el riego, la fertilización, el control de plagas y enfermedades, y la cosecha de los frutos. 

    .row.justify-content-center
      .col-lg-10.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eu tincidunt erat. Fusce cursus mauris in nulla egestas vulputate. Phasellus viverra accumsan libero, sed luctus diam maximus euismod. Mauris sem risus, tincidunt vel libero in, lobortis commodo ante. Sed pulvinar luctus orci in rhoncus. Nulla ut dapibus risus, ac tempor est. Donec nulla augue, vehicula quis malesuada vitae, fermentum non nisi. Donec tincidunt nibh a magna bibendum rutrum. ")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
