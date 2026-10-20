# Estudio Zou · Entrega

Landing para pasarle a cada cliente al terminar su web: qué se lleva, cómo trabajamos, qué opciones tiene después del lanzamiento y cómo contactarme.

Es un proyecto aparte del portfolio (estudiozou.netlify.app). Se publica como sitio propio en Netlify.

## Estilos

Se escriben en `scss/` y se compilan a `css/styles.css`, que trae solo las clases que usa la página. `abstracts/` y `base/` son copias de las del portfolio, para mantener la misma marca.

```
scss/
  main.scss
  abstracts/     variables y mixins
  base/          variables CSS, reset y tipografía
  components/    etiqueta, ventana, botón, link
  layout/        header, secciones y footer
  sections/      intro, entrega (qué te llevás, proceso, después) y contacto
  utilities/     accesibilidad
```

```
npm install
npm run build:css
```
