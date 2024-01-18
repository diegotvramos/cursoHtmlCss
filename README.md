# curso de HTML y CSS

**_[link](https://diegotvramos.github.io/cursoHtmlCss/)_**

https://jonmircha.com/index.html el index(es una convencion al archivo principal que carga tu proyecto se llama index .html) esta oculto en la pagina principal de jonmircha.
solo hay un index.

emmet.io https://docs.emmet.io/  es una herramienta que nos va ayudar a escribir codigo de manera rapida. ya viene integrada en VS code

para los atajos de vs code ¿como hiciste ese atajo?
https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf 

extencion _prettier_.

## Introduccion a HTML y su documentacion

>- html = define el contenido
>- css = estilos 
>- js = para la dinamisidad

los navegadores web ya internamente entienden estas tecnologias, ya son Estandares
regido por personas de grandes tecnologias que van delimitando los avances https://www.w3.org/ 

- https://html.spec.whatwg.org/  la documentacion es muy tediosa

https://developer.mozilla.org/es/docs/Web/HTML 

no me gusta recomendar libros por que los libros se vuelven obsoletos por que los cambios son constantes.

lo recomendable es ir a la documentacion, foros 

> https://htmlreference.io/element/a/ esta es muy buena documentacion con ejemplos.

## Estructura basica de un documento html

```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Hola</title>
    </head>
    <body>
        <h1>Hola, este es otro documento html</h1>
        <a href="index.html">Regresar al Index</a>
    </body>
    </html>
```

hipertext: en griego significa NAVEGACION.

**head** 
en el `head` es para enlazar otro tipo de archivos: css js img para iconos de moviles favicon en los navegadores titulos y las descripciones ceo de paginas. (todo lo que esta en la cabezera se considera metainformacion) {HABLA DE LA PAGINA PERO LOS USUARIOS NO LO VEN } 

**BODY**
todo lo que queremos que se vea en la pagina
debes ser ordenado

## comentarios en html

 `ctrl + k +c`

 `ctrl + k +u` descomentar

## etiqueta html y el atributo lang

se refiere al idioma

**lang="es-bo"** dominio de tu pais
dependiendo en el pais en donde estemos el contexto de las palabras puede cambiar

## DOCTYPE html

algunas etiquetas no eran soportadas.

## Atributo Charset

el el juego de caracteres universal
el ingles es el idioma de los negocios la ñ  la dieresis y los asentos no estan soportados
https://desarrolloweb.com/articulos/11.php 

## meta etiqueta viewport

el area donde se visualiza el contenido es el view port
se adapta al ancho del dispositivo

## etiqueta title y (meta descripcion)descripcion**

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

## Tabla periodica de los elementos html

de preferencia no debes tener texto suelto en el body siempre debe estar envuelto en una etiqueta
todo lo nuevo que vaya saliendo siempre es en Ingles, entonces el Ingles debe ser un exelente compañero tuyo en este maravilloso mundo de la programacion.

![imagen](/assets/html-periodic-table.png)

## Encabezados
nos va permitir titularizar nuestro contenido

```html
    <h1 style="background-color: hotpink;">Encabezado de nivel 1 solo puede existir un h1 por documento html</h1>
    <h2>Encabezado de nivel 2</h2>
    <h3>Encabezado de nivel 3</h3>
    <h4>Encabezado de nivel 4</h4>
    <h5>Encabezado de nivel 5</h5>
    <h6>Encabezado de nivel 6</h6>
```

**Por cuestiones de posicionamiento de SEO _en cada documento html debes de tener un solo titulo H1_ CUANDO los algoritmos (claurels) los algoritmos de los buscadores,  van y revisan nuestro codigo html siempre se fijan en el H1**

es buena practica que solo exista un solo H1

## Etiquetas de texto basicas.

```html
    <p>Parrafo</p>
    <b>Negrita</b>
    <i>Italica</i> 
    <u>Subrayado</u> 
    e=mc <sup>2</sup> H <sub>2</sub>O
    <mark>marcatexto</mark>
    <small>letras pequeñas</small>

```

## Etiquetas de texto Semanticas

cuando hacemos una tesis, hacemos referencias a fichas bibliograficas libros mencionas la frace de un autor, citar una frase.

```html
    <p>
        <!-- tiene un significado -->
        <strong>Este texto es importante</strong>. <em>Este texto hace enfacis</em> 
    </p>
    <p>
        <blockquote>Yo solo sé que nada sé</blockquote>
        <cite>Socrates</cite>
    </p>
```
*** 

## Etiquetas de salto

despues de los `h's h1...` ya tienen un salto nativo

```html
    <br>
    <hr> es un salto semantico de contenido
```

https://madebymike.github.io/html5-periodic-table/#strong 


## 19 Etiquetas de formateo

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

```html
    <pre></pre>
```

*** 

## etiqueta semantica estructurales.

nos van ayudar a definir zonas de maquetacion para delimitar areas de secciones ej: cabezera, pie de página,  el contenido principal
la publicidad el contenido lateral, si lo queremos a 3 columnas a 2 columnas.

si has usado template de jumbla, wordpres o template que te hayas descargado o en los mismos ejemplos que vienen de codigo frameworks como bootstrap, fundation donde todo su codigo está con divs divs 

![imagen2](/assets/estructura_semantica_html5.jpg)

el proceso de maquitacion va depender mucho de como queras planificar el diseño  de tus aplicaciones o de tus sitios web

```html
    <div>Es una etiqueta contenedora que no tiene semantica</div>
    <header>header- Cabecera de un sitio web o de una seccion.</header>
    <main>
        main- Define la session  principal del documento. Solo puede existir una etiqueta main por documento
    </main>

    <footer>footer- Representa pie de pagina de un sito web o de una seccion </footer>
    <nav>nav- Representa la navegacion</nav>
    <article>
        article-Representa una seccion Autocontenido(que por si sola se explica)
    </article>
    <aside>
        aside- Representa un contenido complementario o secundario
    </aside>

    <section>
        section- Representa una seccion de contenido generico
    </section>
    <blockquote> eso de la semantica va ser muy subjetivo segun el contenido que vayas definiendo en tu sitio web </blockquote>

    <address>address- representa informacion de contacto</address>

    antes de utilizar una DIV trata de utilizar cualquiera de las etiquetas semanticas anteriores
```

## Etiquetas de bloque VS etiquetas de linea

la mayoria de las etiquetas html van a ser de `NATURALEZA DE BLOQUE O NATURALEZA DE LINEA`
EJE los encabezados son etiquetas de **bloque**, parrafos. y las etiquetas de texto como  (em, strong, bloqu, italic ... bold)

las etiquetas de bloque son __evidiosas__ por que van a ocupar todo el ancho disponible y generan saltos de linea con las etiquetas que tienen de hermanas y las etiquetas de Linea van a ocupar el espacio que requieren

```html
    <div style="background-color: yellow; color: red;"> la etiqueta de bloque por excelencia es la DIV, una etiqueta de bloque es aquella que genera saltos de linea con sus etiquetas
        hermanas
    </div>
    <span style="background-color: greenyellow;">la etiqueta de linea por excelencia es la SPAN (NO TIENE carga semantica) y una etiqueta de linea solo ocupa el espacio necesario
         que tiene su contenido.
    </span>
    <span>
        Hola soy otra SPAN (LAS ETIQUETAS DE LINEA no generan saltos de linea ni arriba ni abajo)
    </span>
```

## Estilos en HTML; estilos CSS en HTML
HAY 3 formas de aplicar estilos en cascada

primera forma: en los atributos de la etiqueta, otra abrir estilos css en la cabecera [ es importante utilizar las clases y en la medida de lo posible evitar ids para los estilos]

```html
    <style></style>
```

## Scripts en HTML
DEBEN IR AL FINAL ANTES DEL CIERRE DE LA ETIQUETA BODY.
LO IDEAL ES QUE ESTÉ EN UN ARCHIVO INDEPENDIENTE.

```html
 <script></script>
```

## imagenes

`SRC= source`. ORIGEN O FUENTE
formatos soportados: jpg, png, gif, svg(es un vector)
la altura y la anchura lo debemos modificar desde el codigo CSS 
```html
    <img src="assets/html-periodic-table.png" width="600" height="400" alt="TABLA" >
```

## vectores SVG 

este tipo de imagenes son en realidad vectores, puedes hacer el logo en ilustrator.
el código en el cual está echo este logo es xml.
la pagina donde puedes descargar iconos SVG es: 

> - https://css.gg/
> - https://www.svgrepo.com/vectors/mechanic/2 es otra pagina

cuando se hace una pagina web ya es mas comun pedirlas en vector

## figuras

recuerdas que en la primaria teniamos libros de historia, geografia, biologia y al pie de esas imagenes decia: fugura 1.1 ciclo del agua,
tambien podemos agregar un video que tenga nota al pie

**alt=** texto alternativo para los scren reader (las personas que no pueden ver)

```html
    <figure>
        <img src="assets/html-periodic-table.png" alt="tabla de los elementos HTML">
        <figcaption>
            tabla de los elementos HTML (es opcional)
        </figcaption>
    </figure>
```

## Listas Ordenadas

las listas tienen atributos {start(comienzo), tipo(a, i, )} lo que hay en un procesador de texto.

```html
    <p>
    <ol start="100">
        <li>Primavera</li>
        <li>Verano</li>
        <li>Otoño</li>
        <li>Invierno</li>
    </ol>
</p>
```

<p>
    <ol start="100">
        <li>Primavera</li>
        <li>Verano</li>
        <li>Otoño</li>
        <li>Invierno</li>
    </ol>
</p>

## Listas Desordenadasç

lo que en un procesador seria las listas con viñetas. la diferencia con las listas ordenadas son las viñetas en ves de numeros.

`<ul type="circle"></ul>` en el type puedes ponerle: circle

```html
    <ul>
        <li>terminar de grabar los fragmentos del curso de HTML</li>
        <li>Editar el video final</li>
        <li>subirlo a youtube</li>
    </ul>
    <ul type="circle">
        <li>terminar de grabar los fragmentos del curso de HTML</li>
        <li>Editar el video final</li>
        <li>subirlo a youtube</li>
    </ul>
    <ul type="square">
        <li>terminar de grabar los fragmentos del curso de HTML</li>
        <li>Editar el video final</li>
        <li>subirlo a youtube</li>
    </ul>
```

## Listas De definicion

necesitamos 2 elementos
dt , dd
tienen una sangria en el navegador, no son tan utilizadas

```html
    <dl>
        <dt>HTML</dt>
        <dd>es un leguaje de marcado que define el contenido de la web</dd>
        <dt>CSS</dt>
        <dd>es un lenguaje de definicion que da estilos al codigo html</dd>
        <dt>JAVASCRIPT</dt>
        <dd>javaScript es el lenguaje de la Web</dd>
    </dl>
```

## tablas

las tablas se utilizaban para maquetar ya hoy existe _grid y grid css_ hoy las tabla se utilizan para tabular datos

colspan-sirve para conbinar celdas en columna.
rowspan- sirve para conbinar celdas en filas

```html
<table>
            <thead>
                <tr>
                    <th colspan="3">Tabla de los santos de atenas</th>
                </tr>
                <tr>
                    <th>Nombre</th>
                    <th>Constelacion</th>
                    <th>tipo</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Ikki</td>
                    <td>Fenix</td>
                    <td>Bronce</td>
                </tr>
                <tr>
                    <td>Mistry</td>
                    <td>Lagarto</td>
                    <td>plata</td>
                </tr>
                <tr>
                    <td>Saga</td>
                    <td>Geminis</td>
                    <td>Dorado</td>
                </tr>
                <tr>
                    <td>Shaina</td>
                    <td rowspan="2">ofiuco</td>
                    <td>plata</td>
                </tr>
                <tr>
                    <td>Odiseo</td>
                    <td>Dorado</td>
                </tr>
                
            </tbody>
            <tfoot>
                <tr>
                    <th colspan="3"><small>Saint seiya fue creado por el creado por Masami Kurumada</small></th>
                </tr>
            </tfoot>
        </table>
```

## enlaces
sirve para anlazar localmente como externamente(los enlaces externos se le debe poner el protocolo HTTP[s] y el dominio)

como estamos en el mismo sitio o en la misma aplicacion se entiende perfectamente que de un enlace a otro pues estemos moviendonos en la misma pestaña que el usuario este consumiendo nuestro contenido pero que pasa con las redes sociales o con los enlaces externos
¿Como hacemos para que el enlace abra en otra pespaña?
debemos hacer uso de un atributo llamado *target="_blank"* es como el objetivo, hacia donde queres que se abra

para aclarar que nustra pagina no forma parte de el otro sitio

```html
    <a href="https://jonmircha.com" target="_blank" rel="nofollow">visita mi sitio web jonmircha.com</a>
```

## enlaces internos

sirve para mostrar la seccion de nuestra pagina usando el simbolo # en el _a href_
https://emojipedia.org/
a parte de que los enlaces nos sirven para generar anclas internas y poder acceder hacia otras rutas paginas, aplicaciones documentos html ya sean externos o internos dentro de nuestro sitio de aplicacion tambien podemos acceder hacia otros protocolos por ejemplo podriamos activar que mediante un enlace se abriera la aplicacion que tenemos predeterminada de correo electronico para poder mandar un mensaje de correo electronico tambien podriamos acceder a marcar un telefono oviamente desde nuestra pc no va funcionar, pero si lo consumimos desde nuestro telefono movil este tipo de protocolos si van a funcionar.

```html
    <a href="index.html#inicio">☝️</a>
```

## enlaces y protocolos especiales

hay algunas aplicaciones que estamos usando ultimamente para comunicarnos como: whatsap, telegram, mesenger que cada uno de esto, tiene sus propios protocolos.
¿como podriamos poner un enlace hacia estos protocolos? 
 vayanse a estas aplicaciones de comunicacion y las mismas les van a dar las urls

>- <a href="https://api.whatsapp.com/send?phone=59176503020&">Enlace hacia WhatsApp</a>
>- ?= signifia que puedes pasar valores     
>- &= significa que le vas a pasar otra variable

```html
        <a href="mailto:diegovillacortaramos@gmail.com">Enlace a correo electronico</a>
        <br>
        <a href="tel:+59175288751">Enlace a telefono</a>
        <br>
        <a href="https://api.whatsapp.com/send?phone=59176503020&Hola">Enlace hacia WhatsApp</a>
```


## Elementos Interactivos 

para mas informacion visiten la pagina: *https://htmlreference.io/element/a/* 
botones, acordeon(details), modales.

```html
    <button onclick="alert(`Hola, haz cliqueado el boton`)">este es un boton</button>
        <br>
<!-- atributo booleano OPEN. si existe en la etiqueta va a plicar su comportamiento -->
        <details open>
            Titulo del acordeon
            <article>
                <h3>contenido del acordeon</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing 
                    elit. Nihil rem impedit dolorum nobis accusamus 
                    quidem tempore, a fuga ex atque illum nulla 
                    accusantium blanditiis nesciunt eos facere 
                    sequi laudantium quia.
                    <img src="/assets/estructura_semantica_html5.jpg" alt="estructura semantica">
                </p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing 
                    elit. Nihil rem impedit dolorum nobis accusamus 
                    quidem tempore, a fuga ex atque illum nulla 
                    accusantium blanditiis nesciunt eos facere 
                    sequi laudantium quia.
                </p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing 
                    elit. Nihil rem impedit dolorum nobis accusamus 
                    quidem tempore, a fuga ex atque illum nulla 
                    accusantium blanditiis nesciunt eos facere 
                    sequi laudantium quia.
                </p>
            </article>
        </details>
        <br>
        <details>
            Titulo del acordeon
            <article>
                <h3>contenido del acordeon</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing 
                    elit. Nihil rem impedit dolorum nobis accusamus 
                    quidem tempore, a fuga ex atque illum nulla 
                    accusantium blanditiis nesciunt eos facere 
                    sequi laudantium quia.
                    <img src="/assets/estructura_semantica_html5.jpg" alt="estructura semantica">
                </p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing 
                    elit. Nihil rem impedit dolorum nobis accusamus 
                    quidem tempore, a fuga ex atque illum nulla 
                    accusantium blanditiis nesciunt eos facere 
                    sequi laudantium quia.
                </p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing 
                    elit. Nihil rem impedit dolorum nobis accusamus 
                    quidem tempore, a fuga ex atque illum nulla 
                    accusantium blanditiis nesciunt eos facere 
                    sequi laudantium quia.
                </p>
            </article>
        </details>
        <br>
        <dialog open>
            Esto es una ventana modal en html
        </dialog>
```


## Audio y Video 

Se estila a que por cada tipo de archivo tengas una carpeta. 
son etiquetas en linea, quiere decir que ocupan el espacio necesario, la visualizacion del reproductor depende del navegador, la funcionalidad es la misma

algunos atributos boolean de la etiqueta audio: autoplay(en mobiles hay que otorgarles permisos es una regla de estandares web),
loop- cuando acabe el track lo va volver a reproducir
muted- comienza el audio muteado en silencio 
preload- cuando cuano el navegador detecta que tu etiqueta audio tiene el atributo preload desde el momento que está cargando la pagina aunque el usuario no le de click al boton de play va empesar a _precargar_ en el caché del navegador

```html
    <audio src="/media/legendary-cinematic-piano-by-ob-13554.mp3" controls preload></audio>
    <br>
    <video src="/media/La luna llena....mp4" controls preload poster="/assets/estructura_semantica_html5.jpg"></video>
    <br>
```

## Iframes (no recomendable)

para hacer carga de informacion externa la mejor estrategia es con programacion de javascript a travez de peticiones via ajax pero cuando tengas la necesidad de incrustar un elemento que venga de otra pagina, imagina que tienes que cargar un PDF con cierta informacion en tu ducumento html esta etiqueta te va servir muy bien

**no todo los sitios se pueden mandar a llamar con Iframes.**
carga la informacion que tiene en el documento: pdf, html.
pdf- son documentos que el navegador interpreta por si solos.

**No es recomendable tener mas de un Iframe por documento html* por que el documento se vuelve lento**

```html
    <iframe src="https://jonmircha.com/" frameborder="1"></iframe>
    <br>
    <iframe src="/media/cheatsheet-a5.pdf" frameborder="0"></iframe>
    <br>
```

## formulario
        
### Elementos de formularios

```html
    <input type="text">
        <br>
        <input type="checkbox">
        <br>
        <!-- solo una opcion -->
        <input type="radio">
        <br>
        <input type="date">
        <br>
        <input type="color">
        <br>
        <input type="button" value="Boton">
        <br>
        <input type="submit">
        <br>
        <input type="reset">
        <br>
        <input type="file">
        <br>
        <input type="file" multiple>
        <br>
        <!-- son inputs que no se van a ver sirven para que  para mandar algun valor 
            hay que activarle el atributo name, es como el nombre de la variable que va tomar cuando se envie la informacion.
        -->
        <input type="hidden" name="idioma" value="es">
        <br>
        <!-- input semantico, en el teclado tactil nos va agregar el arroba o el .com para facilitar la escritura -->
        <input type="email">
        <br>
        <!-- el mobil detecta que es un imput de tipo Numero y el teclado lo pone el teclado numerico  -->
        <input type="number">
        <br>
        <input type="tel">
        <br>
        <input type="password">
        <br>
        <input type="search">

        <br>
        <textarea cols="50" rows="5"></textarea>
        <br>
        <select name="" id="">
            <option value="">HTML</option>
            <option value="">CSS</option>
            <option value="">JS</option>
            <option value="">PHP</option>
            <option value="">PYTHON</option>
        </select>
        <br>
        <!-- Con el atributo Multiple te va permitir poner mas de una opcion. -->
        <select name="" id="" multiple>
            <option value="">HTML</option>
            <option value="">CSS</option>
            <option value="">JS</option>
            <option value="">PHP</option>
            <option value="">PYTHON</option>
        </select>
```

 ## Atributos de inputs y Formularios

 ```html
    <!-- el atributo "readonly" es un atributo boleano simpre va al final de la etiqueta 
        si vas a tener un atributo de solo lectura te combiene desabilitarlo para que se se vea mejor
    -->
    <input type="text"  value="diegoTV" readonly disabled>
    <br>
    <input type="text" placeholder="Escribe tu nombre">
    <br>
 ```

**action** el atributo `action` es hacia donde se va enviar.
**name**- nombre de variable de formulario que se va crear para cada uno de los inputs.
https://jonmircha.com/?usuario=diego&password=1234 
**METODO GET** el metodo GET es el metodo predeterminado de los formularios y va enviar por la URL los valores
**POST**- lo va enviar en las cabezeras del documento lo va enviar (de forma oculta)

https://jonmircha.com/

>- _ya en la practica profecional el envio de los formularios generalmente se controla con programacion javascript e incluso haciendo peticiones con AJAX_ 

el **NAME** si o si debe tener el ID es opcional
al poner el valor usuario tanto en el atributo _FOR_ de la etiqueta LABEL, y el _ID_ de el _INPUT_ estos se vinculan y lo podemos probar haciendo click en el label, y esto automaticamente saltará al input vinculado

**required**- es un atributo booleano nos obliga a completar el campo

**pattern** - es para las expreciones regulares

**title**-  lo usa como mensaje de validacion

>- **Nota**¡ Toda validacion del formulario se debe validar a nivel de programacion en JS idealmente si esa informacion se envia a una base de datos antes de insertar o modificar los datos en el sistema tambien tendria que validarse a lado del servidor(php node, js)!.

```html
    <h4>Formulario de login</h4>
    <form action="https://jonmircha.com/" method="POST" autocomplete="off">
        <label for="usuario">Usuario: </label>
        <input type="text" name="usuario" id="usuario" placeholder="escribe tu usuario" pattern="^[A-Za-z]+$" title="el campo solo acepta letras" required>
        <br>
        <label for="password">password</label>
        <input type="password" name="password" id="password" placeholder="escribe tu password" required>
        <br>
        <input type="submit">
        <br>
        <input type="reset">
    </form>
```

#### Selects, Radios y Checkboxs 

en esta seccion veremos como se envian y como el formulario va mandar en formato de variable los valores de los selects que vienen a ser listas de los radio buttons y de los checkbox de hecho estos elementos te pueden servir para encuestas,

>- si quieres que alguna de las opciones queda cargada por defecto le agregas el atributo *SELECTED*
_LOS RADIO BOTONES_
va servir cuando tu tengas que elegir de diferentes opciones solo una.
el label sirve para acompañar al radio boton.
tanto los Checkboxs como los RadioButtons los valores son como los interuptores {ON || OFF}.
Cuando vayas a tener un grupo de Inputs Radios de donde solamente vas a poder seleccionar una opcion entonces al atributo NAME tiene que ser exactamente igual en los 3

>- checked- es un atributo booleano que nos permite seleccionar predeterminadamente una opcion _LOS CHECKBOXS_ la intencion de los Checkboxs es para que los usuarios puedan seleccionar mas de una.

> __trata de poner valores VALUE="" siempre en ingles para evitar poner acentos (CARACTERES AJENOS AL INGLES)__ puedes no ponerle VALUE ya que el usario al seleccionar automaticamente se va poner en ON

```html
    <form>
        <p>Elige tu idioma:</p>
        <select name="idioma">
            <option value="" selected>Elige una opcion</option>
            <option value="es" >Español</option>
            <option value="en">Ingles</option>
            <option value="fr">Frances</option>
            <option value="it">Italiano</option>
            <option value="pt">Portugues</option>
        </select>
        <p>Elige tu lenguaje de programacion favorito</p>
        <input type="radio" name="lenguaje" id="radio-js" value="js" required>
        <label for="radio-js">javaScript</label>
        <input type="radio" name="lenguaje" id="radio-py" value="py" checked>
        <label for="radio-py">Python</label>
        <input type="radio" name="lenguaje" id="radio-php" value="php">
        <label for="radio-php">php</label>
        <p>Elige tus intereses</p>

        <!-- otra forma de manipular las etiquetas con su respectivo input -->
        <label>
            <input type="checkbox" name="intereses" value="deportes" checked>
            Deportes
        </label>
        <label>
            <input type="checkbox" name="intereses" value="finanzas" checked>
            Finanzas
        </label>
        <label>
            <input type="checkbox" name="intereses" value="salud">
            Salud
        </label>
        <label>
            <input type="checkbox" name="intereses" value="politica">
            Política
        </label>
        <label>
            <input type="checkbox" name="intereses" value="ecologia">
            Ecología
        </label>
        <br>
        <p>
            <label>
                <input type="checkbox" name="terminos" required>
                ¿Aceptas terminos y condiciones?
            </label>
        </p>
        <input type="submit">
        <input type="reset">
    </form>
```

**FORMULARIO DE CONTACTO**

hazme expresiones regulares para que el usuario ingrese correo electrónico en un formulario html. 
```html
    <input type="email" name="email" pattern="[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}" required>
```

para que el formulario funcione vamos a usar un servicio de envio de formulario.
https://formsubmit.co/ 

**si solo hacemos 2ble click en el archivo, estamos abriendo desde el el archivo local(usamos el protocolo FILE) lo que necesitamos es ejecutarlo en un entorno de servidor. por eso instala LIVE SERVER**

```html
    <form action="https://formsubmit.co/00dramos@gmail.com" method="POST">
        <input type="text" name="nombre" placeholder="Escribe tu nombre" pattern="[A-Za-zÁÉÍÓÚáéíóúüÜñÑ\s'-]+" title="Nombre- solo acepta letras y espacios en blanco" required>
        <br>
        <input type="email" name="correo" placeholder="Escribe tu correo" pattern="[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}" title="Formato de correo invalido" required>
        <br>
        <textarea name="comentarios" cols="30" rows="5" required></textarea>
        <input type="submit">
    </form>
```

## Data Attributes

HTML nos permite agregarles atributos que nosotros nos inventamos a las etiquetas como ids nombre etc.
Lo usan mucho frameworks como BOOTSTRAP DATA- ALGO DATA- ALGO, DATA-ALGO.

```html
    <ul>
        <li data-id="1" data-name="spring">Primavera</li>
        <li data-id="2" data-name="summer">Verano</li>
        <li data-id="3" data-name="outumn">Otoño</li>
        <li data-id="4" data-name="winter">Invierno</li>
    </ul
```

## MetaEtiquetas para SEO

Te pueden servir para ayudar al posicionamiento de motores de busqueda es decir para conbribuir al SEO de tus documentos HTML.

**canonical**- tu puedes tener varias URLs para llegar a un mismo contenido pero aca le decis al navegador cual es la IMPORTANTE. Solo pones cuando ya sabes el dominio donde va estar alojada tu sitio web

**FAVICON**- son los iconos pequeños que aparecen en las pestañas de los navegadores, tiene que ser cuadrado perfecto, de preferencia en formato PNG  PUNTO.ICO(viejita).

```html
    <link rel="canonical" href="">
    <link rel="icon" href="/assets/favicon.png">
    <!-- para los dispositivos mobiles -->
    <link rel="apple-touch-icon" href="/assets/favicon.png">
    <!-- podemos cambiar el color de la barra de direcciones para los mobiles-->
    <meta name="theme-color" content="#ff6600">
```


**META ETIQUETAS PARA REDES SOCIALES**

cuando copiamos y pegamos un link a nuestras redes sociales, se nos muestra con una previsualizacion y una pequeña informacion del sitio web.

cada red social tiene herramientas para desarrolladores web para poder interactuar

https://developers.facebook.com/docs/plugins/page-plugin/ 

la mayoria de las redes sociales trabajan con este formato de:
https://ogp.me/ 

y tambien usan sus propias metaEtiquetas, debe ser diferente para cada pagina que tengas

## Accesibilidad Web

son estos mecanismos que a las personas que tienen problemas visuales, ciertas discapacidades, muestra con ciertos contrastes de color, 

>- aria= accesibility,  reach internet accesibilitey aria accesibility rech
>- wai= web accesibility internet.

tiene que entrar como Etica como desarrolladores y diseñadores, el preucuparse por que nuetro codigo sea accesible, es pensar en esas personas que tienen discapacidades visuales, auditivas, interaccion con todas estas tecnologias que se encuentran en la internet, trata de ponerlos, es unmundo.

personas Daltonicas

    los Frameworks como botstrap como fundation, materialize, sementic iai, taywild ya llevan  en sus etiquetas la Accesibilidad

https://www.w3.org/news/2021/first-public-working-draft-w3c-accessibility-guidelines-wcag-3-0/ 

https://html5accessibility.com/ 

https://web.dev/explore/accessible?hl=es-419 

```html
    <a role="link" aria-label="en este enlace econtraras mas informacion sobre las estaciones del año" target="_blank" >MAS INFORMACION</a>

```

