git init
Con este comando de git lo que estamos haciendo es decirle a git que este pendiente de los cambios que se produzcan en los archivos de ese directorio.
git status
Este comando git imprimirá los archivos que van a ser guardados, el siguiente paso es ejecutar:
git add .
Con esto añadiremos todos los archivos que aparecían anteriormente para ser guardados. Si queremos añadir un archivo o carpeta en concreto lo podemos hacer mediante
git add NOMBREDELARCHIVO
Si queremos eliminar los archivos que acabamos de añadir para ser guardados lo podemos hacer con
git rm .
Con estos comandos hemos añadido o hemos quitado archivos pero aún no han sido guardados, para ello:
git commit -m "Nombre descriptivo del cambio que hemos realizado"
ara imprimir todos los commits que hemos realizado tenemos el comando de git:
git log
La cadena de números y letras que aparece al lado de la palabra “commit” es el identificador que podemos usar para revertir los cambios y volver atrás a ese punto. Para ello ejecutamos:
git reset --hard IDENTIFICADOR
Si quires ver los cambios que has realizado desde el último commit lo puedes hacer con:
git diff

