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

## Resultados

<img width="236" height="211" alt="{E0BD4885-1C8B-47FF-80F9-8A0769C40664}" src="https://github.com/user-attachments/assets/1146f6d4-f6dc-4f16-be0f-9a3ea3a9e49a" />

<img width="944" height="498" alt="{AB0CD4E7-EA4F-49BB-9627-647BADB7B35E}" src="https://github.com/user-attachments/assets/28215d17-4627-4563-8a8f-29b4d2f036fc" />


El análisis del NDVI promedio anual revela un comportamiento dinámico de la cobertura vegetal entre 2016 y 2025, con fluctuaciones que reflejan variaciones ambientales, climáticas y posiblemente antrópicas.

## 1. Periodo 2016–2021: Tendencia ligeramente descendente

- Entre 2016 y 2021 se observa una disminución leve del NDVI promedio:

En 2016 el NDVI inicia en 0.63, indicando buena cobertura vegetal.

- El valor disminuye hasta 0.54 en 2018, convirtiéndose en el año con menor vigor vegetal en todo el periodo.

- En 2019 y 2020 hay una recuperación moderada.

- En 2021 vuelve a caer a 0.57, manteniéndose por debajo de los niveles iniciales.

Esto sugiere un ciclo de estrés vegetal, posiblemente relacionado con variaciones climáticas (lluvias, sequías) o cambios en uso del suelo.


## 2. Periodo 2022–2025: Recuperación significativa

A partir de 2022 ocurre un cambio importante:

- 2022 muestra un aumento notable con 0.697, el valor más alto hasta ese momento.

- 2023 presenta el NDVI máximo del periodo (0.721), indicando excelente productividad vegetal.

- En 2024 existe una ligera reducción (0.667), aunque manteniéndose en niveles altos.

- 2025 recupera de nuevo un valor elevado (0.709).

Este periodo evidencia una recuperación fuerte y sostenida en la cobertura vegetal, probablemente asociada a mejores condiciones ambientales o procesos de regeneración.


Tambien se hizo un estudio con respecto a las diferencias y logramos observar que:

<img width="233" height="222" alt="{DD70AF6E-F28D-4A0C-B905-D933B3F44E32}" src="https://github.com/user-attachments/assets/72aeed31-1321-4437-8db1-fcd94645a018" />

<img width="912" height="483" alt="{B5FF14CD-766A-4CDE-A00E-20507FEA1414}" src="https://github.com/user-attachments/assets/d2db57fd-ecdb-4ba9-9060-37b6dde24551" />


## 1. Años con valores positivos (2016, 2017, 2020, 2022)

- Estos años presentan incrementos, indicando que predominan los extremos positivos.

- El año 2016 y 2022 destacan con los valores más altos, sugiriendo condiciones ambientales más favorables o eventos que llevaron a aumentos en la variable analizada.

## 2. Años con valores negativos (2018, 2019, 2021, 2023, 2024, 2025)

- Representan períodos donde los extremos son negativos, indicando descensos en la variable.

- 2021 es el año con el mayor descenso, lo que sugiere un evento crítico o una condición ambiental significativamente diferente.

## 3. Tendencia general

- Hay una variación marcada entre años, con alternancia entre incrementos y descensos.

- Se observa un comportamiento más negativo a partir de 2018, lo que podría sugerir:

una tendencia a la degradación, mayor presencia de eventos extremos negativos o una posible alteración sostenida del ecosistema/variable.

## 4.Comparación 2024 vs 2025

- 2024 y 2023 comparten el mismo valor, lo cual puede indicar estabilidad o repetición del patrón.

- En 2025 hay un aumento leve (menos negativo), pero no recupera valores positivos.

Esto se debe a que posiblemente no haya muchos cambios durante los dos meses del año y cuando son muy estremos es por que si los hubo.





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
