# Trabajo Práctico Nro 1 - PAW
## Introducción al Maquetado

**Objetivo:** Obtener los conocimientos básicos sobre el maquetado de una página web. 


#### 1. ¿Qué es un lenguaje de marcado? ¿Cuál es su utilidad? ¿Qué es un tag? ¿Qué es un atributo?
Un lenguaje de marcado es una forma de codificar un documento que utiliza una notación especial para marcar las diferentes secciones de un documento, junto con el texto, incorpora etiquetas o marcas que contienen información adicional acerca de la estructura del texto o su presentación, por ejemplo HTML (*HyperText Markup Language*, lenguaje de marcado de hipertexto). No son lenguajes de programación.
<p>
Los tags, o etiquetas, son los "comandos" que los navegadores leen e interpretan para armar y dar forma a las páginas de Internet.
<p>
Los elementos en HTML tienen atributos, estos son valores adicionales que configuran los elementos (tags) o ajustan su comportamiento de diversas formas para cumplir los criterios de los usuarios.

* * *
#### 2. ¿Cuál es la utilidad de HTML? ¿Qué conjunto mínimo de tags debe contener un documento elaborado en este lenguaje? Describa brevemente su utilidad.
Básicamente el lenguaje HTML sirve para describir la estructura básica de una página y organizar la forma en que se mostrará su contenido.
<p>
Estructura HTML

```html
<html> <!-- Bloque que indica que es codigo HTML -->
    <head> <!-- Bloque de cabecera, se incluye metadata del sitio -->
        <title>Título del sitio Web</title> <!-- Titulo de la pagina -->
    </head>
    <body> <!-- Bloque del contenido del sitio -->
        <header> Aqui se incluye contenido introdutorio de la pagina </header>
        <main> Aqui va el contenido principal del sitio </main>
        <footer> Aqui se incluyen los pie de pagina </footer>
    </body>
</html>
```

* * *
#### 3. ¿Cuál es la utilidad e importancia de los enlaces o links entre páginas? ¿Qué significa hipertexto? ¿Un link solo puede apuntar a otra página? ¿Qué importancia tiene esto último?
Un link describe una redireccion unidireccional que pueden enlazar tanto dos documentos diferentes como distintas partes dentro de un mismo documento y si un texto está compuesto por diferentes hyperlinks recibe el nombre de hipertexto.
<p>
Los enlaces o links pueden ser textos o imágenes, que con solo darle clic nos pueden dirigir a otro sitio web o algún documento que quieras descargar.
<p> 
Un link no necesariamente debe apuntar a otra pagina externa, existen links que pueden redireccionar a una seccion especifica del mismo sitio web. 
<p>
Ejemplo de link:
    
```html
<a href="url">link text</a>
```

* * *
#### 4. ¿Cómo funcionan los tags audio y video?   
Antes de HTML5, los archivos de audio/video solo se podian reproducir con un complemento, como por ejemplo flash. El tag <audio> y <video> en HTML 5 especifican una forma estandar de incluir audio y video en una pagina web.

Ejemplo de Audio:
    
```html
<audio controls> 
    <source src="horse.ogg" type="audio/ogg">
    Your browser does not support the video tag.
</audio>
```

Ejemplo de Video:
    
```html
<video width="320" height="240" autoplay>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

El atributo *controls* agrega controles de audio y video, como reproducción, pausa y volumen.

El tag *source* permite especificar archivos de audio o video alternativos que el navegador puede elegir. El navegador usará el primer formato reconocido.

El texto entre el los tags *audio* o *video* sólo se mostrará en los navegadores que no soportan el elemento audio/video.

Una buena idea es incluir siempre los atributos *widthy* y *height*. Si no se configuran alto y ancho, la página puede parpadear mientras se carga el video.

En HTML5, hay 3 formatos de video y audio compatibles:

* Video:
    * MP4
    * WebM
    * Ogg

* Audio: 
    * MP3
    * WAV
    * OGG



* * *
#### 5. ¿Qué es el Rendering Engine de un Browser? ¿Cuál es el que utiliza cada uno de los 5 browsers más conocidos (Chrome, Firefox, Safari, IE-Edge, Opera)? ¿Cuál es la importancia de conocer cada uno de ellos en la construcción de un sitio?
El rendering Engine es un proceso que todos los browser tienen. El objetivo fundamental es transformar documentos HTML y otros recursos  de una pagina web en una representacion visual interactiva en el dispositivo de un usuario.
<br>

| Browser Client | Browser Engine |
| :---------: | :---------: |
| Chrome | Blink |
| Firefox | Gecko |
| Safari | WebKit |
| IE-Edge | Trident |
| Opera | Presto |



* * *
#### 6. Dibujar el Wireframe correspondiente a la página principal de lujan.gob.ar y en función a este desarrollar el código HTML5 correspondiente.
El wireframe se encuentra en el archivo: *Punto_6.html*

* * *
#### 7. Elabore en HTML5 una página que contenga su currículum vítae, respetando la estructura que se muestra a continuación. Tenga en cuenta que los elementos subrayados son enlaces a páginas web o a direcciones de correo electrónico y que la foto debe ser un enlace a la propia imagen. Determine qué tags con qué atributos son necesarios en cada caso.


* * *
#### 8. Elabore el código necesario para representar la siguiente tabla:
La tabla se encuentra en el archivo: *Punto_8.html*
