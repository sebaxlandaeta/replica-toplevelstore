# 🎮 Top Level Store — Maqueta Web Responsive 🚀

¡Bienvenido! 👋 Esta es una maqueta web completamente responsive inspirada en la interfaz y diseño de [Top Level Store](https://toplevelstore.com/). 🛍️✨

El proyecto fue creado como solución a un desafío práctico de la academia **CADIF1** 🎓, poniendo a prueba el uso de **Sass (SCSS)** avanzado y la implementación de una arquitectura modular mediante archivos parciales. 🎨🔥

---

## 🌐 Live Demo
👉 **[Haz clic aquí](https://tu-usuario.github.io/tu-repositorio/)**

---

## 🛠️ Tecnologías y Herramientas 🧰

* 📄 **HTML5**: Estructura semántica y accesible de toda la maqueta.
* 🎨 **Sass / SCSS**: Modularizado a través de archivos parciales (`_variables.scss`, `_mixins.scss`, `_placeholders.scss`, `_functions.scss`) e importados en la hoja de estilos principal.
* 📐 **CSS Flexbox & CSS Grid**: Layouts responsivos para la barra de navegación, el banner promocional, el catálogo de juegos y el footer.

---

## 📋 Resumen del Desafío Técnico (CADIF1) 📝

La lógica Sass de este repositorio responde a los 5 requerimientos clave exigidos por la academia (implementados organizadamente en sus correspondientes archivos parciales):

1. 🔘 **Mixin & Placeholder para Botones:** Creación de un `%placeholder` y `@mixin` para estandarizar el diseño de los botones principales (formato de bordes, padding y alineación Flexbox).
2. 📏 **Variable Global de Ancho (`$anchoBoton`):** Definición de la variable global `$anchoBoton` inicializada por defecto en `25px` en el parcial `_variables.scss`.
3. 🎨 **Función `formatoBoton()` y Validación RGB:** Desarrollo de una función dinámica en `_functions.scss` que recibe el ancho y parámetros opcionales `$r, $g, $b`. Incluye una advertencia de consola (`@warn`) en caso de ingresar valores fuera del rango RGB estándar (`0 - 255`).
4. ⚙️ **Cálculo Aritmético y Control de Ancho:** Operación interna que evalúa `$ancho * 5`. Si el resultado supera los `125px`, ajusta automáticamente el ancho del elemento y le asigna su color de fondo dinámico.
5. 🚨 **Control de Errores en Consola (`@error`):** Si la variable global `$anchoBoton` es menor a `20px` (haciendo que el cálculo `$ancho * 5` sea inferior
