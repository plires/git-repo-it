# Clase 03 - GIT

## Repaso de Branch

### Listo ramas

```sh
git branch
```

### Creo una rama

```sh
git branch <nombreRama>
```

### Cambio entre ramas

```sh
git switch <nombreRama>
```

## Git Merge

### Tipos de Merge

Fast-Fodward (No hay ningun cambio que se solape con lo que esta en la otra rama)

Fast-Fodward - Unión automáticas (No hay ningun cambio que se solape con lo que esta en la otra rama)

Recursiva -  Uniones automáticas (No hay colisiones de cambios)

Manual - Conflictos (ocure cuando hay modificaciones en las mismas líneas)

### Abortar Merge

```sh
git merge --abort
```
### TAREAS: Agrego cosas que quiero tener en consideración.

* Tener en cuenta subir una rama al remoto
* Ver Clone
* Ver Fork

## ALIAS

### ¿Cómo creo un alias?

```sh
git config alias.lg "log --oneline --decorate --all --graph"
git config alias.l "log --oneline"
git config alias.s "status --short"
```

### Para editar el archivo de configuración de GIT

```sh
git config -e
```

### Para eliminar un alias

```sh
git config --unset alias.s
```

# Git Clone
Me permite clonar cualquier repositorio que exista en GitHub, GitLab, etc

## Lo clona en la carpeta con el nombre react

```shh
git clone https://github.com/facebook/react.git
```

## Clona en una carpeta en especifico

```shh
git clone https://github.com/facebook/react.git <nombreCarpeta>
```
# Fork
Me permite crear un repo en mi cuenta de cualquier proyecto de Github

1. Vamos al repo que queremos hacer el fork. Presionamos el botón.
2. Se crear el repo en mi cuenta.
3. Puedo clonar ese repo y empezar a trabajar.


