<h1> Curso oracle </h1>

<h2>Curso Git </h2>
dentro de git >>
  - cd = para posicionarse
  - ls = para ver carpetas
  - git clone = para sincronizar (?)
  - clear = limpiar pantasha
  - git log = historial de Commit changes
  - git pull = ver si está todo actualizado
  - git add .
  - $ git commit -m "para agregar commit al archivo recien subido "
<h2> Resumen</h2>
<p>Localizo archivo con cd. Luego de hacer cambios.
  <br>1. "git status" para ver si hay archivos modificados
  <br>2. "git add ." para agregar archivos
  <br>3. "git commit -m "mensaje relevante" para commit
  <br>4. "git push" para actualizar y subir todo.
  <br> <h3> para volver atras en un archivo </h3>
  <br> git log--online muestra los cambios. 
  <br> se copia (ctrl + ins) numero de commit y usa codigo
  <br> git restore --source 27982e5 index.html
</p>

<p>
  <h3> Ejemplo clase </h3>
  

Una persona que actúa como desarrolladora front-end concluyó importantes implementaciones en el desarrollo del proyecto en el cual está trabajando y necesita verificar los cambios realizados, agregarlos en su repositorio local, guardarlos y después enviar al repositorio remoto utilizando Git. Según ese contexto, ¿qué comandos de Git puede usar para ejecutar estas acciones?
Opinión del instructor

1 - Para verificar los cambios realizados:

    Utiliza el comando git status, sirve para listar todos los archivos que han sido modificados.

2 - Para agregar los cambios al repositorio local:

    Para agregar los cambios realizados de una sola vez, es necesario usar git add . (git add y un punto) y, para agregar los cambios en algún archivo específico, usamos a git add nombre-del-archivo-modificado.

3 - Para guardar los cambios:

    Utiliza el comando git commit, que sirve para capturar y guardar el estado actual del repositorio.

4 - Para enviar las modificaciones al repositorio remoto:

    Utiliza el comando git push, que sirve para enviar las modificaciones guardadas en el directorio local para el repositorio remoto.


</p>

<h3>Git merge y demases</h3>
<br>git switch main
<br>git merge desarrollo
<h1>Resumen clase </h1>
¡Hola! En esta clase, repasamos los comandos esenciales de Git y GitHub que aprendiste durante el curso.
Configuración: git config --global user.name y user.email para registrar tu información y git config --list para ver la configuración.
Repositorios: git clone para copiar un repositorio existente y git init para crear uno nuevo.
Verificación: git status para ver el estado del proyecto, git log para el historial de commits, git diff para los cambios en archivos y git branch para las ramas.
Agregar: git add . para agregar todos los archivos o git add <nombre_archivo> para uno específico.
Commit: git commit -m "mensaje" para guardar los cambios con un mensaje.
Enviar y actualizar: git push para enviar los cambios al repositorio remoto y git pull para descargar las actualizaciones.
Ramas: git checkout -b <nombre_rama> para crear una nueva rama, git merge para fusionar ramas, git switch para cambiar entre ramas y git restore --source <hash> para volver a un commit anterior.

