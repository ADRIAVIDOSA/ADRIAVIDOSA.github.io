# XML
XML significa _ExtensibleMarkupLenguage_.

Es un lenguaje de transporte

Esto es la **cabecera**: \<?xml version="1.0" encoding="UTF-8"?\>

Todo archivo .xml necesita una **etiqueta raiz**

Hay varios tipos de etiquetas, las **pares** y **impares**.

## Código XML
```XML 
<?xml version="1.0" enconding="UTF-8" ?>
<!-- COMENTARIO -->
<character>
	<name>Nombre</name>
	<surname>Apellido</surname>
	<age years="0" />
</character>
```
## HTML

**HTML** → Hyper Text Markup Language, fue creado en el 1993 (mientras que el HTTP fue creado en el 1991).

Se dice que **Tim Berners-Lee** fue el creador de HTTP y por consecuencia HTML.

HTML fue muy importante ya que antes del 1991 no havia manera de tener una comunicación estandar, y HTML es importante ya que es un estandar de comunicación y por eso fue revolucionario.

En esta asignatura aprenderemos HTML5, que es html Life Scheme.

``` HTML
<!DOCTYPE html>
<html>
<head>
	<title> Martí Tarrasón: Alumne de Cyber de ENTI</title>	
</head>

<body>

	<header>
		<h1><a href="index.html">Martí Tarrasón</a></h1>
		<p>Alumne de Enti, hacker en los tiempos libres</p>
	</header>

	<nav>
		<ul>
			<li><a href="cv.html><abbr title="Curriculum Vitae">CV</abbr></a></li>
			<li><a href="hobbies.html><abbr title="Hobbies de Martí">Hobbies</abbr></a></li>
			<li><a href="contacto.html><abbr title="Contacto,contactame">Contacto</abbr></a></li>
		</ul>
	</nav>

	<main>
		<h2>Estudiante en:</h2>
		<p>ENTI, Escoles Noves Tecnologíes de la Informació</h2>
		
		<blockquote>
		El conocimiento es poder. <em>Francis Bacon</em>
		</blockquote>
		
		<h2>Ficha</h2>
		<p><img src="https://d273yxk2oj202w.cloudfront.net/upldr/enti-classlife-education/2023/03/07/minithumbnail/qweqweqew.webp" alt="Foto de perfil de Classlife"></p>
	
		<h3>Asignaturas</h3>
		<ol>
			<li> Implantació de sistemes operatius (Rafa Laguna Corripio)</li>
				<ul>
					<li>Instal·lació, configuració i explotació del sistema informàtic </li>
					<li>Gestió de la informació i de recursos en una xarxa </li>
					<li>Implantació de programari específic </li>
					<li>Seguretat, rendiment i recursos </li>
				</ul>
		</ol>
	</main>

	<footer>
		<h2>Información extra<h2>
		<p>Taratara (c) 2023</p>
	</footer>

</body>
</html>
```

**APUNTES**

Las etiquetas son como XML y DTD, se abren y se tienen que cerrarse.

Si no se entiende los apuntes, puedes mirar el archivo index.html para que se pueda ver que es lo que hace y como se usan bien las etiquetas.

Tambien hay etiquetas que no he hablado aqui pero en el archivo nombrado anteriormente se puede ver lo que hace.

* En cada html, necesita su etiqueta raiz, que en este caso es ```<html>```
* Para poner un titulo se usa ```<title>```
* Para la cabezera del html se usa ```<head>```
* Para el cuerpo de html se usa ```<body>```
* Para poner un titulo se usa ```<h1> <h2>```
* Para poner un texto de forma normal se usa ```<p>```
* Para poner el texto en nergita se usa ```<strong>```
* Para poner el texto en cursiva se usa ```<em>```
* Para hacer una lista primero se usa ```<ol>``` (ordenate list) o ```<ul>``` (uordenate list) y despues ```<li>``` para cada linea de la lista
* Para poner una etiqueta cringe se usa ```<marquee>``` o ```<blink>``` pero esta ultima ya no funciona
* Para poner un link se usa ```<a>```
* Para poner una imagen se usa ```<img>```
	* Se puede poner un link en la img usando ```<a>```
	* Se puede poner un id para clasificar cada img ```<id="name">```
	* Por si no carga se usa, o para que los ciegos sepan que es ```<alt="name">```
	* Tendriamos que poner un titulo a la imagen para que cuando tengamos al raton en la imagen, salga una descripcion ```<title="name">```
* Para comentar se usa ```<!-- -->```
* Para citar un comentario se usa ```<blockquote>```

**Campos del formulario de contacto**

* input type="text" name="contact_name": campo de texto para el nombre del usuario.
* input type="text" name="contact_surname": campo de texto para el apellido del usuario.
* input type="email" name="contact_email": campo de texto para el correo electrónico del usuario.
* input type="password" name="contraseña": campo de texto para la contraseña del usuario.
* input type="color" name="contact_color": campo para seleccionar el color de los ojos del usuario.
* input type="date" name="contact_date": campo para ingresar la fecha de nacimiento del usuario.
* select name="contact_zodiaco": campo de selección para elegir el signo zodiacal del usuario.
* input type="number" name="edad": campo para ingresar la edad del usuario.
* textarea name="mensaje": campo de texto para que el usuario pueda escribir un mensaje.

**RECORDATORIO**, si estas en firefox, y el html esta bien hecho, hacemos control+u y saldra una ventana extra con el html.

---

## Titulo 1

## Titulo 2
A continuacion una lista

* linea 1 de la lista
* linea 2 de la lista
* linea 3 de la lista

## Titulo 2
*cursiva* _cursiva_
**negrita** __negrita__
~~TACHADO~~
~~***tachado negrita y cursiva***~~

> Esto es una cita
> Para destacar cosas concretas
> Como por ejemplo codigo
>> Esto es una cita dentro de una cita

Esto es un enlace a la mejor web del mundo:
[CondorChem](http://condorchem.com)
y [ESTO](http://enti.cat) es otro enlace.

### Imagen incrustrada
![Nugguet](https://i.etsystatic.com/18862914/r/il/9ddd2d/3355087118/il_570xN.3355087118_rgbz.jpg)

### Ejemplo de resaltado de sintaxis
```kotlin
	
// Hello World Program

fun main(args : Array<String>) {
    println("Hello, World!")
}

```

### Listas de tareas
- [ ] Primera tarea
- [X] Segunda tarea
- [ ] Tercera tarea

### Carácteres extendidos
:poop: :alien: :cry: :imp:

### Tablas

| id _character | name | age | level |
| --- | --- | --- | --- |
| 1 | Eustaquio | 197 | 99 |
| 2 | Mariana | 20 | 100 |
| 3 | Mortadelo | 100 | 1 |
| 4 | Messi | 44 | 32 |

### Escapar caracteres

\# Ejemplo de escapado
\* Ejemplo de escapado\*