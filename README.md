# Middleman Base

Estructura base para la inicialización de un proyecto en [[https://middlemanapp.com/]](Middleman). 

El stack tecnológico en el que está construido este kit de inicialización es el siguiente:

- [Middleman](https://middlemanapp.com/)
- [https://getbootstrap.com/](Bootstrap 4)
- [https://sass-lang.com/](SASS)
- [https://bradfrost.com/blog/post/atomic-web-design/](Atomic Design)
- [https://gulpjs.com/](Gulp)

**Middleman**

Generador de sitios estáticos, basado en ruby, para la creación de sitios webs modernos.

**Bootstrap 4**

Framework CSS que se usa como base para el proyecto. Se incluye en su versión SASS.
Es recomendable no realizar modificaciones sobre el core del framework, para ello utilizaremos la capa CSS de Overrides siempre que sea posible.

Tomando como base todo lo que nos proporciona Bootstrap 4 crearemos nuestros elementos, componentes, bloques y estructuras propios, que dispondrán de sus propios archivos SCSS para aplicar los estilos personalizados del proyecto.

**SASS**

Preprocesador de CSS con el que se escribirá el todo el código CSS del proyecto en la carpeta Source.

**Atomic Design**

Metodología de desarrollo de CSS que nos permite modularizar todo el CSS para obtener un código más escalable, reutilizable y mantenible.

A la filosofía original de Diseño Atómico se le cambia la nomenclatura por una un poco más generalizada, resultando en:

- Elementos
- Componentes
- Bloques
- Páginas

**Gulp**

Utilizamos este automatizador de tareas para concatenar, minificar y ofuscar código JS así como para la optimización del peso de las imágenes post publicación.

Sientase libre de añadir sus propias funcionalidades.
