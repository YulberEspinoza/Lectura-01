# Lectura-01

## Configuración de Herramientas para Desarrolladores.
### Describe como los archivos HTML, CSS y JS son “analizados” en el navegador.
El navegador descompone en Html, Css y JavaScript, luego los junta todos para crear el diseño y hacer que la página sea renderizada. Luego de todo eso, reune de nuevo todos los archivos para crear el DON, CSSOM y luego empieza a calcular el Layou y pintar la pagina web segun los datos que tenga.

### ¿Cómo puedes encontrar imágenes para agregar a una página web?
Lo mas adecuador es buscarlas en las páginas web de google en donde podrás encontrar diversos tipos de imagenes y que se ajusten a tus requerimientos, sin embargo, debemos tener en cuanta que deben ser libres y sin que tengan derechos de autor por que entreriamos en conflictos.

### ¿Cómo creas una String en comparación con un Number en Javascript?
Para poder crear una variable lo mas adecuado es trabajarlo en formato de variable o constante como un conjunto de caracteres entre comillas y en cambio en el number es necesario expresarlo como numero, sin comillas. 

### ¿Qué es una Variable y por qué son importantes en JavaScript?
Las variables son muy importantes en javascript y en otros programas de programación, se necesita declararlos con las palabras claves de let, const y var. 

## Introducción a HTML.
### ¿Qué es un atributo en HTML?
El artibuto en html es un complemento a los elementos, esto quiere decir que nos ayuda a que con estos atributos se puedan desarrollar ciertas funcionalidades.

### Describe la anatomía de un elemento en HTML.
La anatomina de un html se desarrolla como un conjunto de elementos en la cabecera, luego el body y dentro de este los elementos del header, main y footer, todos ellos siempre tienen que tener una apertura y al momento de terminar nuestro código una cerradura.

### ¿Cuál es la diferencia entre las etiquetas y <article> y <section>?
El article se usa mas para una composición completa de una página, mientras que la section se utiliza mas para poder agrupar elementos que tengan cierta relación.
 
### Qué elementos se incluyen en una página web “típica”?
Los elementos de una página web típica sería el uso de las etiquetas secction, p, h1,h2,h3,h4,h5 y h6, junto con los div, nav y a.

### ¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?
Los metadatos influyen en el SEO al ayudar a los motores de busqueda a entender y clasificar el contenido de una pagina web. Elementos como el titulo, la descripción meta mejoran el CTR y su vcisibilidads. Además, los datos estructurados y las etiquetas alt de imágenes también contribuyen a una mejor indexación y accesibilidad.

### ¿Cómo se utliza la etiqueta en HTML cuando se quiere especificar metadatos?
<meta charset="utf-8">: Este elemento representa metadatos que no pueden ser representados por otros elementos HTML relacionados con metadatos, como <base>, <link>, <script>, <style> o <title>. El atributo charset especifica la codificación de caracteres para su documento como UTF-8, que incluye la mayoría de los caracteres de la gran mayoría de los lenguajes humanos escritos. Con esta configuración, la página ahora puede manejar cualquier contenido textual que pueda contener. No hay razón para no configurar esto, y puede ayudar a evitar algunos problemas más adelante.

## Miselania
### ¿Qué es necesario hacer, y en qué orden, para alcanzar mis metas?
La mayoria de proyectos fallan, no por falta de conocimiento técnico sino por falta de objetivos y visión.

### ¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?
La pregunta mas importante a reponder es: ¿Qué es exactamente lo que quiero lograr?, esta pregunta es el inicio y la motivacion que debes tener para poder realizar lo demas.

## Semántica.
#### ¿Por qué se debe utilizar un elemento h1> en vez de un span para mostrar un título de primer nivel?
Se debe de usar h1 por que de esa manera se obtiene un valor semantico y siempre se usa para encabezados, span es para que simplemente parezca un encabezado, y no tendra valor semantico, por lo que no tendra ningun beneficio adicional. ¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML? Estos son algunos beneficios:
- Los motores de búsqueda considerarán su contenido como palabras clave importantes para influir en las clasificaciones de búsqueda de la página (ver SEO).
- Los lectores de pantalla pueden usarlo como señal para ayudar a los usuarios con discapacidad visual a navegar por una página.

### ¿Qué es JavaScript?
Describe 2 cosas que requieran de JavaScript en el navegador.
Mostrar un mensaje emergente meidante un prompt sería un ejemplo de interactividad básica que requiere JavaScript en un navegador, o talvez un reloj que simplemente te muestre la hora.

## ¿Cómo se puede añadir JavaScript a un documento en HTML?
En línea (Inline): Utiliza la etiqueta <script> para insertar JavaScript directamente en el HTML. Puedes colocarla en la sección <head> o en el cuerpo (<body>) del documento, según cuándo desees que se cargue el JavaScript.
Archivo externo: Crea un archivo JavaScript con extensión .js y luego enlázalo al HTML mediante la etiqueta <script> con el atributo src. Así, el navegador descargará el archivo JavaScript junto con el documento HTML.
