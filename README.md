## Quitar archivos de seguimiento
```
$ git reset HEAD archivo
```

## Revertir cambios en archivos

```
$ git reset --hard HEAD 
```
Revierte los cambios que se han hecho a los archivos en seguimiento,
regresa un archivo a su estado ultimo salvado antes de modificar 
y regresa archivos que se han elimiando.

## Eliminar/Descartar archivos que no estan en seguimiento

```
$ git clean -d -f
```

Revisar archivos que se van a eliminar
```
$ git clean -d -n
```

## Descargar cambios del Servidor
```
$ git fetch origin master
```

## Ver la diferencia entre 2 ramas
```
$ git diff master origin/master
```

## Mezclar dos ramas
Siempre debe estar el puntero en la rama a donde se 
van a agregar los cambios
```
$ git merge origin/master
```

## Descargar cambios del servidor y mezclar
```
$ git pull origin master
```
