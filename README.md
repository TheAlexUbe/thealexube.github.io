# AeroLab

AeroLab es una experiencia web estática para explorar aviación, física y mecánica mediante simulaciones visuales en tiempo real con HTML5 Canvas y Tailwind CSS.

## Simulaciones incluidas

### 1. Aviación: AGL, MSL y conciencia del terreno

- Relación `AGL = MSL - elevación`.
- Panel visual con MSL, AGL, elevación y margen.
- Escenarios Aeropuerto, Costa, Cordillera y Aproximación.
- Relieve navegable, referencias visuales, modo piloto automático y alertas didácticas GPWS, PULL UP y CFIT.

### 2. Motor de cuatro tiempos

Animación del ciclo Otto de 720 grados con cinemática de biela-manivela, válvulas sincronizadas, partículas de combustible, combustión, controles de RPM y avance paso a paso.

### 3. Flujo laminar y turbulento

Visualización Canvas del número de Reynolds, túnel con obstáculo, chorro laminar, inyección de tinte y presets de agua, aceite, glicerina y aire.

## Desarrollo

No requiere compilación. `index.html` carga Tailwind y las fuentes desde CDN, y ejecuta JavaScript nativo en el navegador. Para probarlo localmente:

```powershell
python -m http.server 4173
```

Los modelos son educativos y no sustituyen cartas, procedimientos operativos, instrumentos certificados ni entrenamiento aeronáutico.
