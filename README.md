# AluraStoreLatam
AluraStoreLatam
🛍️ Análisis de Datos - Alura Store
📋 Objetivo del Proyecto
El Sr. Juan, dueño de la cadena Alura Store, busca vender una de sus tiendas para financiar un nuevo proyecto. Este análisis tiene como propósito identificar, con base en los datos, cuál de las cuatro tiendas tiene el rendimiento más bajo y recomendar su venta.

📊 Descripción del Conjunto de Datos
El dataset contiene información detallada sobre:

🛒 Productos adquiridos

🗂️ Categoría de los productos

💰 Precios y costos de envío

📅 Fecha y ubicación de las compras

⭐ Calificación del cliente

💳 Tipo de pago y número de cuotas

📍 Coordenadas geográficas de las transacciones

🔍 Análisis Realizado
1️⃣ Facturación
🏆 La Tienda 1 lidera en ingresos con el 26.13% del total y un ingreso promedio por producto de $487,867.9.

📉 La Tienda 4 tiene la menor participación con 23.58% y un promedio de $440,362.8 por producto.

⚖️ La diferencia entre ambas tiendas es de solo 2.55%, lo que indica un rendimiento financiero similar.

2️⃣ Ventas por Categoría
💻 Las categorías de Electrónicos y Electrodomésticos representan el 68.92% de los ingresos, siendo las más rentables.

🪑 Muebles tienen alta demanda con ingresos medios.

🧸 Juguetes y 🏀 Deportes presentan altos volúmenes de venta, pero bajos ingresos por producto.

🎸 Instrumentos musicales muestran bajas ventas pero precios altos, siendo una categoría con potencial.

3️⃣ Calificaciones
⭐ Las calificaciones promedio varían entre 3.7 y 4.2.

🧸 Juguetes y 🪑 Muebles suelen tener mejores calificaciones.

🏠 Artículos para el hogar y 🏀 Deportes muestran variabilidad entre tiendas.

4️⃣ Costos de Envío
Se estimaron los costos de envío promedio por tienda, detectando posibles oportunidades para mejorar la logística.

5️⃣ Utilidades
💵 Las tiendas muestran una utilidad bruta del 94.67%, reflejando buena salud financiera.

🏆 Electrónicos, Electrodomésticos y Muebles aportan más del 83% de la utilidad global.

📉 Aunque la Tienda 4 tiene los ingresos más bajos, se destaca en Electrónicos.

6️⃣ Productos Más y Menos Vendidos
| Tienda | Producto                  | Categoría         | Calificación | Comentario                            |
| ------ | ------------------------- | ----------------- | ------------ | ------------------------------------- |
| 1      | Microondas                | Electrodomésticos | 4.03         | Alta demanda con buena calificación   |
| 2      | Iniciando en programación | Libros            | 3.95         | Popularidad relacionada con contenido |
| 3      | Kit de bancas             | Muebles           | 4.10         | Reafirma el éxito de la categoría     |
| 4      | Cama box                  | Muebles           | 3.99         | Producto relevante y competitivo      |

🏅 Productos más vendidos por tienda:
Tienda	Producto	Categoría	Calificación	Comentario
1	Microondas	Electrodomésticos	4.03	Alta demanda con buena calificación
2	Iniciando en programación	Libros	3.95	Popularidad relacionada con contenido
3	Kit de bancas	Muebles	4.10	Reafirma el éxito de la categoría
4	Cama box	Muebles	3.99	Producto relevante y competitivo

❌ Productos menos vendidos por tienda:

| Tienda | Producto                  | Categoría              | Calificación | Comentario                                  |
| ------ | ------------------------- | ---------------------- | ------------ | ------------------------------------------- |
| 1      | Auriculares con micrófono | Electrónicos           | 4.00         | Posible competencia o precio                |
| 2      | Juego de mesa             | Juguetes               | 4.02         | Baja venta sin relación con la calificación |
| 3      | Bloques de construcción   | Juguetes               | 4.20         | Baja demanda específica                     |
| 4      | Guitarra eléctrica        | Instrumentos musicales | 3.91         | Baja calificación podría afectar ventas     |

Tienda	Producto	Categoría	Calificación	Comentario
1	Auriculares con micrófono	Electrónicos	4.00	Posible competencia o precio
2	Juego de mesa	Juguetes	4.02	Baja venta sin relación con la calificación
3	Bloques de construcción	Juguetes	4.20	Baja demanda específica
4	Guitarra eléctrica	Instrumentos musicales	3.91	Baja calificación podría afectar ventas

💡 Recomendaciones
Priorizar categorías clave: Enfocar esfuerzos en Electrónicos, Electrodomésticos y Muebles, que representan más del 83% de la utilidad.

Estrategias de marketing: Mejorar la percepción de las categorías con calificaciones menores a 3.8 para incentivar ventas.

Optimizar categorías secundarias: Potenciar el crecimiento en Instrumentos musicales, Juguetes y Artículos para el hogar con campañas específicas.

🛑 Conclusión Final
Se recomienda vender la Tienda 4 por las siguientes razones:

Tiene baja participación en Electrodomésticos, una de las categorías más rentables.

Aunque sus ingresos no son muy diferentes del resto, no presenta ventajas competitivas destacables.

🛠️ Herramientas Utilizadas
Python: Procesamiento y análisis de datos

Pandas: Manipulación del dataset

Matplotlib y Seaborn: Visualización gráfica

Google Colab: Plataforma interactiva para análisis y documentación

📈 Visualizaciones
El análisis incluyó gráficos de Pareto, distribuciones de calificaciones y visualizaciones de ventas por categoría.

