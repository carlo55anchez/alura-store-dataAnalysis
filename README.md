# Análisis de Datos de Alura Store

Este proyecto analiza las cuatro tiendas de Alura Store para recomendar cuál vender, ayudando al Sr. Juan con su nuevo emprendimiento. Se usaron datos de ventas para evaluar ingresos, categorías, calificaciones, productos, costos de envío y distribución geográfica, con un cuaderno en Google Colab.

## ¿Qué contiene?
El cuaderno `Alura_Store_Analysis.ipynb` incluye:
- Carga de datos desde URLs de GitHub.
- Cálculos de métricas clave.
- Gráficos para visualizar tendencias.
- Un informe recomendando vender una tienda.

## Cómo usar
1. Abre `Alura_Store_Analysis.ipynb` en [Google Colab](https://colab.research.google.com).
2. Ejecuta las celdas en orden:
   - Carga los datos.
   - Calcula ingresos, categorías, calificaciones, productos, costos y análisis geográfico.
   - Genera gráficos.
   - Lee el informe final.
3. No necesitas descargar los CSV; los datos se cargan desde URLs.

## Resultados principales
- **Ingresos**: Tienda 1 lidera ($1,150,880,400); Tienda 4 es la más baja ($1,038,375,700).  
  *Gráfico*:  
  ![Ingresos Totales por Tienda](img/Análisis%20de%20facturación.png)

- **Categorías**: Muebles y Electrónicos son los más vendidos; Tienda 4 flaquea en Electrodomésticos (254 ventas).  
  *Gráfico*:  
  ![Distribución de Categorías - Tienda 1](img/Ventas%20por%20categoría.png)

- **Calificaciones**: Tienda 3 sobresale (4.05); Tienda 1 es la más baja (3.98).  
  *Gráfico*:  
  ![Calificaciones Promedio por Tienda](img/Calificación%20promedio%20de%20la%20tienda.png)

- **Productos**: Destacan Microondas (Tienda 1, 60 ventas) y Cama box (Tienda 4, 62 ventas).  
  *Gráfico*:  
  ![Top 5 Productos Más Vendidos - Tienda 1](img/Productos%20más%20y%20menos%20vendidos.png)

- **Costos de envío**: Tienda 4 tiene el menor costo ($23,459.46), pero no compensa otras áreas.  
  *Gráfico*:  
  ![Costos de Envío Promedio por Tienda](img/Envío%20promedio%20por%20tienda.png)

- **Geografía**: Ventas concentradas en Bogotá (~980-990) y Medellín (~560-590). Tienda 4 tiene menos ventas en Pereira (122) y Cúcuta (32), mostrando un alcance regional más débil.  
  *Gráficos*:  
  ![Ventas Geográficas - Tienda 1](img/Análisis%20Geográfico%20de%20Ventas%20por%20Tienda%201.png)  
  ![Ventas Geográficas - Tienda 2](img/Análisis%20Geográfico%20de%20Ventas%20por%20Tienda%202.png)  
  ![Ventas Geográficas - Tienda 3](img/Análisis%20Geográfico%20de%20Ventas%20por%20Tienda%203.png)  
  ![Ventas Geográficas - Tienda 4](img/Análisis%20Geográfico%20de%20Ventas%20por%20Tienda%204.png)

## Recomendación
Se sugiere vender la **Tienda 4** por sus bajos ingresos, calificaciones promedio (4.00), menor variedad en categorías y menor presencia en algunas ciudades, lo que la hace menos competitiva frente a las Tiendas 1, 2 y 3.

## Herramientas
- **Python** con Pandas y Matplotlib.
- **Google Colab** para ejecutar el análisis.

## Notas
Desarrollado para el desafío de Alura Latam, procesando datos para decisiones claras.
