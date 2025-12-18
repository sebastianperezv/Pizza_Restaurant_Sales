# 🍕 Análisis de Ventas de Pizzería

Este proyecto combina el análisis exploratorio de datos (EDA) con **Python** y la visualización avanzada en **Power BI** para identificar patrones de demanda y mejorar la gestión de recursos, principalmente turnos, en un restaurante de pizzas.

El análisis en Jupyter Notebook se hizo en inglés, ya que los datos e instrucciones en Kaggle estaban en ese idioma.

## 🎯 Pregunta de Negocio
El análisis se centró en resolver una duda crítica para la operación:
> **"¿En qué días y horas el restaurante experimenta mayor carga de trabajo?"**

## 📂 Fuente de Datos
La información utilizada en este proyecto proviene del dataset público de Kaggle: 
[Pizza Sales Dataset](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales/data).

## 📊 Principales Hallazgos
Tras el análisis de los datos anuales de 2015, los resultados revelan:
* **Día de mayor demanda:** En una base anual, los **viernes** son los días con mayor actividad para el restaurante.
* **Horas punta:** Las horas de mayor demanda ocurren entre las **12:00 PM y 1:00 PM** (almuerzo), seguidas de otro repunte significativo entre las **5:00 PM y 6:00 PM** (cena).
* **Distribución Semanal:** Las ventas muestran una tendencia donde los viernes se consolidan como el punto máximo de trabajo.

## 🛠️ Tecnologías y Metodología

### 1. Análisis de Datos (Python)
Se utilizó un entorno de Jupyter Notebook para realizar el EDA inicial:
* **Limpieza y Carga:** Se importaron librerías como `pandas` y `matplotlib` para la manipulación y visualización de datos.
* **Transformación:** Se procesaron tipos de datos temporales (fechas y horas) para extraer el nombre del día y la hora específica.
* **Visualización:** Se generaron gráficos de líneas y barras para validar las tendencias de ventas de los productos.

### 2. Visualización e Inteligencia de Negocio (Power BI)
Se desarrolló un dashboard interactivo que permite:
* **Análisis de Series de Tiempo:** Evaluación detallada de las tendencias de ventas que poseen los productos.
* **Inteligencia de Tiempo:** Aplicación de funciones de inteligencia de tiempo utilizando la **jerarquía de fechas** (año, mes, trimestre, día).
* **Desglose Dinámico:** El reporte permite segmentar la información por mes, día o pizza específica para obtener visualizaciones profundas y las ventas totales por producto.



## 🚀 Conclusión
El análisis confirma que los viernes son los días con mayor demanda, principalmente durante el horario de almuerzo y la cena. Ademas, se logra visualizar que las ventas a lo largo del año poseen un comprtamiento estacional.

## 📊 Resultados Power BI
<img width="581" height="330" alt="1" src="https://github.com/user-attachments/assets/e09a3ea6-ad96-4732-93c9-269e67dedaa4" />

<img width="589" height="313" alt="2" src="https://github.com/user-attachments/assets/84216d36-6250-4abb-8230-0e83c2cb8887" />
