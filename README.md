# AstraCore AI (PWA Instalable para Celular y PC)

Aplicación web progresiva (PWA) de carta natal con motor astronómico offline, rueda zodiacal SVG y consultor astrológico con Gemini AI.

## Archivos incluidos en el paquete
- `index.html`: Aplicación principal (100% adaptable a pantallas móviles y escritorio).
- `manifest.json`: Configuración oficial PWA para que Android e iOS reconozcan la app al instalarla.
- `sw.js`: Service Worker que permite instalarla como aplicación nativa y usarla sin conexión.
- `icon-192.png` y `icon-512.png`: Íconos cuadrados recortados de la abejita astróloga para Android / Chrome.
- `apple-touch-icon.png`: Ícono de alta resolución (180x180) para iPhone / iPad (Safari).
- `favicon.png`: Ícono de pestaña del navegador.
- `abejita_2.jpg`: Imagen original completa de respaldo.

## Cómo subir a GitHub Pages e instalar en el celular
1. Sube **todos los archivos** de esta carpeta a la raíz de tu repositorio en GitHub.
2. Ve a **Settings > Pages**, selecciona la rama `main` (carpeta `/root`) y haz clic en **Save**.
3. Abre la URL de GitHub Pages en **Chrome (Android)** o **Safari (iPhone)**.
4. En Android te aparecerá el botón **"Instalar aplicación"** (o en el menú `⋮` > *Añadir a pantalla de inicio*). En iPhone toca **Compartir** > *Agregar a inicio*.
5. Se instalará en tu teléfono con el ícono de la abejita astróloga y pantalla completa.
