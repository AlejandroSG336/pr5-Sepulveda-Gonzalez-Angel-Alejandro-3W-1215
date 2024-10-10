# pr5-Sepulveda-Gonzalez-Angel-Alejandro-3W-1215

# 5. Función que calcula el área de un círculo dado el radio

import math  # Importamos la librería math para usar pi

def area_circulo(radio):

  # Fórmula del área de un círculo: A = πr^2
  return math.pi * radio ** 2

# Función que calcula el volumen de un cilindro usando el área del círculo

def volumen_cilindro(radio, altura):
    
  # Calculamos el volumen multiplicando el área de la base por la altura
  
  return area_circulo(radio) * altura

# Pedimos al usuario que introduzca el radio del círculo

radio = float(input("Introduce el radio del círculo: "))

# Mostramos el área del círculo

print(f"El área del círculo con radio {radio} es: {area_circulo(radio)}")

# Pedimos al usuario que introduzca la altura del cilindro

altura = float(input("Introduce la altura del cilindro: "))

# Mostramos el volumen del cilindro

print(f"El volumen del cilindro con radio {radio} y altura {altura} es: {volumen_cilindro(radio, altura)}")

![image](https://github.com/user-attachments/assets/4db82d1d-9076-4374-a44f-96dfd627abcf)
![image](https://github.com/user-attachments/assets/23b4dd5a-84c1-4193-917f-54622ee00111)
![image](https://github.com/user-attachments/assets/9e112936-9f2f-483d-b5bd-0962ecddc178)
