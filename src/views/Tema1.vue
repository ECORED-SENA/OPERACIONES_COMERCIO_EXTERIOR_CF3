<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Infraestructura terminales de carga
    p Las terminales de carga se identifican como el agrupamiento de actividades operativas ubicadas en el puerto para facilitar el cambio modal y los servicios portuarios. Están compuestas por una infraestructura especializada, zonas de depósito transitorio y rutas del transporte.
    p.mb-5 Los componentes que caracterizan las terminales son:
    .r-n Componentes de los terminales de carga
    .row(data-aos="fade-left")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-1.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-2.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-3.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-4.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-5.svg")                                        
    .row.mt-0.mb-5(data-aos="fade-left")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-6.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-7.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-8.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-9.svg")
      .col 
        figure.mb-3
          img(src="@/assets/tema1/img-10.svg")  

    p.mb-5 Los tipos de terminales de carga, a nivel comercial, más utilizados son:

    LineaTiempoD.color-primario.mb-5
      .row(numero="1" titulo="Terminales de contenedores")
        p Estos cuentan con espacios para utilización de todos los modelos de contenedores, sin diferenciar el tipo de carga, y proporcionan comunicación entre los modos de transporte.
        p Cuentan con las siguientes zonas:
        .col-md-6.mb-5.mb-md-0
          ul.lista-ul
            li 
              i.ii.fas.fa-caret-square-right
              | Zona de carga y descarga: se encarga de la función de estiba y desestiba de los contenedores en el buque.
            li 
              i.ii.fas.fa-caret-square-right
              | Zona de almacenamiento:  dispone de la mayor parte del espacio en la terminal, aquí los contenedores se organizan de manera que faciliten el proceso de estiba. 
            li 
              i.ii.fas.fa-caret-square-right
              | Zona de recepción y entrega terrestre: está compuesta por puertas terrestres para ingreso de vehículos pesados, funciona para poder recibir mercancías en espacios designados para esta operación logística.
            li 
              i.ii.fas.fa-caret-square-right
              | Zona de conexión interna: garantiza y brinda apoyo al transporte de los contenedores entre el buque y la zona de recepción y entrega terrestre.  Además, aquí se ubican las oficinas de control, parqueaderos, aduanas, talleres de reparación, entre otros.

        .col-md-6.mb-5  
          figure.mb-3
            img(src="@/assets/tema1/img-11.svg") 
        .row.justify-content-around.align-items-center
          .col-md-2.mb-4
            figure.mb-3
              img.img-150(src="@/assets/tema1/img-12.svg")         
          .col-md-9.mb-4              
            p.mb-5 Se conoce como contenedor a la herramienta utilizada para transporte de mercancías, protegiendo la carga, por los diferentes modos que se puedan dar durante el proceso; facilita la manipulación para traslado entre los diferentes medios; hace que resulte más cómodo la carga y descarga en los puertos; cuenta con un sistema de ventilación para la carga y es muy resistente para uso frecuente.

      .row(numero="2" titulo="Terminales de granel sólido")
        p Son los encargados de cargar, descargar, manipular y depositar la carga granel sólido, como trigo, maíz, cebada, cemento, etc., que transportan los buques graneleros especializados en este tipo de productos.  Posee en tierra sistemas de almacenamiento para todas estas necesidades requeridas por la mercancía.  Los equipos básicos que utilizan deben tener tolvas para canalizar materiales y cintas especiales de transporte.

        .col-md-6
          figure
            img(src='@/assets/tema1/img-13.svg')
            
        .col-md-6.mb-4.mb-md-0
          p Para el transporte de los graneles sólidos desde el lugar de su producción hasta la instalación industrial de su procesamiento y distribución, se recorren distancias considerables y las terminales portuarias de exportación e importación constituyen un pequeño eslabón en toda esta cadena. Por ello, se deben conocer los distintos tipos de almacenamiento que existen en una terminal, esto supondrá analizar las distintas cargas que pueda recibir una terminal.
          p El almacenamiento de los productos sólidos obedece a las características del producto, los agentes climatológicos, la resistencia y otros efectos ambientales. Si el producto a almacenar no está organizado en unidades de carga y se puede almacenar suelto, en montones o en grandes depósitos o silos, en naves diáfanas, se dice que el almacenamiento es a granel. 

      

      .row(numero="3" titulo="Terminales de granel líquido")
        p Son especializados en la carga, principalmente, para el sector de hidrocarburos, productos alimenticios, químicos y gases licuados. Para su carga y descarga, utilizan bombas centrífugas, mediante un perímetro de tuberías de acero, de acuerdo con el volumen de los productos que se encargan del líquido hasta los tanques de almacenamiento.

        .col-md-6.mb-5.mb-md-0
          p Las funciones más frecuentes que se presentan en este tipo de terminales son: 
          ul.lista-ul
            li.mb-4 
              i.ii.fas.fa-caret-square-right
              | Recibo de mercancía en buques a granel líquido.            
            li.mb-4  
              i.ii.fas.fa-caret-square-right
              | Almacenamiento en tanques.            
            li.mb-4  
              i.ii.fas.fa-caret-square-right
              | Trasiego de la carga entre buques y tanques.
          p Las estructuras de los tanques de almacenamiento son en forma cilíndrica, diseñadas para preservar líquidos o gases, a presión ambiente, usados en las industrias del petróleo y la química, mayormente para este tipo de productos.


        .col-md-6.mb-5  
          figure.mb-3
            img(src="@/assets/tema1/img-14.svg") 

        p.mb-3 Las características reguladas para los tanques de almacenamiento son las siguientes:
        figure.mb-3
          img(src="@/assets/tema1/img-15.svg")         
        p Finalmente, los detalles de volumen, acabado, y protección interna son de acuerdo con las necesidades del usuario final.

    p.mb-5 Se pueden encontrar otros tipos de terminales como: terminales de carga general; terminales de buques Ro-Ro; terminales de gas; encargados de procesamiento, recepción, embarque y desembarque de mercancías; disponen de infraestructura especializada para el modo requerido, de acuerdo con los productos.
    .row.justify-content-around.align-items-center 
      .col-md-5.mb-5 
        .cajon-b.color-primario.p-3.mb-5
          p No se pueden dejar de lado los terminales aéreos, que, como su nombre lo indica, transportan mercancías y productos en naves por vía aérea y ofrecen los mismos servicios de procesamiento, recepción, embarque y desembarque de mercancías a nivel nacional e internacional. La operación de este modo es segura y cumple con normativas requeridas por las autoridades, ofreciendo beneficios como reducción de costos, tiempo de entrega, distribución de los productos y conectividad con los modos de transporte terrestre, marítimo y ferroviario.
      .col-md-6.mb-5     
        p.r-n2 Terminales aéreos  
        figure.mb-3
          img(src="@/assets/tema1/img-16.svg")   

    p.mb-5 El transporte aéreo de carga es utilizado por la mayoría de los sectores y cadenas de distribución, ya sea para transporte de mercancías a comercializar en el campo internacional o envío de muestras y/o documentos relacionados con el comercio exterior. Cumple con algunas características que le hacen llamativo, entre estas:

    .row.justify-content-around.align-items-center
      .col-lg-8.col-md-10
        p.r-n2 Características del transporte aéreo
        figure.mb-3
          img(src="@/assets/tema1/img-17-.svg")  

    .row.justify-content-around.align-items-center
      p Entre los inconvenientes que presenta, se encuentran las restricciones y limitaciones técnicas, debido a las dimensiones de puertas y bodegas de los aviones, en cuanto a tamaño y peso de los productos, además de que es un transporte costoso, lo que no lo hace favorable para productos de bajo costo, como las materias primas.
      .col-lg-6
        p.mb-5 Se puede concluir que las mercancías que se transportan por modo aéreo pueden ser de cualquier tipo, teniendo en cuenta las siguientes consideraciones.
        ul.lista-ul        
          li.mb-4 
            i.ii.fas.fa-caret-square-right
            | Valor elevado, que permita pagar costos.

          li.mb-4 
            i.ii.fas.fa-caret-square-right
            | Urgente su envío por ser perecederas, muestras previo contrato, elementos médicos o de ayuda humanitaria.
          li.mb-4 
            i.ii.fas.fa-caret-square-right
            | No sobrepasar tamaños y pesos predeterminados por limitaciones de los aviones.
          li.mb-4 
            i.ii.fas.fa-caret-square-right
            | Principalmente, productos terminados, listos para su consumo final.

      .col-lg-6
        figure.mb-3
          img(src="@/assets/tema1/img-18.svg") 
    separador
    #t_1_1.titulo-segundo
      h2 1.1 Operadores portuarios 
    p.mb-5 Un puerto se conoce como un espacio geográfico con infraestructura e instalaciones ubicadas en la ribera u orilla de un río o del mar, que cumple ciertos requerimientos físicos necesarios para realizar operaciones de carga y descarga o de embarque y desembarque.

    .row.mb-5.justify-content-around.align-items-center(data-aos="fade-left")
      .col-lg-8.col-md-10
        p.r-n2 Los puertos
        figure.mb-3
          img(src="@/assets/tema1/img-19.svg")  

    p La resolución Nº 0000850 de 2017 del Ministerio de transporte “reglamenta las condiciones técnicas de operación de los puertos marítimos y se dictan otras disposiciones”, donde se compila reglamentación general para acceso a los servicios, condiciones técnicas de operación, protocolos y procedimientos, infraestructura y acceso, servicios generales a las naves, pasajeros y carga, operaciones en puertos, control de riesgos del medio ambiente, documentación y autoridades.
    p Los puertos deben cumplir las siguientes condiciones:
    p.r-n2 Condiciones que se exigen a los puertos

    .row.align-items-center.img-c.mb-5
      .col-md-4.mx-0.px-0.col-lg-2
        figure.mb-3
          img(src="@/assets/tema1/img-20.svg")         
      .col-md-4.mx-0.px-0.col-lg-2
        figure.mb-3
          img(src="@/assets/tema1/img-21.svg")
      .col-md-4.mx-0.px-0.col-lg-2
        figure.mb-3
          img(src="@/assets/tema1/img-22.svg")
      .col-md-4.mx-0.px-0.col-lg-2
        figure.mb-3
          img(src="@/assets/tema1/img-23.svg")
      .col-md-4.mx-0.px-0.col-lg-2
        figure.mb-3
          img(src="@/assets/tema1/img-24.svg")      

    p La función principal de un puerto es el traslado de mercancías para un tráfico comercial a través de aduanas y la legalización de importaciones y exportaciones, generando liquidación de impuestos decretados.
    p.mb-5 En los puertos se encuentran zonas destinadas y específicas para llevar a cabo operaciones en relación con el transporte de la mercancía, es así como se tiene:
    h5 Zonas básicas en los puertos
    p  En los puertos, se encuentran zonas destinadas a acciones relacionadas con el transporte de mercancía. Estas son:   
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul bb")
      .row(titulo="Zona asignada a buques")
        .col-md-6.mb-4.mb-md-0
          p Permite acceso a las embarcaciones, ofreciendo seguridad y protección adecuadas durante la permanencia y operación en el puerto.  Entre los servicios de seguridad, está la señalización, el dragado, los espacios para cargue o descargue, entre otros.
        .col-md-6
          figure
            img(src='@/assets/tema1/img-30.svg')
      div(titulo="Zona terrestre")
        .row
          .col-md-6.mb-4.mb-md-0
            p Superficie especial para la operación de la mercancía; ofrece servicio de almacenaje provisional y espacio para organización de los flujos terrestre-marítimo.
          .col-md-6
            figure
              img(src='@/assets/tema1/img-31.svg')
      div(titulo="Zona de evacuación")
        .row
          .col-md-6.mb-4.mb-md-0
            p Dedicada únicamente al transporte terrestre, donde se enmarcan las vías de ingreso al puerto desde las principales carreteras, para su acceso y utilización.
          .col-md-6
            figure
              img(src='@/assets/tema1/img-32.svg')
         
    p Los servicios portuarios deben prestar todas aquellas funciones de asistencia en la seguridad, calidad, eficiencia y regularidad para la correcta utilización de los puertos, fomentando el movimiento de la carga.
    p.mb-5 Entre los principales servicios básicos portuarios se encuentran los siguientes:
    .row.justify-content-around.align-items-center.img-c.mb-5
      .col-lg-8.col-md-10
        p.r-n2 Condiciones que se exigen a los puertos     
        figure.mb-3
          img(src="@/assets/tema1/img-33-.svg")  

    .row
      .col-md-6.mb-5  
        figure.mb-3
          img(src="@/assets/tema1/img-34.svg")     
      .col-md-6.mb-5.mb-md-0
        p Servicios portuarios realizados a través de empresas externas
        ul.lista-ul
          li 
            i.ii.fas.fa-caret-square-right
            | Empresa estibadora: se encarga de la operación de manipulación de mercancías y regularmente deben estar autorizados por la autoridad portuaria para uso de espacio cerca al muelle. 
          li 
            i.ii.fas.fa-caret-square-right
            | Empresa de prácticos: equipo humano con práctica en el puerto, delegados en trasladar el buque por infraestructura para permitir entrada y salida al puerto en condiciones de seguridad. 
          li 
            i.ii.fas.fa-caret-square-right
            | Empresa de remolcadores: empresa con permiso para efectuar labores de remolque, poseedoras de equipos de gran potencia, con la capacidad de mover buques de gran peso. 
          li 
            i.ii.fas.fa-caret-square-right
            | Empresa de amarre: son empresas delegadas por la autoridad portuaria para cumplir con la operación de amarre de la carga.
          li 
            i.ii.fas.fa-caret-square-right
            | Empresa de retirada de residuos: son las empresas que ofrecen el servicio de retiro de residuos sólidos y aguas residuales originados por los buques, seleccionándolos para su proceso de reciclaje.

    p.mb-5 En sí mismos, los servicios portuarios deben garantizar a sus usuarios y clientes la prestación de un servicio de calidad, donde prime la atención al cliente, así como a la mercancía que se deposita en el puerto para su transporte; además, deben demostrar competencia en la prestación de dicho servicio, ofreciendo garantía y transparencia en la asistencia y responsabilidad ante posibles siniestros que pudieran presentarse en el lugar.

    .bloque-texto-a.color-secundario.pp-0.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-8
          .bloque-texto-a__texto.p-4
            h5 Para tener en cuenta...
            p.mb-2 La SuperTransporte, en su página web, dedica un espacio para el sector portuario, donde se resuelven todas las preguntas que se presentan referentes al manejo, servicio y normatividad. Se invita a su consulta: 
            
            a.bb(:href="('https://www.supertransporte.gov.co/index.php/faq-delegatura-de-puertos/')" target="_blank")
              p.bb https://www.supertransporte.gov.co/index.php/faq-delegatura-de-puertos/
            br
            | En cuanto a la normativa, recurrentemente se actualizan las leyes y normas. Para la ley 1242 de 2008, la última modificación presenta fecha de Julio 23 -2021
        .col-lg-4.mb-4.mb-lg-0
          figure.mb-3
            img(src="@/assets/tema1/img-35.svg")  
        
    .tarjeta.color-secundario.p-3.mb-5.px-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-2.m-2
          img(src="@/assets/tema1/img-36.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              p.texto-blanco Ley 1242 de 2008, por el cual se establece el Código Nacional de Navegación y Actividades Portuarias Fluviales y se dictan otras disposiciones.
              p.texto-blanco Se le invita a consultar el enlace, donde encontrará esta legislación y normatividad nacional referente a las actividades portuarias.
 
            .col-sm-auto
              a.boton.color-acento-botones(:href="('http://www.secretariasenado.gov.co/senado/basedoc/ley_1242_2008.html')" target="_blank")
                span Ver
                i.fas.fa-link
    separador
    #t_1_2.titulo-segundo
      h2 1.2 Normativa ambiental
    .row
      .col-md-6.mb-5.mb-md-0
        p La legislación colombiana en el tema ambiental es extensa y posee gran cubrimiento en diferentes contenidos. No es muy conocida debido a que su divulgación no ha sido la más adecuada. Es importante saber que se modifica y se actualiza en cualquier momento.  A continuación, se relaciona la normativa para prevenir la contaminación de los buques. MARPOL es el principal convenio existente creado para la prevención de la contaminación del medio marino por los buques.
      .col-md-6.mb-5  
        figure.mb-3
          img(src="@/assets/tema1/img-37.svg")     
    .row.justify-content-around.align-items-center
      .col-11
        .bloque-texto-a.color-secundario.pp-0.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8
              .bloque-texto-a__texto.p-4
                
                p.mb-2 El Convenio #[strong MARPOL] fue adoptado el 2 de noviembre de 1973 en la sede de la OMI. El Protocolo de 1978 se adoptó en respuesta al gran número de accidentes de buques tanque ocurridos entre 1976 y 1977. Habida cuenta de que el Convenio MARPOL 1973 aún no había entrado en vigor, el Protocolo de 1978, relativo al Convenio MARPOL, absorbió el convenio original. El nuevo instrumento entró en vigor el 2 de octubre de 1983. En 1997, se adoptó un protocolo para introducir enmiendas en el convenio y se añadió un nuevo Anexo VI, que entró en vigor el 19 de mayo de 2005. A lo largo de los años, el Convenio MARPOL ha sido objeto de diversas actualizaciones, mediante la incorporación de enmiendas.
            .col-lg-4.mb-4.mb-lg-0
              figure.mb-3
                img(src="@/assets/tema1/img-38.svg")  
    .row.justify-content-around.align-items-center
      .col-lg-6.mb-5 
        a.anexo.mb-4.mb-lg-0(href="https://en.wikipedia.org/wiki/Main_Page" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto.mb-0
            h5.mb-0 Enlace web. 
            p.mb-0 Convenio MARPOL
    p.mb-5 En el convenio MARPOL, se relacionan 6 reglas, mediante anexos, las cuales tienen el propósito de prevenir y reducir la contaminación ocasionada por los buques, derivada de las operaciones normales y accidentalidad. Estos son:
    .r-n2.mb-3 Reglas para prevenir y reducir la contaminación por causa de buques
    figure.mb-3
            img(src="@/assets/tema1/img-39.svg")  
    separador
    #t_1_3.titulo-segundo
      h2 1.3 Tarifarios terminales portuarios
    p Las tarifas están vigiladas, inspeccionadas y controladas por la Superintendencia de Transporte y son de dominio público. Son actualizadas permanentemente y publicadas en su página web. Aquí se encuentran tarifas en los siguientes ítems, de acuerdo con los servicios requeridos: 
    .row.mb-5
      .col-lg-6 
        figure.mb-3
            img(src="@/assets/tema1/img-40.svg")  
      .col-lg-6 
        .r-n2.mb-3 Ítems tarifarios, según servicios
        ul.lista-ul
          li 
            i.iii.fas.fa-caret-square-right
            | Muellaje
          li 
            i.iii.fas.fa-caret-square-right
            | Uso de instalaciones portuarias a la carga
          li 
            i.iii.fas.fa-caret-square-right
            | Uso de instalaciones al operador portuario marítimo
          li 
            i.iii.fas.fa-caret-square-right
            | Uso de instalaciones al operador portuario terrestre
          li 
            i.iii.fas.fa-caret-square-right
            | Uso de instalaciones al operador portuario remolcadores
          li 
            i.iii.fas.fa-caret-square-right
            | Uso de instalaciones al operador portuario piloto
          li 
            i.iii.fas.fa-caret-square-right
            | Almacenaje
            br
            ul.lista-ul
              li 
                i.iii.fas.fa-check
                | Carga general normal
              li 
                i.iii.fas.fa-check
                | Contenedores llenos
              li 
                i.iii.fas.fa-check
                | Contenedores vacíos
              li 
                i.iii.fas.fa-check
                | Vehículos
          li 
            i.iii.fas.fa-caret-square-right
            | Almacenaje carga transbordo
          li 
            i.iii.fas.fa-caret-square-right
            | Servicio de conexión, desconexión 
          li 
            i.iii.fas.fa-caret-square-right
            | Recargos
          li 
            i.iii.fas.fa-caret-square-right
            | Descuentos

    .tarjeta.color-secundario.p-3.mb-5.px-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-2.m-2
          img(src="@/assets/tema1/img-36.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              p.texto-blanco Se le invita a consultar la página de la Superintendencia de Transporte, del Ministerio del Transporte, donde puede encontrar las tarifas de las sociedades portuarias para el servicio público que rigen para el año 2021.
 
            .col-sm-auto
              a.boton.color-acento-botones(:href="('https://www.supertransporte.gov.co/index.php/superintendencia-delegada-de-puertos/tarifas-sociedades-portuarias-y-fluviales/')" target="_blank")
                span Ver
                i.fas.fa-link


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

<style lang="sass" scoped></style>
