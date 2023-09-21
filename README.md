# Reto_4 😲
By Juan Esteban Molina Rey (eljuanessoy)

### 1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```pseudocode
numero = float(input("Número: "))
if numero == 97:
    print("El número ingresado corresponde a la vocal 'a' en el código ASCII")
elif numero == 101:
    print("El número ingresado corresponde a la vocal 'e' en el código ASCII")
elif numero == 105:
    print("El número ingresado corresponde a la vocal 'i' en el código ASCII")
elif numero == 111:
    print("El número ingresado corresponde a la vocal 'o' en el código ASCII")
elif numero == 117:
    print("El número ingresado corresponde a la vocal 'u' en el código ASCII")
else:
    print("El número ingresado no corresponde a una vocal minúscula en el código ASCII")
```

### 2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```pseudocode
x = (input("Ingrese UNA letra: "))
n = ord(x)
if n%2 == 0:
  print("El codigo ASCII de la letra es par")
else:
  print("El codigo ASCII de la letra es impar")
```

### 3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```pseudocode
x: float = 0.0
print("Ingrese un carácter: ")
x = input("x:")
if (x >= "0" and x <= "9"):
    print("El carácter SI es un dígito")
else:
    print("El carácter NO es un dígito")
```

### 4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

* Positivo: "El número x es positivo"
* Negativo: "El número x es negativo"
* Cero (0): "El número x es el neutro para la suma"

```pseudocode
x: int
print("Ingrese un número: ")
x=int( input("x: "))
if x>0:
  print("El número es positivo")
elif x<0:
  print("El número es negativo")
else:
  print("El número es 0 (neutro)")
```

### 5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

```pseudocode
a : float
b : float
c : float
d : float
e : float
a = float(input("Ingresa el valor del centro de la circunferencia en X: "))
b = float(input("Ingresa el valor del centro de la circunferencia en Y: "))
c = float(input("Ingresa el valor del radio de la circunferencia en X: "))
d = float(input("Ingresa el valor para el punto en X: "))
e = float(input("Ingresa el valor para el punto en Y: "))
if ((d-a)**2 + (e-b)**2)**0.50 <= c:
  print("El punto en X " +str(d)+ "y el punto en Y " +str(e)+ "estan dentro de la circunferencia")
else:
  print("El punto en X " +str(d)+ "y el punto en Y " +str(e)+ "no estan dentro de la circunferencia")
```

### 6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

```pseudocode
LA: float
LB: float
LC: float
LA=input("LA: ")
LB=input("LB: ")
LC=input("LC: ")
if (LA+LB) > LC:
  print("Si se puede formar un triángulo")
else:
  print("No se puede formar un triángulo")
```
