# Estimación de Señal VPY a partir de Señal PPG

Este proyecto se enfoca en la **adquisición y procesamiento de señales PPG (fotopletismografía)** para la estimación de la señal VPY mediante análisis y caracterización utilizando la biblioteca **SciPy**.

Se realiza un análisis morfológico de los ciclos promedios de la señal PPG, seguido por un proceso de **detección de anomalías** empleando técnicas de **clustering con K-means** y **reducción de dimensionalidad mediante Análisis de Componentes Principales (PCA)**.

El enfoque combina herramientas clásicas de procesamiento de señales con algoritmos de **aprendizaje no supervisado** para la exploración de patrones fisiológicos y la identificación de irregularidades potenciales.

## Tecnologías utilizadas
- Python
- SciPy
- NumPy
- Matplotlib
- scikit-learn (K-means, PCA)

## Objetivos principales
- Estimar la señal VPY a partir de la señal PPG.
- Caracterizar los ciclos promedios usando herramientas de análisis de señales.
- Detectar anomalías utilizando técnicas de clustering no supervisadas.
