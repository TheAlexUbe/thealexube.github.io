# 🕒 Horario Personalizado - Optimizador de Tiempo

![GitHub last commit](https://img.shields.io/github/last-commit/tu-usuario/mi-horario?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/tu-usuario/mi-horario?style=flat-square)
![GitHub](https://img.shields.io/github/license/tu-usuario/mi-horario?style=flat-square)

Aplicación web para organizar tu tiempo durante vacaciones, priorizando actividades clave como vóley, guitarra y tiempo personal.

![Captura de pantalla](https://i.imgur.com/placeholder.png) *(Reemplazar con imagen real)*

## ✨ Características

- 📅 **Horario visual** por bloques de tiempo
- 🎯 **Priorización inteligente** de actividades
- 🔔 **Notificaciones** de cambios de actividad
- 📱 **Diseño responsive** para todos los dispositivos
- 🌓 **Modo oscuro/claro** automático
- 🔄 **Sincronización** entre dispositivos

## 🚀 Cómo Usar

1. **Accede a la aplicación**:


2. **Navega entre días** usando el selector superior

3. **Personaliza actividades** editando el archivo `schedule-data.js`

4. **Configura recordatorios** en tu calendario favorito

## 🛠️ Personalización

Edita estos archivos para adaptar a tus necesidades:

| Archivo | Propósito |
|---------|-----------|
| `index.html` | Estructura principal |
| `style.css` | Apariencia visual |
| `app.js` | Lógica interactiva |
| `schedule-data.js` | Contenido del horario |

Ejemplo de modificación de actividad:
```javascript
// En schedule-data.js
{
time: "17:00 - 18:00",
activity: "Tiempo Guitarra",
description: "Practica escalas y nuevas canciones",
icon: "fas fa-guitar",
category: "music"
}
