<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Protocolos para análisis de agua

    .row.justify-content-center.align-items-center
      .col-md-5.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img.png' alt='Imagen decorativa')
      .col-md-7.mb-4(data-aos="fade-left")
        p El objetivo primordial de cualquier análisis relacionado con la calidad del agua es brindar la información necesaria para el manejo adecuado de los recursos hídricos para obtener datos de forma precisa y exacta de las características físicas, químicas y microbiológicas de la muestra de agua   evaluada; los datos deben provenir de muestras representativas y análisis de acuerdo con protocolos que sigan estrictas normas técnicas y legales de control de calidad.
        .bg-green4.p-4.mb-4
          p.mb-0 Recuerde que la calidad del agua depende tanto de factores naturales, como de la acción humana, y se determina comparando las características físicas, químicas y microbiológicas de una muestra de agua; con unas directrices legales de calidad del agua y estándares técnicos.
        p La principal norma que rige el tema de calidad del agua en Colombia es el Decreto 1575 y resolución 2115 del año 2007, por medio del cual se establece el sistema para la protección y control de la calidad del agua para consumo humano.

    Separador


    #t_5_1
    .titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 5.1 Variables físicas, químicas y microbiológicas del agua
    
    p.mb-5(data-aos="fade") Los parámetros físicos, químicos y microbiológicos del agua que se va analizar dependen de la carga de contaminantes y uso que se va dar a la misma; es así que se pueden agrupar protocolos de análisis.

    h3.subt.text-white.mb-4(data-aos="fade") Parámetros físicos

    p.mb-5(data-aos="fade") A continuación, le mostramos la forma en que los protocolos de análisis se encuentran agrupados o clasificados. ¡Adelante!

    .row.fondo-tema4-4.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center
          .col-md-8(data-aos="fade-right")
            h4.t-green.mb-4 Sólidos suspendidos totales en agua
            p.mb-4 El agua puede contener tanto partículas en suspensión como compuestos solubilizados, definiéndose la suma de ambos como Sólidos Totales (ST) La determinación de ST se realiza, conforme a la norma UNE 77030:1982, evaporando un volumen conocido de muestra y secando el residuo en estufa a 105 ºC, hasta pesada constante, indicándose el resultado en mg/L.
            p.mb-4 Esta medida nos permite conocer el contenido total de sustancias no volátiles presentes.
          .col-md-4(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1.png' alt='Imagen decorativa')

    .row.align-items-center.mb-5
      .col-md-8(data-aos="fade-right")
        h4.t-green.mb-4 Conductividad eléctrica
        p.mb-4 La conductividad es una medida de la propiedad que poseen las soluciones acuosas para conducir la corriente eléctrica. Esta propiedad depende de la presencia de iones, su concentración, movilidad, valencia y de la temperatura de la medición. Las soluciones de la mayor parte de los compuestos inorgánicos son buenas conductoras. Las moléculas orgánicas al no disociarse en el agua, conducen la corriente a muy baja escala. Para la determinación de la conductividad la medida física hecha en el laboratorio es la resistencia, en ohmios o megaohmios. 
        p.mb-4 La conductividad es el inverso de la resistencia específica, y se expresa en micromho por centímetro (µmho/cm) equivalentes a microsiemens por centímetro (µS/cm) o milisiemens por centímetro (mS/cm) en el Sistema Internacional de Unidades.
      .col-md-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-2.png' alt='Imagen decorativa')


    .row.fondo-tema5-1.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center
          h4.t-green.mb-4 El intervalo de aplicación del método
          .col-md-8.mb-4(data-aos="fade-right")
            .bloque-texto-c.bg-green2.box-shadow.p-3.px-4
              i.fas.fa-quote-right.mb-2
              p.mb-3 El intervalo de aplicación del método es de 10 a 10.000 (o hasta 50.000) µmho/cm, las conductividades fuera de estos valores son difíciles de medir con los componentes electrónicos y las celdas convencionales. El método es aplicable a aguas potables, superficiales, salinas, aguas residuales domésticas e industriales y lluvia ácida. El rango de trabajo en el IDEAM oscila entre 0.0 y 1999 µS/cm. (p.2) 
              span.text-bold.mb-0 - Según IDEAM (2016)            
          .col-md-4.mb-4(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-3.png' alt='Imagen decorativa')
          .col-md-12.text-white
            .bg-color-primario.p-4
              h5 Sabía qué…
              p.mb-0 En su estado puro el agua está formada por dos átomos de hidrógeno y uno de oxígeno, un enlace covalente que no permite el flujo de electrones. Sin embargo, el agua común que utilizamos para bañarnos, lavar o tomar agua, contiene sales minerales que están ionizadas, es decir que están cargadas eléctricamente, además de diferentes iones  como calcio, magnesio, nitratos, cloruros y nitratos, que permiten el paso de la corriente.

    h4.t-green.mb-4(data-aos="fade") Potencial de hidrógeno pH
    .row.justify-content-center.mb-5
      .col-md-8
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-4.svg' alt='Imagen decorativa')

    .row.fondo-tema4-4.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center
          h4.t-green.mb-4 El pH
          .col-md-9.mb-4(data-aos="fade-right")
            p El término pH es una forma de expresar la concentración de ion hidrógeno o , más exactamente, la actividad del ión hidrógeno. En general se usa para expresar la intensidad de la condición ácida o alcalina de una solución, sin que esto quiera decir que mida la acidez total o la alcalinidad total.  
            p Hasta este punto, le hemos mostrado 5 de los tipos de agrupación de los protocolos de análisis. Es momento de continuar con otros, adicionales, de suma importancia.             
          .col-md-3(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-5.png' alt='Imagen decorativa')


    h4.t-green.mb-4 Suministro de aguas
    p.mb-4 El suministro de aguas es un factor que debe considerarse con respecto a la coagulación química, la desinfección, el ablandamiento y el control de corrosión. En las plantas de tratamiento de aguas residuales que emplean procesos biológicos, el pH debe controlarse dentro de un intervalo favorable a los organismos. Tanto por estos factores como por la relaciones que existen entre pH, alcalinidad y acidez es importante entender los aspectos teóricos y prácticos del pH. 
    .row.align-items-center.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-8
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-6.svg' alt='Suministro de aguas')

    .row.align-items-center.mb-5
      .col-md-4.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-7.png' alt='Imagen decorativa')
      .col-md-8(data-aos="fade-left")
        .bloque-texto-c.bg-blue2.p-3.px-4
          i.fas.fa-quote-right.mb-2
          p El principio básico de la medida electrométrica del pH se fundamenta en el registro potenciométrico de la actividad de los iones hidrógeno por el uso de un electrodo de vidrio y un electrodo de referencia, o un electrodo combinado. La fuerza electromotriz (fem) producida por el sistema electroquímico varía linealmente con el pH y puede verificarse por la obtención de una gráfica de pH vs. fem para diferentes soluciones de pH conocido.
          p.mb-3 El pH de la muestra se determina por interpolación. Casi todos los aparatos usados hoy en día utilizan el electrodo de vidrio, en combinación con un electrodo de calomel, empleado como electrodo de referencia, para medir el pH. El potencial entre los electrodos es proporcional a la concentración de iones hidrógeno en solución. El sistema de electrodos se calibra siempre con soluciones de pH conocido. De acuerdo con el fabricante y el tipo de medidor de pH, cada aparato posee sus propias características e instrucciones de uso. (P.1).
          span.text-bold.mb-0 - Según IDEAM (2007)

    .row.fondo-tema10-1-1.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center          
          .col-md-8.mb-4(data-aos="fade-right")
            h4.t-green.mb-4 Turbiedad
            p La turbiedad en el agua es causada por materia suspendida y coloidal tal como arcilla, sedimento, materia orgánica e inorgánica dividida finamente, plancton y otros microorganismos microscópicos.
            p La turbiedad es una expresión de la propiedad óptica que causa la luz al ser dispersada y absorbida en vez de transmitida sin cambios en la dirección del nivel de flujo a través de la muestra: en otras palabras, es la propiedad óptica de una suspensión que hace que la luz sea emitida y no transmitida a través de la suspensión. A mayor intensidad de dispersión de la luz, la turbidez será mayor.
          .col-md-4(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-8.png' alt='Imagen decorativa')

    .row.align-items-center.mb-5
      .col-md-8.mb-4(data-aos="fade-right")
        .bloque-texto-c.bg-blue2.p-3.px-4
          i.fas.fa-quote-right.mb-2
          p La correlación de la turbiedad con el peso o concentración del número de partículas de material suspendido es difícil debido a que el tamaño, forma e índice de refracción de las partículas afecta las propiedades de dispersión de la luz de la suspensión. La determinación de turbiedad es de gran importancia en aguas para consumo humano y en un gran número de industrias procesadoras de alimentos y bebidas. 
          p.mb-3 Los valores de turbiedad sirven para establecer el grado de tratamiento requerido por una fuente de agua cruda, su filtrabilidad y consecuentemente, la tasa de filtración más adecuada, la efectividad de procesos de coagulación, sedimentación y filtración, así como para determinar la potabilidad del agua. (P.1)
          span.text-bold.mb-0 - Según IDEAM (2007)
      .col-md-4(data-aos="fade-left")        
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-9.png' alt='Imagen decorativa')  

    .row.fondo-tema10-1-1.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center          
          .col-md-9.mb-4(data-aos="fade-right")
            h4.t-green.mb-4 Temperatura
            p La temperatura es un parámetro físico que afecta mediciones de otros como pH, alcalinidad o conductividad. Las temperaturas elevadas resultantes de descargas de agua caliente, pueden tener un impacto ecológico significativo por lo que la medición de la temperatura del cuerpo receptor, resulta útil para evaluar los efectos sobre éste. 
            p El método se aplica a todo tipo de aguas: potables, residuales y superficiales, incluyendo las marinas. 
          .col-md-3(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-10.png' alt='Imagen decorativa')

    .row.align-items-center.mb-5         
      .col-md-9.mb-4(data-aos="fade-right")
        h4.t-green.mb-4 Color, olor y sabor
        p Son las propiedades organolépticas que se evalúan a través de los sentidos. No se evalúan  de forma  experimental a nivel de contaminación, pero  su presencia es una señal de que la depuración de un efluente no está siendo correcta. Son de gran relevancia en aguas potabilizadas, por el rechazo que puede darse en el consumidor al detectar colores, olores o sabores que no asocie con agua apta para el consumo humano. 
      .col-md-3(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-11.png' alt='Imagen decorativa')

    .row.fondo-tema5-2.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.mb-4          
          .col-md-7.mb-4(data-aos="fade-right")
            h3.subt.text-white.mb-4 Parámetros químicos
            p La calidad química del agua está determinada por las sustancias químicas presentes en la muestra   analizada en un tiempo determinado y un punto específico.
            h4.t-green.mb-4 Oxígeno disuelto
            ul.lista-ul--color.color-primario.ps-3
              li 
                i.fas.fa-check
                | El oxígeno disuelto (OD) es necesario para la respiración de los microorganismos aerobios así como para otras formas de vida aerobia. No obstante, el oxígeno es ligeramente soluble en el agua; la cantidad real de oxígeno que puede estar presente en la solución está determinada por:
              ol.lista-ol.ps-4
                li 
                  span.text-bold a. 
                  | La solubilidad del gas.
                li 
                  span.text-bold b. 
                  | La presión parcial del gas en la atmósfera.
                li 
                  span.text-bold c. 
                  | La temperatura.
                li 
                  span.text-bold d. 
                  | La pureza del agua (salinidad, sólidos suspendidos).    
          .col-md-5(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-12.png' alt='Imagen decorativa')
          
        p.text-center.mb-4 Según IDEAM (2004):

        .row.justify-content-center(data-aos="fade-down") 
          .col-md-10
            SlyderF.align-items-center(columnas="col-lg-6 col-xl-6")
              .tarjeta.h-tem5-tarj.color-acento-contenido.fondo-tema3-tarj.p-4.align-items-center.d-flex
                p.text-center La interrelación de estas variables debe ser consultada en textos apropiados (ver bibliografía) para conocer los efectos de la temperatura y la salinidad sobre la concentración de OD.
              .tarjeta.h-tem5-tarj.color-acento-contenido.fondo-tema3-tarj.p-4.align-items-center.d-flex
                p.text-center Las concentraciones de OD en aguas naturales dependen de las características fisicoquímicas y la actividad bioquímica de los organismos en los cuerpos de agua. El análisis del OD es clave en el control de la contaminación en las aguas naturales y en los procesos de tratamiento de las aguas residuales industriales o domésticas.
              .tarjeta.h-tem5-tarj.color-acento-contenido.fondo-tema3-tarj.p-4.align-items-center.d-flex
                p.text-center La muestra obtenida se trata con sulfato manganeso (MnSO4), hidróxido de sodio (NaOH) y yoduro de potasio (KI) estos dos últimos reactivos combinados en una solución única, y finalmente se acidifica con ácido sulfúrico (H2SO4).
              .tarjeta.h-tem5-tarj.color-acento-contenido.fondo-tema3-tarj.p-4.align-items-center.d-flex
                p.text-center Inicialmente se obtiene un precipitado de hidróxido manganoso, Mn(OH)2, el cual se combina con el OD presente en la muestra para formar un precipitado carmelito de hidróxido mangánico, MnO(OH)2; con la acidificación, el hidróxido mangánico forma el sulfato mangánico que actúa como agente oxidante, para liberar yodo del yoduro de potasio. El yodo libre es el equivalente estequiométrico del OD en la muestra y se valora con una solución estándar de tiosulfato de sodio 0.025N.
              .tarjeta.h-tem5-tarj.color-acento-contenido.fondo-tema3-tarj.p-4.align-items-center.d-flex
                p.text-center Para minimizar el efecto de los materiales interferentes existen algunas modificaciones del método yodométrico. La modificación de la azida elimina la interferencia causada por los nitritos (esta es la más común en efluentes tratados biológicamente y en muestras incubadas para la prueba de la DBO) se emplea en el análisis del OD en la mayoría de aguas residuales, efluentes y aguas superficiales, especialmente si las muestras tienen concentraciones mayores de 50 µg NO2 – - N/L y no más de 1 mg de hierro ferroso/L. Los compuestos oxidantes y reductores interfieren en la determinación.  (p.1).


    .row.align-items-center.mb-5         
      .col-md-8.mb-4(data-aos="fade-right")
        h4.t-green.mb-4 Demanda química de oxígeno DQO
        p La Demanda Química de Oxígeno (DQO) determina la cantidad de oxígeno requerido para oxidar la materia orgánica en una muestra de agua, bajo condiciones específicas de agente oxidante, temperatura y tiempo. 
        p Las sustancias orgánicas e inorgánicas oxidables presentes en la muestra, se oxidan mediante reflujo cerrado en solución fuertemente ácida (H2SO4) con un exceso de dicromato de potasio (K2Cr2O7) en presencia de sulfato de plata (Ag2SO4) que actúa como agente catalizador, y de sulfato mercúrico (HgSO4) adicionado para eliminar la interferencia de los cloruros. Después de la digestión, el K2Cr2O7 remanente se titula con sulfato ferroso amoniacal para determinar la cantidad de K2Cr2O7 consumido.
        .cajon.color-primario.row.align-items-center.p-4.mb-4
          .col-md-2
            img.mx-auto(src='@/assets/curso/temas/tema5/ico.svg' alt='Imagen decorativa')
          .col-md-10
            p.mb-0 La materia orgánica se calcula en términos de oxígeno equivalente. Para muestras de un origen específico, la DQO se puede relacionar empíricamente con la DBO, el carbono orgánico o la materia orgánica. El método es aplicable a aguas superficiales y residuales, usando el dicromato de 0,025 N en un rango de 2.0 mg O2/L a 100 mg O2/L, usando el dicromato de 0,10 N en un rango de 10 mg O2/L a 450 mg O2/L y con el dicromato de 0,25 N tiene un intervalo de lectura de 10 mg O2/L a 1000 mg O2/L.
      .col-md-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-13.png' alt='Imagen decorativa')


    .row.align-items-center.mb-5
      .col-md-4(data-aos="fade-right")        
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-14.svg' alt='Imagen decorativa')  
      .col-md-8.mb-4(data-aos="fade-left")
        p También, la oxidación microbiana o mineralización de la materia orgánica es una de las principales reacciones que ocurren en los cuerpos naturales de agua y constituye una de las demandas de oxígeno, ejercida por los microorganismos heterotróficos, que hay que cuantificar. 
        p Uno de los ensayos más importantes para determinar la concentración de la materia orgánica de aguas residuales es el ensayo de DBO a cinco días. Esencialmente, la DBO es una medida de la cantidad de oxígeno utilizado por los microorganismos en la estabilización de la materia orgánica biodegradable, en condiciones aeróbicas, en un periodo de cinco días a 20 °C.
        .bloque-texto-c.bg-blue2.p-3.px-4
          i.fas.fa-quote-right.mb-2
          p En aguas residuales domésticas, el valor de la DBO a cinco días representa en promedio un 65 a 70% del total de la materia orgánica oxidable. La DBO, como todo ensayo biológico, requiere cuidado especial en su realización, así como conocimiento de las características esenciales que deben cumplirse, con el fin de obtener valores representativos confiables.  
          p El ensayo supone la medida de la cantidad de oxígeno consumido por organismos vivos en la utilización de la materia orgánica presente en un residuo; por tanto, es necesario garantizar que durante todo el periodo de ensayo exista suficiente oxígeno disuelto para ser utilizado por los organismos. Además, debe garantizarse que se suministran las condiciones ambientales adecuadas para el desarrollo y trabajo de los microorganismos, así que hay que proporcionar los nutrientes necesarios para el desarrollo bacteriano, tales como N y P y eliminar cualquier sustancia tóxica de la muestra.  
          p Es también necesario que exista una población de organismos suficiente en cantidad y en variedad de especies, llamada “Cepa” o “semilla”, durante la realización del ensayo, para la degradación de la materia orgánica. El método se aplica en este laboratorio para la matriz aguas naturales superficiales y residuales industriales. Es empleado para el intervalo de 2 a 5000 mg/L. Es un método electrométrico, en el que se determina el oxígeno disuelto consumido, en sus procesos metabólicos, por los microorganismos, en la degradación de la materia orgánica, incubando la muestra en la oscuridad a 20 ± 30C, por cinco días. (P.2) 
          span.text-bold.mb-0 - Según IDEAM (2007)


    .row.fondo-tema10-1-1.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center          
          .col-md-7.mb-4(data-aos="fade-right")
            h4.t-green.mb-4 Alcalinidad
            p La alcalinidad del agua es su capacidad de neutralizar ácidos, y es la suma de todas las bases titulables; el valor medido puede variar significativamente con el pH de punto final empleado. La alcalinidad es una medida de una propiedad agregada del agua y se puede interpretar en términos de sustancias específicas sólo cuando se conoce la composición química de la muestra. 
            p Debido a que la alcalinidad de muchas aguas superficiales es primariamente una función del contenido de carbonato, bicarbonato e hidróxido, se toma como un indicador de la concentración de estos constituyentes. Los valores medidos también pueden incluir contribuciones de boratos, fosfatos, silicatos, u otras bases que estén presentes.  
            .cajon.color-primario.color2.row.align-items-center.p-4.mb-4
              p La alcalinidad superior a las concentraciones de metales alcalinotérreos es significante para determinar la aptitud de un agua para irrigación. Las mediciones de alcalinidad se emplean en la interpretación y control de los procesos de tratamiento de aguas. Las aguas residuales domésticas tienen una alcalinidad menor, o ligeramente mayor, que la del agua de suministro.
          .col-md-5(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-15.png' alt='Imagen decorativa')

        p Los iones hidroxilo presentes en una muestra como resultado de disociación o hidrólisis de solutos reaccionan con adiciones de ácido estándar. En consecuencia la alcalinidad depende del pH de punto final empleado. La alcalinidad de una muestra se determina mediante el volumen de un ácido estándar requerido para titular una porción a un pH seleccionado.

        .row.align-items-center          
          .col-md-5.mb-4(data-aos="fade-right")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-16.png' alt='Imagen decorativa')
          .col-md-7(data-aos="fade-left")
            p La titulación se efectúa a temperatura ambiente con un pH metro o un titulador automático calibrados, o mediante indicadores coloreados. En este último caso, se debe preparar y titular un blanco del indicador. La construcción de una curva de titulación permite la identificación de puntos de inflexión y capacidad tampón, si existe, y permite determinar la alcalinidad con respecto a cualquier pH de interés.
            p En la titulación de especies básicas simples, como en la estandarización de reactivos, el punto final más exacto se obtiene del punto de inflexión de una curva de titulación. Debido a que la identificación exacta de puntos de inflexión puede ser difícil o imposible en mezclas tamponadas o complejas, la titulación en tales casos se lleva a cabo hasta un punto final de pH arbitrario basado en consideraciones prácticas.

        .row.align-items-center
          .col-md-8.mb-4(data-aos="fade-right")
            .bloque-texto-c.bg-white.box-shadow.p-3.px-4
              i.fas.fa-quote-right.mb-2
              p Para titulaciones de control rutinarias o estimaciones preliminares rápidas de la alcalinidad, se puede usar el cambio de color de un indicador como punto final. Para muestras de baja alcalinidad (menor de 20 mg CaCO3/L) se aplica una técnica de extrapolación basada en la proporcionalidad aproximada de la concentración de iones hidrógeno por el exceso de titulante más allá del punto de equivalencia. Se mide cuidadosamente la cantidad de ácido estándar requerido para reducir el pH exactamente en 0,30 unidades.  
              p Debido a que este cambio de pH corresponde al doble de la concentración de iones hidrógeno, se puede hacer una simple extrapolación del punto de equivalencia. La alcalinidad está expresada como alcalinidad a la fenolftaleína (P), o como alcalinidad total (T) La primera corresponde al contenido total de hidróxido y carbonato presentes en la muestra, y la segunda, además de los anteriores, incluye el contenido de bicarbonato. 
              p.mb-3 Sabía que: consumir agua alcalina puede ayudar a aliviar el reflujo gastroesofágico, donde el líquido permite contrarrestar la acidez al impedir la activación de la pepsina y ejercer un efecto antiácido, reduciendo las molestas agruras. Sin embargo, no es aconsejable beber grandes cantidades de agua alcalina  pues al  alcalinizar el estómago puede traer como consecuencia dificultad al digerir la comida. Imagen. (pp.2-3) 
              span.text-bold.mb-0 - Según IDEAM (2007)            
          .col-md-4.mb-4(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-17.png' alt='Imagen decorativa')      
    
    
    h4.t-green.mb-4(data-aos="fade") Dureza
    p(data-aos="fade") En la práctica se considera que la dureza es causada por iones metálicos divalentes, capaces de reaccionar con el jabón para formar precipitados y con ciertos aniones presentes en el agua para formar incrustaciones.

    .row.justify-content-center.mb-4
      .col-lg-4.col-md-6.col-sm-8.col-10
        .titulo-sexto.color-acento-contenido(data-aos="fade-down")
          p.mb-0 #[b Tabla 2.] Cationes y aniones
        table(data-aos="fade-down")
          caption
            p.mb-0 Nota. Lievano E, (2020)
          tr.bg-green8
            td
              h4.text-center.mb-0 Cationes
            td
              h4.text-center.mb-0 Aniones
          tr
            td
              p.mb-0.text-center Ca++
            td
              p.mb-0.text-center HCO3 -
          tr
            td
              p.mb-0.text-center Mg++
            td
              p.mb-0.text-center SO4 =
          tr
            td
              p.mb-0.text-center Sr++
            td
              p.mb-0.text-center Cl -
          tr
            td
              p.mb-0.text-center Mn++
            td
              p.mb-0.text-center NO3 -
          tr
            td
              p.mb-0 
            td
              p.mb-0.text-center SIO3=

    p(data-aos="fade") Los principales cationes que causan dureza en el agua y los principales aniones asociados con ellos son los siguientes:

    .row.fondo-tema5-3.align-items-center.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center
          .col-md-10.mb-5 
            .row.tarjeta.bg-blue2.align-items-center.p-4
              .col-md-10
                p.mb-0 En menor grado, Al +++ y Fe +++ son considerados como iones causantes de dureza. En general, la dureza es igual a la concentración de cationes polivalentes del agua. Desde el punto de vista sanitario, las aguas duras son tan satisfactorias para el consumo humano como las aguas blandas; sin embargo, un agua dura requiere demasiado jabón para la formación de espuma y crea problemas de lavado; además deposita lodo e incrustaciones sobre las superficies con las cuales entra en contacto, así como en los recipientes, calderas o calentadores en los cuales se calienta.
              .col-md-2
                img.mx-2(src="@/assets/curso/temas/tema5/ico2.svg")
          h5.text-center.mb-5 Según IDEAM (2007):
          .col-md-8
            .row.align-items-center.justify-content-center
              .col-md-4.mx-0.px-0
                img(src="@/assets/curso/temas/tema5/img5-1-18.svg")
              .col-md-8.mx-0.px-0
                SlyderE.bg-white.box-shadow.p-4(indicadores="derecha")
                  .row
                    p El límite para dureza en agua potable es de 160 mg CaCO3/L. Para aguas de caldera de presión intermedia el límite es 1 mg/L y de presión alta, 0.07 mg CaCO3/L, en aguas de enfriamiento 650 mg CaCO3/L. Este método es aplicable a aguas potables, superficiales, contaminadas y aguas residuales. El ácido etilendiaminotetraacético y sus sales de sodio (EDTA) forman un complejo de quelato soluble al añadirlo a las soluciones de algunos cationes metálicos. Cuando se añade EDTA al agua que contiene calcio y magnesio, aquél se combina primero con el calcio. 
                  .row
                    p De acuerdo con los criterios actuales, la dureza total se define como la suma de las concentraciones de calcio y magnesio, ambos expresados como carbonato de calcio, en miligramos por litro. La nitidez del punto final en el método volumétrico de EDTA, aumenta con los incrementos de pH.
                  .row
                    p Sin embargo, el pH no puede aumentar indefinidamente debido al peligro de precipitación de carbonato de calcio (CaCO3) o hidróxido magnésico, Mg (OH)2, y por que la titulación cambia de color a pH alto. El valor de pH especificado de 10 constituye una solución satisfactoria. (P.1).


    .row.fondo-tema5-4.align-items-center.mb-4.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.align-items-center.justify-content-center
          h4.t-green.mb-4(data-aos="fade") Grasas y aceites
          p Le presentamos, ahora, elementos importantes sobre el método de extracción Soxhlet para la determinación de grasas y aceites.
          p.mb-4 El método de extracción Soxhlet para la determinación de grasas y aceites es aplicable para determinar lípidos biológicos, hidrocarburos ya sea fracciones pesadas o relativamente polares del petróleo y cuando los niveles de grasas no volátiles pueden alterar el límite de solubilidad del solvente. 

          SlyderF(columnas="col-lg-6 col-xl-4" data-aos="fade-down")
            .row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico1.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p El método es aplicable en aguas residuales o afluentes tratados que contengan estos materiales, aunque la complejidad de la muestra puede producir resultados desviados a causa de la falta de especificidad Los jabones metálicos solubles son hidrolizados por acidificación. Sólo los aceites y las grasas sólidas o viscosas presentes se separan de la muestra líquida por filtración sobre una matriz sólida absorbente.
            .row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico2.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p Después de la extracción en un aparato soxhlet con solvente orgánico, se pesa el residuo que queda de la evaporación del solvente para determinar el contenido en grasa y aceite. En la determinación de grasas y aceites no se mide una cantidad absoluta de una sustancia específica; se determinan grupos de sustancias con características físicas similares con base en su solubilidad en el solvente.
            .row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico3.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p Así, el término “grasas y aceites” comprende cualquier material recuperado como una sustancia soluble en el solvente (n-hexano). Esto incluye otros materiales extraídos por el solvente de la muestra acidificada, tales como compuestos azufrados, algunos colorantes orgánicos y clorofila, no volatilizados durante el ensayo.
            .row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico4.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p Cloruros: El cloruro (Cl - ) es uno de los aniones inorgánicos que se encuentran en mayor concentración en aguas de consumo y aguas de desecho. En agua potable el sabor salino producido por la presencia de cloruros es variable y depende de la composición química del agua. Un alto contenido de cloruros en las aguas puede dañar estructuras y tuberías metálicas, al igual que afecta el crecimiento de la flora.
            .row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico5.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p El método argentométrico para la determinación de cloruros es útil en aguas relativamente claras que contengan de 0,15 a 10 mg Cl - en la alícuota de muestra titulada.
            .row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico6.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p El cloruro puede titularse con una solución de nitrato de plata utilizando cromato de potasio como indicador del punto final, en medio neutro o ligeramente alcalino, el cloruro de plata se precipita cuantitativamente antes de formarse el color rojo del cromato de plata.
            row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico7.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p Interferencias y limitaciones: Los yoduros, bromuros y cianuros reaccionan con cloruros. Los iones sulfuros, tiosulfatos y sulfitos interfieren pero pueden ser eliminados por tratamiento con peróxido de hidrógeno.
            .row
              .tarjeta-avatar.text-center.h-tem5-tarj3
                img(src='@/assets/curso/temas/tema5/slide-f-ico8.svg' alt='Grasas y aceites')
                .tarjeta.bg-green11
                  .p-4
                    p Las concentraciones de ortofosfatos mayores de 25 mg/L interfieren por precipitación de fosfato de plata. Las concentraciones de hierro mayores de 10 mg/L interfieren enmascarando el punto final en la titulación.


    p.mb-5(data-aos="fade") Luego de conocer sobre el método de extracción Soxhlet para la determinación de grasas y aceites, le invitamos a conocer, en la siguiente gráfica, algunos factores de importancia respecto a Sulfatos y Nitritos.
    
    h4.t-green.mb-4(data-aos="fade") Factores de importancia respecto a sulfatos, nitritos y nitratos

    AcordionA.mb-4(data-aos="fade-down" tipo="a" clase-tarjeta="tarjeta bg-gris3")
      .row.justify-content-center(titulo="Sulfatos")
        .col-md-11
          p #[b El sulfato (SO4 2–)] se encuentra ampliamente distribuido en la naturaleza y puede estar presente en aguas naturales en concentraciones que van desde unos pocos miligramos por litro hasta algunos gramos por litro. Algunos drenajes de minería pueden contribuir con grandes cantidades de sulfatos a través de la oxidación de piritas. Como los sulfatos de sodio y de magnesio tienen un efecto purgante, especialmente entre los niños, se recomienda un límite superior en aguas potables de 250 mg/L de sulfatos. 
          p.mb-0 #[b Contenido:] El contenido es también importante, porque las aguas con alto contenido de sulfatos tienden a formar incrustaciones en las calderas y en los intercambiadores de calor. El ion SO4 2– forma una suspensión con cloruro de bario (BaCl2) en presencia de ácido acético para formar cristales de sulfato de bario (BaSO4) de tamaño uniforme. Se mide la dispersión de luz de la suspensión de BaSO4 con un turbidímetro, y la concentración de SO4 2– se determina por comparación de la lectura contra una curva estándar. Reacción: 
          p.mb-0 #[b SO4 = + 2 HCl  → H2SO4 + 2 Cl - ]
          p #[b H2SO4 + BaCl2 → BaSO4 + 2 HCl ]
          p #[b Intervalo:] El intervalo de aplicación de este método va de 3 a 40 mg SO4 2–/L. Para muestras con concentraciones superiores, use una alícuota que contenga menos de 40 mg SO4 2–/L. Este método es aplicable a aguas potables, lluvia, superficiales, y efluentes domésticos e industriales.
      .row.justify-content-center(titulo="Nitritos")
        .col-md-11
          p El nitrógeno de nitritos raras veces aparece en concentraciones mayores de 1 mg/L, aún en fuentes de plantas de tratamiento de aguas residuales. En aguas superficiales y subterráneas su concentración por lo general es menor de 0.1 mg/L. Su presencia indica, por lo regular, procesos activos biológicos en el agua, ya que es fácil y rápidamente convertido en nitrato. Los nitritos en concentraciones elevadas reaccionan dentro del organismo con aminas y amidas secundarias y terciarias formando nitrosominas de alto poder cancerígeno
          p #[b NO2:] El nitrito (NO2 – ) se determina mediante la formación de un colorante azo de color púrpura rojizo por reacción de diazotación-copulación de sulfanílamida con diclorhidrato de N-(1-naftil)-etilendiamina (NED diclorhidrato) a pH entre 2,0 y 2,5. Según el Standard Methods este método es adecuado para determinar nitrito en concentraciones de 10 a 1000 µg NO2 – -N/L. El sistema de color obedece la Ley de Beer en concentraciones hasta de 180 µg NO2 – -N/L a 543 nm si se emplea celda de 1 cm de longitud; se pueden hacer mediciones en el intervalo de 5 a 50 µg NO2 – -N/L con una celda de 5 cm de paso de luz y un filtro de color verde.
          p #[b Concentración:] Se pueden determinar concentraciones más altas por dilución de la muestra. En el laboratorio se analizan con éste método muestras de agua superficial, en un rango de concentraciones entre 0.006 y 0.20 mg N - NO2 – /L Según el Decreto 475 del 10 marzo de 1998 del Ministerio de Salud, en el artículo 8 parte b) se especifica como criterio de calidad química para agua con implicaciones de tipo económico o acción indirecta sobre la salud, un valor máximo admisible de 0,2 mg/L de nitritos.
      .row.justify-content-center(titulo="Nitratos")
        .col-md-11
          p La técnica de monitoreo espectrofotométrico ultravioleta (UV) mide la absorbancia del nitrato (NO3 – ) a 220 nm y es adecuada para la determinación rápida de NO3 – y el monitoreo de aguas con bajo contenido de materia orgánica, como aguas naturales sin contaminar y fuentes de agua potable. Debido a que la materia orgánica disuelta también puede absorber a 220 nm y a que el NO3 – no absorbe a 275 nm, se usa una segunda medición a 275 nm para corregir el valor de NO3 –
          p #[b Corrección Empírica:] La aplicación de esta corrección empírica está relacionada con la naturaleza y concentración de materia orgánica y puede variar de una muestra a otra. Consecuentemente, este método no es recomendado si se requiere una corrección significativa para absorbancia de materia orgánica, aunque puede usarse en el monitoreo de niveles de NO3 – en un cuerpo de agua con un tipo constante de materia orgánica.
          p #[b Absorbancia:] Los factores de corrección para la absorbancia de la materia orgánica se pueden establecer por el método de adiciones en combinación con el análisis del contenido original de NO3 – por otro método. La filtración de muestra tiene la intención de remover la posible interferencia de partículas suspendidas.
          p #[b Acidificación:] La acidificación con HCl 1 N está designada para prevenir la interferencia de concentraciones de hidróxido o carbonato hasta de 1000 mg CaCO3/L. El cloruro no tiene efecto en la determinación. La técnica de monitoreo espectrofotométrico ultravioleta de NO3 – obedece la Ley de Beer entre 0.03 y 5 mg NO3 – -N/L.

    
    p.mb-5(data-aos="fade") Para continuar el apartado Parámetros químicos, Conozca a continuación otros elementos de suma importancia referentes al mismo.
    
    h4.t-green.mb-4(data-aos="fade") Acidez
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="fade-down") 
      .col-md-7.mb-4
        p La acidez del agua puede definirse como su capacidad para neutralizar bases o también como su capacidad para reaccionar con iones hidróxido o su capacidad para ceder protones o como la medida de su contenido total de sustancias ácidas. Las aguas excesivamente ácidas atacan los dientes.
        p De acuerdo al SENA (2019):
        ul.lista-ul--color.color-primario.ps-3
          li 
            i.fas.fa-check
            | La causa más común de acidez en aguas es el CO2 el cual puede estar disuelto en el agua como resultado de las reacciones de los coagulantes químicos usados en el tratamiento o de la oxidación de la materia orgánica, o por disolución de dióxido de carbono atmosférico, pero en residuos industriales es la acidez mineral.
          li 
            i.fas.fa-check
            | El CO2 se combina con el agua para formar un ácido débil, inestable, H2CO3, el cual se descompone muy fácilmente. Por ello todo el dióxido, aun combinado se considera CO2  libre.
          li 
            i.fas.fa-check
            p La acidez se titula mediante la adición de iones OH- provenientes de una disolución de NaOH 0,02N. Dando paso a la siguiente reacción. #[br]#[br]
              strong.bg-green7.mb-0.p-2 2NaOH + CO2→ Na2CO3 + H2O #[br]
              strong.bg-green7.mb-0.p-2 Na2CO3 + CO2 + H2O -→ 2NaHCO3 #[br]
              strong.bg-green7.mb-0.p-2 NaOH + CO2 → -NaHCO3
          li 
            i.fas.fa-check
            | En una muestra que contenga únicamente dióxido de carbono, bicarbonatos y carbonatos, la titulación hasta pH 8.3 a 25ºC corresponde a la neutralización estequiometria del ácido carbónico a bicarbonato, por esta razón, el cambio de color del indicador. (P.1).

      .col-md-5.mb-4
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-1-19.png' alt='Formula')


    .row.fondo-tema5-5.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center(data-aos="fade-down")
          p.mb-5 Le invitamos ahora a finalizar el apartado Parámetros químicos, estudiando, atentamente, algunos factores referentes a Carbono total y Nitrógeno total.
          h4.text-center.mb-4 Carbono total
          .row.justify-content-center.mb-5
            .col-md-6.col-lg-5.mb-5.mb-lg-0(data-aos="fade-right")
              .tarjeta-avatar.text-center
                img(src='@/assets/curso/temas/tema5/icono1.svg' alt='Carbono total')
                .tarjeta.bg-color-acento-contenido
                  .p-4
                    p Indica la cantidad total de carbono orgánico presente en una muestra, expresada en mg/L. En la actualidad existen equipos comerciales que proporcionan simultáneamente y como valores independientes el contenido total de carbono orgánico, junto al inorgánico y CO2 disuelto. Es un método instrumental, basado en la combustión total del carbono por oxidación a CO2 (Tª > 900 ºC) en presencia, si es necesario, de catalizadores de oxidación (V2O5).
            .col-md-6.col-lg-5.mb-5.mb-lg-0(data-aos="fade-right")
              .tarjeta-avatar.text-center
                img(src='@/assets/curso/temas/tema5/icono2.svg' alt='Carbono total')
                .tarjeta.bg-color-acento-contenido
                  .p-4
                    p Es un método rápido, siendo su principal inconveniente el coste del equipo y que en la actualidad no es un parámetro aceptado en la legislación vigente para aguas, situación que puede modificarse en un futuro próximo. Los métodos de muestreo son similares a los descritos para la determinación de DQO y DBO, debiendo tener especial cuidado en no someter las muestras a la luz.

          h4.text-center.mb-4 Nitrógeno total
          .row.justify-content-center.mb-5
            .col-md-10
              SlyderF(columnas="col-lg-6 col-xl-6")
                .row
                  .tarjeta-avatar.text-center.h-tem5-tarj2
                    img(src='@/assets/curso/temas/tema5/slide-ico1.svg' alt='Nitrógeno total')
                    .tarjeta.bg-green4
                      .p-4
                        p De acuerdo con el ciclo del nitrógeno, una concentración alta de nitrógeno orgánico es característica de una contaminación fresca o reciente, y por consiguiente de gran peligro potencial.
                        p Todo el nitrógeno presente en compuestos orgánicos puede considerarse nitrógeno orgánico. 
                .row
                  .tarjeta-avatar.text-center.h-tem5-tarj2
                    img(src='@/assets/curso/temas/tema5/slide-ico2.svg' alt='Nitrógeno total')
                    .tarjeta.bg-green4
                      .p-4
                        p El contenido de nitrógeno orgánico en un agua incluye el nitrógeno de aminoácidos, aminas, polipéptidos, proteínas y otros compuestos orgánicos del nitrógeno.
                        p El nitrógeno amino de la mayoría de materiales orgánicos y el amoniaco libre son convertidos a amonio en presencia de H2SO4, sulfato de potasio (K2SO4), y sulfato de Cobre II (CuSO4) como catalizador.
                .row
                  .tarjeta-avatar.text-center.h-tem5-tarj2
                    img(src='@/assets/curso/temas/tema5/slide-ico3.svg' alt='Nitrógeno total')
                    .tarjeta.bg-green4
                      .p-4
                        p Durante la digestión, el carbono y el hidrógeno son oxidados a dióxido de carbono y agua, mientras el sulfato es reducido a dióxido de azufre y el grupo amino es liberado como amoníaco, el cual no puede escapar del medio ácido y permanece como una sal de amonio. Después de la adición de hidróxido, el amoniaco es destilado desde el medio alcalino y absorbido en ácido sulfúrico 0.02M, de la solución ácida el amoniaco es liberado por adición de NaOH a pH 11 y es leído con un electrodo selectivo de amoníaco.
                .row
                  .tarjeta-avatar.text-center.h-tem5-tarj2
                    img(src='@/assets/curso/temas/tema5/slide-ico4.svg' alt='Nitrógeno total')
                    .tarjeta.bg-green4
                      .p-4
                        p El método se aplica en este laboratorio para la matriz aguas residuales industriales y superficiales. Se emplea para el intervalo de 0,50 a 1.000 mg de N/L. Es un método electrométrico, en el que se determina el amoniaco y se expresa como nitrógeno (N). El método Kjeldahl determina el nitrógeno en estado tri negativo; el “Nitrógeno Kjeldahl” es la suma del nitrógeno Orgánico y el nitrógeno amoniacal.


    h3.subt.text-white.mb-4(data-aos="fade") Parámetros microbiológicos
    p.mb-4(data-aos="fade") El objetivo de la prueba microbiológica del agua es proveer subsidio acerca de su potabilidad, es decir, ausencia de riesgo de ingestión de microorganismos causadores de enfermedades, mayormente provenientes de la contaminación por excrementos humanos y de otros animales de sangre caliente. Vale resaltar que los microorganismos presentes en aguas naturales son, en su mayoría, inofensivos a la salud humana.

    SlyderA.bg-blue2.br-20.p-4.mb-5(tipo="b" data-aos="fade-down")
      .row.justify-content-center
        .col-md-5.mb-4.mb-md-0
          p Pero en la contaminación por desecho sanitario están presentes microorganismos que podrán perjudicar la salud humana. Los microorganismos patogénicos incluyen virus, bacterias, protozoarios y helmintos, coliformes totales y  E.Coli. Bajo el Método NMP pueden encontrarse:
          p La Escherichia coli forma la mayor parte de la flora comensal aerobia y anaerobia facultativa del tubo digestivo, y se elimina por las heces al exterior, por lo tanto, no es Infrecuente que se encuentre en el medio ambiente, donde son capaces de sobrevivir durante cierto tiempo en el agua y los alimentos, de manera que su aislamiento constituye un indicador de contaminación fecal reciente.      
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema5/slide-b-1.png', alt='Imagen decorativa')
      .row.justify-content-center
        .col-md-5.mb-4.mb-md-0
          p Puede intervenir en procesos patológicos como la producción de cuadros intestinales, diarreas e infecciones extra intestinales diversas.
          p Los coliformes totales, se encuentran con más frecuencia en el medio ambiente, pueden estar en el suelo y en las superficies del agua dulce, por lo que no son siempre intestinales, su identificación en estas fuentes sugiere fallas en la eficiencia del tratamiento y la integridad del sistema de distribución.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema5/slide-b-2.png', alt='Imagen decorativa')   
      .row.justify-content-center
        .col-md-5.mb-4.mb-md-0
          p La prueba de enzima – sustrato definido, se fundamenta en la actividad enzimática de los Coliformes totales y los coliformes fecales (E. coli) Los coliformes totales se diferencian según su capacidad para fermentar lactosa, así:
          p Fermentadores rápidos: E. coli, klebsiella, enterobacter, poseen 2 enzimas, la betagalactósido - permeasa, su actividad es permitir que la lactosa se difunda a través de la membrana celular. La otra es la beta-galactosidasa la cual descompone por hidrólisis el enlace beta - galactósido que une las moléculas de glucosa y galactosa para formar el disacárido de lactosa, liberando así la glucosa que de esta manera puede ser fermentada. Los fermentadores lentos: carecen de la enzima beta -galactósido - permeasa.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema5/slide-b-3.png', alt='Imagen decorativa')               
      .row.justify-content-center
        .col-md-5.mb-4.mb-md-0
          p Los no fermentadores, no poseen ninguna de las enzimas. En los medios sólidos con lactosa se comportan en general como no fermentadoras y solo puede detectarse demostrando la presencia de beta - galactosidasa por la reacción del ONPG (ortonitrofenil – galactopiranósido) compuesto capaz de atravesar la pared celular y que la beta -galactosidasa descompone en galactosa y ortonitrofenil, que al liberarse en medio alcalino toma un color amarillo pálido.
          p El método está recomendado para análisis microbiológico para las muestras de agua en general, ya sea potable, de consumo humano, no tratadas, residuales, aguas de alberca y de playa. El método es aplicable en un rango de 1 a 1800 NMP/100mL para detectar y cuantificar la concentración de coliformes totales y E.coli para evaluar la calidad microbiológica de estas.
        .col-md-6
          figure
            img(src='@/assets/curso/temas/tema5/slide-b-4.png', alt='Imagen decorativa')

    .row.justify-content-center.mb-5
      .col-md-10(data-aos="fade")
        .cajon.color-acento-contenido.row.align-items-center.p-4
          .col-md-2
            img.mx-auto.px-4(src='@/assets/curso/temas/tema5/cajon-ico2.svg' alt='Imagen decorativa')
          .col-md-10
            p.mb-0 La materia Según el Decreto 475 de 1998, por el cual se expiden normas técnicas de calidad de agua potable:
            p Artículo 25. El agua para consumo humano debe cumplir con los siguientes valores admisibles desde el punto de vista microbiológico. Número más probable:
            ol.lista-ol
              li 
                span.text-bold a. 
                | Coliformes totales.  microorganismos 0/100 mL
              li 
                span.text-bold b. 
                | E. coli. 0 microorganismos /100mL

    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema5/bloque-img.jpg')})`}")
      .bloque-texto-g__texto.p-4
        p.mb-0 Otro método por el cual se puede identificar presencia de microorganismos es el Método de filtración por membrana en agar chromocult. La filtración por membrana es el mecanismo mediante el cual se atrapan en la superficie de la membrana microorganismos cuyo tamaño es mayor que el tamaño del poro 0.45 um, esto gracias a que una bomba eléctrica ejerce una presión diferencial sobre la muestra de agua haciendo que se filtre.

    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        p Los contaminantes de tamaño menor que el específico del poro atraviesan la membrana o se quedan retenidos en su interior, las bacterias quedan en la superficie de la membrana y luego está es llevada a un medio de enriquecimiento selectivo. En el IDEAM se utiliza el medio de cultivo Chromocult el cual promueve el crecimiento y la identificación.
        p El medio de cultivo contiene el sutrato Salmon GAL – 6 cloro – 3 indol y βD galactopiranosido es un sustrato cromogénico que es usado para la detección de la enzima galactosidasa de colonias bacterianas en un ensayo colorimétrico; que da como resultado el cambio de la colonia a un color rojo salmón.
        p Esta reacción se observa cuando hay coliformes totales. Para diferenciar la E.coli de los coliformes totales se hace por medio del sustrato cromogénico X-Glucorósido, que reacciona con la enzima glucuronidasa pero estas también reaccionan con el sustrato Salmón- GAL produciendo un color azul - violeta en la colonia.
      .col-md-5(data-aos="fade-left")   
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img-5-1-20.png' alt='Imagen decorativa')

    .row.align-items-center.mb-4
      .col-md-4.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img-5-1-21.png' alt='Imagen decorativa')
      .col-md-8(data-aos="fade-left")   
        .bloque-texto-c.bg-green2.box-shadow.p-3.px-4.mb-4
          i.fas.fa-quote-right.mb-2
          p.mb-3 El método es aplicable a aguas superficiales y residuales en el IDEAM en un rango de 1 a 200000 UFC/100mL. Según el Decreto 1575 de 2007 “Por el cual se expiden normas técnicas de calidad de agua potable”. Artículo 25. El agua para consumo humano debe cumplir con los siguientes valores admisibles desde el punto de vista microbiológico. Filtración por membrana: 
          p.mb-0 • Coliformes totales. 0 UFC/100mL y
          p.mb-3 • E. coli, 0 UFC/100mL. (pp.2-3)
          span.text-bold.mb-0 - Según IDEAM (2007)

    p.mb-5 Le invitamos a continuar con el estudio de los ítems Macroinvertebrados y Bioindicadores para se ha preparado una gráfica interactiva. ¡Adelante!


    h4.t-green.mb-4 Macroinvertebrados y Bioindicadores

    .row.align-items-center.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        SlyderA.bg-blue2.br-20.p-4(tipo="b" data-aos="fade-down")
          .row.justify-content-center
            .col-md-2.col-6.mb-3
              img.mx-auto.px-3(src='@/assets/curso/temas/tema5/slide-b2-1.png' alt='Imagen decorativa')
            p Los macroinvertebrados bénticos son animales que habitan en el sustrato de lagos, cursos de agua, estuarios y aguas marinas. Pueden construir camisas, tubos o redes fijas, viviendo dentro o sobre ellos, o vagar libremente sobre las rocas, residuos orgánicos y otros sustratos durante todo o parte de su ciclo vital. 
          .row.justify-content-center
            .col-md-2.col-6.mb-3
              img.mx-auto.px-3(src='@/assets/curso/temas/tema5/slide-b2-2.png' alt='Imagen decorativa')
            p Las respuestas de la comunidad macroinvertebrada a las perturbaciones ambientales son útiles para evaluar el impacto de los residuos municipales, agrícolas, de la industria petrolífera y los impactos de otros usos del suelo sobre los cursos de agua superficiales.
          .row.justify-content-center
            .col-md-2.col-6.mb-3
              img.mx-auto.px-3(src='@/assets/curso/temas/tema5/slide-b2-3.png' alt='Imagen decorativa')
            p Por otra parte, el cieno y la contaminación química tóxica pueden no sólo reducir, sino incluso eliminar la comunidad macroinvertebrada completa de una zona afectada.
          .row.justify-content-center
            .col-md-2.col-6.mb-3
              img.mx-auto.px-3(src='@/assets/curso/temas/tema5/slide-b2-4.png' alt='Imagen decorativa')
            p Aunque los macroinvertebrados por definición se consideran visibles a simple vista, y quedan retenidos en un tamiz del número 30 U. S. Standard (abertura de 0.595mm). (APHA,1995).
          .row.justify-content-center
            .col-md-2.col-6.mb-3
              img.mx-auto.px-3(src='@/assets/curso/temas/tema5/slide-b2-5.png' alt='Imagen decorativa')
            p Existe documentación acerca de tres situaciones en las que cambia el tipo estructural de la comunidad macroinvertebrada, y son la carga orgánica, alteración del sustrato y contaminación química tóxica. La contaminación orgánica tóxica suele restringir la variedad de macroinvertebrados, quedando los más resistentes, y da lugar al correspondiente aumento de densidad de los que toleran las condiciones contaminadas, normalmente una baja concentración de oxígeno disuelto.
          .row.justify-content-center
            .col-md-2.col-6.mb-3
              img.mx-auto.px-3(src='@/assets/curso/temas/tema5/slide-b2-6.png' alt='Imagen decorativa')
            p Limitaciones e interferencias. Limitaciones en la separación: dado el gran volumen de muestra y para economizar tiempo en una labor tan dispendiosa algunos investigadores recomiendan no observar toda la muestra, sino la separación y observación de submuestras de la muestra integrada. Sin embargo, otros científicos desaprueban esta práctica. Debido a que el nivel de conocimiento en Colombia de la flora y fauna acuática de agua dulce es aún escaso e incompleto, se propone utilizar un método intermedio.
          .row.justify-content-center
            .col-md-2.col-6.mb-3
              img.mx-auto.px-3(src='@/assets/curso/temas/tema5/slide-b2-7.png' alt='Imagen decorativa')
            p Limitación por el nivel de determinación: debe tenerse en cuenta que dentro de los métodos existentes los hay desde los más simples, en los cuales bastaría utilizar sólo grupos mayores de organismos (por ejemplo, al nivel de órdenes y familias), hasta los más complejos como el sistema saprobio alemán, el cual exige llegar hasta el nivel de especie.    
      .col-md-5(data-aos="fade-left")   
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img-5-1-22.png' alt='Imagen decorativa')








    Separador


    #t_5_2
    .titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 5.2 Manejo de residuos, características de peligrosidad 

    p(data-aos="fade") Los residuos de laboratorios de análisis de agua se clasifican en diversas categorías en función de su naturaleza, peligrosidad y destino final. Le invitamos a revisar la Tabla 5 del Anexo 6 para que afiance su comprensión al respecto del Manejo de residuos, característica de peligrosidad.

    Separador


    #t_5_3
    .titulo-segundo.color-acento-contenido(data-aos="fade")
      h2 5.3 Método Biological Monitoring Working Party BMWP

    .row.justify-content-center.align-items-center.mb-4
      .col-md-3.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-3-1.png' alt='Imagen decorativa')
      .col-md-9.mb-4(data-aos="fade-left")
        AcordionA(data-aos="fade-down" tipo="a" clase-tarjeta="tarjeta bg-gris3")
          .row.justify-content-center(titulo="BMWP / Clasificación de contaminación orgánica")
            .col-md-11
              p En el caso de BMWP / Clasificación de contaminación orgánica, la presencia de moscas de mayo o moscas de piedra, por ejemplo, indica las vías fluviales más limpias y se les da un puntaje de tolerancia de 10. [2] Los invertebrados con menor puntuación son los gusanos (Oligochaeta) que puntúan 1. El número de macroinvertebrados diferentes también es un factor importante, porque se supone que una mejor calidad del agua contiene menos contaminantes que incluirían especies “sensibles”, lo que da como resultado una mayor diversidad.
          .row.justify-content-center(titulo="Muestreo de patada")
            .col-md-11
              p Se emplea el muestreo de patada, donde se coloca una red de aguas abajo del muestreador y el lecho del río se agita con el pie durante un período de tiempo determinado (el estándar es de 3 minutos) Todos los macroinvertebrados atrapados en la red se almacenan y conservan con una solución de alcohol, y se identifican a nivel familiar , esto también se puede hacer con los organismos vivos.

    p.text-center.mb-5(data-aos="fade") Recolección de macroinvertebrados. 

    .row.justify-content-center.align-items-center
      .col-md-9.mb-4(data-aos="fade-right")
        AcordionA(data-aos="fade-down-right" tipo="a" clase-tarjeta="tarjeta bg-gris3")
          .row.justify-content-center(titulo="Puntaje de BMWP")
            .col-md-11
              p El puntaje de BMWP es igual a la suma de los puntajes de tolerancia de todas las familias de macroinvertebrados en la muestra. Se considera que un puntaje BMWP más alto refleja una mejor calidad del agua. Alternativamente, también se calcula el puntaje promedio de puntaje por taxón (ASPT) El ASPT es igual al promedio de los puntajes de tolerancia de todas las familias de macroinvertebrados encontrados, y varía de 0 a 10. 
          .row.justify-content-center(titulo="Índice de Calidad de Lincoln (LQI)")
            .col-md-11
              p La principal diferencia entre ambos índices es que el ASPT no depende de la riqueza familiar. Una vez que se calculan BMWP y ASPT, se utiliza el Índice de Calidad de Lincoln (LQI) para evaluar la calidad del agua en el área de la Autoridad de Agua de Anglian.
      .col-md-3.mb-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema5/img5-3-2.png' alt='Imagen decorativa')
        


</template>

<script>
export default {
  name: 'Tema5',
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
