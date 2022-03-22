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
      .col-md-6.tarjeta.bg-acento-botones.recuadros-bottom-right.float-left-center
        .row
          .col-md-11.p-4
            p.mb-0.text-white Para una adecuada contabilización de los hechos económicos es indispensable contratar un profesional del área de la contaduría pública, responsable del manejo contable y financiero de los recursos de la empresa y del reporte de estas operaciones ante las entidades de control y vigilancia, que, para el caso de las empresas del sector solidario, se encuentran, la Superintendencia de la economía solidaria, la superintendencia financiera y la Dirección de Impuestos y Aduanas Nacionales – DIAN.

    .row.justify-content-center.align-items-center.mb-5
      .col-md-5(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 9.</b> Partida doble
        img(src='@/assets/curso/tema3-img1.svg' alt='Partida doble')
      .col-md-5(data-aos="fade-left")
        p De otra parte, para la contabilización de un hecho económico existe un principio contable que se conoce como partida doble y significa que se debe registrar la misma cantidad $$, tanto al débito como al crédito y que por lo menos se deben utilizar dos cuentas contables de cuatro dígitos; a continuación se presenta un esquema del mismo.
        p Además, en la contabilización de un hecho económico hay otro aspecto a tener presente y es la naturaleza de las cuentas y de su saldo según su clase. Cada clase, sea activo, pasivo o patrimonio, ingresos o costos, tiene su forma o movimiento contable para registrar una cifra, tanto al crédito como al débito; esta naturaleza permite conservar el principio contable de partida doble, tal como se aprecia a continuación.  

    .row.d-flex.tema-3.mb-5
      .col-md-12.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 10.</b> Naturaleza de las cuentas
      .col-md-4.img-center.border-r10.bg-2.py-3.mb-4.mb-md-0
        h2.text-center CUENTAS
        img(src='@/assets/curso/tema3-img2.png' alt='Cuentas')
      .col-md-8
        .tabla-b.color-secundario.text-center.mb-3
          .tabla-b__header
            h4.mb-0 1. ACTIVO
          table
            tr
              th DEBE
              th HABER
              th SALDO NATURALEZA
            tr.bg-blanco
              td Aumentan +
              td Disminuyen -
              td Débito
        .tabla-b.color-secundario.text-center.mb-3
          .tabla-b__header
            h4.mb-0 2. PASIVO
          table
            tr
              th DEBE
              th HABER
              th SALDO NATURALEZA
            tr.bg-blanco
              td Disminuyen -
              td Aumentan +
              td Crédito     
        .tabla-b.color-secundario.text-center.mb-3
          .tabla-b__header
            h4.mb-0 3. PATRIMONIO
          table
            tr
              th DEBE
              th HABER
              th SALDO NATURALEZA
            tr.bg-blanco
              td Disminuyen -
              td Aumentan +
              td Crédito  
        .tabla-b.color-secundario.text-center.mb-3
          .tabla-b__header
            h4.mb-0 4. INGRESOS
          table
            tr
              th DEBE
              th HABER
              th SALDO NATURALEZA
            tr.bg-blanco
              td Disminuyen -
              td Aumentan +
              td Crédito        
        .tabla-b.color-secundario.text-center.mb-3
          .tabla-b__header
            h4.mb-0 5. GASTOS Y COSTOS
          table
            tr
              th DEBE
              th HABER
              th SALDO NATURALEZA
            tr.bg-blanco
              td Aumentan +
              td Disminuyen -
              td Débito

    p.mb-5(data-aos="fade") Ahora, para cerrar esta temática, se presentan algunos ejemplos comunes de Cardozo (2015), para la contabilización de los hechos económicos en una empresa del sector solidario:

    ImagenInfograficaB.color-primario.tema-3-modal.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema3-infog1.svg', alt='Ejemplo hechos económicos')

      div(x="29%" y="8.5%")
        h3.mb-2 Registros de aportes
        p Una de las primeras transacciones, <b style="font-size: 18px;">es el registro de los aportes</b> realizados por cada asociado; para lo cual en los estatutos de la entidad se deben mencionar el aporte mínimo irreducible y el valor total de los aportes sociales. 
        p Estos aportes mínimos irreducibles y el total de aportes sociales pueden ser incrementados, previa autorización de la asamblea y esta decisión obedecerá a la proporción de crecimiento económico que tenga la empresa.
        p Según el artículo 52 de la Ley 79 de 1988, las entidades podrán establecer en sus estatutos la amortización parcial o total de los aportes sociales hechos por los asociados, mediante la constitución de un fondo especial denominado Fondo para amortización de aportes, cuyos recursos provendrán del remanente de los excedentes. La amortización se hará en igualdad de condiciones para los asociados (Cardozo, 2015).
        p De tal manera, que bajo este artículo que refiere la legislación el registro contable de la constitución del fondo por mandato de la asamblea, es:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Constitución del fondo
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Patrimonio-Excedentes del ejercicio
                    td.text-center $5.500.000
                    td  
                  tr
                    td Patrimonio – Fondo para amortizar aportes
                    td  
                    td.text-center $5.500.000  
        p <b style="font-size: 18px;">Hecho económico:</b> constitución del fondo con los excedentes del ejercicio contable. Entiéndase por ejercicio contable las fechas entre el 01 de enero y el 31 de diciembre de cada año.  Como se observa en la cuenta de excedentes del ejercicio se registra la partida $$ al débito y disminuye el patrimonio y se aumenta la cuenta Fondo para amortizar aportes al crédito, es decir que aumenta. 

      div(x="21%" y="29.5%")
        h3.mb-2 Fondo específico
        p Otro ejemplo, es la creación de un fondo específico como el fondo de mercadeo de productos, cuya finalidad es adquirir un capital de trabajo para el mercadeo de productos. Es de aclarar, que este tipo de fondos de destinación específica, no podrán ser cambiado de acuerdo con los reglamentos de la entidad del sector solidario.
        p Una cooperativa bananera recibe de una empresa de jugos naturales, el valor de $8.000.000 como aporte de patrocinio para el crecimiento económico de la cooperativa. El registro contable quedaría: 
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Patrimonio – Fondo mercadeo de productos
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Activo – Fondo específico
                    td.text-center $8.000.000
                    td  
                  tr
                    td Patrimonio – Fondo mercadeo de productos
                    td  
                    td.text-center $8.000.000  
        p <b style="font-size: 18px;">Hecho económico:</b> registro de recursos para un fondo específico. En donde la cuenta del activo se registra al débito y aumenta y la cuenta del patrimonio se registra al crédito y aumenta, la cuenta fondo mercadeo de productos, cumpliéndose el principio de partida doble. 

      div(x="14%" y="50%")
        h3.mb-2 Adquisición
        p En este ejemplo, veamos la adquisición de un bien para uso del fondo de educación. Una empresa del sector solidario adquiere un televisor por valor de $3.300.000, paga con cheque. Los recursos provienen del fondo social de educación. El registro contable quedaría así:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Registro de adquisición del bien
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Pasivo – Fondo social de educación
                    td.text-center $3.300.000
                    td  
                  tr
                    td Bancos y otras entidades
                    td  
                    td.text-center $3.300.000
        p <b style="font-size: 18px;">Hecho económico:</b> registro de adquisición del bien. Para este registro contable intervienen dos cuentas, una del pasivo con su partida en el débito, disminuyendo y la otra cuenta es del activo, bancos y su partida disminuye en el crédito. 

      div(x="21%" y="70%")
        h3.mb-2 Registro de ingresos
        p El registro de los ingresos, es otra de las operaciones comunes para las empresas, en entidades de economía solidaria, veamos el siguiente ejemplo: 
        p La empresa solidaria, obtiene ingresos por valor de $5.200.000, pagados por el cliente en efectivo, el registro contable simple es:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Registro de ingresos por ventas
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Efectivo – Caja
                    td.text-center $6.188.000
                    td  
                  tr
                    td Ingresos – Ventas al por mayor y al por menor
                    td  
                    td.text-center $5.200.000
                  tr
                    td Pasivo - IVA generado por ventas 19%
                    td  
                    td.text-center $988.000 
        p <b style="font-size: 18px;">Hecho económico:</b> para el registro de ingresos, interviene la cuenta del activo, y su registro aumenta en el debe y las cuentas del ingreso y del pasivo; sus registros van en el crédito, aumentando. Este asiento contable se conoce como compuesto, porque como observa hay tres cuentas contables participando en el registro. 


      div(x="29%" y="91%")
        h3.mb-2 Registro contable
        p El registro contable de los servicios públicos para la empresa solidaria se causa a una cuenta de gasto. Ejemplo: la empresa solidaria paga el servicio de energía eléctrica por valor de $250.000 en efectivo, contablemente se registra:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Registro de gastos administrativos
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Gastos – Servicios
                    td.text-center $250.000
                    td  
                  tr
                    td Efectivo - Caja
                    td  
                    td.text-center $250.000
        p <b style="font-size: 18px;">Hecho económico:</b> registro de gastos administrativos. Este es un asiento simple, con dos únicas cuentas. Una cuenta del gasto, aumentando en el débito y otra cuenta del activo, disminuyendo en el crédito. 


      div(x="71%" y="9.5%")
        h3.mb-2 Registros de restitución
        p Los excedentes económicos provenientes de los resultados del ejercicio contable, se reflejan en las cuentas contables del patrimonio, así como su uso y destinación. Ejemplo: Una entidad solidaria refleja en sus estados financieros excedentes por $32.000.000 en total, de estos excedentes se trasladan $7.000.000, para restituir la reserva de protección de aportes que se utilizó en el año inmediatamente anterior y que fue autorizada por la asamblea general de asociados, así:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Registro de restitución de la reserva
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Patrimonio – Excedentes del ejercicio
                    td.text-center $7.000.000
                    td  
                  tr
                    td Patrimonio – Reserva para protección de aportes
                    td  
                    td.text-center $7.000.000 
        p <b style="font-size: 18px;">Hecho económico:</b> registro de restitución de la reserva. Intervienen dos cuentas contables del patrimonio, la cuenta de excedentes, disminuye al debe y la cuenta de reserva aumenta en el crédito.

      div(x="81%" y="29.5%")
        h3.mb-2 CDT
        p Otra transacción común entre las organizaciones de economía solidaria, son las relacionadas al registro de inversiones. Ejemplo: una empresa de economía solidaria, adquiere un título CDT por la suma de $30.000.000 y pactado a seis meses con una tasa del 6% anual por mes vencido. Los registros contables quedarían:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Adquisición del CDT
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Inversiones a costo amortizado instrumentos de deuda. Título CDT
                    td.text-center $30.000.000
                    td  
                  tr
                    td Bancos y otras entidades – bancos comerciales
                    td  
                    td.text-center $30.000.000  
        p A continuación, se registran los intereses o valoración del portafolio de inversiones, correspondientes a los intereses del primer mes. En el siguiente mes el proceso se realiza de la misma manera y así sucesivamente.
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Causación o valoración del CDT
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Inversiones a costo amortizado instrumento de deuda. Título CDT - intereses
                    td.text-center $150.000
                    td  
                  tr
                    td Ingresos, valoración de inversiones a costo amortizado. Instrumentos de deuda.
                    td  
                    td.text-center $150.000                
        p <b style="font-size: 18px;">Hecho económico:</b> durante esta transacción existen dos momentos, en donde, el primero es la adquisición del CDT con una cuenta del activo en el debe y otra cuenta también del activo que disminuye en el crédito. Así mismo, la causación o valoración del CDT, interviene una cuenta del activo que aumenta en el debe y una cuenta del ingreso que aumenta en el crédito. 

      div(x="86.5%" y="50%")
        h3.mb-2 Servicios
        p Una cooperativa firma un contrato para la prestación de servicios funerarios a los asociados por valor de $6.000.000 mensuales. Los cuales se descontarán de la nómina de los asociados. El registro de la causación del contrato se realiza:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Registro contrato de servicios funerarios
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Convenio por cobrar – servicios funerarios
                    td.text-center $6.000.000
                    td  
                  tr
                    td Proveedores - Nacionales
                    td  
                    td.text-center $6.000.000
        p Finalizado el mes, la cooperativa gira el cheque para el pago de la póliza mensual y el registro contable, queda así: 
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Cancelación del proveedor
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Proveedores - nacionales
                    td.text-center $6.000.000
                    td  
                  tr
                    td Bancos y otras entidades
                    td  
                    td.text-center $6.000.000        
        p <b style="font-size: 18px;">Hecho económico:</b> se registran dos momentos, en el registro del contrato, interviene una cuenta del activo que aumenta al debe y una cuenta del pasivo, proveedores que aumenta al crédito. En la cancelación al proveedor, tenemos, la cuenta del pasivo, que disminuye al debe y la cuenta del activo, que disminuye al crédito.

      div(x="81%" y="70%")
        h3.mb-2 Asesoría
        p Una empresa del sector solidario paga con cheque a un abogado por concepto de asesoría jurídica especializada, la suma de $700.000. La razón de la contratación del abogado se debe a un crédito comercial de un asociado moroso de la empresa solidaria. El registro contable es:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Pago por cuenta del asociado
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Pagos por cuenta de asociados – comercial
                    td.text-center $700.000
                    td  
                  tr
                    td Bancos y otras entidades
                    td  
                    td.text-center $700.000 
        p <b style="font-size: 18px;">Hecho económico:</b>  en este registro contable, interviene una cuenta de gastos, que aumenta al débito y una cuenta del activo que disminuye al crédito. 

      div(x="73%" y="91%")
        h3.mb-2 Préstamo
        p Una empresa del sector solidario gestiona un crédito bancario por valor de $100.000.000, con el objetivo de invertirlos en la ampliación de la infraestructura física. El registro del capital préstamo por el banco es:
        .row.justify-content-center.mb-3
          .col-md-10
            .tabla-a
              table
                thead.bg-blanco
                  tr
                    th 
                      h4.mb-0 Registro del capital recibido
                    th.col-2 
                      h4.mb-0 Débito
                    th.col-3 
                      h4.mb-0 Crédito
                tbody.bg-blanco
                  tr
                    td Bancos y otras entidades 
                    td.text-center $100.000.000
                    td  
                  tr
                    td Pasivo – créditos de bancos y otras obligaciones financieras
                    td  
                    td.text-center $100.000.000
        p <b style="font-size: 18px;">Hecho económico:</b> interviene una cuenta del activo, que aumenta al debe y una cuenta del pasivo que disminuye al crédito.
 


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
