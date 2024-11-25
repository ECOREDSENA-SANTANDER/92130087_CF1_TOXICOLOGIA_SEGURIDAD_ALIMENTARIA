<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 La contaminación vírica en alimentos y agua

    .row.justify-content-center.align-items-center
      .col-lg-7(data-aos="fade-right")
        .row.justify-content-center.align-items-center.mb-4
          .col-lg-2.col-md-2.col-7.mb-3.mb-lg-0
            img(src='@/assets/curso/temas/t3/img2.svg', alt='')
          .col-lg-10.col-md-10
            p.mb-0 La importancia de la transmisión de virus a través de alimentos está siendo reconocida de forma creciente en los últimos años. También se sabe que el número de infecciones es fuertemente subestimado en los seguimientos rutinarios que se realizan.
        p El envejecimiento de la población y la globalización de las enfermedades, debido a la rapidez de los viajes internacionales y el comercio, indican que habrá probablemente un aumento del número de infecciones en el futuro. El costo de las infecciones virales asociadas a los alimentos o el agua no se conoce exactamente, pero se sabe que solo en el caso de los calicivirus que pueden ser tan frecuentes como la salmonella, se provoca un gasto de 1,2 a 1,5 miles de millones de dólares anuales en Estados Unidos.
        .cajon.color-primario.bg1.p-4.mb-4
          p.mb-0 Los virus entéricos pueden causar la muerte en personas de edad avanzada, muertes que son claramente evitables.   
      .col-lg-5.d-none.d-lg-block(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/img1.png', alt='')


    Separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 3.1. Reservorio de los microorganismos patogénicos

    .row.bgc-1.align-items-center.p-4.py-5.mb-5(data-aos="fade-down")
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.align-items-center

          .col-lg-3.d-none.d-lg-block
            img(src='@/assets/curso/temas/t3/img3.png', alt='')
          .col-lg-8
            SlyderF.fle-circulo(columnas="col-lg-6 col-md-6")
              .tarjeta.bg5.p-4.py-5
                .row.justify-content-center.mb-4
                  .col-6
                    img.ps-4(src='@/assets/curso/temas/t3/ico1.svg' alt='')
                .bg-color-acento-contenido.w-fit.m-auto.mb-4.py-1.px-4
                  h4.text-center.mb-0 Humanos
                p.text-center Hepatitis A, enterovirus.
              .tarjeta.bg5.p-4.py-5
                .row.justify-content-center.mb-4
                  .col-6
                    img.ps-4(src='@/assets/curso/temas/t3/ico2.svg' alt='')
                .bg-color-acento-contenido.w-fit.m-auto.mb-4.py-1.px-4
                  h4.text-center.mb-0 Animales
                p.text-center Campylobacter, cryptosporidium, guardia. 
              .tarjeta.bg5.p-4.py-5
                .row.justify-content-center.mb-4
                  .col-6
                    img.ps-4(src='@/assets/curso/temas/t3/ico3.svg' alt='')
                .bg-color-acento-contenido.w-fit.m-auto.mb-4.py-1.px-4
                  h4.text-center.mb-0 Ambiente
                p.text-center Legionella, vibrio, naegleria.

    .tarjeta--container.row(data-aos="fade")
      .col-md.tarjeta.bg14.p-5
        .row.align-items-end.mb-4
          .col-3.pe-0
            img(src='@/assets/curso/temas/t3/tarj-ico1.svg', alt='')
          .col-9.ps-0
            .bg-color-acento-contenido.w-fit.py-1.px-4
              h3.mb-0 Principales virus entéricos humanos
        p Principales virus entéricos en humanos de transmisión fecal – oral:
        ul.lista-ul--color.fa-ul.color-2.mb-0
          li.mb-2
            i.fas.fa-check-circle
            | Rotavirus.
          li.mb-2
            i.fas.fa-check-circle
            | Enterovirus.
          li.mb-2
            i.fas.fa-check-circle
            | Edenovirus.
          li.mb-2
            i.fas.fa-check-circle
            | Norovirus.
          li.mb-2
            i.fas.fa-check-circle
            | Hepatitis A, Hepatitis E.
          li.mb-2
            i.fas.fa-check-circle
            | Astrovirus.
      .col-md.tarjeta.bg15.p-5
        .row.align-items-end.mb-4
          .col-3.pe-0
            img(src='@/assets/curso/temas/t3/tarj-ico2.svg', alt='')
          .col-6.ps-0
            .bg-color-acento-contenido.w-fit.py-1.px-4
              h3.mb-0 Categorías
        ul.lista-ul--color.fa-ul.color-primario.mb-0
          li.mb-2
            i.fas.fa-check-circle
            | Virus que causan gastroenteritis.
          li.mb-2
            i.fas.fa-check-circle
            | Virus que causan hepatitis.
          li.mb-2
            i.fas.fa-check-circle
            | Virus que causan otras enfermedades, (meningitis, afecciones neurológicas, miocarditis, entre otras).
          li.mb-2
            i.fas.fa-check-circle
            | Otros virus no se transmiten de forma general a través del agua o alimentos, sino por vía respiratoria o contacto con secreciones; por ejemplo: Influenzavirus (orthomyxoviridae), SARS (coronavirus), Ebola virus (filoviridae).
          li
            i.fas.fa-check-circle
            | Otros virus se transmiten de forma general por transmisión sanguínea o transmisión sexual; por ejemplo: HIV (Retriviridae), Hepatisis B (Hepadnaviridae).                


    Separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 3.2. Virus

    .row.justify-content-center.align-items-center
      .col-lg-7(data-aos="fade-right")
        p Son elementos genéticos que presentan dos estados, uno intracelular, donde el virus puede replicarse y uno extracelular que constituye la partícula vírica que sirve para la transmisión de los nuevos huéspedes. Se han caracterizado unos 40.000 virus de varias docenas de familias diferentes, sabiendo además que solo una pequeña fracción de los virus que existen en el planeta son los causantes de enfermedades.
        p Los virus, por lo tanto, son parásitos intracelulares obligados y no pueden replicar en agua o en alimentos. Los alimentos pueden presentar contaminación viral (por ejemplo, las bacterias presentes en los alimentos pueden contener virus) y tener un aspecto, color y sabor completamente normal. Los que están asociados a agua o alimentos son en su totalidad virus de estructura icosahédrica, desnudos (sin envuelta lipídica), relativamente resistentes al calor, desinfección y cambios de pH. 
        p Así, la contaminación vírica de los alimentos no aumenta durante el procesamiento, únicamente puede mantenerse o disminuir por inactivación o dilución de los virus.
      .col-lg-5.d-none.d-lg-block(data-aos="fade-left")
        img(src='@/assets/curso/temas/t3/img4.png', alt='')


    Separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 3.3. Virus entéricos en humanos

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade")
      .col-lg-1.col-md-2.col-7.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/t3/img5.svg', alt='')
      .col-lg-11.col-md-10
        p.mb-0 Los principales virus entéricos en humanos que se transmiten por transmisión fecal-oral son: Rotavirus, Enterovirus, Adenovirus, Norovirus, Hepatitis A, Hepatitis E, Astrovirus. La transmisión por lo general se da por alimentos, agua y de persona a persona, los síntomas clínicos son gastroenteritis, hepatitis o enfermedades neurológicas y miocarditis, entre otras.

    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0
          h3.mb-0.pe-4.pe-lg-5 Virus de la hepatitis A
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.d-none.d-lg-block(data-aos="fade-right")
        img(src='@/assets/curso/temas/t3/img6.png', alt='')
      .col-lg-7(data-aos="fade-left")
        p Es un virus de la familia Picornaviridae del género Hepatovirus, que puede ser transmitido por aguas, alimentos crudos, mariscos y de persona a persona, en instituciones como en colegios. Su período de incubación es de 2 a 6 semanas. Los síntomas que produce son malestar, anorexia, náuseas, letargia e ictericia. La infección generalmente es subclínica en niños. La severidad de los síntomas aumenta con la edad. Los síntomas normales son durante cuatro semanas, pero pueden ser más prolongados, no produce infecciones crónicas y existe un único serotipo. 
        p Este virus es extraordinariamente resistente en agua, alimentos y en el ambiente en general:
        .bg1.h-100.p-4         
          ul.lista-ul--color.fa-ul.color-primario.mb-0
            li
              i.fas.fa-check-circle
              | Desnaturalización térmica, sobrevive a 70 ºC hasta 10 minutos.
            li
              i.fas.fa-check-circle
              | Tratamientos ácidos con pH 1 durante 2 horas a temperatura ambiente.
            li
              i.fas.fa-check-circle
              | Inactivación por detergentes, sobrevive a 37 ºC durante 30 minutos SDS.
            li.mb-0
              i.fas.fa-check-circle
              | Almacenamiento a – 20 ºC durante años.

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-9  
        .row.justify-content-center
          .col-lg-5.col-md-10.pe-lg-0
            .bg8.h-100.d-flex.align-items-end
              img(src='@/assets/curso/temas/t3/img7.svg', alt='')
          .col-lg-7.col-md-10.ps-lg-0
            .bg1.p-4.px-lg-5.h-100
              .bg16.py-1.px-2.mb-4
                h4.mb-0 Es inactivado con:      
              ul.lista-ul--color.fa-ul.color-primario.mb-0
                li
                  i.fas.fa-check-circle
                  | Calentamiento a temperaturas de 80 ºC durante 1 minuto.  
                li
                  i.fas.fa-check-circle
                  | Autoclave a 121 ºC durante 20 minutos.
                li
                  i.fas.fa-check-circle
                  | Radiación ultravioleta de 1.1 W a una profundidad de 0.9 durante 1 minuto.
                li
                  i.fas.fa-check-circle
                  | Cloro en concentraciones de cloro libre residual 2.0 a 2.5 mg/l durante 15 minutos.
                li.mb-0
                  i.fas.fa-check-circle
                  | Componentes que contienen cloro de 3 a 4 mg/l hipoclorito sódico a 20 ºC de 5 a 15 min.
      .col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/t3/img8.png', alt='')

    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0
          h3.mb-0.pe-4.pe-lg-5 Hepatitis E
    
    p El VHE presenta una tasa de mortalidad aproximadamente del 1 % pero puede llegar al 20 % en mujeres embarazadas. La prevalencia de anticuerpos en áreas consideradas no endémicas es de 1 a 3 %. Su morfología es una partícula esférica sin envuelta, es icosaedrico con un tamaño de 32–34 nm. Los antígenos son dos inmodominates.      

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-5.col-md-10.pe-lg-0
        .bg8.h-100.d-flex.align-items-end
          img(src='@/assets/curso/temas/t3/img9.png', alt='')
      .col-lg-7.col-md-10.ps-lg-0
        .bg1.p-4.px-lg-5.h-100
          .bg-color-acento-contenido.w-fit.py-1.px-2.mb-4
            h4.mb-0 Potenciales reservorios del VHE en animales  
          ul.lista-ul--color.fa-ul.color-primario.mb-0
            li
              i.fas.fa-check-circle
              | Según estudios realizados sobre la infección por el virus de la Hepatitis E en porcinos, en Estados Unidos el 80 % de los cerdos mayores de 3 meses son seropositivos.
            li
              i.fas.fa-check-circle
              | Se ha descrito la infección por VHE en porcinos en Tailandia, Vietnam, Taiwán, Corea, China, Canadá y Australia.
            li
              i.fas.fa-check-circle
              | Se han detectado anticuerpos que reaccionan contra el VHE en ratas, ganado, aves (HEV aviar), vacuno, cabras, perros y gatos. Estos diversos animales podrían presentar virus muy diferentes a los humanos y por tanto no se ha comprobado que actúen como reservorio de la infección.

    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0
          h3.mb-0.pe-4.pe-lg-5 Rotavirus

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade")
      .col-lg-1.col-md-2.col-7.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/t3/img10.svg', alt='')
      .col-lg-11.col-md-10
        p.mb-0 Pertenece a la familia Reoviridae, es virus icosaédrico sin envuelta lipídica con la cápsula icosahédrica formada por dos capas concéntricas y un diámetro aproximado de 80 nm. El rotavirus tiene una apariencia característica parecida a la de una rueda. El virus es estable al medio ambiente, contiene 11 segmentos de ARN lineal de cadena doble. La longitud total del genoma es 16500 - 21000 nucleóticos. Codifica para seis proteínas estructurales y cinco no estructurales.

    TabsB.color-acento-contenido.mb-5(data-aos="fade-down")
      .py-4.py-md-5(titulo="Estructura taxonómica" :icono="require('@/assets/curso/temas/t3/tabs-ico1.svg')")
        .row.justify-content-center
          .col-md-7
            h4.mb-4 Estructura taxonómica - grupos antígenos derotavirus
            ul.lista-ul--color.fa-ul.color-primario.mb-0
              li
                i.fas.fa-check-circle
                | Rotavirus del grupo A se han identificado en la mayoría de especies de mamíferos y aves estudiadas.
              li
                i.fas.fa-check-circle
                | Rotavirus del grupo B infectan a humanos, cerdos, ganado vacuno, corderos y ratas.
              li
                i.fas.fa-check-circle
                | Rotavirus del grupo C se identifican en cerdos y raramente en humanos.
              li
                i.fas.fa-check-circle
                | Rotavirus del grupo D en aves de corral y grupo E en cerdos.
          .col-lg-3.col-md-4.col-9
            img(src='@/assets/curso/temas/t3/tabs-img1.svg', alt='')
      .py-4.py-md-5(titulo="Características clínicas" :icono="require('@/assets/curso/temas/t3/tabs-ico2.svg')")
        .row.justify-content-center
          .col-md-7
            h4 Características clínicas
            p El rotavirus es la causa más común de diarrea severa en niños, y causa aproximadamente 55.000 hospitalizaciones cada año en Estados Unidos, además de la muerte de más 600.000 niños a nivel mundial. El período de incubación de la enfermedad por rotavirus es de aproximadamente 2 días, su sintomatología vómitos, diarrea acuosa por 3 a 8 días, fiebre y dolor abdominal ocurrente con frecuencia. La inmunidad después de la infección es incompleta, pero infecciones posteriores tienden a ser menos severas que la infección original.
          .col-lg-3.col-md-4.col-9
            img(src='@/assets/curso/temas/t3/tabs-img2.svg', alt='')
      .py-4.py-md-5(titulo="Características epidemiológicas" :icono="require('@/assets/curso/temas/t3/tabs-ico3.svg')")
        .row.justify-content-center
          .col-md-7
            h4 Características epidemiológicas
            p La forma primaria de transmisión es fecal-oral, aunque algunos casos se han reportado bajo títulos del virus en secreciones del conducto respiratorio y otros fluidos corporales. Dado que el virus es estable en el medio ambiente, la transmisión puede ocurrir a través de la ingestión de agua o comida contaminada, y mediante contacto con superficies contaminadas.
          .col-lg-3.col-md-4.col-9
            img(src='@/assets/curso/temas/t3/tabs-img3.svg', alt='')
      .py-4.py-md-5(titulo="Diagnóstico" :icono="require('@/assets/curso/temas/t3/tabs-ico4.svg')")
        .row.justify-content-center
          .col-md-7
            h4 Diagnóstico
            p El diagnóstico puede hacerse mediante la detección rápida de antígenos de rotavirus en especímenes de heces.
          .col-lg-3.col-md-4.col-9
            img(src='@/assets/curso/temas/t3/tabs-img4.svg', alt='')
      .py-4.py-md-5(titulo="Tratamiento" :icono="require('@/assets/curso/temas/t3/tabs-ico5.svg')")
        .row.justify-content-center.align-items-end
          .col-md-7
            h4.mb-4 Tratamiento
            .bg1.mb-3.mb-lg-0
              .bloque-texto-d.p-4.py-3
                .bloque-texto-d__texto.mb-2
                  i.fas.fa-quote-left
                  h4 Para las personas con sistema inmune saludable, que sufren gastroenteritis por rotavirus el tratamiento es pasivo y consiste en terapia de rehabilitación oral para prevenir la deshidratación. Aproximadamente uno de cada 40 niños con gastroenteritis por rotavirus va a requerir hospitalización para la administración de fluidos intravenosos. 
                  i.fas.fa-quote-right
                .bloque-texto-d__autor 
                  p.mb-0 Centro Materno infantil (s.f).
          .col-lg-3.col-md-4.col-9
            img(src='@/assets/curso/temas/t3/tabs-img5.svg', alt='')

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
