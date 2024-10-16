# TP3: Detector de SPAM - CEIA - 18Co2024

## Integrantes

- a1805 Natalia Beatriz Diaz
- e1401 Martin Nicolas Duarte
- a1822 Cristian Patricio Salinas Talamilla
- a1812 Ezequiel Eduardo Maudet
- a1819 Manuel Pineyro

## Descripción general

Este proyecto implementa un clasificador de correos electrónicos SPAM utilizando modelos de Bayes ingenuo y Regresión Logística.

El objetivo es analizar un conjunto de datos de 4601 observaciones de correos electrónicos (2788 legítimos, 1813 spam) y construir modelos de aprendizaje automático para detectar correos spam. El proyecto explora técnicas de procesamiento de lenguaje natural, ingeniería de características y evaluación de modelos.

## Preguntas a resolver

1. ¿Cuáles son las 10 palabras más encontradas en correos con SPAM y en correos No SPAM? ¿Hay palabras en común? ¿Algunas llaman la atención?
2. Separe el conjunto de datos en un conjunto de entrenamiento y un conjunto de prueba (70% y 30% respectivamente).
3. Utilizando un clasificador de Bayes ingenuo, entrene con el conjunto de entrenamiento.
4. Utilizando un clasificador de Regresión Logística, entrene con el conjunto de entrenamiento (en este caso, normalice los datos).
5. Calcule la matriz de confusión del conjunto de evaluación para ambos modelos. ¿Qué tipo de error comete más cada modelo? ¿Cuál de los dos tipos de error crees que es más importante para este problema?
6. Calcule la precisión y la recuperación de ambos modelos. Para cada métrica, ¿cuál es el mejor modelo? ¿Cómo se relacionan estas métricas con los tipos de errores analizados en el punto anterior? Expanda su respuesta.
7. Obtenga la curva ROC y el AUC (Área Bajo la Curva ROC) de ambos modelos.

## Archivos

- `TP3_IA_Spam.ipynb`: Notebook de Jupyter con análisis e implementaciones de modelos
- `spambase.csv`: Conjunto de datos de características de correos electrónicos y etiquetas de spam
- `requirements.txt`: Dependencias de Python

## Uso

1. Instalar dependencias: `pip install -r requirements.txt`
2. Abrir y ejecutar `TP3_IA_Spam.ipynb` en Jupyter
