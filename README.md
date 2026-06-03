# Crucigrama: Vibraciones y Ondas

Aplicación web estática para una actividad en parejas de Física 11°.

## Archivos
- index.html: página principal.
- styles.css: diseño visual.
- script.js: lógica del crucigrama, verificación y envío.
- config.js: palabras, pistas y URL de Apps Script.
- apps_script.gs: recibe respuestas y las guarda en Google Sheets.

## Conexión con Google Sheets
1. Crea una hoja de cálculo.
2. Cambia el nombre de la primera hoja a `Respuestas`.
3. Ve a `Extensiones > Apps Script`.
4. Pega el contenido de `apps_script.gs`.
5. Implementar > Nueva implementación > Aplicación web.
6. Ejecutar como: Tú. Acceso: Cualquier usuario.
7. Copia la URL y pégala en `config.js` en `scriptURL`.

## Publicación
Sube `index.html`, `styles.css`, `script.js` y `config.js` a GitHub Pages, Netlify o similar.
