## GITHUB
Para crear un repositorio de github:
<br>
1. Iniciar sesión en la pagina de github. Arriba en new repository creamos el repositorio y ponemos un nombre adecuado. Y añadimos el README y lo creamos.

2. Despues, tenemos que  clonarlo a nuestra máquina local. Copiamos el code del repositorio. Abrimos nuestra carpeta de Repositorio GIT, abrimos el CMD, y ponemos git clone url_del_repositorio.

3. Para trabajr localmente y subirlo, tendremos que abrir el CMD de nuestra carpeta ya clonada. y pondremos:
* git init
* git add .
* git commit -m "texto"
* git push origin main

## MARKDOWN

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


## CCS

### ¿Qué es?

Es un lenguaje de diseño gráfico para definir y crear la presentación de un documento estructurado escrito en un lenguaje de marcado.​

1. Si no queremos afectar a solo uno, sino a todos, lo pondremos en el head, para que todos se vean afectados.
2. Para modificar una tabla entero pondremos (style="color:red;"), dentro de head en la tabla. Si quieres definir mejor los bordes ponemos dentro de las comillas (text-align:center) este es para quede centrado, pero podemos poner "right" "left". Si queremos afectar a solo un elemento lo ponemos dentro del codigo de solo una fila.
3. Dentro de body para solo afectar a las filas y rellenarlos con color, ponemos (style="background-color: rgb(104, 104, 13);")

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

## HTML
Es el lenguaje estándar utilizado para estructurar y presentar contenido en la web.
### Estructura básica de HTML

![ejemplohtml](./EJEMPLOS/EJEMPLO%20HTML.png)

Todo documento de HTML sigue una estructura basica, donde pone body nosotros escribiremos nuestro contenido de la página web.En el head añadiremos nuestro documento CSS.

<h3>Encabezado y Párrafo</h3>
Utilizamos etiquetas de encabezado (h1> a h6>) y párrafos (p>). Por ejemplo:
<h3>EJEMPLO H2</h3>
<h4>EJEMPLO H4</h4>
<h5>EJEMPLO H5</h5>
<h6>EJEMPLO H6</h6>

### Listas
Crea listas ordenadas (ol>) y no ordenadas (ul>). Dentro de estas etiquetas, se utilizan li> para cada elemento de la lista.
<br>
Para la etiqeta ol> para que salgan numeros donde sale la etqiueta li saldran 1, 2, 3, es decir una lista rodenada 

![ejemplool](./EJEMPLOS/ejemplo%20lista.png)

Para la etiqueta ul> para que salgan puntos donde sale la etiqueta li>.

![ejemploul](./EJEMPLOS/lista%20desordenada.jpg)


### Imágenes

![ejemploimagen](./EJEMPLOS/ejemplo%20imagen%20html.png)

+ La etiqueta img> se utiliza para insertar una imagen.
+ El atributo src especifica la ruta de la imagen, una URL.
+ El atributo alt te da un texto alternativo para la imagen, que se mostrará si la imagen no se carga.


### Tablas
Podemos crear tablas utilizando las etiquetas table>, tr> (fila), th> (encabezado de columna) y td> (celda de datos).

+ table: La etiqueta table> define el inicio y fin de la tabla
+  tr: La etiqueta tr> define una fila en la tabla.
+ th: La etiqueta th> se utiliza para representar las celdas de encabezado
+ td: La etiqueta td> define una celda de datos en la tabla.
Ejemplo de todo:


![ejemplotable](./EJEMPLOS/ejemplo%20tablas.png)

<br>

### Elemento div en HTML
El elemento div> es un contenedor genérico en HTML que se utiliza para agrupar otros elementos y aplicar estilos o manipularlos con CSS. Tambin se asignan identificadores (id) o clases (class) a los div> para hacer mas facil la selección con CSS. En resumen sirve para organizar y estructurar Ejemplo:

![ejemplodiv](./EJEMPLOS/ejemplo%20div.png)
## Responsive Flex
### Que es
Puedes organizar elementos de una manera que se adapte a diferentes tamaños de pantalla y dispositivos.
### Contenedor Flex
Podemos convertir un elemento contenedor en un contenedor flex. Esto se hace así: display: flex;
### Alineación y Espaciado
Puedes utilizar: justify-content, align-items, y align-self para controlar la posición y alineación de los elementos.

## Responsive Bootstrap
### Como poner Responsive Bootstrap
Agregamos Bootstrap en la sección head> con 
<br>
link rel="stylesheet" href="ruta/bootstrap.min.css"
<br> 
Dentro de nuestro contenido copiares los diferentes div que saldran en la pagina de Bootstrap y,
en la seccion abajo del body pondremos las rutas que queremos y mejor se adapten a nuestra web Por ejemplo:
<br>
"script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity
="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"/script"

