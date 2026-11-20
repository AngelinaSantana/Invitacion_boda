# Invitación de boda digital

Primero se ve un **sobre verde salvia con sello dorado de iniciales**, rosas blancas, hojas doradas y paniculata, bajo luces cálidas. Al tocar el sello el sobre se abre (con forro interior), la tarjeta sale y aparece la invitación completa:

- Tarjeta principal (rosas blancas en acuarela, hojas doradas, marco dorado, fondo marfil)
- Cuenta regresiva
- Itinerario (ceremonia, recepción…)
- Código de vestimenta con paleta de colores
- Regalos
- Confirmación por WhatsApp
- Música de fondo opcional

## Cómo editar los datos
Abre `index.html` y busca el bloque `const BODA = { ... }`. Ahí cambias nombres, fecha, lugar, itinerario, vestimenta, regalos, número de WhatsApp y música.
El **día de la semana y el mes se calculan solos** a partir de `fecha`.

Cambia también el `<title>` y las etiquetas `og:` del inicio: es lo que se ve al compartir el enlace.

## Invitaciones personalizadas
La forma más fácil: abre **`enlaces.html`** (por ejemplo `https://<usuario>.github.io/Invitacion_boda/enlaces.html`), escribe el nombre del invitado y los lugares, y pulsa *Copiar enlace* o *Enviar por WhatsApp*.

O escríbelo a mano: Agrega al final del enlace el nombre del invitado y los lugares reservados:

```
https://<usuario>.github.io/Invitacion_boda/?invitado=Familia%20Pérez&pases=4
```

El sobre dirá "Para Familia Pérez", la tarjeta empezará con "Querido(s) Familia Pérez" y la sección de confirmación mostrará los 4 lugares reservados (también se incluyen en el mensaje de WhatsApp).

## Música (opcional)
Sube un archivo `musica.mp3` al repositorio y escribe `musica: "musica.mp3"`. Empezará a sonar al abrir el sobre y aparecerá un botón para pausarla.

## Publicarla gratis con GitHub Pages
1. En GitHub: **Settings → Pages**.
2. En *Source*, elige la rama y la carpeta `/ (root)`, y guarda.
3. En unos minutos tendrás tu enlace `https://<usuario>.github.io/Invitacion_boda/`.
