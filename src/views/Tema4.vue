<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-primario
      .titulo-principal__numero.text-white
        span 4
      h1 Responsabilidades tributarias

    p.mb-5(data-aos="fade") Antes de iniciar esta temática, se sugiere leer lo que dice la DIAN respecto a las responsabilidades tributarias, así:

    .row.justify-content-center.mb-5
      .col-md-10(data-aos="fade-down")
        .row.align-items-center.tarjeta.bg-secundario.tema-4.p-3.px-md-4
            .col.mb-3.mb-sm-0
              h4.text-white.mb-0 Entidades sin ánimo de lucro
              p.text-white.mb-0 Lea atentamente su concepto y los requisitos que deben tener para su denominación en su página web. Este recurso se encuentra también en el material complementario.
            .col-sm-auto
              a.boton.color-primario(href="https://www.dian.gov.co/impuestos/sociedades/ESAL/Paginas/default.aspx#:~:text=Las" target="_blank")
                i.fas.fa-book-reader 
                span Leer
                

    p.mb-4(data-aos="fade") La DIAN determina los beneficios por pertenecer al Régimen Tributario Especial – RTE, entre los que se encuentran: 

    .row.justify-content-center.mb-4
      .col-md-10
        ul.lista-ul--color.color-verde2.px-md-0.px-2.mb-0
          li 
            i.fas.fa-check
            | Tarifa del 20 % del impuesto de renta y complementario sobre el beneficio neto o excedente.
          li.mb-0 
            i.fas.fa-check
            | Adicionalmente, se puede tener carácter de exento cuando se destine directa o indirectamente a programas que desarrollen el objeto social y la actividad meritoria de la entidad, en el siguiente año gravable, luego de obtener el excedente.

    p.mb-5(data-aos="fade") A continuación, se presentan los pasos a tener en cuenta para pertenecer al Régimen Tributario Especial (RTE).

    .row.justify-content-center.mb-5
      .col-md-10
        #MapaGroup01(data-aos="fade-down")
          .row.justify-content-center.tema-4
            .col-md-11
              .row.justify-content-center.align-items-end
                .col-md
                  .tarjeta.btn-grupo(data-bs-toggle='collapse' data-bs-target='.multi-collapse1' aria-expanded='true' aria-controls='.multi-collapse1')
                    img.ChangeSRC01.centrar-img(src='@/assets/curso/tema4-boton1.svg', alt='botón 1' style="width: 160px;")
                  img.mx-auto.mb-0.multi-collapse1.collapse.show(src='@/assets/curso/tema4-ind1.svg', alt='indicador 1' data-bs-parent='#MapaGroup01' style="width: 4px;")
                .col-md.hover-columna
                  .tarjeta.btn-grupo(data-bs-toggle='collapse' data-bs-target='.multi-collapse2' aria-expanded='false' aria-controls='.multi-collapse2')(@mouseover="mostrarIndicador = false")
                    .indicador--click(v-if="mostrarIndicador")
                    img.ChangeSRC02.centrar-img(src='@/assets/curso/tema4-boton2.svg', alt='botón 2' style="width: 160px;")
                  img.mx-auto.mb-0.multi-collapse2.collapse(src='@/assets/curso/tema4-ind2.svg', alt='indicador 1' data-bs-parent='#MapaGroup01' style="width: 4px;")
                .col-md
                  .tarjeta.btn-grupo(data-bs-toggle='collapse' data-bs-target='.multi-collapse3' aria-expanded='false' aria-controls='.multi-collapse2')
                    img.ChangeSRC03.centrar-img(src='@/assets/curso/tema4-boton3.svg', alt='botón 3' style="width: 160px;")
                  img.mx-auto.mb-0.multi-collapse3.collapse(src='@/assets/curso/tema4-ind3.svg', alt='indicador 1' data-bs-parent='#MapaGroup01' style="width: 4px;")

          .row.justify-content-center.tema4-tarjeta1.bg-gris4.py-4.multi-collapse1.collapse.show(data-bs-parent='#MapaGroup01')
            .col-md-10.mb-4          
              p El primer paso para pertenecer al Régimen Tributario Especial es solicitar a la Dirección de Impuestos y Aduanas Nacionales, su Calificación, Readmisión o Actualización, dentro de los plazos establecidos por esta. Esta Calificación, corresponde a: 
            .col-md-8.mb-4
              p Mediante este trámite las ESAL podrán solicitar su calificación al Régimen Tributario Especial y de esta forma acceder a los beneficios tributarios que este ofrece. En caso de que sean excluidas del RTE por estar incursa en alguna de las causales de exclusión relacionadas en el artículo 364-3 del Estatuto Tributario, podrá presentar nuevamente solicitud de calificación al RTE cuando haya pasado un (1) año de su exclusión (DIAN, s. f.).
            .col-md-10
              p Con esta calificación pertenecerá al RTE y gozará de los beneficios tributarios como, por ejemplo, la tarifa especial del impuesto de renta y complementarios. 

          .row.justify-content-center.tema4-tarjeta2.bg-gris4.py-4.multi-collapse2.collapse(data-bs-parent='#MapaGroup01')
            .col-md-10.mb-4          
              p Un segundo paso es la readmisión, de acuerdo con el artículo 19-4 del Estatuto Tributario, las cooperativas, sus asociaciones, uniones, ligas centrales, organismos de grado superior de carácter financiero, las asociaciones mutualistas, instituciones auxiliares del cooperativismo, confederaciones cooperativas, previstas en la legislación cooperativa, vigilados por alguna superintendencia u organismo de control pertenecen al Régimen Tributario Especial - RTE y, por lo tanto, no requieren calificarse en el mencionado régimen, salvo en los casos que sean reclasificadas al régimen ordinario, por no presentar anualmente el proceso de actualización del registro web, o porque sea excluida por encontrarse incursa en alguna de las causales de exclusión relacionadas en el parágrafo 3 del artículo 364-3 del Estatuto Tributario. 
              p.mb-0 En ese caso, podrá optar por pertenecer nuevamente al RTE, siempre y cuando, hayan transcurrido 3 años de su exclusión.

          .row.justify-content-center.tema4-tarjeta3.bg-gris4.py-4.multi-collapse3.collapse(data-bs-parent='#MapaGroup01')
            .col-md-10.mb-4          
              p Un último paso es la actualización que, de acuerdo con lo señalado en el artículo 364-5 del E. T., las entidades sin ánimo de lucro y del sector cooperativo clasificados en el RTE deberán actualizar anualmente la información en el registro web, en los primeros 3 meses de cada año, iniciando a partir del año 2019.
              p Es importante precisar que el concepto de actualización comprende dos aspectos, a saber:
              ul.lista-ul--color.color-verde2.px-md-3.px-2.mb-0
                li 
                  i.fas.fa-check
                  | La actualización de la información en el registro web, cuya periodicidad es anual.
                li.mb-0 
                  i.fas.fa-check
                  | La actualización de la calidad contribuyente perteneciente al Régimen Tributario Especial en el RUT a que se refiere el artículo 356-3 del E. T., adicionado por el artículo 149 de la Ley 1819 de 2016, la cual se hace con la presentación de la declaración de renta como contribuyente del RTE.

    .row.justify-content-center.mb-5
      .col-md-10(data-aos="fade-down")
        .row.align-items-center.tarjeta.bg-secundario.tema-4.p-3.px-md-4
            .col.mb-3.mb-sm-0
              h4.text-white.mb-0 Actualización
              p.text-white.mb-0 Las entidades sin ánimo de lucro y del sector cooperativo clasificadas en el RTE deberán actualizar anualmente la información en el Registro Web. Lea atentamente en qué consiste de acuerdo con lo estipulado en el Decreto Único Reglamentario en Materia Tributaria - DUR No. 1625 de 2016. Este recurso se encuentra también en el material complementario.
            .col-sm-auto
              a.boton.color-primario(href="https://www.dian.gov.co/impuestos/sociedades/ESAL/Actualizaci%C3%B3n/Paginas/default.aspx" target="_blank")
                i.fas.fa-book-reader 
                span Leer

    p.mb-4(data-aos="fade") Continuando con la información prevista en el material complementario, los reportes a presentar por las empresas del sector cooperativo ante la Dirección de Impuestos y Aduanas Nacionales - DIAN, se encuentran establecidos por la entidad en DIAN y estos son la memoria económica y el registro de contratos.

    figure.mb-4(data-aos="fade-down")
      img(src='@/assets/curso/tema4-infog.svg', alt='Proceso administrativo: planeación')

    p.mb-5(data-aos="fade") En complemento a lo establecido por la DIAN para los contribuyentes que pertenecen al Régimen Tributario Especial - RTE, la entidad identifica la relación de las actividades meritorias-económicas que gozan del beneficio más representativo, que es la tasa del impuesto de renta y complementarios en 20 %; de modo tal, que este listado orienta las empresas de economía solidaria a emprender sus modelos de negocios en el desarrollo de estas actividades meritorias-económicas y gocen de los beneficios tributarios.

    .row.justify-content-center.mb-5
      .col-md-10(data-aos="fade-down")
        .row.align-items-center.tarjeta.bg-secundario.tema-4.p-3.px-md-4
            .col.mb-3.mb-sm-0
              h4.text-white.mb-0 Actividades económicas
              p.text-white.mb-0 Conozca el listado de las actividades económicas que gozan beneficios tributarios. Este recurso se encuentra también en el material complementario.
            .col-sm-auto
              a.boton.color-primario(href="https://www.dian.gov.co/Paginas/PageNotFoundError.aspx?requestUrl=https://www.dian.gov.co/impuestos/sociedades/ESAL/Relaci%C3%B3n%20de%20actividades%20meritorias%20y%20actividades%20econ%C3%B3micas/Paginas/default.aspx" target="_blank")
                i.fas.fa-book-reader 
                span Leer



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
