# Sorpresa especial

Una página web romántica y adaptable a móviles, hecha con HTML, CSS y JavaScript sin dependencias externas. Incluye una galería, mensajes interactivos y un reproductor de música.

## Contenido

- `index.html`: página y estilos.
- `images/`: fotografías de la galería.
- `audio/confianza.mp3`: canción del reproductor.

La música no se reproduce automáticamente: pulsa el botón de reproducción para iniciarla. El reproductor también permite pausar, cambiar el volumen y buscar una posición de la canción.

## Probar en tu equipo

Abre una terminal en la carpeta del proyecto y ejecuta:

```powershell
py -m http.server 8000
```

Después visita <http://localhost:8000>. También puedes abrir `index.html` directamente, aunque un servidor local se comporta más parecido al sitio publicado.

## Publicar con GitHub Pages

1. Crea un repositorio en GitHub y sube el contenido de esta carpeta, conservando las carpetas `audio/` e `images/`.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama principal (`main`) y la carpeta raíz (`/`), y guarda.
5. Espera a que termine el despliegue. GitHub Pages mostrará la dirección pública del sitio en esa misma sección.

No se necesita instalar dependencias ni ejecutar un paso de compilación.

## Antes de compartir

Revisa que tienes permiso para publicar la canción y las fotografías en el repositorio y en el sitio web. Comprueba también que el texto y las imágenes personales se pueden compartir públicamente; si no, configura el repositorio como privado y ten en cuenta que GitHub Pages puede requerir un plan compatible para publicar desde repositorios privados.
