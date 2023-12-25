# curso de HTML y CSS

https://jonmircha.com/index.html el index(es una convencion al archivo principal que carga tu proyecto se llama index .html) esta oculto en la pagina principal de jonmircha.
solo hay un index.

emmet.io https://docs.emmet.io/  es una herramienta que nos va ayudar a escribir codigo de manera rapida. ya viene integrada en VS code

para los atajos de vs code ¿como hiciste ese atajo?
https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf 

extencion _prettier_.


<h2>Introduccion a HTML y su documentacion</h2>
html = define el contenido
css = estilos 
js = para la dinamisidad

los navegadores web ya internamente entienden estas tecnologias, ya son Estandares
regido por personas de grandes tecnologias que van delimitando los avances https://www.w3.org/ 

- https://html.spec.whatwg.org/  la documentacion es muy tediosa

https://developer.mozilla.org/es/docs/Web/HTML 

no me gusta recomendar libros por que los libros se vuelven obsoletos por que los cambios son constantes.

lo recomendable es ir a la documentacion, foros 

> https://htmlreference.io/element/a/ esta es muy buena documentacion con ejemplos.

<h2>Estructura basica de un documento html</h2>
hipertext: en griego significa NAVEGACION.

*head* 
en el ``<head>`</head>`` es para enlazar otro tipo de archivos: css js img para iconos de moviles favicon en los navegadores titulos y las descripciones ceo de paginas. (todo lo que esta en la cabezera se considera metainformacion) {HABLA DE LA PAGINA PERO LOS USUARIOS NO LO VEN } 

*BODY*
todo lo que queremos que se vea en la pagina
debes ser ordenado
<H2>comentarios en html</H2>

 `ctrl + k +c`

``ctrl + k +u`` descomentar
<h2>etiqueta html y el atributo lang</h2>

se refiere al idioma

lang="es-bo" dominio de tu pais
dependiendo en el pais en donde estemos el contexto de las palabras puede cambiar

<H2>DOCTYPE html</H2>

algunas etiquetas no eran soportadas.
<H2>Atributo Charset</H2>

el el juego de caracteres universal
el ingles es el idioma de los negocios la ñ  la dieresis y los asentos no estan soportados
https://desarrolloweb.com/articulos/11.php 

<h2>meta etiqueta viewport</h2>

el area donde se visualiza el contenido es el view port
se adapta al ancho del dispositivo

<h2> **etiqueta title y (meta descripcion)descripcion** </h2>
nos sirve para el posicionamiento
titulo  y una meta descripcion SEO 
gogle hace un sublistado dentro de tu dominio
cada documento html **tenga un titulo y una meta descripcion diferente**

tiene mucha importancia a nivel de posicionamiento en buscadores SEO.
title entre 55 y 65 caracteres 
METADESCRIPCION no mas de 165 caracteres.

HOME,
SECCION,
CONTACTO.

cuando tu sitio web comienze a generar SEO, posicionamiento en los motores de busqueda
debe estar con un titulo y una meta descripcion (cada documento html)

<h2>Tabla periodica de los elementos html</h2>

<p>de preferencia no debes tener texto suelto en el body siempre debe estar envuelto en una etiqueta
    todo lo nuevo que vaya saliendo siempre es en Ingles, entonces el Ingles debe ser un exelente compañero tuyo en este maravilloso mundo de la programacion.

![imagen](/assets/html-periodic-table.png)

</p>

<h2>Encabezados</h2>
nos va permitir titularizar nuestro contenido

**Por cuestiones de posicionamiento de SEO _en cada documento html debes de tener un solo titulo H1_ CUANDO los algoritmos (claurels) los algoritmos de los buscadores,  van y revisan nuestro codigo html siempre se fijan en el H1**

es buena practica que solo exista un solo H1

<H2>Etiquetas de texto basicas.</H2>

`<p></p>`
> Palabras en: <b>Negrita</b>, <i>Italica</i>, <u>Subrayado</u>, e=mc <sup>2</sup>, H <sub>2</sub>O , <mark>marcatexto</mark>
> <small>letras pequeñas</small>

<h2>Etiquetas de texto Semanticas</h2>
cuando hacemos una tesis, hacemos referencias a fichas bibliograficas libros mencionas la frace de un autor, citar una frase 
b¡
<hr>
<h2>Etiquetas de salto</h2>

despues de los h's ya tienen un salto nativo

`<br>`
`<hr>` es un salto semantico de contenido

https://madebymike.github.io/html5-periodic-table/#strong 


<h2>19 Etiquetas de formateo</h2>

            ´<pre>`
                Tareas por hacer
            -HTML
                - terminar de grabar las secciones de este curso.
                - Editar  en un solo video.
            -CSS.
                -comenzar a grabar secciones CSS.
                -Editar en un solo video.
            </pre>`

la etiqueta ``<pre></pre>`` respeta el formateo que tu le estes dando

<hr>
<h2>etiqueta semantica estructurales.</h2>

    nos van ayudar a definir zonas de maquetacion para delimitar areas de secciones ej: cabezera, pie de página,  el contenido principal
    la publicidad el contenido lateral, si lo queremos a 3 columnas a 2 columnas.

    si has usado template de jumbla, wordpres o template que te hayas descargado o en los mismos ejemplos que vienen de codigo frameworks como bootstrap, fundation donde todo su codigo está con divs divs 

![imagen2](/assets/estructura_semantica_html5.jpg)


el proceso de maquitacion va depender mucho de como queras planificar el diseño  de tus aplicaciones o de tus sitios web
<h2>Etiquetas de bloque VS etiquetas de linea</h2>
la mayoria de las etiquetas html van a ser de NATURALEZA DE BLOQUE O NATURALEZA DE LINEA
EJE los encabezados son etiquetas de bloque, parrafos. y las etiquetas de texto como  (em, strong, bloqu, italic ... bold)

las etiquetas de bloque son evidiosas por que van a ocupar todo el ancho disponible y generan saltos de linea con las etiquetas que tienen de hermanas y las etiquetas de Linea van a ocupar el espacio que requieren

<h2>Scripts en HTML</h2>
DEBEN IR AL FINAL ANTES DEL CIERRE DE LA ETIQUETA BODY.
LO IDEAL ES QUE ESTÉ EN UN ARCHIVO INDEPENDIENTE.

SRC= source. ORIGEN O FUENTE
formatos soportados: jpg, png, gif, svg(es un vector)
    la altura y la anchura lo debemos modificar desde el codigo CSS 
<h2>vectores SVG</h2>
este tipo de imagenes son en realidad vectores, puedes hacer el logo en ilustrator.
el código en el cual está echo este logo es xml.
la pagina donde puedes descargar iconos SVG es: 

> - https://css.gg/
> - https://www.svgrepo.com/vectors/mechanic/2 es otra pagina

cuando se hace una pagina web ya es mas comun pedirlas en vector

<h2>figuras</h2>

recuerdas que en la primaria teniamos libros de historia, geografia, biologia y al pie de esas imagenes decia: fugura 1.1 ciclo del agua,
tambien podemos agregar un video que tenga nota al pie

alt= texto alternativo para los scren reader (las personas que no pueden ver)

<h2>Listas Ordenadas</h2>
las listas tienen atributos {start(comienzo), tipo(a, i, )} lo que hay en un procesador de texto.
<p>
    <ol start="100">
        <li>Primavera</li>
        <li>Verano</li>
        <li>Otoño</li>
        <li>Invierno</li>
    </ol>
</p>

<h2>Listas Desordenadas</h2>
lo que en un procesador seria las listas con viñetas. la diferencia con las listas ordenadas son las viñetas en ves de numeros.

`<ul type="circle"></ul>` en el type puedes ponerle: circle

<h2>Listas De definicion</h2>
necesitamos 2 elementos
dt , dd
tienen una sangria en el navegador, no son tan utilizadas

<h2>tablas</h2>

las tablas se utilizaban para maquetar ya hoy existe _grid y grid css_ hoy las tabla se utilizan para tabular datos

colspan-sirve para conbinar celdas en columna.
rowspan- sirve para conbinar celdas en filas

<h2>enlaces</h2>
sirve para anlazar localmente como externamente(los enlaces externos se le debe poner el protocolo HTTP[s] y el dominio)

como estamos en el mismo sitio o en la misma aplicacion se entiende perfectamente que de un enlace a otro pues estemos moviendonos en la misma pestaña que el usuario este consumiendo nuestro contenido pero que pasa con las redes sociales o con los enlaces externos
¿Como hacemos para que el enlace abra en otra pespaña?
debemos hacer uso de un atributo llamado *target="_blank"* es como el objetivo, hacia donde queres que se abra

para aclarar que nustra pagina no forma parte de el otro sitio

<h2>enlaces internos</h2>

sirve para mostrar la seccion de nuestra pagina usando el simbolo # en el _a href_
https://emojipedia.org/
a parte de que los enlaces nos sirven para generar anclas internas y poder acceder hacia otras rutas paginas, aplicaciones documentos html ya sean externos o internos dentro de nuestro sitio de aplicacion tambien podemos acceder hacia otros protocolos por ejemplo podriamos activar que mediante un enlace se abriera la aplicacion que tenemos predeterminada de correo electronico para poder mandar un mensaje de correo electronico tambien podriamos acceder a marcar un telefono oviamente desde nuestra pc no va funcionar, pero si lo consumimos desde nuestro telefono movil este tipo de protocolos si van a funcionar.

<h2>enlaces y protocolos especiales</h2>

hay algunas aplicaciones que estamos usando ultimamente para comunicarnos como: whatsap, telegram, mesenger que cada uno de esto, tiene sus propios protocolos.
¿como podriamos poner un enlace hacia estos protocolos? 
 vayanse a estas aplicaciones de comunicacion y las mismas les van a dar las urls

>- <a href="https://api.whatsapp.com/send?phone=59176503020&">Enlace hacia WhatsApp</a>
>- ?= signifia que puedes pasar valores     
>- &= significa que le vas a pasar otra variable


<h2 id="elementos-interactivos">Elementos Interactivos</h2>

para mas informacion visiten la pagina: *https://htmlreference.io/element/a/* 
botones, acordeon(details), modales.


<h2>Audio y Video</h2>

Se estila a que por cada tipo de archivo tengas una carpeta. 
son etiquetas en linea, quiere decir que ocupan el espacio necesario, la visualizacion del reproductor depende del navegador, la funcionalidad es la misma

algunos atributos boolean de la etiqueta audio: autoplay(en mobiles hay que otorgarles permisos es una regla de estandares web),
loop- cuando acabe el track lo va volver a reproducir
muted- comienza el audio muteado en silencio 
preload- cuando cuano el navegador detecta que tu etiqueta audio tiene el atributo preload desde el momento que está cargando la pagina aunque el usuario no le de click al boton de play va empesar a _precargar_ en el caché del navegador


<h2>Iframes (no recomendable)</h2>

para hacer carga de informacion externa la mejor estrategia es con programacion de javascript a travez de peticiones via ajax pero cuando tengas la necesidad de incrustar un elemento que venga de otra pagina, imagina que tienes que cargar un PDF con cierta informacion en tu ducumento html esta etiqueta te va servir muy bien

*no todo los sitios se pueden mandar a llamar con Iframes.*
carga la informacion que tiene en el documento: pdf, html.
pdf- son documentos que el navegador interpreta por si solos.

*No es recomendable tener mas de un Iframe por documento html* por que el documento se vuelve lento