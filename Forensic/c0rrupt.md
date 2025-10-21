#Reto 
## Descripcion del reto
We found this [file](https://jupiter.challenges.picoctf.org/static/ab30fcb7d47364b4190a7d3d40edb551/mystery). Recover the flag.
## Solucion
picoCTF{c0rrupt10n_1847995}
vemos q tipo de archivo es
![[Pasted image 20251006084749.png]]
checamos con hex code el head
![[Pasted image 20251006084844.png]]
abrimos el editor
![[Pasted image 20251006090346.png]]
le cambiamos los bytes
![[Pasted image 20251006090303.png]]
reparamos el chunk
![[Pasted image 20251006090511.png]]
reparamos la cabecera png
![[Pasted image 20251006092300.png]]
corregimos el chunk ihdr
![[Pasted image 20251006092313.png]]
se corrige el crc del chunk pHYs
![[Pasted image 20251006092323.png]]
corregimos el tipo IDAT
![[Pasted image 20251006092334.png]]
y la longitud del chunk IDAT
![[Pasted image 20251006092348.png]]
vemos el tipo de archivo q es
![[Pasted image 20251006092430.png]]
verificamos si hay errores
![[Pasted image 20251006092502.png]]
y abrimos la imagen
![[Pasted image 20251006092730.png]]
![[Pasted image 20251006092743.png]]
## Notas

## Referencias