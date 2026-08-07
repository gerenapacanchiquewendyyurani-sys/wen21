README
==============================

PROYECTO: STAKEHOLDERS Y REQUERIMIENTOS DE SOFTWARE

1. DESCRIPCIÓN
------------------------------

Este proyecto consiste en una página web educativa sobre
stakeholders y requerimientos de software.

La página explica:

- Qué es un stakeholder.
- Características de los stakeholders.
- Clasificación de stakeholders.
- Requerimientos funcionales.
- Requerimientos no funcionales.
- Tipos de requerimientos no funcionales.
- Diseño responsive.
- Animaciones con CSS.
- Interacción utilizando jQuery.


2. ARCHIVOS DEL PROYECTO
------------------------------

El proyecto contiene los siguientes archivos:

index.html
    Contiene la estructura y el contenido de la página.

styles.css
    Contiene los estilos, colores, tablas, animaciones y
    diseño responsive.

m1.jpeg
    Imagen utilizada en la página.

README.txt
    Contiene la información y documentación del proyecto.


3. TECNOLOGÍAS UTILIZADAS
------------------------------

HTML5
    Se utiliza para crear la estructura de la página.

CSS3
    Se utiliza para los estilos, colores, tablas,
    animaciones y diseño responsive.

jQuery 3.7.1
    Se utiliza para agregar interacción al botón "Hide".


4. FUNCIONALIDAD DEL BOTÓN
------------------------------

El botón "Hide" permite ocultar la imagen de la página.

Cuando el usuario hace clic en el botón, la imagen desaparece
utilizando una animación de 1 segundo.

Código utilizado:

$(document).ready(function () {
    $("button").click(function () {
        $(".m1").hide(1000);
    });
});


5. STAKEHOLDERS
------------------------------

Un stakeholder es una persona, grupo u organización que puede
influir, verse afectado o tener interés en las actividades,
decisiones o resultados de un proyecto.

El proyecto presenta las siguientes clasificaciones:

- Stakeholders internos.
- Stakeholders externos.
- Stakeholders según poder e interés.
- Stakeholders primarios.
- Stakeholders secundarios.


6. REQUERIMIENTOS FUNCIONALES
------------------------------

Los requerimientos funcionales indican qué debe hacer el sistema.

Ejemplos:

RF-001: El sistema debe permitir registrar usuarios.

RF-002: El usuario podrá iniciar sesión con correo y contraseña.

RF-003: El sistema permitirá buscar libros por título.

RF-004: El usuario podrá prestar un libro.

RF-005: El administrador podrá eliminar usuarios.


7. REQUERIMIENTOS NO FUNCIONALES
------------------------------

Los requerimientos no funcionales indican cómo debe funcionar
el sistema y establecen características de calidad.

Ejemplos:

RNF-001: El sistema debe cargar en menos de 2 segundos.

RNF-002: Las contraseñas deben almacenarse cifradas.

RNF-003: El sistema debe estar disponible el 99,9 % del tiempo.

RNF-004: Debe funcionar en computadores y celulares.

RNF-005: La interfaz debe ser fácil de usar.


8. TIPOS DE RNF
------------------------------

El proyecto presenta los siguientes tipos:

- Rendimiento.
- Seguridad.
- Usabilidad.
- Accesibilidad.
- Disponibilidad.
- Escalabilidad.
- Mantenibilidad.
- Portabilidad.
- Compatibilidad.
- Confiabilidad.
- Restricciones tecnológicas.


9. DISEÑO RESPONSIVE
------------------------------

La página se adapta a diferentes tamaños de pantalla mediante
Media Queries de CSS.

MOBILE:
Menor o igual a 600px.

TABLET:
Entre 601px y 900px.

DESKTOP:
Mayor o igual a 901px.

La página muestra un indicador en la esquina inferior derecha
que informa el tipo de dispositivo.


10. ANIMACIONES
------------------------------

El proyecto utiliza diferentes animaciones CSS:

- Animación de aparición de los elementos.
- Cambio de color del título.
- Aumento del tamaño del título.
- Rotación y aumento de tamaño de la imagen.
- Movimiento de los requerimientos.
- Animación de los requerimientos no funcionales en dispositivos
  pequeños.


11. EJECUCIÓN DEL PROYECTO
------------------------------

Para ejecutar el proyecto:

1. Colocar todos los archivos en una misma carpeta.

2. Verificar que existan:

   index.html
   styles.css
   m1.jpeg
   README.txt

3. Abrir el archivo index.html en un navegador.

4. Se recomienda utilizar Google Chrome, Microsoft Edge
   o Mozilla Firefox.


12. jQuery
------------------------------

La página utiliza jQuery 3.7.1 mediante Google CDN.

Código utilizado en el HTML:

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

La conexión a Internet puede ser necesaria para cargar
la biblioteca jQuery.


13. OBJETIVO DEL PROYECTO
------------------------------

El objetivo es presentar de forma clara e interactiva los
conceptos de stakeholders, requerimientos funcionales y
requerimientos no funcionales, utilizando tecnologías web
como HTML, CSS y jQuery.


14. AUTOR
------------------------------

 Wendy Yurani Gerena Pacanchique

Proyecto académico realizado como actividad de aprendizaje
sobre desarrollo web y análisis de requerimientos.