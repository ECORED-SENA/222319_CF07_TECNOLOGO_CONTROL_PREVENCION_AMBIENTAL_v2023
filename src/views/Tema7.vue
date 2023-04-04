<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido.mb-0
      .titulo-principal__numero
        span 7
      h1 Protocolos de análisis de suelos

    .row.fondo-tema7.align-items-center.pt-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.mb-4
          .col-md-4(data-aos="fade-right")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema7/img.png' alt='Imagen decorativa')
          .col-md-8(data-aos="fade-left")
            .bloque-texto-c.p-4.mb-4
              i.fas.fa-quote-right.mb-2
              p.mb-3 El suelo es un cuerpo natural que conforma el hábitat de bacterias, hongos, levaduras, virus y plantas superiores, entre otros, que sirve para la alimentación de los animales y del hombre a través de los ciclos tróficos.
              span.text-bold.mb-0 - Según Fernández L.C (2006)

        .row.justify-content-between
          .col-md-4.mb-4(data-aos="fade-down")
            .bg-color-acento-contenido.h-410.br-20.px-3.py-4 
              .row.justify-content-center.mb-3
                .col-4
                  figure.px-md-2
                    img.mx-auto(src='@/assets/curso/temas/tema7/ico1.svg' alt='Icono decorativo')  
              p.text-center El suelo y los microorganismos mantienen los sistemas ecológicos, ya que le aportan componentes químicos y minerales (como resultado de la biodegradación) y complejos orgánicos como ácidos húmicos y fúlvicos, enzimas, vitaminas, hormonas y antibióticos; además, albergan una rica reserva genética.
          .col-md-4.mb-4(data-aos="fade-down")
            .bg-color-acento-contenido.h-410.br-20.px-3.py-4 
              .row.justify-content-center.mb-3
                .col-4
                  figure.px-md-2
                    img.mx-auto(src='@/assets/curso/temas/tema7/ico2.svg' alt='Icono decorativo')  
              p.text-center Por la gran importancia que representa el suelo para la vida del hombre y de todos los seres vivos, este recurso se debe conservar. Sin embargo, en la actualidad está seriamente amenazado por la práctica de sistemas de producción inadecuados o mal aplicados, que incluso han acelerado los procesos de erosión y desertificación de grandes zonas.
          .col-md-4.mb-4(data-aos="fade-down")
            .bg-color-acento-contenido.h-410.br-20.px-3.py-4  
              .row.justify-content-center.mb-3
                  .col-4
                    figure.px-md-2
                      img.mx-auto(src='@/assets/curso/temas/tema7/ico3.svg' alt='Icono decorativo')        
              p.text-center De igual forma, la industrialización y urbanización han generado una gran cantidad de desechos que son incorporados al suelo, lo cual ocasiona tanto la reducción de su fertilidad como la modificación de sus procesos naturales. Por lo anterior, es necesario estudiar las características particulares del suelo para determinar su grado de contaminación y, consecuentemente, aplicar alguna de las tecnologías de remediación existentes. (p.13).
    

    .row.justify-content-center.align-items-center.mb-5
      .col-md-8.mb-4(data-aos="fade-right")
        .tarjeta.bg-degrade-green.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img.px-md-3(src="@/assets/curso/temas/tema6/icono.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 Protocolo de análisis de suelos
                  p.text-small.mb-0 Para profundizar en el tema “Protocolo de análisis de suelos”, le invitamos a estudiar con atención este documento. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Protocolo-analisis-suelos.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      .col-md-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema7/img2.png' alt='Imagen decorativa')  

</template>

<script>
export default {
  name: 'Tema7',
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
