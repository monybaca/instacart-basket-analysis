# Instacart Basket Analysis

Este proyecto realiza un análisis completo del comportamiento de compra dentro de la plataforma Instacart. Utilizando cinco tablas principales (pedidos, productos, departamentos, historial de compras y más), se lleva a cabo limpieza, preprocesamiento, integración de datos y análisis exploratorio para comprender cómo, cuándo y qué compran los usuarios.


## 📌 Objetivo
- Explorar y comprender la estructura del dataset de Instacart.
- Limpiar y preprocesar datos antes de realizar cualquier análisis.
- Integrar varias tablas para formar un dataset coherente.
- Identificar patrones relevantes en los hábitos de compra.
- Preparar información útil para análisis posteriores o dashboards.


## 🧹 Limpieza y Preparación de Datos
El trabajo incluyó:
- Importación de cinco archivos CSV con estructuras diferentes.
- Estandarización de tipos de datos.
- Detección y eliminación de valores duplicados.
- Revisión de inconsistencias y valores faltantes.
- Validación de claves y relaciones entre tablas.
- Corrección manual de columnas cuando fue necesario.


## 📊 Análisis Realizado
- Revisión completa de cada DataFrame (dimensiones, tipos, estructura).
- Integración de tablas mediante merges (productos, órdenes, historial, etc.).
- Identificación de productos, departamentos y categorías más populares.
- Exploración de tendencias de compra según horario, día o producto.
- Observación del comportamiento del usuario en el recorrido de compra.


## 📈 Resultados Principales
- Se observó una estructura de datos robusta pero con valores duplicados que requerían limpieza.
- Los productos más populares provienen de departamentos específicos como produce, dairy y snacks.
- Los usuarios muestran patrones definidos según el día de la semana y la hora del día.
- La integración del dataset permite analizar con detalle combinaciones como:  
  **producto × departamento × frecuencia de compra**.


## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **Jupyter Notebook**


## 📁 Archivos del Proyecto
- `instacart-basket-analysis.ipynb` — Notebook principal del análisis.
- Archivos CSV utilizados (orders, products, departments, etc.)

---

## 📬 Contacto
Proyecto desarrollado como parte del portafolio analítico de **Monica Baca**.
