# Reto_11 / PD: Capaz alguien llore cuando vea este codigo
1. Desarrolle un programa que permita realizar la [suma/resta de matrices](https://es.wikipedia.org/wiki/Adici%C3%B3n_matricial). El programa debe validar las condiciones necesarias para ejecutar la operación.
```python
# Funcion para imprimir las matrices
def Santa_inquisicion(Princess_Peach,Peach_youre_so_cool,And_with_my_star_were_gonna_rule):
    """
        Asi es toco hacer la funcion al modo anti-pro osea como noob.
        esto solo es para visualizar la matriz, en caso de que la matriz sea mayor a 15 se no se mostrara las matrices originales.
        trae consigo los valores de Princess_Peach que es el numero de filas,Peach_youre_so_cool que es las matrices y And_with_my_star_were_gonna_rule que es el numero de matrices,
        para compara con un condicional if el valor de And_with_my_star_were_gonna_rule para validar que print utilizar y que no de error el codigo, en tal
        caso tiene hasta un limite de 15 matrices sino retorna 0
    """

    # Imprime un doble espacio para diferenciar las matrices
    print(" ")
    print(" ")
    
    if And_with_my_star_were_gonna_rule == 1:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]))
    elif And_with_my_star_were_gonna_rule == 2:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]))
    elif And_with_my_star_were_gonna_rule == 3:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]))
    elif And_with_my_star_were_gonna_rule == 4:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]))
    elif And_with_my_star_were_gonna_rule == 5:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]))
    elif And_with_my_star_were_gonna_rule == 6:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]))
    elif And_with_my_star_were_gonna_rule == 7:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]))
    elif And_with_my_star_were_gonna_rule == 8:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]))
    elif And_with_my_star_were_gonna_rule == 9:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]),(Peach_youre_so_cool[8][y]))
    elif And_with_my_star_were_gonna_rule == 10:
        for y in range(Princess_Peach):    
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]),(Peach_youre_so_cool[8][y]),(Peach_youre_so_cool[9][y]))
    elif And_with_my_star_were_gonna_rule == 11:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]),(Peach_youre_so_cool[8][y]),(Peach_youre_so_cool[9][y]),(Peach_youre_so_cool[10][y]))
    elif And_with_my_star_were_gonna_rule == 12:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]),(Peach_youre_so_cool[8][y]),(Peach_youre_so_cool[9][y]),(Peach_youre_so_cool[10][y]),(Peach_youre_so_cool[11][y]))
    elif And_with_my_star_were_gonna_rule == 13:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]),(Peach_youre_so_cool[8][y]),(Peach_youre_so_cool[9][y]),(Peach_youre_so_cool[10][y]),(Peach_youre_so_cool[11][y]),(Peach_youre_so_cool[12][y]))
    elif And_with_my_star_were_gonna_rule == 14:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]),(Peach_youre_so_cool[8][y]),(Peach_youre_so_cool[9][y]),(Peach_youre_so_cool[10][y]),(Peach_youre_so_cool[11][y]),(Peach_youre_so_cool[12][y]),(Peach_youre_so_cool[13][y]))
    elif And_with_my_star_were_gonna_rule == 15:
        for y in range(Princess_Peach):
            print((Peach_youre_so_cool[0][y]),(Peach_youre_so_cool[1][y]),(Peach_youre_so_cool[2][y]),(Peach_youre_so_cool[3][y]),(Peach_youre_so_cool[4][y]),(Peach_youre_so_cool[5][y]),(Peach_youre_so_cool[6][y]),(Peach_youre_so_cool[7][y]),(Peach_youre_so_cool[8][y]),(Peach_youre_so_cool[9][y]),(Peach_youre_so_cool[10][y]),(Peach_youre_so_cool[11][y]),(Peach_youre_so_cool[12][y]),(Peach_youre_so_cool[13][y]),(Peach_youre_so_cool[14][y]))
    else:
        return


if __name__ == "__main__":

    # Pide numero de filas y de columnas
    This_one_is_for_my_one_and_only_true_love = int(input("Ingresa el numero de columnas: "))
    Princess_Peach = int(input("Ingresa el numero de filas: "))

    # Crea una lista vacia
    Peach_youre_so_cool = []

    # Establece el numero de matrices
    And_with_my_star_were_gonna_rule = int(input("numero de matrices: "))

    # Pide la operacion a realizar
    Peach_understand = str(input("presione S para sumar la matriz y R para restar la matriz: "))

    # crea un bucle con el rango de And_with_my_star_were_gonna_rule
    for x in range(And_with_my_star_were_gonna_rule):

        # Crea una lista vacia
        Im_gonna_love_you_til_the_very_end = []

        # crea un bucle con el rango de Princess_Peach
        for y in range(Princess_Peach):

            # Crea una lista vacia
            Peaches_Peaches_Peaches_Peaches_Peaches = []

            # crea un bucle con el rango de This_one_is_for_my_one_and_only_true_love
            for z in range(This_one_is_for_my_one_and_only_true_love):

                # Pide un valor y lo vuelve flotante
                I_love_you_oh = float(input(f"Matriz [{x+1}] fila [{y+1}] columna [{z+1}]: "))

                # Añade el flotante a la lista Peaches_Peaches_Peaches_Peaches_Peaches
                Peaches_Peaches_Peaches_Peaches_Peaches.append(I_love_you_oh)

            # Añade la lista Peaches_Peaches_Peaches_Peaches_Peaches a la lista Im_gonna_love_you_til_the_very_end
            Im_gonna_love_you_til_the_very_end.append(Peaches_Peaches_Peaches_Peaches_Peaches)

        # Añade la lista Im_gonna_love_you_til_the_very_end a la lista Peach_youre_so_cool    
        Peach_youre_so_cool.append(Im_gonna_love_you_til_the_very_end)


    # Llama a la Santa inquisicion que es una funcion
    Santa_inquisicion(Princess_Peach,Peach_youre_so_cool,And_with_my_star_were_gonna_rule)

    # Busca si en Peach_understand hay una s
    if "s" in Peach_understand:

        # Crea una lista vacia
        Mario_Luigi_and_a_Donkey_Kong_too = []

        # Define un flotante con valor 0
        Princess_Peach_at_the_end_of_the_line = float(0)

        # Bucle for en el rango de Princess_Peach
        for x in range(Princess_Peach):

            # Crea una lista vacia
            A_thousand_troops_of_Koopas_couldnt_keep_me_from_you = []

            # Bucle for en el rango de This_one_is_for_my_one_and_only_true_love
            for y in range(This_one_is_for_my_one_and_only_true_love):

                # Crea una lista vacia
                Ill_make_you_mine_oh = []

                # Bucle for en el rango de And_with_my_star_were_gonna_rule
                for z in range(And_with_my_star_were_gonna_rule):

                    # Suma el valor de Peach_youre_so_cool con respecto a los bucles for (x,y,z)
                    Princess_Peach_at_the_end_of_the_line += (Peach_youre_so_cool[z][x][y])

                # Añade Princess_Peach_at_the_end_of_the_line a la lista Ill_make_you_mine_oh
                Ill_make_you_mine_oh.append(Princess_Peach_at_the_end_of_the_line)

                # Restablece el valor de Princess_Peach_at_the_end_of_the_line a cero
                Princess_Peach_at_the_end_of_the_line = 0

                # Añade Ill_make_you_mine_oh a la lista A_thousand_troops_of_Koopas_couldnt_keep_me_from_you   
                A_thousand_troops_of_Koopas_couldnt_keep_me_from_you.append(Ill_make_you_mine_oh)    

            # Añade A_thousand_troops_of_Koopas_couldnt_keep_me_from_you a la lista Mario_Luigi_and_a_Donkey_Kong_too
            Mario_Luigi_and_a_Donkey_Kong_too.append(A_thousand_troops_of_Koopas_couldnt_keep_me_from_you)
    else:

        # Crea una lista vacia
        Mario_Luigi_and_a_Donkey_Kong_too = []

        # Define un flotante con valor 0
        Princess_Peach_at_the_end_of_the_line = float(0)

        # Bucle for en el rango de Princess_Peach
        for x in range(Princess_Peach):

            # Crea una lista vacia
            A_thousand_troops_of_Koopas_couldnt_keep_me_from_you = []

            # Bucle for en el rango de This_one_is_for_my_one_and_only_true_love
            for y in range(This_one_is_for_my_one_and_only_true_love):

                # Crea una lista vacia
                Ill_make_you_mine_oh = []

                # Bucle for en el rango de And_with_my_star_were_gonna_rule
                for z in range(And_with_my_star_were_gonna_rule):

                    # Resta el valor de Peach_youre_so_cool con respecto a los bucles for (x,y,z)
                    Princess_Peach_at_the_end_of_the_line -= (Peach_youre_so_cool[z][x][y])

                # Añade el valor del numero de la primera matriz mulplicado por dos, debido que al entrar al bucle se resta
                Princess_Peach_at_the_end_of_the_line += 2*(Peach_youre_so_cool[0][x][y])

                # Añade Princess_Peach_at_the_end_of_the_line a la lista Ill_make_you_mine_oh
                Ill_make_you_mine_oh.append(Princess_Peach_at_the_end_of_the_line)

                # Restablece el valor de Princess_Peach_at_the_end_of_the_line a cero
                Princess_Peach_at_the_end_of_the_line = 0

                # Añade Ill_make_you_mine_oh a la lista A_thousand_troops_of_Koopas_couldnt_keep_me_from_you
                A_thousand_troops_of_Koopas_couldnt_keep_me_from_you.append(Ill_make_you_mine_oh)    

            # Añade A_thousand_troops_of_Koopas_couldnt_keep_me_from_you a la lista Mario_Luigi_and_a_Donkey_Kong_too
            Mario_Luigi_and_a_Donkey_Kong_too.append(A_thousand_troops_of_Koopas_couldnt_keep_me_from_you)

    # Imprime un doble espacio para diferenciar las matrices
    print(" ")
    print(" ")

    # Imprime la matriz Mario_Luigi_and_a_Donkey_Kong_too en filas
    for y in range(Princess_Peach):
        print((Mario_Luigi_and_a_Donkey_Kong_too[y]))
```
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
