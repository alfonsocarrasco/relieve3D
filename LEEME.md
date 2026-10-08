# Komakali 3D · PWA

Archivos: index.html, manifest.webmanifest, sw.js e íconos. Súbelos juntos, en la misma carpeta, a un hosting con HTTPS.

## Publicar (elige uno)
- **Netlify:** entra a app.netlify.com/drop y arrastra esta carpeta. Te da una dirección https.
- **GitHub Pages:** crea un repositorio, sube los archivos y activa Pages en Settings > Pages.
- **Cloudflare Pages / Vercel:** también sirven, con subida directa de la carpeta.

## Instalar
- **Android (Chrome):** abre la dirección, toca "Instalar app" en Ajustes o el menú ⋮ > Instalar app.
- **iPhone (Safari):** Compartir > Agregar a pantalla de inicio.
- **Computadora (Chrome/Edge):** ícono de instalar en la barra de direcciones.

## Sin conexión
La primera vez necesita internet: Three.js, las fuentes y el conversor MP4 se cargan de internet y quedan guardados en el teléfono. Después la app abre sin conexión. El conversor MP4 pesa unos 30 MB y solo se descarga cuando tocas "Convertir a MP4".

## Si cambias algo
Cambia el número de versión en sw.js (const V="k39-v1") para que los teléfonos descarguen la versión nueva.
