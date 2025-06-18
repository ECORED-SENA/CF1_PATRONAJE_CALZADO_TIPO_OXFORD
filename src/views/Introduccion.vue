<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción


    .row
      .col-lg-4
        figure
          img(src="@/assets/curso/intro/1.svg", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-8
        .tarjeta.bg-color-19.p-4(data-aos="fade-left").mb-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/intro/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El componente formativo Anatomía, materiales y construcción del calzado, proporciona conocimientos sobre hormas, tipos de patrones, normas de diseño, materiales, estructura y partes del calzado, variaciones según parámetros técnicos, fases de fabricación, ubicación de líneas guía en la horma y estructura anatómica del pie. Se estudiarán sistemas de medidas y adaptaciones para comprender la elaboración de patrones.
    
        p(data-aos="fade-left").mb-4 Este componente formativo se enfoca en los aspectos técnicos del patronaje de calzado tipo Oxford, brindando herramientas para comprender su estructura, materiales, proceso de corte y ensamblaje. Se abordan temas clave como la anatomía del calzado, las características de la horma, los tipos de patrones, y la aplicación de normas de diseño. Además, se estudian los sistemas de medidas y las adaptaciones necesarias para garantizar un ajuste ergonómico y confortable. 

        .row
          .col-lg
            .tarjeta.bg-color-20.px-4.py-5(data-aos="fade-left").mb-4
              p.mb-0 Al finalizar este componente, el aprendiz estará en capacidad de identificar las partes del calzado Oxford, interpretar fichas técnicas y elaborar patrones con base en parámetros de diseño establecidos. Esto le permitirá desarrollar habilidades para modelar calzado con estándares de calidad, combinando funcionalidad, confort y estilo en una propuesta que responde a las exigencias del mercado actual. 
            
          .col-lg-auto.d-none.d-sm-block
            figure
              img(src="@/assets/curso/intro/3.png", data-aos="zoom-in", style="max-width: 295px").mb-4.mx-auto
        
    

</template>

<script>
export default {
  name: 'Introduccion',
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
