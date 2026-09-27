# Portfolio fotográfico — GitHub Pages

## 1. Sustituir las fotografías

En la carpeta `images/` coloca tus fotografías con estos nombres:

- `hero.jpg` — portada
- `foto-01.jpg` a `foto-06.jpg` — galería principal
- `proyecto-bosques.jpg`
- `proyecto-icm.jpg`
- `proyecto-arquitectura.jpg`

Puedes usar JPG, PNG o WebP, pero si cambias las extensiones tendrás que modificar `index.html`.

## 2. Personalizar

Abre `index.html` y cambia:
- `TU NOMBRE`
- el correo electrónico
- los títulos y textos
- los nombres de las fotografías
- los enlaces de Instagram/Flickr

## 3. Publicar gratis en GitHub Pages

1. Crea una cuenta en GitHub.
2. Crea un repositorio nuevo. Por ejemplo: `portfolio-fotografia`.
3. Sube `index.html`, `style.css` y la carpeta `images`.
4. En el repositorio entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
6. Guarda.
7. GitHub generará una dirección similar a:
   `https://TUUSUARIO.github.io/portfolio-fotografia/`

No necesitas contratar hosting.

## Nota

La plantilla utiliza Google Fonts mediante una importación externa. Si quieres que la web funcione sin ninguna petición externa, elimina la primera línea de `style.css` y se utilizarán las fuentes de reserva.
