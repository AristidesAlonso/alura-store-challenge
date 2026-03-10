# Alura Store Challenge - Análisis de Ventas

## 📋 Descripción del Proyecto
Este proyecto analiza el desempeño de cuatro tiendas de Alura Store para determinar cuál debe venderse, permitiendo al Sr. Juan invertir en un nuevo negocio. El análisis se basa en cinco criterios: ingresos totales, categorías populares, calificaciones de clientes, productos más/menos vendidos y costos de envío.

## 🚀 Tecnologías Utilizadas
- **Python 3.x**
- **Pandas**: Manipulación y análisis de datos
- **Matplotlib**: Visualización de datos
- **Google Colab**: Entorno de desarrollo

## 📁 Estructura del Proyecto
alura-store-challenge/
│
├── AluraStoreLatam.ipynb # Cuaderno principal con todo el análisis
├── README.md # Este archivo
└── data/ # Carpeta con archivos CSV (opcional)
├── tienda_1.csv
├── tienda_2.csv
├── tienda_3.csv
└── tienda_4.csv



## ⚙️ Instalación y Configuración

### Prerrequisitos
- Cuenta en Google (para Colab)
- Conexión a internet

### Pasos para ejecutar
1. Abre [Google Colab](https://colab.research.google.com/)
2. Sube el archivo `AluraStoreLatam.ipynb`
3. Ejecuta las celdas en orden secuencial
4. Los datos se cargan automáticamente desde GitHub

## 📊 Análisis Realizados

### 1. Ingresos por Tienda
- Cálculo de facturación total sumando la columna 'Precio'
- **Resultado:** Tienda 1 lidera con $1,150M, Tienda 4 última con $1,038M

### 2. Categorías Más Vendidas
- Conteo de ventas por categoría en cada tienda
- **Resultado:** Muebles es la categoría principal en todas las tiendas

### 3. Calificaciones de Clientes
- Promedio de calificaciones por tienda (escala 1-5)
- **Resultado:** Tienda 3 mejor calificada (4.05), Tienda 1 la más baja (3.98)

### 4. Productos Más y Menos Vendidos
- Identificación de productos estrella y débiles por tienda
- **Resultado:** Tienda 2 tiene el producto más vendido (65 uds)

### 5. Costo de Envío Promedio
- Promedio de la columna 'Costo de envío' por tienda
- **Resultado:** Tienda 4 tiene envío más económico ($23,459)

## 📈 Visualizaciones Incluidas
- Gráfico de barras: Ingresos por tienda
- Gráfico de barras: Ventas por categoría
- Gráfico de barras: Calificaciones promedio
- Gráfico de barras: Top 10 productos más vendidos
- Gráfico de barras: Costo de envío promedio

## 🏆 Conclusión Final
**La tienda recomendada para vender es la Tienda 4** por presentar:
- Menor facturación ($1,038M)
- Calificación estancada (4.00)
- Sin fortalezas destacadas en ningún criterio clave
- Envío barato beneficia al cliente, no a la rentabilidad

## 👨‍💻 Autor
- **Nombre:** [Aristides Alonso]
- **Proyecto:** Challenge ONE Data Science - Alura Store

## 📝 Licencia
Este proyecto fue creado con fines educativos como parte del programa Oracle Next Education (ONE) en colaboración con Alura Latam.

## 🔗 Enlaces Útiles
- [Repositorio base del desafío](https://github.com/alura-es-cursos/challenge1-data-science-latam)
- [Tablero Trello del proyecto](URL-de-tu-tablero)
- [Google Colab](https://colab.research.google.com/)
