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
en el ``<head>`` es para enlazar otro tipo de archivos: css js img para iconos de moviles favicon en los navegadores titulos y las descripciones ceo de paginas. (todo lo que esta en la cabezera se considera metainformacion) {HABLA DE LA PAGINA PERO LOS USUARIOS NO LO VEN } 

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
    todo lo nuevo que vaya saliendo siempre es en Ingles, entonces el Ingles debe ser un exelente compañero tuyo en este maravilloso mundo de la programacion
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

la etiqueta `<pre>` respeta el formateo que tu le estes dando

<hr>
<h2>etiqueta semantica estructurales.</h2>

    nos van ayudar a definir zonas de maquetacion para delimitar areas de secciones ej: cabezera, pie de página,  el contenido principal
    la publicidad el contenido lateral, si lo queremos a 3 columnas a 2 columnas.

    si has usado template de jumbla, wordpres o template que te hayas descargado o en los mismos ejemplos que vienen de codigo frameworks como bootstrap, fundation donde todo su codigo está con divs divs

    ![imagen](/assets/estructura_semantica_html5.jpg). 

el proceso de maquitacion va depender mucho de como queras planificar el diseño  de tus aplicaciones o de tus sitios web