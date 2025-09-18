#Reto 
## Descripcion del reto
Can you find the robots? `https://jupiter.challenges.picoctf.org/problem/60915/` ([link](https://jupiter.challenges.picoctf.org/problem/60915/)) or http://jupiter.challenges.picoctf.org:60915
## Solucion
primero nos metemos a la liga q nos da
https://jupiter.challenges.picoctf.org/problem/60915/
despues ponemos robots.txt al final 
````
https://jupiter.challenges.picoctf.org/problem/60915/robots.txt
`````
y nos manda el puerto al q falta para ir  a la bandera
User-agent: *
Disallow: /8028f.html
ya solo cambiamos el robots.txt por el puerto restante y nos da la bandera
https://jupiter.challenges.picoctf.org/problem/60915/8028f.html
picoCTF{ca1cu1at1ng_Mach1n3s_8028f}
## Notas

## Referencias
