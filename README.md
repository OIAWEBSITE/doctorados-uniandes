# Doctorados Uniandes — prototipo web (octubre de 2026)

Micrositio responsive creado a partir de la presentación **Oct 2026 Propuesta Página Web doctorados.pptx**. Sitio estático, sin dependencias ni compilación.

## Publicación en GitHub Pages

1. Crear repositorio, por ejemplo `doctorados-uniandes`.
2. Subir `index.html`, `styles.css` y `script.js` en la raíz.
3. Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
4. Probar el buscador de programas, filtros, pestañas y enlaces en móvil/escritorio.

## Alcance y asuntos pendientes

- **17 programas:** catálogo conforme a la propuesta, con enlaces institucionales. El enlace individual de **Literatura** estaba incorrectamente asociado a Administración en el archivo fuente; por seguridad se enlazó al **directorio oficial general** hasta validar su dirección específica.
- **Boletín:** se enlaza a Airtable proporcionado en la presentación, sin reproducir datos ni inventar convocatorias vigentes. La automatización quincenal requiere una fuente y configuración autorizadas.
- **Flujo:** navegación orientativa, no un trámite transaccional ni Genially integrado. Falta validar pasos y enlaces de Beca Impacto País, ACADEMIA, curso de ética, PIVOT y reglamento con responsables.
- **Contenido:** identidad visual inspirada en la estética Uniandes (amarillo, negro, blanco), pero NO es un producto institucional aprobado ni usa el logotipo oficial.
- **Enlaces:** las rutas institucionales pueden cambiar; revisar periódicamente. El enlace de Airtable podría requerir autorización.

## Edición

- Datos de programas: `const programs` en `script.js`.
- Etapas de gestión: `const steps` en `script.js`.
- Enlaces y textos de secciones: `index.html`.
- Colores y estilos: `styles.css`.
