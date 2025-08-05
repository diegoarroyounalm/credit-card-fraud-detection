# 💳 Proyecto de Detección de Fraude con Tarjetas de Crédito

Este proyecto analiza y detecta transacciones fraudulentas con tarjetas de crédito utilizando un conjunto de datos realista. Incluye limpieza de datos, análisis exploratorio (EDA) y modelos de clasificación.

![portada](headers_fraud-prev.jpg)

## 🎯 Objetivo del Proyecto

Detectar transacciones potencialmente fraudulentas a partir de datos históricos mediante la identificación de patrones y la construcción de un modelo de clasificación que ayude a las instituciones financieras a reducir el riesgo.

---

## 🧰 Herramientas y Tecnologías

- Python (Pandas, NumPy)
- Seaborn y Matplotlib para visualización
- Scikit-learn para Machine Learning
- Jupyter Notebook

---

## 📊 Descripción del Dataset

El dataset contiene más de 300,000 transacciones con 15 columnas, incluyendo:

| Campo                   | Descripción                                        |
|-------------------------|----------------------------------------------------|
| `trans_date_trans_time` | Fecha y hora de la transacción                     |
| `merchant`              | Nombre del comercio                                |
| `category`              | Categoría del comercio                             |
| `amt`                   | Monto de la transacción                            |
| `city`, `state`         | Ciudad y estado del titular de la tarjeta          |
| `lat`, `long`           | Coordenadas del titular                            |
| `merch_lat`, `merch_long` | Coordenadas del comercio                         |
| `dob`                   | Fecha de nacimiento del titular                    |
| `job`                   | Profesión del titular                              |
| `is_fraud`              | Variable objetivo (1 = fraude, 0 = no fraude)      |

---

## 🧪 Flujo de Trabajo del Proyecto

1. **Limpieza de datos**:
   - Conversión de fechas
   - Creación de nuevas variables como edad y hora
   - Revisión de valores nulos

2. **Análisis Exploratorio (EDA)**:
   - Distribución del fraude
   - Comparación de montos según tipo de transacción
   - Análisis geográfico

4. **Modelado**:
   - División en datos de entrenamiento y prueba
   - Modelos de clasificación: Regresión logística, Random Forest, etc.
   - Métricas: Precisión, Recall, AUC, F1-score, matriz de confusión

5. **Conclusiones**

---

## ✅ Conclusiones

- Se logró construir un pipeline de análisis completo, desde la limpieza de datos hasta el modelado supervisado, enfocado en la detección de fraude con tarjetas de crédito.
- Se observó que las transacciones fraudulentas presentan **patrones distintos** en variables como el monto (`amt`), la hora (`trans_date_trans_time`) y la distancia entre el comercio y el titular.

---

## 💡 Recomendaciones

- **Incorporar más fuentes de datos externas**, como historial del cliente o variables contextuales (fechas clave, feriados, etc.) para mejorar la capacidad predictiva.
- Aplicar **técnicas de balanceo** de clases (como SMOTE o undersampling), dado que los datos suelen estar desbalanceados en problemas de fraude.


## ✏️ Autor

**Diego Arroyo**

📧 diegojulioarroyo@gmail.com 
 
🔗 [Mi LinkedIn](https://www.linkedin.com/in/diego-arroyo-b2153b229/) 
