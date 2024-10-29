<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Toxicidad alimentaria por bacterias, virus y hongos

    .row.justify-content-center.align-items-center
      .col-lg-5.d-none.d-lg-block(data-aos="fade-right")
        img(src='@/assets/curso/temas/t2/img1.png', alt='')
      .col-lg-7(data-aos="fade-left")
        p Las enfermedades producidas por la ingestión de alimentos, y/o agua contaminados por agentes infecciones tales como bacterias, virus, hongos, parásitos, que en la luz intestinal pueden multiplicarse y producir toxinas invadiendo la pared intestinal y desde allí alcanzar otros sistemas, son conocidas como enfermedades alimentarias.
        p Aquellas conocidas como intoxicaciones alimentarias son las producidas por la ingestión de toxinas formadas en tejidos de plantas o animales, o de productos metabólicos de microorganismos en los alimentos, o por sustancias químicas que se incorporan a ellos de modo accidental, incidental o intencional en cualquier momento desde su producción hasta su consumo. En estos últimos se encuentran implicados patógenos como Salmonella spp, Escherichia coli, entre otros, considerados como agentes clásicos y bacterias. (López, 2008)

        .cajon.color-primario.bg1.p-4
          p.mb-0 Dado que en Colombia es incipiente el seguimiento a los brotes de este tipo de enfermedades, este curso responde a la necesidad de conocer las características fundamentales de las enfermedades para identificarlas y atenderlas.


    Separador
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 2.1. La importancia de los microorganismos

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-7(data-aos="fade-right")
        p Los microorganismos, son organismos muy pequeños que sólo se pueden observar con equipos especiales como el microscopio. Estos organismos son unicelulares, lo que quiere decir que están formados por una sola célula.
        p Se pueden clasificar en bacterias, hongos y virus, que abundan en la tierra haciendo parte de todos los ambientes. Por ejemplo, las bacterias son microorganismos que juegan un papel muy importante en la flora intestinal; estos necesitan de un medio idóneo para poder proliferar como son los nutrientes y una temperatura adecuada, si esto es apropiado se reproducen con facilidad produciendo toxinas que convierten un alimento inocuo en peligroso.
      .col-lg-5.d-none.d-lg-block(data-aos="fade-left")
        img(src='@/assets/curso/temas/t2/img2.png', alt='')
    
    .bg2.p-4.mb-5(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-lg-2.col-md-4.col-7.mb-3.mb-lg-0
          img.m-auto(src='@/assets/curso/temas/t2/img3.svg', alt='')
        .col-lg-10 
          p.mb-0 En la actualidad, se les presta gran importancia porque son los causantes de muchas enfermedades de tipo intestinal, algunas de las cuales pueden causar la muerte. La mayoría son transmitidas mediante los alimentos por incorrectas prácticas de manipulación de las personas encargadas de transformarlos; esto ha creado un problema de seguridad alimentaria en el mundo, ya que muchos de estos microorganismos con el tiempo se han vuelto más resistentes a los métodos convencionales utilizados para su control, generando nuevas cepas que resultan letales para el ser humano y que ponen en riesgo la salud de toda la población.

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/t2/img4.png', alt='')
      .col-lg-9
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row.justify-content-center(titulo="Multiplicación bacteriana")
            .col-md-11
              p.mb-4 Las bacterias se multiplican pr división simple, proceso que dura de 15 a 20 minutos. Para que las bacterias puedan crecer necesitan humedad, nutrientes, una temperatura específica y un espacio de tiempo.
              h5 Clasificación de las bacterias:
              p Las bacterias se clasifican dependiendo de las temperaturas óptimas para su desarrollo:
              ul.lista-ul--color.fa-ul.color-primario
                li.mb-1
                  i.fas.fa-check-circle
                  | Las que se desarrollan entre 5 y 10 ºC se llaman psicrófilas.
                li.mb-1
                  i.fas.fa-check-circle
                  | Las bacterias que crecen entre 20 y 45 ºC se llaman mesófilas.
                li
                  i.fas.fa-check-circle
                  | Las bacterias que crecen en temperaturas superiores a 45 ºC se llaman termófilas.
          .row.justify-content-center(titulo="Alimentos y microorganismos")
            .col-md-11
              p Los microorganismos tienen una compleja relación con los alimentos:
              ul.lista-ul--color.fa-ul.color-primario
                li.mb-1
                  i.fas.fa-check-circle
                  | Microorganismos que forman parte de la elaboración del alimento.
                li.mb-1
                  i.fas.fa-check-circle
                  | Microorganismos que alteran el alimento.
                li
                  i.fas.fa-check-circle
                  | Microorganismos infecciosos trasmitidos por los alimentos.
              h5 Principales vías de transmisión de microorganismos hallados en los alimentos:
              .row
                .col-lg-4.col-md-6
                  ul.lista-ul--color.fa-ul.color-primario.mb-0
                    li.mb-1
                      i.fas.fa-check-circle
                      | Suelo y agua.
                    li.mb-1
                      i.fas.fa-check-circle
                      | Plantas/ productos.
                    li.mb-0
                      i.fas.fa-check-circle
                      | Utensilios.
                .col-lg-8.col-md-6
                  ul.lista-ul--color.fa-ul.color-primario
                    li.mb-1
                      i.fas.fa-check-circle
                      | Tracto gastrointestinal.
                    li.mb-1
                      i.fas.fa-check-circle
                      | Manipuladores.
                    li
                      i.fas.fa-check-circle
                      | Piensos (alimento concentrado para animales).
          .row.justify-content-center(titulo="Problemas de salud asociados a los alimentos")
            .col-md-11
              ul.lista-ul--color.fa-ul.color-primario.mb-4
                li.mb-1
                  i.fas.fa-check-circle
                  span.mb-0 #[b Infecciones:] los alimentos sirven de vehículo de patógenos en el proceso de colonización de la infección en el hombre.
                p.ps-4 Ejemplo: infecciones causadas por bacterias Campylobacter sp.
              ul.lista-ul--color.fa-ul.color-primario  
                li.mb-1
                  i.fas.fa-check-circle
                  span.mb-0 #[b Intoxicaciones:] se producen tras el consumo de alimentos que contienen toxinas de origen químico o bacteriano.
                p.ps-4 Ejemplo: la bacteria C. Botulinum que produce toxinas.

    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto.col-md-2.col-2
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0.col-md-10.col-10
          h3.mb-0.pe-4.pe-lg-5 Principales grupos microbianos de importancia en los alimentos

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-8        
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 3. 
          span Bacterias
          
        .tabla-b.color-acento-contenido
          .tabla-b__header
            h4.mb-0 Bacterias
          table
            caption Fuente: SENA (2012)
            tr.bg-white
              td.h5.text-center Gramnegativas
              td 
                p Campylobacter
                p Pseudomonas
                p Brucella
                p.mb-0 Acetobacter
              td
                p Famenterobacteriaceae
                p Aeromonas
                p Vibrio
                p.mb-0 Zymomonas
            tr.bg9 
              td.h5.text-center Grampositivas
              td 
                p Micrococcus
                p Staphylococcus
                p Enterococcus
                p Lactococcus
                p Streptococcus
                p.mb-0 Pediococcus
              td 
                p Bacillus
                p Clostridium
                p Lactobacillus
                p Listeria
                p Propionibacterium
                p.mb-0 Bifidobacterium
           

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-8        
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 4. 
          span Hongos
        .tabla-b.color-acento-contenido
          .tabla-b__header
            h4.mb-0 Hongos
          table
            caption Fuente: SENA (2012)
            tr.bg-white 
              td.h5.text-center Mohos
              td 
                p Mucor
                p Rhizopus
                p Claviceps
                p Fusarium
                p.mb-0 Penicillium
              td 
                p Alternaria
                p Botrytis
                p.mb-0 Aspergillus
            tr.bg9 
              td.h5.text-center Levaduras
              td 
                p Saccharomyces
                p Pichia
                p.mb-0 Zygosaccharomyces
              td 
                p Rhodotorula
                p Candida
                p.mb-0 Kluyveromyces  
            tr.bg-white 
              td.h5.text-center Virus
              td 
                p Norovirus
                p Hepatitis A y E
                p.mb-0 Rotavirus
              td 
                p Astrovirus
                p.mb-0 Bacteriófagas
 

    .row.justify-content-center(data-aos="fade")
      .col-lg-8        
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 5. 
          span Grupos fisiológicos de bacterias de importancia en los alimentos.
        .tabla-b.color-acento-contenido
          .tabla-b__header
            h4.mb-0 Grupo fisiológico
          table.text-center
            caption Fuente: SENA (2012)
            tr.bg-white 
              td.text-start 1. Bacterias del ácido láctico
              td 
                p Lactobacillus
                p Pediococcus
                p.mb-0 Leuconostoc
              td 
                p Lactococcus
                p Streptococcus
                p.mb-0 Microbacterium
            tr.bg9 
              td.text-start 2. Bacterias del ácido acético
              td Acetobacter
              td Gluconobacter
            tr.bg-white 
              td.text-start 3. Bacterias del ácido butírico
              td(colspan="2") Clostridium
            tr.bg9 
              td.text-start 4. Bacterias del ácido propiónico
              td(colspan="2") Propionibacterium
            tr.bg-white 
              td.text-start 5. Bacterias proteolíticas
              td 
                p Pseudomonas
                p Bacillus
                p.mb-0 Micrococcus
              td 
                p Alcaligenes
                p Clostridium
                p.mb-0 Streptococcus
            tr.bg9 
              td.text-start 6. Bacterias lipolíticas
              td Pseudomonas
              td Alcaligenes
            tr.bg-white
              td.text-start 7. Bacterias sacarolíticas
              td 
                p Serratia
                p.mb-0 Bacillus
              td 
                p Micrococcus
                p.mb-0 Clostridium
            tr.bg9 
              td.text-start 8. Bacterias pectolíticas
              td 
                p Erwinia
                p.mb-0 Bacillus
              td 
                p Clostridium
            tr.bg-white
              td.text-start 9. Bacterias formadoras de mucílago o viscosidad
              td 
                p Alcaligenes
                p.mb-0 Streptococcus
              td 
                p Leuconostoc
                p.mb-0 Lactobacillus 
            tr.bg9 
              td.text-start 10. Bacterias productoras de gas
              td 
                p Escherichia
                p Proteus
                p Bacillus
                p.mb-0 Propionibacterium
              td 
                p Enterobacter
                p Clostridium
                p Lactobacillus
                p.mb-0 Leuconostoc


    Separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 2.2. Microbiota inicial de los alimentos

    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0
          h3.mb-0.pe-4.pe-lg-5 La carne
    
    p La contaminación por microorganismos de la superficie de los animales durante la manipulación en el sacrificio se puede presentar en:      

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-5.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/t2/fig22-1.svg', alt='Contaminación en piel y pezuñas: Microorganismos patógenos: Suelo, Estiércoles, Piensos, Agua.')
      .col-lg-7
        img(src='@/assets/curso/temas/t2/fig22-2.svg', alt='Microorganismos responsables de la zoonosis: Bacterias: Gramnegativas son Brucella, Salmonella, Campylobacter, Escherichia coli. Grampositivas son Mycobacterium tuberculosis, Listeria monocytogenes, Streptococcus emoliticus.')

    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0
          h3.mb-0.pe-4.pe-lg-5 Aves de corral
    
    p Se pueden presentar en el tejido muscular, la piel adherida, el tejido conectivo y los organismos comestibles de las aves domésticas y de corral:

    .row.justify-content-center.mb-5
      .col-lg-9
        .bg12.p-4.p-lg-5.mb-4
          img.mb-5(src='@/assets/curso/temas/t2/fig22-3.svg', alt='Microbiota normal: Bacterias Levaduras: Gramnegativas son Pseudomonas, Alteromonas, Aeromonas, Proteus. Grampositivas es Corynebacterium.')
          .row.justify-content-center
            .col-lg-8
              p.mb-0.align-items-center.d-flex #[b Plumas y patas] 
                i.fas.fa-long-arrow-alt-right.flecha
                | Pueden portar bacterias psicrotróficas.
              p.mb-0.align-items-center.d-flex #[b Viseras] 
                i.fas.fa-long-arrow-alt-right.flecha      
                | Pueden portar bacterias entéricas.
        img.mb-4(src='@/assets/curso/temas/t2/fig22-4.svg', alt='Bacterias: Gramnegativas son Salmonella, Campylobacter, Yersinia. Grampositivas son Clostridium perfringens (Temperatura > 15 °C), Staphylococcus aureus.')
        img(src='@/assets/curso/temas/t2/fig22-5.svg', alt='Huevos: Contaminación de la cáscara debido a Intestino de las aves, Material de almacenamiento (cambios de temperatura y humedad), Manipuladores de alimentos.')

    .subt(data-aos='fade-right')
      .row.align-items-center.mb-4
        .col-auto
          img(src='@/assets/curso/temas/t1/subt.png', alt='')
        .col-auto.ps-0
          h3.mb-0.pe-4.pe-lg-5 Los peces
    
    .bg12.p-4
      .row.justify-content-center.align-items-center
        .col-lg-2.col-md-5
          img.m-auto.w-75(src='@/assets/curso/temas/t2/img5.svg', alt='')
        .col-lg-8  
          p.mb-1.align-items-center.d-flex #[b Agallas] 
            i.fas.fa-long-arrow-alt-right.flecha
            | Portan bacterias entéricas (de vertebrados).
          p.mb-0.align-items-center.d-flex #[b Superficie] 
            i.fas.fa-long-arrow-alt-right.flecha      
            | Ambiente donde vive el pez y las condiciones de manipulación.          


    Separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 2.3. Las enterobacterias y los alimentos

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5.d-none.d-lg-block
        img(src='@/assets/curso/temas/t2/img6.png', alt='')
      .col-lg-7
        p Las enterobacterias forman parte de la biota intestinal de muchos animales y se encuentran ampliamente distribuidas en el ambiente: agua, tierra, plantas. Estas pueden usarse como indicadores de contaminación fecal, llamadas coliformes fecales.
        .bg10.p-4
          ul.lista-ul--color.fa-ul.color-primario.mb-0
            li
              i.fas.fa-check-circle
              span.mb-0 #[b Patógenos clásicos:] salmonella entérica, Shigella sp., Escherichia coli.
            li.mb-0
              i.fas.fa-check-circle
              span.mb-0 #[b Patógenos emergentes:] e.coli O157, enterobacter sakazaki.

    TabsA.color-acento-botones.mb-5
      .tarjeta.bg7.p-4.px-lg-5(titulo="Salmonella entérica")
        p Serovar enteritidis, su trasmisión se realiza por comida o agua contaminada (huevos y carne), el período de incubación es de 6 a 48 horas y dura de 2 a 5 días. Es la causante de enfermedades por toxoinfección alimentaria muy importantes como:
        ul.lista-ul--color.fa-ul.color-secundario
          li.mb-1
            i.fas.fa-check-circle
            | Gastroenteritis.
          li
            i.fas.fa-check-circle
            span.mb-0 Fiebre tifoidea, la salmonella entérica #[em serovar typhi] es el agente causal de dicha fiebre.
        p El reservorio es el hombre. La dosis infecciosa es bajo 100 células por colonia. La transmisión es principalmente a través del agua, de alimentos contaminados y a través de manipuladores portadores. El número de afectados disminuye a medida que se trate el agua. La trasmisión es oral – fecal.
      .tarjeta.bg7.p-4.px-lg-5(titulo="<em>Salmonella typhi</em>")
        p Es el agente etiológico de la fiebre tifoidea, esta enfermedad es sistemática, el período de incubación es de 7 a 10 días. Esta bacteria penetra la mucosa intestinal pasando por los nódulos linfáticos, puede ubicarse en el hígado y el bazo. Se extiende por la sangre y puede causar una septicemia, los síntomas que genera son fiebre, dolor, tos, estupor y en la segunda semana de ser contraída puede causar diarrea, dura de 3 a 4 semanas y en casos graves puede causar la muerte.
      .tarjeta.bg7.p-4.px-lg-5(titulo="Escherichia coli")
        p Es bacilo gramnegativo, durante muchos años no se consideró patógeno pero actualmente sí. Puede llegar a los alimentos por vectores como cucarachas, moscas, contaminación cruzada y también puede trasmitirse de persona a persona. La intoxicación por Escherichia coli tiene un período de incubación de 8 a 24 horas y casi siempre es transmitida por aguas y alimentos contaminados. Algunas patogenias causadas son:
        ul.lista-ul--color.fa-ul.color-secundario
          li.mb-1
            i.fas.fa-check-circle
            span.mb-0 Enteritis: diarrea de suave a severa.
          li.mb-1
            i.fas.fa-check-circle
            span.mb-0 Cistitis: infección del tracto urinario.
          li.mb-1
            i.fas.fa-check-circle
            | Septicemia.
          li.mb-1
            i.fas.fa-check-circle
            | Meningitis.
      .tarjeta.bg7.p-4.px-lg-5(titulo="Shigella spp")
        p Es un bacilo gramnegativo inmóvil que pertenece a la familia de las enterobacteriáceas. Se clasifican en cuatro grupos A, B, C y D, cada uno de los cuales tiene serotipos distintos. La trasmisión se realiza de persona a persona (los niños son los más afectados), a través del agua o de la mala manipulación de los alimentos. Las epidemias se relacionan con aguas contaminadas por aportes fecales, por ejemplo, en países en desarrollo con deficiencia en la red sanitaria.
      .tarjeta.bg7.p-4.px-lg-5(titulo="Bacillus cereus")
        p El bacillus cereus es una bacteria de bacilos grampositivos y formadora de esporas, puede presentar movilidad y flagelación peritrica. Su hábitat por lo general es el suelo, medios acuáticos o productos alimenticios como las especias en polvo y el arroz. Este b. cereus puede provocar dos tipos de gastroenteritis, la primera por una enteroxina termoestable y la segunda por una con movilidad; la termoestable es la responsable de la forma emética de la enfermedad, está causada por una toxina que es un péptido.
        p Los síntomas que frecuentemente ocasiona la forma emética son vómitos y nauseas, en general sin fiebre, y diarrea durante 24 horas. Tiene un período de incubación de 1 a 6 horas. Se desconoce el funcionamiento de la toxina, pero puede llegar a provocar fallos hepáticos. La segunda forma que es la de movilidad se presenta con diarreas, náuseas y dolores abdominales, se producen 1 o 2 días y el período de incubación de ambas es de 8 a 16 horas y son autolimitantes.

    .bg13.p-4.mb-5(data-aos="fade")
      .row.justify-content-center.align-items-center
        .col-lg-2.col-md-5.mb-3.mb-lg-0
          img.m-auto.w-75(src='@/assets/curso/temas/t2/img7.svg', alt='')
        .col-lg-10 
          h4 Tratamiento y prevención
          p.mb-0 Atenuar los síntomas para evitar la deshidratación con ingesta abundante de líquidos (suero) y dieta blanda, se debe refrigerar correctamente la comida antes de ingerirla para evitar la germinación de las esporas.

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-5.col-md-10.pe-lg-0
        img(src='@/assets/curso/temas/t2/img8.svg', alt='')
      .col-lg-7.col-md-10.ps-lg-0
        .bg1.p-4.px-lg-5.h-100
          .bg-color-acento-contenido.w-fit.py-1.px-2.mb-4
            h4.mb-0 Botulismo
          p.mb-0 Se genera por la bacteria clostridium botulinum, que es un bacilo grampositivo neurotoxigénico formador de esporas y anaerobio, lo que quiere decir que no necesita oxígeno para crecer. Se desarrolla en medios fermentados de azucares y aminoácidos, su hábitat más frecuente es el suelo. Algunos de estos microorganismos son muy importantes patógenos en el hombre, pero también algunos se usan en la industria. Su transmisión es por la ingesta de alimentos en mal estado donde se acumulan las toxinas; en los niños e botulismo se da por ingerir alimentos que contienen la bacteria que excretan toxinas, pero también se puede trasmitir por enlatados, conservas y embutidos de productos cárnicos.


    .row.justify-content-center(data-aos="fade-down")
      .col-lg-4.col-md-8.col-11.mb-3.mb-md-0
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.px-0
            figure
              img(src="@/assets/curso/temas/t2/tarj1-1.png", alt="")
            .text.p-lg-4.p-3
              .row.text-center.px-1.pt-1.mt-md-4.pt-md-0.mt-lg-3.mt-xxl-4
                h4.mt-4.mb-3 Patología
                p La intoxicación produce parálisis facial, dificultad de deglutir y hablar, debilidad progresiva con parálisis, nauseas, vómitos, cólicos abdominales, boca seca, diplopía (visión doble) y dificultad respiratoria que puede terminar en una insuficiencia respiratoria, usualmente no presenta fiebre, los síntomas aparecen de 8 a 28 horas después de consumidos los alimentos.
      .col-lg-4.col-md-8.col-11.mb-3.mb-md-0
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.px-0(@mouseover="mostrarIndicador2 = false")
            .indicador--hover(v-if="mostrarIndicador2")
            figure
              img(src="@/assets/curso/temas/t2/tarj1-2.png", alt="")
            .text.p-lg-4.p-3
              .row.text-center.px-1.pt-1.mt-md-4.pt-md-0.mt-lg-3.mt-xxl-4
                h4.mt-4.mb-3 Tratamiento
                p Despejar las vías respiratorias, suministrar ayuda respiratoria y administrar la antitoxina botulínica, se recomienda la hospitalización de emergencia para facilitar la detección inmediata de la dificultad respiratoria.
      .col-lg-4.col-md-8.col-11.mb-3.mb-md-0
        .row.px-2.pt-2.h-100
          .col-12.m-0.nav-holder2.align-items-center.px-0
            figure
              img(src="@/assets/curso/temas/t2/tarj1-3.png", alt="")
            .text.p-lg-4.p-3
              .row.text-center.px-1.pt-1.mt-md-4.pt-md-0.mt-lg-3.mt-xxl-4
                h4.mt-4.mb-3 Prevención
                p Esterilizar los alimentos envasados o enlatados, inhibir el crecimiento de la bacteria con pH bajos, mantener los alimentos a temperaturas bajas y almacenaje corto, cocinar la comida a 100 ºC durante 5 minutos, uso de autoclaves para conservas y no dar miel a los bebes.
    

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    mostrarIndicador2: true,
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
