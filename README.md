git init                            ||    Inicializar un proyecto git 
git status                          ||    Visualizar el estado de tus archivos          
git status -s                       ||    Visualizar el estado de tus archivos con detalles
git add -A                          ||    Agregar todos los archivos
git add .                           ||    Agregar todos los archivos
git rm -f                           ||    Forzar a eliminar un archivo
git rm --cached                     ||    Eliminar un archivo preparado(fase temporal) pero conservar en tu directorio de trabajo
git commit -m                       ||    Realizar un commit o captura de tus archivos en ese momento con un mensaje
git clone  URL                      ||    Clonar un archivo git del repositorio de github
git mv OriginalName ChangesName     ||    Renombrar un archivo o carpeta
git log                             ||    Permite visualizar un historico de confirmaciones(commits)
git log -p                          ||    Permite visualizar un historico mostrando las diferencias introducidas en cada commit 
git log -2                          ||    Permite visualizar el historico las dos ultimas confirmaciones 
git log --stat                      ||    Permite ver eliminaciones,modificaciones y adiciones en cada commit 
git log --pretty=oneline            ||    Imprime cada confirmación en una única línea, resulta útil si estás analizando gran cantidad de confirmaciones
git commit --amend                  ||    Si quieres editar el ultimo commit porque olvidaste guardar un cambio, pues add el archivo modificado y luego ejecutas este comando 
git reset --hard NumeIdenti         ||    Permite volver todo el proyecto o lo cambios hasta el commit que nosotros deseemos con solo poner su id identificador 
git remote                          ||    Para ver los remotos que tienes configurados,  Mostrará los nombres de cada uno de los remotos que tienes especificados
git remote set-url origin new.git.url  || Este comando me permite establecer una nueva URL de un repositorio git remoto                             