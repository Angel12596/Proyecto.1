import random

caracteres= "abcdefghijkmlnopqrstuvwxyz1234567890@!%&/()=¿-+*][}{" #codigo donde se puede cambiar los caracteres de la contraseña

password= ""

for i in range(16):
    password+= random.choice(caracteres)

print(f"Tu contraseña aleatoria es: {password}")
