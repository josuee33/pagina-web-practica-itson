# Ingeniería en Software del ITSON — página informativa

Página informativa sobre la carrera de Ingeniería en Software del ITSON.
Es la misma página que ya estaba publicada en Muse, lista para subir a GitHub.

> Página informativa, no oficial del ITSON. Verifica requisitos, planes de estudio
> y fechas en los canales oficiales antes de tomar una decisión.
> - Programa: https://sandbox.itson.edu.mx/oferta/isw/Paginas/isw.aspx
> - Admisiones: https://www.itson.mx/admisiones
> - Oferta educativa: https://itson.mx/oferta

## Archivos

- `index.html` — toda la página: HTML, CSS y JavaScript en un solo archivo.
- `assets/hero-itson.webp` — foto principal (Rectoría del ITSON).
- `assets/lab.jpg` — foto de la sección de ruta de estudio.
- `assets/team.jpg` — foto de la sección de campo laboral.
- `README.md` — este archivo.

No hay que instalar nada ni compilar nada: es una página estática.

## Cómo publicarla en GitHub Pages (sin usar la terminal)

1. Entra a [github.com](https://github.com) y crea un repositorio nuevo, por ejemplo
   `ingenieria-en-software-itson`. Déjalo público.
2. En el repositorio, pulsa **Add file → Upload files**.
3. Sube `index.html`, `README.md` y la carpeta `assets` completa, con sus 3 imágenes.
   Importante: `index.html` tiene que quedar en la raíz del repositorio,
   y las imágenes en `assets/`.
4. Pulsa **Commit changes**.
5. Ve a **Settings → Pages**.
6. En **Build and deployment → Source**, elige **Deploy from a branch**,
   rama `main` y carpeta `/ (root)`. Guarda.
7. Espera 1-2 minutos. Tu página quedará en:

   `https://TU-USUARIO.github.io/ingenieria-en-software-itson/`

   Cambia `TU-USUARIO` por tu usuario de GitHub y el nombre final por el
   nombre que le hayas puesto al repositorio.

## Con git, desde la terminal (opcional)

```bash
git init
git add index.html README.md assets
git commit -m "Página Ingeniería en Software ITSON"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/ingenieria-en-software-itson.git
git push -u origin main
```

Después activa GitHub Pages como en el paso 5 de arriba.

## Editar la página

Abre `index.html` en cualquier editor de texto. Todo el contenido está ahí:
objetivo, perfiles, competencias, ruta de estudio, campo laboral, campus
(Obregón, Guaymas y Navojoa), admisión y preguntas frecuentes.

Si cambias una imagen, pon el archivo nuevo en `assets/` y actualiza su nombre
en el `src` correspondiente dentro de `index.html`.
