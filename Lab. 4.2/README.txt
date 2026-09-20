PROYECTO: Creación de una página web estilizada con CSS
CURSO: NCBTO - 2026-5CC - WADE 1000L - 3663ONL (Front-End Technologies and
       User Interface (UI) and Laboratory)
UNIVERSIDAD: Northbridge University
ESTUDIANTE: Gerardo J. Medina (GJ)
NUMERO DE ESTUDIANTE: 2507056253

DESCRIPCIÓN
-----------
Este proyecto es la continuación del laboratorio del Módulo 3
(index 3.1.html), ahora aplicando los conceptos del Módulo 4 sobre CSS.
La página fue construida en Visual Studio Code y gestionada con control
de versiones (Git/GitHub). Demuestra el uso de:

1. Estructura semántica del Módulo 3: <header>, <nav>, <main>, <section>,
   <article> y <footer>.

2. Selectores CSS:
   - De elemento (ej. body, h1, h2, footer, article) para aplicar un
     mismo estilo a todos los elementos de ese tipo.
   - De ID (ej. #sobre-mi, #contacto, #miLienzo) para aplicar un estilo
     único a un elemento o sección específica de la página.
   - De clase (ej. .btn, .tarjeta-destacada) para reutilizar un mismo
     estilo en varios elementos distintos (el enlace de GitHub y el de
     contacto comparten la clase .btn).

3. Modelo de caja (box model): el segundo artículo de la sección
   "Proyectos" usa la clase "tarjeta-destacada", con un padding, borde y
   sombra distintos al artículo anterior, demostrando cómo el modelo de
   caja permite variar el estilo de una sección específica.

4. Diseño responsivo: mediante una media query (@media max-width: 600px)
   la página ajusta el menú de navegación, el tamaño del título y el
   ancho del video/audio cuando se ve desde una pantalla pequeña.

5. Características de HTML5: <video>, <audio>, <canvas>, <figure> y
   <figcaption>, comentadas dentro del archivo "index 3.1.html".

ARCHIVOS INCLUIDOS
-------------------
- index 3.1.html   -> Estructura de la página con comentarios explicativos.
- style.css        -> Hoja de estilos con selectores, modelo de caja y
                       diseño responsivo, todo comentado.
- imagenes/        -> Carpeta con la captura del proyecto.
- audio/           -> Carpeta con el archivo de audio de prueba.
- videos/          -> Carpeta con el archivo de video de prueba.
- README.txt       -> Este archivo.

ENLACE DEL REPOSITORIO DE GITHUB
---------------------------------
https://github.com/medinalab3/lab-4-2-css-estilos

CÓMO VISUALIZAR EL PROYECTO
-----------------------------
1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Abrir el archivo "index 3.1.html" con la extensión Live Server o
   directamente con el navegador de preferencia.
3. Para probar el diseño responsivo, abrir las herramientas de
   desarrollador (F12), activar la vista de dispositivo móvil y reducir
   el ancho de la ventana a menos de 600px.
