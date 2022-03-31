# DemoGithubActions

El objetivo de este repositorio es realizar una demostracion de Github Actions con el fin de entender cual es su idea principal de los workflows.
Para la creacion de un workflow debemos tener un proyecto alojado en github o ser colaborador del proyecto.

## Repositorio
Primero necesitamos un proyecto no importa el lenguaje de programacion
* Crear el directorio .github/workflows/
![Image text](./img/img1.png)
(La carpeta login es el proyecto en PHP)

* dentro del directorio .github/workflows/ crearemos un archivo .yml (En este caso se llamo demo.yml)
![Image text](./img/img2.png)


* dentro de ese archivo ponemos nuestro codigo para el workflow, yo pondre este codigo dentro del archivo creado
![Image text](./img/img3.png)

* Hacemos un commit a ese archivo creado y despues de ese paso vamos al principio de nuestro repositorio
![Image text](./img/img4.png)

## Mirar si se ejecuta la accion
Para mirar si se ejecuta la accion del workflow realizaremos los siguientes pasos

* en el inicio del proyecto vamos al apartado Actions
![Image text](./img/img5.png)

* Nos aparecera lo siguiente
![Image text](./img/img6.png)

Daremos clic para ver los detalles
![Image text](./img/img7.png)

* estaremos en este menu, daremos clic Explore-Github-Actions
![Image text](./img/img8.png)

* en esta parte nos apareceran los detalles, si nos aparecen con un :white_check_mark: o :ballot_box_with_check: se ejecuto correctamente la Actions 
![Image text](./img/img8.png)


