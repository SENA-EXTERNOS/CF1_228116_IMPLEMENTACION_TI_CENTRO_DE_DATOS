<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Esquema organizativo 
      
    p.txt-inicial Dentro de un esquema organizativo se contempla la infraestructura tecnológica, así como sus características y los modelos de gestión desde una red de datos; a continuación, se describen dichos conceptos. 
      
    h3.mb-5 Infraestructura tecnológica

    .row.mb-5 
      .col-lg-8
        p La infraestructura tecnológica hace referencia a todo componente físico que la conforma: distribución espacial, eléctrica, red de datos, equipos de cómputo, servidores, terminales IP y todo aquello que pueda ser integrado al sistema como cámaras de vigilancia, sensores y demás. Conocer la infraestructura tecnológica permite identificar cada elemento como parte de un todo y garantizar que con su funcionamiento no se presentarán novedades para los usuarios finales.
        p A continuación, se identifica la clasificación de los dispositivos de la infraestructura tecnológica en un centro de datos: 
      .col-lg-4
        img.img-a.img-t(data-aos="fade-left")(src="@/assets/curso/temas/img1-tema1.png", alt="alt")


    .titulo-sexto.color-secundario.mb-3
      h5 Tabla 1
      br
      span <em>Clasificación de los dispositivos de la infraestructura tecnológica en un centro de datos. </em>

    .tabla-a.color-acento-botones.mb-5 
      table
        thead
          tr
            th Equipos
            th Comunicación
            th Red

        tbody
          tr
            td Servidores
            td <em>Routers</em>
            td Cableado

          tr
            td Cámaras de seguridad
            td <em>Modems</em>
            td Sistema eléctrico

          tr
            td Terminales IP
            td <em>Switch</em>
            td
          tr
            td Sensores
            td <em>Access Point</em>
            td

          tr
            td UPS
            td <em>Firewall</em>
            td

          tr
            td Planta eléctrica
            td
            td        

    .row.my-5 
      .col-lg-5
        img.img-a.img-t(data-aos="flip-up")(src="@/assets/curso/temas/img-finf-tabla-tema1.png", alt="alt").img-finf-tabla-tema1     
          
      .col-lg-7
        p #[strong  Ejemplo:] en un edificio bancario existe un cuarto exclusivo para ubicar el centro de datos, allí se encuentran dispositivos como: servidores, <i>racks</i> con <i>switch</i>, <i>routers</i>, <em>módems</em>, pantallas, sensores, red eléctrica, cableada, y lo necesario para permitir su funcionamiento. Todos estos componentes integran la infraestructura tecnológica, pero no podemos dejar de lado el edificio como tal; construir un ambiente apropiado para albergar tecnología requiere de conocimientos de normatividad dado que es indispensable velar porque variables como la temperatura, humedad e incluso nivel de acceso, se garanticen en una disponibilidad del 100% 24/7 (24 horas al día por 7 días a la semana). Factores como la altura, volumen, capacidad de carga, hasta el piso, deben ser revisados con detalle y por ello es importante estudiar estos temas a profundidad. 
        p Si desea conocer sobre las características de la infraestructura de red, criterios de dimensión de un <i>data center</i>, criterios de gestión de servidores y modelos de gestión TI, por favor consulte el siguiente material:

        .col-lg-10
          a.anexo.mb-4(:href="obtenerLink('/downloads/anexo_1_Caracteristicas_red.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
                p #[strong Anexo] Características de la infraestructura 

    .row.container.justify-content-around.align-items-center.fondo-red-de-datos-tema1.p-5
          
      h3.mb-5 Red de datos
        
      .row 
        
        .col-lg-7
        
            p Una red de datos no es más que la interconexión física que existe entre varios dispositivos y que permite la transmisión de información de un equipo a otro o a los demás que están conectados; es decir, una red de datos permite el intercambio de información de manera directa utilizando un medio de comunicación. Al momento de hablar con otras personas, se requiere de un medio de comunicación, un emisor y un receptor, ¿verdad? Así mismo funciona una red de datos, el emisor corresponde al equipo #[em host] que desea enviar la información, el medio será cableado, el mismo aire a través de una conexión #[em wifi] y el equipo receptor se convierte en aquel para el cual fue enviado el mensaje inicial. Así bien, las redes de datos se pueden crear entre dos dispositivos a través de un cable cruzado, conectados a través de una conexión wifi, dispositivo <i>bluetooth</i>, infrarrojo o todo aquel que permita el intercambio de datos de un equipo al otro. 
        
        .col-lg-5
            
            figure
                img(data-aos="fade-right")(src="@/assets/curso/temas/img-red-de-datos-tema1.png", alt="alt").img-red-de-datos-tema1
      


    h3.my-5 Modelos de referencia

    .row 
      .col-lg-10.bloque-cajon-color-mod-refer
        .cajon.color-primario.p-4
          p Los protocolos de red generalmente están estructurados en capas, La Organización Internacional para la Estandarización (ISO) ha diseñado el modelo de referencia de Interconexión de Sistemas Abiertos (OSI) que implementa 7 capas según la actividad de la red y cada uno de ellos tiene asociado uno o más protocolos. <em>“Las capas representan las operaciones de transferencia de datos comunes a todos los tipos de transferencias de datos entre las redes de cooperación”.</em>

    p.mb-5 En la siguiente tabla se describen las diferentes capas del modelo OSI:

    .titulo-sexto.color-secundario.mb-3
      h5 Tabla 2
      br
      span <em>Capas del modelo OSI</em>

    .tabla-a.color-acento-botones 
      table
        caption Nota. Elaboración del experto 2022.
        thead
          tr
            th Nro. Capa
            th Comunicación
            th Red
            //th Encabezado 4
            //th Encabezado 5
        tbody
          tr
            td.text-center 7
            td.col2-tabla1-tema1 Aplicación
            td Servicios y aplicaciones que conocemos para realizar la transferencia de datos entre equipos, que podemos utilizar fácilmente desde cualquier ordenador. 

          tr
            td.text-center 6
            td.col2-tabla1-tema1 Presentación
            td Establece un sistema de comunicación que garantice que ambos “leen” el mismo lenguaje, es decir, el sistema que recibe comprende con facilidad la información que le fue enviada a través de la red.

          tr
            td.text-center 5
            td.col2-tabla1-tema1 Sesión
            td Para garantizar que la comunicación en la red se realizará únicamente entre los dos dispositivos señalados y que no habrá posibles pérdidas de datos, se debe entablar una sesión que administre y termine la conexión. Esta capa garantiza la administración entre los sistemas que cooperan. 

          tr
            td.text-center 4
            td.col2-tabla1-tema1 Transporte
            td Permite crear un sistema de envío de datos por paquetes que garantiza que la información enviada será la misma que se recibe en el otro dispositivo en la red. 

          tr
            td.text-center 3
            td.col2-tabla1-tema1 Red
            td Los vínculos permiten crear esos enlaces entre los dispositivos físicos en la red, la red permite que se puedan identificar cada uno de ellos y transferir la información ya sea en la red LAN o en redes externas. 

          tr
            td.text-center 2
            td.col2-tabla1-tema1 Vínculo de datos
            td Una vez se reconoce el componente físico en la red, se deben establecer los sistemas de comunicación entre los que se desea crear una “conexión”, esta capa permite administrar la transferencia de datos a través de la red. 

          tr
            td.text-center 1
            td.col2-tabla1-tema1 Física
            td Corresponde al <em>hardware</em> de red, sus características y operabilidad. Permite identificar el “dispositivo” y reconocerlo en la red. 

    .row.justify-content-center.align-items-center.mb-5           
      .col-lg-10      
        .row.justify-content-evenly.align-items-center.fondo-tarj-anexo-tema4.tarjeta.p-2.mt-5
          .col-auto
            img.img-t(src="@/assets/template/icono-pdf.svg")

          .col-lg-9.my-3
            h4.text-white Anexo
            p.text-white.mb-0 Para conocer más sobre el modelo OSI, el sistema de direccionamiento IP, protocolos de enrutamiento y las características de los sistemas de cableado estructurado, sistemas de almacenamiento y sistemas en la nube, consulte el siguiente material: 
            
          .col-auto
            a.boton.boton--b(:href="obtenerLink('/downloads/anexo_3_Modelo_OSI.pdf')" target="_blank")
              .anexo__texto
              span Descargar
              i.fas.fa-file-download



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
