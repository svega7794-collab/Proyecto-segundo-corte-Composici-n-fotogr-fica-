# Lo que tarda un adiós

Exposición fotográfica de Stephany Vega Corrales. Tres canciones, una despedida.

## Archivos

- `dist/index.html`: portada, recorrido y sala final del tríptico.
- `dist/01-vitrina.html`, `dist/02-silla.html`, `dist/03-collar.html`: capítulos.
- `dist/styles.css`, `dist/app.js`: diseño e interacciones.
- `dist/assets/`: fotografías, portada y tipografías locales.
- `render.yaml`: configuración de Render.

No necesita instalación, base de datos ni claves. Las fotos están incluidas completas. Las canciones se abren en una pestaña externa; no hay reproducción automática ni archivos de audio incluidos.

## Ver en tu equipo

Abre `dist/index.html` en un navegador. Si usas un servidor local, sirve la carpeta `dist`.

## Subir a GitHub

1. Descomprime el ZIP. No subas únicamente el ZIP: Render necesita los archivos extraídos.
2. Crea un repositorio, por ejemplo `lo-que-tarda-un-adios`.
3. Sube el contenido de esta carpeta. En la raíz del repositorio deben quedar `dist`, `render.yaml` y este archivo.
4. Conserva los nombres y la estructura de `dist/assets`.
5. Confirma la carga con Commit changes.

En iPad, toca el ZIP en Archivos para extraerlo. Si la carga web no conserva carpetas, usa un computador para arrastrar la carpeta `dist` completa o un cliente Git que admita carpetas. No subas todas las imágenes sueltas a la raíz.

## Publicar en Render

1. En Render selecciona New → Static Site. No elijas Web Service.
2. Conecta el repositorio de GitHub y selecciona la rama donde subiste los archivos.
3. Deja Root Directory vacío si `dist` está en la raíz del repositorio.
4. Build Command: `echo "Sitio estatico listo"`
5. Publish Directory: `dist`
6. Pulsa Deploy Static Site y espera la dirección pública.

También puedes usar New → Blueprint para que Render lea `render.yaml`.

## Personalizar

Los textos están en los HTML. Para cambiar una foto, sustituye su archivo en `dist/assets` con el mismo nombre. El diseño se adapta a móviles, iPad y computador. Las obras pueden ampliarse con un toque; Escape o Cerrar permite volver. Se respeta la preferencia de reducir movimiento.

## Referencias

Render: https://render.com/docs/static-sites
GitHub: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
Canciones: sitio oficial de Enrique Bunbury, enlazado en cada obra.
Referente visual: https://www.fundaciovilacasas.com/es/obres/chema-madoz

## Créditos

Propuesta, fotografías de base y textos de la exposición: Stephany Vega Corrales. Música y canciones: derechos de sus respectivos titulares. Exposición académica personal, sin afiliación con Bunbury.
Tipografía P052, URW Base35, distribuida bajo AGPL con excepción de fuentes; licencia incluida en assets/FONT-LICENSE.txt.
