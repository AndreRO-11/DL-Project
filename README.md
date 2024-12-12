# Segmentación Semántica de Tumores Cerebrales

En este código se utiliza la base de datos [BraTS2020](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data/data).

### Primeros pasos
1. Se inportan las dependencias correspondientes para el modelo.
2. Se carga el directorio de la base de datos.
3. Cargar los archivos en un array para poder manipularlos (los archivos de esta base de datos se encuentran en .h5).
4. Analizar las dimensiones de los datos (los datos son de tamaño 240x240x4 y 240x240x3).

### Visualización de los datos
Creación de los métodos:
- display_image_channels: Visualizar los 4 tipos de canales de las imágenes de resonancia magnética.
- display_mask_channels_as_rgb: Visualizar las máscaras realizadas por los médicos especialistas de cada imagen de resonancia magnética en RGB.

### Manipulación de los datos
- Se dividen los datos en datos de entrenamiento y validación.
- Se generan cargadores de estos datos para que los datos de entrenameinto sean al azar.

