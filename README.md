# AppLibreria

## Integrantes

* Ariel Andrés Guemahyel Guzman Leiva
* Diana Quinteros Gallardo
* Francisco Cerda Venegas
* Mariafernanda Lagunas Ivani
* Nicolás Sanhueza Díaz
* Sebastian Muñoz Garrido

## Comandos de Github

### Configuración Básica

Configurar Nombre que salen en los commits
```ssh
	git config --global user.name "dasdo"
```
Configurar Email
```ssh	
	git config --global user.email dasdo1@gmail.com
```

### GIT CLONE

Clonamos el repositorio de github
```ssh
	git clone <url>
```

### GIT ADD

Añadimos todos los archivos para el commit
```ssh
	git add .
```
### GIT COMMIT

Guarda los cambios realizados
```ssh
	git commit -m "Texto que identifique por que se hizo el commit"
```
Agregar y Cargar en el HEAD los cambios realizados
```ssh
	git commit -a -m "Texto que identifique por que se hizo el commit"
```
De haber conflictos los muestra
```ssh
	git commit -a 
```
### GIT PUSH

Subimos al repositorio
```ssh
	git push <origien> <branch>
```
### GIT LOG

Muestra los logs de los commits
```ssh
	git log
```
Muestras los cambios en los commits
```ssh
	git log --oneline --stat
```
Muestra graficos de los commits
```ssh
	git log --oneline --graph
```
### GIT DIFF

Muestra los cambios realizados a un archivo
```ssh
	git diff
	git diff --staged
```