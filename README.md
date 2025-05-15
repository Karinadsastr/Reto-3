# Reto-3
Pseudocódigo y diagrama de flujos de numeros primos

PSEUDOCODIGO

[variables]

n : entero     // número hasta el cual se buscan primos

i : entero     // comienza desde 2

Inicio

    i = 2 
    
    Leer n

    Crear una lista "numeros" desde i hasta n
    // No hay números primos menores que 2

    Mientras i * i <= n hacer
        Si i no está tachado en la lista entonces
            Tachar todos los múltiplos de i mayores que i
        Fin Si
        i = i + 1
    Fin Mientras

    Imprimir los números no tachados

Fin

Explicacion:

Empieza desde 2, que es el primer número primo válido.
Crea una lista desde 2 hasta n, que es lo correcto.
Usa un bucle que va hasta √n, que es suficiente para tachar todos los compuestos.
Dentro del bucle, solo se tachan múltiplos de los números no tachados, es decir, los que son primos.
Finalmente, se imprimen los que no fueron tachados, que son los primos.

DIAGRAMA DE FLUJO 
![Inicio](https://github.com/user-attachments/assets/61f074fa-e776-409e-abf9-0bfe8ef09f2a)


