<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Cálculo de consumo de materiales e insumos

    .row.mb-5
      .col-lg-6(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-lg-12 
            .cajon.color-primario.p-4.mb-5(data-aos="zoom-in")
              p En el área de confecciones de prendas de vestir, una de las funciones importantes a realizar es la relación de los materiales e insumos y el uso de estos en los procesos productivos necesarios para obtener prendas de vestir. En esta área no se define cuáles insumos llevan los vestuarios, esa actividad se realiza en el área de diseño, también conocida, como investigación y desarrollo.
        
        p El encargado de producción no es quien define las materias primas que llevan las prendas de vestir, ni las cantidades unitarias, sin embargo, dentro de sus funciones está el comprender todo lo relacionado con esta actividad y determinar necesidades para los lotes a producir. Por ese motivo hace parte de sus competencias las siguientes actividades:
      
      .col-lg-6(data-aos="fade-left")
        figure
          img.img-a(src='@/assets/curso/temas/tema_5/img_12.png', alt='Imagen decorativa') 


   
    .row
      .col-lg-6
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema_5/img_13.svg' alt='Imagen decorativa')
          .tarjeta.border--bg1
            .p-4
              p Identificar los materiales e insumos que requieren las prendas, información que se encuentra en las fichas técnicas o en las muestras iniciales. Estas fichas técnicas y muestras iniciales especifican los insumos que se utilizarán en los lotes de producción, así como su disposición en la prenda.

      .col-lg-6
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema_5/img_14.svg' alt='Imagen decorativa')
          .tarjeta.border--bg2
            .p-4
              p Determinar las cantidades de materias primas e insumos que componen los atuendos, y con esta información poder calcular todo lo necesario para confeccionar el lote.

    separador

    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in")
      .h2 5.1  Cálculo de consumo unitario


    .tarjeta--bg2.p-5.mb-5(data-aos="zoom-in")
      .row.justify-content-center.align-items-center
        .col-lg-8.mb-4.mb-lg-0
          p.mb-3 Los cálculos de consumo unitario permiten determinar la cantidad de materiales e insumos que se necesitan para la elaboración de una prenda de vestir, o para prestar un servicio que tenga que ver con el sistema moda. Los resultados pueden ser en unidades de medida, o fracciones de ella.  
          p Desde la elaboración de la muestra inicial, se definen por cada prenda los insumos y materiales necesarios, es así como las fichas técnicas cobran gran importancia en el proceso de producción y los cálculos asociados, dejando registro para corroborar esta información y donde el encargado de producción puede basarse para hacer los respectivos cálculos de los lotes de producción.
        .col-lg-4
          img.imagen-arriba(src='@/assets/curso/temas/tema_5/img_1.svg', alt='Cálculo de consumo unitario') 



    .mt-5.d-flex.mb-5
      .d-flex.flex-wrap.align-items-center.pe-4
        h3.col.px-4.mb-0.text-white.bg-img-blue(style='width: 300px;') Cálculo de consumo de hilo
        img.col-lg.d-flex(src='@/assets/curso/temas/icon-bot.svg').icon-img-blue

    p.mb-5(data-aos="zoom-in") Desde diseño establecen cálculos respecto  al hilo teniendo presente los siguientes aspectos, ver tabla 5:

        .row.mb-5
          .col-lg-4.mb-4.mb-lg-0(data-aos="fade-down-right")
            figure
              img.img-a(src='@/assets/curso/temas/tema_5/img_2.png', alt='Imagen decorativa') 
          .col-lg-8(data-aos="fade-down-left")
            TabsA.color-acento-contenido.mb-5
              .tarjeta.tarjeta--bg4.p-4(titulo="El color")
                h4 El color
                p Se define de acuerdo con el diseño, la silueta, las tendencias, y el propósito del diseñador.
              .tarjeta.tarjeta--bg4.p-4(titulo="El calibre")
                h4 El calibre
                p La resistencia o el grosor, se define de acuerdo con el gramaje o peso de las telas, también según el tipo de costura que se va a hacer con él.
              .tarjeta.tarjeta--bg4.p-4(titulo="La composición")
                h4 La composición
                p Según la tela, pero se tienen muy presente los procesos subsiguientes como lavados fuertes y teñidos. Por ejemplo, si la prenda se va a teñir, la tela debe ser 100% algodón y el hilo también. Algunas veces se confecciona con el hilo del color al que se va a teñir.
              .tarjeta.tarjeta--bg4.p-4(titulo="La ubicación del hilo")
                h4 La ubicación del hilo
                p Hay hilos que van al pespunte (derecho de la tela), otros van al amarre (bobina) y otros en el filete o la puntada de seguridad, de acuerdo con la posición donde va se define que hilo se necesita.  Para calcular la cantidad de hilo requerido para una prenda de vestir y para un lote de producción hay que tener en cuenta las máquinas donde están programadas las operaciones de confección y por ende el tipo de puntada que tiene cada una.
              .tarjeta.tarjeta--bg4.p-4(titulo="La puntada")
                h4 La puntada
                p Dentro de toda la información que viene de diseño, también se hace referencia al tipo de puntada que quieren. Al definir el tipo de puntada entonces se conoce la relación del hilo del pespunte (aguja), hilo de amarre (bobina) y el hilo de cadeneta. Hasta ahí se llevan elementos importantes para el cálculo, máquina, tipo de costura,  posición del hilo, el tipo de tejido, las puntadas por pulgada (# de puntadas que hay en una longitud de una pulgada), y la medida de la longitud de la costura. 

        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Tabla 5.
          span Relación de consumo de hilo
        .tabla-a.color-acento-contenido.mb-5(data-aos="zoom-in") 
          table
            thead
              tr
                th(colspan=5) 
                  h4 DATOS APROXIMADOS A 10 PUNTADAS POR PULGADAS
            tbody
              tr.text-center
                td(colspan=2) Estas dos columnas las puntadas definen el consumo de hilo x cada unidad de medida de costura.
                td Esta columna hace referencia a la relación, por cada unidad de medida de costura, a cuanta longitud de consumo de hilo equivale.	
                td Hace referencia al N° de agujas de cada máquina.
                td Hace relación de consumo, del hilo de arriba (pespunte), con el hilo de abajo (amarre).
              tr.text-center
                td
                  h5 Serie (# de la puntada)	
                td
                  h5 Puntada	
                td
                  h5 Total cm de hilo por cm de costura	
                td
                  h5 Nº de agujas	
                td
                  h5 Relación de hilos (recubridor- aguja - inferior)
              tr.text-center
                td 301	
                td Doble pespunte (plana).	
                td 2.8	
                td 2.8	
                td 1/1
              tr.text-center
                td 401	
                td Cadeneta doble.	
                td 5.5	
                td 2.8
                td 1/3
              tr.text-center
                td 	
                td 	
                td 	
                td 
                td 
              tr.text-center
                td 
                td 
                td 	
                td 
                td 
              

        .row.mb-5
          .col-lg-4(data-aos="fade-down-left")
            figure
              img.img-a(src='@/assets/curso/temas/tema_5/img_3.png', alt='Imagen decorativa') 
          .col-lg-8(data-aos="fade-down-right")
            ul.lista-ul--color.lista-ul--separador
              li 
                .lista-ol--cuadro__vineta
                  span 1
                | Los datos de la tabla anterior se relacionan con un tejido con Incrementar desperdicio, o sea 
              li 
                .lista-ol--cuadro__vineta
                  span 2
                | Hilo que no se utiliza o sobrante, así:

              li.pb-0
                ul.lista-ul--color
                  li.pb-0
                    i.lista-ul__vineta
                    | 7% para máquinas sin corte de hilo (que no trabajen en cadena), máquinas convencionales.
                  li 
                    i.lista-ul__vineta
                    | 3% para máquinas con corta hilo (posicionador y cortador), máquinas electrónicas.

              li 
                .lista-ol--cuadro__vineta
                  span 3
                | Se suma el hilo necesario para cada costura y se divide entre el total de la relación de hilos (columna 5), el resultado se relaciona con cada una de las partes que componen la costura. 


    .tarjeta.mb-5
      .col-md.tarjeta.bg-02.p-5
        .row.justify-content-center.mb-5(data-aos="zoom-in")
          .col-lg-2
            .tarjeta--bg6.p-2
              h5.mb-0.text-center Ejemplo     

        .row.justify-content-center.mb-5(data-aos="zoom-in")
          .col-lg-8.border_1
            p Al sumar la longitud de las costuras de cadeneta doble 401, dio como resultado 5.5 metros, y la relación de hilos que componen la costura es de 1/3; 

            p Entonces:   5.5 / 4 = 1,37

            p Eso significa que mientras se tiene un gasto en el hilo de arriba o pespunte de una cuarta parte del consumo total 1, 37 metros, en el looper o costura de abajo se triplica el  gasto, es decir 4.12 metros de costura. 

            p.mb-0 Por eso interpretando la tabla 5, se ve que para esa costura la relación de hilos es 1/3, mientras la cantidad de hilo que se gasta en el pespunte (costura de arriba) es una parte, la cantidad de hilo para el amarre (costura de abajo), es tres veces esa medida.



    .row.mb-5
      .col-lg-9(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-lg-12 
            .cajon.color-primario.p-4.mb-3(data-aos="zoom-in")
              p.mb-3 Los cálculos para desperdicios es importante tenerlos en cuenta para determinar consumos, partiendo de esto, es importante considerar qué tipo de tecnología de la máquina se va a utilizar, pues con una máquina convencional no se corta el hilo a ras de la tela y las máquinas electrónicas si lo hacen.
              p Luego de conocer la cantidad de hilo para cada tipo de costura, la cantidad total de hilo por prenda y la necesidad de hilo para el lote, se calcula la cantidad de metros que trae cada cono y como resultado se conoce cuántos conos se necesitan. Se debe recordar, revisar el inventario inicial existente para este producto.
          p De acuerdo con la empresa proveedora de hilos, vienen en diferente presentación, y diferentes unidades de medida: metros, yardas y conos, teniendo en cuenta el calibre, vienen en presentación 2.500, 5.000, y 8.000 metros. Generalmente existe en las empresas una tabla dinámica para calcular el consumo de hilo, según los tejidos.

      .col-lg-3(data-aos="fade-left")
        figure
          img.img-a(src='@/assets/curso/temas/tema_5/img_4.svg', alt='Imagen decorativa')





    .row
      .col-lg-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema_5/img_15.svg' alt='Imagen decorativa')
          .tarjeta.avatar-b-1
            .p-4
              p El tipo de puntada.

      .col-lg-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema_5/img_16.svg' alt='Imagen decorativa')
          .tarjeta.avatar-b-2
            .p-4
              p El número de puntadas por pulgada.

      .col-lg-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema_5/img_17.svg' alt='Imagen decorativa')
          .tarjeta.avatar-b-3
            .p-4
              p La máquina y el tipo de tecnología que utiliza.

      .col-lg-3
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema_5/img_18.svg' alt='Imagen decorativa')
          .tarjeta.avatar-b-4
            .p-4
              p El tipo de tejido o tela.


    .tarjeta.tarjeta-descarga.color-secundario.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/temas/tema_1/img_31.svg" alt='Imagen decorativa')
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              h3.mb-1 Anexo. Cálculo de consumo de hilo
              p.text-small Descargue la siguiente plantilla y tabla dinámica de Excel, preconfigurada para realizar el cálculo de consumo de hilo para tejido liviano: 
            .col-sm-auto
              a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download

    .mt-5.d-flex.mb-5
      .d-flex.flex-wrap.align-items-center.pe-4
        h3.col.px-4.mb-0.text-white.bg-img-blue(style='width: 300px;') Cálculo de consumo de tela
        img.col-lg.d-flex(src='@/assets/curso/temas/icon-bot.svg').icon-img-blue

    .row.mb-5
      .col-lg-9(data-aos="fade-right")
        .row.justify-content-center.mb-4
          .col-lg-12 
          p Para calcular la cantidad de tela necesaria para cada prenda o lote de producción, se debe realizar un trazo, que consiste en dibujar los moldes de la prenda sobre la tela o un papel con dimensiones similares. Este trazo se realiza teniendo en cuenta el ancho de la tela y procurando evitar espacios vacíos que generen desperdicio de tela. 
            .cajon.color-primario.p-4.mb-3(data-aos="zoom-in")
              p.mb-3 Los moldes se ubican dentro del ancho de la tela, y la longitud del trazo se calcula dividiéndola entre las tallas dibujadas, obteniendo así el consumo promedio (C.P.).
              .cajon.cajon-interno.align-items-center.text-center
                .border--bg5.p-4.text-center
                  h5.mb-0 Fórmula para hallar el Consumo Promedio
                  p.mb-0 C.P. = Largo del trazo / N° de tallas trazadas.

      .col-lg-3(data-aos="fade-left")
        figure
          img.img-a(src='@/assets/curso/temas/tema_5/img_19.png', alt='Imagen decorativa')


    .tarjeta.mb-5
      .col-md.tarjeta.bg-02.p-5
        .row.justify-content-center.mb-5(data-aos="zoom-in")
          .col-lg-2
            .tarjeta--bg6.p-2
              h5.text-center.mb-0 Ejemplo 

        .row.justify-content-center.mb-5(data-aos="zoom-in")
          .col-lg-8.border_1
            p Largo del trazo 5,18 metros, tallas trazadas: la talla M se dibuja 2 veces, la talla L se dibuja 3 veces, y la talla XL se dibuja 2 veces o sea 7 tallas dibujadas. De acuerdo con los estudios de mercado hay unas tallas que se venden más que otras y por eso se producen más unidades de esas tallas.

            p.mb-0 CP = 5,18 m / 7 
            p CP = 0,74 m. →, cantidad de tela necesaria para una unidad. 
            p m = metros 

            p Se llama consumo promedio porque no es la medida de la talla más pequeña (M), ni de la talla más grande (XL), ya que están dibujadas todas las tallas juntas. 

            p Si se fuera a programar la producción de 70 unidades, se multiplica la tela que necesito para una unidad. 

            p.mb-0 Entonces: 
            p.mb-0 CP= 0.74 m * 70 unidades
            p.mb-0 CP= 51.8 m de tela requeridos

    p.mb-5 A continuación, se ve una imagen del trazo, cuya longitud es de 4 m 91.35 cm, en la cual hay dibujadas 4 tallas. De acuerdo con la fórmula se divide el largo del trazo entre el número de tallas dibujadas. 

    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      span Largo del trazo: 4 m
    figure(data-aos="zoom-in")
      img.img-a(src='@/assets/curso/temas/tema_5/img_9.png', alt='Largo del trazo: 4 m') 
    figcaption(data-aos="zoom-in") Nota. SENA (2021).

    separador

    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in")
      .h2 5.2 Cálculo de consumo por lote

    p.mb-5 Una vez se ha determinado cuántas son las cantidades de insumos y materias primas por una unidad, se multiplica por la cantidad del lote u orden de producción.

    .tarjeta.mb-5
      .col-md.tarjeta.bg-02.p-5
        .row.justify-content-center.mb-5(data-aos="zoom-in")
          .col-lg-2
            .tarjeta--bg6.p-2
              h5.text-center.mb-0 Ejemplo 

        .row.justify-content-center.mb-5(data-aos="zoom-in")
          .col-lg-8.border_1
            p Cada unidad requiere de los siguientes insumos: 

            ul.lista-ul--color
              li
                i.lista-ul__vineta
                | Botones: 9 unidades
              li
                i.lista-ul__vineta
                | Entretela: 0,20 metros
              li
                i.lista-ul__vineta
                | Tela principal: 1,30 metros
              li
                i.lista-ul__vineta
                | Bolsa cubre vestido: 1 unidad
              li
                i.lista-ul__vineta
                | Etiquetas: 2 unidades.

            p.mb-0 Se determinan las necesidades de materiales e insumos, en la ficha de cálculo de consumo por lote visible en la tabla 6. 

    .row.justify-content-center.mb-5(data-aos="zoom-in")
      .col-lg-10
        .titulo-sexto.color-acento-contenido(data-aos="fade-right")
          h5 Tabla 6.
          span Ficha de cálculo de consumo por lote
        .tabla-a.color-acento-contenido.mb-5(data-aos="zoom-in") 
          table
            thead
              tr
                th 
                  h4 O.P. #[.text-danger 98]
                th(colspan=5) 
                  h4.mb-0 Materiales e insumos
                  p Ficha de cálculo de consumo por lote
            tbody
              tr.text-center
                td REF: 1030	
                td Tallas:	
                td S/8/28	
                td M/10/30	
                td L/12/32	
                td XL/14/34
              tr.text-center
                td Cantidad total: #[.text-danger 400]	
                td Cantidad:	
                td 50	
                td 150	
                td 150	
                td 50
              tr.text-center.td_bg1
                td(colspan=2) Artículo	
                td Proveedor
                td Presentación
                td Consumo por Prenda
                td Total necesario
              tr.text-center
                td(colspan=2) Tela principal	
                td Texta	
                td Metros	
                td 1,3	
                td 520
              tr.text-center
                td(colspan=2) Entretela	
                td Texta	
                td Metros	
                td 0,2	
                td 80 
              tr.text-center
                td 	
                td 	
                td 	
                td 	
                td 
                td
              tr.text-center
                td
                td 	
                td 	
                td 	
                td
                td 
              tr.text-center
                td(colspan=2) Autorizó
                td
                td Recibe
                td(colspan=2)

      p.mb-5 De acuerdo con este ejemplo, puede observar que la cantidad total de prendas (camisas), a producir son 400 unidades, esta cifra está en el encabezado, en la primera columna aparece el nombre del insumo o producto del cuál se calcula la cantidad necesaria para realizar el lote, ejemplo: tela, botón, etiqueta. 

        

        .row.mb-5 
          .col-lg-9(data-aos="fade-right")
            .cajon.color-primario.p-4.mb-5(data-aos="zoom-in") 
              p.mb-0 En la segunda columna aparece el nombre del proveedor de este insumo o material a utilizar, en la tercera columna se nombra la unidad de medida con que se comercializa ese material, en la cuarta columna aparece el consumo necesario de cada insumo o material, ese consumo viene definido en la ficha técnica de diseño, para diligenciar la última columna se multiplica el consumo x prenda (cuarta columna), por la cantidad de prendas total, en este caso 400 unidades (1,3 X 400 = 520, 0,2 x 400 = 80, 9 x 400 = 3600, 2 x 400 = 800, 1 x 400 =400) y ahí se tienen calculados la necesidad de materiales e insumos para este lote de camisas de la referencia 1030.
            
          .col-lg-3(data-aos="fade-left")
            figure
              img.img-a(src='@/assets/curso/temas/tema_5/img_10.svg', alt='Imagen decorativa') 

      p.mb-4 En algunas ocasiones y de acuerdo con políticas de la empresa, se podrían incluir valores unitarios y valores totales, de los insumos y las materias primas necesarias.   
      p.mb-5 A continuación, se presenta la tabla 7 donde se incluyen valores unitario y total.
            


    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      h5 Tabla 7.
      span Ficha de cálculo de consumo por lote
    .tabla-a.color-acento-contenido.mb-5(data-aos="zoom-in") 
      table
        thead
          tr
            th 
              h4 O.P. #[.text-danger 98]
            th(colspan=6) 
              h4.mb-0 Materiales e insumos
              p Ficha de cálculo de consumo por lote
        tbody
          tr.text-center
            td REF: #[.text-danger 1030]	
            td Tallas
            td S
            td M	 
            td L 	 
            td XL 	
            td XXL
          tr.text-center
            td CANT: #[.text-danger 400]
            td Cantidad
            td 50 	 
            td 150	
            td 150 	
            td 50 	
            td 0
          tr.text-center.td_bg1
            td ARTÍCULO
            td PROVEEDOR	
            td UNIDAD DE MEDIDA	
            td CONSUMO	 
            td VR/UNIT 	 
            td VR/TOTAL UNITARIO 	
            td VR/TOTAL LOTE
          tr.text-center
            td Tela principal	
            td Texta
            td Texta	
            td Metros	
            td 1,3	
            td 520	
            td 
          tr.text-center
            td Entretela	
            td Texta
            td Texta	
            td Metros	
            td 0,2	
            td 80	
            td 
          tr.text-center
            td  	
            td 	
            td 	
            td 	
            td 	
            td  	
            td  
          tr.text-center
            td 
            td 
            td 
            td 
            td 
            td 	
            td
          tr.text-center
            td 
            td
            td  
            td
            td  
            td
            td
          tr.text-center
            td(colspan=5)
            td 
              h5 TOTAL LOTE	 
            td 
              h5 $ 6.020.000,00 

    p.mb-5(data-aos="zoom-in") Para comprender este ejemplo <b>(Ficha Cálculo de materiales e insumos)</b>, se debe tener presente los cálculos que se realizaron en la ficha de cálculo de consumo por lote, donde se realizó el cálculo de las cantidades necesarias de insumos y materiales para el lote de 400 camisas, ahora en esta tabla se entregan los valores a esos materiales e insumos para cada camisa y valor para todo el lote.

    
    .row
      .col-lg-7(data-aos="fade-right")
        .tarjeta--bg1.p-4.mb-5(data-aos="zoom-in") 
          p.mb-0 En la primera columna aparece el nombre del material o insumo que se va a costear, o sea darle valor monetario a esa cantidad de insumo o materia prima.

        p.mb-3 En la segunda columna aparece el nombre del proveedor de este insumo o material a utilizar, en la tercera columna se nombra la unidad de medida con que se comercializa ese material, en la cuarta columna aparece el consumo necesario de cada insumo o material, en la quinta columna aparece el precio de cada unidad de medida con que se comercializa el insumo, en la sexta columna (VR/TOTAL UNITARIO),  se coloca el resultado de multiplicar la columna 4 (CONSUMO), multiplicado por los valores que aparecen en la columna 5 (VR/UNIT), y en la última columna( VR/TOTAL LOTE), se coloca el resultado de la columna (VR/TOTAL UNITARIO) multiplicado por la cantidad total del lote (CANT:400), así se tiene el costo unitario de una camisa y también se tiene el costo total del lote a producir. 
        p Con esta información se pueden planear también las compras y los presupuestos.
      .col-lg-5(data-aos="fade-left")
        figure
          img.img-a(src='@/assets/curso/temas/tema_5/img_11.png', alt='Imagen decorativa') 




</template>

<script>
export default {
  name: 'Tema5',
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
