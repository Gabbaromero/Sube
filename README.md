# Análisis del Uso de la SUBE (2020–2025)

Dashboard desarrollado en Power BI sobre el uso del transporte público 
en Argentina durante y después de la pandemia.

## Objetivo
Analizar la recuperación del uso de colectivo, subte y tren entre 2020 y 2025, 
identificando tendencias, picos de demanda y distribución geográfica.

## Dataset
Datos públicos de transacciones SUBE. Se trabajó con múltiples archivos 
por año que fueron unificados en un solo modelo.

## Proceso de limpieza
- Eliminación de valores nulos
- Exclusión de registros de lancha por no ser relevantes al análisis
- Unificación de datasets de distintos años
- Creación de tabla de fechas para análisis temporal

## Herramientas
Power BI Desktop · DAX · Power Query · ArcGIS Maps

## Próximas mejoras
- Script de Python para automatizar la unificación de archivos
- Consultas SQL sobre el dataset consolidado
- Incorporación de datos de clima para análisis cruzado
