# alura-store
📂 Proyecto_Tiendas
├── 📄 README.md ← Este archivo (documentación principal)
├── 📓 analisis_tiendas.ipynb ← Notebook principal (Google Colab o Jupyter)
├── 📊 datos/
│ ├── tienda1.csv
│ ├── tienda2.csv
│ ├── tienda3.csv
│ ├── tienda4.csv
│ └── (otros archivos de datos si aplica)
└── 📁 resultados/
├── visualizaciones/ ← Gráficos generados (ingresos, categorías, geolocalización)
└── informe_final.md ← Informe generado automáticament

Dependencias principales:

pandas → Manejo y análisis de datos tabulares

matplotlib → Visualización de datos

folium → Mapas interactivos (opcional, para análisis geográfico)

openpyxl → Lectura y escritura de archivos Excel (si se usa formato .xlsx)

🚀 Ejecución del Proyecto

Cargar los datos
Asegúrate de tener los cuatro archivos de datos (tienda1.csv, tienda2.csv, etc.) en la carpeta datos/.

Abrir el notebook
Puedes abrir el archivo analisis_tiendas.ipynb en:

Google Colab

Jupyter Notebook

Ejecutar las celdas paso a paso
El notebook incluye:

Limpieza y preparación de datos (Fecha de Compra, tipos de datos, etc.)

Cálculo de métricas clave (ingresos, calificaciones, costos, etc.)

Visualizaciones (barras, dispersión, pie charts, heatmaps)

Análisis geográfico usando coordenadas (lat, lon)

Generación automática del informe final en Markdown

Visualizar resultados
Al final del notebook se generan:

Gráficos interpretativos.

Una tabla comparativa con métricas clave.

Un informe automatizado con la recomendación final para el Sr. Juan.

📊 Visualizaciones Incluidas

Gráfico de barras — Ingresos totales por tienda.

Gráfico circular (pie chart) — Distribución de categorías más vendidas.

Gráfico de dispersión — Relación entre precio y calificación.

Barras horizontales — Top 10 productos por tienda.

Mapa de calor / Folium Map — Distribución geográfica de ventas.

🧠 Resultados Esperados

El análisis responde a las siguientes preguntas:

¿Qué tienda genera mayores ingresos totales?

¿Qué productos y categorías son los más populares?

¿Qué tienda tiene clientes más satisfechos?

¿Cuál tiene el costo de envío más competitivo?

¿Dónde se concentran las ventas geográficamente?

Finalmente, se recomienda la tienda más conveniente para el Sr. Juan en función de:

Ingresos (50%)

Calificación promedio (30%)

Costo de envío (20%)

Estos pesos pueden modificarse fácilmente en el código (w_ing, w_cal, w_env).

🌍 Análisis Geográfico (Extra)

En la sección extra del notebook, se visualiza la distribución espacial de las ventas utilizando las coordenadas lat y lon.

Esto permite:

Identificar regiones con mayor concentración de ventas.

Detectar patrones geográficos que explican el rendimiento de cada tienda.

Explorar posibles zonas de expansión para nuevas ventas.

Los gráficos incluyen:

Scatter plots para observar dispersión.

Heatmaps para ver densidad de ventas.

Mapas interactivos (Folium) para una exploración dinámica.

🧾 Informe Final

El notebook genera automáticamente un informe en Markdown con:

Introducción y objetivo del análisis.

Resumen numérico de cada tienda.

Gráficos y visualizaciones clave.

Conclusión y recomendación final para el Sr. Juan.

Ejemplo de salida:

Recomendación: Vender en Tienda 2
por su combinación de altos ingresos, buenas calificaciones y coste de envío competitivo.
