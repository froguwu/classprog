
## Operadores Aritmeticos
Los operadores aritmeticos realizan operaciones aritmeticas con operandos, estos son los mismos utilizados en matematicas. Uno de los simbolos que puede ser nuevo para ti, es el operador **%**, el cual regresa el residuo de una division.

|    Operador     |    Descripcion     |  
|:-----------------|:-----------------|
|       +       |       Operador de suma, tambien utilizado para concatenar texto       | 
|       -       |      Operador de resta       | 
|       *       |      Operador de multiplicacion       |  
|       /       |      Operador de division       |  
|       %       |      Operador de residuo       |  

```java
int a = 15; 
int b = 2; 
int c = 0;

c = a + b; // c = 15 + 2 = 17
c = a - b; // c = 15 - 2 = 13
c = a * b; // c = 15 * 2 = 30
c = a / b; // c = 15 / 2 = 7
c = a % b; // c = 15 % 2 = 1
```
Es importante notar que estos operadores **requieren** de dos operandos para funcionar. 

## Operador de Asignacion
Uno de los operadores mas comunes, es el simple operador de asignacion **=**. Este operador asigna el valor a su derecha, al operando a su izquierda.

```java
int a = 15; //El valor 15 se le asigna a la variable a
int b = a; //El valor de a (15), se le asigna a la variable b
int c = a + b; //El valor de el resultado de a + b (15 + 15), se le asigna a la variable C
```
Es importante notar que los operados a la derecha no son afectados por este operador. El valor a la izquierda, debe ser una **variable** y no puede contener una operacion de ese lado.

Existe una manera de combinar los operadores aritmeticos con el operador de asignacion para acortar las expresiones.

|    Operador    |    Ejemplo |  Equivalente|  
|:---------------|:-----------|-------------|
|       +=       |     a+=b   |  a = a + b  | 
|       -=       |     a-=b   |  a = a - b  | 
|       *=       |     a\*=b  |  a = a \* b  | 
|       /=       |     a/=b   |  a = a / b  | 
|       %=       |     a%=b   |  a = a % b  | 


## Operadores Unario
Estos operadores solo requieren de un operando, y realizan varias operaciones distintas

|    Operador     |    Descripcion     |  
|:-----------------|:-----------------|
|       +       |       Operador positivo, indica un valor numerico positivo (Los numeros son positivos sin necesidad de incluir este operador)      | 
|       -       |      Operador negativo, indica un valor numerico negativo. Es el equivalente a multiplicar por (-1)       | 
|       ++       |      Operador de incremento, aumenta el valor por 1       |  
|       --       |      Operador de decremento, decrementa el valor por 1       | 

La posicion del operador de incremento y decremento es importante. Si el operador aparece antes que la variable, el valor es incrementado y luego utilizado. Si el operador se encuentra despues de la operacion, el valor es utilizado, y despues incrementado.

```java
int a = 1;
            //Antes   Durante       Despues
print(+a);  //a = 1;  Salida =  1 ;  a = 1 
print(-a);  //a = 1;  Salida = -1 ;  a = 1
print(++a); //a = 1;  Salida =  2 ;  a = 2
print(a++); //a = 2;  Salida =  2 ;  a = 3
print(--a); //a = 3;  Salida =  2 ;  a = 2
print(a--); //a = 2;  Salida =  2 ;  a = 1
```

## Operadores Relacionales
Los operadores relaciones determinando si la relacion entre dos operandos. 

|    Operador    |    Descripcion     |  
|:---------------|:-----------------|
|       ==       |   Igual que      | 
|       !=       |   Diferente que    | 
|       >        |   Mayor que  | 
|       >=       |   Mayor o igual que    | 
|       <        |   Menor que      | 
|       <=       |   Menor o igual que    | 

Todos estos operadores se hacen en relacion del operando a la izquierda de acuerdo al operando a la derecha. 

Estos operadores regresan un valor **booleano** como respuesta, osea solo regresan **CIERTO** o **FALSO**.

**Nota: Recordar que se debe usar == para comparar dos valores, ya que solo un = es un operador de asignacion**

```java
int a = 1; 
int b = 2;
int c = 2;

a == b; // 1 == 2; FALSO
a != b; // 1 != 2; CIERTO
b  > a; // 2  > 1; CIERTO
a  > b; // 1  > 2; FALSO
b <= c; // 2 <= 2; CIERTO
b  < c; // 2  < 2; FALSO
```