# Segmentación Semántica en Imágenes Médicas Cerebrales

En este código se utiliza la base de datos [BraTS2020](https://www.kaggle.com/datasets/awsaf49/brats2020-training-data/data).

## Preparación de entorno

Para el uso de este código, es necesaria la creación y configuración de un entorno adecuado para no presentar fallas al momento de ejecutarlo. 
Para esto se necesita lo siguiente:
- Python 3.10
- h5py
- Matplotlib
- TensorFlow

## 



## Muestra de los datos

Para visualizar una muestra de como son los datos se necesita realizar lo sigueinte:
- Cargar el directorio de la base de datos. En este caso, se han colocado la base de datos en una carpeta y se accede a esta desde el código.
- Cargar los archivos dentro de un array para manipularlos (los archivos en esta base de datos se encuentran en formato H5).

- Se crean los siguientes métodos:
  - display_image_channels: Visualizar los 4 tipos de canales de las imágenes de resonancia magnética.
  - display_mask_channels_as_rgb: Visualizar las máscaras realizadas por los médicos especialistas de cada imagen de resonancia magnética en RGB.

- Analizar las dimensiones de los datos (los datos son de tamaño 240x240x4 y 240x240x3).
