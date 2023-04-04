<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Equipos para análisis de suelos

    .row.justify-content-center.align-items-center.mb-5
      .col-md-6(data-aos="fade-right")
        p La calidad del suelo ha sido definida por la Sociedad de Ciencias del Suelo de América como “la capacidad de un tipo específico de suelo para funcionar, dentro de los límites de los ecosistemas naturales, para sostener la productividad vegetal y animal, mantener y/o mejorar la calidad del agua y del aire, y apoyar la salud y la vivienda”. Esta funcionalidad del suelo varía dependiendo del interés del observador: para los administradores puede significar la capacidad del suelo de mejorar la productividad y mantener los recursos del suelo para el futuro; para los conservacionistas mantener los recursos del suelo y la protección del medio ambiente; para los consumidores la producción de alimentos sanos y de bajo costo; para los ambientalistas la capacidad de sustentar la biodiversidad, la calidad del agua, el ciclo de nutrientes y la producción de biomasa.
      .col-md-6(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema8/img.png' alt='Imagen decorativa')

    .row.justify-content-center.align-items-center.mb-5
      .col-md-5(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema8/img2.png' alt='Imagen decorativa')
      .col-md-7(data-aos="fade-left")
        .bloque-texto-c.bg-green4.p-4.mb-4
          i.fas.fa-quote-right.mb-2
          p.mb-3 La calidad del suelo, entonces, es cada vez más aceptada como un indicador integral de la calidad ambiental, seguridad alimentaria y viabilidad económica. 
          p.mb-0 Por lo tanto, es un indicador ideal de la gestión sostenible de la tierra.
          p.mb-4 Es así, que se hace indispensable conocer en qué estado y que tan funcional es un suelo para tomar las decisiones pertinentes de uso y manejo; de esta manera el análisis de suelos entra a jugar un papel importantísimo en los diagnósticos de calidad ya que es éste el que nos va a permitir reconocer de manera puntual cada una de las características físicas y químicas. (pp 51-52).
          span.text-bold.mb-0 - De acuerdo a Gómez J.C (2013)
        .tarjeta.bg-degrade-green.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img.px-2(src="@/assets/curso/temas/tema6/icono.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 Equipos utilizados en los análisis del suelo
                  p.text-small.mb-0 En la tabla 9, contenida en el anexo 12, se muestran algunos equipos utilizados en los análisis del suelo. Conózcalos.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Tabla9-Equipos-utilizados-en-analisis-suelo.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download    


</template>

<script>
export default {
  name: 'Tema8',
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
