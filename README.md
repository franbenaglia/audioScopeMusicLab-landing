# AudioScope Music Lab — landing

Sitio estático de presentación y política de privacidad de la app **AudioScope Music Lab**, pensado para
publicarse con GitHub Pages y enlazarse desde la ficha de Google Play.

| Archivo | Contenido |
|---|---|
| `index.html` | Landing en inglés. |
| `es.html` | Landing en español. |
| `privacy.html` | Política de privacidad en inglés. **Es la URL que pide Google Play.** |
| `privacidad.html` | Política de privacidad en español. |
| `styles.css` | Estilos. Sin fuentes, scripts ni recursos externos. |
| `AudioScope-Google-Play-Icon-512.png` | Icono de la app (512 × 512), también para la ficha de Google Play. |
| `AudioScope-Google-Play-Feature-Graphic-1024x500.png` | Gráfico de funciones original para la ficha de Google Play. |
| `feature-graphic.jpg`, `icon-192.png`, `favicon.png` | Versiones ligeras de las imágenes para la web. |
| `.nojekyll` | Indica a GitHub Pages que sirva los archivos tal cual. |

## Publicar

1. En GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**, rama `main`, carpeta `/ (root)`.
2. El sitio queda en `https://franbenaglia.github.io/audioScopeMusicLab-landing/`.
3. URL de la política de privacidad para Google Play:
   `https://franbenaglia.github.io/audioScopeMusicLab-landing/privacy.html`

## Cuando la app esté publicada

En `index.html` y `es.html`, sustituir el aviso

```html
<span class="badge">Coming soon to Google Play</span>
```

por el enlace a la ficha (cambiando el identificador si el definitivo es otro):

```html
<a class="button" href="https://play.google.com/store/apps/details?id=com.audioscope.musiclab">Get it on Google Play</a>
```

## Mantener la política al día

`privacy.html` y `privacidad.html` describen lo que hace la app hoy: sin permiso de internet, único permiso el del
micrófono, sin captura en segundo plano y sin recogida de datos. Si una versión cambia algo de eso, hay que
actualizar ambas páginas y su fecha de vigencia **antes** de publicar esa versión.

Contacto: feedback@fab-apps.com
