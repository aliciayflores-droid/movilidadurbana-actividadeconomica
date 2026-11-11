# Título del Proyecto: 
*Evaluación de Movilidad Urbana y Productividad Económica*
## Contexto del Problema:
*Evaluar cómo la movilidad urbana se relaciona con la productividad económica en las principales ciudades latinoamericanas, para identificar en qué ciudades conviene invertir en infraestructura de transporte.*
## Herramientas Utilizadas: 
*Pandas, Numpy, Matplotlib, Seaborn.
## Metodología y Proceso:
*Se realizó limpieza de datos y cambio de data type para poder realizar el análisis, se cambió el nombre de las columnas para una mejor comprensión del data set, igualmente se corrigieron formatos de números y fechas, cambio de comas por puntos para evitar errores dentro del análisis y al unir ambos data sets.
Mediante la agregación por ciudad-año, se resumieron los registros calculando el promedio de los retrasos por ciudad para el año 2024 una vez teniendo éstos datos se unieron con el data set que incluía datos de PIB per cápita con la información para cada país con un registro de tráfico durante el 2024.
Se realizaron gráficos de validación, bloxpot para la distribución del tráfico, histograma para conocer la distribución del PIB durante ése año y finalmente la gráfica dónde analizamos el PIB per cápta y la cantidad de tráfico para cada ciudad con datos disponibles para el 2024.*
 # Principales Hallazgos:
 *Se encontraron los siguientes patrones entre los índices de tráfico y el PIB per cápita: Alta congestión + alto PIB: México City: ~21,000 PIB + ~3,000 min de retraso , São Paulo: ~15,000 PIB + ~2,000 min de retraso Alto PIB+ baja congestión: Montevideo: ~26,000 PIB per cápita + solo ~200 min de retraso Buenos Aires: ~18,000 PIB + ~500 min de retraso , Brasilia: ~16,500 PIB + ~1,500 min de retraso Bajo PIB+ baja congestión: Salvador: ~9,000 PIB + ~200 min de retraso Fortaleza: ~9,000 PIB + ~500 min de retraso Alta congestion+ bajo PIB Por lo que no existe una relación clara entre el PIB per cápita y el tráfico de las ciudades analizadas.
Sería importante revisar aquellas ciudades con un PIB per cápita bajo y un tráfico alto, como lo es el caso de Santiago con un PIB cercano a ~2000 y ~500 min de retraso, por lo que valdría la pena analizar éste caso particular, así como ampliar el estudio a otros años. *
