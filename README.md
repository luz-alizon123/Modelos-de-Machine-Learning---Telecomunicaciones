📱 Telecom Customer Churn Prediction: ML + XAI
📄 Descripción del Proyecto
Este proyecto desarrolla un sistema de inteligencia artificial para la predicción proactiva del abandono de clientes (Churn) en empresas de telecomunicaciones. El objetivo principal es identificar usuarios con alta probabilidad de fuga para implementar estrategias de retención basadas en datos.

Se utiliza un enfoque de IA Explicable (XAI) para desmitificar las predicciones del modelo y proporcionar conocimiento accionable a la gerencia estratégica.

🚀 Características Principales
Tratamiento de Datos Desbalanceados: Implementación de la técnica híbrida SMOTEENN para equilibrar la clase minoritaria y reducir el sesgo algorítmico.

Modelado Avanzado: Evaluación y optimización de algoritmos de ensamble (Random Forest y XGBoost).

Interpretabilidad (XAI): Uso de valores SHAP para cuantificar el impacto de cada variable en la decisión de abandono.

Alto Desempeño: Alcanza un Recall del 84% y un AUC-ROC de 0.86.

🛠️ Stack Tecnológico
Lenguaje: Python 3.12.4

IDE: Google Colab / Jupyter Notebooks

Librerías Clave:

pandas & numpy: Manipulación de datos.

scikit-learn: Pipeline de ML y métricas.

xgboost: Modelo de Gradient Boosting.

imbalanced-learn: Aplicación de SMOTEENN.

shap: Interpretabilidad del modelo.

seaborn & matplotlib: Visualización analítica.

📊 Dataset
El conjunto de datos contiene 7,043 registros y 21 variables, incluyendo:

Demografía: Género, jubilados, dependientes.

Servicios: Telefonía, internet (DSL/Fibra), seguridad online, soporte técnico.

Cuenta: Antigüedad (tenure), tipo de contrato, cargos mensuales y totales.

📈 Resultados y Hallazgos
Métrica de Éxito: Se logró identificar correctamente al 84% de los clientes que efectivamente abandonaron el servicio (Recall).

Drivers de Churn: Los factores con mayor impacto predictivo fueron:

El tipo de contrato (Mes a mes).

El uso de servicio de Fibra Óptica.

Los cargos mensuales elevados.

💻 Instalación y Uso
Clona este repositorio:

Bash
git clone https://github.com/tu-usuario/telecom-churn-prediction.git
Instala las dependencias necesarias:

Bash
pip install -r requirements.txt
Ejecuta el notebook en tu entorno local o cárgalo en Google Colab.

🖋️ Autor
Tu Nombre - Trabajo Final de Diplomado - Tu LinkedIn

¿Cómo usar este README?
Crea un archivo llamado README.md en la raíz de tu repositorio de GitHub.

Copia y pega el código anterior.

Personalización: Asegúrate de cambiar tu-usuario y tu-perfil por tus datos reales.

Imágenes: Si tienes las imágenes de tu matriz de confusión o el gráfico SHAP, súbelas a una carpeta llamada img en tu repo y actualiza los enlaces en el markdown.
