<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción


    .row.justify-content-center.align-items-center.bg-1.py-4.px-4.px-md-0
      .col-md-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/intro/img.svg' alt='Imagen introducción')
      .col-md-6.bg-white.br-20.p-4(data-aos="fade-left")
        p La importancia del análisis de las muestras que se llevan al laboratorio radica particularmente en el tratamiento que se le de a las mismas, desde la toma, el embalaje, el transporte y su respectiva identificación.
        p.mb-0 Puesto que, si las muestras son alteradas en alguno de los procesos de la muestra, su posterior análisis entra en un margen de baja confiabilidad que se traduce en un resultado de poca fiabilidad.

    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
