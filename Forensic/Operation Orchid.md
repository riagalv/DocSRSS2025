#Reto 
## Descripcion del reto
Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/213/disk.flag.img.gz)
## Solucion
picoCTF{h4un71ng_p457_5113beab}
Descomprimimos al archivo del reto, es nuevamente una imagen de disco a examinar, listamos las particiones:
![[Pasted image 20251016145944.png]]
listamos los archivos en la partición
![[Pasted image 20251016150004.png]]
vemos el archivo con el historial de comandos
![[Pasted image 20251016150215.png]]
vemos el archivo que tiene la bandera encriptada
![[Pasted image 20251016150242.png]]
metemos la bandera encriptada en un archivo txt
![[Pasted image 20251016150345.png]]
desencriptamos la bandera, haciendo las operaciones inversas que se usaron para encriptarla
![[Pasted image 20251016150334.png]]
y solo leemos el archivo
![[Pasted image 20251016150431.png]]
## Notas

## Referencias