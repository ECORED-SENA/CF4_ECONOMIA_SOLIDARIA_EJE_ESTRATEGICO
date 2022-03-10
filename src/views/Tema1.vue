<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-primario
      .titulo-principal__numero.text-white
        span 1
      h1 Planes estratégicos

    p.mb-5(data-aos="fade") Para una correcta estructuración del plan estratégico, hay que abordar inicialmente el proceso administrativo que es una metodología que permite al administrador, gerente, ejecutivo, empresario, o cualquier otra persona, manejar eficazmente una organización. 

    .row.justify-content-center.hover-columna.banner.mb-5
      .col-md-10.mb-4
        img(src='@/assets/curso/tema1-banner.png' alt='Imagen decorativa')
      .col-md-6.tarjeta.bg-acento-botones.recuadros-top-left.float-left
        .row.justify-content-end
          .col-md-10.p-4.py-md-3
            p.mb-0.text-white <b style="font-size: 18px;">Es importante</b>, para establecer un proceso eficaz al interior de la organización, responder a las seis preguntas clave que direccionan el qué hacer de la empresa; estos interrogantes se enmarcan en: ¿qué?, ¿para qué?; ¿cómo?, ¿con quién?; ¿cuándo? y ¿dónde?, al responder estas preguntas el equipo de trabajo podrá organizar sus procesos administrativos en coherencia al ciclo productivo de la organización.  

    p.mb-4(data-aos="fade") En la siguiente figura se visualizan los procesos administrativos y cómo las preguntas clave encajan en cada uno de ellos:

    .row.justify-content-center.align-items-center.mb-5
      .col-md-6.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema1-infog1.svg', alt='Administración')
      .col-md-4(data-aos="fade-left")
        p La planeación, como se evidenció en la anterior figura, constituye, entonces, el primer paso para cualquier actividad sea empresarial o personal que realice un ser humano o equipo de trabajo, donde se logre determinar escenarios futuros, fijar las metas o resultados que se pueden alcanzar, y lograr minimizar riesgos y contrarrestarlos con estrategias efectivas y competitivas frente a los cambios del entorno de mercado.
        p Existen diversas técnicas para aprovechar los esfuerzos, conocimiento y experiencia del equipo de trabajo con miras a la elaboración del direccionamiento o planes estratégicos, como es reconocido en el mundo empresarial, a los productos que se generan durante esta primera etapa del proceso administrativo. Entre las más reconocidas se tienen:
    
    .row.justify-content-center.hover-columna.banner.mb-4(data-aos="fade-down")
      .col-md-10
        h3.text-center.mb-5 Técnicas para el desarrollo de productos en equipo
        figure
          img(src='@/assets/curso/tema1-infog2.svg', alt='Técnicas para el desarrollo de productos en equipo')

    .row.tema1-rectangulo.justify-content-center.align-items-center.mb-4(data-aos="fade-down")
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
              img(src='@/assets/curso/tema1-infog3.svg', alt='Texto que describa la imagen')

          .tarjeta.bg-2.p-3(x="40.8%" y="9.3%" numero=" ")
            p.text-white.mb-0 En cuanto al primer entregable, <b style="font-size: 18px;">el modelo de negocio</b>, en el componente anterior se profundizó y detallaron cada uno de sus bloques y elementos claves para tener en cuenta en su elaboración.
          .tarjeta.bg-2.p-3(x="40.8%" y="16.7%" numero=" ")
            p.text-white.mb-0 Ahora veamos, <b style="font-size: 18px;">la filosofía y valores corporativos</b>, que, aunque están establecidos por la legislación (Ley 454 de 1998, marco conceptual de las organizaciones de economía solidaria), es importante que para la construcción se realice un ejercicio de creación colectiva que implique que todos los asociados generen sus aportes y opiniones de lo que quieren como empresa solidaria y su identidad corporativa.
          .tarjeta.bg-2.p-3(x="40.8%" y="24%" numero=" ")
            p.text-white.mb-0 Así mismo, la elaboración de <b style="font-size: 18px;">los objetivos estratégicos</b> implica un ejercicio de creación colectiva donde cada asociado acudiendo a su experiencia laboral, profesional o formación académica, genere sus aportes en la elaboración de estos objetivos por cada una de las áreas funcionales de la empresa solidaria; es importante referenciar que, como mínimo, una organización solidaria deberá contener para la gestión de su línea de negocio un área de operación o producción, de mercadeo y ventas, financiera y contable y administrativa.
          .tarjeta.bg-primario.p-3(x="69.7%" y="73%" numero=" ")
            p.text-white.mb-0 A partir de los objetivos estratégicos fijados para el área de ventas, mercadeo, financiera, contable, administrativa y de producción u operaciones se procede a elaborar las estrategias, junto con los programas que promuevan el desarrollo integral de los asociados y presupuestos.


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
