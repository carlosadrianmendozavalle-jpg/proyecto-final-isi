# proyecto-final-isi
# Ejercicios y algoritmos básicos desarrollados en Python para ISI.

# Proyecto Final - Algoritmos de Programación

Nombre: Carlos Adrian Mendoza Valle
Sección:ISI-101

## 📝 Lista de Algoritmos en PSeInt
Estos son los algoritmos que he desarrollado hasta ahora:
Algoritmo 1: Hola Mundo

print("Hola Mundo")

nombre = "Carlos Adrian"
print("Bienvenido al proyecto final de", nombre)


Algoritmo 2: Cálculo de áreas


# Algoritmo 2: Cálculo de Áreas Geométricas
import math

print("--- Menú de Áreas ---")
print("1. Cuadrado")
print("2. Triángulo")
print("3. Círculo")

opcion = input("Elige una opción (1, 2 o 3): ")

if opcion == "1":
    lado = float(input("Ingresa el lado del cuadrado: "))
    area = lado * lado
    print(f"El área del cuadrado es: {area}")

elif opcion == "2":
    base = float(input("Ingresa la base del triángulo: "))
    altura = float(input("Ingresa la altura del triángulo: "))
    area = (base * altura) / 2
    print(f"El área del triángulo es: {area}")

elif opcion == "3":
    radio = float(input("Ingresa el radio del círculo: "))
    area = math.pi * (radio ** 2)
    print(f"El área del círculo es: {area:.2f}")

else:
    print("Opción no válida.")




Algoritmo 4:Suma simple


print("--- Programa de Suma Simple ---")

numero1 = float(input("Ingresa el primer número: "))
numero2 = float(input("Ingresa el segundo número: "))

# Realizamos la operación
resultado = numero1 + numero2

# Mostramos el resultado final
print(f"La suma de {numero1} y {numero2} es: {resultado}")

