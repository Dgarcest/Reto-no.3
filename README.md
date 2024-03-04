# Reto-no.3
Repositorio donde se plantea el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo y se revisa el procedimiento matemático para hallar raíces cuadradas planteando el algoritmo en pseudocódigo y en diagrama de flujo.

# Algoritmo - primos

### Este algoritmo sirve para hallar los numeros primos hasta un numero n

PASO 1. Escoger el numero n hasta el que va la lista

PASO 2. Crear la lista con los numeros del 2 hasta el n

PASO 3. Eliminar de la lista todos los multiplos del 2, menos el 2

PASO 4. Ubicar el siguiente numero en la lista

PASO 5. Eliminar todos los multiplos del número del paso anterior de la lista, menos el mismo número

PASO 6. Repetir 4 y 5 hasta que ya no queden números por ubicar

PASO 7. Todos los números de la lista resultante son primos

# Pseudocódigo - primos

### Este es el pseudocódigo del mismo problema

```pseudocode
  n : entero
  m : entero
  j = 3
  x = 3
  INICIO
    Lista[2, ..., n]
    Mientras x<n hacer
      Si x == multiplo de 2, entonces
        eliminar x de la lista
      x = x+1
    Fin Mientras
    Mientras j != n hacer
        m=3
        Mientras m<n hacer
          Si m == multiplo del siguiente numero en la lista, entonces
          eliminar m de la lista, excepto si es el siguiente numero en la lista
          m = m+1
        Fin Mientras
    j = j+1
    Fin mientras
    imprimir "Los números de la lista son primos"
  FIN
```

# Diagrama de flujo - primos

[![Diagrama-de-flujo.png](https://i.postimg.cc/13gmytk9/Diagrama-de-flujo.png)](https://postimg.cc/JsLVq17g)

# Pseudocódigo - raíces

### Este pseudocódigo sirve para hallar raices cuadradas exactas

```pseudocode
  INICIO
  n : entero
  j = 1
  x = n/j
  Mientras j!=x hacer:
    x=n/j
    Si j!=x, entonces
    j = j+1
    Si j>x, entonces
      imprimir "El numero no tiene raiz cuadrada exacta"
      terminar Mientras
  Fin Mientras
  Imprimir "la raíz es j"
  FIN
```

# Diagrama de flujo - raíces

[![diagrama-de-flujo-2.png](https://i.postimg.cc/jq3B1zsg/diagrama-de-flujo-2.png)](https://postimg.cc/grRMXLL8)

