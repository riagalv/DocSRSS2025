#Reto 
## Descripcion del reto
You’re given a seemingly ordinary JPG image. Something is tucked away out of sight inside the file. Your task is to discover the hidden payload and extract the flag. Download the jpg image [here](https://challenge-files.picoctf.net/c_saffron_estate/608baf23f98a5a3b435309361a85e3821a917015b2bea188c19921ce38a106c7/img.jpg).
## Solucion

vemos el tipo de archivo q es
![[Pasted image 20251014181303.png]]
en los comentarios viene algo en base64, lo decodificamos
![[Pasted image 20251014181335.png]]
lo extraemos en un txt
![[Pasted image 20251014181411.png]]
y lo leemos
![[Pasted image 20251014181425.png]]

## Notas

## Referencias
