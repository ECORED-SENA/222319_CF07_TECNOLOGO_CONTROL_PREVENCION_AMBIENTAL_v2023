<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Equipos de análisis de agua

    .row.justify-content-center.mb-5
      .col-md-6(data-aos="fade-right")
        p Las técnicas instrumentales de análisis tienen gran relevancia en el monitoreo de la calidad del agua, como también durante el proceso de tratamiento de agua residual. La concentración de metales y aniones en el agua se pueden detectar, empleando técnicas modernas de análisis.
        p.bg-green3.p-4.mb-0 Es de gran importancia hallar las concentraciones de estos componentes para tener un conocimiento de su calidad y corroborar si se cumple con los límites máximos permisibles nacionales e internacionales.
        p.mt-3 Visita la tabla 7 en el anexo 8 donde se muestran algunos equipos utilizados en los análisis de agua.
        .tarjeta.bg-degrade-green.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/curso/temas/tema6/icono.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 Equipos utilizados en los análisis de agua
                  p.text-small.mb-0 Visita la tabla 7 en el anexo 8 donde se muestran algunos equipos utilizados en los análisis de agua.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Tabla7-Equipos-instrumentales-analisis.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      .col-md-6(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema6/img.png' alt='Imagen tema6')

</template>

<script>
export default {
  name: 'Tema6',
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
