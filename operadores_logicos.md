---
layout: default
---

# Operadores Logicos

Los operadores logicos se utilizan para combinar dos valores **booleanos** y devolver un resultado verdadero o falso, de acuerdo a las entradas.

Existen 3 operadores logicos **AND**, **OR**, **NOT**.

### AND

**AND** es el operador logico mas estricto. Este operador solo regresa **TRUE** cuando ambas entradas son **TRUE**.
Si la entrada1 **AND** la entrada2 son **TRUE**, regresa **TRUE**.

|    Entrada 1     |    Entrada 2     |  Salida |
|:-----------------|:-----------------|:--------|
|       TRUE       |       TRUE       |   TRUE  |
|       TRUE       |      FALSE       |  FALSE  |
|      FALSE       |       TRUE       |  FALSE  |
|      FALSE       |      FALSE       |  FALSE  |

### OR

Este operador regresa **TRUE** cuando alguna de las dos entradas es **TRUE**, sin importar el valor del otro.
Si la entrada1 **OR** la entrada2 son **TRUE**, regresa **TRUE**.

|    Entrada 1     |    Entrada 2     |  Salida |
|:-----------------|:-----------------|:--------|
|       TRUE       |       TRUE       |   TRUE  |
|       TRUE       |      FALSE       |   TRUE  |
|      FALSE       |       TRUE       |   TRUE  |
|      FALSE       |      FALSE       |  FALSE  |

### NOT

Este operador solo recibe una entrada, y regresa el valor inverso a este. Si recibe un **TRUE**, regresa un **FALSE** y viceversa.

|    Entrada 1     |  Salida |
|:-----------------|:--------|
|       TRUE       |  FALSE  |
|      FALSE       |   TRUE  |

