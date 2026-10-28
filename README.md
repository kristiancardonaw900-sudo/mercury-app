# Mercury

Aplicación de hábitos, enfoque, metas, estudios y finanzas. La interfaz principal está en `index.html` y guarda los datos en el `localStorage` del navegador.

## Abrir

- Para uso local, abre `index.html` en un navegador.
- Para instalarla como aplicación y permitir el almacenamiento sin conexión, sirve la carpeta por HTTPS o desde `localhost`. El service worker no funciona con una URL `file://`.

## Archivos

- `index.html`: aplicación y estilos.
- `icon.svg`: icono de la aplicación.
- `manifest.webmanifest`: metadatos de instalación.
- `sw.js`: caché del shell de la aplicación para uso sin conexión en un origen compatible.

Los datos siguen guardándose localmente en cada navegador; exporta un respaldo desde Configuración para conservarlos o trasladarlos.
