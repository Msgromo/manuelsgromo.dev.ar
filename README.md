# Portfolio profesional de Manuel

Portfolio personal desarrollado como sitio estático con HTML, CSS y JavaScript. No utiliza frameworks, dependencias externas ni proceso de build.

## Estructura

```text
.
├── index.html
├── 404.html
├── favicon.svg
├── css/
│   └── site.css
└── js/
    └── site.js
```

## Ejecutar en local

Puedes abrir `index.html` directamente en el navegador o levantar un servidor estático simple:

```powershell
python -m http.server 8080
```

Luego entra en `http://localhost:8080`.

## Publicar en GitHub Pages

1. Sube el repositorio a GitHub.
2. Ve a `Settings > Pages`.
3. En `Build and deployment`, selecciona `Deploy from a branch`.
4. Elige la rama `main` y la carpeta `/root`.
5. Guarda los cambios.

GitHub Pages publicará el sitio desde `index.html`.
