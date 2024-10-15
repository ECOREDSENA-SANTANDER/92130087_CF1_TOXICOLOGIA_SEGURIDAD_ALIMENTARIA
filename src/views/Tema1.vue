<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Antinutrientes



    Separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 1.1. Toxicología  
      
    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0
          h3.mb-0.pe-4.pe-lg-5 Limite Residual Crítico (LRM) Y Cantidad de Tóxico (IDA)


</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
