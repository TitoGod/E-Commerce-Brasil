# Proyecto de Análisis de Datos - E-commerce en Brasil

## Descripción del Proyecto
Este proyecto tiene como objetivo analizar datos de transacciones de comercio electrónico en Brasil utilizando el dataset público de Olist, disponible en Kaggle. El proceso de análisis incluye la automatización de la descarga de datos, su transformación y limpieza con Python, el almacenamiento en SQL Server y la creación de un dashboard en Power BI para visualizar tendencias y patrones de compra.

## Objetivos
- Automatizar la descarga y procesamiento de los datos desde Kaggle.
- Diseñar un esquema de base de datos en SQL Server.
- Transformar y limpiar los datos con Pandas.
- Analizar las tendencias de ventas, clientes, pagos y envíos.
- Crear un dashboard en Power BI para visualizar los resultados.

## Preguntas de Negocio
Este análisis se enfoca en responder las siguientes preguntas clave:

### 1. Análisis de Ventas y Tendencias
- ¿Cuáles son los productos más vendidos y cuáles generan más ingresos?
- ¿Qué categorías de productos tienen la mayor cantidad de ventas?
- ¿Cuál es la tendencia de ventas a lo largo del tiempo? (mensual, anual)
- ¿Qué épocas del año tienen más ventas? (Black Friday, Navidad, etc.)
- ¿Cómo varían las ventas según la ubicación geográfica de los clientes?

### 2. Análisis de Clientes
- ¿Cuál es el perfil de los clientes más frecuentes? (ubicación, cantidad de compras)
- ¿Cuáles son los estados o ciudades con mayor número de clientes y compras?
- ¿Cuántos clientes son recurrentes vs. clientes nuevos?

### 3. Análisis de Métodos de Pago
- ¿Cuál es el método de pago más utilizado? (tarjeta de crédito, boleto bancario, débito)
- ¿Cómo varía el monto promedio de compra según el método de pago?
- ¿Cuántas cuotas en promedio eligen los clientes al pagar con tarjeta de crédito?

### 4. Análisis de Envíos y Logística
- ¿Cuál es el tiempo promedio de entrega por categoría de producto?
- ¿Cuáles son los estados con mayor retraso en la entrega?
- ¿Cómo afecta el tiempo de entrega a la satisfacción del cliente?

### 5. Análisis de Reseñas y Satisfacción del Cliente
- ¿Cómo se relaciona la calificación de los productos con el tiempo de entrega?
- ¿Qué factores influyen en las calificaciones bajas de los clientes?
- ¿Cuál es la distribución de calificaciones en cada categoría de producto?

## Tecnologías Utilizadas
- **Python** (Pandas, NumPy, Pyodbc, Matplotlib, Seaborn)
- **SQL Server** (Para almacenamiento y consulta de datos)
- **Power BI** (Para visualización de datos)
- **Kaggle API** (Para descarga automatizada del dataset)

## Estructura del Proyecto
- `data/` : Carpeta donde se almacenan los datos originales.
- `scripts/` : Contiene los scripts de Python para limpieza, ETL y carga en SQL Server.
- `notebooks/` : Análisis exploratorio de los datos.
- `sql/` : Consultas SQL utilizadas para el análisis.
- `dashboard/` : Archivos de Power BI con visualizaciones.

## Instalación y Ejecución
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/TitoGod/E-Commerce-Brasil.git
   cd nombre_repositorio
   ```
2. Crear un entorno virtual e instalar dependencias:
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Configurar la API de Kaggle para descargar los datos.
4. Ejecutar los scripts de ETL y carga de datos en SQL Server.
5. Abrir Power BI para analizar los resultados.

## Contacto
Si tienes dudas o sugerencias, contáctame a: [mauro.dr07@gmail.com]

