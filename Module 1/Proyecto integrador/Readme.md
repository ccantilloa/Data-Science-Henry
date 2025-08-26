# Proyecto integrador

## Conociendo al Cliente 360°: Datos, Opiniones y Tendencia

Formas parte de un proceso de selección técnica para el rol de Científico de Datos Junior en InsightReach.

InsightReach es una empresa de marketing digital especializada en campañas personalizadas para negocios locales. Con el crecimiento de su base de clientes y la expansión a nuevos mercados, la empresa busca optimizar su estrategia de segmentación para mejorar la efectividad de sus campañas.

Como postulante, tu desafío es demostrar tu capacidad para analizar, enriquecer e interpretar bases de datos complejas para generar recomendaciones accionables. Tu rol simula el trabajo de un profesional en un entorno real, donde deberás construir análisis sólidos, justificar decisiones y comunicar resultados de manera clara y estructurada.
Para ello, se ha diseñado un reto técnico dirigido a candidatos para el rol de Científico de Datos Junior, cuyo objetivo es demostrar su capacidad para integrar múltiples fuentes de datos, analizarlas y generar insights accionables


## Objetivos del PI
- Explorar y comprender estructuras de datos reales provenientes de fuentes diversas.
- Aplicar técnicas de limpieza y transformación de datos para preparar datasets para análisis.
- Utilizar librerías de Python como pandas, numpy, matplotlib y seaborn para realizar análisis exploratorio de datos (EDA).
- Conectar con una API externa (Yelp) para enriquecer un dataset con información contextual e implementar técnicas de web scraping para extraer datos relevantes de páginas web.
- Interpretar los resultados del análisis para generar recomendaciones accionables.
Documentar el proceso de análisis de forma clara, estructurada y reproducible.

### Avances / Notebooks
- Avance_EDA.ipynb
- Avance_API_Yelp.ipynb
- Avance_Analisis_Final.ipynb
### Documentación
- README.pdf / .docx (Pasos, resultados)
- Recomendaciones.pdf (Propuestas de segmentación)

 ### Entregable final: 
 El entregable debe ser una carpeta comprimida (.zip) con la siguiente estructura organizada: ProyectoM1_NombreEstudiante/


 ## Detalles de avances

 ### Avance 1
 Tareas:
 1. Cargar y explorar una base de datos de clientes. 
2. Filtrar la base de datos para un país específico. 
3. Realizar limpieza de datos, identificar valores nulos, duplicados y errores. 
4. Generar tablas básicas para entender la distribución de variables como género, duración de sesión, calificaciones, etc.
5. Comenzar a documentar en el notebook Avance_1_EDA.ipynb

Conocimientos necesarios:
- Lectura de archivos CSV con pandas
- Limpieza de datos (valores nulos, duplicados, tipos de datos)
- Python, numpy, pandas

### Avance 2
Tareas:
1. Conectarse a la API de Yelp para obtener información de negocios locales de una ciudad según el país seleccionado. 2. Extraer datos como nombre del negocio, categoría, calificación, número de reseñas, etc.  
3. Integrar esta información al análisis que se está realizando para una ciudad/país en específico. 
4. Documentar los resultados en Avance_2_API_Yelp.ipynb

Conocimientos necesarios:
- Uso de APIs REST
- Manejo de autenticación con claves API
- Manipulación de respuestas JSON
- Integración de datos externos con pandas
- Python, requests, pandas, Yelp fusion API

### Avance 3
Tareas:
1. Analizar los datos integrados (clientes, Yelp, tendencias externas) para identificar patrones relevantes que puedan guiar decisiones de marketing. 
2. Formular preguntas clave del negocio y responderlas con visualizaciones y análisis descriptivo. 
3. Elaborar recomendaciones basadas en los hallazgos.
4. Complementar el archivo Avance_1_EDA.ipynb

Conocimientos necesarios:
- analisis exploratorio de datos
- interpretacion de graficos y metricas
- Matplotlib, seaborn, python, numpy, pandas



