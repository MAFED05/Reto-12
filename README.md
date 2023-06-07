# Quiero que ya se acabe el semestre

Bienvenidos a este reto #12, algo corto pero bastante complejo desde mi punto de vista. Pero bueno, sin más que añadir, comencemos...

## Punto 1

Consulte que hacen los siguientes métodos de strings en python: endswith, startswith, isalpha, isalnum, isdigit, isspace, istitle, islower, isupper.

### Solución

* #### endswith

Funciona por medio de Booleanos (True and False) para determinar si una cadena termina con un sufijo en específico

``` python
cadena = "Hola, ¿Hoy nos podemos ver?"
if cadena.endswith("?"):
    print("La cadena finaliza con un signo de interrogación.")
else:
    print("La cadena no finaliza con un signo de interrogación.")

```

* #### startswith

Es parecido a endswith pues también trabaja por medio de booleanos, pero la diferencia es que este determina si la cadena comienza con un prefijo específico.

``` python
cadena = "Buenas tardes, ¿cómo estás?"
if cadena.startswith("Buenas"):
    print("La cadena comienza con 'Buenas'.")
else:
    print("La cadena no comienza con 'Buenas'.")

```

* #### isalpha

Esta función es utilizada para determinar si una cadena de texto contiene únicamente caracteres alfabéticos. Retorna True, si la cadena solo contiene caracteres del abecedario y no esta vacía, en caso contrario retornará False como respuesta

``` python
cadenaA = "Saludo"
cadenaB = "Saludo123"

print(cadenaA.isalpha())  # True
print(cadenaB.isalpha())  # False
```
* #### isalnum

Esta es una función similar a .isalpha, pero en este caso el programa revisa si la cadena contiene caracteres de tipo alfanumérico y retorna un booleano dependiendo de la cadena ingresada

``` python
cadenaA = "Saludo123"
cadenaB = "Saludo 123"

print(cadenaA.isalnum())  # True
print(cadenaB.isalnum())  # False
```
* #### isdigit

Igual que todas las funciones vistas anteriormente, esta también retorna booleanos. En este caso, la función .isdigit verifica que la cadena ingresada solo contenga dígitos.

``` python
cadenaA = "98765"
cadenaB = "12a45"
```

print(cadenaA.isdigit())  # True
print(cadenaB.isdigit())  # False


* #### isspace

Se utiliza para verificar si la cadena contiene solamente espacios en blanco

``` python
cadenaA= "    "
cadenaB = "   Saludo   "
cadenaC = "Saludo"

print(cadenaA.isspace())  # True
print(cadenaB.isspace())  # False
print(cadenaC.isspace())  # False
```
* #### istitle

Esta función verifica si la cadena contiene algún título dentro de esta.

``` python
cadenaA = "Hola Mundo"
cadenaB = "Hola mundo"
cadenaC = "Hola 123"

print(cadenaA.istitle())  # True
print(cadenaB.istitle())  # False
print(cadenaC.istitle())  # False

```
* #### islower

Verifica si la cadena solo contiene caracteres en minúscula.

``` python
cadenaA = "saludo global"
cadenaB = "Saludo Global"
cadenaC = "12a353"
cadenaD = ""

print(cadenaA.islower())  # True
print(cadenaB.islower())  # False
print(cadenaC.islower())  # False
print(cadenaD.islower())  # False
```

* #### isupper

Parecida a .islower, pero en este caso se verifica si la cadena contiene únicamente caracteres en mayúscula

``` python
cadenaA = "SALUDO GLOBAL"
cadenaB = "Saludo Global"
cadenaC = "12rt345"
cadenaD = ""

print(cadenaA.isupper())  # True
print(cadenaB.isupper())  # False
print(cadenaC.isupper())  # False
print(cadenaD.isupper())  # False
```
