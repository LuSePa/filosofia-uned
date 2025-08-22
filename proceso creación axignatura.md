# Guía de Actualización del Repositorio de Apuntes

Este documento sirve como recordatorio del proceso para añadir nuevas asignaturas y nuevos temas al sitio web alojado en GitHub Pages.

---

## ## Cómo Añadir una NUEVA Asignatura

Este proceso se realiza solo una vez por cada nueva asignatura. Crearemos la carpeta y su primer tema (`tema1.html`) en un solo paso.

1.  **Iniciar**: En la página principal del repositorio `filosofia-uned`, haz clic en `Add file` > `Create new file`.

2.  **Crear Carpeta y Archivo**: En el campo del nombre, escribe la ruta completa. La barra (`/`) es crucial para que GitHub cree la carpeta.
    * **Formato**: `Nombre De La Asignatura/tema1.html`
    * **Ejemplo**: `Historia de la Filosofía Antigua I/tema1.html`

3.  **Añadir Contenido**: Pega el código HTML completo del Tema 1 en la caja de edición.

4.  **Guardar**: Ve al final y haz clic en el botón verde `Commit changes...`. Esto creará la nueva carpeta y el archivo `tema1.html` dentro de ella.

5.  **Verificar Enlace**: La nueva página estará disponible en una URL con la siguiente estructura (recuerda que los espacios se convierten en `%20`):
    * `https://<tu-usuario>.github.io/filosofia-uned/Nombre%20De%20La%20Asignatura/tema1.html`

---

## ## Cómo Añadir un NUEVO Tema a una Asignatura EXISTENTE

Este es el proceso más común para añadir los temas 2, 3, 4, etc.

1.  **Navegar a la Carpeta**: En la página principal del repositorio, haz clic en la carpeta de la asignatura a la que quieres añadir un tema (por ejemplo, `Teoría del Conocimiento II`).

2.  **Iniciar**: Dentro de la carpeta, haz clic en `Add file` > `Create new file`.

3.  **Nombrar Archivo**: En el campo del nombre, escribe solo el nombre del nuevo archivo.
    * **Ejemplo**: `tema2.html`

4.  **Añadir Contenido y Guardar**: Pega el código HTML del nuevo tema y haz clic en `Commit changes...`.

5.  **Verificar Enlace**: El enlace seguirá la misma estructura que los temas anteriores de esa asignatura.
    * `https://<tu-usuario>.github.io/filosofia-uned/Teoría%20del%20Conocimiento%20II/tema2.html`

---
### ### Chuleta Rápida

* **Asignatura Nueva**: `Add file` en la raíz -> Escribir `Nombre Asignatura/tema1.html` -> Pegar y Guardar.
* **Tema Nuevo**: Entrar en carpeta de Asignatura -> `Add file` -> Escribir `temaX.html` -> Pegar y Guardar.
