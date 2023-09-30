<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->
punto 1
def calculadora(n1,n2,operacion):
    resultado:0
    if operacion=="+":
        resultado =n1+n2
    elif operacion=="-":
        resultado =n1-n2
    elif operacion =="*":
        resultado =n1*n2
    elif operacion=="/":
        resultado =n1/n2
    return resultado
i=calculadora(10,56,"-")
print(i)

punto 2
def contar_vocales(cad):
    return sum(c in {"a", "A", "e", "E", "i", "I", "o", "O", "u", "U"} for c in cad)
cadena = input("Ingresa una cadena: ")
print(contar_vocales(cadena))

punto 3
def es_primo(num):
    if num < 2:
        return False
    for i in range(2, int(num ** 0.5) + 1):
        if num % i == 0:
            return False
    return True
numero = int(input("Ingresa un número: "))
print(es_primo(numero))

punto 4
def contar_palabras(cadena):
    palabras = cadena.split()
    return len(palabras)
cadena = input("Ingresa una cadena: ")
print(contar_palabras(cadena))

punto 5
def potencia(base, exponente):
    resultado = base ** exponente
    return resultado
i=potencia(2,3)
print(i)





