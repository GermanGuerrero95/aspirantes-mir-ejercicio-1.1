<!--Session2 Git-->
<!--Git y Github-->

<!--1.Abrir la consola e imprimir la ubicación actual-->

pwd

<!-- 2.Crear una carpeta llamada ejercicios en el escritorio desde la consola, si no estas en la ruta del escritorio, muevete a ella. -->

Primero cambio mi posición al escritorio
cd desktop
Segundo crear la carpeta
mkdir ejercicios

<!-- 3.Cambiar la ubicación a la nueva carpeta que crearon. -->

cd ejercicios

<!-- 4.Abrir la carpeta con VSCode. -->

Desde powershell code .

<!-- 5.En VSCode crear una carpeta ejercicio1. -->

mkdir ejercicio1

<!-- 6.Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1. -->

touch README.md

<!-- 7.Configurar nombre e email globalmente en git. -->

Ya había hecho este paso previamente. Sin embargo adjunto los comandos=>

git config --global user.name="German G" // Para el correo git config --global user.email="german95guerrero@hotmail.com"

<!--8.Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios. -->

1.git init
2.git add .

<!--9.Crear un primer commit con el mensaje “Versión Inicial”. -->

git commit -m "Version Inicial

<!--10. Agregar al README.md los comandos que ejecutaron en cada paso. -->

Escribo paso por paso.

<!-- 11.Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio” -->

git add .

git commit -m "Agregar solución primer ejercicio"

Importante:git add . y git commit -""se puede abreviar con git commit -am "Agregar solución primer ejercicio"

<!-- 12. Publicar a Github en un repositorio llamado aspirantes-mir-ejercicio-1. -->

Crea repositorio aspirantes-mir-ejercicio-1 desde Github.

Crea repositorio aspirantes-mir-ejercicio-1
aspirantes-mir-ejercicio-1.1 porque estoy repitiendo el curso.

git remote add origin git@github.com:GermanGuerrero95/aspirantes-mir-ejercicio-1.1.git
git branch -M main
git push -u origin main
