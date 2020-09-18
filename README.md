# campusciff


Lo primero que hacemos es crear el repositorio y una vez creado nos
dirigimos a una cmd y alli utilizando el comando **git clone (url)**.

Una vez realizado esto, añadimos los comandos anteriores los cuales
son los mencionados anteriormente, y realizamos un commit, para ello
previamente deberemos de usar el comando **git add --all** para que
nos coja todo los cambios hechos hasta ahora, ahora es turno de poner
el comando commit. Dentro de este comando se tendra que poner un 
comentario este se hara con -m y acontinuacion se pondra el comentario
que en este caso sera "commit incial", el resultado del comando sera
el siguiente:
** git commit -m "commit inicial"**

Una vez hecho esto subiremos los resultados a **GitHub** mediante el
comando **git push**.

Ahora crearemos un archivo txt y una carpeta, para realizar lo primero
tendremos que utilizar el comando copy con lo haremos de la siguiente
manera: **copy con privado.txt**. Ahora nos saldra para poder escribir 
en el documento, aqui lo que haremos sera darle al enter una vez y luego
ctrl+c, una vez hecho esto ya habremos creado el archivo **privado.txt**.
Para crear el archivo necesitaremos el comando **mkdir**, para crear la 
carpeta lo unico que haremos sera **mkdir privada**.

Para poder ignorar una carpeta y un archivo lo vamos a hacer de la siguiente
manera, lo primero que debemos hacer es crear un documento **.gitignore**. 
Dentro de este documento introduciremos los archivos o carpetas que nosotros
queremos que sean ignorados por git.

Para comprobar que hemos ignorado la carpeta como el archivo, antes de crear 
el **.gitignore** haremos un **git status** y despues de crearlo lo haremos
y veremos que se a ignorado correctamente. Para comprobar que es lo que se ha 
ignorado podemos poner el siguiente comando **git status --ignored**.

A continuacion crearemos otro archivo .txt de la misma manera que anteriormente
con el comando **copy con 1.txt**.Ahora crearemos un tag esto lo haremos con el
siguiente comando **git tag -a v0.1 -m "Version 0.1 -Realizando cambios**.

Cuando hayamos hecho esto subiremos todo lo que hayamos hecho a nuestro repositorio
en GitHub con lo comando escritos anteriormente. Tambien tendremos que subir el tag
creado en pasos atras, esto lo haremos con el siguiente comando, antes de nada 
tendremos que hacer **git add --all** y el **git commit -m "v0.1 realizando cambios"**, 
una vez hecho esto tendremos que usar **git push --tags**.


|NOMBRE|GITHUB|
|---||---|
|Rafael Dominguez|https://github.com/rafadominguez71|
|Alejandro Guerra|https://github.com/aguerra952|
|David Bueno|https://github.com/dvidgb|