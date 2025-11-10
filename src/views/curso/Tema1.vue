<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Neuroplasticidad y aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-3.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema1/1.png', alt='')
        .col-lg.order-1.mb-3.mb-lg-0
          .p-4.text-white
            p.mb-0(data-aos="fade-up") Aunque todos los cerebros parecen similares a simple vista, en realidad presentan diferencias significativas. Triglia (2025) señala que, si bien los cerebros humanos comparten una estructura básica, sus circuitos neuronales muestran formas y distribuciones únicas que no dependen exclusivamente de la genética. Estas variaciones emergen de las experiencias individuales, lo que significa que nuestros cerebros son moldeados constantemente por nuestras vivencias. Este proceso se conoce como plasticidad cerebral o neuroplasticidad.
    
    h2(data-aos="fade-left") ¿Qué es la neuroplasticidad?
    p.mb-5 La neuroplasticidad, según Triglia (2025), se refiere a la capacidad del sistema nervioso para transformarse mediante su interacción con el entorno. Incluso los gemelos monocigóticos desarrollan cerebros diferentes porque cada persona actúa y experimenta el mundo de manera singular. Este fenómeno no es estático ni lento: ocurre de forma continua, incluso durante el sueño, a medida que interactuamos con múltiples estímulos y modificamos nuestro entorno.

    .row.justify-content-center.align-items-center.bg-full-width.bg-color-6.mb-5
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-7(data-aos="fade-left").mb-3.mb-lg-0.order-2
            p Una forma sencilla de entender la neuroplasticidad es compararla con el material plástico: ambos pueden cambiar de forma. Sin embargo, hay dos matices importantes:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 La neuroplasticidad requiere una inteligencia externa que guíe su dirección (como el moldeador del plástico).
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right
                p.mb-0 A diferencia del plástico, el cerebro no se moldea solo en una fase inicial, sino que puede seguir transformándose a lo largo del tiempo.
          .col-lg-5(data-aos="zoom-in").order-1
            img.img-fluid(src='@/assets/curso/tema1/2.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    p.mb-5 Los fundamentos históricos de la neuroplasticidad son: 

    .row.align-items-start.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/3.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
    
        AcordionA(tipo="b")
          .div(titulo="Ramón y Cajal (siglo XIX)")
            p Propuso que la base física del aprendizaje reside en la plasticidad de las conexiones neuronales.
    
          .div(titulo="Hebb (1949)")
            p Estableció que la coincidencia entre actividad pre y post-sináptica fortalece las conexiones neuronales.
    
          .div(titulo="Matthies (1978)")
            p Reafirmó la idea de que las sinapsis cambian su eficacia en la transmisión de información.
    
          .div(titulo="Lomo y Tim Bliss")
            p Descubrieron la potenciación a largo plazo (PLP), como mecanismo de aprendizaje y memoria.
          .div(titulo="John O’Keefe")
            p Observó cambios anatómicos en el hipocampo por aprendizaje de mapas cognitivos.

    .bg-full-width.bg-color-3.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/4.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Estos hallazgos demuestran que el aprendizaje modifica la estructura y función cerebral. Espinoza et al. (2010) explican que esta actividad neuronal transforma la organización del citoesqueleto y la expresión genética de las neuronas mediante cambios en los niveles intracelulares de calcio (Ca²⁺).
    
    .bg-full-width.bg-color-10
      .px-4.px-md-5.pb-md-3
        
        h2(data-aos="fade-left") Periodos sensibles y neuroplasticidad
        p.mb-5 La influencia de la experiencia en el cerebro es especialmente notable durante los periodos sensibles o críticos, que son etapas en las que el desarrollo de ciertas funciones depende de la estimulación ambiental adecuada. Ejemplos relevantes:

        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-4.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema1/5.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Visión
                p.mb-0 Niños con cataratas no tratadas antes de la pubertad pueden desarrollar ambliopía permanente.
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema1/6.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Audición
                p.mb-0 El éxito de un implante coclear es mayor si se realiza a edades tempranas.
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/tema1/7.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Lenguaje
                p.mb-0 La falta de estimulación lingüística durante la infancia afecta la adquisición del lenguaje.

    .row.justify-content-center.align-items-center.bg-color-12.mb-5
      .col-lg-12
        .row.justify-content-center.align-items-center
          .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0.order-2
            p Espinoza et al. (2010) también destacan cómo la plasticidad se manifiesta de forma sorprendente en la activación de la corteza visual primaria durante la lectura de Braille en personas ciegas desde la infancia. Esto demuestra que la reorganización cortical ocurre en respuesta a la experiencia sensorial.
            p En todos los casos estudiados, tanto en humanos como en animales, el periodo sensible para inducir cambios corticales finaliza con la pubertad. Esto sugiere que los mecanismos de plasticidad son comunes en distintas regiones cerebrales y que conocerlos es clave para estrategias terapéuticas en adultos, sobre todo en procesos de recuperación tras trauma infantil.
          .col-lg-4(data-aos="zoom-in").order-1
            img.img-fluid(src='@/assets/curso/tema1/8.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    h2(data-aos="fade-left") Lenguaje y plasticidad neuronal

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/9.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left").mb-5 Los estudios citados por Espinoza et al. (2010) muestran cómo la experiencia lingüística temprana es determinante:
    
        .bg-color-7.p-4(data-aos="fade-left")
          ul.lista-ul--color
            li.mb-0.d-flex
              i.far.fa-arrow-alt-circle-right
              p.mb-0 <b>Niños sordos sin acceso temprano a lenguaje alternativo</b>: Pierden la posibilidad de desarrollar una comunicación eficaz.
            li.mb-0.d-flex
              i.far.fa-arrow-alt-circle-right
              p.mb-0 <b>Niños que pierden la audición después de aprender a hablar o que crecen con padres con psicopatologías</b>: También presentan deterioro del lenguaje hablado.
        .bg-color-8.p-4(data-aos="fade-left")
          p.mb-0 Esto se debe a la ausencia de retroalimentación auditiva, crucial durante las etapas finales del periodo sensible para el lenguaje. Además, la estructura fonética que una persona escucha en su infancia moldea tanto la percepción como la producción del habla.
    
    p.mb-5 Un último ejemplo importante es la adquisición de una lengua no materna. Según los estudios, la capacidad para aprender la fonética de un nuevo idioma de forma fluida persiste hasta el inicio de la pubertad. Después de esta etapa, la habilidad disminuye gradualmente, independientemente de la práctica o exposición.

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/10.png", data-aos="zoom-in")
      .col-lg-8
        h2(data-aos="fade-left").mb-5 Plasticidad neuronal
        .bg-color-4.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/11.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La neuroplasticidad, según Gómez Fernández (2000), citado por Espinoza et al. (2010), es una propiedad dinámica del sistema nervioso que le permite modificarse en respuesta al aprendizaje, la estimulación sensorial o cognitiva, e incluso tras una lesión cerebral. Esta capacidad no solo opera en los primeros años de vida, sino que se mantiene activa en la adultez, permitiendo adaptaciones funcionales y estructurales a lo largo del tiempo.
        p(data-aos="fade-left") Una de las contribuciones más importantes de la investigación contemporánea ha sido identificar los diversos mecanismos a través de los cuales ocurre la neuroplasticidad. Estos mecanismos permiten comprender cómo el cerebro cambia, se adapta o se reorganiza, y son fundamentales tanto para el desarrollo cognitivo como para la recuperación neurológica después de un daño. A continuación, se presenta una tabla que resume los principales factores, tipos de cambios y condiciones asociados a la plasticidad neuronal:
    
    .bg-full-width.bg-fondo-1.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema1/12.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="66%" y="69.5%" numero="+")
                h5 Factores activadores
                p Estimulación sensorial, cognitiva, física; aprendizaje; entorno enriquecido.
    
              .bg-color-white.box-shadow.p-3(x="77.3%" y="34%" numero="+")
                h5 Cambios estructurales
                p Crecimiento de dendritas y axones; formación de nuevas sinapsis; reorganización funcional tras una lesión.
    
              .bg-color-white.box-shadow.p-3(x="46%" y="9%" numero="+")
                h5 Cambios funcionales y moleculares
                p Alteración de la respuesta a neurotransmisores y neuropéptidos; regulación del citoesqueleto y expresión génica.
    
              .bg-color-white.box-shadow.p-3(x="16%" y="43%" numero="+")
                h5 Neurogénesis
                p Producción de nuevas neuronas en cerebros adultos; estimulada por ejercicio físico y cognitivo.
    
              .bg-color-white.box-shadow.p-3(x="30%" y="78%" numero="+")
                h5 Áreas implicadas
                p Varias regiones del cerebro, con especial énfasis en el hipocampo por su rol en la memoria y el aprendizaje.
    
    h2(data-aos="fade-left").mb-5 Fortalecimiento de conexiones neuronales

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-6.tarjeta.p-4.h-100(data-aos="fade-left")
          p(data-aos="fade-left") De acuerdo con Triglia (2025), cuando un grupo de neuronas se activa simultáneamente de manera repetida, sus conexiones se refuerzan y se vuelven más estables. Esta sincronicidad hace que, con el tiempo, esas neuronas tengan más probabilidades de activarse juntas en el futuro. Así, el sistema nervioso sufre cambios físicos a nivel microestructural, resultado directo de la experiencia.
          figure.d-flex.justify-content-end
            img(src="@/assets/curso/tema1/14.svg" data-aos="zoom-in", style="max-width: 67px")
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/13.png" data-aos="zoom-in")
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-7.tarjeta.p-4.h-100(data-aos="fade-left")
          p(data-aos="fade-left") Un ejemplo ilustrativo de este fenómeno es el reconocimiento de patrones visuales. Si las neuronas que responden a la visión de un chocolate y las que responden al sabor dulce se activan juntas de manera frecuente, sus conexiones se fortalecen. Como consecuencia, el cerebro asocia ambos estímulos, lo que evidencia la importancia de la plasticidad cerebral en los procesos de aprendizaje, percepción y memoria.
    
    h2(data-aos="fade-left") Tipos y características de la neuropasticidad
    p.mb-5 La neuroplasticidad, como explica Ceupe (2023), es la capacidad del cerebro para modificar su estructura y funcionamiento a lo largo de la vida, en respuesta a experiencias, aprendizajes y estímulos del entorno. Este proceso no solo impulsa el desarrollo cognitivo, emocional y conductual, sino que también permite la adaptación, el desaprendizaje o incluso respuestas disfuncionales. En este contexto, se distinguen dos formas principales: neuroplasticidad positiva y neuroplasticidad negativa:
        
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/15.png")
            .col-lg-7
              h5 Neuroplasticidad positiva
              p Favorece el desarrollo cognitivo, emocional y funcional. Se manifiesta en la neurogénesis, el fortalecimiento sináptico y la mejora de habilidades.
              p <b>Ejemplo</b>. Un estudiante que lee regularmente fortalece redes neuronales vinculadas al lenguaje y la comprensión.

    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema1/16.png")
            .col-lg-7
              h5 Neuroplasticidad negativa
              p Conduce al debilitamiento o pérdida de funciones por desuso, adaptación a patrones nocivos o falta de estimulación.
              p <b>Ejemplo</b>. Una persona que deja de usar un segundo idioma ve deterioradas las redes asociadas a esa habilidad.
    
    p.mb-5 Ahora bien, la importancia de esta propiedad del sistema nervioso radica en su capacidad de respuesta flexible y eficiente ante las demandas del entorno. Las características de la neuroplasticidad explican cómo el cerebro se moldea, se regenera, se adapta y optimiza a partir de la experiencia, la estimulación y el aprendizaje continuo:

    .row.align-items-start.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/17.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
        AcordionA(tipo="b")
          .div(titulo="Moldeable")
            p El cerebro reajusta sus circuitos neuronales según las experiencias. Por ejemplo, aprender un instrumento musical genera nuevas rutas auditivas, motoras y sensoriales.
    
          .div(titulo="Capacidad regenerativa")
            p Regiones como el hipocampo generan nuevas neuronas incluso en la adultez, favoreciendo la renovación neuronal con experiencias significativas y entornos enriquecidos.
    
          .div(titulo="Activa toda la vida")
            p Aunque es más intensa en la infancia, la plasticidad persiste en la adultez y vejez, permitiendo el aprendizaje continuo y la recuperación funcional.
    
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/18.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="b")
          .div(titulo="Habilidad adaptativa")
            p Reorganiza redes neuronales para responder a nuevos desafíos. Ejemplo: una persona ciega desarrolla áreas cerebrales más activas en audición o tacto.
    
          .div(titulo="Crea y elimina conexiones (poda sináptica)")
            p Las sinapsis se fortalecen o se debilitan según el uso. En el aula, la práctica constante refuerza habilidades; la falta de uso las debilita.
    
          .div(titulo="Consolida vínculos existentes")
            p La repetición y la significación fortalecen conexiones previas, mejorando la retención y comprensión. Actividades como el repaso activo o el aprendizaje multisensorial lo potencian.

    h2(data-aos="fade-left") Aprendizaje y neuroplasticidad
    p.mb-5 A continuación, se presenta un video que explora el vínculo entre aprendizaje y neuroplasticidad, abordando cómo el desarrollo cerebral, la experiencia y los estímulos del entorno moldean la capacidad de aprender y recordar a lo largo de la vida.

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/9cqLwqWDCzs?si=F1b2M6SlLRnGqFf9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    h2(data-aos="fade-left") Introducción a los mecanismos funcionales de la neuroplasticidad
    p.mb-5 Los hallazgos de Lee (2024) permiten afirmar que incluso los procesos de aprendizaje más complejos, como la formación de la memoria explícita, se basan en mecanismos de plasticidad sináptica. Esta capacidad del cerebro para reorganizar sus conexiones neuronales —añadiendo nuevas y eliminando las que no son necesarias— es esencial para que podamos aprender, adaptarnos y desarrollarnos. A continuación, se detallan los principales mecanismos mediante los cuales la neuroplasticidad interviene en el aprendizaje:

    .row.justify-content-center.align-items-stretch.mb-4
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-8.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/19.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Creación de nuevas rutas neuronales
              p.mb-0 Cada vez que aprendemos algo nuevo, el cerebro establece nuevas conexiones entre neuronas, facilitando la codificación y recuperación de la información. (Lee, 2024).

      .col-lg-6.mb-3.mb-lg-0
        .bg-color-8.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/20.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Fortalecimiento sináptico
              p.mb-0 La repetición y la práctica refuerzan las sinapsis, consolidando el conocimiento adquirido. 

    .row.justify-content-center.align-items-stretch.mb-5
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-8.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/21.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Adaptación funcional
              p.mb-0 Ante desafíos cognitivos o cambios en el entorno, el cerebro puede redistribuir funciones entre diferentes áreas, optimizando el rendimiento.
      .col-lg-6.mb-3.mb-lg-0
        .bg-color-8.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/22.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Recuperación y compensación
              p.mb-0 En casos de daño cerebral o dificultades de aprendizaje, la neuroplasticidad permite que otras regiones compensen las funciones afectadas.
    
    h2(data-aos="fade-left").mb-5 Neuroplasticidad como base del aprendizaje significativo

    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/23.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p(data-aos="fade-left") La neuroplasticidad no solo permite que el cerebro se adapte a nuevas situaciones, sino que también mantiene su capacidad de transformación a lo largo de toda la vida. Esta propiedad facilita el aprendizaje continuo, independientemente de la edad, y promueve estrategias educativas más inclusivas y personalizadas.
    
        .bg-color-6.p-4(data-aos="fade-left")
          p.mb-0 Lee (2024) destaca que “cada estudiante puede responder de forma única a los estímulos educativos, lo que da paso a metodologías personalizadas y mucho más eficaces, centradas en las características individuales del aprendiz”. Además, la plasticidad neuronal refuerza la resiliencia cognitiva, permitiendo que el cerebro se reajuste frente a errores, dificultades o cambios en el entorno sin detener el aprendizaje.
    
    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/24.svg", style="max-width: 90px").mx-auto
          .col-lg.text-white
            p.mb-0 Esta capacidad también sustenta el aprendizaje significativo, ya que “las experiencias que generan una implicación emocional positiva tienden a consolidarse más profundamente en la memoria” (Lee, 2024).



    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/122878?page=34 " target="_blank" rel="noopener noreferrer") Mora, F. (2017). Neuroeducación: solo se puede aprender aquello que se ama: ( ed.). Difusora Larousse - Alianza Editorial.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.escritosdepsicologia.es/importancia-de-la-plasticidad-cerebral/ " target="_blank" rel="noopener noreferrer") Escritos de Psicología. (s.f.). La importancia de la plasticidad cerebral en el aprendizaje y salud. 


            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=9j7c2DvtUNY" target="_blank" rel="noopener noreferrer") Sinapsis EMP. (2024, 29 de marzo). ¿Qué es la neuroplasticidad? [Vídeo]. YouTube.  



          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
