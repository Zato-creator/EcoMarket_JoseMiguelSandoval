Markdown
# 🌿 EcoMarket - Tienda Sostenible

## 📖 Descripción del Proyecto
EcoMarket es una plataforma web (e-commerce) dedicada a la visibilización y venta de productos ecológicos, reutilizables y sustentables. 

El objetivo de este proyecto es ofrecer una experiencia de usuario (UX/UI) "clean", transmitiendo calma y confianza mediante el uso de paletas naturales y espacios en blanco. Además, representa un reto técnico significativo: **toda la interactividad fue desarrollada utilizando estrictamente HTML5 semántico y CSS3 puro**, sin la intervención de JavaScript ni librerías externas.

## 🚀 Tecnologías y Metodologías Utilizadas
* **HTML5 Semántico:** Estructuración accesible y optimizada.
* **CSS3 Avanzado:**
  * Diseño responsivo mediante **CSS Grid** y **Flexbox**.
  * Enfoque de diseño **Mobile First**.
  * Interactividad sin JS: Implementación de *Checkbox Hack* para menús y botones, `scroll-snap` para carruseles, y validaciones de formularios en tiempo real con pseudo-clases (`:valid`, `:invalid`, `:not(:placeholder-shown)`).
* **Arquitectura de Código:** Aplicación rigurosa de la metodología **BEM** (Block, Element, Modifier).
* **Control de Versiones:** GitFlow y Conventional Commits.

## ![alt text](image![alt text]( /img/image.png).png) Capturas de Pantalla

### Versión Escritorio (Desktop)
> **Nota:** ![alt text](/img/image2.png)

### Versión Móvil (Mobile)
> **Nota:** ![alt text](/img/image3.png)
## ⚙️ Link de GitHub
https://github.com/Zato-creator/EcoMarket_JoseMiguelSandoval.git

## 🌐 Despliegue en Vivo (Live Demo)
El proyecto ha sido desplegado exitosamente y es accesible desde cualquier dispositivo.
👉 **[Haz clic aquí para ver el proyecto en vivo](https://ecomarket-website.vercel.app/)**


## 🚀 Últimas Actualizaciones: Sección de Blog y Artículos

Se ha trabajado en la optimización y maquetación de la sección del blog para mejorar la experiencia de usuario y la estética general del proyecto EcoMarket:

* **Corrección de enrutamiento:** Se ajustaron las rutas relativas (`../`) en `views/blog.html` garantizando la carga correcta del header global y los archivos CSS de layout.
* **Refinamiento UI en tarjetas:** Se implementó `border-radius` en las imágenes de las publicaciones para un acabado más suave y moderno.
* **Nueva Vista de Lectura (`articulo.html`):**
  * Estructuración semántica con HTML5 (`<main>`, `<article>`, `<aside>`).
  * **Layout con CSS Grid:** Diseño a dos columnas (contenido principal y barra lateral) completamente responsivo, adaptándose a una sola columna en dispositivos móviles.
  * **Sidebar maquetado con Flexbox:** Incluye tarjeta de autor, sección de artículos relacionados y un formulario de suscripción con estilos pulidos.
  * **Centrado de Layout:** Se limitó el ancho del contenedor principal a `1200px` con márgenes automáticos para proporcionar "aire" visual y evitar que el contenido se extienda a los bordes de la pantalla.

---
**Autor:** Jose Miguel Sandoval Jaimes