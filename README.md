# Análisis de clientes de ConnectaTel 📱

## Objetivo
Analizar el uso de llamadas y mensajes de los clientes de ConnectaTel (México y Colombia) para identificar patrones de uso, detectar comportamientos atípicos y segmentar clientes por edad y nivel de uso.

## Datos
- `plans.csv`: planes y sus características.
- `users_latam.csv`: información de los clientes.
- `usage.csv`: detalle de llamadas y mensajes.

## Proceso
1. Carga y exploración de los datos.
2. Detección de problemas de calidad: nulos, sentinels y fechas imposibles.
3. Limpieza de datos.
4. Resumen estadístico por usuario.
5. Visualización con histogramas y boxplots, y detección de outliers con IQR.
6. Segmentación de clientes por edad y nivel de uso.
7. Conclusiones y recomendaciones de negocio.

## Principales hallazgos
- El 74% de los usuarios tiene uso medio; solo el 7% tiene alto uso.
- Los adultos de 30-59 años son el segmento más grande (50%).
- Los usuarios Premium no consumen notablemente más que los Básico.

## Herramientas
Python, pandas, numpy, matplotlib, seaborn, Jupyter Notebook.

## Autora
Carolina Rodriguez— Analista de Datos en formación (TripleTen).
