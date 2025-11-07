#Reto 
## Descripcion del reto
We found a leak of a blackmarket website's login credentials. Can you find the password of the user `cultiris` and successfully decrypt it?Download the leak [here](https://artifacts.picoctf.net/c/151/leak.tar).The first user in `usernames.txt` corresponds to the first password in `passwords.txt`. The second user corresponds to the second password, and so on.
## Solucion
picoCTF{C7r1F_54V35_71M3}
descragamos el archivo
![[Pasted image 20251106175746.png]]
vemos q tipo de archivo es, lo extraemos
![[Pasted image 20251106180454.png]]
buscamos el use q nos da, q es cultiris, vemos la posicion en la q esta
![[Pasted image 20251106182157.png]]
ahora en passwords buscamos en la misma posicion
![[Pasted image 20251106182317.png]]
tomamos la llave y la decodificamos en cyberchef usando la herramienta de ROT13
![[Pasted image 20251106182525.png]]

## Notas

## Referencias
