# Ruta elegida y dataset:
Se eligió la ruta de detección de objetos.
El dataset está disponible en: https://www.kaggle.com/datasets/akhatova/pcb-defects
Autores: Huang, Weibo, and Peng Wei. "A PCB dataset for defects detection and classification." arXiv preprint arXiv:1901.08204 (2019).

# Cómo ejecutar
Se debe descargar manualmente el dataset, descomprimir y verificar que la ruta base es data/pcb-defects/PCB_DATASET.
Dentro de dicha carpeta deberían existir la carpeta images y Annotations.

Ejecutar en Jupyter (Visual Studio Code), previamente instalar las librerías en requirements.txt.

# Cómo entrenar y evaluar
Para entrenar basta con ejecutar los bloques de código dentro de la sección Entrenamiento. Previamente se deben haber generado el archivo yaml y haber separado las imágenes en los sets de entrenamiento y prueba (celdas anteriores).

Para evaluar, se debe haber corrido las celdas anteriores, las cuales generan los pesos correspondientes.

# Cómo generar la tabla y el gráfico de métricas
Ejecutar las celdas correspondientes de las secciones Evaluación y Guardado de resultados.
