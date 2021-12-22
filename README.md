# Otros sistemas de versionado
Bitbucket
Gitlab


# Clase 01 - Git

## Archivos Markdown (laravel)

https://www.markdownguide.org/cheat-sheet/

**Nota:** ` = backtick => ALT + 96

```sh
git --version
```

```js
console.log('Hola');
```
## Comandos de Consola

### Limpio la consola
```sh
clear
```

### Listar archivos en consola
```sh
ls -la
```

### Crear directorio
```sh
cd <directorio>
```

### Retrocedo un directorio
```sh
cd ..
```

### Borrar de forma forzada la carpeta
```sh
rm -rf <carpeta/archivo>
```

### Varios comandos al mismo tiempo
```sh
git init && npm init -y && touch index.html && mkdir css && mkdir js
```

## Inicialización del proyecto
```sh
git init
```

### Configuracion Inicial Nombre/Mail/Listo configuraciones
```sh
λ git config user.name "FedeR"
λ git config user.email "fede.riccio@hotmail.com"
git config --get-regexp user
```

## Status: Compara el WD con el commit
```sh
git status
```

## Paso del Working Directory (WD) al Index (Staged)
```sh
git add <archivo>
```

## Paso del WD al Index
```sh
git add .
```

## Para pasar del INDEX al REPOSITORIO LOCAL
```sh
git commit -m "Agrego el README.md" <archivo>
```

### Log (info del Commit - identificación univoca)
```sh
git log
```

### Log (info del Commit - resumido)
```sh
git log --oneline
```
