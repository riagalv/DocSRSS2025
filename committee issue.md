#Reto 
## Descripcion del reto
I accidentally wrote the flag down. Good thing I deleted it!You download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/76/challenge.zip)
## Solucion
picoCTF{s@n1t1z3_7246792d}
````
cowboyofnoname-picoctf@webshell:~$ cd drop-in/
cowboyofnoname-picoctf@webshell:~/drop-in$ git checkout e720dc26a1a55405fbdf4d338d465335c439fb3e
Note: switching to 'e720dc26a1a55405fbdf4d338d465335c439fb3e'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at e720dc2 create flag
cowboyofnoname-picoctf@webshell:~/drop-in$ ls message.txt 
message.txt
cowboyofnoname-picoctf@webshell:~/drop-in$ cat message.txt 
picoCTF{s@n1t1z3_7246792d}
cowboyofnoname-picoctf@webshell:~/drop-in$ 
`````
## Notas

## Referencias
