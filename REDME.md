## Información del estudiante
Nombre: Thomas jesus guerrero Vizcaino
matricula: 2026-0953

## 1. Descripción del programa

Rentacar es una aplicación de escritorio desarrollada en C# utilizando Windows Forms. Su objetivo es registrar alquileres de vehículos y calcular automáticamente el monto total que debe pagar un cliente.

El programa permite introducir los datos del cliente, registrar diferentes vehículos, seleccionar el tipo de seguro, agregar GPS y elegir la modalidad de entrega.

También realiza los cálculos del subtotal, descuento, costo de entrega, ITBIS y total a pagar.

## 2. Datos de entrada

El programa solicita los siguientes datos:

- Nombre del cliente.
- Fecha de salida.
- Nombre del vehículo.
- Tarifa diaria del vehículo.
- Cantidad de días del alquiler (de 1 a 30).
- Tipo de seguro (Básico o Completo).
- Servicio de GPS.
- Tipo de entrega (En sucursal o a domicilio).

Las tarifas se introducen manualmente en el formulario.

## 3. Proceso

El programa realiza los siguientes procedimientos:

1. Recibe los datos del cliente y del vehículo.
2. Calcula la tarifa diaria agregando RD$300 si el seguro es completo.
3. Agrega RD$100 diarios si el cliente selecciona GPS.
4. Multiplica la tarifa diaria por la cantidad de días.
5. Acumula el subtotal de los vehículos registrados.
6. Aplica un descuento del 15 % sobre el subtotal.
7. Agrega RD$500 si el cliente selecciona entrega a domicilio.
8. Calcula la base imponible.
9. Calcula el ITBIS del 18 %.
10. Obtiene el total final que debe pagar el cliente.


## 4. Datos de salida

El programa muestra los siguientes resultados:

- Lista de vehículos registrados.
- Cantidad de días de cada alquiler.
- Tarifa diaria de cada vehículo.
- Total por vehículo.
- Subtotal acumulado.
- Descuento aplicado.
- Costo de entrega a domicilio.
- ITBIS del 18 %.
- Total final a pagar.
