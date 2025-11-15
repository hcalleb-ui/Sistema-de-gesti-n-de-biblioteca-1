1. ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero diseñado para ser simple y fácil de leer en formato de texto plano. Permite dar formato a un documento usando una sintaxis intuitiva de caracteres especiales (como #, *, -) que luego se puede convertir fácilmente a HTML.

- Uso en Proyectos de Software
Markdown se ha convertido en el estándar para la documentación en proyectos de software debido a:

- Legibilidad: Su sintaxis limpia no interfiere con la lectura del texto.

- Velocidad: Permite crear documentación (archivos README, guías, wikis) rápidamente.

- Compatibilidad con Git: Al ser texto plano, es ideal para el control de versiones (Git), ya que los cambios y las diferencias (diffs) son fáciles de rastrear.

2. Ejemplo Práctico de Sintaxis de Markdown
A continuación se muestran los elementos de formato más comunes y su sintaxis:

Encabezados (Jerarquía de Títulos)

Énfasis
Se logra usando **doble asterisco** o __doble guion bajo__.

Se logra usando *un solo asterisco* o _un solo guion bajo_.

Listas
Lista No Ordenada:

- Elemento A

- Elemento B

- Elemento C

Lista Ordenada:

1. Primer paso

2. Segundo paso

3. Tercer paso

Bloques de Código
Código en línea: El comando es \git commit -m "Mensaje"``.

Bloque de código (con resaltado de sintaxis):

- Ventajas con GitHub
GitHub utiliza una versión extendida llamada GitHub Flavored Markdown (GFM), lo que potencia su uso:

README de Presentación: GitHub renderiza automáticamente el archivo README.md como la página de inicio del repositorio, actuando como la tarjeta de presentación del proyecto.

Mejoras de Colaboración: GFM añade herramientas esenciales para el trabajo en equipo, como:

Listas de Tareas: Permite crear checklists dentro de Issues o Pull Requests (- [x] tarea completada).

Menciones y Referencias: Se puede notificar a usuarios específicos (@nombreusuario) y vincular fácilmente a problemas o solicitudes de fusión (#123).

Documentación Unificada: Asegura un formato consistente en la documentación del repositorio, Issues, Pull Requests y Wikis, facilitando la comprensión y el mantenimiento.
