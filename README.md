#  EJERCICIO 01
Ejercicio 01

## Etapa 01. Descripcion del problema
Se requiere un programa en Java para convertir una cantidad de dinero en otros tipos de monedas (al menos a cinco tipos de monedas distintas). 

## Etapa 02. Definicion de la Solucion 

~~~
-Entrada
Float Cantidad 
StringMoneda1,StringMoneda2,StringMoneda3,StringMoneda4,StringMoneda5
Double Conversion



-Proces
Solicitar moneda a convertir 
Solicitar cantidad a convertir
Solicitar moneda para procesar conversion

Si el monto es mayor o igual que cero entonces se convertira a la moneda deseada
Si el monto es menor que cero entonces se cancela la operación

Salida


+-----------+----------------+----------------+---------------+
|CANTIDAD    | MONEDA ORIGEN|  CANTIDAD CONVERTIDA | MONEDA DESTINO |
+-----------+----------------+---------------+-------------+
| 15        |     DLSS       |        13.93   | EUR          +
+-----------+-----------------+--------------+--------------+
|15   |  DLS  |  15.04  | Balboa   |
+---------+------------------+----------------+-------------+
|    15   | DLS    |  53.02   |  Kina |
+--------------+----------------+------------------+---------------+
| 15    | DLS     |  295575.00 |  Leone |
+--------------+----------------+-----------------+--------------+
| 15   | DLS   |   266.25 |   Loti |
+------------+------------------+------------------+--------------+

~~~

## Etapa 03. Diseño de la solucion


[](Diagrama de Clases.png)

