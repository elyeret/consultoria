# Informe

Análisis Temporal del NDVI (2016–2025) para Evaluación de la Dinámica de la Vegetación**

## 1. Introducción

El Índice de Vegetación de Diferencia Normalizada (NDVI) es una de las métricas más utilizadas en teledetección para evaluar el vigor, densidad y salud de la vegetación. Este índice, basado en relaciones espectrales del infrarrojo cercano y el rojo, permite caracterizar cambios temporales en áreas agrícolas, ecosistemas naturales y zonas intervenidas.

Este informe presenta un análisis de la variación del NDVI en el periodo 2016 a 2025, utilizando dos mapas NDVI por cada año (NDVI_1 y NDVI_2). El objetivo central es identificar tendencias, patrones de crecimiento o disminución, así como valores extremos que puedan señalar procesos ambientales relevantes como degradación, recuperación, cambios de cobertura o fluctuaciones estacionales.

## 2. Objetivo General

Evaluar la dinámica temporal del NDVI entre 2016 y 2025 mediante la extracción de valores extremos y la construcción de una serie de tiempo basada en dos mediciones por año.

## 3. Objetivos Específicos

- Organizar los mapas NDVI disponibles para cada año del periodo 2016–2025.

- Extraer valores extremos (valores positivos altos y negativos significativos).

- Calcular un valor promedio anual basado en los extremos de NDVI.

- Construir una serie de tiempo que permita identificar tendencias.

- Generar visualizaciones y tablas que apoyen la interpretación del comportamiento de la vegetación.


## 4. Metodología
4.1 Datos utilizados

Para cada año se cuenta con:

- NDVI_YYYY_1: Primer mapa NDVI del año

- NDVI_YYYY_2: Segundo mapa NDVI del año

Los datos provienen de imágenes satelitales de sentinel L2A previamente procesadas y normalizadas.

4.2 Procesamiento

Se aplicaron los siguientes pasos:

a) Extracción de valores extremos

Se definieron dos umbrales:

Azul (baja vegetación / áreas críticas): NDVI < -0.2

Rojo (alta productividad o expansión): NDVI > 0.2

Ambos NDVI por año se procesaron individualmente.

b) Consolidación anual

Los valores extremos de NDVI_1 y NDVI_2 se combinaron en un único conjunto por año.

Luego se calculó el:

<img width="406" height="104" alt="{E47CA05B-19B4-4790-8FF9-478332B94AA1}" src="https://github.com/user-attachments/assets/0f176782-f6e1-4f19-a0ef-e6ee463479a1" />


c) Serie de tiempo

Se generó un DataFrame con:

Año (2016–2025)

Promedio de valores extremos

Este fue representado mediante un gráfico de línea.



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
