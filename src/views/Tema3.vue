<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Documentación técnica

    .row.justify-content-center.align-items-center
      .col-lg-auto.pt-lg-0.pt-md-4
        img.img-a.img-t(src='@/assets/curso/temas/25.png' alt='')
      .col.pt-lg-0.pt-md-4
        p.mb-0 La documentación técnica es una herramienta de carácter superior en el proceso de instalación y mantenimiento del cableado estructurado, ya que facilita la organización, el seguimiento y el cumplimiento de los estándares de calidad y normativos. Además, asegura que cualquier técnico o ingeniero que trabaje en el sistema pueda interpretar y dar continuidad al proyecto. Este apartado cubre los elementos necesarios para la creación de documentación precisa y completa, que será necesario en la ejecución y en el mantenimiento a largo plazo de la instalación.
      .col-lg-auto.pt-lg-0.pt-md-4
        img.img-a.img-t(src='@/assets/curso/temas/26.png' alt='')  
      
    Separador 
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Planos y diagramas

    p.mb-5 Los planos y diagramas constituyen el primer nivel de documentación técnica y ofrecen una representación gráfica del sistema de cableado estructurado. Estos documentos son menester tanto en la fase de planificación como en la ejecución y el mantenimiento de la instalación.


    .row.bg4.align-items-center.mb-5.pb-3
      .px-lg-5.px-4
        .row.justify-content-center
          .col-lg-8      
            .titulo-sexto.color-acento-botones
              h5 Figura 2.
              span Clasificación de documentación técnica
            
            .mb-2
              img.img-a.img-t(src='@/assets/curso/temas/27.svg' alt='La Figura 2 se denomina «Clasificación de documentación técnica» y presenta la funcionalidad principal de los planos y diagramas.') 
            figcaption Fuente: OIT, 2024. 

    .row.justify-content-center.mb-4   
      .col-lg-9.my-lg-0.my-3
        AcordionA(tipo="a" clase-tarjeta="tarjeta bg3")
          div(titulo="Planos de distribución ")
            p Muestran la disposición física de los cables, puntos de conexión, paneles de parcheo (patch panels) y dispositivos finales en el área de trabajo. Permiten una visualización clara de las rutas de los cables y la ubicación de los puntos de acceso, lo que facilita la instalación y evita errores de distribución. Estos planos también son útiles para identificar posibles puntos de interferencia o colisiones con otras instalaciones.
          div(titulo="Diagramas de conexión ")
            p Estos diagramas detallan la interconexión de cada componente dentro del sistema de cableado estructurado. Especifican las conexiones entre los cables y los equipos, mostrando cómo se enlazan los elementos de la red y las posiciones de los puertos en los paneles de parcheo y los equipos de red. También incluyen información sobre la asignación de colores para el cableado y otros aspectos técnicos para el ensamblaje de las conexiones. 
          div(titulo="Simbología eléctrica y de telecomunicaciones ")
            p La correcta interpretación de la simbología empleada en los planos y diagramas garantiza la precisión en la instalación. Esta simbología estandarizada permite que todos los técnicos comprendan el diseño independientemente de su experiencia previa con el proyecto. Entre los símbolos más comunes se encuentran los de puntos de acceso de red, paneles de conexión, fuentes de energía, y dispositivos específicos de red.

      .col-lg-3.my-lg-0.my-3
        img.img-a.img-t(src='@/assets/curso/temas/28.png' alt='')                

    .row.justify-content-center
      .col-lg-10
        .row.justify-content-center.bg1.p-4.brad
          .col-lg-auto.j1
            img.img-a.img-t(src='@/assets/curso/temas/29.png' alt='')
          .col.pt-lg-0.pt-md-4.j1
            p.mb-0 El uso de planos y diagramas detallados y correctamente etiquetados es fundamental para evitar errores en la instalación y garantizar un sistema de cableado estructurado ordenado y fácil de mantener.                                                 

    Separador 
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Especificaciones técnicas

    .row.justify-content-center
      .col-lg-9.my-lg-0.my-3
        .row.justify-content-center.align-items-center.mb-4
          .col-lg-auto
            img.img-a.img-t(src='@/assets/curso/temas/30.png' alt='')
          .col.pt-lg-0.pt-md-4
            p.mb-0 Las especificaciones técnicas son documentos que detallan los requisitos de cada componente del sistema, los materiales a utilizar y los estándares de calidad y rendimiento que deben cumplirse en la instalación. Su propósito es asegurar que todos los aspectos técnicos del cableado estructurado sigan criterios de desempeño y normativos específicos.

        TabsC.color-acento-botones.mb-5
          .tarjeta.color-acento-botones--borde.p-4.mb-3(titulo="Requisitos de los materiales")

            p.mb-0 Este documento enumera todos los materiales necesarios para la instalación, incluyendo tipos de cables (con sus respectivas categorías), conectores, paneles de parcheo, canaletas, y soportes, entre otros. Cada material debe cumplir con estándares internacionales (como TIA/EIA o ISO/IEC) y normativas nacionales aplicables. Esto garantiza que los componentes son de alta calidad y adecuados para el entorno de instalación.

          .tarjeta.color-acento-botones--borde.p-4.mb-3(titulo="Especificaciones de rendimiento")

            p.mb-0 Las especificaciones de rendimiento establecen los parámetros mínimos de calidad para cada componente del sistema. Por ejemplo, en el caso de los cables de par trenzado, las especificaciones de rendimiento incluyen valores de atenuación, diafonía (crosstalk) y capacidad de transmisión de datos según la categoría del cable. En cables de fibra óptica, las especificaciones técnicas deben cubrir aspectos como el tipo de fibra, la distancia máxima de transmisión y las características de atenuación óptica.

          .tarjeta.color-acento-botones--borde.p-4.mb-3(titulo="Requisitos de instalación")

            p.mb-0 Las especificaciones técnicas también deben incluir instrucciones sobre el manejo y la instalación de los materiales. Esto abarca detalles como el radio mínimo de curvatura para los cables, la distancia de separación recomendada entre cables de datos y de energía, y el tipo de terminación en los conectores. Estos requisitos aseguran que los materiales y procedimientos utilizados no comprometan el rendimiento del sistema y que el cableado sea durable.                        

      .col-lg-3.my-lg-0.my-3
        img.img-a.img-t(src='@/assets/curso/temas/31.png' alt='')        


    .row.justify-content-center
      .col-lg-10
        .row.justify-content-center.bg1.p-4.brad
          .col-lg-auto.j1
            img.img-a.img-t(src='@/assets/curso/temas/32.png' alt='')
          .col.pt-lg-0.pt-md-4.j1
            p.mb-0 Las especificaciones técnicas sirven de guía para que los técnicos y los supervisores puedan validar que todos los elementos cumplen con los requisitos normativos y de rendimiento antes, durante y después de la instalación. 

    Separador 
    #t_3_3.titulo-segundo.color-acento-contenido
      h2 3.3 Protocolos de verificación
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-auto.pt-lg-0.pt-md-4
        img.img-a.img-t(src='@/assets/curso/temas/33.png' alt='')
      .col
        p.mb-0 Los protocolos de verificación constituyen el conjunto de procedimientos y pruebas que deben llevarse a cabo para garantizar que la instalación cumple con los estándares técnicos y normativos, y para validar que el sistema funcionará adecuadamente una vez puesto en operación. Los protocolos aseguran que la instalación ha sido ejecutada conforme a las especificaciones, brindando un respaldo documentado de la calidad del trabajo realizado.

    .row.justify-content-center.mb-5
      .col-lg-8      
        .titulo-sexto.color-acento-botones
          h5 Figura 3.
          span Procedimientos y pruebas de verificación
        
        .mb-2
          img.img-a.img-t(src='@/assets/curso/temas/34.svg' alt='La Figura 2 se denomina «Clasificación de documentación técnica» y presenta la funcionalidad principal de los planos y diagramas.') 
        figcaption Fuente: OIT, 2024.  

    .row.bg5.align-items-center.mb-5
      .px-lg-5.px-4
        .bgw.brad.p-5.my-5
          SlyderA(tipo="b")
            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Pruebas de continuidad y conexión: 
                p Estas pruebas verifican que todos los cables están conectados correctamente y no presentan cortes, cortocircuitos o empalmes incorrectos. La continuidad asegura que cada punto de conexión funciona adecuadamente y que los datos podrán fluir sin interrupciones en todo el sistema. Se utilizan dispositivos de prueba, como verificadores de continuidad, para realizar estas pruebas de forma precisa. 
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/35.png', alt='')    

            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Pruebas de rendimiento (certificación de cableado): 
                p Este protocolo de verificación implica la realización de pruebas específicas para comprobar que el sistema cumple con los estándares de rendimiento establecidos. Estas pruebas incluyen la medición de parámetros como la atenuación, la pérdida de retorno y la diafonía en cables de par trenzado. En instalaciones de fibra óptica, se mide la atenuación óptica y se verifica la integridad de las conexiones mediante reflectometría en el dominio del tiempo (OTDR).
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/36.png', alt='')   

            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Verificación de cumplimiento normativo: 
                p Una parte fundamental de los protocolos de verificación es asegurar que la instalación cumple con las normativas locales e internacionales, como el RETIE en Colombia. Esto implica revisar que la infraestructura de cableado cumple con los criterios de seguridad, la separación adecuada de cables de energía y de datos, y otros parámetros que eviten posibles fallos eléctricos o riesgos de interferencia.
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/37.png', alt='')   

            .row.justify-content-center
              .col-lg-6.my-2
                h5.mb-4 Elaboración de reportes de verificación: 
                p Al finalizar las pruebas, se debe documentar el resultado en reportes que detallen cada una de las mediciones realizadas, los parámetros evaluados y los valores obtenidos. Este reporte sirve como comprobante de que la instalación ha sido revisada exhaustivamente y es conforme a los requisitos técnicos y normativos. Además, permite llevar un registro que facilita futuras inspecciones y mantenimiento del sistema.
              .col-lg-5.my-2 
                img.img-a.img-t(src='@/assets/curso/temas/38.png', alt='')

    .row.justify-content-center
      .col-lg-10
        .row.justify-content-center.bg1.p-4.brad
          .col-lg-auto.j1
            img.img-a.img-t(src='@/assets/curso/temas/39.png' alt='')
          .col.pt-lg-0.pt-md-4.j1
            p.mb-0 Los protocolos de verificación garantizan que el sistema de cableado estructurado ha sido instalado de acuerdo con las normativas y los estándares de calidad. También proporcionan una base de referencia para el mantenimiento, asegurando que cualquier eventualidad futura pueda ser resuelta con eficiencia.                                                                                   

</template>

<script>
import TabsC from '../bootstrap/TabsC'
import AcordionA from '../bootstrap/AcordionA'
import SlyderA from '../bootstrap/SlyderA'
export default {
  name: 'Tema3',
  components: { TabsC, AcordionA, SlyderA },

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
