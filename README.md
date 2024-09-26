#Examen Del Primer Parcial. Codigo Creado Por Ramirez Torres Angel Manuel De 3°W
-  Desarrollar código que lea dos valores que captures, determinar cual de los dos valores es el
menor y escríbalo. Realizar un algoritmo que sume dos números y desplegarlo

print(" ")#Espacio entre lineas
print("-INSTRUCCIONES-")# Imprime las instrucciones del codigo 
print(" Desarrollar código que lea dos valores que captures, determinar cual de los dos valores es el menor y escríbalo. Realizar un algoritmo que sume dos números y desplegarlo ")
print(" ")#Espacio entre lineas

print(" ")
d = "Examen del primer parcial:" #Se declara la variable 'd'
a = "/ Alumno: Ramirez Torres Angel Manuel"#Se declara la variable 'a'
b = "/ Grado y Grupo: 3°W"#Se declara la variable 'b'
c = "/ Mi numero de contro es: 1206"#Se declara la variable 'c'
espacio = (" ")#Se declara la variable 'espacio'

info = d +espacio + a + espacio + b + espacio + c #Aqui se juntan los valores (d, a, b, c, espacio) para crear una sola variable 
print (info)#Muestra el contenido de la variable 'info'
print(" ")

# Capturar dos valores ingresados por el usuario
a = float(input("Ingresa el primer valor: "))
b = float(input("Ingresa el segundo valor: "))

suma = a + b
print("El resultado de la suma es: ") 
print(suma)
print("Y")
# Determinar cuál valor es el menor y el mayor 
if a < b:
    print(f"El valor menor es: {a}")
elif b < a:
    print(f"El valor menor es: {b}")
else:#De lo contrario te marca error y de imprime lo siguiente
    print("Ambos valores son iguales ingresa otros por favor")


![image](https://github.com/user-attachments/assets/51ed75ae-c94e-49c6-88f9-549633f0ca8e)
![image](https://github.com/user-attachments/assets/b57e88f6-434b-4d15-b0d2-8cc80356f5c4)


