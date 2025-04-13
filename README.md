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
  *Gráfico*: Gráfico de barras mostrando ingresos totales por tienda.
- **Categorías**: Muebles y Electrónicos son los más vendidos; Tienda 4 flaquea en Electrodomésticos (254 ventas).  
  *Gráfico*: Gráfico circular de distribución de categorías para Tienda 1.
- **Calificaciones**: Tienda 3 sobresale (4.05); Tienda 1 es la más baja (3.98).  
  *Gráfico*: Gráfico de barras horizontales comparando calificaciones promedio.
- **Productos**: Destacan Microondas (Tienda 1, 60 ventas) y Cama box (Tienda 4, 62 ventas).  
  *Gráfico*: Gráfico de barras con los 5 productos más vendidos en Tienda 1.
- **Costos de envío**: Tienda 4 tiene el menor costo ($23,459.46), pero no compensa otras áreas.  
  *Gráfico*: Gráfico de dispersión de costos de envío promedio por tienda.
- **Geografía**: Ventas concentradas en Bogotá (~980-990) y Medellín (~560-590). Tienda 4 tiene menos ventas en Pereira (122) y Cúcuta (32), mostrando un alcance regional más débil.  
  *Gráfico*: Gráficos de dispersión por tienda, mostrando ventas según coordenadas geográficas.

## Recomendación
Se sugiere vender la **Tienda 4** por sus bajos ingresos, calificaciones promedio (4.00), menor variedad en categorías y menor presencia en algunas ciudades, lo que la hace menos competitiva frente a las Tiendas 1, 2 y 3.

## Herramientas
- **Python** con Pandas y Matplotlib.
- **Google Colab** para ejecutar el análisis.

## Notas
Desarrollado para el desafío de Alura Latam, procesando datos para decisiones claras.
