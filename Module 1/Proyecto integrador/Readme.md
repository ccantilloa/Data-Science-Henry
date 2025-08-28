# 📊 Proyecto Integrador  
## Conociendo al Cliente 360°: Datos, Opiniones y Tendencia  

Este proyecto forma parte de un proceso de selección técnica para el rol de **Científico de Datos Junior en InsightReach**.  
El objetivo principal es demostrar la capacidad para **analizar, enriquecer e interpretar múltiples fuentes de datos**, generando insights y recomendaciones accionables para campañas de marketing digital personalizadas.  

---

## 🎯 Objetivos
- Explorar y comprender estructuras de datos reales provenientes de fuentes diversas.  
- Aplicar técnicas de limpieza y transformación de datos para preparar datasets para análisis.  
- Utilizar librerías de Python como **pandas, numpy, matplotlib y seaborn** para realizar análisis exploratorio de datos (EDA).  
- Conectar con la **API de Yelp** para enriquecer un dataset con información contextual.  
- Implementar técnicas de **web scraping** para extraer datos relevantes de páginas web.  
- Interpretar los resultados para generar **recomendaciones accionables**.  
- Documentar el proceso de forma clara, estructurada y reproducible.  

---

## 🗂️ Estructura del proyecto

El entregable final debe organizarse en una carpeta comprimida


---

## 🚀 Flujo de ejecución

Para asegurar reproducibilidad y coherencia en los análisis, **ejecutar los avances en el siguiente orden**:  

1. **Avance_1_EDA.ipynb**  
   - Carga y exploración inicial de la base de datos de clientes.  
   - Limpieza de datos: manejo de nulos, duplicados y tipos de variables.  
   - Tablas y visualizaciones básicas.  

2. **Avance_2_API_Yelp.ipynb**  
   - Conexión con la API de Yelp (requiere clave de autenticación).  
   - **Antes de ejecutar este notebook:**  
     - Crear un archivo `.env` en la raíz del proyecto con las credenciales necesarias.  
     - El archivo debe contener las variables de entorno para el `CLIENT_ID` y `API_KEY`.  
     - Se incluye un archivo **`.env.example`** que muestra el formato correcto.  
   - Extracción de datos de negocios (nombre, categoría, calificación, reseñas).  
   - Integración con la información de clientes para contextualizar resultados.  

3. **Avance_3_Analisis_Final.ipynb**  
   - Análisis exploratorio integrado (clientes + Yelp + tendencias externas).  
   - Visualizaciones y métricas para responder preguntas clave de negocio.  
   - Generación de insights finales.  

---

## 📑 Documentación y Entregables

- **README.md / README.pdf**  
  Este archivo, con instrucciones claras sobre el proyecto, objetivos y flujo de trabajo.  

- **Recomendaciones.pdf**  
  Documento que resume los hallazgos más relevantes y contiene propuestas concretas de segmentación, estrategias de marketing y optimización de campañas.  

- **Notebooks (Avance_1, Avance_2, Avance_3)**  
  Contienen el desarrollo técnico, análisis exploratorio, integración de datos y generación de visualizaciones.  

- **.env.example**  
  Ejemplo de archivo de configuración de entorno para almacenar las credenciales necesarias (no subir el archivo `.env` real con claves a repositorios públicos).  

---

## 🛠️ Requisitos técnicos

- **Python 3.8+**  
- Librerías necesarias:  
  ```bash
  pip install pandas numpy matplotlib seaborn requests python-dotenv

