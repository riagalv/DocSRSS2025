#Reto 
## Descripcion del reto
Fix the syntax error in the Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/5/fixme2.py)
## Solucion
picoCTF{3qu4l1ty_n0t_4551gnm3nt_4863e11b}

````
cowboyofnoname-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/5/fixme2.py
--2025-09-10 16:55:49--  https://artifacts.picoctf.net/c/5/fixme2.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.170.131.33, 3.170.131.18, 3.170.131.72, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.170.131.33|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1029 (1.0K) [application/octet-stream]
Saving to: 'fixme2.py'

fixme2.py               100%[============================>]   1.00K  --.-KB/s    in 0s      

2025-09-10 16:55:49 (9.98 MB/s) - 'fixme2.py' saved [1029/1029]

cowboyofnoname-picoctf@webshell:~$ python fixme2.py 
  File "/home/cowboyofnoname-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
cowboyofnoname-picoctf@webshell:~$ python3 fixme2.py 
  File "/home/cowboyofnoname-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
cowboyofnoname-picoctf@webshell:~$ nano fixme2.py 
cowboyofnoname-picoctf@webshell:~$ python3 fixme2.py 
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_4863e11b}
cowboyofnoname-picoctf@webshell:~$ 
`````
## Notas

## Referencias