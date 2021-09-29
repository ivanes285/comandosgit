# Comandos Básicos de GIT  

- Inicializar un proyecto git 
```
git init  
```

- Visualizar el estado de tus archivos  
```
git status     
```
- Visualizar el estado de tus archivos con detalles
```
git status -s       
```
- Agregar todos los archivos
```
git add -A 
```
- Agregar todos los archivos
```
git add .   
```
-  Forzar a eliminar un archivo
```
git rm -f 
```
- Eliminar un archivo preparado(fase temporal) pero conservar en tu directorio de trabajo
```
git rm --cached  
```
- Realizar un commit o captura de tus archivos en ese momento con un mensaje
```
git commit -m
```
- Clonar un archivo git del repositorio de github
```
git clone  URL    
```
- Renombrar un archivo o carpeta
```
git mv OriginalName ChangesName 
```
- Permite visualizar un historico de confirmaciones(commits)
```
git log      
```
- Permite visualizar un historico mostrando las diferencias introducidas en cada commit 
```
git log -p       
```
- Permite visualizar el historico las dos ultimas confirmaciones
```
git log -2     
```
- Permite ver eliminaciones,modificaciones y adiciones en cada commit
```
git log --stat 
```
- Imprime cada confirmación en una única línea, resulta útil si estás analizando gran cantidad de confirmaciones
```
git log --pretty=oneline  
```
- Otra manera mas ordenada y amistosa de mostrar los logs
```
git log --oneline --decorate --all --graph
```

- Si quieres editar el ultimo commit porque olvidaste guardar un cambio, pues add el archivo modificado y luego ejecutas este comando
```
git commit --amend  
```
-  Permite volver todo el proyecto o lo cambios hasta el commit que nosotros deseemos con solo poner su id identificador 
```
git reset --hard NumeIdenti 
```
- Para ver los remotos que tienes configurados,  Mostrará los nombres de cada uno de los remotos que tienes especificados
```
git remote            
```
- Este comando me permite establecer una nueva URL de un repositorio git remoto 
```
git remote set-url origin new.git.url
```
- Union de una rama 'namerama' con la rama principal (main)
```
git checkout main 
git merge 'namerama'
```
- Eliminar una rama 
```
git branch -d 'namerama'
```
-- Crear una rama y cambiarnos en el mismo comando 
```
git checkout -b 'newnamerama'
```
-- Guardar y hacer un commit en el mismo comando 
```
git commit -am "comentario"
```
