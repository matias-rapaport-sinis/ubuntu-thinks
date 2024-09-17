# ubuntu-thinks

## ¿Como cambiar el nombre de un usuario de Ubuntu en el archvio de sudoers?

1. Iniciar sesion con cualquier usuario. Abrir una terminal con CTRL + ALT + T e iniciar el root con el comando.

````
sudo -i
````

2. Darle una contraseña al usuario de root, algo que puedas recordar, con el comando;

````
passed
````

3. Cierra sesion del usuario que quieres cambiarle el nombre.

4. En la pantalla de inicio con la lista de usuarios de la computadora, sin haber iniciado sesion con ningun usuario vamos a abrir la interfaz de consola con las teclas CTRL + ALT + F4

5. Inicia sesion con el root.

login : root
password : "lo que halla elegido"

6. Ejecutamos el siguiente comando para cambiar el nombre.

````
usermod -l <NuevoNombre> <NombreActual>
````

NOTA: Si te dice que el actual usuario esta actualmente funcionando en cierto puerto, significa que no cerraste correctamente sesion. La solucion mas facìl es ejecutar el paso 7 para salir de la interfaz de consola, reiniciar el equipo y sin abrir sesion con el usuario ejecutar desde el paso 4. 

7. Cierra la interfaz grafica con las teclas CTRL + ALT + F7 o F3

¡Listo!, Inicia sesion y abre una consola, el nombre del usuario en la terminal debeio haber cambiado. 

