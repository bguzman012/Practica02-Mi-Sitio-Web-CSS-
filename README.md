Se ha creado un archivo principal index.html el cual va a ser el principal. La
navegabilidad entre diferentes paginas del sitio web se ha obtenido de la
siguiente manera:

\<section class="listas"\>

        \<h1 id="list_title"\>Menu\</h1\>

        \<nav\>

            \<ul\>

                \<li\>\<a href="accesorios/juegos.html"\>Juegos\</a\>\</li\>

                \<li\>\<a href="accesorios/hardware.html"\>Hardware\</a\>\</li\>

                \<li\>\<a href="general/noticias.html"\>Noticias\</a\>\</li\>

                \<li\>\<a href="accesorios/tienda.html"\>Tienda\</a\>\</li\>

                \<li\>\<a href="general/ps_plus.html"\>Ps Plus\</a\>\</li\>

                \<li\>\<a href="contacto/contacto.html"\>Contactanos\</a\>\</li\>

            \</ul\>

        \</nav\>

    \</section\>

Esa es la estructura básica, pero se ha utilizado Css para estructurar la
**forma de las columnas, colores, fuentes.**

\<head\>

    \<meta charset="UTF-8"\>

    \<meta name="viewport" content="width=device-width, initial-scale=1.0"\>

    \<link type="text/css" rel="stylesheet" href="css/dos_columnas.css"\>

    \<link type="text/css" rel="stylesheet" href="css/styles.css"\>

    \<meta http-equiv="X-UA-Compatible" content="ie=edge"\>

    \<title\>Play Station\</title\>

\</head\>

Para importar los archivos .css donde se encuentran los estilos, se ha puesto lo
siguiente:

\<link type="text/css" rel="stylesheet" href="css/dos_columnas.css"\>

Esto enlaza automáticamente los dos archivos.

Se ha creado 3 archivos css: uno para la estructura de dos columnas, uno para la
estructura de tres columnas y otro para los diferentes estilos.

![](media/8425aaf69f8fad8e7f3ea0ee0658f61d.png)

Para darle el estilo necesario se ha puesto a cada elemento del código html
**clases e ID,** asi de esta forma se puede controlar las características de
cada uno desde el archivo CSS.

**Estructura de dos columnas**

header {

  clear: top;

}

.contenido {

  width: 75%;

  float: left;

  margin-left: 4%;

}

p{

  text-align: justify;

  font-size: 105%;

  font-family: cursive;

}

.listas {

  background-color: \#000000b5;

  width: 6%;

  float:left;

  padding:2%;

  border-radius: 10%;

  min-width: min-content;

  margin: 1%;

}

.logo{

  text-align: center;

}

footer{

  clear: both;

}

\#formu {

  margin: 0 auto;

  float: left;

  width: 60%;

  padding: 10%;

}

clear: top; se ha utilizado para que la etiqueta header flote hacia arriba

**A la clase .listas** que es la etiqueta \<section Class: “listas”\> se le ha
dado una dimensión y se la ha otrogado que flote hacia la izquiera

**A la clase .contenido** que es la etiqueta \<section Class: “contenido”\> se
le ha dado una dimensión y se la ha otrogado que flote hacia la izquiera

Se ha utilizado size relativos como el **Porcentaje** para que no importe la
resolución de la pantalla en la que se visualize la pagina

Float: left;

Width: 6%;

Border-radius: 10%

![](media/1a42605db340a7adf3fe9a5ab99213c7.png)

![](media/decf81c130904e8a13eba7cf04f080a9.png)

La estructura ha quedado asi al momento de implementar CSS

**Las etiquetas de títulos y subtitulos han sido implementadas de la siguiente
forma**

**\#titulo** hace referencia a la etiqueta **h1**

\#titulo {

  text-align: center;

  font-size: 170%;

  font-family: 'Maven Pro','sans-serif','serif';

  font-style: unset;

  text-decoration: underline;

  background-color: \#0675d45c;

  color: darkblue;

  border-style: dashed;

}

h3 {

  text-align: justify;

  font-size: 135%;

  font-family: 'Maven Pro','sans-serif','serif';

}

h4{

  text-align: justify;

  font-size: 125%;

  font-family: 'Maven Pro','sans-serif','serif';

}

En la navegación de ha otorgado un tamaño relativo de margen y se ha dado un
tque ovalado para la correcta realización de la practica

Line-height: 200% de margen

nav \> ul {

  line-height: 200%;

  list-style-type: none;

  padding-left: 5%;

}

.listas {

  background-color: \#000000b5;

  width: 6%;

  float:left;

  padding:2%;

  border-radius: 10%;

  min-width: min-content;

  margin: 1%;

}

Border-radius permite darle un toque ovalado a la sección donde se encuentra la
lista de vanegacion

![](media/e511f72471bcb4a31be939d3212df45b.png)

El formulario se ha realizado en el archivo **contacto.html** de la siguiente
forma

\<article class="formulario"\>

            \<p\>Nombre: \<input type="text" name="nombre" size=20\>\</p\>

            \<p\>Correo : \<input type="text" name="apellidos" size=20\>\</p\>

            \<p\>Motivo: \<input type="text" name="nacionalidad" size=20\>\</p\>

            \<p\>

                \<button type="submit" name="enviar"\> Enviar \</button\>

            \</p\>

        \</article\>

Donde se escribe la palabra antes del imput va un **tipo label**

\<input\> sirve para crear cajas de texto

\<button\> para crear el botón

**El resultado es el siguiente:**

![](media/68c80650894c5ae7abb930a57f056ef1.png)

**Estructura de tres columnas:**

header {

    clear: top;

  }

  .contenido {

    width: 60%;

    float: left;

    margin-left: 2%;

    margin-right: 2%;

  }

  .listas {

    background-color: \#000000b5;

    width: 6%;

    float:left;

    padding:2%;

    border-radius: 10%;

    min-width: min-content;

    margin: 1%;

  }

  .logo{

    text-align: center;

  }

  footer{

    clear: both;

  }

  .noticias{

      float: left;

      width: 13%;

  }

**Se ha creado un \<header\> que va en la parte alta; una \<section\> donde se
encuentra la lista de navegación y un \<aside\> donde va la columna de
promociones; el contenido neto de la pagina se encuentra en el medio en una
\<section\> \<article\> \<p\>; en la parte derecha se ha colocado una
\<section\> con \<aside\> de noticas random.**

**El resultado obtenido ha sido el siguiente:**

![](media/1605ccbee512f5cf9986546582697fb5.png)

![](media/c73956095620a23f51d066d57670275a.png)

**Evidencia de la validación de cada pagina creada:**

**Index.html**

![](media/0a9f9c0e15b45f7ccc51eef133631c30.png)

![](media/cd89593c072619e555a87dc07adab6db.png)

**Juegos.html**

![](media/9246931eeed655e4783f8946f20b590f.png)

![](media/946758365d9d9487d0659d577c919f37.png)

**Hardware.html**

![](media/e06b097143f7fe24df6eeee126c2bc4b.png)

![](media/93649b7a1cd927bc851f2cc14a436b7f.png)

![](media/60c6ed4174a293c3694bd55c2105beef.png)

**Noticias.html**

![](media/ac7f14a3203e0e6be2e33ace64cc872b.png)

![](media/cebc9682d98c8880ec38d98da2dddc53.png)

![](media/7a1da12b8b51117ff939aede1d53d6c4.png)

**Tienda.html**

![](media/f056f949f524d331a94e0f8fed1b8ea4.png)

![](media/534282fc6e3969dea9bbcfebefa146dc.png)

![](media/a903589c589726ac44c51688e9221a88.png)

**Ps_plus.html**

![](media/534282fc6e3969dea9bbcfebefa146dc.png)

![](media/534282fc6e3969dea9bbcfebefa146dc.png)

![](media/5272f7471b8e278bd0a948cfaba092ca.png)

**Contacto.html**

![](media/e5b97d34e9026a9f58d38066b99dfb53.png)

![](media/ddc7d0557bfa21f5e2807b1c1c85bf22.png)

**Validar Pagina Css**

**Dos_columnas.css**

![](media/c7f2d392a2aca8a77fe4ed1eaf4fabb6.png)

**Tres_columnas.css**

![](media/2c6e8015a7efc60ab1b07de4b3581f77.png)

**Styles.css**

![](media/a83399bbbb03a55fa24ca9260c906d6f.png)

**En el informe se debe incluir la información de GitHub (usuario y URL del
repositorio de la práctica)**

*Usuario: bguzman012*

*Link: https://github.com/bguzman012/Practica02-Mi-Sitio-Web-CSS*

**Tutorial**

Usuario: bguzman012

Link: <https://github.com/bguzman012/Tutorial-02---1TriAndSuccedSports>
