# Videos Virales: Factores que Contribuyen a la Viralidad

## 📈 Descripción
Este proyecto analiza los factores clave que contribuyen a la viralidad de videos en YouTube. Utilizando la **API de YouTube**, técnicas de **análisis de datos**, **visualización** y **modelado de tópicos con BERTopic**, se exploran categorías de contenido, etiquetas, títulos, descripciones, patrones temporales y dinámicas de interacción para identificar qué hace que un video se vuelva viral.

## 🎯 Pregunta de Investigación
**¿Qué factores contribuyen a la viralidad de un video en YouTube, y cómo se relacionan las características del contenido con la interacción de los usuarios y los patrones de visualización?**

## 🔍 Objetivos Específicos
- Identificar las categorías de contenido más comunes en videos virales.
- Analizar la influencia de etiquetas y calidad de video en la viralidad.
- Evaluar patrones específicos en videos aptos para niños.
- Explorar la longitud y los términos comunes en títulos y descripciones.
- Determinar los horarios y días óptimos para publicar videos.
- Aplicar **BERTopic** para identificar temas predominantes en videos virales.

## 🛠️ Herramientas Utilizadas
- **Lenguaje:** Python
- **Bibliotecas:**
  - `pandas`, `numpy` para manipulación de datos
  - `matplotlib`, `seaborn` para visualización
  - `nltk`, `re` para preprocesamiento de texto
  - `TextBlob` para análisis de sentimientos
  - `BERTopic` para modelado de tópicos
  - `WordCloud` para nubes de palabras
  - `googleapiclient` para conexión con la API de YouTube

## 📅 Metodología
1. **Recolección de Datos:**
   - Datos obtenidos a través de la **API de YouTube** (15 de octubre - 15 de noviembre de 2024).
   - Se recopilaron vistas, likes, comentarios, etiquetas, títulos, descripciones, duración, idioma y más.

2. **Limpieza y Preprocesamiento:**
   - Manejo de datos nulos y vacíos.
   - Preprocesamiento de texto con `nltk` y expresiones regulares.

3. **Análisis de Datos:**
   - Análisis descriptivo con histogramas y gráficos de barras.
   - Evaluación de categorías, etiquetas, títulos y descripciones.
   - Análisis temporal de horarios y días de publicación.

4. **Modelado de Tópicos:**
   - Uso de **BERTopic** para identificar temas predominantes en videos virales.
   - Visualización de temas y relaciones semánticas.


## 📂 Estructura del Proyecto
```
📦 youtube-viral-analysis
 ├── 📁 data            # Datos crudos y procesados
 ├── 📁 notebooks       # Notebooks de Jupyter
 ├── 📁 src             # Scripts de Python
 ├── 📄 README.md       # Documentación del proyecto
 └── 📄 Informe.pdf     # Informe completo del análisis
```

## 📧 Autores
Juan Torres, Juliana Rubio y Julián Páez
