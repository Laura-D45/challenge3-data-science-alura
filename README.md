# Challenge3-data-science-alura
## Predicción de Cancelación de Clientes (Churn Prediction)

## Descripción
Este proyecto tiene como objetivo analizar los factores que influyen en la cancelación de clientes (churn) y desarrollar modelos de machine learning capaces de predecir qué clientes tienen mayor probabilidad de cancelar el servicio.

## Objetivos
- Analizar el comportamiento de los clientes mediante análisis exploratorio de datos (EDA).
- Identificar variables relevantes relacionadas con la cancelación.
- Construir modelos predictivos para anticipar el churn.
- Evaluar el desempeño de los modelos mediante métricas de clasificación.

## Metodología
El proyecto se desarrolló siguiendo las siguientes etapas:

1. **Carga y limpieza de datos**
2. **Análisis exploratorio de datos (EDA)**
3. **Codificación de variables categóricas**
4. **Análisis de correlación**
5. **Entrenamiento de modelos predictivos**
6. **Evaluación de modelos**
7. **Análisis de importancia de variables**

## Modelos Utilizados
- **Regresión Logística**
- **Random Forest**

## Métricas de Evaluación
Para evaluar el rendimiento de los modelos se utilizaron:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

## Principales Hallazgos
Las variables que mostraron mayor influencia en la cancelación de clientes fueron:

- Tiempo de permanencia del cliente (**tenure**)
- Cargos mensuales (**Charges.Monthly**)
- Gasto total (**Charges.Total**)
- Tipo de contrato

Los resultados muestran que los clientes con **contratos mensuales, menor tiempo de permanencia y mayores cargos mensuales** presentan mayor probabilidad de cancelar el servicio.

## Recomendaciones
A partir del análisis se sugieren las siguientes estrategias de retención:

- Incentivar contratos de mayor duración.
- Implementar programas de fidelización para clientes nuevos.
- Evaluar beneficios adicionales para clientes con altos cargos mensuales.

## Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Autor
Proyecto desarrollado como ejercicio de análisis de datos y machine learning aplicado a la predicción de cancelación de clientes, planteado por alura y hecho por Laura Diaz.
