# ProyFin1
Proyecto final de Tratamiento de datos
Se utilizaron las librerìas:
matplotlib, keras, seaborn, sklearn, tensorflow,numpy, cv2, os y sys
En primer lugar se importaron las librerìas mencionadas.
Se realizò la carga del dataset utilizando las etiquetas correspondientes a cada clase y la función get_data 
En la carga se uso la función imread y reaustò a 224 en tamaño
Se realizó una visualización de la información cargada por medio de la librería seaborn
Se preprocesaron las imágenes por medio de normalización, reshape y la función ImageDataGenerator
finalmente se utilizó el proceso fit

El modelo que se utilizó es CNN, con tres capas convolucionales y de maximización.
Se optimizó por medio de ADAM y se entrenó el modelo con 20 epochs
En la evaluación de resultados no se obtuvo los esperados pero se sigue trabajando en la mejora del código.
