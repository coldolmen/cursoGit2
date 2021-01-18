# cursoGit2
Repetición del curso de fatz
Comandos de git:
- git init : inicializa el proceso
- git status : nos informa de en qué momento está
- git add : para añadir los archivos al área de preparación ( si escribo git add . añade todos los archivos)
- git commit: todos los archivos seleccionados son enviados al directorio git
- git commit -m 'mensaje'
- git config user.mail   y git config user.name : sólo para configurar el usuario (la primera vez)
- git push origin <master> : para enviar confirmaciones locales a la rama maestra del repositorio remoto , <master> indica la rama del repositorio a la que lo estoy enviando
- command git checkout -b <btanch-new.name>: crea ramas 
- git checkout  para navegar entre las diferentes ramas
- git remote -v : permite listar todos los repositorios
- git remote add origin <host or remote url> : para conectar el repositorio local a un servidor remoto
- git remote <url> borra la conexión a un remoto
- git branch : listar las diferentes ramas de un repositorio
- git branch -d <name> : borra una rama
- git pull fusiona todos los cambios que se han hecho 
- git diff : para ver lista de conflictos respecto a un archivo base ( de un archivo que no se ha enviado)  , también entre ramas
- git log : ver el historial y los detalles de cada versión
- git rm filename : borra archivos
