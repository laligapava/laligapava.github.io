# La Liga Pava — Web oficial

Web inmersiva de La Liga Pava. HTML + CSS + JavaScript puro (sin dependencias ni build).

## Estructura
```
index.html        → página principal
liga-web.css      → estilos
liga-web.js       → interacciones (scroll, contadores, estadios, Pava Media, formularios)
assets/           → imágenes y logo
```

## Probar en local
Abre `index.html` en el navegador. (Para evitar restricciones de rutas, puedes servirlo con
`python3 -m http.server` y abrir `http://localhost:8000`.)

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub y sube todo el contenido de esta carpeta a la raíz.
2. En el repo: **Settings → Pages**.
3. En **Source**, elige la rama `main` y la carpeta `/ (root)`. Guarda.
4. En 1–2 minutos tu web estará en `https://<usuario>.github.io/<repositorio>/`.

> El archivo de entrada ya se llama `index.html`, así que GitHub Pages lo detecta automáticamente.

## Notas
- Los formularios envían los datos por correo a **laligapava@gmail.com** (abren el cliente de
  correo del visitante). Si más adelante quieres recibirlos automáticamente sin abrir el correo,
  se puede integrar un servicio como Formspree.
- Para cambiar una foto, sustituye el archivo dentro de `assets/` manteniendo el mismo nombre.

© La Liga Pava · Castelldefels — Sant Boi · Baix Llobregat
