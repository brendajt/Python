## Ejercicio de Pares 
    while(i<10):
        print(i)
        i=i+1
    print("Continua con el flujo del programa despues del while \n")
    i=0
    for x in range (0,10):
        i=i+2
        print(x," : ",i,"\n")
    print("Continua con el flujo del programa despues del while \n")


##  Ejercicio de Hola Mundo
    print("Hola Mundo")
    h="5"
    print(h)
    print(int(h)+1)
    x=input("Ingresa el valor: ")
    print(x)
    anio=2023
    z=input("Ingresa tu año de nacimiento:")
    print("Tu edad es:")
    print(anio-int(z))

##   #Preguntar si el numero es par, imprimir del 0 a ese numero 
## #Si es impar vamos a multiplicar ese numero por los anteriores a el 
    num=int(input("Digita un número: "))
    factorial=1
    if num %2==0:
        print("Tu número es par")
        for x in range (0,num+1):
            print(x)
    else: 
        print("Tu numero es impar")
        for x in range(1,num+1):
            factorial=factorial*x
        print(factorial) 
### Ejericicio de pares e impares
    numero = int
    z=input("Ingresa un número:")
    if int(z)%2 == 0:
        print("Tu número es par")
    else:
        print("Tu número es impar")
    print("El programa continua y ahora te imprime los números pares del 1 al 100")
    i=0
    for x in range (0,50):
        i=i+2
        print(i)
    print("El programa continua y ahora te imprime los números impares del 1 al 100")
    i=0
    while(i<50):
        
 ###       Ejercicio de Hipotenusa
     import math
    print("Este programa da como resultado la medida de uno de los angulos internos de un triangulo rectangulo conociendo los otros")
    a1=input("Digita el primer angulo: ")
    a2=input("Digita el segundo angulo: ")
    a3=180-int(a1)-int(a2)
    print("El resultado de tu tercer angulo es: ", a3)

## Ejercicio de Fibonacci
    x1=0
    x2=1
    x3=1
    for i in range(0,15):
    	x3=x1+x2
    	x1=x2
    	x2=x3
    	if x3%2 == 0:
    		print(" *",x3)
    	else:
    		print(" .",x3)

## Ejercicio de cuadrado figuras geometricas  
    for x in range(0,5): # Este código se refiere a la "altura" 
        print("")
        for x in range(0,10): # Esta linea se refiere a la "anchura"
            print("*",end="")
    
    print("\n")
    print("ahora un triangulo")
    
    for i in range(0,5):
        print("")
        for j in range(0,10):
            if i>j:
                print("*",end="")
    
    print("\n")
    print("ahora una piramide")
    a=25
    b=25
    for x in range(0,25): # Este código se refiere a la "altura" 
        for y in range(0,50): # Esta linea se refiere a la "anchura"
            if(y>=a) and (y<=b):
                print("*",end="")
            else:
               print(" ",end="") 
        a-=1
        b+=1
        print("")
    
    print("\n")
    print("ahora otra piramide")
    a=25
    b=25
    for x in range(0,25): # Este código se refiere a la "altura" 
        for y in range(0,50): # Esta linea se refiere a la "anchura"
            if(y>=a) and (y<=b):
                print("*",end="")
            else:
                if y==(a-1) or y==(b+1):
                    print(" ",end="")
                else:
                    print("*",end="")     
        a-=1
        b+=1
        print("")


## Ejercicio sobre la edad
    #Realizar un código cuya funcion sea decir que es menos de 0 a 18 años, decir que es mayor de edad de 18 a 100 y si es mayor de 65 decir que puede adquirir el inapam. Si el numero no esta en el rando de 0 a 100 decir que no es valida
    edad=input("Ingresa tu edad: ")
    if (int(edad)>=0) and (int(edad)<=100):
        if int(edad)<18:
            print("Es menor de edad")
        else:
            print("Es mayor de edad")
            if int(edad)>=65:
                print("Pasar por su tarjeta de INAPAM")
            else:
                print("Aun no cuentas con la edad requerida para INAPAM")
    else: 
        print("Intentalo de nuevo, edad invalida")            
    
