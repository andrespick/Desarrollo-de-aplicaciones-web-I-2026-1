# Mi Primera Pagina Web

## Proposito del proyecto
Este proyecto es una practica inicial de desarrollo web. Incluye una pagina HTML con estilos CSS basicos y una interaccion simple con JavaScript.

## Objetivos de aprendizaje
- Estructurar contenido con HTML.
- Aplicar estilos visuales con CSS.
- Agregar interactividad con JavaScript.
- Documentar el proyecto correctamente en un `README.md`.

## Contenido del proyecto
- `Index.html`: pagina principal con:
  - Encabezado con nombre del estudiante.
  - Parrafo de descripcion.
  - Enlace al perfil de GitHub.
  - Imagen local en `img/foto.JPG`.
  - Boton que imprime un mensaje en consola.
- `img/foto.JPG`: imagen usada en la pagina.
- `README.md`: documentacion y preguntas teoricas.

## Requisitos
- Navegador web moderno (Chrome, Edge o Firefox).
- No requiere instalacion de dependencias.

## Instalacion
1. Descargar o clonar este repositorio.
2. Abrir la carpeta del proyecto en tu editor (por ejemplo, VS Code).

## Uso
1. Abrir el archivo `Index.html` en el navegador.
2. Verificar que se muestre:
   - Titulo: "Mi Primera Pagina".
   - Nombre del estudiante.
   - Enlace a GitHub.
   - Imagen local.
3. Hacer clic en el boton "Mostrar mensaje".
4. Abrir DevTools y revisar la consola para confirmar el texto:
   - `Hola Mundo desde JavaScript`.

## Preguntas y respuestas

### 1) Que es HTML y cual es su funcion en la web?
HTML (HyperText Markup Language) es el lenguaje que estructura el contenido de una pagina web. Define titulos, parrafos, enlaces, imagenes, listas y formularios.

### 2) Que es una etiqueta HTML y menciona las etiquetas mas comunes?
Una etiqueta HTML marca el tipo de contenido que el navegador debe interpretar.
Etiquetas comunes: `html`, `head`, `body`, `h1` a `h6`, `p`, `a`, `img`, `div`, `span`, `ul`, `li`, `form`, `input`, `button`.

### 3) Que es un atributo de una etiqueta HTML y menciona los mas comunes?
Un atributo agrega informacion o configuracion a una etiqueta.
Atributos comunes: `id`, `class`, `href`, `src`, `alt`, `title`, `style`, `type`, `name`, `value`, `placeholder`.

### 4) Que es CSS y como se utiliza para el diseno web?
CSS (Cascading Style Sheets) define la apariencia visual de una pagina: colores, fuentes, espaciados, distribucion y adaptacion a pantallas.

### 5) Que es una propiedad en CSS y menciona las propiedades mas comunes?
Una propiedad CSS es una caracteristica visual que se configura con un valor.
Propiedades comunes: `color`, `background-color`, `font-size`, `font-family`, `margin`, `padding`, `border`, `width`, `height`, `display`, `text-align`.

### 6) Que es un selector en CSS y cuales tipos existen?
Un selector indica a que elementos HTML se les aplicara una regla CSS.
Tipos comunes: selector de etiqueta (`p`), clase (`.clase`), id (`#id`), atributo (`[type="text"]`), pseudoclase (`:hover`), pseudoelemento (`::before`).

### 7) Que es JavaScript y como anade interactividad a las paginas web?
JavaScript es un lenguaje de programacion que permite controlar comportamiento en la pagina, responder a eventos y modificar el DOM en tiempo real.

### 8) Cuales son los tipos de datos primitivos en JavaScript?
`string`, `number`, `boolean`, `null`, `undefined`, `symbol`, `bigint`.

### 9) Como funcionan las estructuras de control de flujo como if, else, switch y bucles en JavaScript?
- `if` y `else`: ejecutan bloques segun condiciones.
- `switch`: compara una expresion con varios casos.
- Bucles (`for`, `while`, `do...while`): repiten instrucciones mientras se cumpla una condicion o durante una cantidad de iteraciones.

### 10) Por que es importante usar nombres significativos para variables y metodos?
Porque mejora la legibilidad, facilita mantenimiento, reduce errores y acelera el trabajo en equipo.

### 11) Que es una variable de entorno y por que son importantes para JavaScript o la programacion en general?
Es un valor externo a la aplicacion (por ejemplo, claves API o configuracion) que se carga en ejecucion. Permite separar configuracion del codigo, mejorar seguridad y facilitar despliegues en distintos entornos.

### 12) Que son las herramientas de desarrollo de Chrome y como se accede a ellas?
Son utilidades integradas en Chrome para inspeccionar, depurar y medir rendimiento de una web.
Acceso: tecla `F12`, `Ctrl + Shift + I` o clic derecho -> "Inspeccionar".

### 13) Que se puede hacer en el panel "Elements" de las herramientas de desarrollo?
Inspeccionar y editar HTML/CSS en tiempo real, revisar estilos aplicados, ver el modelo de caja y analizar la estructura del DOM.

### 14) Como se utiliza el panel "Console" de las herramientas de desarrollo y para que es util?
Permite ver mensajes (`console.log`, errores, advertencias), ejecutar JavaScript manualmente y depurar comportamiento de la pagina.

### 15) Que informacion se puede obtener del panel "Network" y por que es importante?
Muestra solicitudes HTTP, tiempos de carga, codigos de estado, tamano de recursos y errores de red. Es clave para diagnosticar problemas de carga y optimizar rendimiento.
