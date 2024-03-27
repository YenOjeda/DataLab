# Análisis de las Reviews de AMAZON SALE

Datalab, empresa líder en análisis de datos, ofrece consultoría innovadora y flexible para el éxito empresarial. Su modelo único permite a los analistas elegir proyectos alineados con sus intereses, fomentando un ambiente dinámico y relaciones sólidas con los clientes. Esto demuestra su compromiso con el empoderamiento profesional y la entrega de soluciones personalizadas. Por otro lado, Amazon, una empresa multinacional de tecnología, domina el comercio electrónico con un proceso integral desde la compra y almacenamiento del inventario hasta el servicio al cliente, mostrando así su influencia global en el mercado.

# Datasets

Este conjunto de datos tiene los datos de más de 1.000 calificaciones y reseñas de productos disponibles para venda en Amazon.
- Conte con 2 datasets, una con la información de los productos (categoría, precio, decsuento, % de descuento, about del producto, etc) y otra con la informaciónde las reviews de los productos (quien envio la review, titulo de la review, contenido de la review, rating del producto, etc).

# Objetivos

Validar hipotesis a través de un score de sentimiento obtenido por la técnica NLP en Python conla libreria TEXTBLOD.

- Los productos con un mayor descuento, tienden a tener una mayor puntuación.
- Productos con un score positivo, tiende a tener una mayor puntuación.
- El precio del producto afecta el score positivo.

# Proceso del análisis

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

# Herramientas y Lenguajes

    •  Big Query (SQL).
    •  Google Colab (Python).
    •  Power BI.
    •  Google Slides.
    •  Loom.
