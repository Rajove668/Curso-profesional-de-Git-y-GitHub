# *Git Comandos*
- git init [Nombre de la carpeta] !! git init
  - ; Crea un repositorio dentro de la carpeta dada.
  - ; Crea un repositorio en la ubicacion donde se este.
- git status
  - ; muestra los archivos modificados que no se han subido a staging area.
- git add (-A|.|-A -n|<file>)
  - ; pasa todos los archivos modificados a staging area . == -a.
  - ; muestra los archivos que van hacer agregados a staging area -n.
- git rm --cached <file>
  - ; Saca algun archivo de staging area.
- git commit -m "mensaje"
  - ; Pasa los archivos en staging area a el repositorio.
  - ; "mensaje" es el titulo del commit.
-git commit --amend
  - ; Modificar el ultimo commit realizado, nombre, archivos
- git clone
- git checkout [branch]



- git pull origin master ; actualizar el branch con el del repositorio
  - fetch
  - merge
- git push ; sube al branch
- git reset --HARD pasa a local todo
- git log
- git log --graph
- git log --oneline --decorate --graph
- git remote prune origin
- git branch [branch]
- git push --set-upstream origin [branch]
- git branch -d [branch] ;-d elimina , -D fuerza, -dr elimina en local y github
