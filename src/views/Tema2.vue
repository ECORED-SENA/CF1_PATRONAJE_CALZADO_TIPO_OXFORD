<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Tipologías de calzado: características y usos

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/1b.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El calzado es un elemento esencial en la vestimenta, diseñado para proteger los pies y proporcionar comodidad, estilo y funcionalidad según la ocasión y la actividad. Existen diversas tipologías de calzado, cada una con características y usos específicos que responden a necesidades particulares, desde el ámbito deportivo hasta el formal o industrial.

    
    Separador

    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1  Clasificación del calzado según su uso

    p.mb-5 El calzado se clasifica principalmente según la función y el entorno en el que se usa. Algunas de las principales categorías son:

    TabsC.color-acento-botones
      .py-4.py-lg-5.px-4.px-lg-5(titulo="Formal")
        .row.align-items-center
          .col-lg.order-lg-2
            h4 Formal
            p Diseñado para eventos elegantes, trabajo de oficina o reuniones formales. Ejemplos: zapatos Oxford, Derby, mocasines y tacones de vestir.
        
          .col-lg-auto.order-lg-1
            figure
              img(src='@/assets/curso/tema2/slider-1.png', alt='', style="max-width: 468px")
      .py-4.py-lg-5.px-4.px-lg-5(titulo="Deportivo")
        .row.align-items-center
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema2/slider-2.png', alt='', style="max-width: 468px")
          .col-lg
            h4 Deportivo
            p Creado para brindar soporte y amortiguación en actividades físicas. Ejemplos: tenis para correr, calzado de fútbol, zapatillas de baloncesto.
      .py-4.py-lg-5.px-4.px-lg-5(titulo="Casual")
        .row.align-items-center
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema2/slider-3.png', alt='', style="max-width: 468px")
          .col-lg
            h4 Casual
            p Ideal para el día a día, combinando comodidad y estilo. Ejemplos: zapatillas urbanas, baletas, sandalias, botines.
      .py-4.py-lg-5.px-4.px-lg-5(titulo="Industrial")
        .row.align-items-center
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema2/slider-4.png', alt='', style="max-width: 468px")
          .col-lg
            h4 Industrial
            p Diseñado para entornos de trabajo que requieren protección especial. Ejemplos: botas de seguridad con punta de acero, calzado dieléctrico, botas antideslizantes.
      .py-4.py-lg-5.px-4.px-lg-5(titulo="Ortopédico")
        .row.align-items-center
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema2/slider-5.png', alt='', style="max-width: 468px")
          .col-lg
            h4 Ortopédico
            p Especialmente diseñado para corregir o aliviar problemas en los pies. Ejemplos: zapatos con plantillas anatómicas, calzado con soporte para el arco.


    Separador

    #t_2_2.titulo-segundo.color-acento-contenido
      h2 2.2  Diferencias entre modelos de calzado

    p.mb-5 Cada modelo de calzado se distingue por su diseño, estructura y materiales, los cuales influyen en su funcionalidad, comodidad y uso. A continuación, se presentan las diferencias clave entre los distintos tipos de calzado.

    .row.align-items-start.mb-5#aco-5
      .col-lg-4
        figure
          img(src="@/assets/curso/tema2/3b.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonB")
          .div(titulo="Forma y estructura")
            p El Oxford tiene una estructura cerrada con cordones internos, mientras que el Derby es más flexible con cordones abiertos. El mocasín es un zapato sin cordones, fácil de poner y quitar. El calzado con velcro es ideal para niños o personas con movilidad reducida, mientras que el elástico permite un ajuste sin sujetadores adicionales.
    
          .div(titulo="Materiales")
            p El calzado varía en materiales según su función y uso. El cuero es duradero, transpirable y elegante. Los materiales sintéticos son ligeros, económicos y fáciles de limpiar, además de ofrecer resistencia al agua. Las mallas y lonas son cómodas y transpirables.
    
          .div(titulo="Función y comodidad")
            p Los tenis están diseñados para absorber impactos, mientras que los zapatos formales priorizan la estética y la elegancia.



    .row.align-items-start.mb-5#aco-6
      .col-lg-8

        AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonB")
          .div(titulo="Suela y amortiguación")
            ul.lista-ul--color
              li 
                i.fas.fa-check-circle.bg-color-17
                | #[strong Plana vs. con tacón.] Los zapatos planos brindan estabilidad y comodidad, mientras que los de tacón realzan la postura y la elegancia.
              li 
                i.fas.fa-check-circle.bg-color-17
                | #[strong Goma vs. cuero.] Las suelas de goma ofrecen mayor tracción y amortiguación, mientras que las de cuero son más rígidas y elegantes, pero menos antideslizantes.
              li 
                i.fas.fa-check-circle.bg-color-17
                | #[strong Flexible vs. rígida.] Los tenis deportivos tienen suelas flexibles para amortiguar impactos, mientras que las botas de seguridad tienen suelas rígidas para mayor protección.

          .div(titulo="Protección y soporte")
            ul.lista-ul--color
              li 
                i.fas.fa-check-circle.bg-color-17
                | #[strong Bota vs. zapato bajo.] Las botas cubren el tobillo o la pierna, brindando mayor protección, mientras que los zapatos bajos permiten mayor movilidad.
              li 
                i.fas.fa-check-circle.bg-color-17
                | #[strong Punta de acero vs. punta reforzada.] En el calzado industrial, las botas con punta de acero protegen contra impactos fuertes, mientras que las de punta reforzada ofrecen protección media sin el peso del acero.
          .div(titulo="Estilo y uso")
            ul.lista-ul--color
              li 
                i.fas.fa-check-circle.bg-color-17
                | #[strong Casual vs. formal.] Los zapatos casuales priorizan la comodidad y versatilidad, mientras que los formales buscan elegancia y sofisticación.
              li 
                i.fas.fa-check-circle.bg-color-17
                | #[strong Deportivo vs. urbano.] Los tenis deportivos están diseñados para alto rendimiento, mientras que los urbanos combinan estilo y comodidad para el día a día.
      .col-lg-4
        figure
          img(src="@/assets/curso/tema2/2b.png", alt="").mt-4.mt-lg-0


    .row.justify-content-center
      .col-lg-10.tarjeta.p-4.bg-color-22
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema2/4b.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Cada modelo de calzado se adapta a diferentes necesidades, estilos y actividades, por lo que conocer sus diferencias ayuda a elegir el más adecuado para cada ocasión.
    
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

<style lang="sass">

.tarjeta.acordeonB
  background-color: #FBE7B9 !important

.acordion__accion__btn--a.acordeonB
  background-color: $color-acento-botones !important
  i
    color: #fff !important

.acordion__activo.acordeonB
  background-color: #DAF6D7 !important
</style>
