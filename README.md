# Leonel Fernández en Harvard / Leonel Fernández at Harvard

Sitio bilingüe del reporte del evento celebrado en el John F. Kennedy Jr. Forum, Institute of Politics, Harvard Kennedy School, el 28 de septiembre de 2026. Los reportes están fechados el 30 de septiembre de 2026.

**Preparado por ODLC / Prepared by ODLC.**

## Nombre del repositorio

`LEONEL-FERNANDEZ-HARVARD-2026`

Descripción sugerida:

> Reporte bilingüe y transcripción del encuentro con Leonel Fernández en Harvard: democracia, diáspora y geopolítica. 28 de septiembre de 2026. Español / English.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo con el nombre indicado, dentro de la cuenta u organización que prefieras.
2. Descomprime el ZIP y abre su carpeta.
3. En el repositorio, pulsa **uploading an existing file** o **Add file → Upload files**.
4. Sube el contenido de la carpeta. `index.html` y `en.html` deben quedar en la raíz, junto con `README.md` y la carpeta `documentos`.
5. Guarda con **Commit changes** en `main`.
6. Si no se carga `.nojekyll`, créalo con **Add file → Create new file**; utiliza `.nojekyll` como nombre y `# Static bilingual site` como contenido.
7. En **Settings → Pages**, selecciona **Deploy from a branch**, **main**, **/(root)** y **Save**.
8. GitHub mostrará el enlace público cuando termine el despliegue.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Archivos

```text
index.html                         Español
en.html                            English
documentos/
  reporte-harvard-es.docx
  reporte-harvard-en.docx
README.md
.nojekyll
```

Las dos páginas incluyen sus estilos y funciones. No requieren instalación, compilación ni bibliotecas externas. Puedes revisarlas abriendo `index.html` en el navegador. Sube también `en.html` y `documentos` para que funcionen el selector y las descargas.

## Selector de idioma

- **Español** abre `index.html`.
- **English** abre `en.html`.
- Cada idioma utiliza su documento original, sin traducción automática.
- Con JavaScript, cambiar de idioma conserva la sección o subsección que se está leyendo. Desde la portada abre la portada del otro idioma.
- Sin JavaScript, los enlaces de idioma siguen funcionando y todo el contenido continúa accesible.
- Cambian los textos del reporte, la navegación, los controles, la descripción y el idioma del documento.
- La impresión incluye únicamente la versión abierta.

## Contenido y fuentes

Se conserva el contenido sustantivo de ambos documentos: detalles del evento, trayectoria personal, democracia, migración y diáspora, Haití, corrupción, clima, geopolítica, preguntas del público y transcripción con marcas de tiempo. Las cifras, declaraciones y valoraciones permanecen en el contexto de cada reporte. No se agregaron fotografías, logotipos ni datos externos.

La nota sobre el proceso de corrección de la transcripción se sustituyó por una indicación breve de idioma, de acuerdo con la preferencia del usuario por una presentación final sin comentarios de edición. No se eliminaron intervenciones. Los documentos originales en Word se conservan sin modificaciones.

Se diferencia la fecha del encuentro (28 de septiembre) de la fecha de publicación de los reportes (30 de septiembre). El enlace a la grabación es el suministrado en los documentos; no se realizó una nueva transcripción o comprobación contra el video.

## Actualizaciones

Corrige el español en `index.html` y el inglés en `en.html`. Si cambias contenido, revisa ambos idiomas: las páginas no se traducen ni sincronizan automáticamente. Mantén los mismos identificadores de sección en ambas páginas para conservar la navegación bilingüe.

Los estilos están en `<style>` y las funciones en `<script>`. Los archivos Word se sustituyen dentro de `documentos`, conservando sus nombres.

## Impresión y metadatos

Usa **Imprimir / PDF** o **Print / PDF**, selecciona A4 y guarda como PDF desde el navegador. Los párrafos se justifican en pantallas amplias y en papel, y se alinean a la izquierda en móvil.

Cada página incluye título, descripción, idioma, Open Graph y enlaces alternativos de idioma. Cuando conozcas la URL definitiva, puedes añadir `canonical` y `og:url` a cada versión y convertir las referencias `hreflang` a URL absolutas. No se ha supuesto una dirección pública.
