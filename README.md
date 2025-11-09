# INFORME FINAL — Análisis de las 4 tiendas de Alura Store

# Introducción
El objetivo de este análisis es ayudar al Sr. Juan a decidir cuál de las cuatro tiendas de su cadena Alura Store es la mejor candidata para vender, de modo que pueda liberar capital y financiar un nuevo emprendimiento. Para tomar una decisión fundamentada se analizaron las siguientes métricas: **ingresos totales**, **categorías más y menos vendidas**, **calificaciones promedio de clientes**, **productos más y menos vendidos** y **coste de envío promedio** por tienda.  

Las conclusiones se basan en los datos combinados de las cuatro tiendas y en las visualizaciones generadas (gráficas de barras de ingresos, gráfico circular de categorías y gráfico de dispersión precio vs calificación).



# Resumen ejecutivo (valores calculados)

Ingreso total por tienda (ordenado de mayor a menor):

| Tienda   | Ingreso total (moneda)      |
|----------|-----------------------------:|
| tienda_1 | 1.150.880.000                |
| tienda_2 | 1.116.344.000                |
| tienda_3 | 1.098.020.000                |
| tienda_4 | 1.038.376.000                |

Coste de envío promedio por tienda:

| Tienda   | Coste de envío promedio |
|----------|------------------------:|
| tienda_1 | 26.018,61              |
| tienda_2 | 25.216,24              |
| tienda_3 | 24.805,68              |
| tienda_4 | 23.459,46              |

Calificación promedio (clientes) por tienda:

| Tienda   | Calificación promedio |
|----------|----------------------:|
| tienda_3 | 4,0483               |
| tienda_2 | 4,0373               |
| tienda_4 | 3,9958               |
| tienda_1 | 3,9767               |



#Desarrollo — hallazgos detallados

# 1) Ingresos totales
- La tienda_1 tiene el mayor ingreso total, seguida por **tienda_2**, tienda_3 y finalmente tienda_4.  
- Observación: la tienda_4 presenta el ingreso total más bajo (≈ 1.038.376.000), lo que la coloca en la posición de menor desempeño desde la perspectiva estricta de facturación.

# 2) Categorías más vendidas (top por tienda)
(En el notebook se imprimieron los top 3 de cada tienda; aquí se resumen los patrones)
- Cada tienda muestra concentraciones en ciertas categorías — hay categorías que se repiten entre tiendas (categorías fuertes a nivel global).  
- Acción sugerida: centrar promociones en las categorías top de cada tienda, y replantear stock o promociones para las categorías con baja demanda.

> Nota: en la celda del notebook se listan las 3 categorías más vendidas por cada tienda para revisión detallada.

# 3) Calificaciones de clientes
- Las calificaciones promedio se mueven entre ~3.98 y ~4.05.  
- tienda_3 tiene la calificación promedio más alta (~4.05), y tienda_1 la más baja (~3.98).  
- Aunque las diferencias no son muy grandes, una calificación más baja puede indicar problemas de satisfacción que conviene investigar (tiempos de envío, atención, producto).

#4) Productos más y menos vendidos
- Se identificaron los top 5 productos con mayor número de ventas y los últimos 5 con menor venta a nivel global (lista impresa en el notebook).
- **Acción sugerida:** promover los top 5 y evaluar si conviene descontinuar o promocionar los últimos 5.

#5) Coste de envío promedio
- Las diferencias en coste de envío promedio entre tiendas existen (tienda_1 es la más alta).  
- Un coste de envío elevado puede afectar margen o satisfacción; conviene revisar acuerdos con logística.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Análisis combinado y justificación de la recomendación

Para elegir una tienda candidata a vender se evaluaron **dos señales principales**:
1. Ingreso total (indicador directo de desempeño económico).  
2. Calificación promedio (indicador indirecto de satisfacción y reputación).

# Resultado objetivo: la tienda_4 es la que presenta el ingreso total más bajo entre las cuatro tiendas.  
- Si bien su calificación promedio (≈ 3,9958) no es la más baja —esa corresponde a tienda_1— la diferencia en calificaciones es pequeña entre tiendas.  
- Dado que la decisión de vender busca liberar capital de la tienda que menos aporta en términos de facturación, tienda_4 es la candidata más clara por su menor ingreso total.

# Razones específicas para recomendar vender `tienda_4`:
- Ingreso total más bajo → menor aporte a la facturación global de la cadena.  
- Coste de envío promedio más bajo, lo que sugiere que su bajo ingreso no se compensa por menores gastos de envío; es decir, la tienda genera menos ventas en términos absolutos.  
- Calificación cercana al resto → no es la peor valorada (por lo que no se trata de un caso de reputación catastrófica que se pueda arreglar fácilmente con mejoras simples), lo que facilita la venta sin crear una gran percepción negativa.

> Precaución: esta recomendación se basa únicamente en los datos de ventas, precios y calificaciones disponibles. Antes de concretar la venta, es imprescindible revisar información adicional: contratos de arrendamiento, costos fijos (personal, mantenimiento), inventario remanente, márgenes reales (costos de producto), y potencial de recuperación (posible reestructuración y mejora operativa).

-------------------------------------------------------------------------------------------------------------------------------------------------------------

# Recomendaciones prácticas (pasos siguientes)
1. Auditoría financiera de `tienda_4`: revisar alquiler, gastos fijos, contratos y márgenes por producto.  
2. Revisión de inventario: decidir qué hacer con el stock actual (traspaso, liquidación o migración a otra tienda/almacén).  
3. Considerar ofertas o subasta: para acelerar la venta si se necesita capital rápido.  
4. Acciones antes de vender (si se busca alternativa a la venta)**: pruebas piloto de promociones, mejora de marketing local o ajustes en catálogo.  
5. Validar decisiones con métricas adicionales: comparar coste fijo mensual vs ingreso mensual, y proyectar impacto en caja tras la venta.

---------------------------------------------------------------------------------------------------------------------------------------------------------------

# Conclusión
Con base en los ingresos totales, el análisis de ventas por categoría, las calificaciones promedio, los productos top/bottom y el coste de envío promedio, "se recomienda considerar la venta de `tienda_4`". La decisión se fundamenta principalmente en que `tienda_4` aporta el menor ingreso a la cadena y no presenta una calificación anormalmente baja que justifique una intervención costosa para recuperar clientes.  

No obstante, antes de ejecutar la venta se aconseja llevar a cabo las auditorías y validaciones adicionales señaladas para confirmar que la venta es la mejor opción financiera y operativa para el Sr. Juan.

