# Tesis Identificacion de ACPs - CNN
# CNN mediante 5FCV
 
## Carpetas:
- "Creación Bases de Datos (ACP - NoACP)" : Creación de las bases de datos a utilizar una vez las secuencias han sido procesadas mediante CD-Hit

- "Creación Datasets - Autoencoder - SVD - OneHot - K Mers" : Creación de los Datasets de Entrenamiento e Independiente con las distintas codificaciones y Features Sets seleccionados (AAC, DPC, PCP, Autoencoder con SVD, One Hot Encoding, K-mers Sparse Matrix)

- "Model Selection - 5FCV" (.ipynb): Selección del modelo previo a a la investigación (SVM - RF - CNN - LSTM)

- "TSNE - PCA" : Creación de figuras para cada método de tSNE y PCA

- "Reducción de Composición de Aminoácidos" (.py): Selección del grupo que reduzca la cantidad de aminoácidos en cada secuencia en base a su momento dipolar, momento hidrofóbico, polaridad, polarizabilidad y volumen de Van Waals.

- "ACP - Final Model" (.ipynb) : Entrenamiento, Testing y evaluación con Dataset Independiente del modelo seleccionado (CNN)
	- "Databases" : Bases de datos para Entrenamiento y Dataset Independiente
	- "SavedModel" : Modelos guardados después de la ejecución del modelo mediante 5 Fold Cross Validation
