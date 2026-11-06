# buap_servicio_social

Sitio web estático con la información del **Servicio Social de la Facultad de Ciencias de la Computación (FCC) de la BUAP** (Benemérita Universidad Autónoma de Puebla): qué es el servicio social, cómo inscribirse, qué se necesita para liberar el servicio y obtener el certificado, y las respuestas a las preguntas más frecuentes de los aspirantes.

Es un sitio legado, construido con páginas HTML/XHTML, CSS y JavaScript (biblioteca Spry de Adobe), sin backend: todo el contenido vive en las páginas del repositorio.

## Páginas del sitio

La entrada es `index.html`. Desde ahí se enlaza al resto del contenido:

| Página | Contenido |
| --- | --- |
| `index.html` | Portada del sitio de Servicio Social. |
| `intro.html` | Introducción. |
| `mision.html` | Misión. |
| `fcc.html` | La Facultad de Ciencias de la Computación. |
| `aspirantes.html` | Información para aspirantes. |
| `inscripcion.html` | Proceso de inscripción al servicio social. |
| `formulario.html` | Formulario de registro. |
| `requisitosCertificado.html` | Requisitos para el certificado. |
| `liberarServicioSocial.html` | Cómo liberar el servicio social. |
| `reglamento.html` | Reglamento del servicio social. |
| `bajas.html` | Bajas del servicio social. |
| `avisos.html` | Avisos. |
| `preguntas.html` | Preguntas frecuentes. |
| `consejos.html` | Consejos para realizar el servicio social. |
| `contacto.html` | Contacto. |

## Estructura

- Páginas HTML en la raíz del repositorio.
- `Scripts/` — JavaScript de apoyo (`swfobject_modified.js`, para contenido Flash histórico).
- `SpryAssets/` — Biblioteca Spry (`SpryAccordion.js` y su CSS), usada en los paneles desplegables.
- Carpetas de imágenes y recursos gráficos: `imgback/`, `imgCertificado/`, `imagenes_enlaces/`, `gif/`, `logo buap/`, `marco botones fcc/`, `vinetas/`, `popup/`, `fondo_video/`, `efecto agua/`, `intro_/`, además de `LOGO_BUAP.jpg`.

## Cómo verlo

No requiere instalación ni servidor: abre `index.html` en un navegador.

Si prefieres servirlo por HTTP (recomendado para que todas las rutas relativas se comporten igual):

```bash
python3 -m http.server 8000
# y abre http://localhost:8000 en el navegador
```

## Nota

Parte del material gráfico y de los scripts corresponde a la época del sitio original (XHTML 1.0 Transitional, Flash/SWF), por lo que algunos elementos históricos pueden no reproducirse en navegadores actuales; el contenido informativo de las páginas se conserva completo.
