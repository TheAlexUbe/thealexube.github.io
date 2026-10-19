# AeroLab

AeroLab es una experiencia web estática para explorar física, mecánica y dinámica de fluidos mediante simulaciones visuales en tiempo real con HTML5 Canvas y Tailwind CSS.

## Simulaciones incluidas

### 1. Motor de cuatro tiempos

Animación del ciclo Otto de 720 grados con cinemática de biela-manivela, válvulas sincronizadas, partículas de combustible, combustión, controles de RPM y avance paso a paso.

### 2. Flujo laminar y turbulento

Visualización Canvas del número de Reynolds, túnel con obstáculo, chorro laminar, inyección de tinte y presets de agua, aceite, glicerina y aire.

## Desarrollo

No requiere compilación. `index.html` carga Tailwind y las fuentes desde CDN, y ejecuta JavaScript nativo en el navegador. Para probarlo localmente:

```powershell
python -m http.server 4173
```

Los modelos son educativos y sirven como apoyo visual para comprender principios de mecánica y dinámica de fluidos.
