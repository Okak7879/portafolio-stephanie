# Portafolio de Stephanie Pardo

Sitio 100% autoalojado — ya no depende de claude.ai. `index.html` es autocontenido (todas las fotos y videos van embebidos directamente en el archivo, no necesita build ni servidor), y cada tarjeta de proyecto enlaza a su propia página de detalle guardada localmente en las carpetas `portafolio-proyectos-1/` y `portafolio-proyectos-2/`.

## Estructura (subir las 3 cosas juntas, en la raíz del repo)

```
index.html
portafolio-proyectos-1/   (19 páginas de detalle)
portafolio-proyectos-2/   (14 páginas de detalle)
```

`index.html` enlaza a estas carpetas con rutas relativas (`portafolio-proyectos-1/proyecto-x.html`), así que las tres cosas tienen que quedar al mismo nivel — si mueves `index.html` a una subcarpeta, los links de las tarjetas se rompen.

Nota: dentro de esas carpetas hay algunas páginas viejas que ya no se enlazan desde `index.html` (proyectos que se renombraron o se fusionaron con otro más adelante). No hacen daño estando ahí — solo son las que no se usan hoy.

## Publicarlo en GitHub Pages

1. Sube este repositorio tal cual a GitHub (puede llamarse como quieras, por ejemplo `portafolio-stephanie`), conservando la estructura de carpetas de arriba.
2. En GitHub, entra a **Settings → Pages**.
3. En "Build and deployment", selecciona **Deploy from a branch**.
4. Elige la rama `main` (o `master`) y la carpeta `/ (root)`.
5. Guarda. GitHub te da un link tipo `https://tu-usuario.github.io/portafolio-stephanie/` — tarda uno o dos minutos en activarse.

Listo — ese link ya es el portafolio en vivo, completo, sin depender de ningún servicio externo (salvo los botones que sí van a Behance, Instagram o Drive, que son enlaces normales).

## Actualizarlo más adelante

- **Cambios en el diseño de la página principal o en el contenido de las tarjetas**: reemplaza `index.html` por la versión nueva y sube el cambio (commit + push).
- **Cambios dentro de una página de detalle de proyecto**: reemplaza el archivo correspondiente dentro de `portafolio-proyectos-1/` o `portafolio-proyectos-2/` y sube el cambio.
- **Proyecto nuevo**: agrega su página de detalle a cualquiera de las dos carpetas de proyectos y agrega la tarjeta correspondiente (con su link relativo) en `index.html`.

GitHub Pages se actualiza solo, en un par de minutos, después de cada push.
