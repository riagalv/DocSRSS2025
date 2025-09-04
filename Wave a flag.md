#Reto 
## Descripcion del reto
Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm) has extraordinarily helpful information...
## Solucion
picoCTF{b1scu1ts_4nd_gr4vy_f0668f62}

````
se descarga el archivo
wget https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm
 se le dan los permisos
cowboyofnoname-picoctf@webshell:~$ chmod +x warm
se ejecuta el archivo
cowboyofnoname-picoctf@webshell:~$ ./warm
Hello user! Pass me a -h to learn what I can do!

cowboyofnoname-picoctf@webshell:~$ ./warm -h
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_f0668f62}
`````
## Notas

## Referencias
