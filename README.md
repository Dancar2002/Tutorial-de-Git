# Tutorial-de-Git
Actividad 2 Ciencia de Datos

Daniel Carrillo

TUTORIAL DE GIT


PROCESO SEGUIDO
1. Se utilizó una cuenta existente.
2. Instalación: Se verificó con git --version y se configuró la
   identidad con git config --global user.name  y git config --global user.email .
3. Se creó en GitHub el repositorio con el nombre Tutorial-de-Git.
4. Se hizo la clonación git clone https://github.com/Dancar2002/Tutorial-de-Git.git
5. Se crearon 3 capítulos basados en Pro Git. Los documentos Word se exportaron a PDF.
6. Registro de cambios por capítulo, con el ciclo:
git add .
git commit -m “Agrega x capitulo”
git push origin main

7. Comandos utilizados

git --version: Verificar la instalación de Git
git config: Configurar nombre y correo
git clone: Copiar el repositorio a la computadora
git status: Ver el estado de los archivos
git add: Preparar los cambios
git commit -m: Confirmar los cambios con un mensaje
git push origin main: Enviar los cambios a GitHub
git rm --cached: Dejar de rastrear un archivo
git log --oneline --graph: Ver el historial de commits

8. Cambios realizados

- Se agregó el Primer capítulo (Word y PDF).
- Se agregó el Segundo capítulo 2 (Word y PDF).
- Se agregó el Tercer capítulo 3 (Word y PDF).
- Se eliminó el archivo .DS_Store (generado por macOS) y se agregó a .gitignore.
- Se documentó todo el proceso en este README.
