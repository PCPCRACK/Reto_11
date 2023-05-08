# Reto_11

1. Desarrolle un programa que permita realizar la [suma/resta de matrices](https://es.wikipedia.org/wiki/Adici%C3%B3n_matricial). El programa debe validar las condiciones necesarias para ejecutar la operación.

2. Desarrolle un programa que permita realizar el [producto de matrices](https://es.wikipedia.org/wiki/Multiplicaci%C3%B3n_de_matrices). El programa debe validar las condiciones necesarias para ejecutar la operación.

3. Desarrolle un programa que permita obtener la  [matriz transpuesta](https://es.wikipedia.org/wiki/Matriz_transpuesta) de una matriz ingresada. El programa debe validar las condiciones necesarias para ejecutar la operación.

4. Desarrollar un programa que sume los elementos de una columna dada de una matriz.
```python
if __name__ == "__main__":

    # Pide la cantidad de filas y columnas al usuario
    la = int(input("Ingrese filas: "))
    li = int(input("Ingrese columnas: "))

    # Crea una lista vacia
    m = []

    # Establece un ciclo con el valor de la
    for i in range(la):

        # Crea una lista vacia
        fila = []

        # Establece un ciclo con el valor de li
        for j in range(li):

            # Pide los valores de n dado fila y columna
            n=int(input(f"valores fila {i+1} columna {j+1}: "))

            # Añade el valor n a la lista fila
            fila.append(n)

        # Añade la lista fila a la lista m
        m.append(fila)

    # Establece un ciclo en el tamaño de la lista m
    for fila in m:

        # Imprime el valor fila
        print(fila)

    # Estable sum igual a cero como entero
    sum = int(0)

    # Establece un ciclo con el valor de li
    for i in range(li):

        # Establece un ciclo en el tamaño de la lista m
        for fila in m:

            # Suma el valor de fila[i] en la variable sum
            sum += fila[i]

        # Imprime la suma de la columna
        print(f"suma columna {i+1} es {sum}")

        # Establece sum con valor igual a cero
        sum = 0
```
5. Desarrollar un programa que sume los elementos de una fila dada de
una matriz.
```python
# Definimos una funcion
def imprimirMatriz(mat):

    # Establecemos un ciclo del tamaño del arreglo mat
    for i in range(len(mat)):

        # Imprime el valor de mat
        print(mat[i])
  

if __name__ == "__main__":

    # Estable el tamaño de las filas
    nFilas = int(input("Ingrese filas: "))

    # Estable el tamaño de las columnas
    nCols = int(input("Ingrese columnas: "))

    # Crea dos listas vacias
    ones = []
    twos = []

    # Define sum igual a cero como entero
    sum = int(0)

    # Establecemos un ciclo del tamaño nFilas
    for j in range(nFilas):

        # Establecemos un ciclo del tamaño nCols
        for i in range(nCols):

            # Establece n como el numero ingresado
            n = int(input(f"valores columna {i+1} fila {j+1}: "))

            # Aa variable sum agrega el valor de n
            sum += (n)

            # Añade el valor de n a la lista ones
            ones.append(n)

        # Añade la lista ones a la lista twos al terminar el ciclo for
        twos.append(ones)

        # Imprime la suma fila
        print(f"suma fila {j+1} es {sum} ")

        # Vacia la lista ones
        ones = []

        # Establece sum igual a cero
        sum = 0

    # Al finalizar los dos ciclos llama la funcion
    imprimirMatriz(twos)
```
