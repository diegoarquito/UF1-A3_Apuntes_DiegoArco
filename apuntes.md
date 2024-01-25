<h1>MARKDOWN</H1>

### Subtítulo

Este texto esta en *cursiva*.
Este texto esta en _cursiva_.
Este texto esta en **negrita**
Este texto esta en __negrita__

Este texto esta en _**negrita y cursiva**_

1. Primera opción de menú
2. Segunda opción de menú
3. Tercera opción de menú

* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submenuú (tab)
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú

+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

[Esto es un enlace](https://www.youtube.com/ "Enlace a Youtube")

![Esto es una imagen de un influencer](https://github.com/diegoarquito/ASIX1M4UF1_A3apuntes/blob/main/unnamed.jpg "Título opcional de la imagen")
|Primera Col.| Segunda Col.| 3 col.|
|---------------|:------------:|---------:|
|Col 2 es |Centrada|20$|
|Col 3 es |Derecha|5$|
|Estilo Cebra|Gris|Blanco
|Clase|ASIX1|M4|

-[] Opción A

-[X] Opción B

-[] Opción C</h1>


<h1>CCS</h1>

<h3>¿Qué es?</h3>

Es un lenguaje de diseño gráfico para definir y crear la presentación de un documento estructurado escrito en un lenguaje de marcado.​
<ol>
    <li>Si no queremos afectar a solo uno, sino a todos, lo pondremos en el head, para que todos se vean afectados.
    <li>Para modificar una tabla entero pondremos (style="color:red;"), dentro de head en la tabla. Si quieres definir mejor los bordes ponemos dentro de las comillas (text-align:center) este es para quede centrado, pero podemos poner "right" "left". Si queremos afectar a solo un elemento lo ponemos dentro del codigo de solo una fila.
    <li>Dentro de body para solo afectar a las filas y rellenarlos con color, ponemos (style="background-color: rgb(104, 104, 13);")
</ol>
Para editar colores tenemos que modificar los numeros RGB, signfica rojo verde y azul, mezclando los colores primarios conseguiremos colores. Dentro del head para editar todos los valores ponemos la declarion de style y dentro de style ponemos tbody[color:#0000ff], para que solo afecte al body.
<br>
<br>

Por ejemplo:Para añadir estilos en CSS ponemos la etiqueta style

```
<DOCTYPE html>
<html>
<head>
    <title>color apuntes</title>
    <style="color:red;">
</head>
<body>
<ol>
    <p>Este es un ejemplo de una página web simple.</p> <style="background-color:rgb(104,104,13);">
</ol>
</body>
</html>
```

Esto sirve para ir mas rapido y poder editar de manera mas rapida.

Para poder afectar a elementos particulares, tenemos que definir esa etiqueta, y ponerle un atributo de identificación (id="primerafila"), y para asignar una etiqueta y afectar un identificador ponemos # dentro de head.

Una class es un conjunto de elemntos que agrupamos apra que tengan la mismas caracteristicas, con la etiqueta class (class="textoazul"). Y en el head ponemos #textoazul[color:#0000ff].

```
<DOCTYPE html>
<html>
<head>
    <title>color apuntes</title>>
 <style>
    textozul[color:#00000ff]
</style>
</head>
<body>
<ol>
    Este es un ejemplo de una página web simple. <style="background-color:rgb(104,104,13);">

    Hola <class="textoazul">

</ol>
</body>
</html>
```
Abrimos una carpeta de css y dentro del head ponemos lo siguiente: 
```
<DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="./css/estilos.css" type="text/css">
</style>
</head>
<body>
```
Y en la carpeta css ponemos .TextoRojo{
    color: red #ff0000
} 
Para despues en el body actue segun lo que le hayas puesto.

Concepto de descendiente:
Dejar un espacio entre diferentes elementos. Una misma declaracion podemos separarlos por comas (en el head). El combinador (que se supone que representan un espacio, o mejor dicho uno o más espacios en blanco) combina dos selectores tales que el selector combinado incluye sólo los elementos que coinciden con el segundo selector para los que hay un elemento ancestro que coincide con el primer selector. Los selectores descendientes son similares a selectores hijos , pero que no requieren que la relación entre los elementos coincidentes ser estrictamente entre padres e hijos.

Tambien podemos crear una hoja con estilo css escribiendo nombre.css y desde la propia hoja editar nuestras etuiquetas. Por ejemplo:

body{

    font-family: 'Arial', sans-serif;
    font-size: 16px;
    color: #333;
}
<br>
Y así con las diferentes etiquetas , tambien se pueden añadir mas valores y crear a nuestro gusto

<h1>HTML</h1>
Es el lenguaje estándar utilizado para estructurar y presentar contenido en la web.
<h3>Estructura básica de HTML</h3>

![ejemplohtml](./APUNTS/EJEMPLO%20HTML.png)

Todo documento de HTML sigue una estructura basica, donde pone body nosotros escribiremos nuestro contenido de la página web.En el head añadiremos nuestro documento CSS.

<h3>Encabezado y Párrafo</h3>
Utilizamos etiquetas de encabezado (h1> a h6>) y párrafos (p>). Por ejemplo:
<h3>EJEMPLO H2</h3>
<h4>EJEMPLO H4</h4>
<h5>EJEMPLO H5</h5>
<h6>EJEMPLO H6</h6>

<h3>Listas</h3>
Crea listas ordenadas (ol>) y no ordenadas (ul>). Dentro de estas etiquetas, se utilizan li> para cada elemento de la lista.
<br>
Para la etiqeta ol> para que salgan numeros donde sale la etqiueta li saldran 1, 2, 3, es decir una lista rodenada 

![ejemplool](./APUNTS/EJEMPLOS/ejemplo%20lista.png)

Para la etiqueta ul> para que salgan puntos donde sale la etiqueta li>.

![ejemploul](./APUNTS/EJEMPLOS/lista%20desordenada.jpg)

<h3>Imágenes</h3>

![ejemploimagen](./APUNTS/EJEMPLOS/ejemplo%20imagen%20html.png)
<ul>
    <li>La etiqueta img> se utiliza para insertar una imagen.
    <li>El atributo src especifica la ruta de la imagen, una URL.
    <li>El atributo alt te da un texto alternativo para la imagen, que se mostrará si la imagen no se carga.
</ul>

<h3>Tablas</h3>
Podemos crear tablas utilizando las etiquetas table>, tr> (fila), th> (encabezado de columna) y td> (celda de datos).
<ul>
<li>table: La etiqueta table> define el inicio y fin de la tabla
<li> tr: La etiqueta tr> define una fila en la tabla.
<li>th: La etiqueta th> se utiliza para representar las celdas de encabezado
<li>td: La etiqueta td> define una celda de datos en la tabla.
Ejemplo de todo:


![ejemplotable](./APUNTS/EJEMPLOS/ejemplo%20tablas.png)

</ul>
<h3>Elemento div en HTML</h3> 
El elemento div> es un contenedor genérico en HTML que se utiliza para agrupar otros elementos y aplicar estilos o manipularlos con CSS. Tambin se asignan identificadores (id) o clases (class) a los div> para hacer mas facil la selección con CSS. En resumen sirve para organizar y estructurar Ejemplo:

![ejemplodiv](./APUNTS/EJEMPLOS/ejemplo%20div.png)
<h3>Diseño responsive</h3>