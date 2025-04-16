📊 Análisis de rendimiento de tiendas con Python.

Este proyecto consiste en un análisis de datos realizado con Python utilizando pandas y matplotlib, con el fin de evaluar el rendimiento de cuatro tiendas y ayudar al dueño a decidir cuál debería cerrar por bajo rendimiento.

🧭 1. Propósito del análisis
El objetivo principal es determinar, a través de análisis exploratorio de datos, cuál de las cuatro tiendas tiene el menor rendimiento en términos de facturación, popularidad de productos, satisfacción del cliente y costos logísticos. Este análisis busca aportar una base sólida para la toma de decisiones comerciales.

Se analizaron los siguientes aspectos clave:

Facturación total por tienda

Categorías más populares

Calificación promedio de los clientes

Productos más y menos vendidos

Costo promedio del envío

📁 2. Estructura del proyecto
css
Copiar
Editar
├── data/
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
├── visualizaciones/
│   └── (gráficos generados del análisis)
├── Tiendas_Analisis.ipynb
├── README.md
data/: Contiene los archivos CSV con los datos de cada tienda.

visualizaciones/: Carpeta opcional para guardar los gráficos generados.

Tiendas_Analisis.ipynb: Notebook principal con el código de análisis.

README.md: Archivo de documentación del proyecto.

📈 3. Ejemplos de gráficos e insights
💰 Facturación total por tienda
Gráfico de barras que muestra que la Tienda 4 fue la de menor facturación, con $1,038,375,700.

⭐ Calificaciones promedio
Tienda 1: 3.98

Tienda 2: 4.04

Tienda 3: 4.05

Tienda 4: 4.00

Aunque no es la peor en satisfacción, Tienda 4 está por debajo de la media.

📦 Productos más vendidos
Tienda 1: Microondas

Tienda 2: Iniciando en programación

Tienda 3: Kit de bancas

Tienda 4: Cama box

💸 Costo promedio de envío
Tienda 1: $26,018

Tienda 2: $25,216

Tienda 3: $24,805

Tienda 4: $23,459 (el más bajo)

Insight final: A pesar del menor costo de envío, la Tienda 4 tuvo la menor facturación, una calificación inferior al promedio y menor volumen de ventas. Se recomienda su cierre.

⚙️ 4. Instrucciones para ejecutar el notebook
Abre el archivo Tiendas_Analisis.ipynb en Google Colab.

Asegúrate de subir los archivos .csv de cada tienda a tu entorno Colab.

Ejecuta cada celda en orden para visualizar el análisis paso a paso.

Los gráficos generados mostrarán los resultados y comparaciones entre tiendas.

Requisitos:

Python 3.7 o superior

pandas

matplotlib

seaborn (opcional, si decides mejorar visuales)
