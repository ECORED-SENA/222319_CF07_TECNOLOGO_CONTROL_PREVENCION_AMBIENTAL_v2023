<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Protocolos para análisis de agua, suelo, olores y residuos sólidos
    
    
    .row.justify-content-center
      .col-md-4.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema4/img.png' alt='Imagen decorativa')
      .col-md-8(data-aos="fade-left")
        p La importancia que representa la calidad del agua, el suelo y la reducción de los malos olores emitidos por distintos tipos de fuentes es asegurado por los protocolos de análisis químicos, físicos y microbiológicos donde se identifica la información necesaria de los analitos en cuestión; para obtener datos de forma precisa y exacta de las características de la muestra analizada. Estos datos deben provenir de muestras representativas y análisis de acuerdo con protocolos que sigan estrictas normas técnicas y legales de control de calidad. Los análisis clásicos (volumétricos y gravimétricos) y las técnicas instrumentales de análisis cobran gran relevancia en el control y caracterización medioambiental; ofreciendo alternativas de solución a diversas problemáticas que surgen de los las prácticas de uso del agua y el suelo y de los procesos industriales de los diversos sectores de mundo. 

    Separador

    #t_4_1
    .titulo-segundo.color-acento-contenido
      h2 4.1 Parámetros de análisis físicos, químicos y microbiológicos el agua     

    .row.justify-content-center.align-items-center
      .col-md-7.mb-4(data-aos="fade-right")
        p.mb-md-5 La calidad del agua superficial es una de las condiciones ambientales más importantes en el monitoreo actual del país y el mundo; la calidad del agua depende tanto de factores naturales, como de la acción humana, y se determina comparando las características físicas y químicas de una muestra de agua, con unas directrices legales de calidad del agua o estándares técnicos.
        .tarjeta.bg-degrade-green.p-3
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img.px-2(src="@/assets/curso/temas/tema6/icono.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 Parámetros análisis del agua
                  p.text-small.mb-0 Conozca los Parámetros de análisis físico, químico y microbiológico del agua.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Parametros-analisis-agua.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      .col-md-5(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema4/img4-1.png' alt='Imagen decorativa')

    Separador

    #t_4_2
    .titulo-segundo.color-acento-contenido
      h2 4.2 Parámetros de análisis físicos, químicos y microbiológicos del suelo  

    .row.justify-content-center.align-items-center
      .col-md-5.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema4/img4-2.png' alt='Imagen decorativa')
      .col-md-7(data-aos="fade-left")
        p.mb-md-5 La calidad del suelo ha sido definida por la Sociedad de Ciencias del Suelo de América, como “la capacidad de un tipo específico de suelo para funcionar, dentro de los límites de los ecosistemas naturales, para sostener la productividad vegetal y animal, mantener y/o mejorar la calidad del agua y del aire, y apoyar la salud y la vivienda”.
          .tarjeta.bg-degrade-green.p-3
            .row.justify-content-around.align-items-center
              .col-3.col-sm-2.col-lg-2
                img.px-2(src="@/assets/curso/temas/tema6/icono.svg")
              .col
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0.text-white
                    h4.mb-1 Parámetros análisis del suelo
                    p.text-small.mb-0 Conozca los Parámetros de análisis físico, químico y microbiológico del suelo.
                  .col-sm-auto
                    a.boton.color-acento-botones(:href="obtenerLink('/downloads/Parametros analisis-suelo.pdf')" target="_blank")
                      span Descargar
                      i.fas.fa-file-download

    Separador

    #t_4_3
    .titulo-segundo.color-acento-contenido
      h2 4.3 Parámetros de análisis físicos, químicos y microbiológicos del olor      

    p.mb-md-5(data-aos="fade") Al hablar de calidad del aire atmosférico se debe recurrir, a la siguiente normatividad legal y técnica.       

    .row.fondo-tema3-2-1.align-items-center.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-between.align-items-center.py-5
          .col-md-5.mb-4
            h4 Normatividad legal y técnica para la calidad del aire atmosférico
            p Es momento de revisar la normatividad que rige los parámetros de análisis físicos, químicos y microbiológicos del olor. Presione cada uno de los botones que aparecen en pantalla y estúdielos atentamente.
          .col-md-6
            ImagenInfografica.color-acento-botones
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/tema4/img-infog.svg', alt='Normatividad legal y técnica para la calidad del aire atmosférico')

              .tarjeta.bg-yellow.p-3(x="31%" y="28%" numero="+")
                .h4.mb-2 Resoluciones
                ul.lista-ul
                  li.mb-1
                    i.lista-ul__vineta
                    | Resolución 601 de 2006
                  li.mb-1 
                    i.lista-ul__vineta
                    | Resolución 1541 de 2013
                  li.mb-1 
                    i.lista-ul__vineta
                    | Resolución 672 de 2014
                  li.mb-1
                    i.lista-ul__vineta
                    | Resolución 1490 de 2014
                  li.mb-1 
                    i.lista-ul__vineta
                    | Resolución 2087 de 2014
                p.mb-0 “Por la cual se establece la norma de calidad de aire o nivel de inmisión, para todo territorio nacional en condiciones de referencia”.
              .tarjeta.bg-yellow.p-3(x="27%" y="75%" numero="+")
                .h4.mb-2 Normas internacionales
                ul.lista-ul
                  li.mb-1
                    i.lista-ul__vineta
                    | Norma Europea UNE EN 13725 de 2004
                  li.mb-1 
                    i.lista-ul__vineta
                    | Norma Chilena NCh 3190 de 2010
                  li.mb-1 
                    i.lista-ul__vineta
                    | Norma Alemana VDI 3880 de 2011
                  li.mb-1 
                    i.lista-ul__vineta
                    | Norma Alemana VDI 3884 de 2015  
                p.mb-0 Citado de: tqi.co (s, f). Soluciones-confiables-olfatometría https://tqi.co/soluciones-confiables/olfatometria/#
              .tarjeta.bg-yellow.p-3(x="71%" y="15.5%" numero="+")
                .h4.mb-2 Normas técnicas colombianas
                ul.lista-ul
                  li.mb-1
                    i.lista-ul__vineta
                    | NTC 5880
                  li.mb-1 
                    i.lista-ul__vineta
                    | NTC 6011
                  li.mb-1 
                    i.lista-ul__vineta
                    | NTC 6012 – 1
                p.mb-0 Calidad del aire. Determinación de la concentración de olor por olfatometría dinámica.
              .tarjeta.bg-yellow.p-3(x="63%" y="72%" numero="+")
                .h4.mb-2 Norma UNE-EN 13725: 2004
                p.mb-0 Según la norma UNE-EN 13725: 2004 “Calidad del aire. Determinación de la concentración de olor por olfatometría dinámica”, define el olor como “la propiedad organoléptica perceptible por el órgano olfativo cuando inspira sustancias volátiles”. Esta norma desarrolla las cuestiones relacionadas con la toma de muestras, cuantificación de la concentración de olor y cálculo de la emisión de olor de los focos.


    p(data-aos="fade") Para afianzar más y mejor los parámetros físicos, químicos y microbiológicos del olor, le presentamos algunos elementos conceptuales y técnicos, adicionales, de suma importancia.      

    .row.fondo-tema4-3.align-items-center.mb-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center.py-5
          .col-md-12.mb-4
            h4 Parámetros de análisis físicos, químicos y microbiológicos del olor:
            p El olor es una reacción sensorial de determinadas células situadas en la cavidad nasal. La relación entre olor y molestia percibida es compleja de definir. En esa confluyen factores físicos y químicos fáciles de determinar, pero también otros de carácter subjetivo más difícil de evaluar, como, por ejemplo, el carácter agradable o desagradable del olor (tono hedónico), la sensibilidad de cada persona, o el entorno en el que es percibido. 
          
          .col-md-6.mb-4
            ImagenInfografica.color-acento-botones
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/tema4/img-infog2.svg', alt='Parámetros de análisis físicos, químicos y microbiológicos del olor')

              .tarjeta.bg-yellow.p-3(x="62%" y="7%" numero="+")
                .h4.mb-2 Regulación Ambiental
                p.mb-0 En los últimos años, la regulación ambiental ha aumentado significativamente, en paralelo a una sociedad más participativa y dotada de una mayor concienciación ambiental, que reclama la intervención de las administraciones públicas con el objetivo de garantizar el bienestar y la calidad de vida.
              .tarjeta.bg-yellow.p-3(x="100%" y="35%" numero="+")
                .h4.mb-2 Contaminación Ambiental
                p.mb-0 Los malos olores causados por actividades tales como explotaciones de ganado, actividades industriales, depuradoras, vertederos, etc., se entienden como un tipo de contaminación ambiental debido a que, aunque los olores no lleguen a ser tóxicos, pueden llegar a provocar malestar, molestias respiratorias, alteraciones psicológicas.
              .tarjeta.bg-yellow.p-3(x="99%" y="71%" numero="+")
                .h4.mb-2 Los olores y la salud pública
                p.mb-0 Al ser los olores un factor para la aceptación o rechazo, la población puede llegar a percibir los olores como un peligro para su salud, ocasionando niveles de descontento tan negativos como cualquier otro problema ambiental. Los problemas derivados de las molestias a la población de las actividades generadoras de los olores son difíciles de abordar por cuestiones de vacío legal o técnicas ya que por el momento no existe en nuestro país legislación estatal que regule o limite las emisiones de olor.
              .tarjeta.bg-yellow.p-3(x="48%" y="100%" numero="+")
                .h4.mb-2 Orígenes
                p.mb-0 El olor puede tener varios orígenes en función de la fuente que lo genere. Esto implica que la forma de tratar las molestias asociadas se debe abordar de distintas formas. Se debe tener en consideración que la afectación sobre el entorno varía y tiene unas características específicas según el tipo de procedencia.
              .tarjeta.bg-yellow.p-3(x="0%" y="71%" numero="+")
                .h4.mb-2 Episodios de Olor
                p.mb-0 Así, por ejemplo, se pueden producir desde situaciones en las que existan áreas extensas afectadas hasta fenómenos puntuales, tanto en el ámbito espacial como temporal. Es decir, que es necesario tener en cuenta que puede haber muchos tipos de episodios de olor: baja intensidad, pero larga duración, alta intensidad y corta duración, puntuales a lo largo de un período de tiempo, o de una alta frecuencia temporal. Este hecho obliga a objetivar la molestia ofreciendo unas garantías tanto al ciudadano como a las instalaciones generadoras de olor.
              .tarjeta.bg-yellow.p-3(x="1%" y="33%" numero="+")
                .h4.mb-2 Olfatometría
                p.mb-0 La olfatometría es una técnica de toma de muestras y análisis de olores que, unida al desarrollo de sistemas de modelización de la dispersión, permite evaluar las molestias producidas por malos olores y determinar el origen de las mismas.
          
          .col-md-10
            .row.justify-content-center.align-items-end.tarjeta.bg-gris.px-4.pt-3
              .col-md-2.col-5.mb-3.mb-md-0
                img.px-2(src="@/assets/curso/temas/tema4/icono.svg")
              .col-md-10.p-md-3
                p Los estudios olfato métricos constituyen una herramienta de gran utilidad para el control y reducción de los malos olores emitidos por distinto tipo de fuentes. Estos estudios permiten no sólo determinar el grado de molestia creado en el entorno, sino también identificar las fuentes de olor realmente importantes y adoptar sistemas eficaces de eliminación.
                p.mb-0 Citado de: Asociación Española para la calidad AEC (2010) Contaminación Odorífera  p.1-2
                p https://www.aec.es/c/document_library/get_file?uuid=3527643c-0525-42fd-9943-1c881254e44f&groupId=10128

    p Es momento de adentrarse en las Técnicas físico químicas de análisis olfatométricos. La caracterización de los olores se puede realizar mediante dos técnicas esencialmente: sensoriales y analíticas.

    .row.fondo-tema4-3-1.align-items-center.mb-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center.pt-5
          .col-md-7.mb-4(data-aos="fade-right")
            h3.subt.text-white.mb-4 a. Técnicas sensoriales
            p.mb-5 Se basan en la percepción de los olores por el olfato humano. También incluyen la determinación del carácter de un olor (mapeo) y el nivel de agrado o desagrado de un olor (tono hedónico). Las técnicas sensoriales utilizan asesores humanos para medir un olor, siendo la olfatometría, la técnica usada comúnmente. Dicha prueba evalúa las diluciones con aire limpio que un olor debe sufrir para no ser detectable por un humano promedio (umbral de detección).
            h4.t-green Mapeo triangular
            p Otras técnicas sensoriales incluyen la determinación del carácter de un olor (mapeo triangular) y el nivel de agrado o desagrado de un olor (tono hedónico) Las técnicas sensoriales tienen la ventaja de que proveen información útil sobre cómo las personas perciben los olores y el grado de molestia que provoca un olor determinado, o bien para evaluar la efectividad de un equipo de control de olores. La desventaja de este método es que no es específico y consecuentemente no identifica las especies químicas causantes del olor. Dentro de las técnicas sensoriales tenemos:
          .col-md-5(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema4/img4-3.png' alt='Imagen decorativa')
        .row.mb-4 
          .col-md-6.mb-4(data-aos="fade-down")
            .bg-color-acento-contenido.h-477.br-20.px-3.py-4 
              .row.justify-content-center.mb-4
                h4.t-green2.text-center.mb-4 Olfatometría dinámica
                .col-3
                  figure.px-md-2
                    img.mx-auto(src='@/assets/curso/temas/tema4/ico1.svg' alt='Icono decorativo')  
              p.px-md-4 La norma UNE-EN 13725:2004 establece un marco normativo de regulación para la toma de muestras y ensayo por olfatometría dinámica, en los que se utiliza el olfato humano como sensor. Esta norma define una metodología para la determinación de la concentración de olor de una muestra gaseosa usando un panel de “evaluadores” humanos (panelistas) como sensor, así como la determinación de la emisión. 
          .col-md-6.mb-4(data-aos="fade-down")
            .bg-color-primario.h-477.br-20.px-3.py-4 
              .row.justify-content-center.mb-3
                h4.t-green.text-center.mb-4 Interpretación de Valores
                .col-3
                  figure.px-md-2
                    img.mx-auto(src='@/assets/curso/temas/tema4/ico2.svg' alt='Icono decorativo')  
              .bloque-texto-c.sin-cuadro.p-4
                i.fas.fa-quote-right.mb-2
                p.mb-3.text-white El objetivo primordial de un estudio olfatométricos es evaluar si las emisiones de una determinada instalación pueden ser responsables o no de quejas en la población vecina. A esta conclusión se llega con la interpretación de los valores de concentración de inmisión, habitualmente denominados mapas de olores.
                span.text-bold.text-white.mb-0 - Según Monteiro T (2012)  (pp.51-52).      

    .row.justify-content-center.align-items-center.pt-5
      .col-md-8.mb-4(data-aos="fade-right")
        h3.subt.text-white.mb-4 b.	Técnicas analíticas
        p Son métodos tradicionales de análisis químico para medir la concentración de compuestos específicos presentes en un olor. Puede hacerse mediante cromatografía de gases y espectrometría de masas, mediante métodos húmedos (para mercaptanos) mediante narices electrónicas o mediante indicadores.
        p.p-3.bg-green3 Las técnicas analíticas para caracterización de olores son relativamente fáciles de aplicar e identificar cuantitativamente las especies químicas presentes en un olor. La desventaja de la técnica es que no provee información alguna referente a la molestia que puede generar un olor.
        p La contribución de las especies químicas aisladas puede sumarse para obtener la concentración global del olor. La presencia o ausencia de una especie química en la mezcla de gases, o las concentraciones de éstas pueden potenciar, disminuir o inclusive cambiar la percepción de un olor por completo.
        p Debido a esto, las técnicas analíticas son usadas para definir criterios de diseño de métodos de control de olores, para determinar si las emisiones de una sustancia química específica están dentro de los niveles permitidos por las normas o para estimar la relación entre la concentración de una sustancia química y su equivalente en términos de percepción humana.
      .col-md-4(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema4/img4-3-2.png' alt='Imagen decorativa')


    .row.justify-content-center.align-items-center.pt-5
      .col-md-4.mb-4(data-aos="fade-right")
        figure
          img.mx-auto(src='@/assets/curso/temas/tema4/img4-3-3.png' alt='Imagen decorativa')
      .col-md-8(data-aos="fade-left")
        AcordionA(data-aos="fade-down-right").mb-5(tipo="a" clase-tarjeta="tarjeta bg-green7")
          .row.justify-content-center(titulo="Narices electrónicas")
            .col-md-8.mb-4.mb-lg-0
              p Las narices electrónicas son una serie de sensores de distintos materiales metálicos que reaccionan de forma distinta a un mismo componente químico.
              p Cuando una muestra olorosa entra en contacto con estos, se produce una respuesta química que se evalúa de forma conjunta para la totalidad de los sensores. La respuesta se relaciona con la intensidad o concentración del olor a partir de los valores obtenidos por panelistas humanos que  trasladan los resultados a una base de datos que queda registrada.
            .col-md-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema4/acord1.png')  
          .row.justify-content-center(titulo="Espectrometría infrarroja")
            .col-md-8.mb-4.mb-lg-0
              p Los análisis químicos son métodos de investigación y tienen la ventaja de ser repetibles y seguros, y se usan para caracterizar los componentes químicos de episodios de olor, especialmente para compuestos desconocidos. Sin embargo, una muestra puntual para un periodo de tiempo con análisis químicos subsecuentes, provee sólo información integrada de tiempo, pero no información relacionada con la frecuencia, intensidad y duración de la exposición, la cual es requerida para identificar efectivamente la huella de los componentes del olor. 
              p En décadas anteriores se han desarrollado mejores tecnologías para análisis de compuestos químicos, como el espectrómetro transformador infrarrojo de paso abierto de Fourier (Open-Path Fourier transforminfrared / OP-FTIR) el cual ofrece monitoreo remoto, análisis multicompuestos rápidos y mediciones promedio.
            .col-md-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema4/acord2.png')       
          .row.justify-content-center(titulo="Cromatografía de gases‐olfatometría, o GCO")
            .col-md-8.mb-4.mb-lg-0
              p La cromatografía de gases‐olfatometría, o GCO, consiste en evaluar con la nariz humana las cualidades aromáticas de los compuestos que eluyen de la columna cromatográfica, a la vez que el detector instrumental instalado proporciona un cromatograma.
              p De esta manera se pueden asignar olores a los picos y/o determinarse a qué tiempos de retención se detectan olores. Así, tal y como puede verse en la siguiente figura, la detección olfatométrica y la instrumental son simultáneas, lo que permite relacionar la información sensorial con la información química.
            .col-md-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/temas/tema4/acord3.png')       

    p.mb-5(data-aos="fade") En la siguiente tabla se enuncian algunos procedimientos para la determinación de la concentración de sustancias de olores ofensivos en calidad del aire o inmisión:

    .titulo-sexto.color-acento-contenido(data-aos="fade-down")
      h5 Tabla 1. 
      span Elementos para la determinación de la concentración de sustancias de olores ofensivos en calidad del aire o inmisión

    .tabla-c.tema4.mb-4(data-aos="fade-down")
      table
        tr.bg-green8
          td(colspan="2")
            h4.text-center.mb-0 Elementos para la determinación de la concentración de sustancias de olores ofensivos en calidad del aire o inmisión
        tr
          td(rowspan="5" class="text-center")
            h5 Sustancia Evaluación analítica 
            h5 Sulfuro de hidrógeno (H2S)
          td 
            p.mb-0 Sustancia Evaluación analítica.
        tr
          td 
            p.mb-0 Método automático. Determinación de los niveles de sulfuro de hidrogeno y TRS en el aire por fluorescencia UV.
        tr
          td 
            p.mb-0 Método 701. Determinación de sulfuro de hidrógeno en la atmósfera.
        tr
          td 
            p.mb-0 Métodos de muestreo y análisis de aire, 3a edición.
        tr
          td 
            p.mb-0 Método MFC/FD/FPD. Determinación de las emisiones de azufre.
        tr
          td 
            h5.text-center Azufre total reducido (TRS)
          td 
            p.mb-0 Azufre total reducido Método automático. Determinación de los niveles de sulfuro de hidrogeno y TRS en el aire por fluorescencia UV.
        tr
          td(rowspan="4" class="text-center")
            h5 Amoniaco (NH3)
          td 
            p.mb-0 Método 401. Determinación de amoniaco en la atmósfera - Método del indofenol. Métodos de muestreo y análisis de aire, 3a edición.
        tr
          td 
            p.mb-0 Método Automático. Determinación de amoniaco en la atmósfera.
        tr
          td 
            p.mb-0 Método trampas de ácido. Determinación de las concentraciones de amoniaco en aire por trampas de ácido.
        tr
          td 
            p.mb-0 Método Denuders. Medición de amoniaco por muestreo denuder anular con análisis en línea.

    .bg-gris3.text-small.p-2 
      p.mb-1 Citado de: fenavi.org. (2014). Resolución-2087-de-2014-Protocolo-Monitoreo-control-y-Vigilancia-de-Olores-Ofensivos-1.pdf. Colombia.p.9
      p.mb-0 https://fenavi.org/wp-content/uploads/2018/05/Resoluci%C3%B3n-2087-de-2014-Protocolo-Monitoreo-control-y-Vigilancia-de-Olores-Ofensivos-1.pdf         


    Separador

    #t_4_4
    .titulo-segundo.color-acento-contenido
      h2 4.4 Parámetros de análisis físicos y químicos de los residuos sólidos

    p(data-aos="fade") Entre los diversos temas que guardan relación con una problemática de tanta actualidad como la protección y conservación del medio ambiente, la gestión de residuos sólidos ocupa un lugar principal dentro de la gestión ambiental. Esta gestión integrada es el término aplicado a todas las actividades asociadas con el manejo de los diversos flujos de residuos dentro de la industria y sociedad.

    h3.subt.text-white.mb-4(data-aos="fade") Caracterización física y peso específico

    .row.mb-4 
      .col-md-6.mb-4(data-aos="fade-down")
        .bg-gris.h-410.br-20.px-3.py-4 
          .row.px-md-3.mb-4
            .col-3
              figure.px-md-2
                img(src='@/assets/curso/temas/tema4/ico3.svg' alt='Icono decorativo')  
          h5.px-md-4.mb-4 Caracterización física
          p.px-md-4 Las características físicas más importantes de los residuos sólidos incluyen: peso específico o, contenido de humedad, tamaño de partícula y distribución del tamaño, capacidad de campo y porosidad de los residuos compactados.
      .col-md-6.mb-4(data-aos="fade-down")
        .bg-color-secundario.h-410.br-20.px-3.py-4 
          .row.px-md-3.mb-3
            .col-3
              figure.px-md-2
                img(src='@/assets/curso/temas/tema4/ico4.svg' alt='Icono decorativo') 
          h5.px-md-4.mb-4 Peso específico
          p.px-md-4 El peso específico se define como el peso de un material por unidad de volumen (por ejemplo, kg/m3) Como el peso específico de los RS frecuentemente se refiere a residuos sueltos, encontrados en los contenedores, no compactados, compactados, etc., la base utilizada para los valores presentados siempre debe ser citada. Los datos sobre el peso específico a menudo son necesarios para valorar la masa y el volumen total de los residuos que tienen que ser gestionados.


    .row.fondo-tema4-4.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4(data-aos="fade-right")
              h3.subt.text-white.mb-4 Caracterización física y peso específico
              p.text-bold #[em M= (w-d) X 100]
              p donde:
              p.mb-0 #[em M] = Contenido de humedad, porcentaje.
              p.mb-0 #[em w] = Peso inicial de la muestra según se entrega (kg)
              p #[em d] = Peso de la muestra después de secarse a 105 ºC (kg)
              p El contenido de humedad de los residuos sólidos normalmente se expresa de dos formas. En el método de medición peso-húmedo, la humedad de una muestra se expresa como un porcentaje del peso del material húmedo; en el método peso-seco, se expresa como un porcentaje del peso seco del material. El método peso-húmedo se usa más frecuentemente en el campo de la gestión de residuos sólidos. En forma de ecuación, el contenido de humedad peso­-húmedo se expresa de la siguiente forma: 
              p.text-center.text-bold.bg-color-secundario2  #[em M= (w-d) X 100]
          .col-md-5(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema4/img4-3-4.png' alt='Imagen decorativa')


    h3.subt.text-white.mb-4(data-aos="fade") Tamaño de partícula y distribución del tamaño
    p.mb-4(data-aos="fade") El tamaño y la distribución del tamaño de los componentes de los materiales en los residuos sólidos son una consideración importante dentro de la recuperación de materiales, especialmente con medios mecánicos, como cribas, tromeles y separadores magnéticos. El tamaño de un componente puede definirse mediante una de las siguientes medidas:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-3.mb-4
        figure
          img.mx-auto(src='@/assets/curso/temas/tema4/form1.svg' alt='Formula')
      .col-md-5.mb-4
        p donde:
        p.mb-0 #[em M] = Contenido de humedad, porcentaje.
        p.mb-0 #[em w] = Peso inicial de la muestra según se entrega (kg)
        p #[em d] = Peso de la muestra después de secarse a 105 ºC (kg)

    .row.fondo-tema4-4.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4(data-aos="fade-right")
              h3.subt.text-white.mb-4 Capacidad de campo
              p La capacidad de campo de los residuos sólidos es la cantidad total de humedad que puede ser retenida por una muestra de residuo sometida a la acción de la gravedad. La capacidad de campo de los residuos es de una importancia crítica para determinar la formación de la lixiviación en los vertederos. El exceso de agua sobre la capacidad de campo se emitirá en forma de lixiviación. La capacidad de campo varía con el grado de presión aplicada y el estado de descomposición del residuo. Una capacidad de campo de un 30 por 100 en volumen se corresponde con 76,2 cm/256 cm. La capacidad de campo de los residuos no seleccionados y no compactados de orígenes domésticos y comerciales está en la gama del 50 al 60 por 100.
          .col-md-5(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema4/img4-3-5.png' alt='Imagen decorativa')


    h3.subt.text-white.mb-4(data-aos="fade") Permeabilidad de los residuos compactados
    p.mb-4(data-aos="fade") La conductividad hidrológica de los residuos compactados es una propiedad física importante que, en gran parte, gobierna el movimiento de líquidos y gases dentro de un vertedero. El coeficiente de permeabilidad normalmente se escribe como la imagen a continuación, donde:

    .row.justify-content-center.align-items-center.mb-4
      .col-md-3.mb-4
        figure
          img.mx-auto(src='@/assets/curso/temas/tema4/form2.svg' alt='Formula')
      .col-md-5.mb-4
        p donde:
        p.mb-0 #[em K] = Coeficiente de permeabilidad.
        p.mb-0 #[em C] = Constante sin dimensiones o factor de forma.
        p.mb-0 #[em d] = Tamaño medio de los poros.
        p.mb-0 #[em y] =  Peso específico del agua.
        p.mb-0 #[em µ] = Viscosidad dinámica del agua.
        p #[em K] = Permeabilidad intrínseca.


    .row.fondo-tema4-4.align-items-center.mb-5.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center
          .col-md-7.mb-4(data-aos="fade-right")
              h3.subt.text-white.mb-4 Caracterización fisicoquímica 
              p.mb-4 La información sobre la composición química de los componentes que conforman los RS es importante para evaluar las opciones de procesamiento y recuperación. Por ejemplo, la viabilidad de la incineración depende de la composición química de los residuos sólidos. Normalmente, se puede pensar que los residuos son una combinación de materiales semihúmedos combustibles y no combustibles. Si los residuos sólidos van a utilizarse como combustible, las cuatro propiedades más importantes que es preciso conocer son de acuerdo a Propiedades físicas, químicas y biológicas de los residuos sólidos urbanos capítulo 4:
              ul.lista-ul--color.color-primario.ps-3
                li 
                  i.fas.fa-check
                  | Humedad (pérdida de humedad cuando se calienta a 105 ºC durante una hora).
                li 
                  i.fas.fa-check
                  | Materia volátil combustible (pérdida de peso adicional con la ignición a 950 ºC en un crisol cubierto).
                li 
                  i.fas.fa-check
                  | Carbono fijo (rechazo combustible dejado después de retirar la materia volátil).
                li 
                  i.fas.fa-check
                  | Ceniza (peso del rechazo después de la incineración en un crisol abierto). (pp.4-5)   

          .col-md-5(data-aos="fade-left")
            figure
              img.mx-auto(src='@/assets/curso/temas/tema4/img4-3-6.png' alt='Imagen decorativa')

</template>

<script>
export default {
  name: 'Tema4',
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
