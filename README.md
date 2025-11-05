# Landing Page — Resumen de cambios

> Breve README que resume los cambios realizados en el HTML y CSS, con fechas y un changelog fácil de extender.

Última actualización: 29 de octubre de 2025

## Descripción corta


## Cambios principales (resumen por archivo)

- css/styles.css — 03/11/2025
	- Alineación entre los íconos y el texto, creando una lista más ordenada y profesional. Los íconos ahora estarán perfectamente centrados con respecto al texto. `css/styles.css`

- index.html — 02/11/2025
	- Integración y cambio en los <div>, separando por secciones y así integrar de mejor manera los cambios en el `css/styles.css`
	<section class="section-one">
    <section class="section-two">
	- Se integra dentro de la <section class="section-two"> una nueva continuación de la landing page, para mostrar una lista <ul>, con check, y además de una nueva imagen con subtitulos.
- css/styles.css
	- Cambios en las etiquetas para integrar de mejor manera las <section> y agregar nuevos elementos de responsive.


- css/styles.css-index.html — 29/10/2025 
    - Actualización de estilos y estructura de la landing; responsive y componentes principales. — `index.html`, `css/styles.css`

- css/styles.css — 28/10/2025
	- Import de tipografías desde Google Fonts (`Inter` y `Martian Mono`).
	- Variables CSS en `:root` para paleta de colores y neutrales.
	- Estilos generales: fuente base, fondo, tipografías y limpieza de box model.
	- Componente `.mainContainer` con layout centrado y limitación de ancho (1100px).
	- Estilos específicos:
		- `#title`: gran título con gradiente aplicado a texto y tipografía monospace.
		- `.contentText`: párrafo de presentación con tamaño y color legibles.
		- `.primaryButton`: botón CTA con borde, icono y estados hover/focus.
		- `.componentTestimonial`: diseño del testimonial con avatar, grupo de estrellas y texto.
		- `.heroImage`: imagen destacada posicionada en desktop (position: absolute; left: 800px) y adaptada responsive en móvil/tablet.
	- Reglas responsive para 1024px, 768px y 480px ajustando fuentes, layout y comportamiento del hero y testimonial.


- index.html — 23/10/2025
	- Estructura principal añadida o actualizada:
		- `header .brand` con `logo.svg`.
		- Contenedor principal `.mainContainer` con `#title` (título multi-línea), `heroImage` (imagen responsiva), párrafo `.contentText` y botón `.primaryButton` con icono.
		- Componente de testimonial `.componentTestimonial` con `avatarImage`, `.meta`, `.starGroup` y `.testimonialText`.

## Changelog (formato extendible)

Añade nuevas entradas al final siguiendo el formato:

YYYY-MM-DD — Breve descripción — archivos afectados

Ejemplo actual:

- 2025-10-29 — Actualización de estilos y estructura de la landing; responsive y componentes principales. — `index.html`, `css/styles.css`

### Historial tomado desde git

- 2025-10-28 — Integraciones de CSS: botones, subtítulos, títulos y mejoras responsive. — `index.html`, `css/styles.css`
- 2025-10-23 — Integración de primeros archivos y carpetas. — `index.html`, `css/styles.css`

## Cómo añadir una nueva entrada

1. Edita `README.md` y añade una línea nueva al final del bloque "Changelog".
2. Usa la fecha del cambio, un texto breve y los archivos modificados.

Formato sugerido (copiable):

```
YYYY-MM-DD — Descripción corta del cambio — `ruta/archivo.ext`
```



