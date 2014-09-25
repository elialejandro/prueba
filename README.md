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