#Reto 
## Descripcion del reto
How well can you perfom basic binary operations?

Additional details will be available after launching your challenge instance.
## Solucion
picoCTF{b1tw^3se_0p3eR@tI0n_su33essFuL_aeaf4b09}
````
Welcome to the Binary Challenge!"
Your task is to perform the unique operations in the given order and find the final result in hexadecimal that yields the flag.

Binary Number 1: 11001000
Binary Number 2: 01110110


Question 1/6:
Operation 1: '+'
Perform the operation on Binary Number 1&2.
Enter the binary result: ^C
cowboyofnoname-picoctf@webshell:~$ nc titan.picoctf.net 56454

Welcome to the Binary Challenge!"
Your task is to perform the unique operations in the given order and find the final result in hexadecimal that yields the flag.

Binary Number 1: 01111000
Binary Number 2: 11101100


Question 1/6:
Operation 1: '<<'
Perform a left shift of Binary Number 1 by 1 bits.
Enter the binary result: 101100100
Incorrect. Try again
Enter the binary result: 11110000
Correct!

Question 2/6:
Operation 2: '*'
Perform the operation on Binary Number 1&2.
Enter the binary result: 110111010100000
Correct!

Question 3/6:
Operation 3: '>>'
Perform a right shift of Binary Number 2 by 1 bits .
Enter the binary result: 01110110
Correct!

Question 4/6:
Operation 4: '|'
Perform the operation on Binary Number 1&2.
Enter the binary result: 11111100
Correct!

Question 5/6:
Operation 5: '&'
Perform the operation on Binary Number 1&2.
Enter the binary result: 01101000
Correct!

Question 6/6:
Operation 6: '+'
Perform the operation on Binary Number 1&2.
Enter the binary result: 101100100
Correct!

Enter the results of the last operation in hexadecimal: 0x164

Correct answer!
The flag is: picoCTF{b1tw^3se_0p3eR@tI0n_su33essFuL_aeaf4b09}

`````
## Notas
use cyberchef
https://gchq.github.io/CyberChef/
## Referencias
