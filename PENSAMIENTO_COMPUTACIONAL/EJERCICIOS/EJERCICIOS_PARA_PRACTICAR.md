### ESTOS EJERCICIOS REALIZALOS EN PSEINT PARA QUE PUEDAS PRACTICAR EL PENSAMIENTO COMPUTACIONAL.

Escribe un programa que permita saber si un año es bisiesto.(Para que un año sea bisiesto debe ser divisible por 4 y no debe ser divisible por 100, excepto que también sea divisible por 400.)
 ### Algoritmo  Año_Bisiesto
   * Escribir "ingresa el año"
   * Leer año
    
    A1<-año%4
    
    A2<-año%100
    
    A3<-año%400
    Si [(A1=0)&(A3=0)] | [(A1=0)&(A2<>0)]  Entonces
      
      Escribir año,' es año bisiesto'
      SiNo
      Escribir año,' no es año bisiesto'
   FinSi
 FinAlgoritmo  
     
 
 
 



Escribe un programa que permita al usuario ingresar 6 números enteros, que pueden ser positivos o negativos. Al finalizar, mostrar la sumatoria de los números negativos y el promedio de los positivos.

Escribe un programa que permita al usuario ingresar los montos de las compras de un cliente (se desconoce la cantidad de datos que cargará, la cual puede cambiar en cada ejecución), cortando el ingreso de datos cuando el usuario ingrese el monto 0. Si ingresa un monto negativo, no se debe procesar y se debe pedir que ingrese un nuevo monto.

### Algoritmo Monto_total
    total < - 0
    Repetir
    
    Escribir "ingresa monto"
    
    Leer monto
    
    si monto<0 Entonces 
    
    Escribir "ingresa otro monto:'
    
    Leer monto 
    
    SiNo 
    FinSi
    total< - total + monto
    hasta que monto =0
    
    Escribir "el monto total es :',total
    
 FinAlgoritmo    

Hallar Aumento al Sueldo de un empleado; si el sueldo es mayor a $500.000 su aumento será del 12%, pero si su sueldo es menor El aumento será del 15%. 
## Algoritmo Aumento_de_sueldo
 * Escribir "intruduzca su sueldo actual 
 * Leer sueldo 
   si sueldo > = 500 Entonces 
   nuevo<-sueldo + 0 . 12 * sueldo
   
   Escribir "su nuevo sueldo será de $ ', nuevo
 SiNO 
   nuevo < - sueldo + 0 .15 * sueldo
   Escribir"Su nuevo sueldo será de $', nuevo
   
 FinSi
FinAlgoritmo  
 
