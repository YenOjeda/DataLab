# PROYECTO DATALAB AMAZON SALE

Datalab, una empresa especializada en análisis de datos, se destaca por su enfoque innovador en la toma de decisiones informada para el éxito empresarial. Como socio confiable para diversas empresas, su modelo de consultoría único permite a los analistas de datos elegir proyectos alineados con sus intereses, fomentando un ambiente dinámico y creativo. Esta flexibilidad no solo empodera a los profesionales, sino que también fortalece las relaciones con los clientes, proporcionando soluciones personalizadas y enriquecedoras. Invitan a los profesionales a trabajar en proyectos que reflejen sus intereses y habilidades, demostrando así su potencial en el campo del análisis de datos. 
Amazon es una empresa de tecnología estadounidense con operación multinacional, cuyos intereses comerciales incluyen el comercio electrónico, para el que compran y almacenan el inventario, y se encargan de todo el proceso, desde fijar los precios hasta el envío, el servicio al cliente y las devoluciones.

# Datasets

Este conjunto de datos tiene los datos de más de 1.000 calificaciones y reseñas de productos disponibles para venda en Amazon.
- Conte con 2 datasets, una con la información de los productos (categoría, precio, decsuento, % de descuento, about del producto, etc) y otra con la informaciónde las reviews de los productos (quien envio la review, titulo de la review, contenido de la review, rating del producto, etc).

# Objetivos

Validar hipotesis a través de un score de sentimiento obtenido por la técnica NLP en Python conla libreria TEXTBLOD.

- Los productos con un mayor descuento, tienden a tener una mayor puntuación.
- Productos con un score positivo, tiende a tener una mayor puntuación.
- El precio del producto afecta el score positivo.

# Proceso

- ETL: nulos, duplicados, datos fuera de alcance, cambio de tipo de dato,subcategorización de productos (BigQuery, SQL).
- Score de sentimiento: positivo, neutro, negativo. (Python)
- Análisis de cohorte (segmentación(precio, descuento, rating, score)). (Python).
- Prueba de significancia: Test de Shapiro para validar hipótesis.
- Comprobación a través de Test de Pearson o Correlación de Pearson.

# Insights

- Los productos con un MAYOR DESCUENTO, tienen un MEJOR RATING.
- Los productos con un SCORE POSITIVO, tienen un MAYOR RATING.
- El PRECIO del producto NO determina el SCORE DE SENTIMIENTO.
- Hay un mayor número de riviews positivas.
- La subcategoria más vendida es Computadores y Accesorios.
- El promedio de rating = 4/5.
- El producto más vendido es: Cable HDMI

# HERRAMIENTAS UTILIZADAS

    •  Big Query (SQL).
    •  Google Colab (Python).
    •  Power BI.
    •  Google Slides.
    •  Loom.
