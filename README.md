# eficiencia-energetica-edificios
Proyecto de Data Analytics: eficiencia energética en edificios con datos abiertos (UCI).
# Eficiencia energética en edificios: análisis con datos abiertos

Proyecto del curso Data Analytics en Gestión Industrial.
Integrantes:
- Daniel Felipe Trujillo Lugo 
- David Santiago Rincón Zabaleta


## Descripción
Análisis del dataset *Energy Efficiency* para identificar qué parámetros de diseño
explican la carga de calefacción y refrigeración de un edificio. Incluye ETL,
análisis exploratorio, clustering, clasificación, PCA y LDA, y una propuesta de
gestión para preseleccionar diseños eficientes.

## Datos
Tsanas, A. y Xifara, A. (2012). Energy Efficiency [Dataset]. UCI Machine Learning
Repository. DOI 10.24432/C51307. Licencia: [completar].
Los datos son simulados, no mediciones de edificios reales.

## Contenido
- `[Proyecto_Analisis].ipynb`: notebook con todo el análisis
- `ENB2012_data.xlsx`: datos originales
- `enb2012_limpio.csv`: datos después del ETL

## Cómo ejecutarlo
1. Abrir el notebook en Google Colab.
2. Subir `ENB2012_data.xlsx` a la carpeta `/content/` de Colab.
3. Ejecutar todas las celdas en orden (semilla aleatoria fija: 42).

## Herramientas
Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, Google Colab.

## Uso de inteligencia artificial
Siguiendo la política de integridad académica del curso, declaramos que se usó un asistente de IA (Claude, de Anthropic) como apoyo para estructurar el código del pipeline ETL y del modelado, proponer validaciones y variables derivadas, depurar errores y redactar borradores de las secciones del informe. Los resultados se obtuvieron ejecutando el código en Google Colab con nuestros datos, y las decisiones del proyecto (como el enfoque, el número de hipótesis y la elección del modelo) fueron revisadas y ajustadas por el equipo.
