<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0.text-white Técnico laboral en operaciones de comercio exterior 
          
          .h2.text-white Información del programa
          .banner-principal__datos
            ul.text-white
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Técnico laboral en operaciones de comercio exterior 
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 134600
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 2208 Horas
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 15 meses
              li.mb-3.banner-principal__datos__item
                p.h5.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo 
                .banner-principal__datos__item__texto
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe width="560" height="315" src="https://www.youtube.com/embed/ppE5ucJiiFc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                   

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p.mb-3 Bienvenido al programa Técnico laboral en operaciones de comercio exterior, que busca formar aprendices con alta proyección, competentes en las operaciones y actividades del comercio exterior. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p La tecnificación de los procesos logísticos y de operaciones de comercio exterior, mediante el uso de las tecnologías de la información para la cualificación a nivel de técnico laboral o de quienes ejercen tales funciones hace que el desempeño de las actividades sea más eficiente. Por tanto, el SENA está comprometido con la modernización y cualificación del talento humano en aras del cumplimiento de los objetivos y desarrollo del Estado colombiano.
    p En consecuencia, el Plan Nacional de Desarrollo - PND 2018-2022 “Pacto por Colombia, Pacto por la Equidad” establece cuatro objetivos para aprovechar al máximo las ventajas en el acceso a los mercados internacionales, estos son: (1) ampliar la oferta exportable y los mercados de destino; (2) optimizar los procesos de comercio exterior, a través del uso de las herramientas de facilitación del comercio, en línea con el Acuerdo sobre Facilitación del Comercio; (3) incrementar el monto de inversión dirigida a lograr una mayor eficiencia productiva en las empresas; y (4) incentivar el desarrollo de megaproyectos de inversión de alto impacto económico. 
    p Asimismo, el informe de la Organización Mundial del Comercio – OMC (2020) resalta la importancia de crear nuevos conocimientos mediante la invención, para luego ser divulgados utilizando el sistema educativo y su importancia radica en que las políticas orientadas al exterior, permiten a los países acceder a tecnología avanzada mediante la importación de bienes de capital y de la participación en las cadenas de valor mundiales.
    p.mb-0 Por lo anterior, el SENA en su estrategia de redes de conocimiento a través de la Red de Logística y Gestión de la Producción ha diseñado el programa Técnico laboral en operaciones de comercio exterior, el cual forma al aprendiz en actividades aduaneras, portuarias, de logística y transporte, para su posterior vinculación en empresas del sector. Se puede desempeñar en áreas como zonas aduaneras, portuarias y francas, cruces de frontera, así como también en operaciones contempladas en la normativa aduanera. 
 

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a<br> desarrollar

    ul.lista-ul
      li 
        i.lista-ul__vineta
        | Desarrollar la operación de importación y exportación de mercancías según la normativa de comercio exterior.      
      li 
        i.lista-ul__vineta
        | Coordinar el transporte según rutas y medios.
      li 
        i.lista-ul__vineta
        | Calcular costos de operación de acuerdo con métodos.
      li 
        i.lista-ul__vineta
        | Tramitar documentos según la normativa aduanera.
      li 
        i.lista-ul__vineta
        | Identificar la dinámica organizacional del SENA y el rol de la formación profesional integral de acuerdo con su proyecto de vida y el desarrollo profesional.
      li 
        i.lista-ul__vineta
        | Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li 
        i.lista-ul__vineta
        | Ejercer derechos fundamentales del trabajo en el marco de la Constitución Política y los convenios internacionales.
      li 
        i.lista-ul__vineta
        | Generar hábitos saludables de vida, mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li 
        i.lista-ul__vineta
        | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
      li 
        i.lista-ul__vineta
        | Fomentar la cultura emprendedora según habilidades y competencias personales.
      li 
        i.lista-ul__vineta
        | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li 
        i.lista-ul__vineta
        | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li 
        i.lista-ul__vineta
        | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de Referencia para las Lenguas.
      li 
        i.lista-ul__vineta
        | Utilizar herramientas informáticas, de acuerdo con las necesidades de manejo de información.   


  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de <br> ingreso

    ul.lista-ul
      li 
        i.lista-ul__vineta
        | Básica Secundaria, grado 9. Requiere certificación académica.
      li 
        i.lista-ul__vineta
        | No requiere formación para el trabajo y desarrollo humano.
      li 
        i.lista-ul__vineta
        | Edad mínima definida por ley: 16 años. 
      li 
        i.lista-ul__vineta
        | Superar prueba de aptitud y conocimiento. 
      li 
        i.lista-ul__vineta
        | No existe legislación que establezca restricciones de ingreso, a nivel de discapacidad física y cognitiva. 
      li 
        i.lista-ul__vineta
        | Aspectos actitudinales, motivacionales o de interés: responsabilidad, compromiso, honestidad, lealtad, iniciativa, cumplimiento, colaboración, comunicación asertiva, buenas relaciones interpersonales, capacidad de trabajo en equipo, capacidad para la resolución de conflictos, alta capacidad de adaptabilidad, capacidad de trabajo bajo presión, presentación personal acorde con sus funciones, capacidad de redacción de informes técnicos, organización para el manejo de información, seguimiento e interpretación de instrucciones, liderazgo de equipos de trabajo. 




  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso

    p.mb-0 El egresado del programa Técnico laboral en operaciones de comercio exterior estará en capacidad de desempeñarse en funciones relacionadas con el apoyo a la coordinación, supervisión, soporte y gerencia de los procesos de comercio exterior relacionados con la exportación, importación, inspección aduanera, almacenamiento de mercancías nacionales e internacionales; con la integración y uso de tecnologías de la información y la comunicación para la toma de decisiones que permita la racionalización de los recursos de la organización y el cumplimiento de los acuerdos comerciales.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las Tecnologías de la Información y la Comunicación, integradas en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:


    p.p1 -	El instructor - tutor
    p.p1 -	El entorno
    p.p1 -	Las TIC
    p.p1 -	El trabajo colaborativo

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 7. Creditos
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
