<div align="center">

# Darknes$

**Detecta. Analiza. Protege.**

Sitio web de *Darknes$*, servicio profesional de ScreenShare y análisis anti-cheat para servidores de FiveM.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=threedotjs&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222?logo=github)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

## Sobre el proyecto

Landing page de una sola página (single-page) para presentar el servicio de ScreenShare de Darknes$:

- Revisión remota en vivo de la PC del jugador
- Detección de cheats y software que dé ventaja injusta
- Análisis de procesos, archivos eliminados e historial de actividad
- Informe con evidencia para decidir sanciones con seguridad

## Secciones

| Sección | Descripción |
|---|---|
| Inicio | Hero con propuesta de valor y llamada a la acción |
| Sobre nosotros | Cómo funciona el servicio en 3 pasos |
| Capacidades | Qué se analiza durante un ScreenShare |
| Aplicaciones | Herramientas del servicio |
| Preguntas frecuentes | FAQ en acordeón |
| En números | Estadísticas |
| Contacto | Formulario de solicitud de ScreenShare |

## Tecnologías

- **HTML5 / CSS3 / JavaScript** (vanilla, sin build ni dependencias que instalar)
- [**Lenis**](https://lenis.darkroom.engineering/) — scroll suave
- [**Three.js**](https://threejs.org/) — elementos visuales 3D
- [**Inter**](https://fonts.google.com/specimen/Inter) (Google Fonts) — tipografía

Lenis, Three.js y la fuente se cargan por CDN, por lo que se necesita conexión a internet para verla completa.

## Estructura

```
.
├── index.html        # Página completa (HTML + CSS + JS)
├── 404.html          # Página de error personalizada
├── robots.txt        # Reglas para buscadores
├── .nojekyll         # Desactiva Jekyll en GitHub Pages
├── assets/           # Imágenes, favicon, etc. (para agregar)
├── .github/          # Plantillas de issues
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
├── CHANGELOG.md
└── README.md
```

## Uso local

No requiere instalación. Opciones:

```bash
# 1. Abrir directamente
# Doble clic en index.html

# 2. Servidor local (recomendado)
python -m http.server 8000
# luego visita http://localhost:8000
```

## Estado

En desarrollo. Ver [CHANGELOG.md](CHANGELOG.md).

## Contacto

Discord: *darkness.k7k*

## Licencia

Distribuido bajo licencia MIT. Ver [LICENSE](LICENSE).
