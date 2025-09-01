#Reto 
## Descripcion del reto
Our flag printing service has started glitching!`$ nc saturn.picoctf.net 54510`
## Solucion
picoCTF{gl17ch_m3_n07_a4392d2e}
no s conectamos al servidor
````
cowboyofnoname-picoctf@webshell:~$ nc saturn.picoctf.net 54510
'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'
`````

despues usamos python para decifrar la bandera

````python
>>> 'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'
'picoCTF{gl17ch_m3_n07_a4392d2e}'
>>> 
`````
## Notas

## Referencias
