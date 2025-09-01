#Reto 
## Descripcion del reto
This file has a flag in plain sight (aka "in-the-clear"). [Download flag](https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag).
## Solucion
se descarga el archivo
````
cowboyofnoname-picoctf@webshell:~$ wget https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag
--2025-09-01 17:14:10--  https://mercury.picoctf.net/static/33996e32dce022205a6a36f69aba56f0/flag
Resolving mercury.picoctf.net (mercury.picoctf.net)... 18.189.209.142
Connecting to mercury.picoctf.net (mercury.picoctf.net)|18.189.209.142|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 34 [application/octet-stream]
Saving to: 'flag'

flag                    100%[============================>]      34  --.-KB/s    in 0s      

2025-09-01 17:14:10 (34.6 MB/s) - 'flag' saved [34/34]
`````
se lee con  cat flag

````
cowboyofnoname-picoctf@webshell:~$ cat flag
picoCTF{s4n1ty_v3r1f13d_2aa22101}
cowboyofnoname-picoctf@webshell:~$ 
`````

picoCTF{s4n1ty_v3r1f13d_2aa22101}
## Notas
cat permite mostarr un archivo de texto
## Referencias
