# Predicción del Estado de Bombas de Agua en Tanzania 🚰

Este proyecto resuelve el desafío de predecir el estado funcional de bombas de agua en Tanzania. Utiliza datos públicos proporcionados por la plataforma Taarifa y el Ministerio de Agua de Tanzania, en el marco de la competencia de DrivenData:  
🔗 [Pump it Up: Data Mining the Water Table](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/23/)

---

## 🎯 Objetivo

Clasificar el estado funcional de cada bomba de agua en tres categorías:

- ✅ Funcional  
- ⚠️ Funcional pero necesita reparación  
- ❌ No funcional  

Este proyecto busca optimizar el mantenimiento de infraestructura hídrica para garantizar acceso continuo a agua limpia y potable en comunidades rurales.

---

## 🧠 Enfoque del Proyecto

1. **Exploración de Datos**  
   Análisis de las variables y su distribución para detectar patrones y problemas de calidad en los datos.

2. **Modelo Base**  
   Implementación de un primer modelo sencillo para establecer una línea base de rendimiento.

3. **Preprocesamiento**  
   - Limpieza de datos
   - Imputación de valores faltantes
   - Codificación de variables categóricas
   - Escalado de variables numéricas

4. **Modelado Predictivo**  
   Entrenamiento de modelos de clasificación:
   - Árboles de decisión (Decision Tree)
   - Bosques aleatorios (Random Forest)
   - Otros modelos exploratorios

5. **Evaluación del Modelo**  
   Evaluación utilizando métricas como:
   - Accuracy
   - F1-Score

6. **Optimización**  
   Ajuste de hiperparámetros y comparación de modelos para mejorar el rendimiento predictivo.

---

## 🛠️ Requisitos

- Python 3.x
  
📦 Librerías utilizadas
**Lo básico y análisis**
- pandas
- numpy

**Visualización**
- matplotlib
- seaborn
- plotly
- pandas.plotting

**Preprocesado**
- scikit-learn
- imbalanced-learn
- scipy

**Modelado**
- scikit-learn
- xgboost

**Reducción de dimensionalidad**
- scikit-learn

**Selección de características**
- scikit-learn

**Manejo de desbalanceo**
- imbalanced-learn


**Instalación recomendada:**

```bash
pip install -r requirements.txt


