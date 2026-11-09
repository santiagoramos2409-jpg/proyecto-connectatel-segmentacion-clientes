# Segmentación de clientes – ConnectaTel

Análisis del comportamiento de uso de 4,000 clientes de una empresa de telecomunicaciones, realizado como proyecto del programa de Análisis de Datos de TripleTen.

## Objetivo
Identificar segmentos de clientes según su edad y nivel de uso, y proponer mejoras a la oferta de planes.

## Herramientas
Python, pandas, matplotlib y seaborn.

## Proceso
1. Limpieza de datos: valores centinela, fechas imposibles y valores nulos.
2. Agregación del consumo por usuario (mensajes, llamadas y minutos).
3. Análisis de distribuciones y outliers con histogramas, boxplots y el método IQR.
4. Segmentación de clientes por nivel de uso y por edad.

## Hallazgos principales
- La elección del plan no depende del nivel de uso ni de la edad: todos los segmentos tienen cerca de 65% Básico y 35% Premium.
- La mayoría de clientes consume muy por debajo de lo que incluyen los planes.
- Solo el 7% de los clientes es de alto uso, y la mayoría de ellos tiene plan Básico, lo que representa una oportunidad de venta del plan Premium.

## Autor
Santiago Ramos
