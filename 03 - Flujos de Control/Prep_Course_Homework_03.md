## Flujos de Control

1) Crear una variable que contenga un elemento del conjunto de números enteros y luego imprimir por pantalla si es mayor o menor a cero
x = 10
if (x < 0):
   print ('La variable es menor a cero')
elif (x > 0):
   print ('La variable es mayor que cero)`
else:
    print('La variable es igual a cero')

2) Crear dos variables y un condicional que informe si son del mismo tipo de dato
a = 10
b = 'hola'
if (type(x)==type(b))
   print ('las variables son del mismo tipo)
else:
   print ('Las variables tienen un tipo de dato diferente) 
3) Para los valores enteros del 1 al 20, imprimir por pantalla si es par o impar
for i in range (1,21):
if i%2 == 0
    print('El numero, str(i), es par)
else:
    print('El numero, str(i), 'es impar')
4) En un ciclo for mostrar para los valores entre 0 y 5 el resultado de elevarlo a la potencia igual a 3
for i in range (0,6)
   x= i**3
   print (x)

5) Crear una variable que contenga un número entero y realizar un ciclo for la misma cantidad de ciclos
a= 4
for i in range(0,n):
     pass
print(i)

6) Utilizar un ciclo while para realizar el factorial de un número guardado en una variable, sólo si la variable contiene un número entero mayor a 0

numero = 4
factorial = 1
while(numero > 1):
   factorial = numero*factorial
   print (factorial)
   numero = numero -1

7) Crear un ciclo for dentro de un ciclo while
 n= 8
while ( n < 20 ):
    for i in range (0,n):
     x= n+1
     n += 1
     print(x)
8) Crear un ciclo while dentro de un ciclo for
n=20
for i in range( 0,n ):
  while(n < 15):
  n= +=1
  
9) Imprimir los números primos existentes entre 0 y 30
tope_rango = 30
n= 0
primo = true
while (n < tope_rango):
    for i in range ( 2, n):
        if(n % i == 0):
           primo = false
    if ( primo):
       print(n)
    else:
       primo = True
    n += 1

10) ¿Se puede mejorar el proceso del punto 9? Utilizar las sentencias break y/ó continue para tal fin
n= 0
primo = true
while (n < tope_rango):
    for i in range ( 2, n):
        if(n % i == 0):
           primo = false
           break
    if ( primo):
       print(n)
    else:
       primo = True
    n += 1
11) En los puntos 9 y 10, se diseño un código que encuentra números primos y además se lo optimizó. ¿Es posible saber en qué medida se optimizó?
ciclos_sin_break = 0
n = 0
primo = True
while (n < tope_rango):
    for div in range(2, n):
        ciclos_sin_break += 1
        if (n % div == 0):
            primo = False
    if (primo):
        print(n)
    else:
        primo = True
    n += 1
print('Cantidad de ciclos: ' + str(ciclos_sin_break))

12) Si la cantidad de números que se evalúa es mayor a treinta, esa optimización crece?

13) Aplicando continue, armar un ciclo while que solo imprima los valores divisibles por 12, dentro del rango de números de 100 a 300

14) Utilizar la función **input()** que permite hacer ingresos por teclado, para encontrar números primos y dar la opción al usario de buscar el siguiente

15) Crear un ciclo while que encuentre dentro del rango de 100 a 300 el primer número divisible por 3 y además múltiplo de 6
