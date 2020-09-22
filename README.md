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

![Captura 1](https://user-images.githubusercontent.com/71384524/93804979-53fa1f80-fc47-11ea-9be3-7da8108ea636.PNG)

Ahora crearemos un archivo txt y una carpeta, para realizar lo primero
tendremos que utilizar el comando copy con lo haremos de la siguiente
manera: **copy con privado.txt**. Ahora nos saldra para poder escribir 
en el documento, aqui lo que haremos sera darle al enter una vez y luego
ctrl+c, una vez hecho esto ya habremos creado el archivo **privado.txt**.
Para crear el archivo necesitaremos el comando **mkdir**, para crear la 
carpeta lo unico que haremos sera **mkdir privada**.

![Captura](https://user-images.githubusercontent.com/71384524/93805074-7d1ab000-fc47-11ea-8202-c356de31ad95.PNG)

Para poder ignorar una carpeta y un archivo lo vamos a hacer de la siguiente
manera, lo primero que debemos hacer es crear un documento **.gitignore**. 
Dentro de este documento introduciremos los archivos o carpetas que nosotros
queremos que sean ignorados por git.

Para comprobar que hemos ignorado la carpeta como el archivo, antes de crear 
el **.gitignore** haremos un **git status** y despues de crearlo lo haremos
y veremos que se a ignorado correctamente. Para comprobar que es lo que se ha 
ignorado podemos poner el siguiente comando **git status --ignored**.

![Captura2](https://user-images.githubusercontent.com/71384524/93805250-c0751e80-fc47-11ea-8bff-b21a0465420b.PNG)

![Captura3](https://user-images.githubusercontent.com/71384524/93805266-c8cd5980-fc47-11ea-98d2-8ee427004f80.PNG)

![Captura4](https://user-images.githubusercontent.com/71384524/93805284-cff46780-fc47-11ea-8570-78f6e829a2f8.PNG)


A continuacion crearemos otro archivo .txt de la misma manera que anteriormente
con el comando **copy con 1.txt**.Ahora crearemos un tag esto lo haremos con el
siguiente comando **git tag -a v0.1 -m "Version 0.1 -Realizando cambios**.

Cuando hayamos hecho esto subiremos todo lo que hayamos hecho a nuestro repositorio
en GitHub con lo comando escritos anteriormente. Tambien tendremos que subir el tag
creado en pasos atras, esto lo haremos con el siguiente comando, antes de nada 
tendremos que hacer **git add --all** y el **git commit -m "v0.1 realizando cambios"**, 
una vez hecho esto tendremos que usar **git push --tags**.

Esto es lo que sale una vez subido todo al repositorio.
![Captura6](https://user-images.githubusercontent.com/71384524/93805486-1cd83e00-fc48-11ea-863e-27cadcb560e7.PNG)

Aqui se puede ver como se ha subido el tag.
![Captura7](https://user-images.githubusercontent.com/71384524/93805631-4a24ec00-fc48-11ea-84b6-561feb942748.PNG)

Ahora pondremos una foto de perfil en GitHub, activaremos el doble factor de 
autentificacion y la clave publica de nuestro ordenador.

![Captura8](https://user-images.githubusercontent.com/71384524/93806074-e6e78980-fc48-11ea-8c5c-b2959dfabbae.PNG)

![Captura9](https://user-images.githubusercontent.com/71384524/93806088-eea72e00-fc48-11ea-8822-f84aaf9b1224.PNG)

![Captura10](https://user-images.githubusercontent.com/71384524/93806105-f666d280-fc48-11ea-9c05-d43af893ca15.PNG)

Ahora buscaremos el usuario de mis compañeros y lo seguiremos, seguiremos sus 
repositorios y les daremos una estrella.

Para crear una tabla se hara de la siguiente manera.
|NOMBRE|GITHUB|
|-|-|
|Rafael Dominguez|https://github.com/rafadominguez71|
|Alejandro Guerra|https://github.com/aguerra952|
|David Bueno|https://github.com/dvidgb|

Para terminar añadiremos como colaborador a asanzdiego.
![captura11](https://user-images.githubusercontent.com/71384524/93806432-6e34fd00-fc49-11ea-93a4-129b191abd9e.PNG)


#####Ejercicio avanzado
----------------------------------------------------------------------------

Crearemos una rama mediante el comando **git checkout v0.2**, haciendo esto 
pondremos a la carpeta bajo esta rama. Ahora crearemos un fichero .txt con 
el comando **copy con 2.txt**. Subiremos los cambios hechos al repositorio
esto se hara con los dos primeros comando iguales que las veces anteriores
mientras que el push sera de la siguiente manera:
**git push --set-upstream origin v0.2**

Para posicionarnos en la rama master se hara con ** git checkout master**. 
A continuacion realizaremos un merge de la rama v0.2 en la rama master, 
**git merge v0.2**. Ahora en la rama master dentro del fichero 1.txt haremos
una modificacion añadiendo un *Hola* y haremos commit. Nos iremos a la rama 
v0.2 y pondremos dentro del mismo fichero 1.txt un *Adios* y haremos commit.

Una vez realizado esto tendremos que volver a irnos a la rama master, y 
tendremos que hacer un merge, al hacer esto nos saldra como existe un 
conflicto. Ahora listaremos las ramas con merge y sin merge, esto se hara
de la siguiente manera:
-**git branch --merge**
-**get branch --no-merge**

Para arreglar el conflicto tendremos que hacer lo siguiente, primero haremos
un **git add .**, a continuacion haremos **git merge v0.2** y por ultimo un
**git commit -m "El conflicto esta arreglado"**.

A continuacion crearemos un tag v0.2 con el comando ** git tag v0.2** y 
borraremos la rama v0.2 con el comando **git branch -D v0.2**. Una vez hecho
esto subiremos las domificaciones hechas.

