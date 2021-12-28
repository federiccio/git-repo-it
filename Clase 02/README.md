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