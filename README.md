# SlideForge

**Presentaciones profesionales con identidad institucional. 100% local, zero riesgo de fuga.**

## Qué es

SlideForge es una app web estática que permite crear presentaciones con tus plantillas institucionales, editar contenido en vivo y exportar como PNG pixel-perfect para pegar en PowerPoint.

**Todo corre en tu navegador.** No hay servidor, no hay base de datos, no hay API. Tus datos nunca salen de tu dispositivo.

## Para quién

- Académicos defendiendo tesis con identidad institucional
- Profesionales con plantillas corporativas restrictivas
- Cualquiera que necesite presentar sin subir sus datos a la nube

## Uso

1. Abre `index.html` en Chrome, Brave o Edge
2. Sube tus plantillas (portada, contenido, cierre)
3. Define tus slides con título y contenido
4. Edita en vivo con el editor visual
5. Exporta como PNG (4:3 o 16:9)

## Características

- **Zero backend**: Pyodide corre Python en el navegador para procesamiento de imágenes
- **Plantillas institucionales**: Sube tus propios fondos, respeta tu marca
- **Exportación PNG**: 1500×1125px (4:3) o 1920×1080px (16:9), listo para PPT
- **Edición en vivo**: Contenteditable sobre la diapositiva, sin formularios separados
- **Múltiples layouts**: Título, contenido, comparación, datos, cierre

## Deploy

No necesitas deploy. Solo abre `index.html` en tu navegador.

Si quieres compartirlo:
- Sube a GitHub Pages (el código, no los datos)
- Deploy en Cloudflare Pages
- O simplemente comparte el archivo HTML

## Tech Stack

- HTML/CSS/JS vanilla
- Pyodide (Python en el navegador) para procesamiento de imágenes
- Canvas API para exportación PNG
- Google Fonts (Inter)

## Privacidad

- **Cero datos salen de tu navegador**
- No hay analytics, no hay tracking, no hay cookies
- Las plantillas y contenido se almacenan solo en memoria RAM
- Al cerrar la pestaña, todo se pierde

## Licencia

MIT

## Autor

Creado por Cris + Bela (Hermes Agent)
