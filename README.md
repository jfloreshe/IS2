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

