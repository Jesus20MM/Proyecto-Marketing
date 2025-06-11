# Segmentación de Clientes para Campañas de Marketing

## Descripción
Este proyecto guiado tiene como objetivo segmentar a los clientes activos de una institución financiera con el fin de diseñar campañas de marketing más efectivas para la promoción de tarjetas de crédito. Utilizando Python como herramienta principal, se trabajó con un conjunto de datos que incluye diversas características. El proceso comenzó con una limpieza y exploración de datos para detectar valores atípicos, datos faltantes y variables irrelevantes. Posteriormente, se aplicaron técnicas de reducción de dimensionalidad y escalamiento para preparar los datos para la segmentación.

La segmentación se realizó mediante algoritmos de clustering, con especial énfasis en K-Means. Se evaluó el número óptimo de segmentos utilizando el método del codo analizando la inercia. Como resultado, se obtuvieron perfiles de clientes bien diferenciados, permitiendo diseñar campañas específicas para cada grupo con mayor probabilidad de éxito. Además, se generaron visualizaciones para facilitar la interpretación de los segmentos.

## Dataset
Se trabajó con un conjunto de datos proporcionado por una institución financiera. Contiene múltiples variables relacionadas con el comportamiento y características de los clientes activos. Las variables incluyen información demográfica, transaccional y de productos financieros.  

## Metodología

1. **Análisis exploratorio de datos (EDA)**  
   - Revisión inicial de variables.
   - Detección de valores atípicos y datos faltantes.  

2. **Limpieza y transformación de datos**  
   - Imputación de valores faltantes.
   - Eliminación de variables irrelevantes.
   - Codificación y normalización de datos.

3. **Reducción de dimensionalidad**  
   - Aplicación de PCA (Análisis de Componentes Principales) para representar la información en menos dimensiones sin perder significado relevante.  

4. **Clusterización (K-Means)**  
   - Segmentación de clientes mediante K-Means.
   - Evaluación del número óptimo de clusters con el método del codo.  

5. **Visualización de resultados**  
   - Representación gráfica de los clusters formados.  

## Resultados
- Se lograron identificar segmentos de clientes bien diferenciados.
- La visualización permitió interpretar los grupos para diseñar campañas de marketing dirigidas.
- Se seleccionó un número óptimo de clusters mediante el análisis de inercia.

## Lecciones aprendidas
- Visualizaciones más complejas para datos de alta dimensión.
- Aplicación y optimización de modelos de segmentación.
- Evaluación efectiva de modelos con el método del codo e inercia.
- Reducción de dimensión con PCA para visualización e interpretación.

## Tecnologías
Scikit-learn, Pandas, Numpy, Matplotlib, Seaborn  
(Clusterización, K-Means, PCA)

## Mejoras futuras
- Incluir autoencoders u otros modelos de reducción de dimensionalidad.
- Realizar un análisis de resultados más exhaustivo para comprender aún mejor el comportamiento de cada segmento.
