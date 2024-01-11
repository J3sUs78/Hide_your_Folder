
Aquí te explico el código de forma sencilla:

Este código está diseñado para proteger una carpeta llamada "CarpetaProtegida" en tu ordenador. Lo hace ocultando la carpeta y requiriendo una contraseña para desbloquearla.

Así funciona:

Comprueba si la carpeta protegida existe: Si la carpeta ya existe, el código te preguntará si quieres ocultarla. Si no existe, la creará.

Ocultar la carpeta: Si eliges ocultar la carpeta, el código la renombrará con un nombre especial que la oculta de la vista normal. También la marcará como oculta y de sistema, lo que dificulta aún más su acceso.

Desbloquear la carpeta: Para desbloquear la carpeta, deberás introducir la contraseña correcta. Si la contraseña es correcta, el código hará visible la carpeta de nuevo y eliminará los atributos ocultos y de sistema.

Primera vez que abres tu archivo de texto vacio dentro de la carpeta donde tengas tus archivos dedlicados, entonces una vez en esa carpeta, creas un txt...
a este el nombre que quieras esta bien ponerle....
-Luego vamos a lo rico, pegamos todo el codigo que esta en script base....
-despues pegado el codigo, debemos cambiar el parametro para crear la contraseña que queramos...

-El bloque de codigo que buscamos es este: 
============================================
:UNLOCK
echo Introduzca la contrasena para mostrar la CarpetaProtegida
set/p "pass="
if NOT %pass%== YOUR-PASSWORD goto FAIL
attrib -h -s "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}"
ren "Control Panel.{21EC2020-3AEA-1069-A2DD-08002B30309D}" CarpetaProtegida
echo Folder Unlocked successfully
goto End

=============================================

-Bueno claramente debemos cambiar solo el parametro que dice YOUR-PASSWORD
borramos y reemplazamos...
luego guardamos como... y guardamos como .bat ahora en vez de .txt
-IMPORTANTE cambiar a todo tipo de archivos, no solo .txt
Esto lo guardamos en el carpeta y creara el bat, bueno lo abrimos 
y esto tira: Quiere ocultar la CarpetaProtegida? (S/N) 
tu dale que si...
esto crea la carpeta secreta y bueno mete todo lo delicado ahi, luego abres el bat 
y este ahora preguntará por una contraseña, la que ingresaste en el codigo es...
como olvides esta clave... perdiste amig@...
te deseo suerte en tu camino... luego ingresada la clave esta muestra la carpeta y listo, volvieron, para ocultar denuevo, solo abre el bat...
Like 