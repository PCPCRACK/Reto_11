# Reto_11

1. Desarrolle un programa que permita realizar la [suma/resta de matrices](https://es.wikipedia.org/wiki/Adici%C3%B3n_matricial). El programa debe validar las condiciones necesarias para ejecutar la operación.

2. Desarrolle un programa que permita realizar el [producto de matrices](https://es.wikipedia.org/wiki/Multiplicaci%C3%B3n_de_matrices). El programa debe validar las condiciones necesarias para ejecutar la operación.

3. Desarrolle un programa que permita obtener la  [matriz transpuesta](https://es.wikipedia.org/wiki/Matriz_transpuesta) de una matriz ingresada. El programa debe validar las condiciones necesarias para ejecutar la operación.

4. Desarrollar un programa que sume los elementos de una columna dada de una matriz.
```python
def imprimirMatriz(mat):
  for i in range(len(mat)):
      print(mat[i])
  

if __name__ == "__main__":
  nFilas = int(input("Ingrese filas: "))
  nCols = int(input("Ingrese columnas: "))
  ones = []
  twos = []
  tresh = []
  sum = int(0)
  for j in range(nFilas):
      for i in range(nCols):
        n = int(input(f"valores fila {i+1} columna {j+1}: "))
        sum += (n)
        ones.append(n)
      twos.append(ones)
      print(f"suma columna {j+1} es {sum} ")
      ones = []
      sum = 0
  imprimirMatriz(twos)
```
5. Desarrollar un programa que sume los elementos de una fila dada de
una matriz.
```python
if __name__ == "__main__":
    la = int(input("Ingrese filas: "))
    li = int(input("Ingrese columnas: "))
    m = []
    for i in range(la):
        fila = []
        for j in range(li):
            n=int(input(f"valores fila {i+1} columna {j+1}: "))
            fila.append(n)
        m.append(fila)
    for fila in m:
        print(fila)
    sum = int(0)
    for i in range(li):
        for fila in m:
            sum += fila[i]
        print(f"suma fila {i+1} es {sum}")
        sum = 0
```
