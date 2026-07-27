# Mi Entrenamiento (PWA)

App de seguimiento de entrenamiento: rutina PPL/Torso-Pierna, mesociclos con RIR
automático, timer de descanso, cronómetro de sesión, mapa muscular y evolución
de 1RM. Exporta datos a un .xlsx compatible con la planilla de mesociclos.

## Instalar
1. Subí esta carpeta a un hosting estático (GitHub Pages, Netlify, etc.) o abrí
   `index.html` directamente en el navegador.
2. En el celular: abrí el link → menú del navegador → "Agregar a pantalla de inicio".

## Archivos
- `index.html` — la app
- `manifest.json` — metadata PWA
- `sw.js` — service worker (offline)
- `icons/` — íconos de instalación

Los datos se guardan en el dispositivo (localStorage). Usá "Exportar a Excel"
en Ajustes para hacer respaldo o pasar el historial a tu planilla.
