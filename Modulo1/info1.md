# Etiquetas
Las etiquetas nos van a permitir poder marcar el contenido que queremos tener en nuestra web.
a continuación un ejemplo de como creamos una etiqueta

````````
<p> Contenido de la etiqueta </p>
````````

La mayoria de etiquetas tiene apertur y cierre , sin embargo existen algunas etiquetas que no tiene etiqueta de cierre y se denominan **Self-Closing**


````````
<br>
<hr>
````````

Las etiquetas nos sirven para definir el tipo de contenido que queremos tener en nuestra web , es por ello que antes de empezar a crear nuestra página web debemos tener claro el diseño de lo que vamos a trabjar , ya que parte del trabajo es la interpretación de los contenidos para luego creaer nuestra web.

Es así que tendremos distintas etiquetas para agregar el contenido en nuestra web (archivo.html), por lo que vamos a tener desde etiquetas para agregar parrafos , títulos hasta etiquetas para poder agregar reproductores de audio y video en nuestra web.


# Estructura HTML

Cuando hablamos de una estructura HTML , nos referimos a la estructura básica a nivel de etiquetas para poder crear nuestro página web.
a continuación se muestra un ejemplo de estructura en el nivel más basico.

````````
<!DOCTYPE HTML>
<html lang="ES">
	<head>
		<meta charset="utf-8">
		<title>Title de la página</title>
	</head>
	<body></body>
</html>
````````

La etiquetas mostradas tienen un función especifica dentro del marcado de cotenido dentro de nuestra web

## DOCTYPE
La linea n1 del doctype no es una etiqueta , es una DTD (Declaración de tipo de documento), mediante la cual definimos la versión de html que vamos a usar.
DTD versión HTML
 ````````
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
   "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
````````

DTD versión HTML5
 ````````
<!DOCTYPE html>
````````
## html
La etiqueta html nos permite definir un ambito en donde vamos a colocar todas las etiquetas html con las que vamos a trabajar.

## head
provee información general (metadatos) acerca del documento, incluyendo su título y enlaces a scripts y hojas de estilos.
Podemos definir este etiqueta como la que nos va a permitir definir valores para el navegador, tener en cuenta que los contenidos que sean agregados en esta etiqueta no son visibles para el usuario.

## body
El Elemento HTML **body** representa el contenido de un documento HTML.  Es decir que todo los contenidos que quiero que sean visibles para el usuario deben estar dentro de esta etiqueta.


## Etiquetas de tipo parrafo
la etiqueta de tipo **p** nos permite a nosotros poder marcar un parrafo en nuestra página.

 ````````
<p>cada vez que queramos usar un parrafo , debemos utilizar esta etiqueta</p>
````````


## Etiquetas de tipo Título
Las etiquetas de tipo títulos nos va a permitir poder definir los titulos de nuestros contenidos.
para ello html no solo nos brinda 1 sola etiqueta de tipo título , por lo contrario nos brinda hasta 6 variantes de títulos con la finalidad de manejar la jerarquía de títutlos.

 ````````
<h1>La evolución de la TV</h1>
<h2>Historia de la TV</h2>
	<h3>La tv en blanco y Negro</h3>
<h2>Presente de la TV</h2>
	<h3>La tv tradicional vs el contenido bajo demanda</h3>
<h2>Futuro de la TV</h2>

````````

## Etiquetas de tipo Img
las etiquetas **img** nos va permitir poder agregar a nuestra web imágenes.

````````
<img src="rutadefoto.jpg">

````````