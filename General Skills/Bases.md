#Reto 
## Descripcion del reto
What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases.
## Solucion
picoCTF{l3arn_th3_r0p35}
la verdad en esta batalle y le pregunte a chatgpt primero si sabia como solucionar algo asi, lo intente con un ejemplo q me dio pero no me compilaba en la webshell, entonces mejor le di todo el problema y me explico y pues de ahi lo puse como me dijo y me dio esa respuesta :p
````python
>>> import base64
>>> 
>>> texto = "bDNhcm5fdGgzX3IwcDM1"
>>> decodificado = base64.b64decode(texto).decode("utf-8")
>>> print(decodificado)
l3arn_th3_r0p35
````


## Notas
creo para la otra lo puedo hacer mejor y espero no buscar en chatgpt

## Referencias
