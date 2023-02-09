# Iniciar proyecto con git 

    $ git init

# Verificar el estado del repositorio 

    $ git status

# Preparar archivos a guardar en el repositorio 

    $ git add <file>

    $ git add .

    $ git add -A

    $ git add *

# Guardar cambios en el repositorio 

    $ git commit -m "Mensaje Descriptivo de lo que se hizo"

# Deshacer cambios 

    $ git restore <file>

    $ git checkout <file>

    $ git reset -- hard HEAD~1


# Listar, Crear, Eliminar branch(ramas)

    $ git branch
    $ git branch <name>
    $ git branch -D <name>

# Activar una rama o crear y activar una rama (branch)

    $ git checkout <name>
    $ git checkout -b <name>


# Unir cambios de una rama(branch) a otra

    $ git merge prueba

# Verificar los cambios guardados 

    $ git log

# Administrar repositorios remotos (github, gitlab, bitbucket, etc)

Ver listado de Repositorios

    $ git remote