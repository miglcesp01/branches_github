# Ramas de Github
Fundamentos del uso de ramas en Github

### Crear nueva rama
```
git branch <name>
```

### Eliminar rama en local
```
git branch -d <branch_name>
```

### Eliminar rama en remoto
```
git push origin --delete <branch_name>
```

### Crear rama y automaticamente cambiar la rama
```
git branch -b <name>
```

### Ver la rama en la que trabajamos
```
git branch
```

### Cambiar de rama
```
git checkout <branch_name>
```

### Unir el trabajo de la rama con el main
```
git merge <branch_name>
```

## Restaurar rama eliminada

### 1. Conocer el nombre de la rama y el SHA1 del commit
```
git reflog
```
![Imagen de la salida de git reflog]
(https://github.com/miglcesp01/branches_github/blob/main/img/InkedRecuperar%20rama_LI.jpg) 

La idea es buscar el último merge que hiciste de una rama a la rama que deseas recuperar.
Luego necesitas el nombre de la rama a recuperar y el código SHA1 del merge que ya buscamos.

### 2. Recuperación de la rama
```
git branch <branch_name> <SHA1>
```

## Otros comandos útiles

### Obtener ramas fusionadas
```
git branch --merged
```

### Obtener ramas no fusionadas
```
git branch --no-merged
```

### Conocer la diferencia entre dos ramas
```
git diff <branch_1> <branch_2>
```

# Referencias 
https://git-scm.com/doc




  
  
 
