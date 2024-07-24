# Clase 01 - Desarrollo Colaborativo GIT

## Configuraciones iniciales de la herramienta

### Agrego un usuario y un correo
Este usuario y el correo va a ser utilizafo para firmar caa una de las instantaneas  (fotos/commits). Es obligatorio la configuracion de este usuario y correo.


```sh
$ git config --global user.name "Marianela Chiarillo"
$ git config --global user.email marianelachiarillo@gmail.com

```
# Para controlar --> $ git config --get-regexp user
# Para quitar --> $ git config --global --unset user.mail "Marianela Chiarillo"

# Modificar el editor de texto que usa GIT
```sh
git config --global core.editor "nano"
```

# Quieren cambiar la rama por defect. Es master a main
```sh	
git config --global init.defaultBranch main
```

# Empezando a trabajar con GIT

```sh
git init
```

Nota: Este comando crea un repositorio de git en la carpeta actual. Osea se crea un directorio oculto llamado .git (donde dentro tengo los archivos del repositorio)

# Controlar el status de los archivos dentro del repositorio 

```sh
git status
```

# Agregar al area de Staging
Marca el archivoy los cambios para que formen en un futuro parte de la siguiente instantanea (foto/commit)

```sh
git add <nombre-archivo>
git add clase.01/README.md
```