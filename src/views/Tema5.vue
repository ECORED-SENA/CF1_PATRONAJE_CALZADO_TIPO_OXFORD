<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span 5
        h1 Fichas técnicas de diseño


      .row
        .col-lg-8
          .bg-color-23.px-4.py-5(data-aos="fade-left").mb-4
            p.mb-0 La ficha técnica de diseño es un documento esencial que reúne la información detallada de un producto en desarrollo. Su objetivo es asegurar que, desde el diseño hasta la producción final, se sigan parámetros estandarizados que garanticen la calidad del artículo. Este instrumento es ampliamente utilizado en sectores como el calzado, la marroquinería, el textil y la manufactura en general.
          
        .col-lg-4.d-none.d-sm-block
          figure
            img(src="@/assets/curso/tema5/1.png", data-aos="zoom-in").mb-4.mb-lg-0
      
  
      Separador
      <!-- BLOQUE 1 -->
      #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 5.1 Características de la ficha técnica de diseño
  
      p.mb-5.ajustes___movil-1 Una ficha técnica bien elaborada debe contener diversos elementos que permitan comprender todas las características del producto. A continuación, se describen los apartados que la componen:
  

      .row.align-items-center.mb-5
        .col-lg-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/tema5/2.png", alt="" style="width: 505px").m-auto
        .col-lg
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
            .row(titulo="Información general").ajuste-cajaAcordion
              p Incluye los datos básicos que identifican el producto y su registro documental:
              <ul class="fa-ul">
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Nombre del producto.</li>
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Código o referencia.</li>
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Fecha de creación y versión.</li>
              </ul>
            .row(titulo="Descripción del diseño").ajuste-cajaAcordion
              p Define visual y dimensionalmente el producto para su correcta interpretación por parte del equipo técnico: 
              <ul class="fa-ul">
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Boceto o imagen del producto.</li>
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Especificaciones de forma y dimensiones.</li>
              </ul>     
            .row(titulo="Materiales y componentes").ajuste-cajaAcordion
              p Detalla los elementos físicos que conforman el producto, tanto estructurales como decorativos:
              <ul class="fa-ul">
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Tipo de materiales utilizados (cuero, tela, sintético, etc.).</li>
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Herrajes, cremalleras, botones u otros accesorios.</li>
                <li><span class="fa-li"><i class="fas fa-cut"></i></span>Colores y texturas.</li>
              </ul>

      .row.align-items-center

        .col-lg
          AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")

              .row(titulo="Técnicas de fabricación").ajuste-cajaAcordion
                p Define los procesos que se deben seguir para ensamblar las partes del producto:
                <ul class="fa-ul">
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Tipo de costuras y uniones.</li>
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Métodos de ensamblaje (pegado, cosido, termosellado, etc.).</li>
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Tipo de curtido en caso de cuero.</li>
                </ul>
              .row(titulo="Medidas y tallas").ajuste-cajaAcordion
                p Especifica las dimensiones del producto y, si corresponde, la tabla de tallas según su aplicación:
                <ul class="fa-ul">
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Dimensiones en centímetros o pulgadas.</li>
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Tabla de tallas en caso de calzado o prendas.</li>
                </ul>
              .row(titulo="Indicaciones de uso y cuidado").ajuste-cajaAcordion
                p Proporciona instrucciones necesarias para preservar el producto y prevenir daños:
                <ul class="fa-ul">
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Recomendaciones para su conservación.</li>
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Restricciones de uso (temperaturas, humedad, exposición al sol, etc.).</li>
                </ul>
              .row(titulo="Observaciones y requisitos de calidad").ajuste-cajaAcordion
                p Incluye datos adicionales relacionados con los estándares que deben cumplirse y pruebas necesarias:
                <ul class="fa-ul">
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Pruebas de resistencia o durabilidad.</li>
                  <li><span class="fa-li"><i class="fas fa-cut"></i></span>Normativas aplicables.</li>
                </ul>

        .col-lg-auto
          figure(data-aos="fade-right").d-none.d-xl-block
            img(src="@/assets/curso/tema5/3.png", alt="" style="width: 505px").m-auto
      
      Separador.ajustes___movil-2
      <!-- BLOQUE 2 -->
      #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 5.2 Usos de la ficha técnica de diseño
  
      p.mb-5.ajustes___movil-1 La ficha técnica cumple diversas funciones clave en el ciclo de vida del producto. No solo sirve como guía para la producción, sino que también es un documento de soporte para los procesos de control de calidad y gestión comercial.


      .row.justify-content-center.mb-5
        .col-lg-10

          .bg-color-23.mb-4
            .row.justify-content-center.align-items-center
              .col-xl-auto(data-aos="fade-right")
                img(src="@/assets/curso/tema5/4.png", style="max-width: 515px", alt="").m-auto.mt-xl-0.mt-4
              .col-xl(data-aos="fade-left")
                .pe-4
                  <ul class="fa-ul">
                    <li class="espacio__li"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Facilita la producción</strong>: sirve como guía clara para el equipo de fabricación.</li>
                    <li class="espacio__li"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Garantiza calidad y uniformidad</strong>: asegura que todas las piezas del producto sean fabricadas bajo los mismos estándares.</li>
                    <li class="espacio__li"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Optimiza costos y tiempos</strong>: al estandarizar el proceso, se reducen errores y retrabajos.</li>
                  </ul>
          
          .bg-color-24
            .row.justify-content-center.align-items-center
              .col-xl(data-aos="fade-left")
                .ps-4
                  <ul class="fa-ul">
                    <li class="espacio__li"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Sirve para cotizaciones</strong>: permite a proveedores conocer los requerimientos específicos del producto.</li>
                    <li class="espacio__li"><span class="fa-li"><i class="fas fa-cut"></i></span><strong>Documento de referencia</strong>: es útil en auditorías, certificaciones y control de calidad.</li>
                    <li><span class="fa-li"><i class="fas fa-cut"></i></span><strong>En la industria del calzado y marroquinería</strong>: la ficha técnica es fundamental para coordinar todos los procesos desde el diseño hasta la manufactura y comercialización del producto.</li>
                  </ul>
              .col-xl-auto(data-aos="fade-right")
                img(src="@/assets/curso/tema5/6.png", style="max-width: 515px", alt="").m-auto.mt-xl-0.mt-4
</template>

<script>
export default {
  name: 'Tema5',
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

<style lang="sass" scoped>
/// BLOQUE 2
.ajuste-caja-tema2
  background-color: $color-adicional-13
  padding: 0.7rem 2rem 0.1rem 2rem
  margin-left: -0.8rem
  @media screen and (max-width: 390px)
    width: 92% !important
    margin-left: 0.5rem
  @media screen and (max-width: 1024px)
    width: 96%
    margin-left: 0.5rem
    padding: 2rem
  @media screen and (min-width: 1400px)
    padding: 3rem 3rem 1.4rem 3rem

.espacio__li
  margin-bottom: 0.5rem
  @media screen and (min-width: 1400px)
    margin-bottom: 1rem
</style>
