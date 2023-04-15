# CURSO HTML5

## ¿Qué es HTML?
HTML (HyperText Markup Language), es un lenguaje de etiquetas o marcado, donde estructuramos nuestros sitios o aplicaciones web, este es un lenguaje base.

## Sintaxis HTML5
HTML es un lenguaje de marcado, donde estructuramos toda la información que llevara nuestro sitio web o aplicación web, por información hacemos referencia a párrafos, títulos, textos, imágenes, videos y más.

Todo el código HTML se escribe con etiquetas, estas etiquetas tienen un proposito, dentro o en medio de las etiquetas va el contenido. Existen etiquetas para textos, imagenes, videos, etc.. Cada una de estas tiene un proposito. Ejemplo:

````
<nombreEtiqueta>
    Contenido de la etiqueta
</nombreEtiqueta>
````

>**NOTA**: Existen etiquetas HTML que no necesitan ser cerradas estas se denominan Selft-closing. No requieren la etiqueta de cierre, pero se pueden cerrar de la siguiente forma.
````
<nombreEtiqueta />

<br />
````

## Como empezamos
> Crea una carpeta donde crearas los archivos de tu proyecto, el nombre debe ser identificable sobre que se tratar.

> Crea un archivo nuevo y como extención (.html) esta es la extención de los archivos donde se escribe código HTML.

> Abre tu carpeta o archivo en un editor de texto para que lo puedas editar.

> Y Abre el archivo desde el navegador para que puedas ir viendo lo que hace el código HTML que se esta escribiendo.

## Caracteristicas de las Etiquetas HTML

**Atributos**
Los atributos nos sirven para dar caracteristicas especiales a las etiquetas. Siempre van en la etiqueta de apertura.

Existen dos atributos los cuales podemos habilitar o asignar a cada etiqueta HTML que son el (id) y (class)

> (id) sirve para darle una identificación unica al elemento que le asignemos este atributo. El nombre que le asignemos al elemento no debe repertirse en el documento HTML. Esto podria ocacionar problemas o conflictos al manipularlos con CSS o Javascript

> (class) sirve para manipular las propiedades del elemento HTML con CSS y Javascript. Este se puede repetir tantas veces sea necesario, o desee utilizar en diversos elementos ya que no necesariamente debe ser el mismo elemento HTML.


## Estructura basica de un documento HTML
````
<!DOCTYPE html><!-- Indica que el contenido del documento es HTML -->
<html lang="en">
<!-- Etiqueta que define donde empieza el código HTML, considerado elemento de nivel superior  -->
<!-- Su atributo (lang) es para indicar al navegador que el contenido de la pagína sera en el idioma que se indique. -->
<head><!--Define los metadatos de nuestro documento HTML-->
    <meta charset="UTF-8"> <!-- Permite que podamos usar caracteres especiales en nuestros documentos HTML -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"><!-- Para diseño adaptable a dispositibos -->
    <title>Document</title><!--Define el titulo de la pestaña del navegador-->
</head>
<body><!-- Va todo el contenido, información, estructura -->
    
</body>
</html>
````

## Etiquetas HTML

### Comentarios en HTML
Los comentarios sirven para dejar notas para otros desarrolladores, o tu yo del futuro. En HTML como en todos los lenguajes de programación existen los comentarios. Estos tambien sirven para documentar lo que hace el código.

````
<!-- Esto seria un comentario en HTML  -->
````

### Heading
> Las etiquetas (h) representan encabezados o titúlos de las secciones o partes de nuestro documento. Estos se deben utilizar basados en la semantica HTML.

> Solo deberia haber un (h1) por documento HTML. Porque este define el titulo principal de toda la pagina, de que se va hablar en el contenido del documento, definiendo las palabras claves de la pagína web.

> Los (h2, h3, h4, h5, h6) se usan como subtitulos de la pagina por ende estos se pueden repetir cuantas veces sea necesario.

````
<h1>Hola soy un encabezado H1</h1>
<h2>Hola soy un encabezado H2</h2>
<h3>Hola soy un encabezado H3</h3>
<h4>Hola soy un encabezado H4</h4>
<h5>Hola soy un encabezado H5</h5>
<h6>Hola soy un encabezado H6</h6>
````

### Texts

> (p) Esta etiqueta sirve para definir parrafos.
````
<p>Hola mundo</p>
````

> (em) Esta etiqueta sirve para dar enfasis en el texto que envuelve semanticamente. Pone en cursiva o italica la letra.
````
<em>Da enfasis al texto</em>
````

> (i) Esta etiqueta sirve para transformar en cursiva o italica la letra. Pero sin la semantica que otorga la etiqueta anterior.
````
<i>Texto en cursiva o italica</i>
````

> (span) Esta etiqueta sirve para darle estilos a un elemento, o como contenedor de elementos (inline) o en linea, lo que significa que no hacen salto de linea.
````
<span>Contenido</span>
````

> (mark) Esta etiqueta sirve para resaltar el texto por su relevancia.
````
<mark>Texto resaltado</mark>
````

> (b) Esta etiqueta no tiene significado semantico. Solo formatea el texto en negritas.
````
<b>Texto en negrita</b>
````

> (strong) Esta etiqueta formatea el texto en negritas y a su vez le da importancia. Se puede utilizar para incorporar palabras claves de la pagina.
````
<strong>Texto en negrita y con importancia</strong>
````

> (u) Esta etiqueta nos sirve para subrayar el texto.
````
<u>Texto subrayado</u>
````

> (small) Esta etiqueta que tiene importancia semantica, define que un texto no es tan relevante, y para hacerlo, hace el texto mas pequeño.
````
<small>Texto sin mucha importancia y mas pequeño</small>
````

> (s) Esta etiqueta define que el texto es irrelevante, y lo tacha
````
<s>Texto irrelevante y tachado</s>
````

> (cite) Esta etiqueta nos sirve para citar un proyecto crativo (Libro, pelicula, etc), y el contenido se pondra en letra cursiva o italica. Esta etiqueta tiene importancia semantica.
````
<cite>proyecto crativo, y el contenido se pondra en letra cursiva o italica</cite>
````

> (sup) Esta etiqueta representa un superindice. Un numero al cuadrado, o al cubo
````
Representa un superindice X<sup>4</sup>
````
> (sub) Esta etiqueta representa un subindice. Un numero al cuadrado, o al cubo
````
Representa un subindice X<sub>3</sub>
````

> (br) Esta etiqueta genera un salto de line y es (self-closing)
````
<p> Genera un salto de <br> de linea y es (selft-closing)</p>
````

> (abbr) Esta etiqueta Sirve para abreviar palaras
````
<abbr title="Kilometros">KM</abbr>
````

### links
> (a) Esta etiqueta para crear enlaces. En su atributo (href) escribimos la dirección a la cual nos dirige, y el contenido de la etiqueta es un texto o contenido representativo. Puede contener texto, imagenes y otras etiquetas HTML.
````
<a href="google.com">Ir a Google</a>
````
> El mismo atributo (href) se puede utilizar para algo mas que enlazar paginas y enlaces.
````
<!-- Se habilita el enviar un correo en el computador -->
<a href="mailto:hola@correo.com">Enviar mail</a>
````
> El atributo (_target) es de objetivo
````
<!-- Se habilita el enviar un correo en el computador -->
<a href="mailto:hola@correo.com">Enviar mail</a>
````

### images
> (img) Es la etiqueta que utilizamos para adjuntar imagenes en los documentos HTML.
> Esta etiqueta por defecto trae dos atributos.
> (src) = al source o lugar donde se almacena la imagen.
> (alt) = a un texto alternativo por si la imagen no se encuentra o no puede cargar y tambien por el CEO para posicionar la imagen y la web.
````
<img src="" alt="No hay ninguna imagen">
````

### content
Las etiquetas de contenido son usadas para agrupar contenido dentro de ellas, tienen importancia semántica y pueden definir secciones, pies de página, menus de navegación.

> (nav) Esta etiqueta define que es una sección de navegación
````
<nav>
    <a href="./">Inicio</a>
    <a href=""#>Blog</a>
    <a href="#">Contacto</a>
</nav>
````

> (section) Esta etiqueta define una seccion en un documento HTML
````
<section>
    <h2>Somos nosotros</h2>
    <p>Lorem ipsum dolor sit amet consectetur.</p>
</section>
````

> (div) Esta etiqueta sirve para agrupar contenido que den un sentido, pero no es semantico 
````
<div>
    <h2>Somos nosotros</h2>
    <p>Lorem ipsum dolor sit amet consectetur.</p>
</div>
````

> (header) Esta etiqueta define un encabezado en HTML puede ser de secciones o de la pagina web
````
<header>
    <nav>
        <a href="./">Inicio</a>
        <a href=""#>Blog</a>
        <a href="#">Contacto</a>
    </nav>
</header>
````

> (main) Esta etiqueta define el contenido principal del documento HTML al igual que el h1 solo debe haber 1 por documento.
````
<main>
    <h2>Somos nosotros</h2>
    <p>Lorem ipsum dolor sit amet consectetur.</p>
</main>
````

> (footer) Esta etiqueta define el pie de una sección o de una página.
````
<footer>
    <h2>Copyright</h2>
    <p>Derechos reservados &copy;</p>
</footer>
````

> (aside) Esta etiqueta define una sección relacionada con el contenido del documento HTML (barra lateral)
````
<aside>
    <h2>Nuestros Articulos</h2>
    <div>
        <img src="" alt="Articulo">
        <h3>Nombre del articulo</h3>
    </div>
</aside>
````

> (article) Esta etiqueta define una seccion independiente del contenido, puede existir por si misma (articulo blog, rvista, periodico, etc)
````
<article>
    <h2>Casa en tucuman</h2>
        <img src="" alt="Articulo">
    <div>
        <p>texto ....</p>
    </div>
    <a href="#">Ver más</a>
</article>
````

### Elementos en linea y en bloque
Todos los elementos o etiquetas HTML poseen una propiedad (display) por defecto cada uno de estos. Esta propiedad puede ser (inline) o (block). Aunque existen otros valores para esta misma propiedad.

Referencia ([https://developer.mozilla.org/es/docs/Web/HTML/Inline_elements])
````
<a href="#">Inicio</a>
<a href="#">Contacto</a>
<a href="#">Texto mas grande que el anterior</a>
````
> El (a) por defecto viene con (inline) como valor del display, lo que significa que si tenemos varios de ellos uno al debajo del otro estos en el navegador se posicionaran uno al lado del otro y solo ocuparan el espacio que ocupe su contenido.

Referencia ([https://developer.mozilla.org/es/docs/Web/HTML/Block-level_elements])
````
<p>hola</p>
<p>hola</p>
````
> A diferencia del (a) el elemento (p) tiene un display (block) lo que significa que ocupara todo el bloque o espacio disponible y el elemento que este justo debajo de este se presentara en el navegador con un salto de linea.


## Listas

### Ordenadas
Se les llaman ordenadas porque llevan un ornde. Al lado aparece el numero que ocupa en la lista
````
<!-- Listas ordenadas -->
<h2>Marvel</h2>
<ol>
    <li>Advengers</li>
    <li>Iron Man</li>
    <li>Hulk</li>
    <li>THOR</li>
    <li>Capitan America</li>
</ol>
````

## Desordenadas
Esta igual se colocan en lista pero se coloca una biñeta (punto negro) sin numeracion.

````
<!-- Listas desrodenadas -->
<h2>Compras</h2>
<ul>
    <li>Leche</li>
    <li>Harina</li>
    <li>Pan</li>
    <li>Aceite</li>
</ul>
````

## Tablas
Para usar tablas en HTML se utiliza la etiqueta <table></table>
````
<tr></tr> <!-- Son las filas -->
<th></th> <!-- Definen el valor que ira en la columna -->
<td></td> <!-- Definen los valores de cada columna -->
<thead></thead> <!-- Definen la cabecera de la tabla -->
<tbody></tbody> <!-- Define el cuerpo de la tabla -->
<tfoot></tfoot> <!-- Define el pie de la tabla -->
<caption></caption> <!-- Para ponerle nombre a la tabla -->
````
> Ejemplo de una tabla
````
<table>
    <caption>Nombre de la tabla</caption>
    <tr>
        <th>Nombre</th>
        <th>Apellido</th>
        <th>Edad</th>
        <th>Sexo</th>
    </tr>
    <tr>
        <td>Francisco</td>
        <td>Perez</td>
        <td>50</td>
        <td>Masculino</td>
    </tr>
    
</table>
````


## Formularios
Para definir un formulario se utiliza la etiqueta (form) por defecto este viene con el atributo (action) este se utiliza para indicar la url en donde se enviara la información que este formulario contenga.

````
    <form action=""></form>
````

Dentro de este se utilizan otras etiquetas HTML para obtener los datos. Como las etiqueta (input), (label), (select), (textarea)

> Ejemplo input


````
<input type="text" name="" id="">
<input type="email" id="email" required>
<input type="password" id="password" require placeholder="*********">
<input type="color">
<input type="date">
<label>
    <input type="radio" name="turno"> Matutino
</label>
<label>
    <input type="checkbox">Acepto los terminos y condiciones
</label>

<!--Entrada de datos. El atributo  -->
<!--(type) define el tipo de input -->
<!--(name) el nombre del input -->
<!--(id) El identificador unico -->
<!--(value) El valor por defecto que tendra el input -->
<!--(placeholder) Para indicar o decir que informacion queremos  que obtenga el input-->
<!-- (maxlength) Atributo para indicar la cantidad maxima de caracteres permitidos -->
<!-- (minlength) Atributo para indicar la cantidad minima de caracteres -->
````

> Ejemplo label


````
<label for="nombre">Nombre</label>
<!-- Sirve para identificar el un input -->
<!--El atributo (for) sirve para conectarlo con el atributo (id) del input -->
````

> Ejemplo select

````
<select>
    <option value="valor">Mexico</option>
    <option>Chile</option>
    <option selected>Venezuela</option>
</select>
````

> Ejemplo textarea

````
<textarea name="comment" id="comment" cols="30" rows="10"></textarea>
````