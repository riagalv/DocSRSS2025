#Reto 
## Descripcion del reto
Unzip this archive and find the flag.

- [Download zip file](https://artifacts.picoctf.net/c/504/big-zip-files.zip)
## Solucion
picoCTF{gr3p_15_m4g1c_ef8790dc}
primero se descarga con wget y despues se ponen estos comandos
````
cowboyofnoname-picoctf@webshell:~$ file *
README.txt:        ASCII text, with escape sequences
big-zip-files:     directory
big-zip-files.zip: Zip archive data, at least v1.0 to extract, compression method=store
enc_flag:          ASCII text
cowboyofnoname-picoctf@webshell:~$ grep -r picoCTF big-zip-files
big-zip-files/folder_pmbymkjcya/folder_cawigcwvgv/folder_ltdayfmktr/folder_fnpfclfyee/whzxrpivpqld.txt:information on the record will last a billion years. Genes and brains and books encode picoCTF{gr3p_15_m4g1c_ef8790dc}
`````
## Notas
olvide poner el -r al momento de usar el grep y por eso no me daba
## Referencias
