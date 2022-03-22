<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-primario
      .titulo-principal__numero.text-white
        span 1
      h1 Planes estratégicos

    p.mb-5(data-aos="fade") Para una correcta estructuración del plan estratégico, hay que abordar inicialmente el proceso administrativo que es una metodología que permite al administrador, gerente, ejecutivo, empresario, o cualquier otra persona, manejar eficazmente una organización. 

    .row.justify-content-end.hover-columna.banner.mb-5
      .col-md-8
        img(src='@/assets/curso/tema1-banner.png' alt='Imagen decorativa')
      .col-md-6.tarjeta.bg-acento-botones.recuadros-top-left.float-left
        .row.justify-content-end
          .col-md-10.p-4.py-md-3
            p.mb-0.text-white <b style="font-size: 18px;">Es importante</b>, para establecer un proceso eficaz al interior de la organización, responder a las seis preguntas clave que direccionan el qué hacer de la empresa; estos interrogantes se enmarcan en: ¿qué?, ¿para qué?; ¿cómo?, ¿con quién?; ¿cuándo? y ¿dónde?, al responder estas preguntas el equipo de trabajo podrá organizar sus procesos administrativos en coherencia al ciclo productivo de la organización.  

    p.mb-4(data-aos="fade") En la siguiente figura se visualizan los procesos administrativos y cómo las preguntas clave encajan en cada uno de ellos:

    .row.justify-content-center.align-items-center.mb-5
      .col-md-12.mb-3.mb-md-0 
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 2.</b> Procesos administrativos
      .col-md-5.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema1-infog1.svg', alt='Administración')
      .col-md-6(data-aos="fade-left")
        p La planeación, como se evidenció en la anterior figura, constituye, entonces, el primer paso para cualquier actividad sea empresarial o personal que realice un ser humano o equipo de trabajo, donde se logre determinar escenarios futuros, fijar las metas o resultados que se pueden alcanzar, y lograr minimizar riesgos y contrarrestarlos con estrategias efectivas y competitivas frente a los cambios del entorno de mercado.
        p Existen diversas técnicas para aprovechar los esfuerzos, conocimiento y experiencia del equipo de trabajo con miras a la elaboración del direccionamiento o planes estratégicos, como es reconocido en el mundo empresarial, a los productos que se generan durante esta primera etapa del proceso administrativo. Entre las más reconocidas se tienen:
    
    .row.justify-content-center.hover-columna.banner.mb-4(data-aos="fade-down")
      .col-md-12.mb-3.mb-md-0 
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 3.</b> Técnicas para el desarrollo de productos en equipo
      .col-md-10
        .row.justify-content-center.bg-gris.tarjeta.py-4
          .col-md-10
            figure
              img(src='@/assets/curso/tema1-infog2.svg', alt='Técnicas para el desarrollo de productos en equipo')

    .row.tema1-rectangulo.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-md-2.contenedor-imagenes
        img(src='@/assets/curso/tema1-icono.svg' alt='Imagen decorativa' style="width: 135px")
      .col-md-8.py-5.py-md-2
        .row
         .col-md-11
            p.px-md-3.mb-0 Un aspecto que resaltar para las empresas de economía solidaria es la aplicación precisamente de técnicas creativas que logren empatizar con el sentir de cada asociado y de este ejercicio se plasme un texto que dará vida al plan estratégico de la empresa solidaria. 

    p.mb-5(data-aos="fade") Aplicando entonces las técnicas, durante el proceso de planeación el equipo de trabajo prepara lo siguiente:      

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10  
        ImagenInfografica.tema-1.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema1-infog3.svg', alt='Productos del equipo')

          .tarjeta.bg-2.p-3(x="80.3%" y="5.3%" numero=" ")
            p.mb-0 En cuanto al primer entregable, <b style="font-size: 18px;">el modelo de negocio</b>, en el componente anterior se profundizó y detallaron cada uno de sus bloques y elementos claves para tener en cuenta en su elaboración.
          .tarjeta.bg-2.p-3(x="80.3%" y="18%" numero=" ")
            p.mb-0 Ahora veamos, <b style="font-size: 18px;">la filosofía y valores corporativos</b>, que, aunque están establecidos por la legislación (Ley 454 de 1998, marco conceptual de las organizaciones de economía solidaria), es importante que para la construcción se realice un ejercicio de creación colectiva que implique que todos los asociados generen sus aportes y opiniones de lo que quieren como empresa solidaria y su identidad corporativa.
          .tarjeta.bg-2.p-3(x="80.3%" y="31%" numero=" ")
            p.mb-0 Así mismo, la elaboración de <b style="font-size: 18px;">los objetivos estratégicos</b> implica un ejercicio de creación colectiva donde cada asociado acudiendo a su experiencia laboral, profesional o formación académica, genere sus aportes en la elaboración de estos objetivos por cada una de las áreas funcionales de la empresa solidaria; es importante referenciar que, como mínimo, una organización solidaria deberá contener para la gestión de su línea de negocio un área de operación o producción, de mercadeo y ventas, financiera y contable y administrativa.
          .tarjeta.bg-primario.p-3(x="80.3%" y="52%" numero=" ")
            p.mb-0 A partir de los objetivos estratégicos fijados para el área de ventas, mercadeo, financiera, contable, administrativa y de producción u operaciones se procede a elaborar las estrategias, junto con los programas que promuevan el desarrollo integral de los asociados y presupuestos.

    p.mb-5(data-aos="fade") De acuerdo con lo anterior, el siguiente esquema ayudará en la interpretación del proceso administrativo y posteriormente su construcción ajustada al modelo de negocio de la empresa solidaria, así:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10.mb-4
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 4.</b> Procesos administrativos de planeación
        p.mb-0 La planeación es un proceso fundamental para el éxito en el corto, mediano o largo plazo de las organizaciones, marcando la diferencia frente a sus competidores directos en cuanto a su posición competitiva en el mercado.
      .bg-gris2.p-2.p-md-4
        figure
          img(src='@/assets/curso/tema1-infog4.svg', alt='Proceso administrativo: planeación')

    p.mb-5(data-aos="fade") Como se observa en la figura se mencionan tres herramientas para la estructuración de este proceso administrativo, como son: lienzo Canvas, mapa estratégico y el plan de acción. Ahora, se explica cómo se pueden desarrollar.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-10
        TabsB.color-primario.tema-1
          .py-4.py-md-5.bg-gris3(titulo="Lienzo Canvas" :icono="require('@/assets/curso/tema1-tab1.svg')")
            .row.justify-content-center
              .col-md-10
                p.mb-5 El lienzo Canvas se compone de nueve bloques. Cada uno tiene preguntas orientadoras que ayudarán en su formulación. Haga clic en cada casilla.
                ImagenInfografica.color-secundario
                  template(v-slot:imagen)
                    figure
                      img(src='@/assets/curso/tema1-tab1-infog1.svg', alt='Lienzo Canvas')
                  .tarjeta.bg-2.p-3(x="2.8%" y="6%" numero="+")
                    p.text-center.mb-0 ¿Quiénes son nuestros socios clave?   
                  .tarjeta.bg-2.p-3(x="23%" y="6%" numero="+")
                    p.text-center.mb-0 ¿Qué actividades clave requieren nuestras propuestas de valor, canales de distribución, relaciones con clientes y fuentes de ingresos? 
                  .tarjeta.bg-2.p-3(x="43%" y="6%" numero="+")
                    p.text-center.mb-0 ¿Cuál es el valor que proporcionamos a nuestros clientes?
                  .tarjeta.bg-2.p-3(x="63%" y="6%" numero="+")
                    p.text-center.mb-0 ¿Qué tipo de relación esperan los diferentes segmentos de mercado?
                  .tarjeta.bg-2.p-3(x="82.5%" y="6%" numero="+")
                    p.text-center.mb-0 ¿Para quién creamos valor?
                  .tarjeta.bg-2.p-3(x="23%" y="38%" numero="+")
                    p.text-center.mb-0 ¿Qué recursos clave requiere la propuesta de valor, los canales de distribución, relaciones con clientes y fuentes de ingresos?
                  .tarjeta.bg-2.p-3(x="63%" y="38%" numero="+")
                    p.text-center.mb-0 ¿Cuáles canales prefiere nuestro segmento de mercado?
                  .tarjeta.bg-2.p-3(x="3%" y="66%" numero="+")
                    p.text-center.mb-0 ¿Cuáles son los costos más importantes inherentes a nuestro modelo de negocio?  
                  .tarjeta.bg-2.p-3(x="53%" y="66%" numero="+")
                    p.text-center.mb-0 ¿Por qué valor están dispuestos a pagar nuestros clientes?
          .py-4.py-md-5.bg-gris3(titulo="Mapa estratégico" :icono="require('@/assets/curso/tema1-tab2.svg')")
            .row.justify-content-center
              .col-md-10
                p.mb-4 Ahora, veamos una de las plantillas que se pueden utilizar para la elaboración del mapa estratégico: 
                figure
                  img(src='@/assets/curso/tema1-tab1-infog2.svg', alt='Mapa estratégico')
          .py-4.py-md-5.bg-gris3(titulo="Plan de acción" :icono="require('@/assets/curso/tema1-tab3.svg')")
            .row.justify-content-center
              .col-md-10
                p.mb-4 Este plan de acción deberá contener, para los programas y proyectos a desarrollar por la empresa de economía solidaria, las actividades, tiempos, responsables, presupuesto, metas e indicadores. Adicionalmente, el plan de acción se deberá controlar permanentemente, de tal manera que se logre el cumplimiento de los objetivos estratégicos trazados por la organización. A continuación, se presenta la estructura para el plan de acción: 
                h3.text-center PLAN DE ACCIÓN DE LA EMPRESA DE ECONOMÍA SOLIDARIA
                figure.mb-3
                  img(src='@/assets/curso/tema1-tab1-infog3.svg', alt='Plan de acción')
                p.mb-0 Con la estructuración del plan de acción se termina el proceso administrativo de planeación e inmediata se inicia con la operación de la empresa y empiezan a actuar los procesos de organización, integración, dirección y control.


    p.mb-5(data-aos="fade") Cada uno de estos procesos administrativos busca que la empresa, en el normal desarrollo de sus actividades, logre una gestión oportuna, eficaz y eficiente en todas sus operaciones. En la siguiente figura se observan las funciones principales para cada uno de los procesos mencionados y sus fines frente a la gestión empresarial.

    .titulo-sexto.color-acento-contenido(data-aos="fade-down")
      p.mb-0 <b>Figura 5.</b> Funciones principales del proceso administrativo, luego de la planeación

    .row.tema-1(data-aos="fade-down")
      .col-md-3.mb-4
        h4.text-center.tarjeta-titulo.mb-2.py-3 Organización
        img.mb-4(src='@/assets/curso/tema1-deco1.png', alt='Imagen decorativa')
        ul.lista-ul--color.color-primario.tema-1.px-md-4.px-2
          li.mb-0  
            i.fas.fa-play
            | División del trabajo.
          li.mb-0 
            i.fas.fa-play
            | Coordinación.  
        .tema-1.border-r10.bg-gris.py-4.px-3
          p.mb-0 Realizar la distribución adecuada de las funciones y pertinentes al perfil del trabajador.
      .col-md-3.mb-4
        h4.text-center.tarjeta-titulo.mb-2.py-3 Integración
        img.mb-4(src='@/assets/curso/tema1-deco2.png', alt='Imagen decorativa')
        ul.lista-ul--color.color-verde.tema-1.px-md-4.px-2
          li.mb-0  
            i.fas.fa-play
            | Selección. 
          li.mb-0 
            i.fas.fa-play
            | Determinación de requisitos.
          li.mb-0  
            i.fas.fa-play
            | Análisis de proveedores. 
          li.mb-0  
            i.fas.fa-play
            | Contratación.     
        .tema-1.border-r10.bg-gris.py-4.px-3
          p.mb-0 Conformar el equipo de trabajo de conformidad con la legislación laboral y la coordinación de las funciones de acuerdo con el organigrama establecido.
      .col-md-3.mb-4
        h4.text-center.tarjeta-titulo.mb-2.py-3 Dirección
        img.mb-4(src='@/assets/curso/tema1-deco3.png', alt='Imagen decorativa')
        ul.lista-ul--color.color-secundario.tema-1.px-md-4.px-2
          li.mb-0  
            i.fas.fa-play
            | Toma de decisiones. 
          li.mb-0 
            i.fas.fa-play
            | Motivación.
          li.mb-0  
            i.fas.fa-play
            | Liderazgo. 
          li.mb-0  
            i.fas.fa-play
            | Comunicación.   
        .tema-1.border-r10.bg-gris.py-4.px-3
          p.mb-0 Liderar los equipos de trabajo teniendo en cuenta las funciones, habilidades y destrezas de cada trabajador contratado.
      .col-md-3.mb-4
        h4.text-center.tarjeta-titulo.mb-2.py-3 Control
        img.mb-4(src='@/assets/curso/tema1-deco4.png', alt='Imagen decorativa')
        ul.lista-ul--color.color-acento-contenido.tema-1.px-md-4.px-2
          li.mb-0  
            i.fas.fa-play
            | Estándares. 
          li.mb-0 
            i.fas.fa-play
            | Medición.
          li.mb-0  
            i.fas.fa-play
            | Corrección.
          li.mb-0  
            i.fas.fa-play
            | Retroalimentación.  
        .tema-1.border-r10.bg-gris.py-4.px-3
          p.mb-0 Aplicar los indicadores de gestión a las metas y acciones fijadas en el plan de acción.           




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
