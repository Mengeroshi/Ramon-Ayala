# Todos los Comandos de Git! 100% real no fake
 

 - ¿Donde estamos?
 no lose y tu? :v 
 - ls
 - cd +ubicacion = ir a un lugar
 - git  init = iniciar un repositorio
 - git add -A = Agrega todos los archivos
 - git add + nombre de archivo = Agregar archivo
 - git commit -m "mensaje" = realizar cambios en el proyecto
 - git status = muestra en que punto de la itarcion estas
 - git log = Cambios
 - git log --oneline --graph = ver con *
 - git superlog=$ git log --graph --abbrev-commit --decorate
   --date=relative --format=format:'%C(bold blue)%hC(reset) - %C(bold green)(%ar)%C(reset) %C(white)%s$C(reset) %C(dim white)-
   %an%C(reset)%C(bold yellow)%d%C(reset)' --all
 - git config --global alias. "comando sin git" = cambiar nombre a un
   comando
 - git restet --hard +SHA commit = Borrar desde el commit seleccionado 
   (para volver a poner la parte borrada insertar la clave del ultimo
   borrado ascendente)
 - git reset --mixed + SHA commit  (Guarda varios commits en 1) (no se
   mete con working directory y cambia staying area y repositorio porlo
   que se tiene que guardar manual, es decir, es para preparar varios
   archivos)
 - git reset --soft +SHA comiit (Hace cambios en el repository. Staging 
   = working. Ya estan los archivos preparados)
 - git checkout -b "nombre de la rama" = crear rama
 - git checkout master = cambiar a la rama principal
 - git merge + nombre de la rama =
   ->O + "nombre de la fusion" + ESC + :x
 - git  branch -d experimental= Borrar rama(una rama no se puede borrar
   hasta que haga una fusion
 - ls -la = encontrar .git
 - rm - rf .git = borrar todos los cambios de git
 - git commit -am "descripcion" --amend= rectificar el ultimo commit
 - git rebase master=hacer rebase  (despues pasarse a master y hacer un
   merge)
 - git commit -am "mensaje" = hacer commit sin hacer add
 - git log --decorate =mostrar en que punto esta el head
 - git --stat = muestra el numero de lineas que se agregaron
 - git log -p = me dice en verde y rojo cuales fueron los cambios en
   codigo
 - git shortlog= ver el trabajo hceho por los desarrolladores
 - git log --graph --oneline --decorate= crear la historia del proyeto
   en lineas
 - git log --pretty=format:"string"
 - git log --pretty=format:"%cn hizo un commit %h el dia %cd"
 - git log -2(o cualquier)= salen unicamnete el numero de commits
   seleccionados  en este caso, dos.
 - git log --before="today"= todo lol que se hizo hoy
 - git log --author="Xavier Bawerk"= ver los commits por autor
 - git log --grep="palabra clave" -i = buscar por palbra clave el nombre
   de los commits"
 - git log -- nombre del archivo= mostrar donde se creo el archivo
 - git log -s"mensaje"= por comtenido
 - git clone + direccion de git=  ssh-keygen -t rsa -b 4096 -C
   "dpllgr@hotmail.com"= (regresar a punto de usuario con "cd ..")
 - cat id_rsa.pub= mostrar llave publica
 - mkdir + nombre = crear una carpeta
 - git remote add origin https://github.com/xavierbawerk/ejercicio.git=
   conectarse con repositorio propio
 - git push origin master= subir el archivo a github
 - git fetch origin= descargar el repositorio en github en la rama
   oculta origin (despues hacer un git merge origin/master)
 - $ git remote -v= ver direccion del remoto
 - git remote add upstream
   git@github.com:cyberpixelpunk/impresionante.git= conectarse con el
   link original del fork
 - git fetch upstream= descarga los cambios del fork original (despues
   hacer git merge upstream/master)

