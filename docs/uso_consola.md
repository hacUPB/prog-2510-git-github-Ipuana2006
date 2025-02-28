# Uso de la Consola para Navegar y Gestionar Archivos y Directorios

Git Bash es una terminal que permite usar comandos de Unix en Windows, facilitando la gestión de archivos y directorios con herramientas similares a las de Linux y macOS.

## 1. Navegación por la Consola

Para moverte entre directorios en Git Bash, usa los siguientes comandos:

- **`pwd`** (*Print Working Directory*): Muestra la ruta del directorio actual.
- **`ls`** (*List*): Lista los archivos y carpetas dentro del directorio actual.
  - `ls -l` → Muestra detalles como permisos, propietario, tamaño y fecha de modificación.
  - `ls -a` → Muestra archivos ocultos.
- **`cd`** (*Change Directory*): Cambia de directorio.
  - `cd nombre_del_directorio` → Entra en un directorio específico.
  - `cd ..` → Retrocede un nivel (al directorio padre).
  - `cd /ruta/absoluta` → Accede a un directorio usando su ruta completa.
  - `cd ~` o simplemente `cd` → Vuelve al directorio personal del usuario.

> ⚠️ En Git Bash, las rutas de Windows se escriben en formato Unix. Por ejemplo, `C:\Users\Usuario` se convierte en `/c/Users/Usuario`.

## 2. Creación de Directorios y Archivos

Para organizar archivos y proyectos en Git Bash, usa:

- **`mkdir nombre_del_directorio`** → Crea un nuevo directorio.
- **`touch nombre_del_archivo`** → Crea un nuevo archivo vacío.
- **`echo "Texto" > archivo.txt`** → Crea un archivo con contenido.
- **`cat archivo.txt`** → Muestra el contenido de un archivo.
- **`nano archivo.txt`** o **`vim archivo.txt`** → Abre un archivo en un editor de texto dentro de la terminal.

## 3. Gestión de Archivos y Directorios

Para manipular archivos y carpetas, usa:

- **`mv nombre_origen nombre_destino`** → Mueve o renombra un archivo o directorio.
- **`cp archivo_origen archivo_destino`** → Copia un archivo.
- **`cp -r directorio_origen directorio_destino`** → Copia un directorio y su contenido.
- **`rm nombre_del_archivo`** → Elimina un archivo.
- **`rm -r nombre_del_directorio`** → Elimina un directorio y su contenido.

## 4. Uso de Git en Git Bash

Además de los comandos de navegación, Git Bash permite el uso de **Git** para gestionar repositorios:

- **`git init`** → Inicializa un nuevo repositorio Git en el directorio actual.
- **`git clone URL`** → Clona un repositorio desde una URL.
- **`git status`** → Muestra el estado de los archivos en el repositorio.
- **`git add archivo.txt`** → Añade un archivo al área de preparación (*staging*).
- **`git commit -m "Mensaje del commit"`** → Guarda los cambios con un mensaje descriptivo.
- **`git push origin main`** → Envía los cambios al repositorio remoto.

Estos comandos permiten trabajar con Git directamente desde Git Bash, facilitando la gestión de versiones en proyectos de desarrollo.

---

Con estos conocimientos, puedes usar Git Bash para navegar, crear y gestionar archivos, además de trabajar con repositorios Git de manera eficiente. 🚀
