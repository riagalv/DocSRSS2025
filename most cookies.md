#Reto 
## Descripcion del reto
Alright, enough of using my own encryption. Flask session cookies should be plenty secure! [server.py](https://mercury.picoctf.net/static/60f76192f6e1fea6f4e6e8c5fc9a6a27/server.py) [http://mercury.picoctf.net:44693/](http://mercury.picoctf.net:44693/)
## Solucion
picoCTF{pwn_4ll_th3_cook1E5_dbfe90bf}
sacamos la cookie del sitio web
![[Pasted image 20250930185840.png]]
del archivo server.py copiamos el contenido de las galletas
![[Pasted image 20250930185939.png]]
creamos un archivo y agregamos el contenido anterior
crackeamos la cookie para q nos de la palabra clave
![[Pasted image 20250930185814.png]]
sacamos una nueva cookie
![[Pasted image 20250930191955.png]]
y la usamos para saber la bandera
![[Pasted image 20250930191740.png]]
## Notas

## Referencias

pluma server.py 

flsk-unsing --sign --cookie "{'very_auth' : 'admin'}"  --secret 'fortune'

curl -s  -H""