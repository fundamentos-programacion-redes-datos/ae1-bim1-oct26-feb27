# ae1-bim1-oct26-feb27
# Problemática

Una librería desea optimizar su sistema de facturación y análisis de ventas de libros. Para ello, se requiere desarrollar un programa que cumpla con los siguientes requisitos:

## Entrada de datos

- Ingresar el nombre y apellido del cliente.
- Ingresar la cantidad de libros que desea comprar el cliente.
- Cada libro tiene un mismo precio unitario, que también debe ser ingresado por el usuario (por ejemplo: novela, libro escolar, texto universitario, libro de cocina, etc.).

## Cálculo de descuentos

La librería aplica descuentos según la cantidad de libros comprados en una misma compra:

- Si se compra **1 libro**, se aplica un **15%** de descuento.
- Si se compran **2 o 3 libros**, se aplica un **20%** de descuento.
- Si se compran **4 o 5 libros**, se aplica un **25%** de descuento.
- Si se compran **6 o más libros**, se aplica un **35%** de descuento.

## Cálculo de totales

Para cada compra registrada se debe:

- Calcular el **subtotal** antes del descuento:
  
  `Subtotal = Cantidad de libros × Precio unitario`

- Calcular el monto del descuento aplicado.
- Calcular el total a pagar después de aplicar el descuento.

## Registro de múltiples clientes

El sistema debe permitir registrar la compra de libros de varios clientes utilizando un ciclo `while`.

Antes de iniciar el ciclo, el programa debe preguntar cuántas ventas se van a registrar (número de clientes).

Para cada cliente se debe realizar todo el proceso:

1. Ingreso de datos.
2. Cálculo del subtotal.
3. Cálculo del descuento.
4. Cálculo del total a pagar.

## Almacenamiento de datos

Se deben utilizar **arreglos unidimensionales paralelos** para almacenar la información de cada venta:

- Un arreglo para registrar el nombre de cada cliente.
- Un arreglo para registrar el apellido de cada cliente.
- Un arreglo para registrar la cantidad de libros comprados.
- Un arreglo para registrar el precio unitario del libro.
- Un arreglo para registrar el total a pagar de cada cliente.

Las posiciones de los arreglos se corresponden entre sí:

- La posición **0** representa la primera venta.
- La posición **1** representa la segunda venta.
- La posición **2** representa la tercera venta.
- Y así sucesivamente.

## Reporte final

Al finalizar el registro de todas las ventas, el programa debe:

1. Mostrar la información detallada de cada compra registrada:
   - Nombre.
   - Apellido.
   - Cantidad de libros.
   - Precio unitario.
   - Total a pagar.

2. Calcular y mostrar el **promedio de ventas**, considerando el total pagado por todos los clientes.

3. Determinar y mostrar:

## Importante
* Usar los conceptos estudiados hasta el momento en la asignatura
   - La venta de **mayor monto**.
   - La venta de **menor monto**.
