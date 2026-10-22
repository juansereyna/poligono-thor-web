# Polígono Thor · prototipo del rediseño

Sitio estático de 17 páginas para el rediseño de [poligonothor.com](https://www.poligonothor.com).

| Página | Archivo |
| --- | --- |
| Inicio | `index.html` (copia en `inicio.html`) |
| Reserva y pago | `reservar.html` |
| Pagos y políticas | `pagos.html` |
| Lecciones de tiro | `lecciones.html` |
| Cursos avanzados | `cursos.html` |
| Certificado DCCAE y membresías | `certificaciones.html` |
| Aprende (blog) | `aprende.html` + 8 artículos `aprende-*.html` |
| Guía legal | `guia-legal.html` |
| Gobierno | `gobierno.html` |

Es HTML, CSS y JavaScript sin dependencias ni paso de compilación: se sirve tal cual desde GitHub Pages o cualquier hosting.

## Estado

Prototipo. Los pagos y formularios están simulados y no cobran ni envían nada. Las páginas llevan `noindex` para que los buscadores no las confundan con el sitio actual.

Pendiente antes de producción:

- Conectar el botón de pago a la cuenta de GlobalPay Redeban.
- Conectar los formularios (cotización de Gobierno, portal de certificados, consulta de puntos).
- Precios de las membresías y enlace a la política de privacidad.
- Quitar la franja de prototipo y la etiqueta `noindex`.

## Imágenes

- **Fotos reales** de Polígono Thor (sedes, galería, DCCAE): se cargan desde `poligonothor.com/wp-content/uploads/`.
- **Imágenes generadas con IA** (FLUX 2 en YouArt) para lecciones, cursos y manejo evasivo. Llevan la etiqueta "Imagen ilustrativa" porque no muestran instalaciones ni personas reales del polígono. Se cargan desde `static.youart.ai`.
- **Fotos de Unsplash** en el blog, con crédito en cada artículo:
  - LOGAN WEAVER — https://unsplash.com/photos/man-doing-practice-shooting-3VXaCtUgp-E
  - Thomas Tucker — https://unsplash.com/photos/a-couple-of-guns-sitting-next-to-each-other-bUFWYWJt7zw
  - Mikhail Pavstyuk — https://unsplash.com/photos/selective-focus-photography-of-three-books-beside-opened-notebook-EKy2OTRPXdw
  - Giammarco Boscaro — https://unsplash.com/photos/book-lot-on-black-wooden-shelf-zeH-ljawHtg
  - Tingey Injury Law Firm — https://unsplash.com/photos/woman-holding-sword-statue-during-daytime-DZpc4UY8ZtY
  - Ainsley Myles — https://unsplash.com/photos/architectural-photography-of-hallway-LYmsz-TPEXA
  - Artem Zhukov — https://unsplash.com/photos/a-man-wearing-headphones-and-holding-a-gun-08M4vqU_Q-k
  - Thomas Tucker — https://unsplash.com/photos/black-semi-automatic-pistol-and-magazine-kVjj9zPshxU

Antes de producción conviene descargar todas las imágenes al repositorio, convertirlas a WebP y reemplazar las ilustrativas por fotos propias.
