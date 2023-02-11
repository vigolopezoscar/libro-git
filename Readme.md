# Tarea GIT y comandos utilizados.

### Ejercicios de creación y actualización de repositorios.

- git config --global user.name "Your-Full-Name". Configuramos nuestro usuario de Git.
- git config --global user.email "your-email-address". Configuramos nuestro correo electronico.
- git config --list. Comprobamos que nuestro correo y email con correctos.
- git init. Iniciamos nuestro repositorio local.
- git status. Podemos ver el estado actual del repositorio (cambios pendientes de añadir en caso de que haya).
- git add. Añadimos los cambios al area de intercambio temporal.
- git commit -m "Mensaje de referencia commit". Añade los cambios en el repositorio local con el mensaje introducido.
- git show. Nos muestra los cambios entre las ultimas dos versiones (commits).


### Ejercicios de manejo del historial de cambios.
- git log. Podemos ver las distintas versiones comiteadas.
- git diff HEAD~2..HEAD. Vemos la diferencias entre la ultima version y dos versiones anteriores.
- git annotate. Mostramos quien ha hecho los cambios sobre un fichero especificado.


### Ejercicios de deshacer cambios.
- git checkout -- nombre.txt. Deshacemos los cambios realizados en un fichero para volver a su anterior versión.
- git reset nombre.txt. Quitamos los cambios de la zona de intercambio temporal, pero los mantendremos en el directorio local.
- git clean -f. Desacemos los cambios realizados para volver a la versión del repositorio.
- git reset --hard HEAR~1. Volvemos al ultimo commit y los cambios anteriores del directorio volverán a la version anterior.


### Ejercicios de gestión de ramas.
- git branch. Creamos una nueva rama
- git branch -av. Mostramos las ramas del repositorio.
- git log --graph --all --oneline. Mostramos la historia del repositorio incluyendo todas las ramas.
- git checkout nombre. Cambiamos a otra rama.
- git merge nombre. Fusionamos la rama con la rama Master.


### Ejercicios de repositorios remotos.
- git remote add github url. Añadimos el repositorio local a Git.
- git remote -v. Mostramos los repositorios remotos configuramos.
- git push github master. Añadimos los cambios del repositorio local al repositorio remoto de Git.
- git clone url. Con este comando podemos descargar el repositorio remoto a local en nuestro ordenador.
