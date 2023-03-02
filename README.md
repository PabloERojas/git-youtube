
# Comandos útiles de Git

1. git init: inicializa el repos.
2. git add .: toma todos los archivos desde el ultimo commit y los prepara para una fotografia (commit). "git add ." sube los archivos al Stage...
3. git reset: revierte todo lo que hace "git add ."
4. git commit -m "coment": confirmacion del archivo.
5. git chekout -- .: reconstruye archivos a como se encontraban en el ultimo commit incluso si los borro.
6. git log: listado de los commit.
7. git commit --amend: arregla/edita el ultimo commit.
8.  q: sale del --amend.
9.  i: inserta nuevo texto para poder editar el ultimo commit. Se corrobora con "git log"
10. salir del commit editado: Esc+:+w+q+! (:wq!)
11. git chekout -b rama-xxx: crea una nueva rama
12. git branch: muestra las distintas ramas.
13. git commit -am "coment": combina el add . + commit -m, cuando git ya esta haciendole seguimiento al archivo.
14. git push: despliega el archivo a GitHub. 

# Identificacion para Git en la consola:

1. git config user.name "PabloRojas"
2. git config user.email "p_e_rojas@hotmail.com"

