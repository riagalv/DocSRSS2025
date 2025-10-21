#Reto 
## Descripcion del reto
Fix the syntax error in this Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/26/fixme1.py)
## Solucion
picoCTF{1nd3nt1ty_cr1515_09ee727a}

````
cowboyofnoname-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/26/fixme1.py
--2025-09-10 16:53:00--  https://artifacts.picoctf.net/c/26/fixme1.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.170.131.33, 3.170.131.72, 3.170.131.18, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.170.131.33|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 837 [application/octet-stream]
Saving to: 'fixme1.py'

fixme1.py               100%[============================>]     837  --.-KB/s    in 0s      

2025-09-10 16:53:00 (29.6 MB/s) - 'fixme1.py' saved [837/837]

cowboyofnoname-picoctf@webshell:~$ nano fixme1.py
cowboyofnoname-picoctf@webshell:~$ python3 fiix
.local/        .ssh/          big-zip-files/ files/         fixme1.py      
cowboyofnoname-picoctf@webshell:~$ python3 fiix
Display all 3238 possibilities? (y or n)
cowboyofnoname-picoctf@webshell:~$ python3 fiix
python3: can't open file '/home/cowboyofnoname-picoctf/fiix': [Errno 2] No such file or directory
cowboyofnoname-picoctf@webshell:~$ python3 fixme1.py 
That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}
cowboyofnoname-picoctf@webshell:~$ 
`````
## Notas

## Referencias

