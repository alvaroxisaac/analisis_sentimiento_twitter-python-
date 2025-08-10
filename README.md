Análisis de Sentimientos en Tweets sobre Salud 🏥📊
📝 Descripción
Este proyecto realiza un análisis de sentimientos de tweets relacionados con temas de salud utilizando Python y técnicas de procesamiento de lenguaje natural (NLP). El objetivo es identificar y visualizar las tendencias de opinión pública sobre temas de salud en Twitter.
🎯 Objetivos

Analizar sentimientos en tweets sobre salud usando TextBlob
Comparar diferentes métodos de clasificación de sentimientos
Visualizar tendencias y patrones en las opiniones sobre salud
Identificar palabras clave asociadas con cada tipo de sentimiento

🛠️ Tecnologías Utilizadas

Python 3.x
Pandas - Manipulación y análisis de datos
TextBlob - Procesamiento de lenguaje natural y análisis de sentimientos
Matplotlib/Seaborn - Visualización de datos
WordCloud - Generación de nubes de palabras
NumPy - Operaciones numéricas
Scikit-learn - Preprocesamiento de texto

📊 Dataset

Fuente: Sentiment140 Dataset
Tamaño total: 150,000 tweets
Tweets analizados sobre salud: 183
Período: Datos históricos de Twitter

🔍 Metodología
1. Preprocesamiento de Datos

Normalización a minúsculas
Eliminación de URLs, menciones y hashtags
Tokenización y eliminación de stopwords
Filtrado por términos relacionados con salud

2. Análisis de Sentimientos

TextBlob: Análisis de polaridad y subjetividad
Clasificación original: Comparación con etiquetas del dataset
Métricas: Polaridad (-1 a 1) y subjetividad (0 a 1)

3. Visualizaciones Generadas

Distribución de sentimientos originales vs TextBlob
Análisis de polaridad y subjetividad
Evolución temporal de sentimientos
Nubes de palabras por tipo de sentimiento
Análisis de usuarios más activos

📈 Resultados Principales
Distribución de Sentimientos (TextBlob)

Neutral: 63.7% (117 tweets)
Positivo: 29.0% (53 tweets)
Negativo: 7.3% (13 tweets)

Insights Clave

La percepción general sobre salud en Twitter es NEUTRAL/MIXTA
Las opiniones están balanceadas entre positivas y negativas
Palabras más frecuentes: "health", "medical", "care", "work", "really"
Los usuarios con sentimientos extremos (positivos/negativos) tienden a ser más subjetivos
