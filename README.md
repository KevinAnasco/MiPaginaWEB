# 1 ¿Qué es HTML y cuál es su función en la web? 
- El HTML es un lenguaje utilizado para crear y estructurar contenido web, La cual su función 
principal es definir la estructura de un documento web, el HTML es un lenguaje que indica al navegador que tipo de elemento es el que esta en la estructura de la pagina  
Los navegadores se encargan de leer e interpretar el código HTML y así mostrar un contenido 
entendible para el usuario. 

# 2 ¿Que es una etiqueta HTML y menciona las etiquetas más comunes? 
- Las Etiquetas son comandos que transforman el texto en una experiencia digital mas 
atractiva y bien estructurada, además de organizar el contenido las etiquetas son 
fundamentales para destacar una navegación fluida para el usuario  
Las etiquetas mas utilizadas son:  

- <!doctype>: Declara el tipo de documento (HTML5). 
<html> y </html>: Envuelven todo el contenido de la página web. 
<head> y </head>: Contiene metadatos (información no visible). 
<title> y </title>: Define el título de la página (en la pestaña del navegador). 
<body> y </body>: Contiene el contenido visible de la página. 
<h1> ... <h6>: Define encabezados, siendo <h1> el más importante. 
<p> y </p>: Define un párrafo de texto. 
<header>: Cabecera de la página (típicamente con el logo o título). 
<footer>: Pie de página (con información como derechos de autor). 
<nav>: Sección de navegación (enlaces de menú). 
<main>: Contenido principal de la página. 
<form>: Define un formulario para enviar datos. 
<input>: Campo para ingresar datos en un formulario. 
<label>: Define una etiqueta para un campo de formulario. 
<font> y </font>: Define el estilo de la fuente (obsoleta en HTML5). 
<strong> y </strong>: Resalta texto en negrita (para énfasis semántico). 
<br>: Inserta un salto de línea. 
<nobr>: Evita el salto de línea en el texto (obsoleto). 
<p align="...">: Alinea un párrafo (obsoleto, se recomienda usar CSS). 
<ul>: Define una lista no ordenada (con viñetas). 
<ol>: Define una lista ordenada (numerada). 
<li>: Define un ítem dentro de una lista. 
<a> y </a>: Crea un enlace. 
<img>: Inserta una imagen.  

# 3 ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?  
- Un atributo es una característica adicional que proporciona información sobre el 
comportamiento o la apariencia de un elemento HTML, Los atributos van dentro de la 
etiqueta de apertura y generalmente se componen de un nombre y su valor, Se utilizan para 
configurar o modificar comportamientos de la etiqueta que pertenece.

- Id =" ": Para identificar un elemento único. 
class =" ": para Identificador de varios elementos. 
style =" ": Para darle un estilo al elemento. 
alt=" ": Proporciona un texto alternativo para elementos multimedia, como imágenes. 
href =" ": Para establecer URL de destino de un enlace. 
height =" ": Para determinar altura. 
width =" ": Para determinar ancho. 
src=" ": Para especificar la fuente de imágenes. 

# 4 ¿Qué es CSS y cómo se utiliza para el diseño web? 
- CSS “hojas de estilo en cascada” Básicamente, es un lenguaje que maneja el diseño y 
presentación de las páginas web, es decir, cómo lucen cuando un usuario las visita. Funciona junto con el lenguaje HTML que se encarga del contenido básico de los sitios. 

- Como se utiliza: CSS permite seleccionar elementos HTML específicos, como títulos, párrafos, imágenes, enlaces, etc.
- para aplicarles estilos. CSS puedes cambiar el color de los textos, establecer fuentes, ajustar tamaños, aplicar bordes, añadir sombras y controlar el espaciado entre los elementos. 

- CSS te ayuda a organizar el diseño de una página web, usando herramientas como el 
modelo de caja (para márgenes, bordes y rellenos) y técnicas de layout como Flexbox 
o Grid, que permiten una distribución más avanzada y responsiva. 

- Puedes hacer que el diseño se adapte a diferentes tamaños de pantalla, como 
móviles, tabletas y computadoras de escritorio. 
CSS permite agregar efectos visuales como transiciones y animaciones para hacer la 
página más interactiva y atractiva.

- Separación de contenido y diseño: CSS ayuda a mantener el código más limpio y 
organizado, separando la estructura (HTML) del estilo visual (CSS), lo que facilita su 
mantenimiento y actualización. 

# 5 ¿Que es una propiedad en CSS y menciona las propiedades más comunes? 
- Las propiedades CSS son elementos que determinan cómo se visualiza y se comporta el 
contenido en una página web HTML. Desde el color y el tamaño hasta el diseño y la 
animación, estas propiedades son esenciales para dar estilo a elementos como imágenes y 
texto. 

- Las más comunes son: 
color: Cambia el color del texto. 
font-size: Ajusta el tamaño de la fuente. 
background-color: Define el color de fondo de un elemento. 
margin: Controla el espacio exterior entre elementos. 
padding: Define el espacio interior dentro de un elemento. 
border: Añade un borde alrededor de un elemento. 
display: Establece cómo se muestra un elemento (por ejemplo, bloque o en línea). 
text-align: Alinea el texto dentro de un contenedor. 
width y height: Establecen el tamaño de un elemento. 
position: Controla la ubicación de un elemento en la página. 
font-family: Define la tipografía del texto. 
line-height: Establece la altura de la línea de texto. 
text-transform: Cambia la capitalización del texto (mayúsculas, minúsculas, etc.). 
font-weight: Ajusta el grosor de la fuente (normal, negrita, etc.). 
opacity: Controla la transparencia de un elemento. 
z-index: Controla el orden de apilamiento de los elementos (quién queda encima de 
quién). 
overflow: Controla lo que sucede cuando el contenido de un elemento se desborda 
(como ocultarlo o mostrar barras de desplazamiento). 
border-radius: Redondea las esquinas de un elemento. 
box-shadow: Añade sombras a un elemento. 
transform: Permite aplicar transformaciones (rotar, escalar, mover) a un elemento. 

# 6 ¿Qué es un selector en CSS y cuales tipos existen? 
los selectores nos ayudan a indicar el elemento sobre el que se van a aplicar los estilos. Los selectores pueden apuntar a elementos específicos, clases, identificadores o incluso 
atributos de un elemento. 

- Estos son los mas comunes, aunque hay más: 
p { color: blue; } = Selecciona todos los elementos <p>. 
.mi-clase { font-size: 16px; } = Selecciona todos los elementos con la clase mi-clase. 
#mi-id { color: red; } = Selecciona el elemento con el ID mi-id. 
*{ margin: 0; } = Selecciona todos los elementos de la página. 
input[type="text"] { border: 1px solid black; } = Selecciona los elementos <input> con el 
atributo type="text". 
div p { color: green; } = Selecciona todos los párrafos dentro de un <div>. 
div > p { color: orange; } = Selecciona los párrafos que son hijos directos de un <div>. 
h1 + p { font-weight: bold; } = Selecciona el primer párrafo que sigue a un <h1>. 
h1 ~ p { color: purple; } = Selecciona todos los párrafos que son hermanos de un <h1>. 
a:hover { color: red; } = Selecciona el enlace cuando el usuario pasa el cursor sobre él. 
p::first-letter { font-size: 2em; } = Selecciona la primera letra de cada párrafo. 

# 7 ¿Qué es JavaScript y cómo añade la interactividad a las páginas web? 
JavaScript es un lenguaje de programación construido para el navegador Netscape en 1995. 
Todos los navegadores modernos lo adoptaron desde entonces para añadir funciones a los 
sitios web y, más recientemente, a aplicaciones web. se utiliza para crear interactividad en las páginas web. Es un lenguaje interpretable y client-side, lo que significa que el código se 
- ejecuta directamente en el navegador del usuario, sin necesidad de pasar por un servidor. 
Permite que las páginas web no sean solo estáticas, sino que respondan a las acciones del 
usuario y puedan actualizarse en tiempo real sin necesidad de recargar toda la página 

- Manipulación del DOM: 
Modifica el contenido de la página (texto, imágenes, botones) de forma dinámica. 
Eje: Cambiar el texto de un párrafo al hacer clic en un botón. 

- Eventos: 
 Responde a interacciones del usuario como clics, movimiento del ratón, teclas, etc. 
Eje: Mostrar un mensaje emergente al pasar el ratón sobre una imagen. 

- Validación de formularios: 
Verifica que los datos ingresados sean correctos antes de enviar el formulario. 
 Eje: Comprobar que la contraseña tenga la longitud mínima. 

- Animaciones y efectos visuales: 
Crea efectos como transiciones, deslizamientos y cambios de color para mejorar la 
experiencia. 
Eje:  Cambiar el color de un botón cuando el usuario pasa el ratón.

- Comunicación asíncrona (AJAX): 
Realiza solicitudes al servidor sin recargar la página, permitiendo actualizar contenido 
dinámicamente. 

# 8 ¿Cuáles son los tipos de datos primitivos en Javascript? 
- Los tipos primitivos en JavaScript son aquellos valores que no son un objeto y tampoco tienen métodos. Además, los tipos primitivos son valores inmutables (no se pueden modificar). 

- String: Representa: Una secuencia de caracteres (texto). 
Sintaxis: 'texto' o "texto" 
Number: Representa: Números (enteros y decimales). 
Sintaxis: 123 o 3.14 
BigInt: Representa: Números enteros grandes. 
Sintaxis: 1234567890123456789012345678901234567890n 
Boolean: Representa: Un valor lógico, true o false. 
Sintaxis: true o false 
Undefined: Representa: Una variable que ha sido declarada pero no tiene valor asignado. 
Sintaxis: let x; (sin valor asignado) 
Null: Representa: La ausencia intencional de valor. 
Sintaxis: null 
Symbol:Representa: Un valor único e inmutable. 
Sintaxis: Symbol('descripcion') 

# 9 ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en JavaScript? 

- Las estructuras de control son la columna vertebral de cualquier lenguaje de programación, incluido PHP, JavaScript, y muchos otros. Permiten a los desarrolladores escribir código que tome decisiones lógicas, ejecute bloques de código repetidamente y más. 

- La Declaración if 
La declaración if es una de las estructuras de control más básicas y esenciales. Te permite 
ejecutar un bloque de código si, y solo si, una condición específica es verdadera. 
if (condicion) { 
 Bloque de código a ejecutar si la condición es verdadera 
} 

- La Declaración else 
La declaración else se usa junto con if para ejecutar un bloque de código cuando la condición 
if no se cumple (es decir, es falsa). 
if (condicion) { 
 Bloque de código a ejecutar si la condición es verdadera 
} else { 
 Bloque de código a ejecutar si la condición es falsa 
} 

- La Declaración else if 
Para casos en los que necesitas verificar múltiples condiciones, else if permite encadenar 
otra condición si la primera if es falsa. 
if (condicion1) { 
 Bloque de código a ejecutar si condicion1 es verdadera 

} else if (condicion2) { 
    Bloque de código a ejecutar si condicion2 es verdadera 
} else { 
     Bloque de código a ejecutar si ninguna de las condiciones anteriores es verdadera 
} 

- La Declaración switch 
La declaración switch es una alternativa a if cuando tienes múltiples casos para evaluar 
sobre una misma variable o expresión. 
switch (expresion) { 
    case valor1: 
         Bloque de código a ejecutar 
        break; 
    case valor2: 
        Bloque de código a ejecutar 
        break; 
    default: 
        Bloque de código a ejecutar si ninguno de los casos anteriores coincide 
} 

- Bucles for y while 
Los bucles for y while permiten repetir un bloque de código múltiples veces. for es útil cuando sabes cuántas veces quieres que se ejecute el bloque, mientras que while es ideal cuando quieres que el bloque se ejecute hasta que una condición deje de ser verdadera. 

- Bucle for 
for (inicio; condicion; incremento) { 
    Bloque de código a ejecutar en cada iteración 
} 
 Bucle while 
while (condicion) { 
    Bloque de código a ejecutar mientras la condición sea verdadera 
} 

# 10 ¿Por qué es importante usar nombres significativos para variables y métodos? 
Usar nombres significativos para variables y métodos es crucial en la programación por varias razones, ayuda a uno mismo como a otros desarrolladores a trabajar con el código de manera más eficiente y comprensible. 

Claridad: un nombre de variable descriptivo comunica el propósito y el contenido de la 
variable de manera clara.  

Mantenibilidad: un código con nombres de variables significativos es más fácil de mantener 
y actualizar en el futuro.  

Colaboración: en proyectos colaborativos, los nombres de variables significativos son 
esenciales para que los miembros del equipo comprendan el código de los demás y 
colaboren de manera eficiente.

Prevención de errores: nombres confusos o ambiguos de variables pueden llevar a errores 
difíciles de rastrear.  

Legibilidad del código: un código con nombres de variables significativos es más legible y 
fácil de seguir. 

Comunicación efectiva: los nombres de variables bien elegidos actúan como una forma de 
comunicación entre los desarrolladores 

Facilita el aprendizaje: cuando los desarrolladores novatos estudian código bien nombrado, 
pueden aprender más rápido y comprender los conceptos con mayor facilidad. 

# ¿Qué es una variable de entorno y por qué son importantes para JavaScript o la 
- programación en general? 
Una variable de entorno es una variable dinámica que contiene información del entorno en el 
que se está ejecutando un programa. Estas variables se utilizan para configurar parámetros 
de un sistema o aplicación sin necesidad de modificar el código fuente directamente. 
Las variables de entorno son pares clave-valor almacenados fuera del código fuente de la 
aplicación, generalmente en el sistema operativo o en el entorno de ejecución. Estas 
variables contienen información importante que puede ser utilizada por el sistema o las 
aplicaciones para cambiar su comportamiento sin tener que tocar el código directamente. 

- Seguridad: Permiten almacenar información sensible (como contraseñas o claves API) fuera 
del código fuente, evitando exponer datos confidenciales. 
- Configuración flexible: Facilitan la adaptación de la aplicación a diferentes entornos 
(desarrollo, producción, staging) sin necesidad de modificar el código fuente. 

- Portabilidad: Hacen que el código sea más portable y fácil de ejecutar en diferentes 
máquinas o servidores, ya que solo se necesitan cambiar los valores de las variables de 
entorno. 

- Facilitan la integración con servicios externos: Permiten almacenar de forma segura las 
claves de autenticación o tokens necesarios para interactuar con servicios de terceros (como APIs externas).

- Evitan la codificación rígida (hardcoding): Reducen la necesidad de codificar valores 
directamente en el código, mejorando la flexibilidad y mantenibilidad de la aplicación. 
Facilitan el despliegue en diferentes entornos: Ayudan a tener configuraciones específicas 
para cada entorno sin tocar el código, lo que facilita el despliegue y la gestión de la aplicación en producción, desarrollo, etc. 

- Mejor mantenimiento: El uso de variables de entorno permite que el código sea más fácil de mantener, ya que los cambios en la configuración no requieren modificar el código 
directamente. 

# 12 ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas? 
Las Herramientas para desarrolladores de Chrome son un conjunto de herramientas para 
desarrolladores web que están integradas directamente en el navegador Google Chrome. 
Herramientas para desarrolladores te permite editar páginas sobre la marcha y diagnosticar 
problemas con rapidez, lo que te ayuda a crear mejores sitios web en menos tiempo. 
¿Cómo se accede a las herramientas de desarrollo de Chrome? 

- Usando el Menú de Chrome: 
Haz clic en el botón de tres puntos verticales en la esquina superior derecha de Chrome. 
Ve a Más herramientas > Herramientas para desarrolladores o inspeccionar.

# 13 ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo? 
El panel "Elements" de las Herramientas de Desarrollo de Chrome es una de las herramientas 
más poderosas y útiles para los desarrolladores web. Este panel permite inspeccionar y 
modificar el HTML y CSS de una página web de manera visual y en tiempo real. 

# 14 ¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil? 
- El panel "Console" de las Herramientas de Desarrollo de Chrome es una de las 
herramientas más útiles para los desarrolladores, ya que permite interactuar con el código 
JavaScript de una página web en tiempo real, ver mensajes de error, advertencias, y registrar información durante la ejecución del script. 

# 15 ¿Qué información se puede obtener del panel "Network" y por qué es importante? 
- El panel Network de las Herramientas de Desarrollo de Chrome proporciona información 
detallada sobre todas las solicitudes de red realizadas por la página web. Esto incluye la 
carga de recursos como imágenes, scripts, hojas de estilo, archivos JSON, y solicitudes API. Es una herramienta esencial para analizar el rendimiento de la página, depurar problemas de 
