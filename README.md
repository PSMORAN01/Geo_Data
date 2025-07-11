# Análisis geoespacial y clasificación de zonas 🗺️🌍

Este proyecto tiene como objetivo explorar y clasificar datos geográficos a partir de múltiples variables numéricas. Utilicé distintas técnicas de preprocesamiento, visualización y modelos de clasificación para entender patrones y predecir categorías dentro de un contexto espacial.

---

## 📊 Descripción general

Trabajé con un dataset que contiene variables geográficas y numéricas asociadas a distintas zonas o regiones. El objetivo final fue construir modelos que pudieran clasificar correctamente las observaciones con base en esas características.

El flujo del proyecto fue el siguiente:
- Exploración y análisis visual
- Procesamiento y transformación de datos
- Entrenamiento de modelos
- Evaluación de desempeño

---

## ⚙️ Tecnologías utilizadas

- Python 3
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 🔍 Exploración y visualización

En la fase inicial:
- Se graficaron distribuciones de variables numéricas
- Se compararon correlaciones
- Se analizaron patrones visibles por categorías

Este análisis me ayudó a tomar decisiones sobre escalado y selección de variables.

---

## ⚗️ Preprocesamiento

Se aplicaron técnicas de escalado y transformación como:
- `StandardScaler`
- `MinMaxScaler`
- `PowerTransformer`

Esto fue importante para modelos sensibles a la escala de los datos, como regresiones y Random Forest.

También se manejaron variables desbalanceadas, y se construyeron pipelines personalizados con `make_pipeline` para combinar etapas de preprocesamiento y modelado.

---

## 🤖 Modelos utilizados

Entrené distintos modelos de clasificación:

- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **GridSearchCV** para optimizar hiperparámetros

Todos fueron evaluados con métricas como:
- Accuracy
- F1-score
- AUC-ROC
- Matriz de confusión
- Curvas ROC y Precision-Recall

---

## 📈 Resultados

El modelo con mejor desempeño logró un equilibrio entre precisión y recall, con buen puntaje F1 y AUC. Las curvas de evaluación mostraron que el modelo no solo era preciso, sino consistente entre clases, incluso en presencia de cierto desbalance.

---

## 🧠 Lecciones aprendidas

Este proyecto me ayudó a consolidar el uso de pipelines para modelado, entender el impacto de diferentes tipos de escalado en los algoritmos y comparar múltiples métricas más allá del accuracy. También reforcé la importancia de explorar visualmente los datos antes de decidir cualquier estrategia.

---

## 👨‍💻 Autor

**Pablo Sebastián Morán**  
📧 psmoran01@gmail.com  
🔗 [GitHub](https://github.com/PSMORAN01)  
