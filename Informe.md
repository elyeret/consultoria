# Consultoria

## Análisis Temporal del NDVI (2016–2025)
Repositorio oficial del proyecto de consultoría con el profesor Jose Francisco Ruiz
Este repositorio contiene el desarrollo completo de un trabajo de consultoría cuyo objetivo es analizar la evolución del NDVI (Índice de Vegetación de Diferencia Normalizada) durante el periodo 2016–2025, utilizando imágenes satelitales procesadas y técnicas avanzadas de teledetección y análisis temporal.

Objetivo del proyecto

Evaluar los cambios en la cobertura vegetal a lo largo de nueve años, identificando:

- Tendencias de crecimiento o disminución de la vegetación
- Cambios interanuales significativos
- Valores extremos (zonas con deterioro o fortalecimiento)
- Patrones temporales basados en dos NDVI por cada año

## Contenido del repositorio

El repositorio incluye:

1. Scripts de análisis

Códigos en Python para:

- Cargar mapas NDVI por año

- Extraer valores extremos

- Construir series de tiempo

- Generar gráficos y consolidar dataframes

2. Datos

- Archivos NDVI procesados (formato raster)

- Dataframes consolidados por año

- Resultados de extracción de extremos

3. Visualizaciones

- Gráficos de series de tiempo

- Comparaciones interanuales

- Mapas de NDVI y mapas de cambio (si se incluyen)

4. Informe de consultoría

- Análisis técnico

- Hallazgos clave

- Recomendaciones ambientales

- Conclusiones del estudio

## Metodología general

El análisis se basa en:

- Lectura y organización de mapas NDVI (2016–2025)

- Extracción de valores extremos (por debajo de –0.2 y por encima de +0.2)

- Cálculo del promedio anual usando NDVI_1 y NDVI_2

- Construcción de serie de tiempo para entender tendencias

- Interpretación ambiental de los resultados

## Equipo de trabajo

Proyecto desarrollado por:

Mara Daniela Morales Gutiérrez

Carlos Alberto López


## Aplicaciones del estudio

Este análisis es útil para:

- Gestión ambiental y territorial

- Monitoreo de ecosistemas

- Evaluación de planes de conservación

- Identificación de áreas degradadas o en recuperación

- Toma de decisiones en agricultura, minería y ordenamiento territorial
