# Tarea 4
- Primera tarea: Colaborar 


1. Primero descargar el repositorio de otra persona. Para descargarlo habrá que clonar un repositorio.

`git clone https://github.com/nombre-usuario/nombre-repositorio.git`

![Captura de pantalla 1](https://user-images.githubusercontent.com/82807688/154710486-89c96c20-78a1-4242-a02b-05e57674c46d.png)

2. Ir al repositorio. Para ir al repositorio se usa el comando `cd`.

`cd nombre-repositorio`

3. Crear una nueva rama. 

`git branch my-branch`

4. Ahora se cambia a la nueva rama creada 

`git checkout my-branch`

![Captura de pantalla 2](https://user-images.githubusercontent.com/82807688/154712192-81ed9e46-5791-4232-9dd2-e6e95bccf84f.png)

5. Modificamos el archivo README.md con `vim`. Una vez dentro del editor insertamos la tecla `i` y despues al intro; a continuación podemos editar. Al acabar, `esc` y despues `:wq` para poder salir del editor de la consola.

`vim README.MD`![Captura de pantalla 3](https://user-images.githubusercontent.com/82807688/154713996-2dfd125b-d664-4361-b256-f0b655492baf.png)

6. Para guardar se hace un commit 
`git commit -m "nombre del comentario"`

7. Para lanzarlo 
`git push --set-upstream origin my-branch`

![Captura de pantalla 4](https://user-images.githubusercontent.com/82807688/154716039-6f714d85-0f5c-4da1-889b-74e595f7eb15.png)

- Tarea 2: Nuevo repositorio.

1. Crear nuevo repositorio `git init`.

`git init repositorio`

2. Ir al nuevo repositorio.

`cd nuevo-repositorio`

![Captura de pantalla 1](https://user-images.githubusercontent.com/82807688/154718208-489e7f42-1382-47ac-b7e0-ed134ce0d9c4.png)

3. Crear el primer archivo en el nuevo repositorio.

`touch README.md`

4. Añadir el archivo

`git add README.md`

5. Tomar una instantánea del área de preparación

`git commit -m "add README to initial commit"`

6. Ponemos la ruta del repositorio creado.

`$ git remote add origin https://github.com/usuario/nombre-repositorio.git`

![Captura de pantalla 3](https://user-images.githubusercontent.com/82807688/154722066-3ef348a4-98d9-4be4-84f1-0a03f21c7ffb.png)

7. Lanzar los cambios.

` $ git push --set-upstream origin my-branch`

- Tarea 3: Contribuir a una rama existente en GitHub.

1. Para empezar hay que ir al repositorio deseado

`cd repositorio`

2. Actualizar todas las ramas de seguimiento retorno y las actualmente ya registradas

`git pull`

![Captura de pantalla 1](https://user-images.githubusercontent.com/82807688/154723413-ad58a3fc-30f8-46cd-81a2-d41b1707e3f6.png)

3. Cambiar a la rama existente.

`git checkout feature-a`

4. añadir el nuevo archivo editado.

`git add file1.md`

![Captura de pantalla 2](https://user-images.githubusercontent.com/82807688/154724317-9404eaee-a822-47c1-b38e-6359463bfa78.png)

5. Guardar las modificaciones o creaciones.

`git commit -m "edit file1"`

![Captura de pantalla 3](https://user-images.githubusercontent.com/82807688/154724445-06ce4ab0-2708-4f37-bc26-367946c35bea.png)

7. Por último enviar cambios a Github.

`git push`

![Captura de pantalla 4](https://user-images.githubusercontent.com/82807688/154724511-756024d5-35b0-48b1-9835-33e9c5fecacb.png)
