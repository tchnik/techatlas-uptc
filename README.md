# TechAtlas UPTC

**Landing page educativa - Proyecto académico**  
**Autor:** JHONATAN GIRALDO  
**Código:** 202522863  
**Universidad:** Universidad Pedagógica y Tecnológica de Colombia (UPTC)

## Descripción

TechAtlas UPTC es una landing page de carácter académico para presentar una propuesta de consulta y aprendizaje de conceptos de sistemas informáticos. Incluye navegación adaptable a distintos tamaños de pantalla, apartados temáticos y un formulario de interés.

El sitio web es un prototipo independiente y no representa una página oficial de la universidad ni una versión web de la aplicación Android TechAtlas.

## Funcionalidades

- Página de inicio con presentación del proyecto y acceso a sus secciones.
- Tarjetas informativas sobre la propuesta y sus beneficios.
- Pestañas interactivas para explorar programación, redes y aplicaciones.
- Preguntas frecuentes desplegables.
- Indicador del progreso de lectura.
- Formulario con validación de campos, almacenamiento local, recuperación de borradores y opción para eliminar datos guardados.
- Vista adaptativa para dispositivos móviles, tabletas y computadores.

Los escenarios de uso incluidos en la página son ilustrativos; no se presentan como testimonios reales.

## Tecnologías

- HTML5 semántico.
- CSS3 y variables personalizadas de diseño.
- JavaScript ES6+ sin bibliotecas externas.
- `localStorage` para conservar temporalmente los campos del formulario.
- Integración opcional con Formspree para la recepción de mensajes.

## Estructura del repositorio

```text
.
├── index.html       # Página y estilos, componentes y lógica web
├── README.md        # Información del proyecto
├── .gitignore       # Exclusiones para control de versiones
└── .nojekyll        # Configuración para GitHub Pages
```

## Ejecución local

1. Descarga o clona el repositorio.
2. Abre `index.html` en un navegador moderno.
3. Navega por las secciones y comprueba las funciones del formulario.

Para revisar el comportamiento publicado, utiliza un servidor web o GitHub Pages.

## Publicación en GitHub Pages

1. Sube el contenido de esta carpeta a la **raíz** de tu repositorio.
2. En GitHub, abre **Settings > Pages**.
3. Selecciona **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
4. Guarda los cambios y consulta la dirección publicada por GitHub.

## Configuración del formulario

En `index.html` hay una constante llamada `FORM_ENDPOINT`. Debes establecer allí el enlace del formulario de tu cuenta de Formspree antes de habilitar el envío real de mensajes.

Hasta que esa dirección esté configurada, el formulario permite validar y conservar borradores en el navegador, pero **no envía mensajes a un servidor**. No introduzcas contraseñas, números de identificación ni información sensible en los campos de demostración.

## Autoría

JHONATAN GIRALDO - 202522863  
Proyecto académico UPTC.
