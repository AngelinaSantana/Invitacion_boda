# Invitación de boda digital

Una invitación web: primero se ve un **sobre verde salvia con sello dorado**. Al tocarlo, el sobre se abre, la tarjeta sale y aparece la invitación completa (eucalipto, marco dorado, fondo marfil).

## Cómo editar los datos
Abre `index.html` y busca el bloque `const BODA = { ... }` (cerca del final). Ahí cambias:
- nombres, iniciales y fecha
- hora de la ceremonia, lugar y frase final
- `mapsUrl`: enlace de Google Maps del salón
- `whatsapp`: número para confirmar asistencia (con código de país, sin `+`; ej. `18095551234`)

Cambia también el `<title>` y las etiquetas `og:` del inicio del archivo: son el texto que se ve al compartir el enlace por WhatsApp.

## Cómo publicarla (gratis) con GitHub Pages
1. En GitHub: **Settings → Pages**.
2. En *Source*, elige la rama y la carpeta `/ (root)`, y guarda.
3. En unos minutos tendrás un enlace `https://<usuario>.github.io/Invitacion_boda/` para enviar por WhatsApp.
