<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 11
      h1 Tratamiento y disposición de los residuos generados en el laboratorio

    .bloque-texto-g.color-secundario.tema-pb.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema11/img.jpg')})`}")
      .bloque-texto-g__texto.row.p-4
        p.mb-md-5.pb-md-5(data-aos="fade") Se abordarán las características de tratamiento y disposición de los residuos generados en el laboratorio; estos, son los productos químicos que quedan en pequeñas cantidades como restos inutilizables y son residuos especiales ya que pueden ser residuos de disolventes orgánicos halogenados y no halogenados, compuestos mercuriados, ácidos orgánicos e inorgánicos, bases, sales y demás compuestos que se hallen en el laboratorio.
        .row.justify-content-center.cta-sobre(data-aos="fade-down")
          .col-md-11.col-12.tarjeta.bg-degrade-green.p-3
            .row.justify-content-around.align-items-center
              .col-3.col-sm-2.col-lg-2
                img.px-2(src="@/assets/curso/temas/tema6/icono.svg")
              .col
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0.text-white
                    h4.mb-1 Tratamiento y disposición residuos
                    p.text-small.mb-0 Para profundizar en el tema “tratamiento y disposición de los residuos generados en el laboratorio”, le invitamos a estudiar con atención este documento. 
                  .col-sm-auto
                    a.boton.color-acento-botones(:href="obtenerLink('/downloads/Tratamiento-disposicion-de-residuos-generados-en-laboratorio.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download


</template>

<script>
export default {
  name: 'Tema11',
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
