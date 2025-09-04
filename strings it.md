#Reto 
## Descripcion del reto
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/5bd86036f013ac3b9c958499adf3e2e2/strings) without running it?
## Solucion
picoCTF{5tRIng5_1T_827aee91}
````
cowboyofnoname-picoctf@webshell:~$ strings strings |grep pico 
picoCTF{5tRIng5_1T_827aee91}
`````

## Notas
strings muestra todas las cadenas
para ejecutar archivos tengo q tener permisos de admin y para darle permiso es chmod +x strings
## Referencias
