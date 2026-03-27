# 📊 Predicción de Recompra de Clientes

## Realizado por Óscar Fernández-Chinchilla López - Máster Data Science & IA Generativa Evolve Academy (2025/2026)

## 🎯 Objetivo

El objetivo del proyecto es **predecir qué clientes volverán a comprar**, utilizando su historial de compras.  
Esto permite identificar clientes valiosos y mejorar estrategias de negocio como marketing o fidelización.

---

## Observaciones
Además, al haber utilizado la plantilla por defecto para el proyecto, en mi caso personal hay veces que al ejecutar todo el archivo con la opción "ejecutar todo", da error con el controlador del notebook. Sin embargo funciona todo correctamente si se va ejecutando celda por celda. Utilizar de esta manera si ocurre el error mencionado, sino, puede funcionar perfectamente ejecutando todo a la vez.

---

## 🗂️ Estructura del proyecto

El proyecto está organizado en tres bloques principales:

### 📁 EDA
- **Data_01_Exploration.ipynb** → Análisis exploratorio inicial
- **Data_02_Cleansing_Transformation.ipynb** → Limpieza y preparación de datos
- **Data_03_Visualization.ipynb** → Visualizaciones y análisis más avanzados

### 📁 Model
- **modelML_logistic_LGBM.ipynb** → Construcción del modelo, entrenamiento, evaluación y scoring

---

## ⚙️ Qué se ha hecho

- Limpieza y preparación de datos transaccionales
- Análisis exploratorio para entender el comportamiento de clientes
- Creación de variables a nivel cliente (frecuencia, gasto, recencia, etc.)
- Definición de un problema de predicción de recompra
- Entrenamiento y comparación de varios modelos
- Optimización de modelos (GridSearch y Optuna)
- Cálculo de la probabilidad de recompra por cliente
- Segmentación de clientes según su probabilidad
- Análisis de variables más importantes (explicabilidad)

---

## 📈 Principales insights

- La **recencia** (tiempo desde la última compra) es la variable más importante
- Los clientes con compras recientes tienen mayor probabilidad de volver
- La mayoría de clientes compran pocas veces → distribución muy desigual
- Existe un pequeño grupo de clientes muy recurrentes y de alto valor
- El negocio está muy concentrado en **United Kingdom**
- Hay productos con alta frecuencia → catálogo típico de retail
- Las devoluciones son pocas, pero aportan información relevante
- No hay una separación clara entre clientes → comportamiento continuo

---

## 🚀 Resultado

Se ha construido un modelo capaz de:

- Predecir la probabilidad de recompra de cada cliente
- Segmentar clientes en función de su valor potencial y probabilidad de recompra
- Explicar qué variables influyen en la recompra

---

## 📌 Uso del modelo

El modelo permite:

- Identificar clientes con alta probabilidad de recompra
- Mejorar la toma de decisiones basada en datos

---

## 🧩 Conclusión

El proyecto muestra un flujo completo de análisis de datos y machine learning aplicado a un caso real de negocio, combinando:

- Análisis exploratorio
- Feature engineering
- Modelado predictivo
- Interpretabilidad

👉 Enfocado tanto a **técnica como a aplicación práctica** , además ha sido comentado y documentado de tal manera que sirva como plantilla y refuerzo para el futuro por si necesito consultar algo relacionado con lo visto en el proyecto.