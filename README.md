Paso 1 Crear Repositorio en Github

Paso 2 Copiar La direccion HTTPS del repositorio y ejecutar el comando

git clone direccionhttpsdelrepo
git clone https://github.com/IgnaciodeJesus/tallerpweb1.git

cd = change directory

Recordar utilizar el comando git status para informarse sobre donde uno se encuentra en el proyecto y los cambios que han sido guardados o no
git status

Es una buena practica utilizar multiples ramas o branch en los repositorios ya que se trabaja de manera conjunta y permite garantizar la organizacion de los proyectos

# Se crea una rama con el comando git branch
git branch nombredelarama
git branch ignacio

# Por predeterminado la rama que se usa es main por ello para posicionarnos en la rama que hemos creado se usa el comando git checkout nombredelarama
git checkout nombredelarama
git checkout ignacio

# Se tienen que alistan los cambios para el guardado local con el commando git add (se utiliza el . para agregar todas las modificaciones se pueden utilizar otras extensiones como astericso u toras para agregar archivos con caracteristicas en especifico o se puede indicar que archivos incluir de manera especifica)
git add .

# Para hacer el guardado local se utiliza el comando git commit
git commit -m "descripciondeloscambiosrealizados"

# Para subir cambios de local a la rama que has creado
git push origin nombredelarama

# Para traer cambios de una rama en el repositorio de github a local
git pull origin nombredelarama
# tallerpweb1
