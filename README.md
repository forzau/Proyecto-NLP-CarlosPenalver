# Análisis NLP de reseñas de Glassdoor

Proyecto final del Máster de Data Science e IA. Analiza **NTT DATA como empleador** y la compara con Capgemini, Cognizant, Atos y DXC Technology para identificar fortalezas, áreas de mejora y posibles motivos de salida.

## Contenido

- Análisis de rating, recomendación y empleados actuales frente a antiguos.
- Sentimiento con DistilBERT y extracción de temas con BERTopic.
- Categorías de negocio, comparación con peers y matriz de priorización.
- Evolución temporal y análisis según recomendación.
- Dos propuestas de intervención para RRHH.

Las tareas NLP utilizan una muestra reproducible de **2.000 reseñas por empresa**.

## Ejecución

1. Instalar las dependencias de `requirements.txt` y disponer de PyTorch. CUDA es opcional.
2. Colocar `glassdoor_reviews_hr.parquet` y `lista_con_sector.xlsx` en la carpeta del proyecto.
3. Abrir `NTT_DATA_Glassdoor.ipynb` y ejecutar las celdas de arriba abajo desde esa carpeta.

## Alcance

Análisis descriptivo de reseñas de julio de 2018 a julio de 2023. La autoselección de usuarios y la incertidumbre de las categorías limitan la generalización; los resultados no demuestran causalidad.
