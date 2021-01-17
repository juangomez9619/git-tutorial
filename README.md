# Ejemplo tutorial git-github

## Comandos para el control de versiones de manera local:

+ **git version** permite saber si git ya está instalado
+ **git init** permite iniciar un repositorio (de la carpeta del proyecto) **SOLO SE EJECUTA UNA VEZ**
+ **git status -s** Muestra la lista de archivos y su estado:
U o ??: Archivo sin seguimiento (NO registrado)
+ **git add archivo** añade el archivo al _staging area_
+ **git add .** añade todos los archivos presentes en la carpeta
+ **git commit -m "comentario"** crea un commit de lo que esté en el _staring area_ ("Pantallazo del código") 
Se recomienda no añadir tildes ni caracteres propios del español en el comentario de un commit.
Pueden crearse tantos commit como se deseen.
+ **ggit log --oneline** Lista de los commit existentes, su comentario y su estado.
+ **git reset --mixed id_commit** Sitúa el código en ese commit(puede ser a una versión anterior o una más reciente).
+ **git reset --hard id_commit** Sitúa el código en ese commit eliminando cambios futuros.

## Comandos para subir un repositorio hacia GitHub:
+ **Crear el repositorio en blanco desde Github**
+ **git remote add origin https://github.com/juangomez9619/git-tutorial.git** Enlaza al repositorio local con el creado en github. (Se coloca una sola vez)
+ **git branch -M main** Situa en la rama maestra.
+ **git push** Sube los archivos del repositorio local al repositorio en github. 
