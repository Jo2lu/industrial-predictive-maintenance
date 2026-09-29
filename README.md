# Mantenimiento Predictivo & Análisis de Fallas Industriales

Este proyecto aplica técnicas de **Análisis Exploratorio de Datos (EDA)** y modelos de **Machine Learning** para la detección y predicción temprana de fallas en sensores de equipos industriales automatizados.

---

## Objetivo del Proyecto

Optimizar la disponibilidad operativa y reducir paros no programados mediante la identificación de patrones anómalos en variables críticas de proceso (Temperatura, Vibración, Velocidad RPM y Horas de Uso).

---

## Stack Tecnológico & Librerías

- **Lenguaje:** Python 3.x
- **Manipulación de Datos:** `pandas`, `numpy`
- **Visualización:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (`RandomForestClassifier`, `train_test_split`, `metrics`)

---

## Metodología & Flujo de Trabajo

1. **Simulación de Sensores:** Generación de variables continuas de condición operativa basadas en tolerancias industriales realistas.
2. **Análisis Exploratorio de Datos (EDA):**
   - Identificación de límites críticos ($>85^\circ\text{C}$ de temperatura y $>4.0\text{ mm/s}$ de vibración).
   - Matriz de dispersión y análisis de distribución de fallas.
3. **Modelado Predictivo:**
   - Entrenamiento de un algoritmo de clasificación (**Random Forest**).
   - Evaluación del desempeño mediante matrices de confusión y métricas de *Precision/Recall*.
   - Identificación de la importancia de variables (*Feature Importance*).

---

## Resultados Clave

- **Precisión del Modelo:** Clasificación efectiva de equipos en riesgo de falla con alta métrica de sensibilidad (*Recall*).
- **Variable Crítica:** La **Temperatura (°C)** y las **Horas de Uso acumuladas** representan los predictores de mayor peso en la falla del equipo.

---

## Archivos en el Repositorio

- `mantenimiento_predictivo.ipynb`: Código ejecutable en Google Colab / Jupyter Notebook.

---

### Autor
**jo2lu**  
*Ingeniero Mecatrónico | Analista de Datos*  
Puebla, México | [Correo](mailto:martinez.landero.jose@gmail.com)
