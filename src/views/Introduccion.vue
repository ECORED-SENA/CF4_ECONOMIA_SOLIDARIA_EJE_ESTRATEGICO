<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-primario
      .titulo-principal__numero.text-white
        span
          i.fas.fa-info
      h1 Introducción

    p(data-aos="fade") La gestión empresarial es entendida como las acciones diarias que desarrolla una empresa en su ciclo económico que van desde la fijación de la razón de ser de la organización, la compra de sus insumos, materias primas pasando por la gestión de ventas y atención al cliente, hasta llegar al registro de los hechos económicos; un aspecto importante para las organizaciones de economía solidaria es que amplía su mirada al aspecto social, siendo reconocida como aquella gestión socioempresarial asociativa. Además de la identidad corporativa enfocada en el desarrollo integral como un común denominador, con lo que los excedentes económicos se inviertan en sus planes estratégicos futuros en beneficio de los asociados. 

    p.mb-4(data-aos="fade") En el siguiente video se explica un poco más sobre este tipo de gestión y la importancia de su alineación con las actividades empresariales:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/xCZnyMxPScY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    p.mb-4(data-aos="fade") El modelo socioempresarial para la economía solidaria busca generar actividades económicas productivas y rentables, en donde sus excedentes sean invertidos en programas de bienestar integral para sus asociados. Es así como Cabrera y Rodríguez (2016), mencionan que:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-10.tarjeta.bg-secundario.py-3
        .row.justify-content-center
          .col-md-10.text-white
            p.mb-0.text-center El concepto de “modelo de gestión socioempresarial solidario” es la “supraestructura y el suprasistema, organizacional solidario” orientada por la filosofía de la economía solidaria (Ley 454, art. 1-20, 1998), el enfoque praxeológico (Juliao, 2014), el enfoque humanista (Corporación Universitaria Minuto de Dios, 2014; Max Neef, 1998; Sen, 2000) y el enfoque sistémico (De Gregori, 2014).

    p.mb-4(data-aos="fade") La siguiente figura presenta la arquitectura de este modelo socioempresarial en el que se dinamiza, combinan e integran el nivel estratégico, táctico y operativo:

    .row.justify-content-center.tarjeta.bg-1.mb-4(data-aos="fade-down")
      .col-md-10.py-4
        .row.align-items-center.mb-4
          .col-md-12.mb-3.mb-md-0
            .titulo-sexto.color-acento-contenido
              p.mb-0 <b>Figura 1.</b> Arquitectura del modelo
          .col-md-7           
            img(src='@/assets/curso/intro-img1.png' alt='Imagen decorativa')
          .col-md-5.tarjeta.bg-blanco.py-4
            p El modelo dinamiza, combina e integra los niveles estratégico, táctico y operativo y los sistemas social, económico, cultural, ambiental, político, normativo, administrativo y educativo. 
            p Esta última clase de sistemas está agrupada en los cinco ejes: 1) desarrollo humano y social solidario; 2) desarrollo cultural solidario; 3) desarrollo empresarial solidario; 4) desarrollo territorial solidario y 5) educación socioempresarial solidaria. 
        .wrap-player
          audio(controls='')(style= "width: 100%")
            source(src='../../public/downloads/Arquitectura.mp3' type='audio/mp3')
            |  Your browser does not support the audio tag

    p.mb-0(data-aos="fade") La gestión socioempresarial de las empresas de la economía solidaria representa un modelo de gestión capaz de generar excedentes económicos, ser sostenibles, sustentables en beneficio del desarrollo integral de sus asociados como actor principal de los fines solidarios implícitos en la legislación (Ley 454 de 1998, Marco Conceptual de las Organizaciones de Economía Solidaria).

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
