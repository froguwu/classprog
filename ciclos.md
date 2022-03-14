
#Ciclos

Los ciclos, son una manera de iterar sobre un grupo de operaciones de manera controlada. 

Existen **tres** tipos de ciclos: *for*, *while*, *do-while*.


### FOR

El ciclo for nos permite iterar sobre un rango de valores. Este ciclo es especialmente bueno, cuando se conoce la cantidad de veces que se busca repetir el bloque de operaciones. El ciclo for se expresa de la siguiente manera:
```java
    for( inicializacion; condicion; incremento){
        //Operaciones;
    }
```
O en diagrama de flujo, de la siguiente manera:
![for-diagrama](https://i.ibb.co/9rdn8Wk/image.png)

El flujo de un ciclo for es el siguiente:
1.  Se inicializa la variable que se utilizara para el ciclo. Es necesario inicializar la variable a un valor. Este paso solo se ejecuta 1 vez, al entrar al ciclo.
2.  Se verifica la condicion; Si resulta ser **true**, se continua con los pasos, si resulta ser **false** se termina el ciclo.
3.  Se realizan todas las operaciones dentro del ciclo.
4.  Se realiza la operacion de incremento. 
5.  Se regresa al paso 2. 

#####Variable de ciclo
La variable de ciclo, es la variable utilizada para la inicializacion, condicion e incremento del ciclo. Algo importante de notar es que esta variable no necesariamente debe ser creada en el ciclo, se puede utilizar una variable creada anteriormente. La ventaja de utilizar una variable **creada** en el ciclo, es que esta variable dejara de existir en el momento que el ciclo termine. 

Lo mas comun es nombrar las variables en ciclos como: i, j y k.

```java
int i = 0;
for(i = 0; i < 15; i++>){
    print(i);
}
print(a); //El valor de i sera 15

for(int j = 0; j < 15; j++>){
    print(j);
}
print(j); //Como j fue creada dentro del ciclo, esto causara un error ya que j ya no existe en el contexto del programa.
```

#####Ejemplo: 
Ciclo que cuente del 1 al 100.

**Java**
```java
for(int i = 1; i <= 100; i++>){
    print(i);
}
```
**Diagrama de flujo**
![for-ejemplo-1](https://i.ibb.co/Y2jtyhx/if.png)


### WHILE

El ciclo while nos permite ejecutar un bloque de operaciones mientras una condicion sea cierta. El ciclo while se expresa de la siguiente manera:
```java
    while(condicion){
        //Operaciones;
    }
```
O en diagrama de flujo, de la siguiente manera:
![while-diagrama](https://i.ibb.co/MpQjMDr/while.png)

El flujo de un ciclo while es el siguiente:
1.  Se verifica la condicion; Si resulta ser **true**, se continua con los pasos, si resulta ser **false** se termina el ciclo.
2.  Se realizan todas las operaciones dentro del ciclo.
3.  Se regresa al paso 1. 

#####Ejemplo: 
Ciclo, pedir numeros mientras que la suma de estos sea menor a 100.

**Java**
```java
int acum = 0;
int input;
while(acum < 100){
    input = readInput(); //Esto no existe, es para motivos de minimizar el codigo
    acum = acum + input;
}
```
**Diagrama de flujo**
![while-ejemplo-1](https://i.ibb.co/GFJ0PtG/image.png)


### DO-WHILE

El ciclo do-while es una variacion del ciclo while, donde la condicion se verifica al final de las operaciones. El ciclo do-while se expresa de la siguiente manera:
```java
    do{
        //Operaciones;
    }(condicion);
```
O en diagrama de flujo, de la siguiente manera:
![dowhile-diagrama](https://i.ibb.co/xqWg9GY/image.png)

El flujo de un ciclo while es el siguiente:
1.  Se realizan todas las operaciones dentro del ciclo.
2.  Se verifica la condicion; Si resulta ser **true**, se continua con los pasos, si resulta ser **false** se termina el ciclo.
3.  Se regresa al paso 1.