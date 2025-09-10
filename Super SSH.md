#Reto 
## Descripcion del reto
Using a Secure Shell (SSH) is going to be pretty important.

Additional details will be available after launching your challenge instance.

---

_debug info: [u:876542 e: p: c:424 i:295897]_

This challenge launches an instance on demand.  
Its current status is: `NOT_RUNNING`
## Solucion
picoCTF{s3cur3_c0nn3ct10n_3e293eea}

````
cowboyofnoname-picoctf@webshell:~$ ssh ctf-player@titan.picoctf.net -p 57894
The authenticity of host '[titan.picoctf.net]:57894 ([3.139.174.234]:57894)' can't be established.
ED25519 key fingerprint is SHA256:4S9EbTSSRZm32I+cdM5TyzthpQryv5kudRP9PIKT7XQ.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added '[titan.picoctf.net]:57894' (ED25519) to the list of known hosts.
ctf-player@titan.picoctf.net's password: 
Welcome ctf-player, here's your flag: picoCTF{s3cur3_c0nn3ct10n_3e293eea}
Connection to titan.picoctf.net closed.
`````
## Notas

## Referencias