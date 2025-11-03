Carlos Castañeda

9:59

buenos dias para todos !

_keep_Fijado

Carlos Castañeda

10:01

iniciamos 10:05 aver si llegan algunos mas

_keep_Fijado

Carlos Castañeda

10:19

from PIL import Image import numpy as np imagen1 = np.asarray( Image.open('scrambled1.png') ) imagen2 = np.asarray( Image.open('scrambled2.png') ) todo = imagen1 + imagen2 nueva = Image.fromarray(todo) nueva.save('flag2.png', 'PNG')

Nañez Villegas Oscar Emmanuel

10:20

Soy yo

Carlos Castañeda

10:35

numeros = open('message.txt').read().split() flag = ' ' for numero in numeros: mod = int(numero) % 37 if mod>=0 and mod<=25: c = chr(mod+65) elif mod>=26 and mod<=35: c = chr(mod+22) elif mod==36: c = '_' flag += c print(flag)

Carlos Castañeda

10:41

sudo apt install steghide

Carlos Castañeda

10:43

steghide --extract -sf atbash.jpg
openssl req -in readmycert.csr -noout -text
echo "sdflasd" | base64 -d | strings | grep pico