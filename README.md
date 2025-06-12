
# Predicción de Accidentes Cerebrovasculares (ACV): Un Enfoque en la Equidad

## 🚀 Objetivo del Proyecto
Este proyecto busca desarrollar un modelo de Machine Learning para predecir la probabilidad de que una persona sufra un Accidente Cerebrovascular (ACV), utilizando un conjunto de variables clínicas y socioeconómicas.

Más allá del rendimiento técnico, nuestro pilar fundamental es la equidad. Evaluaremos meticulosamente el modelo para garantizar que no reproduzca ni amplifique sesgos en sus predicciones, especialmente en relación con el género y la condición laboral. Nuestro fin último es contribuir a la mejora de la prevención en salud pública y la reducción de las desigualdades sanitarias.

## 🤝 Colaboración y Carácter del Proyecto
Este proyecto fue desarrollado de manera colaborativa por un equipo de trabajo, aplicando diversas técnicas de Machine Learning y explorando herramientas avanzadas para la gestión de modelos como ML FLOW y tecnicas aplicadas como resampling.
https://github.com/Data-Dinasty/Data-Dinasty_TSDCIA_ISPC-PPII 

Importante: Este proyecto tiene un carácter exclusivamente educativo y de aprendizaje. El modelo desarrollado no debe ser utilizado para diagnósticos médicos reales ni para la toma de decisiones clínicas. La responsabilidad final del diagnóstico recae siempre en un profesional de la salud.



## 🎯 Alcance del Proyecto
Este repositorio documenta el ciclo de vida de nuestro proyecto, que incluye:

Uso del Dataset: stroke-prediction.
Análisis Exploratorio de Datos (EDA): Investigación de variables clínicas y demográficas.
Desarrollo de Modelos: Creación de soluciones de clasificación supervisada.
Evaluación Técnica: Medición del rendimiento del modelo con métricas clave (precisión, AUC, recall, etc.).
Evaluación de Equidad (Fairness): Análisis de posibles sesgos utilizando métricas específicas de fairness.
Documentación y Seguimiento: Gestión del proceso a través de GitHub y la metodología TDSP.
Exclusiones Notables:

Implementación directa en entornos clínicos hospitalarios.
Recolección de nuevos datos o integración con sistemas sanitarios locales.
Diagnóstico médico en tiempo real por el modelo (siempre es una herramienta de apoyo).

## 💡 Metodología
Para estructurar nuestro trabajo, hemos adoptado la metodología TDSP (Team Data Science Process). Este enfoque nos guía a través de fases iterativas como: entendimiento del negocio, exploración de datos, modelado, validación y evaluación.

Utilizamos herramientas robustas como Python, Scikit-learn, MLflow (si se usa realmente para trackear) y Fairlearn para asegurar tanto un desarrollo técnico sólido como una revisión exhaustiva de los posibles sesgos del modelo.

## 📊 Justificación del Dataset y Pregunta Central
Dataset Elegido: Stroke Prediction Dataset
La elección de este dataset se fundamenta en su significativo impacto social. El ACV es una causa global de muerte y discapacidad, y la predicción temprana puede facilitar intervenciones, mejorar la calidad de vida y reducir costos.

Además, el dataset contiene variables sensibles (género, edad, etc.), lo que nos permite ir más allá de la simple predicción y analizar críticamente los sesgos algorítmicos, un pilar de este proyecto para asegurar la equidad.

Pregunta de Negocio (Business Question):
"¿El modelo de predicción de ACV tiene un desempeño equitativo entre géneros y grupos socioeconómicos, además de ser clínicamente útil?"

Esta pregunta guía nuestra investigación, enfocándonos tanto en la precisión predictiva (clasificación binaria: ¿tendrá ACV o no?) como en el análisis de equidad usando métricas de Fairlearn.


