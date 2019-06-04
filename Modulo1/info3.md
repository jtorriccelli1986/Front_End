# clase 03	


## Etiquetas de texto
a continuacón definimos algunas etiquetas que debemos conocer para poder manejar textos

* **p**  nos srive para poder representar parrafos en nuestros contenidos
* **a** nos sirve para poder generar enlaces en nuestros contenidos
* **span** Representa texto sin un significado específico. 
* **strong** Representa un texto especialmente importante .
* **blockquote** Representa una contenido citado desde otra fuente.
* **em**  Representa un texto enfatizado , como un acento de intensidad.
* **small**  Representa un comentario aparte , es decir, textos como un descargo de responsabilidad
* **mark** Representa texto resaltado con propósitos de referencia
* **sub** Representan un subíndice .
* **sup** Representan un superíndice, respectivamente.



## Formularios

Los formularios nos permiten generar un bloque con el cual podemos solicitar al usuairo información 
````````
<form>
	<fieldset>
		<legend>Datos personales</legend>
		<label>Nombres:</label>
		<input type="text" name="nombre">
		<label>Apellidos:</label>
		<input type="text" name="apellidos">
	</fieldset>
	<fieldset>
		<legend>Datos Estudios</legend>
		<label>Grado:</label>
		<input type="text" name="nombre">
		<label>Experiencia:</label>
		<input type="text" name="apellidos">
	</fieldset>
	<label>Distrito</label> 
	<select>
		<option value="1">Lince</option>
		<option value="2">Jesús María</option>
		<option value="3">Miraflores</option>
	</select>
	<label>Cursos</label>
	<label><input type="radio">HTML</label>
	<label><input type="radio">CSS</label>
	<label><input type="radio">JS</label>
	<label>Turno</label>
	<label><input type="checkbox">Mañana</label>
	<label><input type="checkbox">Tarde</label>
	<label><input type="checkbox">Noche</label>
	<label>Comentario</label>
	<textarea></textarea>
	<label>selecciona tu archivo</label>
	<input type="file" name="">
	<input type="submit" name="">
	<button type="submit"></button>
</form>
````````


## etiqueta div

la etiqueta **div** representa un contenedor genérico sin ningún significado especial.
````````
<div>
 <!-- bloque de informacion 1 -->
</div>

<div>
 <!-- bloque de informacion 1 -->
 	<div>
 		<!-- item de informacion-->
 	</div>
</div>
````````