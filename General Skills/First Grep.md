#Reto 
## Descripcion del reto
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/315d3325dc668ab7f1af9194f2de7e7a/file)? This would be really tedious to look through manually, something tells me there is a better way.
## Solucion
descargar el archivo en la consolo a con wget
```
wget
cowboyofnoname-picoctf@webshell:~$ wget https://jupiter.challenges.picoctf.org/static/315d3325dc668ab7f1af9194f2de7e7a/file
--2025-09-01 17:05:59--  https://jupiter.challenges.picoctf.org/static/315d3325dc668ab7f1af9194f2de7e7a/file
Resolving jupiter.challenges.picoctf.org (jupiter.challenges.picoctf.org)... 3.131.60.8
Connecting to jupiter.challenges.picoctf.org (jupiter.challenges.picoctf.org)|3.131.60.8|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 14551 (14K) [application/octet-stream]
Saving to: 'file'

file                    100%[============================>]  14.21K  --.-KB/s    in 0s      

2025-09-01 17:05:59 (436 MB/s) - 'file' saved [14551/14551]
``````
 ````
 cowboyofnoname-picoctf@webshell:~$ grep 'picoCTF' file
picoCTF{grep_is_good_to_find_things_f77e0797}
cowboyofnoname-picoctf@webshell:~$ 
 `````
 
picoCTF{grep_is_good_to_find_things_f77e0797}
## Notas
wc cuenta las lineas,bytes y caracteres  de un archivo de texto
## Referencias