<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 12
      h1 Análisis de datos

    .bloque-texto-g.color-primario.tema-pb.p-3.p-sm-4.p-md-5(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema12/img.jpg')})`}")
      .bloque-texto-g__texto.row.p-4
        p.mb-0 Los análisis fisicoquímicos y microbiológicos de las muestras ambientales (agua, suelo, aire y residuos sólidos) comprenden la separación, identificación y determinación de las cantidades relativas de los componentes de una muestra; es decir es un análisis cuantitativo que determina ¿cuánto? de determinado componente está presente en la muestra analizada. El resultado numérico tendrá significado dentro del contexto del análisis, por tanto, es necesario realizar un tratamiento matemático que lleve al valor que mejor represente el resultado buscado.


    Separador

    #t_12_1
    .titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 12.1	Las cifras significativas

    .row
      .col-md-5.mb-4.mb-md-0(data-aos="fade-right")
        p Las cifras significativas de una medida indican, implícitamente, la incertidumbre o inexactitud de la medida sin necesidad de incluir el símbolo “±”. El reporte debe contener un solo dígito incierto o inexacto: el último, que corresponde a la apreciación del instrumento.
        p “Las cifras significativas son los dígitos significativos en una cantidad medida o calculada”) y se sobreentiende que el último dígito es incierto o inexacto. En el caso mostrado en la siguiente imagen, con la pipeta A (4 mL) se está reportando una sola cifra significativa; con la pipeta B (4,0 mL) se están reportando dos cifras significativas.
      .col-md-7(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema12/img12-1.svg' alt='Imagen decorativa')    

    
    Separador

    #t_12_2
    .titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 12.2	Reglas para utilizar cifras significativas

    p(data-aos="fade") A continuación, le presentamos una serie de reglas que le permitirán utilizar cifras significativas.

    .row.justify-content-center.my-5(data-aos="fade-left")
      .col-lg-10.position-relative
        .avatar
          figure
            img(src="@/assets/curso/temas/tema12/img12-2.svg").img450
        .crd.crd--avatarHorizontal.crd--first.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tema12/1.svg", alt="alt").img100
            .col
              h5.mb-0 Todo dígito diferente de cero es una cifra significativa:
              p.mb-0 6 mL tiene una sola cifra significativa. 6,0 mL tiene dos cifras significativas; 640 mL tiene tres cifras significativas.
        .crd.crd--avatarHorizontal.crd--2.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tema12/2.svg", alt="alt").img100
            .col
              h5.mb-0 Todo cero que se encuentre entre dos dígitos diferentes de cero, es una cifra significativa: 
              p.mb-0 307 g tiene tres cifras significativas; 5024 mL tiene cuatro cifras significativas.
        .crd.crd--avatarHorizontal.crd--last.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tema12/3.svg", alt="alt").img100
            .col
              h5.mb-0 Los ceros a la izquierda del primer dígito diferente de cero no son cifras significativas:
              p.mb-0 0,305 kg tiene tres cifras significativas; 0,0085 L tiene dos cifras significativas; 0,00003204 km tiene cuatro cifras significativas; 0,05 cm3 tiene una sola cifra significativa.


    p.mb-4(data-aos="fade") Una forma sencilla de diferenciar cuales ceros son cifras significativas, es cambiar de notación decimal a notación científica ya que las cifras significativas se mantienen sin importar la notación.

    .row.justify-content-center.mb-5
      .col-lg-7.col-md-8.col-sm-10.col-12
        .tabla-c.tema-10-1.sin-sombra.borde-tabla(data-aos="fade-down-right")
          table
            tr
              td.bg-color-acento-contenido.text-center
                h4-mb-0 Notación Decimal
              td.bg-color-acento-contenido.text-center
                h4-mb-0 Notación Científica
              td.bg-color-acento-contenido.text-center
                h4-mb-0 Cifras significativas
            tr
              td.text-center 0,305
              td.text-center = 3,05 x 10─1
              td.text-center Tiene tres cifras significativas
            tr
              td.text-center 0,0086
              td.text-center = 8,6 x 10─3
              td.text-center Tiene dos cifras significativas
            tr
              td.text-center 0,00001004
              td.text-center = 1,004 x 10─5
              td.text-center.p-0.m-0 Tiene cuatro cifras significativas
            tr
              td.text-center 0,03
              td.text-center = 3 x 10─2
              td.text-center Tiene una sola cifra significativa


    p.mb-4(data-aos="fade") De acuerdo a Luzardo M (2016):

    .row.justify-content-center.my-5(data-aos="fade-left")
      .col-lg-10.position-relative
        .avatar
          figure
            img(src="@/assets/curso/temas/tema12/img12-2-2.svg").img450
        .crd.crd--avatarHorizontal.crd--first.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tema12/1.svg", alt="alt").img100
            .col
              h5.mb-1 Todos los ceros a la derecha de una cifra diferente de cero son cifras significativas. 
              p.mb-0 -  2,00 m tiene tres cifras significativas
              p.mb-0 -  3,2400 L tiene cinco cifras significativas.
              p.mb-0 - 120 L tiene tres cifras significativas
              p.mb-3 -  200 g tiene tres cifras significativas
              p.mb-0 25000 mL tiene cinco cifras significativas si se midió con un instrumento cuya apreciación es 1 mL, pero sólo tendrá tres cifras significativas si la apreciación es 100 mL.
        .crd.crd--avatarHorizontal.crd--2.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tema12/2.svg", alt="alt").img100
            .col
              h5.mb-1 Cuando se desee expresar una cantidad sin que queden dudas, es recomendable usar la notación científica:
              p.mb-0 - 120 L con sólo dos cifras significativas se expresará 1,2 x 102 L.
              p.mb-0 - 25000 mL con tres cifras significativas se expresará 2,50 x 104 mL.
        .crd.crd--avatarHorizontal.crd--3.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tema12/3.svg", alt="alt").img100
            .col
              h5.mb-0 Cuando se resuelven problemas, las cifras significativas deberán indicarse en el enunciado.
              p.mb-0 En caso de duda se recomienda al estudiante utilizar al menos tres cifras. significativas en todos los cálculos.
        .crd.crd--avatarHorizontal.crd--4.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tema12/4.svg", alt="alt").img100
            .col
              h5.mb-0 Cuando se resuelven problemas que implican datos experimentales, se deben tomar las cifras significativas que indique el instrumento de medida. (p.24)    

    Separador

    #t_12_3
    .titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 12.3	Exactitud y precisión

    .row.align-items-center.mb-1
      .col-md-4.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema12/img12-3.png' alt='Imagen decorativa')
      .col-md-8(data-aos="fade-left")   
        p Cuando se analizan los datos obtenidos en un análisis es importante tomar en cuenta la exactitud y la precisión de los valores obtenidos experimentalmente.
        p.bg-green4.px-4.py-3.mb-3 Se denomina #[b #[em exactitud]] a la cercanía de un resultado al valor considerado como verdadero. Una medida será más exacta mientras más cerca del valor verdadero se encuentre. Para determinar la exactitud de un resultado es necesario conocer previamente el valor verdadero (valor real) de la medida.Se denomina precisión de un grupo de medidas a la dispersión o separación de las mismas. Un grupo de medidas tendrá mayor precisión cuanto más cercanas se encuentren unas de otras. Se puede determinar la precisión sin necesidad de conocer el valor verdadero o real.
        p La exactitud y la precisión no son dependientes entre sí: puede existir precisión sin exactitud y viceversa.

    p.mb-5 Para comprender mejor estos términos, se utilizará como ejemplo una “diana” de tiro al blanco. El valor considerado como valor real o valor verdadero es el centro de la diana y los puntos corresponden a los lanzamientos realizados que equivaldrían a los resultados de los análisis.

    .row.justify-content-center
      .col-lg-8.col-md-10.col-sm-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          p.mb-0 Exactitud y precisión
        .tabla-c.sin-sombra.borde-tabla.tema-12-3(data-aos="fade-down")
          table
            caption.mt-2
             p.mb-0 Nota.Luzardo M. (s, f) Exactitud y precisión
            tr
              td.bg-color-acento-contenido
                img(src='@/assets/curso/temas/tema12/tabl1.png')
              td.bg-color-acento-contenido
                img(src='@/assets/curso/temas/tema12/tabl2.png')
              td.bg-color-acento-contenido
                img(src='@/assets/curso/temas/tema12/tabl3.png')
              td.bg-color-acento-contenido
                img(src='@/assets/curso/temas/tema12/tabl4.png')
            tr
              td 1- Precisos, pero no exactos (cercanos entre sí, pero desviados del centro).
              td 2- Exactos, pero no precisos (cercanos al centro, pero alejados entre sí).
              td 3- Ni precisos ni exactos.
              td 4- Precisos y exactos (cercanos entre sí y todos cerca del centro).

    Separador

    #t_12_4
    .titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 12.4 Tratamiento matemático de los datos

    p(data-aos="fade") En el siguiente ejercicio se muestra el tratamiento matemático de un análisis de una muestra de agua, en el cual se obtienen una serie de valores que deben ser estudiados y sometidos a un tratamiento estadístico, a fin de reportar un único resultado. 
    p.mb-5(data-aos="fade") En un laboratorio de análisis ambientales, tecnología en prevención y control ambiental del SENA, se desea determinar el contenido de hierro en el agua de una laguna, para lo cual se toman diez muestras y se analizan en el laboratorio. Un laboratorio externo de control de carácter oficial reporta que el contenido de cloro en la laguna es de 250,0 mg/L de Cl. Del análisis se obtuvieron los siguientes resultados:

    .row.justify-content-center.mb-5
      .col-lg-8.col-md-10.col-sm-12
        .tabla-c.sin-sombra.borde-tabla.tema-12-3(data-aos="fade-down")
          table
            tr
              td.bg-color-acento-contenido.text-center
                h4.mb-0 No. de la muestra
              td.bg-color-acento-contenido.text-center             
                h4.mb-0 Contenido de Cl (mg)/L
              td.bg-color-acento-contenido.text-center             
                h4.mb-0 No. de la muestra
              td.bg-color-acento-contenido.text-center             
                h4.mb-0 Contenido de Cl (mg)/L
            tr
              td.text-center 1
              td.text-center 224,3
              td.text-center 6
              td.text-center 261,7
            tr
              td.text-center  2
              td.text-center 240,4
              td.text-center  7
              td.text-center 229,4
            tr
              td.text-center  3
              td.text-center 246,3
              td.text-center 8
              td.text-center  255,5
            tr
              td.text-center 4
              td.text-center 239,4
              td.text-center 9
              td.text-center 235,5
            tr
              td.text-center 5
              td.text-center 253,1
              td.text-center 10
              td.text-center 249,7

    .row.fondo-tema12-4.align-items-center.mb-4.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center
          h4.t-green.mb-4 Media
          p.mb-3 Es el promedio matemático de los valores. Se representa con el símbolo: X
          p.mb-0 #[b X = 224,3+240,4+246,3+239,4+253,1+ 261,7+229,4+255,5+235,5+ 249,7   = 243,53 mg Cl 10]

    
    h4.t-green.mb-4 Mediana
    p.mb-5 Se ordenan los valores en forma creciente y la mediana será el valor central. Si el número de muestras es par, la mediana se calcula con el promedio de los dos valores centrales. Se representa Xmed.

    .row.justify-content-center.mb-5
      .col-lg-8.col-md-10.col-sm-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Tabla 4. 
          span Mediana
        .tabla-c.sin-sombra.borde-tabla.tema-12-3(data-aos="fade-down")
          table.text-center
            caption.mt-2 
              p.mb-0 Nota. Luzardo M (s,f) Toma de muestras
            tr
              td.bg-color-acento-contenido.p-2 
                h4.mb-0.text-center Muestra
              td.bg-color-acento-contenido.p-2
                h4.mb-0.text-center Mg de Cl
              td.bg-color-acento-contenido.p-2
              td.bg-color-acento-contenido.p-2
              td.bg-color-acento-contenido.p-2
            tr
              td.p-2 1
              td.p-2 224,3
              td.p-2 
              td.p-2
              td(rowspan="10").p-2 X med= 240,4+246,3= 243,42
            tr
              td.p-2 7
              td.p-2 229,4
              td.p-2 
              td.p-2 
            tr
              td.p-2 9
              td.p-2 235,5
              td.p-2 
              td.p-2
            tr
              td.p-2 4
              td.p-2 239,4
              td.p-2 
              td(rowspan="3").p-2 Valores Centrales
            tr
              td.p-2 2
              td.p-2 240,4
              td.p-2 
            tr
              td.p-2 3
              td.p-2 246,3
              td.p-2
            tr
              td.p-2 10
              td.p-2 249,7
              td.p-2 
              td.p-2 
            tr
              td.p-2 5
              td.p-2 253,1
              td.p-2 
              td.p-2 
            tr
              td.p-2 8
              td.p-2 255,5
              td.p-2 
              td.p-2 
            tr
              td.p-2 6
              td.p-2 261,7
              td.p-2 
              td.p-2

    .row.fondo-tema12-4-2.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center
          h4.t-green.mb-4 Moda
          p.mb-3 Es el valor que se repite más veces en una serie. Esto se aplica para series muy grandes. En química analítica pocas veces se reporta utilizando la moda; en el ejercicio no hay ningún valor que se repita. Al reportar un resultado se debe indicar la dispersión de las medidas, por tanto, con solo reporta la media o la mediana no es suficiente. Para ello se debe calcular la desviación.


    h4.t-green.mb-4 Desviación absoluta
    p.mb-1 Es la diferencia (en valor absoluto) de cada valor con respecto a la media.
    p.mb-5 Desviación media: es el promedio de las desviaciones absolutas.

    .row.justify-content-center.mb-5
      .col-lg-9.col-md-10.col-sm-12
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          h5 Tabla 5. 
          span Tabla 18 Desviación
        .tabla-c.sin-sombra.borde-tabla.tema12-tabla-5(data-aos="fade-down-right")
          table.text-center
            caption
              p.mb-0 Nota. Luzardo M (s,f) Desviación estándar
            tr
              td.bg-color-acento-contenido
                h4.mb-0 Muestra
              td.bg-color-acento-contenido
                h4.mb-0 Mg de Cl
              td.bg-color-acento-contenido
                h4.mb-0 Desviación absoluta │Xi - media│
              td.bg-color-acento-contenido
            tr
              td 1
              td 224,3
              td 
              td(rowspan="11").bg-color-acento-contenido
                .row.align-items-center.mb-3
                  img(src='@/assets/curso/temas/tema12/tabl5-formula.svg')
                .row.align-items-center.mb-3
                  img(src='@/assets/curso/temas/tema12/tabl5-formula2.svg')
                p D media = 19, 2+14, 1+8, 1+4, 1+3, 1+2, 8+6, 2+9, 6+12, 0
                p 10
                p = 9,73…         9,7 
            tr
              td 7
              td 229,4
              td 
            tr
              td 9
              td 235,5
              td 
            tr
              td 4
              td 239,4
              td 
            tr
              td 2
              td 240,4
              td 
            tr
              td 3
              td 246,3
              td 
            tr
              td 10
              td 249,7
              td 
            tr
              td 5
              td 253,1
              td 
            tr
              td 8
              td 255,5
              td 
            tr
              td 6
              td 261,7
              td 
            tr.bg-color-acento-contenido
              td
                p.mb-0 6
                p.mb-0 Media
                p.mb-0 Mediana
                p.mb-0 Desviación media
              td
                p.mb-0 261,7
                p.mb-0 243,5
                p.mb-0 243,4
                p.mb-0 9,7
              td
                p.mb-0 18,2   __
                p.mb-0 ______________
                p.mb-0 _
                p.mb-0 _____________


    .row.fondo-tema10-1-1.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center
          h4.t-green.mb-4 Desviación estándar
          p.mb-4 Desviación estándar: representa la dispersión de las medidas individuales con respecto a la media y se utiliza en química analítica para reportar el resultado de un grupo de datos entre tres y veinte. La desviación estándar y la media tienen las mismas unidades.
          .row.justify-content-center
            .col-md-3
              figure
                img.mx-auto(src='@/assets/curso/temas/tema12/form.svg' alt='Formula')
            .col-md-5
              p Para grupos mayores de veinte datos, se usa n en lugar de (n ─ 1). Algunas calculadoras científicas utilizan n o n-1 como fórmula predeterminada, sin tomar en cuenta el número de valores utilizados; por ello es recomendable consultar el manual de cada calculadora antes de utilizar esa función.

    p.mb-4 Se puede reportar la desviación estándar relativa a la media. Este valor no tiene unidades:

    .row
      .col-md-5
        figure
          img.mx-auto(src='@/assets/curso/temas/tema12/form2.svg' alt='Formula')


    .row.justify-content-center.my-5.mb-5
      .col-xl-10.col-lg-12.mb-4
        .tabla-c.sin-sombra.borde-tabla.tema12-tabla-6(data-aos="fade-down")
          table.text-center
            tr
              td.bg-color-acento-contenido
                h4.mb-0 Muestra
              td.bg-color-acento-contenido
                h4.mb-0 Mg de Cl (X)
              td.bg-color-acento-contenido
                h4.mb-0 Desviación absoluta │X - media│
              td.bg-color-acento-contenido
                h4.mb-0 Cuadrado de las desviaciones absolutas (X - media)<sup>2</sup>
              td.bg-color-acento-contenido(rowspan="11")
                img.mx-0(src='@/assets/curso/temas/tema12/tabl-form.svg')
                img.mt-5.mx-0(src='@/assets/curso/temas/tema12/tabl-form2.svg')
            tr
              td 1
              td 
                p.mb-0 22
                p.mb-0 4,3
              td
                p.mb-0 19,2
              td
                p.mb-0 368,6
            tr
              td 7
              td
                p.mb-0 22
                p.mb-0 9,4
              td 
                p.mb-0 14,1
              td
                p.mb-0 198,8
            tr
              td 9
              td 
                p.mb-0 23
                p.mb-0 5,5
              td
                p.mb-0 8,1
              td
                p.mb-0 65,6
            tr
              td 4
              td 
                p.mb-0 23
                p.mb-0 9,4
              td
                p.mb-0 4,1
              td
                p.mb-0 16,8
            tr
              td 2
              td 
                p.mb-0 24
                p.mb-0 0,4
              td 
                p.mb-0 3,1
              td
                p.mb-0 9,6
            tr
              td 3
              td 
                p.mb-0 24
                p.mb-0 6,3
              td 
                p.mb-0 2,8
              td
                p.mb-0 7,8
            tr
              td 10
              td 
                p.mb-0 24
                p.mb-0 9,7
              td 
                p.mb-0 6,2
              td
                p.mb-0 38,4
            tr
              td 5
              td
                p.mb-0 25
                p.mb-0 3,1
              td 
                p.mb-0 9,6
              td
                p.mb-0 92,2
            tr
              td 8
              td 
                p.mb-0 25
                p.mb-0 5,5
              td 
                p.mb-0 12,0
              td
                p.mb-0 144,0
            tr
              td 6
              td 
                p.mb-0 26
                p.mb-0 1,7
              td
                p.mb-0 18,2
              td
                p.mb-0 331,2
      .col-lg-2.col-md-4.col-sm-6.col-8(data-aos="fade-down")
        .div.table.table-responsive
          table.borde-tabla
            tr.bg-green10
              td
                p.mb-0 Media 243,5
            tr
              td
                p.mb-0 Desviación media 9,7
            tr.bg-green10
              td
                p.mb-0 Suma de los cuadrados de las desviaciones 1273,2


    .row.fondo-tema12-4-3.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center
          p Las cifras significativas de la desviación estándar dependen directamente de la incertidumbre de la media. La desviación estándar se reporta con el mismo número de decimales de la media.
        .row.align-items-center
          .col-md-4
            figure
              img.mx-auto(src='@/assets/curso/temas/tema12/img12-4.png' alt='')
          .col-md-8
            p En el caso de la determinación del contenido de cloro - Cl en las muestras de agua, la media se debe reportar con cuatro cifras significativas, ya que todos los datos tienen cuatro cifras significativas (un solo decimal). La desviación estándar (absoluta) debe reportarse con igual número de decimales que la media: un solo decimal.
            .bg-gris.p-4   
              p.mb-0 El resultado del análisis de las muestras de agua se reportará:
              p.mb-4 243,5 ± 11,9 mg/L de Cl
              p.mb-0 Otra medida de dispersión es la varianza, la cual se calcula elevando al cuadrado la desviación estándar (S2).
              p En este caso la varianza es = (11,9) 2 = 141,6


    h4.t-green.mb-4 Error en la medición
    p.mb-4 Para calcular el error es necesario conocer el valor real o valor verdadero. En ejercicio se reporta por laboratorio externo de control un valor 250,0 mg de CL.

    .row.justify-content-center.mb-5
      .col-md-6.col-lg-5.mb-5.mb-lg-0(data-aos="fade-right")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema12/ico.svg' alt='EA')
          .tarjeta.bg-green11
            .p-4
              h4.text-center.mb-4 Error absoluto (E)
              p.text-center.mb-5 Es la diferencia entre la media y el valor considerado como verdadero o valor real. El error se reporta con signo positivo (error por exceso) o con signo negativo (error por defecto).
              figure
                img.mx-auto.px-3(src='@/assets/curso/temas/tema12/error-medicion-form1.svg' alt='')
      .col-md-6.col-lg-5.mb-5.mb-lg-0(data-aos="fade-left")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema12/ico2.svg' alt='ER')
          .tarjeta.bg-green11
            .p-4
              h4.text-center.mb-4 Error relativo (Er):
              p.text-center Se relaciona con el valor verdadero y se reporta como porcentaje.
              p.text-center.mb-5 El signo negativo indica un error por defecto, el valor reportado es menor que el valor considerado como verdadero.
              figure.mb-4
                img.mx-auto.px-3(src='@/assets/curso/temas/tema12/error-medicion-form2.svg' alt='')


    .row.fondo-tema12-4-4.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center(data-aos="fade-down")
          h4.t-green.mb-4 Intervalos de confianza
          p.mb-4 También conocidos como límites de confianza, es el intervalo de valores alrededor de la media, dentro del cual es probable que se encuentre el valor verdadero. La expresión general para los límites de confianza (LC) es la siguiente:
          .col-md-3.mb-4
            figure
              img.mx-auto.px-3(src='@/assets/curso/temas/tema12/form3.svg' alt='')
          p.text-center.mb-5 Donde s es la desviación estándar y z se obtiene de la siguiente tabla:
          .col-md-4
            .div.table
              table.text-center
                caption.bg-gris3.py-1  
                  p.mb-0 Skoog (2001) Valores de z para varios niveles de confianza
                tr.bg-green8
                  td
                    h4.mb-0 Nivel de confianza (%)
                  td
                    h4.mb-0 Valor de Z
                tr.bg-gris3 
                  td 50
                  td 0,67
                tr.bg-white 
                  td 68
                  td 1,00
                tr.bg-gris3 
                  td 80
                  td 1,29
                tr.bg-white 
                  td 90 
                  td 1,64
                tr.bg-gris3 
                  td 95 
                  td 1,96
                tr.bg-white 
                  td 95,4
                  td 2,00
                tr.bg-gris3 
                  td 99
                  td 2,58
                tr.bg-white 
                  td 99,7 
                  td 3,00
                tr.bg-gris3 
                  td 99,9 
                  td 3,29

    .row.justify-content-center.align-items-center
      .col-md-7.mb-4(data-aos="fade-right")
        h4.t-green.mb-4 Análisis intervalos de confianza
        p.mb-4 Entonces el intervalo de confianza utilizando un nivel de confianza del 90% para el análisis es:
        p.mb-4 #[b 243,5 ± 11,9 mg Cl/L], con la media #[b (243,5 mg)] y la desviación estándar absoluta #[b (11,9 mg)].
        p.mb-4 De la tabla de valores de z para varios niveles de confianza se obtiene el valor de #[b z = 1,64 para un 90% de confianza y se calcula LC (límites de confianza)].
        .row.mb-5
          .col-md-8
            figure
              img.mx-auto(src='@/assets/curso/temas/tema12/form4.svg' alt='')
        p.mb-4 Por tanto, el intervalo de confianza es: #[b (224,0 ─ 263,0) mg de CL/L]
        p El valor considerado como verdadero es #[b 250,0 mg Cl/L] (reportado por el laboratorio control), se encuentra dentro el intervalo de confianza para el nivel de confianza del 90%      
      .col-md-5(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema12/img12-4-1.png' alt='Imagen decorativa')

    .row.fondo-tema10-1-1.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center(data-aos="fade-down")
          h4.t-green.mb-4 Curva calibración
          .col-md-8
            p Se preparan patrones del analito que cubran un intervalo adecuado de concentraciones, y se mide la señal analítica  proporcionada por los mismos. La medida de la concentración mediante un método instrumental se basa en la existencia de una relación proporcional entre dicha concentración y la señal analítica o respuesta que genera un instrumento.
            p.mb-4 Generalmente esta relación es lineal, de modo que puede expresarse como:
            .row.justify-content-center.mb-4
              .col-md-3
                figure
                  img.mx-auto(src='@/assets/curso/temas/tema12/form5.svg' alt='')
            p Donde CA es la concentración del analito, y la señal medida, a la ordenada en el origen y b la pendiente de la recta.
          .col-md-4
            figure
              img.mx-auto(src='@/assets/curso/temas/tema12/img12-4-2.png' alt='')

    h4.t-green.mb-4(data-aos="fade") Ecuación recta
    p.mb-5(data-aos="fade") La ecuación de la recta se obtiene mediante calibración con disoluciones de concentración perfectamente conocida (disoluciones patrón) a partir de la medida de la señal analítica proporcionada por éstas. Los pares de valores concentración-señal se ajustan a una recta, a partir de la cual pueden obtenerse la concentración del analito en muestras desconocidas.

    .row.justify-content-center.mb-5(data-aos="fade-down") 
      .col-md-10
        .titulo-sexto.color-acento-contenido
          p.mb-0 Disoluciones del analito de concentración conocida y creciente
        .row.bg-blue2.p-3  
          .col-md-6
            figure
              img.mx-auto.mb-3(src='@/assets/curso/temas/tema12/img12-4-3.svg' alt='Disoluciones del analito de concentración conocida y creciente')
              figcaption.bg-gris3    
                p.mb-0 Nota. Autores (2020) Disoluciones del analito de concentración conocida y creciente
          .col-md-6
            ul.lista-ul--color.color-primario.ps-3
              li 
                i.fas.fa-check
                | Paso 1: preparación de los patrones.
              li 
                i.fas.fa-check
                | Paso 2: obtención de la relación señal - concentración.
              li 
                i.fas.fa-check
                | Paso 3: uso de la curva de calibrado.    

    .row.fondo-tema12-4-5.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center(data-aos="fade-down")
          h4.t-green.mb-4(data-aos="fade") Señal-concentración y recta
          p.mb-5(data-aos="fade") Se traza un gráfico con las señales frente a la concentración de analito y se calcula la recta que “mejor” se ajusta a los datos mediante un ajuste por mínimos cuadrados. De esta forma se obtiene la pendiente (b) y la ordenada (a) en el origen que definen la recta.s
          .row.justify-content-center(data-aos="fade-down") 
            .col-md-8
              .titulo-sexto.color-acento-contenido
                p.mb-0 Señal-concentración y recta ajustada por mínimos cuadrados
              .row.bg-gris.justify-content-center.p-3  
                .col-md-10
                  figure
                    img.mx-auto.mb-3(src='@/assets/curso/temas/tema12/img12-4-4.svg' alt='Disoluciones del analito de concentración conocida y creciente')
                    figcaption.bg-gris3    
                      p.mb-0 Nota. Autores (2020) señal-concentración y recta ajustada por mínimos cuadrados

    .row.justify-content-center.align-items-center.mb-5
      .col-md-7.mb-4(data-aos="fade-right")
        h4.t-green.mb-4 Cálculo excel
        p En la actualidad las calculadoras científicas realizan el ajuste por mínimos cuadrados y, dicho ajuste, también puede realizarse en el ordenador mediante la hoja de cálculo EXCEL.
        p.mb-4 A continuación, se brinda una plantilla para el ajuste por mínimos cuadrados mediante la hoja de cálculo EXCEL y dos tutoriales que le ayudarán a utilizar dicha plantilla y la herramienta de gráficos de dicho programa.
        .row 
          .col-md-5
            a.anexo.mb-4.mb-lg-3(href="https://drive.google.com/file/d/1gWslpfJG7dhGpToHu2ZdkZefn1oPCcJl/view?usp=sharing" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p #[b Enlace web.] Pantalla EXCEL para el ajuste por mínimos cuadrados. 
          .col-md-7
            a.anexo.mb-4.mb-lg-3(href="http://mmedia.uv.es/buildhtml?lang=es_ES&user=martiny&name=tutorial_excel_plantilla.swf&path=/&id=6534" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p #[b Enlace web.] Tutorial 1 que explica cómo utilizar la plantilla de EXCEL
        a.anexo.mb-4.mb-lg-3(href="http://mmedia.uv.es/buildhtml?lang=es_ES&user=martiny&name=tutorial_excel_graficos.swf&path=/&id=6530" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p #[b Enlace web.] Tutorial 2 que explica cómo utilizar la herramienta gráficos de EXCEL, para obtener una recta ajustada por mínimos cuadrados.
      .col-md-5(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema12/img12-4-5.png' alt='Imagen decorativa')


    h4.t-green.mb-4(data-aos="fade") Señal analítica
    p.mb-5(data-aos="fade") Se mide la señal analítica para las muestras desconocidas y se interpola en la recta de calibrado para obtener valores de concentración de analito.
    .row.justify-content-center.mb-4(data-aos="fade-down") 
      .col-md-8
        .titulo-sexto.color-acento-contenido
          p.mb-0 Figura 2. Señal-concentración y recta ajustada por mínimos cuadrados
        .row.bg-green3.justify-content-center.p-3  
          .col-md-11
            figure
              img.mx-auto.mb-3(src='@/assets/curso/temas/tema12/img12-4-6.svg' alt='Señal-concentración y recta ajustada por mínimos cuadrados')
              figcaption.bg-gris3    
                p.mb-0 Nota. Autores (2020) Obtención de la concentración de analito en las muestras a partir de la gráfica y la recta

    p(data-aos="fade") Finalmente, para obtener la concentración de analito en la muestra hay que tener en cuenta en los cálculos las posibles diluciones a las que se ha sometido la muestra para obtener las disoluciones M1, M2 y M3 de medida.



</template>

<script>
export default {
  name: 'Tema12',
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
