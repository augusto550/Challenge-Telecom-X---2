# Challenge-Telecom-X---2
Proyecto de análisis de datos y machine learning para predecir la cancelación de clientes en una empresa de telecomunicaciones.
## 1. Introducción
La cancelación de clientes (churn) es uno de los principales desafíos para las empresas de telecomunicaciones. Comprender los factores que influyen en la decisión de los clientes de abandonar el servicio permite diseñar estrategias de retención más efectivas.

Este proyecto tiene como objetivo analizar los datos de clientes de Telecom X y desarrollar modelos de machine learning capaces de predecir la probabilidad de cancelación del servicio.

## 2. Objetivos del proyecto
- Analizar los datos de clientes para identificar patrones relacionados con la cancelación del servicio.
- Preparar y transformar los datos para su utilización en modelos de machine learning.
- Construir modelos predictivos para estimar la probabilidad de churn.
- Evaluar el desempeño de los modelos utilizando métricas de clasificación.
- Identificar las variables más relevantes que influyen en la cancelación de clientes.

## 3. Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

## 4. Metodología
1. Carga y exploración de datos
2. Limpieza y preparación del dataset
3. Transformación de variables categóricas mediante One-Hot Encoding
4. Análisis exploratorio y visualización de datos
5. División del dataset en entrenamiento y prueba
6. Balanceo de clases utilizando SMOTE
7. Estandarización de variables para modelos sensibles a la escala
8. Entrenamiento de modelos de machine learning
9. Evaluación del desempeño mediante métricas de clasificación

## 5. Modelos utilizados
### Regresión Logística
Modelo sensible a la escala de los datos, por lo que se aplicó estandarización utilizando StandardScaler.

### Árbol de Decisión
Modelo basado en árboles que no requiere normalización de los datos.

## 6. Resultados y análisis
El análisis permitió identificar variables que influyen significativamente en la cancelación de clientes, entre ellas:
- Tiempo de permanencia del cliente (tenure)
- Cargos mensuales del servicio (MonthlyCharges)
- Tipo de contrato
- Tipo de servicio de internet

## 7. Estrategias de retención
- Incentivar contratos de mayor duración.
- Implementar programas de fidelización para clientes nuevos.
- Revisar planes con cargos mensuales elevados.
- Mejorar la experiencia del servicio y el soporte técnico.

## 8. Conclusión
El análisis de datos y los modelos predictivos desarrollados permiten comprender mejor los factores asociados a la cancelación de clientes. Estos resultados pueden ayudar a las empresas a implementar estrategias de retención más efectivas y mejorar la toma de decisiones basada en datos.
