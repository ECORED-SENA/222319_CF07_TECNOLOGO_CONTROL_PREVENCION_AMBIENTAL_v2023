<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Aplicación de protocolos de análisis de muestras

    .row.justify-content-center.align-items-center.bg-2.py-4.px-4.px-md-0.mb-4
      .col-md-5(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema1/img.png' alt='Imagen tema1')
      .col-md-6.bg-white.br-20.p-4(data-aos="fade-left")
        p.mb-0 Dentro de la química analítica, se incluye el análisis químico que es la parte práctica que aplica los métodos de análisis para resolver problemas relativos a la composición y naturaleza química de la materia. Los ámbitos de aplicación del análisis químico son muy variados, en la industria destaca el control de calidad de materias primas y productos terminados; en los laboratorios certificados de análisis quienes aseguran las especificaciones de calidad de las mercaderías; en el campo de la medicina, los análisis clínicos facilitan el diagnóstico de enfermedades entre otros.

    .row.justify-content-center.align-items-center
      .col-md-8.tema1.p-4
        .tarjeta-avatar-b.mb-4(data-aos="fade")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/tarj1.svg' alt='Icono decorativo')
          .tarjeta.bg-green
            .p-4
              h5.mb-4 Por esta razón
              p.mb-0 En esta unidad temática, se profundiza como se desarrolla en el análisis de las muestras que se lleva a cabo en el laboratorio. La química analítica es la rama de la química que tiene como finalidad el estudio de la composición química de un material o muestra, mediante diferentes métodos. Se divide en química analítica cuantitativa y química analítica cualitativa.
        .tarjeta-avatar-b.mb-4(data-aos="fade")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/tarj2.svg' alt='Icono decorativo')
          .tarjeta.bg-green
            .p-4
              h5.mb-4 Dentro de la química analítica
              p.mb-0 Se incluye el análisis químico que es la parte práctica que aplica los métodos de análisis para resolver problemas relativos a la composición y naturaleza química de la materia.
        .tarjeta-avatar-b.mb-4(data-aos="fade")
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/tarj3.svg' alt='Icono decorativo')
          .tarjeta.bg-green
            .p-4
              h5.mb-4 Los ámbitos de aplicación
              p.mb-0 Del análisis químico son muy variados, en la industria se destaca el control de calidad de materias primas y productos terminados; en los laboratorios certificados de análisis quienes aseguran las especificaciones de calidad de las mercaderías; en el campo de la medicina, los análisis clínicos facilitan el diagnóstico de enfermedades.
      .col-md-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema1/img2.svg' alt='Imagen decorativa')  
  
      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
