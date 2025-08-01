# Predicción de Calidad del Vino

Este proyecto aplica técnicas de Machine Learning supervisado para predecir la calidad de vinos tintos a partir de características físico-químicas. Utiliza el clásico dataset del Instituto Vinho Verde y busca equilibrar precisión, interpretabilidad y eficiencia computacional.

## Objetivos
- Construir un modelo reproducible para predicción multiclase.
- Explorar relaciones entre variables físico-químicas y la puntuación de calidad.
- Evaluar el impacto de la regularización, el escalado y la selección de atributos.
- Documentar el flujo completo de análisis con visualizaciones interpretativas.

## Tecnologías y herramientas
- Python, scikit-learn, pandas, matplotlib, seaborn
- Clasificadores como Random Forest y Gradient Boosting
- Métricas de evaluación: accuracy, F1-score, matriz de confusión
- Preprocesamiento escalable y modular

## Principales hallazgos
- **Random Forest** obtuvo la mayor precisión promedio (0.5973), destacándose por su capacidad para manejar relaciones no lineales y variabilidad en los datos.
- **Logistic Regression** (0.5678) mostró un rendimiento intermedio, capturando algunas estructuras útiles cuando las relaciones entre variables son lineales.
- **KNN** (0.5295) fue el modelo menos preciso, evidenciando sensibilidad al número de vecinos y al preprocesamiento.
- La evaluación multiclase sugiere que los modelos basados en ensamblaje tienen mayor capacidad de generalización y reducción de sobreajuste.

## Comparación de Modelos

| Modelo               | Precisión Promedio | Interpretación                          | Observaciones Clave                              |
|---------------------|--------------------|------------------------------------------|--------------------------------------------------|
| Random Forest        | **0.5973**         | No lineal, buena generalización          | Mejor desempeño gracias al ensamblaje de árboles |
| Logistic Regression  | 0.5678             | Lineal, eficiente en relaciones simples  | Modelo ligero y comprensible                     |
| KNN                  | 0.5295             | Basado en distancia, sensible al parámetro `k` | Dependiente del preprocesamiento y escalado     |

---

Este análisis puede extenderse fácilmente a otros productos alimenticios, y es ideal como base didáctica para explicar técnicas de clasificación y análisis exploratorio.

---

## 👤 Conéctate conmigo

[![Conectar en LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/daniel-araneda-yasic)

¿Eres reclutador o profesional del sector interesado en proyectos aplicados de Data Science, visualización de datos o inteligencia artificial eficiente?  
Este proyecto refleja mi enfoque técnico y comunicativo, y estoy abierto a oportunidades laborales, colaboración en equipos multidisciplinarios y desarrollo de soluciones prácticas y reproducibles.

📫 No dudes en contactarme para conversar sobre cómo puedo aportar valor desde la intersección entre análisis técnico, creatividad visual y documentación didáctica.
