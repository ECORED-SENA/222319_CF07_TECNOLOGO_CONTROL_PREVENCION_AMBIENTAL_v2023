<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.pb-0.p-4.pb-md-0.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Bases conceptuales


    .row.fondo-tema3.align-items-center.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.mb-4
          .col-md-8(data-aos="fade-right")
            .bloque-texto-c.bg-green2.box-shadow.p-3.px-4.mb-4
              i.fas.fa-quote-right.mb-2
              p.mb-3 Desde los tiempos de Wilhelm Ostwald (1894) la química analítica ha pasado de ser un arte a ser una ciencia con aplicaciones en la industria, medicina y en todas las ciencias. A modo de ilustración podemos citar:
              span.text-bold.mb-0 - Según Caballero M
          .col-md-4(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema3/img.png' alt='Imagen decorativa')

        .row(data-aos="fade-down") 
          SlyderF(columnas="col-lg-6 col-xl-4")
            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico1.svg' alt='Icono decorativo')
              p.text-center Poder determinar la efectividad de los sistemas de control de contaminación de los gases de escape de los automóviles (determinar óxido de nitrógeno y monóxido de carbono)
            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico2.svg' alt='Icono decorativo')
              p.text-center Diagnosticar enfermedades tiroideas a través de la medición cuantitativa de calcio iónico en suero.
            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico3.svg' alt='Icono decorativo')
              p.text-center Determinar cuantitativamente la cantidad de nitrógeno en alimentos para establecer su contenido en proteínas.   

            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico4.svg' alt='Icono decorativo')
              p.text-center El análisis de acero durante su fabricación permite ajustar las concentraciones de carbón, níquel y cromo, para alcanzar la fuerza, dureza, resistencia a la corrosión y ductilidad deseada.
            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico5.svg' alt='Icono decorativo')
              p.text-center El contenido en mercaptano del gas de ciudad se mide de forma continua para asegurar que el gas tiene el suficiente olor desagradable, para servir de aviso ante cualquier fuga peligrosa.
            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico6.svg' alt='Icono decorativo')
              p.text-center En la agricultura moderna se establecen las pautas de fertilización e irrigación a través de análisis cuantitativos de la planta y del suelo.

            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico7.svg' alt='Icono decorativo')
              p.text-center Las medidas cuantitativas de potasio, calcio e iones sodio en los fluidos corporales fisiológicos permiten estudiar el papel que estos iones tienen en la conducción de impulsos nerviosos y la contracción y relajación de los músculos.
            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico8.svg' alt='Icono decorativo')
              p.text-center Los químicos estudian los mecanismos de las reacciones químicas, a partir de estudios sobre las velocidades de reacción midiendo cuantitativamente en intervalos de tiempo iguales, el consumo de reactivos o la formación de productos en una reacción química.
            .tarjeta.h-tem3-tarj.color-acento-contenido.fondo-tema3-tarj.p-4
              .row.justify-content-center.mb-3
                .col-5
                  img(src='@/assets/curso/temas/tema3/ico9.svg' alt='Icono decorativo')
              p.text-center Las medidas cuantitativas analíticas juegan un rol importante en muchas áreas de investigación en química, biología, geología y otras ciencias. (pp.2-3).  
    
    Separador

    #t_3_1
    .titulo-segundo.color-acento-contenido
      h2 3.1 Reacciones químicas analíticas

    p(data-aos="fade") A continuación, conozca los tipos y particularidades de las reacciones químicas analíticas:

    .row
      .col-md-9.mb-4
        TabsA.color-acento-botones
          .tarjeta.bg-green4.p-4(titulo="Reacciones ácido-base")
            h5 Reacciones ácido-base
            p Implican una transferencia de protones. Para el estudio de los equilibrios en disolución quizás la definición más adecuada es la de Bronsted – Lowry, según la cual los ácidos se definen como especies capaces de ceder protones y bases como especies capaces de aceptar protones.
          .tarjeta.bg-green4.p-4(titulo="Reacciones de formación de complejos")
            h5 Reacciones de formación de complejos
            p En estas se producen transferencia de iones o moléculas. A pesar de lo amplio del concepto de compuesto complejo se considera normalmente una reacción de formación de complejos aquélla en que una o varias moléculas del disolvente son reemplazadas por otras especies químicas; estas especies unidas a un ion central se denominan ligandos. El ligando puede ser una molécula neutra o un ion.
          .tarjeta.bg-green4.p-4(titulo="Reacciones de precipitación")
            h5 Reacciones de precipitación
            p Son aquellas en las que además de haber un intercambio de iones o de moléculas tiene lugar la aparición de una fase sólida. La aparición de una fase sólida en el seno de un líquido, bien por adición de un reactivo que forme un producto insoluble con alguno de los iones de la solución, o bien por concentración del mismo líquido hasta sobrepasar la saturación, recibe el nombre de precipitación, y se llama precipitado al producto sólido que se ha formado.
          .tarjeta.bg-green4.p-4(titulo="Reacciones redox")
            h5 Reacciones redox
            p Son aquellas que se realizan mediante un intercambio de electrones, luego para que se produzca una reacción redox tiene que haber una especie que ceda electrones(reductor) y otra especie que los acepte(oxidante) el reductor se transforma en su forma oxidada y el oxidante en su forma reducida.
      .col-md-3
        figure
          img.mx-auto(src='@/assets/curso/temas/tema3/img3-1.png' alt='Imagen decorativa')


    Separador

    #t_3_2
    .titulo-segundo.color-acento-contenido
      h2 3.2 Métodos analíticos volumétricos 

    .row.fondo-tema3-2.align-items-center.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.mb-4
          .col-md-7.mb-4(data-aos="fade-right")
            p.mb-5 El análisis volumétrico se fundamenta lo mismo que el gravimétrico en una reacción química cuantitativa, donde la cantidad de sustancia que se investiga reacciona directamente con un volumen de solución de concentración conocida o con otra sustancia químicamente equivalente. Los métodos volumétricos tienen la ventaja de que son más rápidos y más sencillos que los gravimétricos.
            h3.subt.text-white Patronizada
            p.mb-4 Una vez preparada la solución con la que va a reaccionar la solución desconocida, debe ser patronizada, proceso conocido como estandarización de la solución, lo que produce una solución patrón de concentración conocida.
            p.bg-green2.p-4 La concentración de la solución patrón se determina valorando esta solución con una cantidad exactamente pesada de un compuesto puro conocido como patrón primario.
          .col-md-5(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema3/img3-2.png' alt='Imagen decorativa')

    .row.justify-content-center.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        h3.subt.text-white.mb-4 Característica de un patrón primario
        ol.lista-ol.ms-md-5.ms-3
          li 
            span.text-bold a. 
            | Debe tener alta pureza.
          li 
            span.text-bold b. 
            |  Estable a la humedad, luz, oxígeno etc.
          li 
            span.text-bold c. 
            | No debe ser higroscópico, delicuescente ni eflorescente.
          li 
            span.text-bold d. 
            | Barato, fácil de conseguir.
          li 
            span.text-bold e. 
            | Tener un peso equivalente alto.
        p El patrón primario que se utiliza para la estandarización de soluciones NaOH es el biftalato de potasio.
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema3/img3-2-1.png' alt='Imagen decorativa')

    .row.fondo-tema3-2-1.align-items-center.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.py-5
          .col-12(data-aos="fade")
            h3.subt.text-white.mb-4 Equivalencias
            p.mb-0 En la volumetría se agrega un volumen de la solución patrón que reacciona con la solución problema equivalentemente. Esta situación se alcanza en el llamado punto de equivalencia es decir en el punto estequiométrico de la reacción.

    .row.justify-content-center.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        h3.subt.text-white.mb-4 Titulación
        p La detección del punto final de la titulación se logra mediante el uso de los indicadores, los cuales cambian de color como consecuencia del cambio de la concentración del ion hidronio en los alrededores del punto de equivalencia.
        p Tipos de reacciones volumétricas.
        ul.lista-ul--color.ms-md-5.ms-3
          li 
            i.fas.fa-check
            | Reacciones ácido – base o de neutralización.
          li 
            i.fas.fa-check
            | Reacciones de oxidación – reducción.
          li 
            i.fas.fa-check
            | Reacciones de precipitación.
          li 
            i.fas.fa-check
            | Reacciones de formación de complejos.    
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema3/img3-2-2.png' alt='Imagen decorativa')

    .row.fondo-tema3-2-1.align-items-center.pb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.py-5
          .col-12(data-aos="fade")
            h3.subt.text-white.mb-4 Resumen gráfico
            p.mb-5 Se puede resumir de la siguiente manera:
            .titulo-sexto.color-acento-contenido
              p.mb-0 Mapa conceptual de la química analítica
          .col-md-10
            figure
              img.mx-auto(src='@/assets/curso/temas/tema3/mapa-conceptual.svg' alt='Mapa conceptual de la química analítica')



</template>

<script>
export default {
  name: 'Tema3',
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
