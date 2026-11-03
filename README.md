# TechAtlas UPTC

**Landing educativa académica** 
**Universidad:** Universidad Pedagógica y Tecnológica de Colombia (UPTC)

**Sitio publicado:** https://tchnik.github.io/techatlas-uptc/

## Descripción

TechAtlas UPTC es una landing page académica que presenta una propuesta para consultar y aprender conceptos de sistemas informáticos. Es un prototipo independiente; no es un sitio oficial de la universidad ni una versión web de la aplicación Android.

## Funcionalidades

- Navegación por secciones y diseño adaptable.
- Pestañas interactivas sobre programación, redes y aplicaciones.
- Preguntas frecuentes desplegables e indicador de progreso de lectura.
- Formulario con validación, borradores guardados en el navegador y opción para borrar los datos.

Los escenarios incluidos son ilustrativos y no corresponden a testimonios reales.

## Tecnologías

- HTML5, CSS3 y JavaScript ES6+ sin bibliotecas externas.
- localStorage para conservar temporalmente el borrador del formulario.
- Integración opcional con Formspree.

## Estructura

- index.html
- README.md
- .gitignore
- .nojekyll

## Ejecución local

Clona o descarga el repositorio y abre index.html en un navegador moderno.

## GitHub Pages

El sitio se publica desde la rama main, carpeta raíz (/). Puedes abrirlo aquí: [TechAtlas UPTC](https://tchnik.github.io/techatlas-uptc/).

## Formulario

En index.html, la constante FORM_ENDPOINT está vacía. El formulario valida y conserva los borradores en este navegador, pero no envía mensajes a un servidor hasta configurar una URL real de Formspree. No incluyas información sensible en los campos de demostración.
