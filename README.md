# Historia de la República Dominicana

Web educativa con la línea de tiempo de la historia dominicana (53 fichas en 8 capítulos), la cronología presidencial de 1844 a 2028 y actividades para estudiantes.

Es un solo archivo (`index.html`), sin dependencias ni instalación. Funciona en computadora y celular, y admite modo claro y oscuro.

## Publicar gratis en GitHub Pages

1. Crea una cuenta en [github.com](https://github.com) si no tienes una.
2. Pulsa **New repository**. Ponle un nombre, por ejemplo `historia-rd`, márcalo como **Public** y créalo.
3. En el repositorio, pulsa **Add file → Upload files** y arrastra todos los archivos de esta carpeta: `index.html`, `README.md`, `VERIFICACION.md` y `.nojekyll`. Pulsa **Commit changes**.
4. Ve a **Settings → Pages**. En *Source*, elige **Deploy from a branch**; en *Branch*, elige **main** y la carpeta **/ (root)**. Pulsa **Save**.
5. En uno o dos minutos la web estará en `https://TU-USUARIO.github.io/historia-rd/`.

> El archivo `.nojekyll` empieza con un punto y puede quedar oculto en tu computadora. Si no lo ves, no pasa nada: la web funciona igual sin él.

## Editar el contenido

Todo el contenido está dentro de `index.html`, en el bloque `<script>` del final:

- `F`: las fichas de la línea de tiempo.
- `P`: la cronología presidencial.
- `POOL`: los acontecimientos del juego «¿Qué ocurrió primero?».

Puedes editar el archivo directamente en GitHub (icono del lápiz). La web se actualiza sola al guardar.

## Verificación histórica

El contenido se contrastó con fuentes el 12 de octubre de 2026. Consulta `VERIFICACION.md` para ver las correcciones realizadas y los puntos que conviene revisar con el Archivo General de la Nación.
