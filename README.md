# Clase 05

## Para crear un repositorio en de GIT

´´´sh
git init
´´´

## Ver en que estado estan los archivos y en que área

´´´
git status
´´´

## Áreas del repositorio de GIT

* Workin Directory(WD)
* Staging Area(SA)
* Local Rep (LR)

## Estados de los archivos

* Untracked: Archivos que estan en el WD pero GIT no les esta dando seguimiento
* Unmodify: Archivos que GIT ya esta siguiendo y con respecto al WD, no fueron modificados
* Staged: archivos que están en el área temporal/intermedia

# Agrego al área de confirmación el archivo o los archivos
´´´sh
git add <nombre del archivo>
git add <nombre del archivo> <nombre del archivo><nombre del archivo>
git add . # agrega todos los archivos 