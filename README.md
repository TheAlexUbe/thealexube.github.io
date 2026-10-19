# AeroLab

Sitio estático para GitHub Pages centrado en conceptos aeronáuticos. La experiencia principal es el simulador de conciencia del terreno, con cálculo de:

- **Altitud MSL**: referencia vertical sobre el nivel medio del mar.
- **Altura AGL**: separación entre la aeronave y el terreno.
- **Elevación**: cota del terreno sobre MSL.
- **Margen de seguridad**, estados GPWS y alerta didáctica de CFIT.

Incluye dos módulos secundarios: un ciclo Otto de motor de cuatro tiempos y una visualización de flujo laminar/turbulento basada en un número de Reynolds estimado.

## Desarrollo

No requiere compilación ni servidor: `index.html` carga Tailwind desde CDN y ejecuta JavaScript nativo en el navegador. Para probarlo localmente basta con abrir el archivo o servir el directorio con cualquier servidor estático. Es compatible con GitHub Pages.

Los modelos son educativos y no sustituyen cartas, procedimientos, instrumentos certificados ni entrenamiento aeronáutico.
