<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

      
    .row.container.justify-content-around.align-items-center

      .row.fondo-img-tar-introd

        .col-lg-6
            figure
                img(src="@/assets/curso/temas/img-tar-introd.png", alt="alt").img-tar-introd
        
        .col-lg-6
          
            p.txt-tar-introd.p-4 Aprendiz, reciba una cordial bienvenida al componente formativo Implementación de TI y centro de datos. En la actualidad hay grandes avances en la tecnología, lo que ha permitido que equipos servidores que ocupaban un cuarto completo para procesar datos, ahora estén en espacios pequeños, y que a su vez puedan ofrecer varios “servicios” según sea el caso.
    .row.container.justify-content-around.align-items-center.my-5
      .col-lg-8
        p Con los cambios y actualizaciones en los sistemas, especialmente en los equipos de cómputo, servidores y equipos de comunicaciones, se han generado nuevas dinámicas en la administración de los sistemas de información: también, a través de normas y estándares internacionales, se han aplicado buenas prácticas a la hora de construir un espacio dedicado al procesamiento de la información en una compañía; dicho lugar es conocido como un centro de datos o data center y en él se encuentra la infraestructura tecnológica capaz de soportar la demanda de procesamiento de información de la empresa y en la cual se almacenan todos los datos producidos.
        p Le invitamos a visualizar el siguiente video introductorio donde podrá conocer de manera general los temas tratados en este componente formativo:

      .col-lg-4
        
        figure
            img(data-aos="fade-left")(src="@/assets/curso/temas/img-tarj2-introd.png", alt="alt").img-tarj2-introd
    .row.tarjeta.tarjeta--blanca.p-2.p-md-3

        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/R4qxMGJrnvE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

        


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
