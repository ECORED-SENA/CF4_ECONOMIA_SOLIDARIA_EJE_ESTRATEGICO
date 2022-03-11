<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-primario
      .titulo-principal__numero.text-white
        span 5
      h1 Estados financieros básicos

    p(data-aos="fade") Según Cardozo (2015), el objetivo de los estados financieros es proporcionar información, sobre la situación financiera, el rendimiento y los flujos de efectivo de la entidad, que sea útil para la toma de decisiones económicas acordes con los principios e identidad corporativa de la empresa de economía solidaria.
    
    p.mb-5(data-aos="fade") Los estados de la situación financiera constituyen una representación entre los activos, los pasivos y el patrimonio de una entidad, (Cardozo, 2015), lo que se observa a partir de los datos exactos que genera la contabilidad el estado financiero de la empresa, reflejando la capacidad de liquidez y de endeudamiento frente a terceros y sus asociados o fundadores, tal como se representa en el siguiente recurso.

    .row.tema5-flip.mb-4
      .col-md-4.mb-4
        .tarjeta.tarjeta-flip
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema5-flip1.svg')})`}")
            .tarjeta-flip__contenido.bg-acento-botones.text-white.p-3
              p <b style="font-size: 18px;">Un activo</b> son todos aquellos bienes de la empresa y que generan recursos económicos futuros representados en beneficios para la empresa. <b style="font-size: 18px;">Un pasivo</b> son todas aquellas obligaciones que contrae el ente económico con terceros sean proveedores, el estado y particulares. Un patrimonio refleja los aportes de los asociados y fundadores, así como los excedentes que generan las actividades meritorias económicas.  
              p.mb-0 De tal modo, que con las cuentas que integran el activo, pasivo y patrimonio se prepara el <b style="font-size: 18px;">estado de la situación financiera.</b> 
      .col-md-4.mb-4
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema5-flip2.svg')})`}")
            .tarjeta-flip__contenido.bg-secundario.text-white.p-3
              p De otra parte, las cuentas de ingresos y gastos representan el rendimiento financiero de la empresa solidaria y que se refleja en lo que se conoce como el <b style="font-size: 18px;">estado de resultados.</b>  
              p.mb-0 Los <b style="font-size: 18px;">ingresos</b> son los incrementos en los beneficios económicos producidos por los activos en un periodo de tiempo determinado. <b style="font-size: 18px;">Los gastos</b> son todas aquellas erogaciones generadas por la empresa para su sustento o funcionamiento, estos se discriminan en gastos administrativos, de ventas y financieros.
      .col-md-4.mb-4
        .tarjeta.tarjeta-flip
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema5-flip3.svg')})`}")
            .tarjeta-flip__contenido.bg-acento-contenido.text-white.p-3
              p Otro estado financiero básico es <b style="font-size: 18px;">el flujo de caja</b> que determina las <b style="font-size: 18px;">entradas y salidas</b> de efectivo en el normal desarrollo de las actividades meritorias económicas que se ocasionan en un periodo de tiempo determinado.

    p(data-aos="fade") Otro aspecto importante es cuando se elaboran los estados financieros; por lo general, las empresas tienen determinado un periodo gravable que inicia en el 01 de enero y termina el 31 de diciembre de cada año. 

    p.mb-4(data-aos="fade") En cuanto a la identificación de los estados financieros, se puede mencionar que tanto los informes financieros como las notas aclaratorias, deberán contener como mínimo:

    .row.justify-content-center.mb-4
      .col-md-8.bg-3.border-r10.p-4
        ul.lista-ul--color.color-verde2.px-md-0.px-2.mb-0
          li.mb-3 
            i.fas.fa-check
            | El nombre de la entidad que informa.
          li.mb-3 
            i.fas.fa-check
            | Aclarar en los informes financieros, si son individuales o pertenecen a un grupo de entidade
          li.mb-3 
            i.fas.fa-check
            | La fecha final de cierre o corte contable de presentación de los informes financieros.
          li.mb-3
            i.fas.fa-check
            | La moneda de presentación de los estados financieros.
          li.mb-0
            i.fas.fa-check
            | La fórmula aplicada para el redondeo de las cifras presentadas.    

    p.mb-5(data-aos="fade") De igual forma, los elementos a tener en cuenta para la elaboración de los estados financieros básicos son los siguientes:


</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
    indicadorTarjetaFlip: true,
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
