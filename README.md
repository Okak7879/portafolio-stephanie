# Portafolio de Stephanie Pardo

Sitio de una sola página (`index.html`), autocontenido: todas las fotos y videos están embebidos directamente en el archivo. No necesita build, ni dependencias, ni servidor — es HTML puro.

Cada tarjeta de proyecto enlaza a su propia página de detalle, publicada como Artifact en claude.ai. Eso significa que este repositorio solo necesita alojar `index.html`; las páginas de detalle ya viven en su propia URL y seguirán funcionando igual una vez este archivo esté en GitHub Pages.

## Publicarlo en GitHub Pages

1. Sube este archivo tal cual a un repositorio de GitHub (puede llamarse como quieras, por ejemplo `portafolio-stephanie`).
2. En GitHub, entra a **Settings → Pages**.
3. En "Build and deployment", selecciona **Deploy from a branch**.
4. Elige la rama `main` (o `master`) y la carpeta `/ (root)`.
5. Guarda. GitHub te da un link tipo `https://tu-usuario.github.io/portafolio-stephanie/` — tarda uno o dos minutos en activarse.

Listo — ese link ya es el portafolio en vivo.

## Actualizarlo más adelante

Cuando haya cambios (nuevas fotos, nuevos proyectos, ediciones), basta con reemplazar `index.html` por la versión nueva y subir el cambio (commit + push). GitHub Pages se actualiza solo en un par de minutos.
