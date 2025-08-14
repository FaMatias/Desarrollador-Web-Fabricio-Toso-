# Fabricio Matías Toso | Desarrollador y Biotecnólogo

Este es el repositorio de mi sitio web personal y portafolio, donde muestro mis habilidades como desarrollador web y biotecnólogo. El sitio está construido con HTML puro y utiliza **Tailwind CSS** para los estilos, lo que permite un diseño moderno y responsive.

## Estructura del Proyecto

El proyecto es un único archivo `index.html` que contiene todas las secciones de la página:

-   **Inicio:** Una presentación profesional con un efecto de escritura dinámico.
-   **Mi Filosofía de Trabajo:** Describe mi enfoque y los tipos de proyectos que realizo. Incluye una función de texto a voz.
-   **Mis Servicios:** Una sección de tarjetas que destacan mis áreas de especialización.
-   **Mis Proyectos:** Un portafolio de proyectos con enlaces a sus respectivos repositorios.
-   **IA Hub:** Un espacio interactivo que demuestra la integración de la inteligencia artificial para la generación de imágenes y descripciones de productos.
-   **Contacto:** Un formulario para que los clientes potenciales se pongan en contacto conmigo.

## Corrección de Botón Responsive

Uno de los principales problemas que se identificaron fue que el botón principal de la sección de inicio, "¡Hablemos de tu proyecto!", no era responsive y se cortaba en pantallas móviles.

### Solución Implementada

La solución se basó en ajustar el tamaño de la fuente del botón utilizando las clases de Tailwind de forma condicional.

-   **Código original del botón:**
    ```html
    <a href="#contacto" class="main-btn">
        ¡Hablemos de tu proyecto!
    </a>
    ```

-   **Código corregido del botón:**
    ```html
    <a href="#contacto" class="main-btn text-base md:text-lg px-4">
        ¡Hablemos de tu proyecto!
    </a>
    ```

### Explicación de las Clases

-   `text-base`: Establece el tamaño de la fuente a un tamaño base por defecto, que es ideal para dispositivos móviles, asegurando que el texto quepa en una sola línea.
-   `md:text-lg`: A partir del punto de ruptura de pantalla mediana (`md`), el tamaño de la fuente se incrementa a `text-lg`. Esto restaura el tamaño original en pantallas de escritorio y tablets, manteniendo la coherencia del diseño.
-   `px-4`: Añade un relleno horizontal extra para que el botón no se vea comprimido en pantallas pequeñas.

Con este cambio, el botón se adapta de manera fluida a todos los tamaños de pantalla, mejorando la experiencia del usuario.

## Tecnologías Utilizadas

-   **HTML5:** Estructura básica del sitio.
-   **Tailwind CSS:** Framework de CSS para un diseño rápido y responsive.
-   **JavaScript:** Lógica de las animaciones, efectos de escritura y las funcionalidades de IA.
-   **Font Awesome:** Biblioteca de iconos para elementos visuales.
-   **Gemini API:** Integración para las herramientas de IA (Generador de Imágenes, Analizador de Proyectos y Texto a Voz).

## Contribuciones

Si encuentras algún error o tienes sugerencias de mejora, ¡no dudes en abrir un *issue* o una *pull request*!

---
