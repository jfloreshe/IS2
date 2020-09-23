# IS
## Primer Paso
Creamos el repositorio en este caso se esta creando el repositorio manualmente en github
## Segundo Paso
Clonamos el repositorio usando el siguiente comando
```
git clone https://github.com/jfloreshe/IS2.git
```
Realizando estos pasos no tenemos que configurar la localizacion del repositorio remoto
## Tercer Paso
Para subir lo que hemos realizado hasta ahora tenemos que agregar a git todos los archivos que hemos modificado usando el siguiente comando
```
git add <filename>
```
si queremos agregar todos los files de golpe podemos simplemente colocar 
```.```
Una vez que esten los files en nuestro git podemos darle commit usando el siguiente comando
```
git commit -m "Primer commit en github"
```
No olvidar el -m junto al mensaje para poder tener una referencia rapida de lo que estamos haciendo.
Como ya tenemos configurado el repositorio remoto ahora tenemos que pushear el proyecto con el siguiente comando
```
git push origin master
```
## Cuarto Paso
Podemos revisar el estado de git con el siguiente comando
```
git status
```
Con este comando podemos ver si hay files que no han sido incluidos, donde se han hecho modificaciones y si hay algun conflicto

## Quinto Paso
Podemos crear una nueva rama y trabajar desde esta para no modificar la rama principal.
Primero creamos la rama con el siguiente comando
```
git branch <nombre de la rama>
```
Para cambiarnos de rama usamos el siguiente comando
```
git checkout <nombre de la rama>
```
Ahora podemos trabajar libremente sin afectar a las otras ramas
Cuando hagamos el push no olvidar de colocar el nombre de la rama

## Sexto Paso
Podemos ver la diferencia entre 2 ramas usando el siguiente comando
```
git diff <nombre de la rama>..<nombre de la rama>
```
Podemos ver los ultimos commits hechos por si queremos regresar a una version anterior usando el siguiente comando
```
git log
```
## Septimo Paso
Para juntar una rama con la principal primero debemos dirigirnos a la rama principal haciendo un checkout y colocamos el siguiente comando
```
git merge <nombre de la rama con la que haremos el merge>
```

