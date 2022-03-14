#Decisiones - IF
Esta estructura es la forma mas basica de control de flujo de un algoritmo. Esta condicion le dice al programa que ejecute ciertas operaciones **solo** si cierta condicion se cumple. 

Esta estructura tambien permite el caso **else**, donde si ademas del primer bloque de codigo, se cuenta con un segundo bloque que solo se ejectuta si la condicion inicial es falsa.

La expresion IF se expresa de la siguiente manera:
```java
    //if-then
    if(condicion){
        //Solo se ejecuta este bloque si la condicion es TRUE
    }

    //if-else
    if(condicion){
        //Solo se ejecuta este bloque si la condicion es TRUE
    }else{
        //Solo se ejecuta este bloque si la condicion es FALSE
    }
```

O en diagrama de flujo, de la siguiente manera:

**if-then**
![if-then-diagrama](https://i.ibb.co/FwRGf6R/image.png)
**if-else**
![if-else-diagrama](https://i.ibb.co/nm9Nd0j/image.png)


#####Ejemplo: 
Pedir un numero. Si el numero es mayor o igual a 60, imprimir *aprobado*, de lo contrario, imprimir *reprobado*.

**Java**
```java
    int calificacion = readInput(); //Esto no existe, es para motivos de minimizar el codigo
    if(calificacion >= 60){
        print("aprobado");
    }else{
        print("reprobado");
    }
```
**Diagrama de flujo**
![for-ejemplo-1](https://i.ibb.co/Y2jtyhx/if.png)
