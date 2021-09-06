<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row(data-aos="fade-left")
      .col-lg-6.mb-5
        p Las terminales portuarias de carga desempeñan un papel esencial en la red internacional de transporte, que es al mismo tiempo uno de los mayores promotores para beneficio de la globalización. Aquí se presenta información sobre los términos básicos, los servicios que ofrecen los terminales de carga, los operadores portuarios y los tarifarios, con el fin de preparar el terreno para el desempeño de las funciones que se describen en cada punto, las operaciones y los tipos de equipamiento usados en las terminales; luego se abordan las definiciones de varios indicadores de diseño y rendimiento de las operaciones portuarias; y, por último, se ofrece una visión general de la infraestructura portuaria.
        p.mb-6 Se tiene la certeza de que estos saberes posibilitarán aún más el alcance de metas dentro del programa Técnico laboral en operaciones portuarias.

      .col-lg-6
        figure.mb-5
          img(src="@/assets/tema1/img-intro.svg", alt="Texto que describa la imagen")

    //-.h5.text-center.mb-4 ¡BIENVENIDO!
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
    p.mb-5 Para la elaboración de este componente, se abordaron varios autores conocidos en operación portuaria, de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido de que el conocimiento es social y, por lo tanto, es para ser usado por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos aquellos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de las #[strong operaciones de comercio exterior.]

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
