##📱 Telecom Customer Churn Prediction: Machine Learning + XAI
📌 Resumen del Proyecto
Este proyecto desarrolla un sistema de Analítica Predictiva diseñado para identificar proactivamente el riesgo de abandono (Churn) en una compañía de telecomunicaciones. Utilizando un dataset de 7,043 clientes, se implementó un flujo de trabajo basado en la metodología científica CRISP-DM, logrando un modelo capaz de anticipar fugas con alta sensibilidad técnica y explicabilidad para el negocio.

##🔄 Metodología (CRISP-DM)
El desarrollo se estructuró en las seis fases estándar de la industria:

*Comprensión del Negocio:* Definición de la tasa de abandono como KPI crítico.

*Comprensión de los Datos:* Análisis exploratorio (EDA) de variables demográficas y de servicio.

*Preparación de los Datos:* Limpieza, codificación y tratamiento de desbalanceo.

*Modelado:* Entrenamiento de algoritmos de ensamble.

*Evaluación:* Validación rigurosa mediante métricas de clasificación.

*Despliegue:* Documentación técnica.

##🧠 Innovación Técnica
#⚖️ Balanceo de Datos con SMOTEENN
Debido a que solo el 26.6% de los clientes representan la clase de abandono, se aplicó la técnica híbrida SMOTEENN. Este método combina el sobremuestreo sintético (SMOTE) con la limpieza de ruido (Edited Nearest Neighbors), permitiendo una delimitación precisa de la frontera de decisión.

#🚀 Modelo Random Forest
Se seleccionó a Random Forest como motor predictivo tras un proceso de optimización de hiperparámetros. El modelo final alcanzó:

Recall (Sensibilidad): 84% (Capacidad para detectar fugas reales).

AUC-ROC: 0.86 (Excelente capacidad de discriminación entre clases).

#🔍 IA Explicable (XAI) con SHAP
Para garantizar la transparencia, se utilizaron valores SHAP, identificando los tres principales impulsores del abandono:

*Tipo de Contrato:* Los contratos mensuales presentan el mayor riesgo.

*Tipo de Internet:* La Fibra Óptica muestra una alta correlación con el Churn.

*Cargos Mensuales:* El incremento en la facturación mensual acelera la deserción.

#🛠️ Stack Tecnológico
Lenguaje: Python 3.12.4

Librerías: Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn, SHAP, Seaborn.

Entorno: Google Colab / Jupyter Notebooks.

#⚙️ Instalación y Uso
Clonar el repositorio:
git clone https://github.com/[TU_USUARIO]/telecom-churn.git
Instalar dependencias necesarias:
pip install -r requirements.txt

#🖋️ Autor
Luz Alizon Mamani Mena

Monografía final para el Diplomado en Ciencia de Datos y Machine Learning.
