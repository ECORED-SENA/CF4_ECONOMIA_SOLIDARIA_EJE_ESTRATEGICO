<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-primario
      .titulo-principal__numero.text-white
        span 2
      h1 Fondos monetarios y políticas de inversión de excedentes
    
    p(data-aos="fade") Para abordar los fondos monetarios establecidos por la norma para las empresas de la economía solidaria, primero se abordan conceptos clave como los activos de un balance o estado de situación financiera de las entidades del sector solidario, los cuales están conformados por las cuentas que representan los bienes, derechos y pertenencias, tangibles e intangibles, con los que se espera obtener en el futuro beneficios económicos (Cardozo, 2015).

    p.mb-5(data-aos="fade") A continuación, se explican estos conceptos clave.


    ImagenInfograficaB.color-primario.tema-2-modal.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema2-infog1.svg', alt='Conceptos clave')

      div.row.justify-content-center(x="64%" y="22.5%")
        SlyderE(indicadores="centro")
          .row.align-items-center
            .col-md-8
              h3.mb-2 Activo
              p Para el caso, de las organizaciones de economía solidaria, las cuentas del activo más importantes que se manejan precisamente por el desarrollo de las actividades económicas y por la naturaleza de la organización, son las siguientes:
              ul.lista-ul.px-3
                li.mb-0
                  i.fas.fa-circle
                  | Efectivo y equivalentes a efectivo.
                li.mb-0
                  i.fas.fa-circle
                  | Inversiones.
                li.mb-0
                  i.fas.fa-circle
                  | Cartera de crédito. 
                li.mb-0
                  i.fas.fa-circle
                  | Inventarios.
                li.mb-0
                  i.fas.fa-circle
                  | Cuentas por cobrar.
                li.mb-0
                  i.fas.fa-circle
                  | Activos no corrientes mantenidos para la venta.
                li.mb-0
                  i.fas.fa-circle
                  | Activos materiales.
                li.mb-0
                  i.fas.fa-circle
                  | Otros activos.           
              p Los dos primeros dígitos indican la clase de la cuenta y el grupo, para este caso, todos los grupos inician con 1 porque pertenecen a la clase del activo y el segundo dígito hace referencia al grupo.     
            .col-md-3
              img.px-md-3(src='@/assets/curso/tema2-modal-img1-1.svg', alt='Imagen decorativa')
          .row.align-items-center
            .col-md-11
              h3.mb-2 Activo
              p El grupo 11 que pertenece a la clase del activo y del grupo efectivo y equivalentes a efectivo, corresponde al efectivo considerado con un conjunto de activos financieros en los que se registran los recursos de liquidez inmediata con los que cuenta la entidad del sector solidario y que también pueden utilizarse para fines generales o específicos (Cardozo, 2015).
              p Así mismo, para dar claridad a la estructura contable en este grupo del efectivo y equivalentes a efectivo para el catálogo de cuentas se describe a continuación el grupo 11, así: 
            .col-md-7
              p Efectivo y equivalentes a efectivo (disponible).
              ul.lista-ul.px-3
                li.mb-0
                  i.fas.fa-circle
                  | Caja.
                li.mb-0
                  i.fas.fa-circle
                  | Bancos y otras entidades.
                li.mb-0
                  i.fas.fa-circle
                  | Remesas en tránsito.
                li.mb-0
                  i.fas.fa-circle
                  | Fondos específicos.
                li.mb-0
                  i.fas.fa-circle
                  | Efectivo restringido.       
            .col-md-4
              img(src='@/assets/curso/tema2-modal-img1-2.svg', alt='Imagen decorativa')       
          .row.align-items-center
            .col-md-7
              h3.mb-2 Activo
              p En este grupo de cuentas se maneja el efectivo disponible de las organizaciones de economía solidaria, así mismo, hay otro grupo de cuentas que se identifican con el código 13 inversiones, es importante resaltar que la Superintendencia de la Economía Solidaria emite en su circular básica contable los procedimientos para el registro y manejo de las inversiones y da unas recomendaciones como, por ejemplo, que se debe realizar un análisis sobre el riesgo de invertir el dinero de los asociados en oportunidades de negocio de inversiones de capital. 
              p Es importante aclarar que existen grupos de cuentas tanto para el activo, pasivo, patrimonio y las cuentas de resultados, necesarias para el registro contable de los hechos económicos de la empresa de economía solidaria, así como, que cada una de ellas debe cumplir los procedimientos establecidos para su medición descritos en la Ley 1314 de 2009 y el Decreto 3022 de 2013 relacionados con las NIIF para pyme aplicables al sector solidario.
            .col-md-4
              img(src='@/assets/curso/tema2-modal-img1-3.svg', alt='Imagen decorativa')    

      div.row.justify-content-center(x="64%" y="36.5%")
        .col-md-11
          h3.mb-2 Pasivo
          p Un pasivo son las obligaciones presentes en la entidad surgidas a raíz de sucesos pasados, a cuyo vencimiento, y para pagarlas, la entidad espera desprenderse de recursos que conllevan beneficios económicos. En este grupo de cuentas se registran los rubros que representan obligaciones contraídas por la entidad en el desarrollo del giro ordinario de su actividad, sea financiera, comercio, producción o de servicios (Cardozo, 2015).  
        .col-md-7
          p Entre los grupos de cuentas principales para la clase de pasivo, se encuentran:
          ul.lista-ul.px-3
            li.mb-0
              i.fas.fa-circle
              | Instrumentos financieros a costo amortizado.
            li.mb-0
              i.fas.fa-circle
              | Instrumentos financieros a valor razonable.
            li.mb-0 
              i.fas.fa-circle
              | Aportaciones y participaciones.
            li.mb-0 
              i.fas.fa-circle
              | Cuentas por pagar.
            li.mb-0 
              i.fas.fa-circle
              | Fondos sociales y mutuales.
            li.mb-0 
              i.fas.fa-circle
              | Obligaciones laborales por beneficios a empleados.
            li.mb-0 
              i.fas.fa-circle
              | Provisiones.
            li 
              i.fas.fa-circle
              | Otros pasivos.              
        .col-md-4
          img(src='@/assets/curso/tema2-modal-img2.svg', alt='Imagen decorativa')

      div.row.justify-content-center(x="64%" y="49.5%")
        .col-md-11
          h3.mb-2 Patrimonio
          p Es la participación residual en los activos de una entidad una vez deducidos todos sus pasivos. El patrimonio de las entidades del sector solidario está constituido por las reservas, los fondos de reservas, fondos de destinación específica y el resultado acumulado que son de carácter permanente, pero algunas de estas son aplicables de acuerdo con su destino (Cardozo, 2015), tales como: 
        .col-md-7
          ul.lista-ul.px-3
            li.mb-0
              i.fas.fa-circle
              | Reserva para protección de aportes sociales.
            li.mb-0
              i.fas.fa-circle
              | Fondo de amortización de aportes.
          p Entre los grupos de cuentas se encuentran: 
          ul.lista-ul.px-3
            li.mb-0
              i.fas.fa-circle
              | Capital social.
            li.mb-0
              i.fas.fa-circle
              | Reservas.
            li.mb-0
              i.fas.fa-circle
              | Fondos de reserva de destinación específica.    
        .col-md-4
          img(src='@/assets/curso/tema2-modal-img3.svg', alt='Imagen decorativa')

      div.row.justify-content-center(x="64%" y="63%")
        .col-md-7
          h3.mb-2 Ingresos
          p Son los incrementos en los beneficios económicos producidos a lo largo del periodo sobre el que se informa, en forma de entradas o incrementos el valor de los activos, o la disminución de las obligaciones, que dan como resultado aumentos del patrimonio y no están relacionados con los aportes de los socios (Cardozo, 2015).
          p El grupo principal para el registro de los ingresos provenientes del desarrollo de las actividades económicas es: 
          ul.lista-ul.px-3
            li.mb-0
              i.fas.fa-circle
              | Ingresos de actividades ordinarias generales.
        .col-md-4
          img.px-md-3(src='@/assets/curso/tema2-modal-img4.svg', alt='Imagen decorativa')

      div.row.justify-content-center(x="64%" y="77%")
        .col-md-7
          h3.mb-2 Gastos y costos
          p Son todos aquellos pagos realizados por la empresa de economía solidaria y que se generan en el normal desarrollo de las actividades productivas. Estos gastos se agrupan en administrativos, de ventas y otros gastos. 
          p Con base en Cardozo (2015), los principales grupos de cuentas son: 
          ul.lista-ul.px-3
            li.mb-0
              i.fas.fa-circle
              | Gastos de operación.
            li.mb-0
              i.fas.fa-circle
              | Costos de ventas y de prestación de servicios.
            li.mb-0
              i.fas.fa-circle
              | Costos de producción.    
        .col-md-4
          img.px-md-3(src='@/assets/curso/tema2-modal-img5.svg', alt='Imagen decorativa')



    .row.tema1-rectangulo.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-md-2.contenedor-imagenes
        img(src='@/assets/curso/tema2-icono.svg' alt='Imagen decorativa' style="width: 135px")
      .col-md-8.py-5.py-md-2
        .row
         .col-md-11
            p.px-md-3.mb-0 Es de aclarar que el manejo contable de las empresas de economía solidaria está sujeto a la legislación cooperativa vigente, sus decretos y a las Normas Internacionales de Información Financiera; así como al catálogo de cuentas que utilizan las empresas del sector solidario.

    p(data-aos="fade") Con la Ley 1314 de 2019 se regulan los principios y normas de contabilidad e información financiera y de aseguramiento de información aceptados en Colombia, así mismo, se determina que con observancia de los principios de equidad, reciprocidad y conveniencia nacional, las personas jurídicas y naturales obligadas a llevar la contabilidad realicen la convergencia de las normas contables con estándares internacionales que permita la facilidad y conveniencia de hacer negocios a escala global, sin que existan barreras contables y financieras que impidan la transacción. 

    p.mb-5(data-aos="fade") Entre los objetivos de la implementación de las NIIF (Normas Internacionales de Información Financiera) regidos para el sector solidario se encuentran los siguientes:

    .row.mb-5(data-aos="fade-down")
      .col-md-12.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 6.</b> Objetivos de las NIFF
      figure
        img(src='@/assets/curso/tema2-infog2.svg', alt='Objetivos de las NIFF')

    p(data-aos="fade") En consecuencia, para una adecuada gestión contable y financiera de la empresa de economía solidaria se requiere una asesoría permanente del profesional de la contaduría pública que garantice el cumplimiento oportuno de la normativa contable establecida en la Ley 1314 de 2009. De otra parte, hay que mencionar que la Supersolidaria emitió la Circular Básica Contable y Financiera Externa 22 de 2020, que entró en vigencia con la publicación en el Diario Oficial 51.570 del 27 de enero de 2021. 

    p(data-aos="fade") En esta circular, existen algunas consideraciones en su capítulo IV para el manejo, registro y medición de los fondos sociales y fondos mutuales que se refieren a los recursos con una destinación específica y son la base fundamental de las cooperativas, fondos de empleados y asociaciones mutuales (Supersolidaria, s. f.).

    p.mb-5(data-aos="fade") Estos fondos se dividen en tres grupos, tal como se presenta a continuación:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-10.mb-md-5
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 7.</b> Tipos de fondos
        figure
          img(src='@/assets/curso/tema2-infog3.svg', alt='Tipos de fondos')

    .row.justify-content-center.mb-5
      h3.mb-5 Fondo social pasivo
      .col-md-10
        .row.d-flex
          .col-md-5.bg-secundario.text-white.img-center.p-4.mb-4.mb-md-0(data-aos="fade-right")
            img.mb-2.centrar-img(src='@/assets/curso/tema2-ico1.svg', alt='Icono', style="width: 40px")
            h3.text-center Fondos sociales, según la Ley 79 de 1988
          .col-md-7.bg-5.p-4(data-aos="fade-left")
            p.mb-0 Los fondos sociales pasivos hacen referencia exclusiva a los fondos de solidaridad y de educación, cuyas entradas económicas se originan de los excedentes del ejercicio contable, es decir de las utilidades que genera el desarrollo de la actividad económica pero que, en empresas de economía solidaria, sin ánimo de lucro, se denominan excedentes, y estos excedentes económicos en cuanto a su destino y uso están determinados por la ley.

    p.mb-5(data-aos="fade") La ley especifica el uso porcentual de los excedentes económicos de la empresa solidaria, que se verán más adelante y sus políticas para el destino, manejo y uso

    h3(data-aos="fade") Fondo de educación

    p(data-aos="fade") Es creado para que los recursos económicos colocados en este, su destino y uso sean para el fortalecimiento del principio cooperativo número siete, que refiere en la Ley 454 de 1998, así: formación e información para sus miembros, de manera permanente, oportuna y progresiva.

    p.mb-5(data-aos="fade") Se hace énfasis en la educación en economía solidaria en temas como la educación cooperativa, las responsabilidades y naturaleza de cada una de las formas jurídicas, la contabilidad, la gestión administrativa y estratégica; así como, la formación relacionada con la asistencia técnica, de investigación y de promoción del cooperativismo de las empresas de economía solidaria.

    .row.justify-content-center.mb-5
      .col-md-12
        .row.hover-columna.banner
          .col-md-8
            img(src='@/assets/curso/tema2-banner.png' alt='Imagen decorativa')
          .col-md-6.tarjeta.bg-acento-botones.float-right.recuadros-top-left-mini 
            .row.justify-content-center
              .col-md-11.p-4
                p.mb-0.text-white.pt-4 Los fondos de educación también podrán ser creados por las asociaciones mutuales; así mismo, los fondos de empleados podrán un fondo de educación, de acuerdo con el numeral 2 del artículo 19 del Decreto Ley 1481 de 1989, que menciona la obligatoriedad de adelantar programas y actividades relacionadas con la participación democrática y el desempeño idóneo en la gestión empresarial. (Supersolidaria, 2021).

    p(data-aos="fade") Los excedentes económicos de la empresa solidaria se podrán destinar al fondo de educación, cumpliendo los procedimientos técnicos y normativos contables, así como las disposiciones realizadas por la asamblea general reflejadas en el plan de acción preparado por la empresa solidaria.

    p.mb-5(data-aos="fade") La circular básica contable y financiera establece los pagos que se pueden registrar con cargo al fondo de educación. A continuación, se exponen cada uno de ellos.

    TabsA.color-secundario.mb-5
      .row.justify-content-center.align-items-center.tarjeta.bg-3.p-4(titulo="1. Formación académica")
        .col-md-7
          h4 1. Formación académica
          p Formación académica relacionada con cursos presenciales o a distancia, conferencias, mesas redondas, paneles, seminarios, talleres y demás eventos colectivos que tengan por objetivo predominante la formación o capacitación teórica y práctica de los asociados que asistan a dichos eventos.
        .col-md-4
          img.p-md-3(src='@/assets/curso/tema2-tab1.svg' alt='Imagen decorativa')
      .row.justify-content-around.align-items-center.tarjeta.bg-3.p-4(titulo="2. Información")
        .col-md-7
          h4 2. Información 
          p Elaboración o compra de folletos, cartillas, libros, boletines, carteleras y demás publicaciones impresas que tengan por objetivo la formación, información y capacitación de sus lectores.
        .col-md-3
          img.p-md-3(src='@/assets/curso/tema2-tab2.svg' alt='Imagen decorativa')  
      .row.justify-content-around.align-items-center.tarjeta.bg-3.p-4(titulo="3. Capacitación")
        .col-md-7
          h4 3. Capacitación 
          p Elaboración o compra de medios audiovisuales, cuyos contenidos tengan por objetivo la formación y capacitación de sus usuarios y la creación de páginas web destinadas a la capacitación sobre el tema de educación.
        .col-md-3
          img.p-md-3(src='@/assets/curso/tema2-tab3.svg' alt='Imagen decorativa')
      .row.justify-content-around.align-items-center.tarjeta.bg-3.p-4(titulo="4. Investigación")
        .col-md-7
          h4 4. Investigación 
          p Investigaciones efectuadas con medios técnicos y científicos y personal idóneo que permitan el desarrollo de los fines educativos estatutarios consagrados por la organización solidaria o que contribuyan a su actividad económica, siempre que se ajusten a los principios y filosofía del sector solidario.
        .col-md-3
          img.p-md-3(src='@/assets/curso/tema2-tab4.svg' alt='Imagen decorativa')
      .row.justify-content-center.align-items-center.tarjeta.bg-3.p-4(titulo="5. Bienes muebles")
        .col-md-7
          h4 5. Bienes muebles 
          p Adquisición de bienes muebles que tengan por objeto principal, dotar a las organizaciones solidarias de los medios o instalaciones adecuadas para adelantar las actividades de educación. 
          p En este caso, el presupuesto debe diferenciar claramente las partidas que implican gasto, de las que constituyen inversión, existiendo un sano equilibrio entre las mismas, de acuerdo con las necesidades particulares de cada organización y el monto de los recursos destinados a la educación.
        .col-md-4
          img(src='@/assets/curso/tema2-tab5.svg' alt='Imagen decorativa')
      .row.justify-content-center.align-items-center.tarjeta.bg-3.p-4(titulo="6. Gastos y costos")
        .col-md-7
          h4 6. Gastos y costos 
          p Se pueden sufragar aquellos costos y gastos indirectos que surgen, en virtud de la realización de los eventos educativos, como: gastos de viaje, hospedaje, conferencistas, refrigerios, materiales de apoyo consumibles, transportes terrestres o aéreos, alquiler de auditorios y su logística.
        .col-md-4
          img(src='@/assets/curso/tema2-tab6.svg' alt='Imagen decorativa')                

    .row.tema1-rectangulo.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-md-2.contenedor-imagenes
        img(src='@/assets/curso/tema2-icono2.svg' alt='Imagen decorativa' style="width: 135px")
      .col-md-8.py-5.py-md-2
        .row
         .col-md-11
            p.px-md-3.mb-0 En conclusión, aquellas actividades directas e indirectas relacionadas con el objetivo del fondo de educación se causarán en las respectivas cuentas contables a cargo de este rubro, estas operaciones deben estar autorizadas por la asamblea general o en su defecto el consejo de administración.

    h3(data-aos="fade") Fondo de solidaridad

    p(data-aos="fade") Es un fondo destinado a atender eventos de solidaridad que sean considerados en el estatuto de la empresa de economía solidaria. El fin de este fondo es la ayuda mutua entre los asociados en caso de calamidad doméstica o cualquier otro evento que le suceda al asociado y que requiera de la ayuda de los miembros de la empresa de economía solidaria. 

    p(data-aos="fade") Así mismo, los fondos de empleados y las asociaciones mutuales podrán crear también los fondos de solidaridad, de acuerdo con el artículo 19 del Decreto Ley 1481 de 1989 y cumpliendo los objetivos fijados en los estatutos de la organización de economía solidaria.

    p.mb-5(data-aos="fade") La circular básica contable y financiera establece los pagos que se pueden registrar con cargo al fondo de solidaridad. En la siguiente figura se exponen cada uno de ellos.

    .row.align-items-center.mb-5
      .col-md-12.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 8.</b> Pagos para el fondo de solidaridad
      .col-md-5(data-aos="fade-right")
        figure
          img(src='@/assets/curso/tema2-infog4.svg', alt='Pagos para el fondo de solidaridad')
      .col-md-7(data-aos="fade-left")
        .row.align-items-center.mb-3
          .col-md-1
            h2.mb-0.text-center(style="color: #00A3BE; font-size: 45px; font-weight: bold;") A
          .col-md-10  
            p.mb-0 Auxilio a los asociados de la cooperativa en caso de calamidad doméstica.
        .row.align-items-center.mb-3
          .col-md-1
            h2.mb-0.text-center(style="color: #32D9CB; font-size: 45px; font-weight: bold;") B
          .col-md-10  
            p.mb-0 Auxilio para servicios médicos, hospitalarios y quirúrgicos al asociado o sus familiares en el parentesco señalado en los estatutos o reglamentos de la organización solidaria.
        .row.align-items-center.mb-3
          .col-md-1
            h2.mb-0.text-center(style="color: #12263F; font-size: 45px; font-weight: bold;") C
          .col-md-10  
            p.mb-0 Adquisición de mausoleos, osarios o lotes en parques cementerios, destinados a facilitarles a los asociados o trabajadores mediante diversas modalidades.
        .row.align-items-center.mb-3
          .col-md-1
            h2.mb-0.text-center(style="color: #727997; font-size: 45px; font-weight: bold;") D
          .col-md-10  
            p.mb-0 Pago total o parcial de planes de protección de servicios médicos prepagados, servicios funerarios y de exequias o servicios médicos y hospitalarios, así como demás protecciones similares.
        .row.align-items-center.mb-3
          .col-md-1
            h2.mb-0.text-center(style="color: #678589; font-size: 45px; font-weight: bold;") E
          .col-md-10  
            p.mb-0 Contribuciones y obras para lograr un desarrollo sostenible del medioambiente y de la comunidad, de conformidad con las políticas generales aprobadas por el órgano competente de la organización solidaria.
        .row.align-items-center
          .col-md-1
            h2.mb-0.text-center(style="color: #F37F4C; font-size: 45px; font-weight: bold;") F
          .col-md-10  
            p.mb-0 Donaciones esporádicas y ocasionales frente a calamidades de sus trabajadores o a hechos que generen catástrofes o perjuicios colectivos en el entorno de la organización solidaria.            

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-10.tarjeta.bg-acento-botones.p-4.px-md-5
        p.text-white.mb-0 Todos los pagos realizados a cargo del fondo de solidaridad deberán cumplir con los procedimientos contables exigidos para el registro de los hechos económicos, así como sus respectivos soportes que respalden la transacción económica. Las actividades del fondo de solidaridad deberán ser autorizadas y reglamentadas por el consejo de administración de la empresa de economía solidaria. 

    p(data-aos="fade") En síntesis, se puede decir que, aunque la reglamentación para las empresas del sector solidario determina los fondos sociales pasivos clasificados en los fondos de educación y de solidaridad, el máximo órgano de administración de la empresa solidaria puede crear otros fondos, siempre que conservan los principios y fines solidarios reglamentados por la legislación.

    p.mb-5(data-aos="fade") Adicional a ello, hay que considerar las políticas para el manejo de excedentes económicos, así: 

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-12.mb-3.mb-md-0
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Tabla 1.</b> Manejo de excedentes
      .col-md-10  
        figure
          img(src='@/assets/curso/tema2-infog5.svg', alt='Manejo de excedentes')

    p.mb-5(data-aos="fade") De tal forma, que el uso y destino de los excedentes económicos debe cumplir estrictamente lo establecido en la legislación, dejando abierta la posibilidad de crear nuevos fondos para servicios en beneficio del bien común o para el disfrute de la seguridad social; esta decisión se realiza de manera voluntaria por cada asociado y debe estar aprobada por la asamblea general como máximo órgano de administración de la empresa de economía solidaria. Estas políticas se deben cumplir tal y como se observó en la tabla anterior.


    h4.mb-4(data-aos="fade") Reservas y otros fondos con fines determinados

    p.mb-5(data-aos="fade") Las reservas y otros fondos pueden ser creados por las cooperativas y precooperativas amparados en la Ley 79 de 1988 como resultado de los excedentes económicos de su ejercicio contable. A continuación, se presenta una breve explicación de estos.

    .row.justify-content-center.mb-5.tema-2(data-aos="fade-down")
      .col-md-10  
        PasosA.color-secundario(tipo="n")
          .row.align-items-center.justify-content-around
            .col-md-2.mb-4.mb-md-0
              img(src='@/assets/curso/tema2-paso1.svg', alt='Icono decorativo')
            .col-md-9
              p.mb-0 Las reservas son de carácter patrimonial, al contrario de los fondos que pueden ser de tipo patrimonial o pasivos de carácter agotable. Tanto los fondos como las reservas deben tener un reglamento donde se especifique el destino, manejo y uso de los excedentes; estos, deben estar autorizados por la asamblea general. 
          .row.align-items-center.justify-content-around
            .col-md-9.mb-4.mb-md-0
              p.mb-0 En cuanto a los procedimientos contables estos deben cumplir con las políticas y normativa establecidos por la Ley 1314 de 2009, referentes al marco normativo aplicable a MiPymes del grupo 3 relacionadas con las Normas Internacionales de Información Financiera - NIIF. De tal forma que la empresa solidaria, a partir de las necesidades y expectativas de sus asociados, está autorizada para crear, manejar e invertir sus excedentes económicos en los fondos sociales pasivos, siempre y cuando se cumplan con la legislación y normativa vigente aplicable para las empresas del sector solidario.               
            .col-md-2
              img(src='@/assets/curso/tema2-paso2.svg', alt='Icono decorativo')
          .row.align-items-center.justify-content-around
            .col-md-2.mb-4.mb-md-0
              img(src='@/assets/curso/tema2-paso3.svg', alt='Icono decorativo')
            .col-md-9
              p.mb-0 Finalmente, la gestión administrativa de la empresa solidaria, el representante legal, junto con el consejo de administración y junta de vigilancia son las encargadas de que las actas de la asamblea, donde se crean y aprueban los fondos monetarios y políticas, para la inversión de los excedentes, sean archivadas y custodiadas en el archivo de gestión y estén disponibles cuando la Superintendencia de Economía Solidaria, así lo exija. 






</template>

<script>
export default {
  name: 'Tema2',
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
