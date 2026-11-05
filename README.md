# Triple Espresso - Café de especialidad

## ☕ Descripción del proyecto
**Triple Espresso** es la página web promocional para una cafetería de especialidad y espacio de estudio ubicada en la ciudad ficticia de Triple Peaks. El sitio permite a los visitantes consultar el concepto de la cafetería, revisar sus horarios de atención, ubicar la dirección física y realizar una reserva de mesa en línea mediante un formulario interactivo.

## 🚀 Funcionalidad
- **Navegación fluida:** Menú con enlaces que dirigen directamente a las secciones internas de reserva y contacto mediante desplazamientos o enlaces ancla.
- **Formulario de reserva:** Permite a los usuarios ingresar su nombre, cantidad de comensales, fecha/hora deseada y correo electrónico con validaciones nativas de HTML (`required`, campos de número con rango de 1 a 8 comensales, selector de fecha/hora y casilla de verificación de términos).
- **Diseño interactivo (Hover states):** Estados visuales al pasar el cursor sobre botones y enlaces de navegación y del pie de página para mejorar la experiencia de usuario (UX).
- **Acceso rápido y accesibilidad:** Incluye un enlace visible/focusable (*skip-link*) para saltar directamente al formulario de reserva.

## 🛠️ Tecnologías y técnicas utilizadas
- **HTML5 Semántico:** Estructuración limpia utilizando etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<form>`, `<footer>`, `<address>`).
- **CSS3 Bespoke:** Estilos personalizados estructurados en archivos externos sin dependencias de frameworks masivos.
- **Metodología Flexbox:** Utilizado para la alineación y distribución del menú de navegación, elementos del formulario y disposición vertical de los enlaces del pie de página.
- **Posicionamiento CSS:** Combinación de posicionamiento relativo y absoluto para la superposición exacta de imágenes de fondo y decorativas.
- **Tipografía Web:** Integración de Google Fonts con las familias *Inter* y *Noto Serif*.
- **Normalización CSS:** Inclusión de `normalize.css` para homogeneizar la renderización del código en diferentes navegadores.

## 💡 Ideas de mejora futura
1. **Diseño Adaptativo (Responsive Design / Media Queries):** Implementar puntos de interrupción (*breakpoints*) para optimizar completamente la visualización del sitio en dispositivos móviles y tabletas.
2. **Validación dinámica de formulario:** Incorporar JavaScript para manejar el envío del formulario mediante AJAX/FormSubmit y mostrar mensajes interactivos de confirmación al usuario sin recargar la página.
