# Clase 02

## Muestra los commit
```sh
git log
```

**Nota:** Para salir es con la letra **q**

## Muestra la cantidad de commit elegidos
```sh
git log --oneline
```

### Git Log por Fecha
```sh
git log --since="2021-12-20"
git log --after="2021-12-20"
git log --before="2021-12-20"
git log --after="2021-12-20" --after="2021-12-27"
```

### Cantidad de commit que va a mostrar el Git Log
```sh
git log -1
```

### A cada commit se le pone una etiqueta
```sh
git log --oneline --decorate --all --graph
```

## Pasar lo que tengo a Git
```sh
git push
```

### GIT IGNORE
Sirve para ignorar archivos que no quiero seguir.

Creo el archivo **.gitignore** en el directorio raìz y dentro coloco el nombre del archivo o la carpeta que quiero seguir.

### GIT KEEP
Me permite seguir una carpeta vacía

Creo un archivo llamado **.gitkeep** que lo que hace es tener en cuenta la carpeta vacío

### IMPORTANTE: Forma corta de hacer un git add y un git commit.
**NOTA:** Tengo que tener todos los archivos seguidos (al menos un add). Si tengo algunos untracked esos archivos no se van a comitear

```sh
git commit -am "Mensaje"
```

### REMOTE
```sh
git remote
```

#### Lista de alias de remotos y url
```sh
git remote -v
```

#### Agrego alias al remoto
```sh
git remote add <nombre-alias> <url-repo>
```

#### Renombra el alias de la URL del remoto
```sh
git remote rename <nombre-alias> <url-repo>
```

#### Borrar el remoto
```sh
git remote rm <alias-del-remoto>
```

#### Forma corta de ver los los cambios en el WD (working directory)
```sh
git status --short
```

## RAMAS (BRANCHES)

#### Listo las ramas
```sh
git branch
```

#### Creo rama
```sh
git branch <nombre-rama>
```

#### Cambio a otra ramas
```sh
git switch <nombre-rama>
```

#### Crear y mover a esa rama
```sh
git checkout -b <nombre-rama>
```
