#Reto 
## Descripcion del reto
We found this [file](https://mercury.picoctf.net/static/da18eed3d15fd04f7b076bdcecf15b27/tunn3l_v1s10n). Recover the flag.
## Solucion
picoCTF{qu1t3_a_v13w_2020}
vemos q tipo de archivo es
![[Pasted image 20251012150613.png]]
vemos los metadatos y ahí verificamos que es un bmp  que se corrompio
![[Pasted image 20251012150647.png]]
vemos el q archivo BMP tiene un encabezado de 12 bytes
![[Pasted image 20251012150727.png]]
luego vienen 40 bytes adicionales de información del encabezado
![[Pasted image 20251012151100.png]]

![[Pasted image 20251012151226.png]]
arreglamos el archivo
![[Pasted image 20251013105133.png]]
y lo abrimos y nos aparece la bandera
![[Pasted image 20251013105157.png]]
![[Pasted image 20251013104840.png]]
## Notas

## Referencias
