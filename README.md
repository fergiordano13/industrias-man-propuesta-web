# Industrias MAN — Propuesta Web (Prototipo)

Prototipo front-end (HTML/CSS/JS, sin backend) del sitio de Industrias MAN, basado en research competitivo (Breville + Ninja) y auditoría del sitio actual (industriasman.mx).

## Ver el sitio publicado

Una vez activado GitHub Pages (ver más abajo), el sitio queda disponible en:

```
https://<tu-usuario>.github.io/industrias-man-propuesta-web/
```

## Estructura

- `index.html` — Home
- `catalogo.html`, `catalogo-ventiladores.html`, `catalogo-licuadoras.html`, `catalogo-ollas.html`, `catalogo-refacciones.html` — Catálogo
- `pdp-*.html` — Fichas de producto (4)
- `carrito.html`, `checkout.html`, `confirmacion.html` — Journey de compra
- `nosotros.html`, `contacto.html`, `garantia-servicio.html`, `distribuidor.html`, `preguntas-frecuentes.html` — Páginas institucionales
- `manual-*.pdf` — Manuales de producto (3)

## Decisiones de diseño

- Azul de marca: `#003fa2` (sin cambios)
- Tipografía: Work Sans (títulos) + Public Sans (cuerpo/desplegables)
- Referencia estética: mezcla Breville (elegancia) + Ninja (energía comercial)
- Todo el contenido (fotos, testimonios, datos de contacto, garantía, precios) usa información real de Industrias MAN — nunca inventada

## Cómo activar GitHub Pages

1. En el repo de GitHub, ve a **Settings → Pages**.
2. En "Source", selecciona la rama `main` y la carpeta `/ (root)`.
3. Guarda. GitHub te dará la URL pública en 1–2 minutos.

## Flujo de trabajo para cambios futuros

1. Los cambios se hacen sobre estos mismos archivos (no se generan HTML nuevos sueltos).
2. Antes de subir un cambio a `main`, se revisa un resumen de qué se modificó.
3. Una vez aprobado, se sube con `git add`, `git commit` y `git push`.
