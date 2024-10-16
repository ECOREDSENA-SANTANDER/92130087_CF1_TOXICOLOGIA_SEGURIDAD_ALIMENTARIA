<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Sustancias tóxicas de origen fúngico (hongos) 

    .row.justify-content-center.align-items-center
      .col-lg-5.col-md-8.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/t4/img1.png', alt='')
      .col-lg-7
        p Los alimentos por su alto contenido nutricional constituyen potencialmente un medio de cultivo para muchos microorganismos, los cuales en unos casos son útiles desde el punto de vista de la elaboración de algunos productos como leches fermentadas, procesos de maduración, obtención de bebidas alcohólicas, y en otros casos pueden tener efectos tóxicos, bien por su carácter patógeno o por las toxinas que generan.
        p La toxicidad fúngica de los alimentos se debe a la producción de micotoxinas, como productos derivados del metabolismo intermedio de determinados hongos. Entre los principales hongos productores de micotoxinas se encuentran: Penicillium, Aspergillus y Claviceps. Se generan de determinados cereales (maíz, trigo, cebada, sorgo) y legumbres. Entre los principales factores que favorecen el origen de las micotoxinas se encuentran la humedad, la temperatura (20 y 30 ºC), la presencia de oxígeno, presencia de insectos que poseen mohos en el tracto intestinal.  



    Separador
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 4.1. Micotoxinas





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
