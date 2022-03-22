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
              p Un <b style="font-size: 18px;">activo</b> son todos aquellos bienes de la empresa y que generan recursos económicos futuros representados en beneficios para la empresa. Un <b style="font-size: 18px;">pasivo</b> son todas aquellas obligaciones que contrae el ente económico con terceros sean proveedores, el estado y particulares. Un <b style="font-size: 18px;">patrimonio</b> refleja los aportes de los asociados y fundadores, así como los excedentes que generan las actividades meritorias económicas.  
              p.mb-0 De tal modo, que con las cuentas que integran el activo, pasivo y patrimonio se prepara el <b style="font-size: 18px;">estado de la situación financiera.</b> 
      .col-md-4.mb-4
        .tarjeta.tarjeta-flip(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema5-flip2.svg')})`}")
            .tarjeta-flip__contenido.bg-secundario.text-white.p-3
              p De otra parte, las cuentas de ingresos y gastos representan el rendimiento financiero de la empresa solidaria y que se refleja en lo que se conoce como el <b style="font-size: 18px;">estado de resultados.</b>  
              p.mb-0 Los <b style="font-size: 18px;">ingresos</b> son los incrementos en los beneficios económicos producidos por los activos en un periodo de tiempo determinado. Los <b style="font-size: 18px;">gastos</b> son todas aquellas erogaciones generadas por la empresa para su sustento o funcionamiento, estos se discriminan en gastos administrativos, de ventas y financieros.
      .col-md-4.mb-4
        .tarjeta.tarjeta-flip
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema5-flip3.svg')})`}")
            .tarjeta-flip__contenido.bg-acento-contenido.text-white.p-3
              p Otro estado financiero básico es <b style="font-size: 18px;">el flujo de caja</b> que determina <b style="font-size: 18px;">las entradas</b> y <b style="font-size: 18px;">salidas de efectivo</b> en el normal desarrollo de las actividades meritorias económicas que se ocasionan en un periodo de tiempo determinado.

    p(data-aos="fade") Otro aspecto importante es cuando se elaboran <b>los estados financieros</b>; por lo general, las empresas tienen determinado un periodo gravable que inicia en el 01 de enero y termina el 31 de diciembre de cada año. 

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

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-10
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 11.</b> Tiempos de los estados financieros
        TabsA.color-secundario.tema-5
          .tarjeta.tema4-tarjeta1.bg-blanco.p-4(titulo="Fecha de corte")
            h4 Fecha de corte
            p Se entiende como aquella en la cual la información contable es tomada de los libros de contabilidad.  Para el caso de organizaciones solidarias el ejercicio contable aplica igual que para otro tipo de empresas con ánimo de lucro.
          .tarjeta.tema4-tarjeta1.bg-blanco.p-4(titulo="Periodo contable")
            h4 Periodo contable
            p Es un tiempo de referencia que busca emitir información de la situación financiera y el resultado de las operaciones, donde se identifica claramente la fecha de inicio y cierre del periodo contable (Cardozo, 2015).
            p Los estados financieros se deben emitir, al menos, una vez al año.
          .tarjeta.tema4-tarjeta1.bg-blanco.p-4(titulo="Cierre de ejercicio contable y publicación anual")
            h4 Cierre de ejercicio contable y publicación anual
            p Se procede a comparar los saldos de cada una de las cuentas contables de cada año, respecto a la situación financiera de la empresa y los saldos que están acumulados en el periodo contable. Las organizaciones solidarias supervisadas publican el estado de la situación financiera y el estado de resultados en un medio masivo de circulación nacional.

    p.mb-5(data-aos="fade") Para Cardozo (2015) es importante que los estados financieros reflejen la gestión del gobierno corporativo y que estén sustentados en la revelación de los informes financieros. Para las cooperativas de ahorro y crédito estas gestiones corporativas deben realizarse sobre los siguientes temas.

    .row.mb-5(data-aos="fade-down")
      .col-md-12.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 12.</b> Temas para las gestiones corporativas
      SlyderA.tema-5
        .row.justify-content-center
          .col-md-11
            .tarjeta--container.row.mb-4
              .col-md-4.tarjeta.color-secundario.p-5
                .row.justify-content-center.mb-4
                  .col-7
                    figure
                      img(src='@/assets/curso/tema5-slide-tarje1.svg', alt='Consejo de administración')
                h4.text-normal.mb-1 Consejo de administración
                p.text-normal Informar si estos órganos o instancias están al tanto de la responsabilidad que implica el manejo de los diferentes riesgos y están debidamente enterados de la gestión. 
              .col-md-4.tarjeta.color-acento-botones.p-5
                .row.justify-content-center.mb-4
                  .col-7
                    figure
                      img(src='@/assets/curso/tema5-slide-tarje2.svg', alt='Políticas de división de funciones')
                h4.mb-1 Políticas de división de funciones
                p Informar si han sido impartida por el consejo de administración o junta directiva y si estas abarcan todos los ámbitos de operación del negocio.
              .col-md-4.tarjeta.color-primario.p-5
                .row.justify-content-center.mb-4
                  .col-7
                    figure
                      img(src='@/assets/curso/tema5-slide-tarje3.svg', alt='Reportes al consejo de administración')
                h4.mb-1 Reportes al consejo de administración
                p Informar si los diferentes estamentos le están reportando las distintas posiciones de riesgo. 
        .row.justify-content-center
          .col-md-11
            .tarjeta--container.row.justify-content-center
              .col-md-4.tarjeta.bg-acento-contenido1.p-5
                .row.justify-content-center.mb-4
                  .col-7
                    figure
                      img(src='@/assets/curso/tema5-slide-tarje4.svg', alt='Infraestructura tecnológica')
                h4.text-normal.mb-1 Infraestructura tecnológica
                p.text-normal Revelar si las áreas cuentan con la infraestructura y planes de contingencia que puedan aportar la información y los resultados necesarios. 
              .col-md-4.tarjeta.bg-4.p-5
                .row.justify-content-center.mb-4
                  .col-7
                    figure
                      img(src='@/assets/curso/tema5-slide-tarje5.svg', alt='Estructura organizacional')
                h4.mb-1 Estructura organizacional
                p Revelar si existen independencia entre las áreas y a la vez si son dependientes desde el punto de vista funcional.


    p.mb-5(data-aos="fade") Finalmente, otro aspecto a tener en cuenta son las notas de revelación que contienen la información adicional y explicativa de los estados financieros (estado de la situación financiera, estado de resultados y flujo de caja), reconocidos como los estados financieros básicos. 

    .row.justify-content-center.mb-5
      .col-md-11
        .row.hover-columna.banner
          .col-md-8
            img(src='@/assets/curso/tema5-banner.png' alt='Imagen decorativa')
          .col-md-6.tarjeta.bg-acento-botones.float-right
            .row.justify-content-center
              .col-md-11.p-4
                p.mb-0.text-white Las notas de revelación junto con el manual de políticas contables proporcionan una descripción explicativa de cada una de las cuentas contables y los movimientos que está presente durante el ejercicio contable. 

    p.mb-5(data-aos="fade") Las notas de revelación o aclaratorias representan el estado actual de cada una de las cuentas de balance y nominales proporcionando información fidedigna y veraz de cada informe financiero. Estas notas siempre deben acompañar o complementar los estados financieros básicos de la organización solidaria. Por lo general, contienen la siguiente información.

    .row(data-aos="fade-down")
      h3.text-center.mb-5 Aspectos de las notas de revelación
      figure
        img(src='@/assets/curso/tema5-infog1.svg', alt='Administración')




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
