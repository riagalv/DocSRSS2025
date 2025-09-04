#Reto 
## Descripcion del reto
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.
## Solucion
picoCTF{digital_plumb3r_5ea1fbd7}
- solucion1
````
cowboyofnoname-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 4427 | grep picoCTF  
picoCTF{digital_plumb3r_5ea1fbd7}
`````

- Solucion2
pasar a un archivo y despues leerlo 
````
cowboyofnoname-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 4427 > bandera      
^C
cowboyofnoname-picoctf@webshell:~$ cat bandera | grep pico
picoCTF{digital_plumb3r_5ea1fbd7}
`````
## Notas
| es un pipe en linux q me permite redirigir la salida de un comando, como entradad de otro
## Referencias
