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
    

## Listas 
        lista=[22,True,"lista",[1,2]]
        #print(lista)
        #print(lista[0])
        #print(lista[1])
        #print(lista[2])
        print(lista[3][0])
        
        lista1=[22,"Hola",3,5,3.14]
        lista2=["Mundo",0.1416]
        
        print(str(lista1[1])+" "+str(lista2[0]))
        print(float(lista1[2])+float(lista2[1]))
        lista3=[22,"Hola",3,5,3.14,[25,52,[1,2]],10]
        print(lista3[5][2][0])
        
        # Ejercicio : Declarar 3 listas que vn a contener
        #Primera: numeros del 1-15
        #Segunda: Días de la semana 
        #Tercera: Dos listas Primera: doce meses del año; Segunda:año 2001-2002
        #Imprimir la fecha de 1 de sep del 2001
        #imprimir 8/12/2002
        # imprimir 29 de agosto del 2023
        
        listaA=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]
        listaB=["lunes","martes","miercoles","jueves","viernes","sabado","domingo"]
        listaC=[["enero","febrero","marzo","abril","mayo","junio","julio","agosto","septiembre","octubre","noviembre","diciembre"],[2001,2002]]
        print(str(listaA[0])+ " de " +str(listaC[0][8])+ " " + str(listaC[1][0]))  #str(listaA[0]))+ " de " +
        print(str(listaA[7])+ " de " +str(listaC[0][11])+ " " + str(listaC[1][1]))
        print(int(listaA[13])+int(listaA[14]), " " + str(listaC[0][7])+ " " + str(listaC[1][1]) ) 



## Tuplas 
        tupla=(12,22,32)
        print(tupla[2])

## Ejercicio de Listas 
        #En una sola lista tener tres sub lista 
        #1-31
        #enero-dic
        # 2000
        # Imprimir cumpleaños de 22/11/1984
        #Imprimir 7/01/1943
        #12/11/1982
        lista=[[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31],["Enero","Febrero","Marzo","Abril","Mayo","Junio","Julio","Agosto","Septiembre","Octubre","Noviembre","Diciembre"],[2000]]
        #print(lista[0][21],"",lista[1][10],"",lista[2][0]-16)
        #print(lista[0][6],"",lista[1][0],"",lista[2][0]-57)
        #print(lista[0][11],"",lista[1][10],"",lista[2][0]-18)


## Otro ejercicio de Listas con ciclos
        lista1=[22,"Hola",3,5,3.14,[65,25],90]
        
        print (lista1)
        
        for x in lista1:
            print(x)
        
        for i in range(0,5):
        	print(lista1[i])

### Me dice si los meses son pares o impares 
           listaA=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]
        listaB=["lunes","martes","miercoles","jueves","viernes","sabado","domingo"]
        listaC=["enero","febrero","marzo","abril","mayo","junio","julio","agosto","septiembre","octubre","noviembre","diciembre"]
        
        ## Con un ciclo decir si es un dia par o impar o un mes par o impar
        x=1
        for i in listaC:
            if x%2==0:
                print(i,"Es par")
            else: 
                print(i, "Es impar")
            x+=1     

### Es importante recalcar que x actua como entero mientras que i me va a mostrar los nombres de cada mes    


## Ejercicios 30/08/23

### Serie de Fibonacci con Listas 
        #a=0
        #b=1
        #for i in range(11):
            #print(a,"*"*a)
            #a,b=b,a+b

##### Hacer lo anterior con Listas

        x=[0,1,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
        for f in range(0,15):
            if f>1:
                x[f]=x[f-1]+x[f-2]
            print(x[f],end="")
            for i in range(0,x[f]):
                print("*",end="")
            print("")


## Programa que vaya del 1-50 en una lista se guardan los numeros pares y en otra los impares y en la tercer lista que contenga el factorial de los primeros 10 numeros 

        pares=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
        impares=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0]
        x=0 # x y y son los indices de cada lista 
        y=0
        fact=1
        for i in range(0,50): # i es el valor 
            if(i%2==0):
        	    pares[x]=i
        	    x+=1
            else:
                impares[y]=i
                y+=1
            if i<=10:
                fact=1
                for f in range(1,i+1):
                    fact=fact*f
                    print("El factorial de: ",i," es: ",fact)
        
        print(pares)
        print(impares)

### Ejemplo de la conversion de listas a tuplas y el editar tales listas
        lista=[1,2,3,4,5]
        sublista=[6.1,6.2]
        print(lista)
        lista.append(6)
        print(lista)
        lista.append(sublista)
        print(lista)
        
        tupla=(1,2,3,4,5)
        print(tupla)
        tupla=list(tupla)
        tupla.append(6)
        tupla=tuple(tupla)
        print(tupla)

## Un programa que me pida un numero (numero de estudiantes), solicitar la calificacion de cada uno de los estudiantes, guardar en un lista y entregar el promedio de toda la clase 
### Una lista vacía se declara sin llenar los corchetes 
            calif=[]
            N=int(input("Digite el número de alumnos: "))
            for i in range(0,N):
                calif.append(int(input("Digita la calificación del alumno: ")))
            promedio=0
            for i in calif:
                promedio+=i
            print(promedio/N)
                    
### TAREA 

## Hipotenusas
    import math
    
    def cal_hip(a, b):
        c = math.sqrt(a ** 2 + b ** 2)
        return c
    a = int(input("Ingrese la longitud del primer cateto: "))
    b = int(input("Ingrese la longitud del segundo cateto: "))
    c = cal_hip(a, b)
    
    print("La longitud de la hipotenusa es: ", c)



## Formula gral 

    import math
    def calcular_raices(a, b, c):
        raiz = b**2 - 4*a*c
    
        if raiz > 0:
            x1 = (-b + math.sqrt(raiz)) / (2*a)
            x2 = (-b - math.sqrt(raiz)) / (2*a)
            return x1, x2
        elif raiz == 0:
            x1 = -b / (2*a)
            return x1
        else:
            # Raíces complejas (no reales)
            print("La raiz es negativa, por lo tanto no existe en los reales")
    
    # Solicitar los coeficientes al usuario
    a = float(input("Ingrese el coeficiente de 'a': "))
    b = float(input("Ingrese el coeficiente de 'b': "))
    c = float(input("Ingrese el coeficiente de 'c': "))
    
    # Calcular las raíces utilizando la función
    raices = calcular_raices(a, b, c)





 ## Ejercicios de clase 07/09/2023
### Archivos 

        #operaciones básicas 
    def operacion(x1,x2,op):
        if (op==1):
            return x1+x2
        if (op==2):
            return x1-x2
        if (op==3):
            return x1*x2
        if (op==4):
            return x1/x2
    ********************************
    En otro archivo 
    
    import calculadora
    print(calculadora.operacion(2,2,1))
        
## Otro ejercicio

        # Ingresar un número, si me dice que si es par y si no es impar 
        
        def par(x1):
            if (x1%2==0):
                f_si()
            else:
                f_no()
        
        def f_si():
            print("Es PAR")
        
        def f_no():
            print("No es PAR")
        
            *******************
            En otro Archivo 
        import pares
        numero=int(input("digite un numero : "))
        print(pares.par(numero))


## Otro Ejercicio 

        base={"ernesto@pilares":123,"maria@pilares":456,"luis@pilares":789}
        
        def sesion(usuario,contrasenia):
            if (base[str(usuario)]==contrasenia):
        	    f_si()
            else:
                f_no()
        
        def f_si():
            print("             **")
            print("            ** ")
            print("          **   ")
            print("**      **     ")
            print("  **  **       ")
            print("    **         ")
        
        def f_no():
            print("**         **")
            print("  **      ** ")
            print("   **    **  ")
            print("      **     ")
            print("      **     ")
            print("   **    **  ")
            print("  **      ** ")
            print("**         **")
          
        En otro archivo 
        
        import login
        usuario=str(input("Digite el usuario\n"))
        contrasenia=int(input("Digite la contraseña\n"))
        
        login.sesion(usuario,contrasenia)
            
## Ejercicios de la clase del 08/09/23

        #Calculadora dentro de la función hay resta, suma, muliplicacion y división 
        def cal(x1,x2,op):
            if(op==1):
                print(x1+x2) 
            if(op==2):
                print(x1-x2)
            if(op==3):
                print(x1*x2)
            if(op==4):
                print(x1/x2)
        
        ****************** En otro archivo ******************
        import nuevo
        nuevo.cal(2,2,1)

 ### Crear un programa que convierta °C a °F 
        def cov(c):
            f=(c*1.8)+32
            print(f)  
        ****************** En otro archivo ******************
        import FaC
        x=float(input("digita"))
        FaC.cov(x)

### Un programa con el uso de archivos que solo acepte numeros del 0 al 1000, al ingresar un numero me diga si es o no Fibonacci
        f=[0,1]
        def fibo(valor):
            for i in range (0,17):
                f.append(f[i]+f[i+1])
                if(int(valor)==f[i]):
                    return "Si"
            return "No"
         ****************** En otro archivo ******************
        import funcion
        esNum=True
        while(esNum):
            x=int(input("Digita un valor\n"))
            if(x>0 and x<1000):
                esNum=False
                print(funcion.fibo(x))
        
