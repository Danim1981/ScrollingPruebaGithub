Desarrollo de la interfaz de usuario Android
Aplicando los conceptos y herramientas GitHub.
Se puede iniciar el repositorio en AndroidStudio.
 
Se elige la carpeta del proyecto
 
Una vez iniciado el repositorio se muestra la primera rama :main
 
En la terminal con <git status> , se muestra los archivos que aún no se han agregado en rojo.
 
Después del comando <git add .>  se agregan los archivos y al consultar con un <git status> se muestran en verde listos para el” commit.”
 
Se realiza el primer commit
 

Para preparar un nuevo repositorio en github, se hace click en el botón “New”  =>
 









En la pantalla de nuevo repositorio, se le agrega el nombre ,  una descripción, se define público ó privado,  y otro par de opciones .
 







Una vez Creado el Repositorio, aún está sin archivos,  y muestra las opciones para poder subir los archivos del proyecto realizado localmente en AndroidStudio  o el ide que sea, mostrando una url  que está asociada a la cuenta de github del usuario.
 

Con el comando : <git remote add origin  (mas la url del repositorio)> se prepara la subida de archivos y con <git push > se cargan en github.
 


Una vez realizado lo anterior ya se puede ver el directorio con carpetas y archivos cargados en el repositorio.
 
Con el comando <git branch feature1> se crea una nueva rama (feature1), con el comando <git checkout feature1> se cambia desde la rama main y se conecta a la rama feature1, Con <git branch> se muestran las ramas existentes y la que aparece destacada es a cuál se está enlazado en ése momento , en éste caso (feature1)
 

Se realizan cambios en el proyecto.
 
Los cambios realizados se agregan con <git add .> y luego con un commit se asignan a la rama en que está el proyecto.
 

Realizando un push, se suben los cambios al repositorio.
 


Una vez que existe más de una rama , en la misma página de github , indica que se puede realizar un pull request.
 
Al ejecutar el pull request compara los archivos de ambas ramas y pasa los cambios en éste caso de featured1 a la rama main, se puede agregar comentarios y datos sobre  el procedimiento.
 




Una vez confirmado el procedimiento y si no existe conflictos importantes , se ejecuta el merge, de haber conflictos hay que comparar los archivos y decidir cuál es el código correcto.
 









Una vez confirmado el merge, github muestra el procedimiento y da la opción de borrar la rama que ya se ha agregado a la rama main, e incluso revertir el procedimiento completo.
 

De ésta forma se puede ir agregando cambios a un proyecto de manera progresiva y pasándolos a la rama principal cuando cumplan con un nuevo requerimiento.
Éstos mismos procedimientos se pueden realizar también por comandos desde la terminal.
