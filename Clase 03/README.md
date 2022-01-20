# Clase 03 - GIT

## Repaso de Branch

### Listo ramas
```sh
git branch
```

### Creo una rama
```sh
git branch <nombre-rama>
```

### Cambio entre ramas
```sh
git switch <nombre-rama>
```

## Git Merge
```sh
git merge <nombre-rama>
```

### Tipos de Merge

Se recomienda un commit por funcionalidad (o día)

Fast-Forward - Unión Automática
No hay ningún cambio que se solape con lo que está en la otra rama
En nuestro ejemplo quiero traerme los cambios a master. Switch a Master y luego git merge clase03

Recursivas - Uniones automáticas
No hay colisiones de cambio

Manual - Conflictos
Ocurre cuando hay modificaciones en las mismas líneas

### Abortar el Merge
```sh
git merge --abort
```


### Agrego cosas que quiero tener en consideración.

* Tener en cuenta subir una rama al remoto
* ver clone
* ver fork
