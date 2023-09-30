<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->
def ejercicio1():
    numero = int(input("Ingrese un número: "))
    if numero % 2 == 0:
        print("El número es par")
    else:
        print("El número es impar")

def ejercicio2():
    numero1 = int(input("Ingrese el primer número: "))
    numero2 = int(input("Ingrese el segundo número: "))
    suma = numero1 + numero2
    print("La suma de los números es:", suma)


def ejercicio3():
    numero = int(input("Ingrese un número: "))
    while numero >= 0:
        print(numero)
        numero -= 1

def ejercicio4():
    numero = int(input("Ingrese un número: "))
    factorial = 1
    for i in range(1, numero+1):
        factorial *= i
    print("El factorial de", numero, "es:", factorial)

def ejercicio5():
    numero = int(input("Ingrese un número: "))
    for i in range(1, 11):
        resultado = numero * i
        print(numero, "x", i, "=", resultado)

def main():
    while True:
        print("Menú:")
        print("1. Ejercicio 1")
        print("2. Ejercicio 2")
        print("3. Ejercicio 3")
        print("4. Ejercicio 4")
        print("5. Ejercicio 5")
        print("6. Salir")

        opcion = input("Selecciona una opción: ")

        if opcion == "1":
            ejercicio1()
        elif opcion == "2":
            ejercicio2()
        elif opcion == "3":
            ejercicio3()
        elif opcion == "4":
            ejercicio4()
        elif opcion == "5":
            ejercicio5()
        elif opcion == "6":
            break
        else:
            print("Opción inválida. Por favor, selecciona una opción válida.")

if __name__ == "__main__":
    main()






