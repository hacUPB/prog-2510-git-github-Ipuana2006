# Cómo Crear un Repositorio Local con Git

Sigue estos pasos para inicializar y configurar un repositorio local con Git.

## 1. Inicializar un Repositorio Git
Abre la terminal y navega hasta el directorio donde deseas crear el repositorio:

```sh
cd /ruta/del/proyecto
```

Luego, inicializa el repositorio con:

```sh
git init
```

Esto creará una carpeta oculta `.git`, que contiene la configuración del repositorio.

## 2. Agregar Archivos al Repositorio
Si ya tienes archivos en el directorio, agrégales seguimiento con:

```sh
git add .
```

Esto añadirá todos los archivos al área de preparación (*staging area*).

## 3. Realizar el Primer Commit
Guarda los cambios en el historial del repositorio con:

```sh
git commit -m "Primer commit"
```

## 4. Verificar el Estado del Repositorio
Para comprobar qué archivos han sido modificados o añadidos, usa:

```sh
git status
```

## 5. Configurar un Repositorio Remoto (Opcional)
Si deseas conectar tu repositorio local con GitHub, GitLab u otro servicio, usa:

```sh
git remote add origin https://github.com/tu-usuario/nombre-repositorio.git
```

Luego, sube los cambios con:

```sh
git push -u origin main
```

Si tu rama principal se llama `master`, cambia `main` por `master`.

---

¡Listo! Ahora tienes un repositorio Git local funcionando. 🚀
