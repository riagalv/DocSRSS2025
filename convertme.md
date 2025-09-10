#Reto 
## Descripcion del reto
Run the Python script and convert the given number from decimal to binary to get the flag.[Download Python script](https://artifacts.picoctf.net/c/24/convertme.py)
## Solucion
picoCTF{4ll_y0ur_b4535_722f6b39}
````
cowboyofnoname-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/24/convertme.py
--2025-09-10 20:41:58--  https://artifacts.picoctf.net/c/24/convertme.py
Resolving artifacts.picoctf.net (artifacts.picoctf.net)... 3.170.131.33, 3.170.131.72, 3.170.131.18, ...
Connecting to artifacts.picoctf.net (artifacts.picoctf.net)|3.170.131.33|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1189 (1.2K) [application/octet-stream]
Saving to: 'convertme.py'

convertme.py            100%[============================>]   1.16K  --.-KB/s    in 0s      

2025-09-10 20:41:59 (269 MB/s) - 'convertme.py' saved [1189/1189]

cowboyofnoname-picoctf@webshell:~$ cat convertme.py 

import random



def str_xor(secret, key):
    #extend key to secret length
    new_key = key
    i = 0
    while len(new_key) < len(secret):
        new_key = new_key + key[i]
        i = (i + 1) % len(key)        
    return "".join([chr(ord(secret_c) ^ ord(new_key_c)) for (secret_c,new_key_c) in zip(secret,new_key)])


flag_enc = chr(0x15) + chr(0x07) + chr(0x08) + chr(0x06) + chr(0x27) + chr(0x21) + chr(0x23) + chr(0x15) + chr(0x5f) + chr(0x05) + chr(0x08) + chr(0x2a) + chr(0x1c) + chr(0x5e) + chr(0x1e) + chr(0x1b) + chr(0x3b) + chr(0x17) + chr(0x51) + chr(0x5b) + chr(0x58) + chr(0x5c) + chr(0x3b) + chr(0x42) + chr(0x57) + chr(0x5c) + chr(0x0d) + chr(0x5f) + chr(0x06) + chr(0x46) + chr(0x5c) + chr(0x13)


num = random.choice(range(10,101))

print('If ' + str(num) + ' is in decimal base, what is it in binary base?')

ans = input('Answer: ')

try:
  ans_num = int(ans, base=2)
  
  if ans_num == num:
    flag = str_xor(flag_enc, 'enkidu')
    print('That is correct! Here\'s your flag: ' + flag)
  else:
    print(str(ans_num) + ' and ' + str(num) + ' are not equal.')
  
except ValueError:
  print('That isn\'t a binary number. Binary numbers contain only 1\'s and 0\'s')
cowboyofnoname-picoctf@webshell:~$ python3 convertme.py 
If 67 is in decimal base, what is it in binary base?
Answer: 1000011
That is correct! Here's your flag: picoCTF{4ll_y0ur_b4535_722f6b39}
cowboyofnoname-picoctf@webshell:~$ 
`````
## Notas

## Referencias
