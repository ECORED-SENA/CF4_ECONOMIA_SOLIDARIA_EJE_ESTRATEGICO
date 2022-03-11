<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-primario
      .titulo-principal__numero.text-white
        span 3
      h1 Contabilización de hechos económicos
    
    p.mb-4(data-aos="fade") Un hecho económico es toda aquella transacción u operación sea de compra, venta o financiera que realice una empresa con ocasión al normal desarrollo de sus actividades económicas. El registro de estos hechos económicos se realiza con la contabilidad donde a partir de un conjunto de cuentas contables de cuatro dígitos que se identifican como activos, pasivos, patrimonio, ingresos, costos y gastos; las empresas reconocen, miden y registran estos hechos económicos.

    .row.justify-content-end.hover-columna.banner.mb-5
      .col-md-8
        img(src='@/assets/curso/tema3-banner.png' alt='Imagen decorativa')
      .col-md-6.tarjeta.bg-acento-botones.recuadros-bottom-right.float-left
        .row
          .col-md-11.p-4
            p.mb-0.text-white Para una adecuada contabilización de los hechos económicos es indispensable contratar un profesional del área de la contaduría pública, responsable del manejo contable y financiero de los recursos de la empresa y del reporte de estas operaciones ante las entidades de control y vigilancia, que, para el caso de las empresas del sector solidario, se encuentran, la Superintendencia de la economía solidaria, la superintendencia financiera y la Dirección de Impuestos y Aduanas Nacionales – DIAN.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-5(data-aos="fade-right")
        img(src='@/assets/curso/tema3-img1.svg' alt='Partida doble')
      .col-md-5(data-aos="fade-left")
        p De otra parte, para la contabilización de un hecho económico existe un principio contable que se conoce como partida doble y significa que se debe registrar la misma cantidad $$, tanto al débito como al crédito y que por lo menos se deben utilizar dos cuentas contables de cuatro dígitos; a continuación se presenta un esquema del mismo.
        p Además, en la contabilización de un hecho económico hay otro aspecto a tener presente y es la naturaleza de las cuentas y de su saldo según su clase. Cada clase, sea activo, pasivo o patrimonio, ingresos o costos, tiene su forma o movimiento contable para registrar una cifra, tanto al crédito como al débito; esta naturaleza permite conservar el principio contable de partida doble, tal como se aprecia a continuación.  

    .row.align-items-center
      h3.text-center.mb-5 Naturaleza de las cuentas
      .col-md-4.border-r10.bg-2.py-3
        h2.text-center CUENTAS
        img(src='@/assets/curso/tema3-img2.png' alt='Cuentas')
      .col-md-8


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
