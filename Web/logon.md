#Reto 
## Descripcion del reto
The factory is hiding things from all of its users. Can you login as Joe and find what they've been looking at? `https://jupiter.challenges.picoctf.org/problem/15796/` ([link](https://jupiter.challenges.picoctf.org/problem/15796/)) or http://jupiter.challenges.picoctf.org:15796
## Solucion
picoCTF{th3_c0nsp1r4cy_l1v3s_6edb3f5f}
usando cookie editor y cambiando donde dice admin de Flse por True y ya 
![[Pasted image 20250917111944.png]]
## Notas
curl -X GET https://jupiter.challenges.picoctf.org/problem/15796//flag -H "Cookie: username=admin; password=admin; admin;True "
## Referencias

