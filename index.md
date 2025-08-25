# Ejercicio de HTML Básico: Creando tu Primera Página Sencilla

En este ejercicio, pondrás en práctica los conceptos fundamentales de HTML para construir una página web simple.

### Instrucciones:

Crea un archivo HTML con la siguiente estructura y contenido:

1.  **Declaración DOCTYPE y Etiqueta `<html>`:**
      * Comienza tu archivo con `<!DOCTYPE html>` para indicar que es un documento HTML5.
      * Envuelve todo el contenido dentro de la etiqueta `<html lang="es">` para especificar el idioma español.
2.  **Sección `<head>`:**
      * Define el conjunto de caracteres como UTF-8: `<meta charset="UTF-8">`.
      * Asegúrate de la compatibilidad con Internet Explorer: `<meta http-equiv="X-UA-Compatible" content="IE=edge">`.
      * Configura la vista para dispositivos móviles: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`.
      * Establece el título de la página en la pestaña del navegador como "Mi Página de Ejercicio": `<title>Mi Página de Ejercicio</title>`.
3.  **Sección `<body>`:**
      * Crea un encabezado principal que diga "Bienvenido a mi Web" usando `<h1>`.
      * Agrega un subtítulo que diga "Explorando HTML" usando `<h2>`.
      * Crea un párrafo (`<p>`) que contenga la siguiente frase: "Este es un ejemplo de párrafo en mi primera página HTML."
      * Inserta una imagen de un paisaje (`<img>`). Puedes usar una URL de imagen de prueba como `https://via.placeholder.com/150` o cualquier imagen que tengas localmente. Asegúrate de incluir el atributo `alt` con un texto descriptivo como "Imagen de paisaje".
      * Crea un enlace (`<a>`) que diga "Visita Google" y que dirija a `https://www.google.com`. Haz que el enlace se abra en una nueva pestaña del navegador usando el atributo `target="_blank"`.
      * Agrega un botón (`<button>`) que diga "Haz clic aquí".
      * Crea una lista desordenada (`<ul>`) con tres elementos de lista (`<li>`): "Elemento 1", "Elemento 2", "Elemento 3".
      * Añade un salto de línea (`<br>`) después del botón.

### **Código de referencia (no lo copies directamente, úsalo como guía después de intentar el ejercicio):**


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página de Ejercicio</title>
</head>
<body>
    <h1>Bienvenido a mi Web</h1>
    <h2>Explorando HTML</h2>
    <p>Este es un ejemplo de párrafo en mi primera página HTML.</p>
    <img src="https://via.placeholder.com/150" alt="Imagen de paisaje">
    <a href="https://www.google.com" target="_blank">Visita Google</a>
    <br>
    <button>Haz clic aquí</button>
    <ul>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
        <li>Elemento 3</li>
    </ul>
</body>
</html>
```

-----

## Ejercicio de HTML Semántico: Estructurando un Blog Post

Este ejercicio se enfoca en el uso de etiquetas HTML semánticas para dar significado y estructura a un contenido de tipo blog.

### **Instrucciones:**

Crea un archivo HTML con la siguiente estructura y contenido, utilizando las etiquetas semánticas apropiadas:

1.  **Estructura Base:**
      * Crea la estructura básica de HTML (DOCTYPE, `<html>`, `<head>`, `<body>`) como en el ejercicio anterior, con un título de "Blog Semántico".
2.  **Encabezado de la Página (`<header>`):**
      * Dentro de la etiqueta `<header>`, incluye un título principal del blog (por ejemplo, "Mi Blog de Tecnología") usando `<h1>`.
      * Agrega una barra de navegación (`<nav>`) con enlaces a "Inicio", "Acerca de" y "Contacto". Puedes usar una lista desordenada (`<ul>`) para los enlaces.
3.  **Contenido Principal (`<main>`):**
      * Envuelve todo el contenido principal de la página dentro de la etiqueta `<main>`.
4.  **Artículo (`<article>`):**
      * Dentro de `<main>`, crea un `<article>` para representar una entrada de blog completa.
      * Dentro del `<article>`, incluye un `<h2>` para el título del artículo (por ejemplo, "El Futuro de la Inteligencia Artificial").
      * Agrega un párrafo (`<p>`) con el contenido del artículo (puedes usar Lorem Ipsum o un texto corto sobre IA).
5.  **Sección Adicional (`<aside>`):**
      * Dentro de `<main>`, pero fuera del `<article>`, crea una sección lateral (`<aside>`).
      * Dentro de `<aside>`, agrega un `<h3>` que diga "Artículos Relacionados" y una lista desordenada (`<ul>`) con dos enlaces (`<a>`) a artículos ficticios (por ejemplo, "Blockchain Explicado", "Machine Learning para Principiantes").
6.  **Pie de Página (`<footer>`):**
      * Al final del `<body>`, crea un `<footer>`.
      * Dentro del `<footer>`, incluye un párrafo con el símbolo de copyright y el año (por ejemplo, `&copy; 2024 Mi Blog de Tecnología`).

### **Código de referencia (no lo copies directamente, úsalo como guía después de intentar el ejercicio):**


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Semántico</title>
</head>
<body>
    <header>
        <h1>Mi Blog de Tecnología</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Acerca de</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <article>
            <h2>El Futuro de la Inteligencia Artificial</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio, rerum. Adipisci aliquid tempora veritatis architecto, fugiat mollitia ab nulla asperiores ipsum quas nesciunt recusandae sequi commodi cupiditate aut, fuga dolores.</p>
        </article>
        <aside>
            <h3>Artículos Relacionados</h3>
            <ul>
                <li><a href="#">Blockchain Explicado</a></li>
                <li><a href="#">Machine Learning para Principiantes</a></li>
            </ul>
        </aside>
    </main>
    <footer>
        <p>&copy; 2024 Mi Blog de Tecnología</p>
    </footer>
</body>
</html>
```

-----

## Explicación de Etiquetas HTML Adicionales y de Gran Utilidad

Además de las etiquetas ya mencionadas, aquí tienes algunas otras que son muy comunes y útiles en el desarrollo web:

-----

### **Etiquetas para Formularios**

Los formularios son esenciales para la interacción del usuario en la web, permitiendo la entrada de datos.

  * **`<form>`: El Contenedor del Formulario**

      * **Propósito:** Define un formulario HTML. Sirve como un contenedor para todos los elementos de entrada del formulario, como campos de texto, botones, casillas de verificación, etc.
      * **Atributos comunes:**
          * `action`: Especifica la URL donde se enviarán los datos del formulario cuando este se envíe.
          * `method`: Define el método HTTP a usar al enviar los datos del formulario (`GET` o `POST`). `GET` envía los datos en la URL (visible), y `POST` los envía en el cuerpo de la solicitud (no visible en la URL, más seguro para datos sensibles).
          * `autocomplete`: Controla si el navegador debe ofrecer la autocompletación para los campos del formulario.
          * `target`: Similar al `target` de `<a>`, especifica dónde se mostrará la respuesta después de enviar el formulario.
      * **Ejemplo:**
        ```html
        <form action="/submit-form" method="post">
            </form>
        ```

  * **`<label>`: Etiquetas para Campos de Formulario**

      * **Propósito:** Representa una etiqueta para un elemento de una interfaz de usuario. Su uso principal es asociar texto descriptivo con un control de formulario (como un `<input>`, `<textarea>`, o `<select>`).
      * **Importancia:** Mejora la **accesibilidad**. Cuando un usuario hace clic en la etiqueta, el navegador enfoca automáticamente el control de formulario asociado. Esto es crucial para usuarios con discapacidades o para una mejor experiencia de usuario en general.
      * **Atributos clave:**
          * `for`: Debe coincidir con el atributo `id` del control de formulario al que está asociado.
      * **Ejemplo:**
        ```html
        <label for="nombreUsuario">Nombre de Usuario:</label>
        <input type="text" id="nombreUsuario" name="username">
        ```

  * **`<input>`: Campos de Entrada de Datos**

      * **Propósito:** Se utiliza para crear controles de formulario interactivos para la entrada de datos por parte del usuario. Es una de las etiquetas más versátiles y se usa para una gran variedad de tipos de entrada.
      * **Atributos clave:**
          * `type`: Esencial, define el tipo de control (texto, número, contraseña, correo electrónico, fecha, casilla de verificación, botón de radio, archivo, enviar, etc.).
          * `name`: El nombre del control, usado para identificar los datos cuando se envían al servidor.
          * `id`: Un identificador único para el elemento, usado para vincular con `<label>` y para manipulaciones con JavaScript.
          * `value`: El valor inicial del campo o el valor enviado con el formulario.
          * `placeholder`: Texto que aparece en el campo de entrada cuando está vacío y sin foco, sirviendo de pista para el usuario.
          * `required`: Un atributo booleano que indica que el campo debe llenarse antes de enviar el formulario.
          * `readonly`: Un atributo booleano que hace que el campo no sea editable, pero su valor aún se envía con el formulario.
          * `disabled`: Un atributo booleano que inhabilita el campo, no se puede interactuar con él y su valor no se envía.
      * **Ejemplos de `type`:**
          * `type="text"`: Campo de texto de una sola línea.
          * `type="password"`: Campo de contraseña (los caracteres se ocultan).
          * `type="email"`: Campo para direcciones de correo electrónico (los navegadores pueden validar el formato).
          * `type="number"`: Campo para números (puede tener controles de flecha para aumentar/disminuir).
          * `type="checkbox"`: Casilla de verificación.
          * `type="radio"`: Botón de radio (solo uno puede ser seleccionado de un grupo con el mismo `name`).
          * `type="submit"`: Botón para enviar el formulario.
          * `type="file"`: Permite al usuario seleccionar uno o más archivos.
      * **Ejemplo combinado:**
        ```html
        <form>
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="userEmail" placeholder="tu@ejemplo.com" required>

            <label for="password">Contraseña:</label>
            <input type="password" id="password" name="userPassword" minlength="8">

            <input type="checkbox" id="acepto" name="aceptoTerminos">
            <label for="acepto">Acepto los términos y condiciones</label>

            <input type="submit" value="Registrarse">
        </form>
        ```

-----

### **Etiquetas para Contenido Multimedia**

Para incorporar audio y video directamente en tus páginas web.

  * **`<video>`: Incrustar Video**

      * **Propósito:** Se utiliza para incrustar un reproductor de video en el documento HTML. Permite reproducir formatos de video como MP4, WebM y Ogg.
      * **Atributos comunes:**
          * `src`: La URL del archivo de video.
          * `controls`: Agrega controles de reproducción estándar del navegador (reproducir/pausar, volumen, barra de progreso).
          * `autoplay`: El video comienza a reproducirse automáticamente al cargar la página (a menudo restringido por navegadores).
          * `loop`: El video se reproduce en bucle.
          * `muted`: El video comienza silenciado.
          * `poster`: La URL de una imagen que se mostrará antes de que el video se reproduzca.
          * `width`, `height`: Establecen las dimensiones del reproductor.
      * **Etiqueta `<source>`:** Se utiliza dentro de `<video>` (y `<audio>`) para especificar múltiples fuentes de video/audio, permitiendo al navegador elegir la que soporta.
      * **Ejemplo:**
        <video width="320" height="240" controls poster="miniatura-video.jpg">
            <source src="mi-video.mp4" type="video/mp4">
            <source src="mi-video.webm" type="video/webm">
            Tu navegador no soporta la etiqueta de video.
        </video>
        ```

  * **`<audio>`: Incrustar Audio**

      * **Propósito:** Se utiliza para incrustar contenido de audio en el documento HTML. Permite reproducir formatos de audio como MP3, WAV y Ogg.
      * **Atributos comunes:** Similares a `<video>`, incluyendo `src`, `controls`, `autoplay`, `loop`, `muted`.
      * **Ejemplo:**
        ```html
        <audio controls autoplay loop>
            <source src="mi-cancion.mp3" type="audio/mpeg">
            <source src="mi-cancion.ogg" type="audio/ogg">
            Tu navegador no soporta la etiqueta de audio.
        </audio>
        ```

-----

### **Etiquetas para Estructura y Semántica Avanzada**

  * **`<header>`:**

      * **Propósito:** Representa contenido introductorio, generalmente un grupo de ayudas a la navegación o el logotipo.
      * **Ubicación:** Comúnmente al principio del `<body>` o dentro de `<section>`, `<article>`, etc. (un documento puede tener múltiples `<header>`).

  * **`<nav>`:**

      * **Propósito:** Representa una sección de enlaces de navegación, ya sea para la navegación principal del sitio, un índice de la sección actual, o enlaces relacionados.

  * **`<main>`:**

      * **Propósito:** Representa el contenido dominante del `<body>` del documento. El contenido dentro de `<main>` debe ser único para el documento y no debe incluir contenido repetitivo como barras laterales, enlaces de navegación o información de derechos de autor.
      * **Nota:** Solo debe haber un elemento `<main>` por documento HTML.

  * **`<article>`:**

      * **Propósito:** Representa una pieza de contenido independiente y autónoma dentro de un documento. Podría ser un post de blog, un comentario de usuario, un widget interactivo, o cualquier elemento que podría ser distribuido o reutilizado de forma independiente.

  * **`<section>`:**

      * **Propósito:** Representa una sección genérica de contenido agrupado, a menudo con un encabezado. Agrupa contenido relacionado lógicamente.

  * **`<aside>`:**

      * **Propósito:** Representa una sección de una página que contiene contenido que está indirectamente relacionado con el contenido principal del documento. A menudo se presenta como una barra lateral o un cuadro de información.

  * **`<footer>`:**

      * **Propósito:** Representa el pie de página de su sección de contenido de inclusión más cercana o del elemento raíz de la sección (es decir, de un documento, un artículo o una sección).
      * **Ubicación:** Comúnmente al final del `<body>` o dentro de `<section>`, `<article>`, etc. (un documento puede tener múltiples `<footer>`).

Estas etiquetas te permiten construir páginas web más organizadas y comprensibles tanto para los navegadores como para los motores de búsqueda y las tecnologías de asistencia, lo que lleva a una mejor accesibilidad y SEO.

#Ejercicio:
 creacion de curriculum semantico utilizando las etiquetas HTML vistas, de forma semanticamente correcta
 2 dias de duracion
 