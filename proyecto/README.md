# Proyecto Integrador LM 2026

- Nombre: Proyecto Integrador LM 2026
- Usuario GitHub: gonzaloaragar-svg
- Tema: Musica urbana
- Justificación: Este proyecto nace para mostrar una idea personal y original con contenido pensado para ser claro, útil y visualmente atractivo. La temática elegida permite organizar información en listas estructuradas y presentarla con estilo propio. Además, ofrece una base sencilla para practicar HTML, XML y buenas prácticas de desarrollo web. La finalidad es crear un sitio útil y fácilmente ampliable en futuras entregas.

## Palabra del día
Contexto

## Contenido del proyecto
- `index.html`: página sobre géneros de música urbana y perfiles de artistas.
- `generos.html`: catálogo completo de géneros urbanos basado en los datos estructurados XML.
- `artistas.html`: biografías y discografía de los exponentes más destacados.
- `historia.html`: cronología y etapas clave de la música urbana contemporánea.
- `datos.xml`: catálogo estructurado de los géneros, con origen, categoría y posición.
- `img/`: imágenes optimizadas de los artistas que aparecen en la página.

## UD3 · Estructura HTML
Cosas que le faltan a `index.html` según los requisitos iniciales de la unidad:
1. **Metadatos completos en la cabecera (`<head>`)**: Faltaban las etiquetas `<meta name="description">`, `<meta name="keywords">` y `<meta name="author">`, así como adaptar el `<title>` al formato requerido (`Inicio | Nombre de tu proyecto`).
2. **Jerarquía y coherencia en los títulos**: Corrección de los niveles de encabezados (se saltaba a `<h3>` para la sección de cantantes en lugar de usar un segundo `<h2>`, y existía un `<h4>` duplicado para Luar la L).
3. **Estructura en bloques `<div>` comentados y nuevos elementos requeridos**: Faltaban los comentarios de navegación (`<!-- NAV: aquí irá el menú (UD4) -->`), división del contenido en bloques `<div>` comentados, separadores `<hr>`, bloques de citas (`<blockquote>`), fichas técnicas preformateadas (`<pre>`), pie con copyright (`&copy;`) y entidades HTML (incluyendo al menos una numérica).

### Tabla de validación W3C

| Página | Errores detectados en W3C Validator | Corrección aplicada |
| :--- | :--- | :--- |
| `index.html` | 2 errores de sintaxis en atributo `src` de `<img>` (*Illegal character in path segment: Space is not allowed* en `img/luar la l.jpg` y `img/bad bunnyç.jpg`). | Se normalizaron los nombres de las imágenes eliminando espacios y caracteres conflictivos (`luar-la-l.jpg` y `bad-bunny.jpg`), y se actualizaron las rutas en las etiquetas `<img>` a `img/luar-la-l.jpg` e `img/bad-bunny.jpg`. Tras la corrección: **0 errores**. |
| `generos.html` | 0 errores detectados. | Ninguna requerida; documento 100% válido y conforme a HTML5 en la primera comprobación. |
| `artistas.html` | 0 errores detectados. | Ninguna requerida; documento 100% válido y conforme a HTML5 en la primera comprobación. |
| `historia.html` | 0 errores detectados. | Ninguna requerida; documento 100% válido y conforme a HTML5 en la primera comprobación. |

### Qué he hecho en esta unidad
En esta unidad he transformado una portada básica en un sitio web completo de cuatro páginas respetando una jerarquía visual y semántica estricta. He implementado cabeceras con metadatos completos y títulos formalizados, estructurado el contenido en bloques `div` comentados con sangría coherente y añadido recursos avanzados como citas en bloque (`<blockquote>`), fichas técnicas alineadas en texto preformateado (`<pre>`) y entidades HTML tanto de carácter como numéricas. Por último, integré todo el catálogo de datos estructurados XML en una página dedicada y depuré el código hasta lograr cero errores en el validador oficial del W3C.

## Mapa del sitio

| Fichero | title | Qué contiene |
| :--- | :--- | :--- |
| index.html | Inicio \| Música Urbana | Portada principal: bienvenida, resumen de estilos musicales, ficha técnica comparativa en texto preformateado, perfiles destacados de artistas, cita cultural de Billboard, enlaces externos y pie de página. |
| generos.html | Géneros \| Música Urbana | Catálogo completo de géneros urbanos que recoge todos los elementos de datos.xml (Reggaetón, Trap, Hip Hop, Dembow Dominicano) con categoría, origen, descripción y posición, además de una ficha técnica detallada. |
| artistas.html | Artistas \| Música Urbana | Directorio de artistas urbanos con reseñas biográficas de figuras consagradas y emergentes, discografía destacada, galardones y una cita de autoría propia sobre el trabajo en estudio. |
| historia.html | Historia \| Música Urbana | Recorrido cronológico de la música urbana desde sus orígenes en los años 70 y 90 hasta su consolidación global en la actualidad, hitos culturales y etapas clave. |
