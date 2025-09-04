#Reto 
## Descripcion del reto
Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/static)? This [BASH script](https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/ltdis.sh) might help!
## Solucion
picoCTF{d15a5m_t34s3r_98d35619}
````
cowboyofnoname-picoctf@webshell:~$ strings static | grep pico
picoCTF{d15a5m_t34s3r_98d35619}
cowboyofnoname-picoctf@webshell:~$ bash ltdis.sh static 
Attempting disassembly of static ...
Disassembly successful! Available at: static.ltdis.x86_64.txt
Ripping strings from binary with file offsets...
Any strings found in static have been written to static.ltdis.strings.txt with file offset
cowboyofnoname-picoctf@webshell:~$ cat static.ltdis.strings.txt 
cowboyofnoname-picoctf@webshell:~$ cat static.ltdis.strings.txt | grep pico
   1020 picoCTF{d15a5m_t34s3r_98d35619}
`````

## Notas

## Referencias
