# Challenge-alura-store_Paola-Manrique

A continuacion se presenta el relatorio para el presente proyecto:

## Relatorio de Análisis de Tiendas

1. Datos Generales

Título: Análisis de desempeño y facturación de tiendas
Autor: Cindy Paola Manrique Mahecha
Fecha: 31/12/2025

Objetivo: Evaluar el rendimiento de las tiendas mediante indicadores de facturación, ventas por categoría, calificación promedio de clientes, productos más y menos vendidos, y gasto de envío, con el fin de identificar oportunidades de mejora y decisiones estratégicas.

2. Introducción

Este relatorio resume el análisis realizado sobre los datos de las cuatro (4) tiendas.
El objetivo principal es identificar la tienda con menor rendimiento y proponer recomendaciones para optimizar las ventas y la eficiencia operativa.
Se analizaron datos de facturación, calificaciones de clientes, ventas por categoría, productos más y menos vendidos, y costos de envío.

3. Metodología

Fuentes de datos: Archivos CSV públicos de las tiendas (Tienda 1, Tienda 2, Tienda 3, Tienda 4).
Herramientas utilizadas: Python, Pandas, Matplotlib, Seaborn.
Procedimiento:
Importación y consolidación de datos (df_total)
Análisis exploratorio de facturación por tienda
Ventas por categoría de productos
Calificación promedio de clientes
Identificación de productos más y menos vendidos
Análisis de gasto de envío
Cálculo de rendimiento neto (Facturación - Costo de envío)

4. Resultados

4.1 Facturación por Tienda

Visualización: Gráfico de barras mostrando la facturación total de cada tienda.
Insight: La Tienda 1 presenta la mayor facturación, mientras que la Tienda 4 tiene la menor facturación.

4.2 Ventas por Categoría

Visualización: Barras mostrando ventas totales por categoría de producto.
Insight: Las categorías más vendidas concentran gran parte de los ingresos; las categorías menos vendidas podrían requerir promoción o revisión de inventario.

4.3 Calificación Promedio de Clientes

Visualización: Línea comparativa de calificación promedio por tienda.
Insight: Las calificaciones son relativamente similares, con ligera ventaja en la Tienda 3. Esto indica un nivel de satisfacción aceptable, pero no necesariamente correlaciona con la facturación.

4.4 Productos más y menos vendidos

Visualización: Gráficos de barras para los 5 productos más y menos vendidos.
Insight: Algunos productos se venden muy poco; estos datos pueden guiar decisiones de stock o promociones.

4.5 Gasto de Envío por Tienda

Visualización: Barras mostrando gasto total en envíos por tienda.
Insight: La Tienda 1 tiene el mayor gasto de envío, mientras que la Tienda 4 tiene el menor. Sin embargo, al comparar con la facturación, la Tienda 4 presenta un bajo rendimiento neto.

4.6 Rendimiento Neto y Recomendación Estratégica

Tienda	  Facturación     Total	Costo de Envío	Calificación	  Rendimiento Neto
Tienda_1	1,150,880,000	       61,377,900	         3.98	          1,089,502,100
Tienda_2	1,116,344,000	       59,485,100	         4.04	          1,056,858,900
Tienda_3	1,098,020,000	       58,516,600	         4.05	          1,039,503,400
Tienda_4	1,038,376,000	       55,317,400	         4.00	            983,058,600

Insight: La Tienda 4 presenta el menor rendimiento neto (Facturación - Costo de Envío), lo que la hace la candidata principal para una revisión estratégica o posible venta.

Recomendación:

Se sugiere evaluar la Tienda 4 para optimización de inventario, mejora en marketing o considerar su venta, ya que actualmente genera el menor beneficio neto en comparación con las otras tiendas.

5. Conclusión

El análisis permitió identificar claramente la tienda con menor rendimiento, entender la distribución de ventas por categoría, evaluar la satisfacción del cliente y los productos que requieren atención.
Los resultados ofrecen información valiosa para tomar decisiones estratégicas orientadas a maximizar ingresos y eficiencia operativa.

