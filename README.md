
# Comandos útiles de Git

1. git init: inicializa el repos.
2. git add .: toma todos los archivos desde el ultimo commit y los prepara para una fotografia (commit). "git add ." sube los archivos al Stage...
3. git reset: revierte todo lo que hace "git add ."
4. git commit -m "coment": (git commit: es el comando) confirmacion del archivo + un mensaje.
5. git chekout -- .: reconstruye archivos a como se encontraban en el ultimo commit incluso si los borro.
6. git log: muestra el listado de los commit.
7. git commit --amend: arregla/edita el ultimo commit.
8. git diff + "nombre del archivo": muestra la ultima modificacion que se hizo en el archivo antes del commit.
9.   q: sale del --amend.
10.  i: inserta nuevo texto para poder editar el ultimo commit. Se corrobora con "git log"
11. salir del commit editado: Esc+:+w+q+! (:wq!)
12. git chekout -b rama-xxx: crea una nueva rama
13. git branch: muestra las distintas ramas.
14. git commit -am "coment": combina el add . + commit -m, cuando git ya esta haciendole seguimiento al archivo.
15. git push: despliega el archivo a GitHub.

# Identificacion para Git en la consola:

1. git config user.name "PabloRojas".
2. git config user.email "p_e_rojas@hotmail.com"
3. git status: indica a git que identifique el estado del directorio en tiempo real.

  BIBLIOGRAFIA: Comandos de Git que debes de saber de Fernando Herrera (Youtube)