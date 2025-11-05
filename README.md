# TravelGuide - Sitio de recomendaciones de viajes

Proyecto final: sitio web estático con páginas de Inicio, Sobre Nosotros y Contacto.

Repositorio remoto (proporcionado por el alumno):
https://github.com/Walterfl1/beach.js.git

Descripción corta:
Este proyecto ofrece recomendaciones de viajes (playas, templos, por país) con imágenes, navegación, y un formulario de contacto con validación.

Instrucciones para subir el proyecto desde Windows PowerShell (ejecutar en `c:\Users\flore\OneDrive\Escritorio\cosas papa`):

1. Inicializar git local y hacer el primer commit (si no lo hiciste aún):

```powershell
git init
git add .
git commit -m "Proyecto TravelGuide - sitio inicial"
```

2. Añadir el remoto y subir a GitHub (reemplaza si tu URL es diferente):

```powershell
git remote add origin https://github.com/Walterfl1/beach.js.git
git branch -M main
git push -u origin main
```

3. Activar GitHub Pages (desde la web de GitHub):
- Ve a: https://github.com/Walterfl1/beach.js/settings/pages
- En "Source", selecciona `main` y carpeta `/ (root)`; guarda.
- Copia la URL pública que GitHub te dé (empieza con https://). Pegala en este README.

4. Comprobar imágenes:
- Asegúrate que la carpeta `assets/images` y los archivos (por ejemplo `beach1.jpg`) están incluidos en el commit.
- Si las imágenes no cargan en la página pública, confirma las rutas relativas en `index.html` (deberían ser `assets/images/<nombre>`).

5. Actualizar README con la URL pública (edita este archivo y luego `git add`, `git commit`, `git push`).

Si quieres, puedo:
- Generar un `README.md` más detallado (ya creado),
- Sugerir un nombre distinto para el repo o estructura, o
- Preparar un archivo `.gitignore` si necesitas excluir archivos (por ejemplo `node_modules` o `.env`).

Siguiente paso sugerido: abre PowerShell en la carpeta del proyecto y ejecuta los comandos del paso 2 para vincular y empujar al repo remoto que proporcionaste.