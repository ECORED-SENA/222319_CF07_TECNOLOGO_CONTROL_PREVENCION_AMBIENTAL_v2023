<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 9
      h1 Protocolo para análisis de olores

    .bloque-texto-g.color-secundario.tema-pb.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema9/img.jpg')})`}")
      .bloque-texto-g__texto.row.p-4
        p.mb-md-5.pb-md-5(data-aos="fade") La olfatometría es una técnica de toma de muestras y análisis de olores, que unida al desarrollo de sistemas de modelización de la dispersión, permite evaluar las molestias producidas por malos olores y determinar el origen de las mismas. Los estudios olfatométricos constituyen una herramienta de gran utilidad para el control y reducción de los malos olores emitidos por distintos tipos de fuentes. Estos estudios permiten no sólo determinar el grado de molestia creado en el entorno, sino también identificar las fuentes de olor realmente importantes y adoptar sistemas eficaces de eliminación.
        .row.justify-content-center.cta-sobre(data-aos="fade-down")
          .col-md-11.col-12.tarjeta.bg-degrade-green.p-3
            .row.justify-content-around.align-items-center
              .col-3.col-sm-2.col-lg-2
                img.px-2(src="@/assets/curso/temas/tema6/icono.svg")
              .col
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0.text-white
                    h4.mb-1 Protocolo para análisis de olores
                    p.text-small.mb-0 Para profundizar en el tema “Protocolo para análisis de olores”, le invitamos a estudiar con atención este documento. 
                  .col-sm-auto
                    a.boton.color-acento-botones(:href="obtenerLink('/downloads/Protocolo-analisis-olores.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download


</template>

<script>
export default {
  name: 'Tema9',
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
