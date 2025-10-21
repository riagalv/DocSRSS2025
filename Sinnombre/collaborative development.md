#Reto 
## Descripcion del reto
My team has been working very hard on new features for our flag printing program! I wonder how they'll work together?You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/177/challenge.zip)
## Solucion
picoCTF{t3@mw0rk_m@k3s_th3_dr3@m_w0rk_7ae8dd33}
````
cowboyofnoname-picoctf@webshell:~/drop-in$ nano flag.py 
cowboyofnoname-picoctf@webshell:~/drop-in$ git checkout feature/part-1
Switched to branch 'feature/part-1'
cowboyofnoname-picoctf@webshell:~/drop-in$ ls
flag.py
cowboyofnoname-picoctf@webshell:~/drop-in$ python3 flag.py 
Printing the flag...
picoCTF{t3@mw0rk_cowboyofnoname-picoctf@webshell:~/drop-in$ git checkout feature/part-2
Switched to branch 'feature/part-2'
cowboyofnoname-picoctf@webshell:~/drop-in$ cat flag.py 
print("Printing the flag...")

print("m@k3s_th3_dr3@m_", end='')cowboyofnoname-picoctf@webshell:~/drop-in$ git checkout feature/part-3
Switched to branch 'feature/part-3'
cowboyofnoname-picoctf@webshell:~/drop-in$ cat flag.py 
print("Printing the flag...")

print("w0rk_7ae8dd33}")
cowboyofnoname-picoctf@webshell:~/drop-in$ 
`````
## Notas

## Referencias
