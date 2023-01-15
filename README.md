print('Bienvenido a la calculadora')


print("""
    Selecciona la operacion a realizar:
    1) Sumar
    2) Restar
    3) Multiplicar
    4) Dividir 
    5) Raiz cuadrado 
    6) Exponente
  """)

opcion = int(input('Elige una opcion de la lista: '))

print('')
n1 = float(input('Introduce un numero: '))
n2 = float(input('Introduce otro numero: '))

if opcion==1:
    print('')
    print('La suma de ',n1,'+',n2,' es igual a:',n1 + n2)
elif opcion ==2: 
    print('')
    print('La Resta de ', n1, '-', n2, ' es igual a:', n1 - n2)
elif opcion ==3:
    print('')
    print('La Multiplicacion de ', n1, '*', n2, ' es igual a:', n1 * n2)
elif opcion ==4:
    print('')
    print('La Division de ', n1, '/', n2, ' es igual a:', n1 / n2)
elif opcion ==5:
    print('')
    print(f'La raiz cuadrado de {n1} es igual a {n1**0.5}')
elif opcion ==6:
    print('')
    print(f'{n1} Elevado a {n2} es igual a {n1**n2}')
