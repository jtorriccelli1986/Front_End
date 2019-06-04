## Clase 2

## Etiquetas de tipo Img
las etiquetas **img** nos va permitir poder agregar a nuestra web imágenes.
las etiquetas **img** van a contar 2 atributos importantes **alt=""** y **title=""**

````````
<img src="rutadefoto.jpg" alt="texto alternativo" title=" título de foto">

````````


## Rutas:
el concepto de rutas nos va a permitir entender como podemos incluir img , archivos , enlaces a nuestra web.
estos se dividien en 2 :

### Rutas Absolutas
se puede definir como la ruta del archivo en donde se tiene como origen de la ruta la raiz de los archivos del SO

### Rutas Relativas
se puede definir como la ruta del archivo en donde se tiene como origen de la ruta de la carpeta en donde se encuentra el archivo en el cual estas trabajando.




## Enlaces
los enlances en nuestras paginas son creados mediante las etiquetas **a** y usan el atributo **href=""** para definir el acceso a elementos , en otros palabras la etiqueta de tipo a crea un enlace a otras páginas de internet, archivos o ubicaciones dentro de la misma página

````````
<a href="http://www.gooogle.com">Click Aqui</a>

````````


la etiqueta de tipo a soporta los siguientes atributos:

* **download** Este atributo, indica descargar a los navegadores una URL en lugar de navegar hacia ella, por lo que el usuario será dirigido para salvarla como un archivo local. 


````````
<a href="foto.jpg" download>Click Aqui</a>
````````


* **href** Contiene una URL a la cual apunta el enlace.

````````
<a href="http://www.gooogle.com">Click Aqui</a>
````````
* **target** nos permit definir el compartamiento al hacer click en el enlace.

cuando el atributo target="_self" tiene el valor *_self este permite que en enlace se abra en la misma pestaña
````````
<a href="http://www.gooogle.com" target="_self">Click Aqui</a>
````````
por el contrario cuando el atributo target tiene el valor *_blank este permite que en enlace se abra en otra pestaña
````````
<a href="http://www.gooogle.com" target="_blank">Click Aqui</a>
````````


la etiqueta de tipo **a** también nos permite tener llamados de acción del siguiente tipo

````````
<a href="mailto:jcarlos@gmail.com">Enviar correo a jcarlos@gmail.com</a>
````````
````````
<a href="tel:+51952345456">+51 957 157 156</a>
````````


## Listas

dentro de los contenidos que vamos a tener dentro de una web vamos a tener contenidos de tipo lista , es por ello que html brinda 2 etiquetas orientas al uso de listas teniendo el cuenta que las listas pueden ser de 2 tipos : **Listas Ordenadas** y **Listas Desordenadas** 

**Listas Desordenadas** proviende de unorder-list y la etiqueta para poder marcas las listas de tipo desordenada es la etiqueta **ul**
````````
<ul>
<li></li>
</ul>
````````
**Listas Ordenadas** proviende de order-list y la etiqueta para poder marcas las listas de tipo desordenada es la etiqueta **ol**
````````
<ol>
<li></li>
</ol>
````````
**tener en cuenta que para todos los elementos que queramos representar dentro de nuestas listas vamos a utilizar la etiqueta de tipo **li** (list-item)


## Tablas 
Las tablas en las estructuras html nos va a permitir a nosotros poder mostrar los datos en 2 o mas dimeisnoes 
````````
<table>
  <tr>
    <td>Nombres</td>
    <td>Apellido</td>
  </tr>
  <tr>
    <td>Juan Carlos</td>
    <td>Ramos</td>
  </tr>
</table>
````````
Las estructura de las tablas evolución a la siguiente:
````````
<table>
	<thead>
		<tr>
    		<th>Nombres</th>
    		<th>Apellido</th>
  		</tr>
	</thead>
  	<tobdy>
  		<tr>
	    	<td>Juan Carlos</td>
	    	<td>Ramos</td>
	  	</tr>
  	</tobdy>
  	<footer>
  		<tr>
	    	<td>Juan Carlos</td>
	    	<td>Ramos</td>
	  	</tr>
  	</footer>
  
</table>
````````
en donde los nuevos elementos represetan lo siguiente:

* **thead**  nos permite definir la cabezera de la tabla
* **th**     nos permite definir las columnas de la cabezera de una tabla
* **tbody**  nos permite definir el cuerpo de la tabla
* **tfoot**  nos permite definir el pie de la tabla
 

