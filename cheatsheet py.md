
# Python Cheatsheet

## Variables
```python
x = 5
y = "Hello"
```

## Tipos de Datos
```python
# Números
int_var = 10
float_var = 20.5

# Cadenas
str_var = "Hola, mundo"

# Booleanos
bool_var = True
```

## Operadores
```python
# Aritméticos
suma = 10 + 5
resta = 10 - 5
multiplicacion = 10 * 5
division = 10 / 5

# Comparación
es_igual = 10 == 5
es_mayor = 10 > 5
es_menor = 10 < 5

# Lógicos
and_op = True and False
or_op = True or False
not_op = not True
```

## Estructuras de Control
```python
# Condicionales
if x > y:
    print("x es mayor que y")
elif x == y:
    print("x es igual a y")
else:
    print("x es menor que y")

# Bucles
# Bucle For
for i in range(5):
    print(i)

# Bucle While
while x > 0:
    print(x)
    x -= 1
```

## Funciones
```python
def mi_funcion(nombre):
    print("Hola " + nombre)

mi_funcion("Alejo")
```

## Listas
```python
mi_lista = [1, 2, 3, 4]
mi_lista.append(5)
print(mi_lista[0])  # Accede al primer elemento
```

## Diccionarios
```python
mi_diccionario = {"nombre": "Alejo", "edad": 18}
print(mi_diccionario["nombre"])
```

## Importar Módulos
```python
import math
print(math.sqrt(25))
```

## Manejo de Excepciones
```python
try:
    print(10 / 0)
except ZeroDivisionError:
    print("No se puede dividir por cero")
finally:
    print("Este bloque se ejecuta siempre")
```
