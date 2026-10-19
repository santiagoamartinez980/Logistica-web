LOGÍSTICA INTERNACIONAL — PAQUETE WEB ESTÁTICO

Este paquete adapta la interfaz a alojamiento estático: no necesita .NET, API, Docker, base de datos ni variables de entorno. Mantiene teoría, preguntas, glosario, casos, recursos, herramientas y almacenamiento local del navegador.

VERCEL (recomendado si ya tienes el repositorio conectado)
1. Descomprime este ZIP.
2. Sube/reemplaza en la raíz del repositorio los archivos y la carpeta Data de este paquete (index.html, app.js, styles.css, Data/, vercel.json). No dejes la app dentro de una subcarpeta.
3. En Vercel, abre el proyecto y ve a Settings > Build and Deployment.
4. Framework Preset: Other. Build Command: vacío/desactivado. Output Directory: . (raíz del proyecto). Install Command: vacío o predeterminado si Vercel no permite dejarlo vacío.
5. Redeploy y abre la URL de producción.

RENDER (Static Site)
1. Sube estos archivos a la raíz de un repositorio GitHub.
2. En Render, New + > Static Site y conecta el repositorio.
3. Branch: master (o la rama donde subiste los archivos). Root Directory: vacío. Build Command: vacío. Publish Directory: .
4. Create Static Site.

IMPORTANTE
- No despliegues solo el ZIP en Vercel: normalmente debes subir el contenido a GitHub y conectar el repositorio, o usar la CLI de Vercel.
- Este paquete es para alojamiento estático. Los datos y las notas/progreso viven en el navegador de cada usuario; no se sincronizan entre dispositivos.
- Se conservó la interfaz original y el arreglo de sintaxis de toolsPage().
