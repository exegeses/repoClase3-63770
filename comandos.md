# Listado de comandos

## crear un repositorio
    git init  
> Este comando crear un repositorio en el directorio donde estamos situados

## saber estado de cambios
    git status  
> Este comando te informa qué archivos estan sin seguimiento, 
> qué archivos estan con seguimiento (en el Staging area), 
> y si ya todos los archivos estan con puntos de restauración  
> En rojo: sin seguimiento  
> En verde: en el Staging area  

## crear punto de restauración
    git commit -m 'mensaje'

## crear punto de restauración don mensaje corto (título) y mensaje largo (descripción)
    git commit -m 'mensaje corto' -m 'mensaje largo, descripción'

## agregar a staging area y crear punto de restauración en un sólo comando
    git commit -a -m 'mensaje'

> otro modo de hacer un add y un commit juntos es:   
    git commit -am 'mensaje'  

## ver listado completo de commits con su autor <email>, descripcion, timestamp
    git log  

> se puede ver un logo corto, de un sóla línea con
    git log --oneline

## moverse hace cualquier commit
    git checkout nHASH  

## otro modo de volver al último commit
    git checkout master  
