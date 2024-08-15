# 2-PREDICCION DE VENTAS-
  Predicción de Ventas
Una empresa ha determinado que su beneficio anual es típicamente el 23% de las ventas totales.
Diseña un programa que pida al usuario ingresar la cantidad proyectada de ventas totales, y luego
muestre el beneficio que se obtendrá de esa cantidad.
Pista: Usa el valor 0.23 para representar el 23%.


algoritmo 
1. Inicio
2. Solicitar al usuario que ingrese la cantidad proyectada de ventas totales.
3. Leer la cantidad proyectada de ventas totales y almacenarla en una variable ventas_totales.
4. Calcular el beneficio usando la fórmula: beneficio = ventas_totales * 0.23.
5. Mostrar el beneficio calculado.
6. Fin



pseudocodigo



program beneficio_total 
// un programa que sirva para hallar el beneficio total de una empresa

start

declarefloat_ventas_proyectadas
declare float total 
display " ingrese la cantidad de ventas proyectadas"
input ventas_proyectadas


settotal = ventas proyectadas * 0.23 
display " valor del beneficio total generado por la empresa " total 

END
 







3. . Cálculo de Terreno
Un acre de terreno es equivalente a 43,560 pies cuadrados. Diseña un programa que pida al usuario
ingresar la cantidad total de pies cuadrados en un terreno y calcule el número de acres en el terreno.
Pista: Divide la cantidad ingresada por 43,560 para obtener el número de acres.

Algoritmo

1. Inicio
2. Solicitar al usuario que ingrese la cantidad total de pies cuadrados en el terreno.
3. Leer la cantidad de pies cuadrados y almacenarla en una variable pies_cuadrados.
4. calcular el número de acres usando la fórmula: acres = pies_cuadrados / 43560.
5. Mostrar el número de acres calculado.
6. Fin

4. Compra Total
Un cliente en una tienda está comprando cinco artículos. Diseña un programa que pida el precio de 
cada artículo, y luego muestre el subtotal de la venta, la cantidad del impuesto de venta y el total. 
Asume que el impuesto de venta es del 6%.

Algoritmo:
INICIO
Definir impuesto como 0.06
Definir subtotal como 0
Para cada uno de los 5 artículos:
Solicitar el precio del artículo
Sumar el precio al subtotal
Calcular el impuestoVenta como subtotal * impuesto
Calcular el total como subtotal + impuestoVenta
Mostrar el subtotal, impuestoVenta, y el total
Fin

Pseudocodigo 
INICIO
impuesto <- 0.06
subtotal <- 0
PARA i DESDE 1 HASTA 5 HACER
 ESCRIBIR ¨Ingregar el precio del articulo¨, 1 
LEER precio 
 subtotal <- subtotal + precio 
FIN PARA
impuestoVenta <- subtotal * impuesto 
total <- subtotal + impuestoVenta
ESCRIBIR ¨subtotal:¨, subtotal
ESCRIBIR ¨Impuesyo de venta:¨, impuestoVenta
ESCRIBIR ¨Total: ¨, total
