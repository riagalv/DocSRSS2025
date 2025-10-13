#Reto 
## Descripcion del reto
Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one? Image: [this](https://mercury.picoctf.net/static/5eb456e480e485183c9c1b16952c6eda/dolls.jpg)
## Solucion
picoCTF{336cf6d51c9d9774fd37196c1d7320ff}
descargamos la imagen
![[Pasted image 20251012145836.png]]
y verificamos si tiene contenido anexo con `binwalk`
![[Pasted image 20251012145930.png]]
descomprimimos y hacemos lo mismo
![[Pasted image 20251012150018.png]]
y asi varias veces hasta q lleguemos a la 4_c y ahí nos da la bandera en un txt, solo lo leemos y listo
![[Pasted image 20251012150234.png]]
## Notas

## Referencias
