# Gym Pulse

PWA de gimnasio personal en un único archivo `index.html`, pensada para abrirse desde Safari en iPhone y poder añadirse a la pantalla de inicio.

## Subir gratis a GitHub Pages

1. Crea un repositorio nuevo en GitHub.
   Si usas GitHub Free, hazlo público.
2. Sube el contenido completo de esta carpeta:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. En GitHub entra en `Settings`.
4. Abre `Pages`.
5. En `Build and deployment`, selecciona:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
6. Guarda los cambios y espera unos minutos.
7. GitHub te mostrará la URL pública de la app.

## Usarla en iPhone

1. Abre la URL pública de GitHub Pages en Safari.
2. Pulsa `Compartir`.
3. Elige `Añadir a pantalla de inicio`.

## Notas

- Los datos se guardan en `localStorage` del propio iPhone.
- Si cambias de dominio o borras los datos de Safari, el historial local puede desaparecer.
- Las gráficas usan `Chart.js` desde CDN, así que hace falta conexión a internet para cargar la librería.
