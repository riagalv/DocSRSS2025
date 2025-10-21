#Reto 
## Descripcion del reto
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/18/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/18/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/18/level3.hash.bin) in the same directory too.There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.
## Solucion
picoCTF{m45h_fl1ng1ng_6f98a49f}
````
cowboyofnoname-picoctf@webshell:~$ python3 level3.py 
Please enter correct password for flag: ^CTraceback (most recent call last):
  File "/home/cowboyofnoname-picoctf/level3.py", line 39, in <module>
    level_3_pw_check()
  File "/home/cowboyofnoname-picoctf/level3.py", line 27, in level_3_pw_check
    user_pw = input("Please enter correct password for flag: ")
KeyboardInterrupt

cowboyofnoname-picoctf@webshell:~$ nano level3.py 
cowboyofnoname-picoctf@webshell:~$ python3 level3.py 
zlccIQFwg15dUcl=db1bmZ6j3=a83c}
&h;8U,;5m?      g4f8fi91^n1o99cog%
s>;h@|ncmo\146m0iina:o93:1%
#8;<(>em;
         74b=6i=4n5ji9gj7%
picoCTF{m45h_fl1ng1ng_6f98a49f}
#b>?_?h8
        m1a=ll>4Tk6j3<djm 
t=i>GL*i`?9[2f`j3;?c
                    <7=lke=2w
cowboyofnoname-picoctf@webshell:~$ 
`````
## Notas

## Referencias

