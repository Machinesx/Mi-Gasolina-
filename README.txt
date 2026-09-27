MI GASOLINA - PWA

Contenido:
- index.html: aplicación completa.
- manifest.webmanifest: instalación como aplicación.
- sw.js: caché/offline de la PWA.

Datos:
- Se guardan en localStorage del navegador/dispositivo.
- Copia JSON: respaldo completo y traslado entre dispositivos/navegadores.
- Importar JSON: recupera una copia.
- CSV: exportación para Excel/LibreOffice.
- Borrar todos los datos: requiere confirmación.

IMPORTANTE:
Para que la instalación PWA y el modo offline funcionen, la aplicación debe servirse desde HTTPS (por ejemplo, GitHub Pages). Abrir index.html directamente como archivo local permite usar la aplicación, pero el service worker no puede registrarse desde file://.
