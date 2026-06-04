# SlideForge

**Editor local para crear slides con identidad institucional y exportarlas como PNG para PowerPoint.**

SlideForge es una app web estática de un solo archivo. No tiene backend, API, base de datos, analytics ni almacenamiento persistente. Las plantillas y el contenido viven solo en la RAM del navegador.

## Uso

1. Abre `index.html` en Chrome, Brave o Edge.
2. Carga fondos de plantilla para portada, contenido y cierre, o usa la demo.
3. Crea slides manualmente o importa CSV.
4. Edita el texto directamente sobre la vista previa.
5. Exporta la slide actual o todo el deck como PNG.
6. Pega los PNG en PowerPoint.

## CSV

Con encabezado:

```csv
tipo,titulo,cuerpo,dato,nota
cover,Presentación institucional,Resumen ejecutivo,,Equipo 2026
stat,Cobertura territorial,La muestra cubre 12 zonas,67%,Fuente: demo
```

Sin encabezado usa este orden:

```csv
tipo,titulo,cuerpo,dato,nota
```

Tipos válidos:

- `cover`: portada
- `content`: contenido
- `compare`: comparación
- `stat`: dato fuerte
- `close`: cierre

## Exportación

- 16:9: `1920×1080`
- 4:3: `1500×1125`
- Formato: PNG
- Flujo: `Canvas.toBlob()` → descarga local

## Privacidad

- Cero backend.
- Cero analytics.
- Cero cookies.
- Cero `localStorage` / IndexedDB.
- Cero subida de archivos.
- Al cerrar la pestaña, se pierde todo.

## Tech stack

- HTML/CSS/JS vanilla
- Canvas API
- FileReader API
- Contenteditable
- Sin build step

## Deploy

No necesitas deploy. Puedes abrir `index.html` localmente.

Si quieres compartir el código:

- GitHub Pages
- Cloudflare Pages
- Cualquier hosting estático

El código puede ser público; los datos del usuario no se suben nunca.

## Autor

Creado por Cris + Bela (Hermes Agent).
