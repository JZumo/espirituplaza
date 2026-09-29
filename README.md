# Una dosis de motivación 💛

Web de una sola página para animar a la futura profesora mientras estudia.

## Ejecutar en local
    npm install
    npm run dev
Abre http://localhost:5173. Para probarla en el móvil (misma wifi): npm run dev -- --host

## Dónde cambiar cosas
- Frases, mensajes especiales y firma: src/phrases.js
- Ilustraciones, colores y pegatinas: src/scenes.jsx
- Fotos o memes propios: ponlos en public/memes/ y añade image: '/memes/archivo.jpg' a la frase
- Estilos: src/styles.css

## Desplegar en Vercel
Sube la carpeta a GitHub e impórtala en vercel.com (detecta Vite solo), o ejecuta npx vercel dentro de la carpeta.
