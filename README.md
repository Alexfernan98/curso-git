# Curso de git y github

Curso git master mind 

Comandos git:
			
	• git init 	Para inicializar git debemos correr el comando git init en nuestra terminal del proyecto.
	• git status	Nos dice el estado actual del repositorio. 
	• git add "nombre del archivo"	Pasara solo ese archivo al staging area
	• git add . 	Pasara todos los archivos disponibles al staging area
	• git commit -m "mensaje"	Para subir el archivo a nuestro repositorio local
	• git config --global user.email	Se utiliza el correo con el que esta vinculado github, si no usamos global la configuración será solo para el proyecto.
	• git log	Se utiliza para ver los commits realizados, muestra el autor y la fecha del commit.
	• git log --oneline 	Para ver el historial de commits en una sola linea
	• git checkout (5 primeros dígitos del id del commit)	Nos permite navegar entre distintas versiones utilizando los dígitos del id del commit que obtenemos con git log. pero nos mantendrá en el estado de detached head lo que puede generar problemas en los siguientes commits
	• git checkout main	Para volver a la rama main donde se realizo el ultimo commit y poder seguir realizando cambios.
	• git reset (5 primeros dígitos del id del commit)	Nos dejara como ultimo commit al que hayamos puesto su id. 
	• git reset --hard (5 primeros dígitos del id del commit)	Todos los cambios que se hagan encima del commit que hayamos usado su hash se perderán.
	• git restore (nombre del archivo)	si el archivo es eliminado pero esta trackeado con git podemos recuperarlo con este comando.
	• git remote add origin git@github.com:Alexfernan98/curso-git.git	git remote add origin establece el servidor remoto donde subiremos el proyecto que de momento esta almacenado solo de manera local
		A continuación buscamos en google crear una nueva clave SSH con "github create new ssh key "
	• git checkout -b (nombre de la rama) 	Se usa para crear una rama nueva y desplazarnos a la misma. 
	• git branch	para ver en que rama estamos y las existentes
	• git push -u origin (nombre de la rama)	Pushea la rama actual al repositorio de github
