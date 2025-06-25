
# 📊 Análisis de Rendimiento Estudiantil

Este proyecto analiza datos reales de estudiantes para descubrir cómo los hábitos diarios (estudio, sueño, ejercicio, redes sociales) y factores de bienestar (salud mental, tiempo libre) influyen en el rendimiento académico.

---

## 🚀 Objetivos

- Identificar **patrones de comportamiento estudiantil** mediante técnicas de clustering (K-Means + PCA).
- Predecir el nivel de rendimiento académico (**Alto**, **Medio**, **Bajo**) usando modelos de Machine Learning.
- Evaluar la relación entre **tiempo libre**, **salud mental** y **puntajes de examen**.
- Crear visualizaciones limpias y educativas para compartir en **redes profesionales**.

---

## 📁 Estructura del Proyecto

- `Performance estudiantes.ipynb`: Notebook principal con análisis exploratorio, clustering, clasificación y visualizaciones.
- `student_data_etl_limpio.xlsx`: Dataset limpio utilizado como entrada.
- `carrusel_linkedin_estudiantes.zip`: Kit visual listo para publicar en LinkedIn.
- `README.md`: Documentación general del proyecto.

---

## 🧠 Herramientas y Librerías

- **Python 3**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` (PCA, KMeans, Random Forest)
- `joblib` (opcional para exportar modelos)

---

## 📌 Principales Hallazgos

✅ Los factores más influyentes en el rendimiento:
- Horas de estudio por día
- Ratio estudio/sueño
- Salud mental

📊 Clustering reveló **3 perfiles estudiantiles** con patrones distintos de comportamiento.

📉 El exceso de tiempo libre **no garantiza mejor salud mental**, pero sí puede afectar negativamente el rendimiento.

---

## 💬 ¿Cómo usar este proyecto?

1. Cloná este repositorio o descargá el `.ipynb`.
2. Asegurate de tener instaladas las librerías necesarias:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
