# Alura Store Data Analysis

## Descripción
Este proyecto analiza datos de ventas de las cuatro tiendas de Alura Store para ayudar al Sr. Juan a decidir cuál vender para iniciar un nuevo emprendimiento. Se evaluaron métricas clave como ingresos totales, categorías de productos, calificaciones de clientes, productos más/menos vendidos y costos de envío promedio. El análisis se realizó en un cuaderno de Jupyter alojado en Google Colab, utilizando Pandas para manipulación de datos y Matplotlib para visualizaciones. El resultado es un informe final con una recomendación fundamentada.

## Estructura del Proyecto
- **`Alura_Store_Analysis.ipynb`**: Cuaderno principal con el código, análisis, visualizaciones e informe final.
- **`data/`**: (Opcional) Carpeta para almacenar los archivos CSV, aunque los datos se cargan desde URLs en el cuaderno.
- **`README.md`**: Este archivo, que describe el proyecto.

## Pasos Realizados
1. **Carga de Datos**:
   - Se cargaron los datos de las cuatro tiendas desde URLs en GitHub (`tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`) usando Pandas.
   - Los datos incluyen columnas como `Producto`, `Categoría del Producto`, `Precio`, `Costo de envío`, `Calificación`, etc.

2. **Análisis Realizados**:
   - **Ingresos Totales**: Se sumó la columna `Precio` para cada tienda.
   - **Categorías de Productos**: Se contó la cantidad de ventas por categoría con `value_counts()`.
   - **Calificaciones Promedio**: Se calculó el promedio de la columna `Calificación`.
   - **Productos Más/Menos Vendidos**: Se identificaron los productos con más y menos ventas por tienda.
   - **Costos de Envío Promedio**: Se calculó el promedio de la columna `Costo de envío`.

3. **Visualizaciones**:
   - **Gráfico de barras**: Ingresos totales por tienda.
   - **Gráfico circular**: Distribución de categorías en Tienda 1.
   - **Gráfico de barras horizontales**: Calificaciones promedio por tienda.
   - **Gráfico de barras**: Top 5 productos más vendidos en Tienda 1.
   - **Gráfico de dispersión**: Costos de envío promedio por tienda.

4. **Informe Final**:
   - Se redactó un informe en el cuaderno con una introducción, desarrollo (detallando los análisis y gráficos) y conclusión.
   - Se recomendó vender la Tienda 4, basada en sus menores ingresos, calificaciones promedio no destacadas y menor variedad en categorías, respaldado por los datos.

## Requisitos
- **Google Colab**: Para ejecutar el cuaderno `.ipynb`.
- **Python 3.x** con las bibliotecas:
  - `pandas`: Para manipulación de datos.
  - `matplotlib`: Para visualizaciones.

Instala las dependencias con:
```bash
pip install pandas matplotlib

Cómo Ejecutar
Abre el archivo Alura_Store_Analysis.ipynb en Google Colab.
Ejecuta las celdas en orden:
Carga de datos.
Cálculos de ingresos, categorías, calificaciones, productos y costos de envío.
Generación de gráficos.
Visualización del informe final.
Los datos se cargan automáticamente desde URLs, por lo que no es necesario descargar los CSV.
Resultados
Ingresos: Tienda 1 lideró con $1,150,880,400; Tienda 4 tuvo el menor ingreso ($1,038,375,700).
Categorías: Muebles y Electrónicos dominaron en todas las tiendas; Tienda 4 tuvo menos ventas en Electrodomésticos.
Calificaciones: Tienda 3 tuvo la mayor satisfacción (4.05); Tienda 1 la menor (3.98).
Productos: Productos estrella incluyeron Microondas (Tienda 1) y Cama box (Tienda 4).
Costos de Envío: Tienda 4 tuvo el menor costo promedio ($23,459.46), pero no compensó otras debilidades.
Conclusión
El análisis recomienda vender la Tienda 4 debido a sus bajos ingresos, calificaciones promedio no competitivas y menor desempeño en categorías clave, lo que la hace la menos eficiente para mantener.

Autor
Desarrollado como parte del desafío de análisis de datos de Alura Latam.
