# Análisis Exploratorio de Hábitos de Compra en Instacart

## 📌 Descripción del proyecto
Este proyecto consiste en un análisis exploratorio de datos (EDA) sobre los hábitos de compra de los clientes de Instacart, una plataforma de entrega de comestibles.  
El objetivo es limpiar, preparar y analizar los datos para identificar patrones de compra, frecuencia de pedidos y comportamiento de recompra de productos.

---

## 🎯 Objetivos
- Limpiar y preprocesar múltiples conjuntos de datos relacionados con pedidos y productos.
- Analizar patrones de compra según el día de la semana y la hora del día.
- Identificar productos más pedidos y productos con mayor tasa de recompra.
- Explorar el comportamiento de los clientes en términos de frecuencia y tamaño de pedidos.

---

## 🗂️ Descripción de los datos
El proyecto utiliza cinco tablas proporcionadas por Instacart:

- **instacart_orders.csv**: información de pedidos realizados por los usuarios.
- **products.csv**: catálogo de productos.
- **order_products.csv**: relación entre pedidos y productos.
- **aisles.csv**: categorías de pasillos de productos.
- **departments.csv**: departamentos de productos.

### Columnas principales
- `order_id`, `user_id`, `order_number`
- `order_dow`, `order_hour_of_day`
- `days_since_prior_order`
- `product_id`, `product_name`
- `add_to_cart_order`, `reordered`

---

## 🧪 Metodología
El análisis se desarrolló en las siguientes etapas:

1. **Exploración inicial de los datos**
   - Revisión de estructura, tipos de datos y tamaño de las tablas.

2. **Preprocesamiento de datos**
   - Corrección de tipos de datos.
   - Tratamiento de valores ausentes.
   - Identificación y eliminación de duplicados.
   - Justificación de las decisiones de limpieza.

3. **Análisis exploratorio**
   - Análisis de pedidos por hora del día y día de la semana.
   - Distribución del número de pedidos por cliente.
   - Análisis del tiempo entre pedidos.
   - Identificación de productos más pedidos y más reordenados.
   - Estudio del comportamiento de recompra por producto y por cliente.

4. **Visualización de datos**
   - Gráficos para comunicar patrones de compra y comportamiento del cliente.

---

## 🛠️ Herramientas utilizadas
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📊 Resultados y conclusiones
El análisis revela patrones claros en los hábitos de compra de los clientes de Instacart, incluyendo variaciones en los horarios de pedido, diferencias en la frecuencia de compra y una alta recurrencia en ciertos productos.  
Estos insights pueden ser útiles para estrategias de recomendación, gestión de inventarios y análisis de comportamiento del cliente.

---

## 📁 Estructura del repositorio
├── notebooks/

│ └── proyecto_instacart_eda.ipynb

├── datasets/

│ ├── instacart_orders.csv

│ ├── products.csv

│ ├── order_products.csv

│ ├── aisles.csv

│ └── departments.csv

├── README.md

---

## 👤 Autor
**Carlos Jaramillo**  
Analista de Datos
