# 👟 Análisis Exploratorio de Datos: Ventas de Adidas (EDA)

Este proyecto consiste en un **análisis exploratorio de datos (EDA)** sobre ventas de productos Adidas en Estados Unidos.  
El objetivo es limpiar, transformar y visualizar el dataset para preparar los datos de cara a análisis posteriores o su integración en herramientas de visualización como **Looker Studio**.

> ⚠️ **Fuente de los datos:**  
> El dataset utilizado proviene de Kaggle:  
> [Adidas Sales Dataset – Kaggle](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset)

---

## 🚀 Tecnologías y librerías utilizadas

- **Python** 🐍 – Lenguaje principal del análisis.
- **Pandas** 📊 – Manipulación y limpieza de datos.
- **NumPy** 🔢 – Cálculos numéricos.
- **Seaborn & Matplotlib** 📈 – Visualización de datos.
- **Scikit-learn** 🧪 – Escalado y transformación de variables.
- **SciPy** 🧮 – Análisis estadístico y detección de outliers.

---

## 🛠️ Proceso y pasos realizados

El análisis se desarrolla en un **notebook Jupyter** y sigue esta secuencia:

1. **Importación de librerías** y configuración inicial.
2. **Carga del dataset** desde Google Sheets (descargado previamente desde Kaggle).
3. **Exploración preliminar**: estructura, tipos de datos y valores nulos.
4. **Limpieza y transformación** de datos:
   - Conversión de monedas, porcentajes y fechas a formatos numéricos.
5. **Detección y eliminación de outliers** usando métodos como Z-Score e IQR.
6. **Escalado y normalización** de variables para futuros modelos o visualizaciones.
7. **Visualización exploratoria** de variables numéricas y categóricas.
8. **Análisis de correlaciones** y relaciones entre variables.
9. **Exportación del dataset limpio**, listo para análisis posteriores o visualización.

---

## 📌 Notas adicionales

- Se aplicaron transformaciones necesarias para convertir texto en valores numéricos (por ejemplo, precios y porcentajes).
- Se eliminaron valores atípicos que distorsionaban el análisis.
- El dataset final se encuentra preparado para su uso en dashboards como Looker Studio.

---

## 📊 Dashboard (en desarrollo)

Al fina del proyecto, se incluye un enlace a un **dashboard en Looker Studio**, donde se visualizarán las métricas clave y análisis realizados de forma interactiva. El mismo todavía no está finalizado.  

---

**David Schmidt**  
*Trabajo práctico de análisis exploratorio de datos (EDA)*
