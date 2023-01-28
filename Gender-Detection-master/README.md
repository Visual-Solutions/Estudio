#  Repositorio para detectar el genero
Para hacer funcionar este repositorio se requiere los siguiente:

## Descargar muestra de fotos

La carpeta 
[gender_dataset_face](https://drive.google.com/drive/folders/1qWGbGvdgH2IRhbGg8bpjT6MtQCyUe42j?usp=share_link), debe ser rellenada con la carpeta del siguiente link:
> https://drive.google.com/drive/folders/1qWGbGvdgH2IRhbGg8bpjT6MtQCyUe42j?usp=share_link

## Librerias a instalar en python
- tensorflow
>pip install  tensorflow
- sklearn
> pip install scikit-learn
- matplotlib 
>pip install matplotlib
- numpy 
>pip installnumpy
- random 
>pip installrandom
- cv2
<!-- >conda install --channel https://conda.anaconda.org/menpo opencv3 -->
>opencv-python==3.4.3.18
>opencv-contrib-python==3.4.3.18
os 
>viene de fabrica
glob
>pip install glob2
cvlib
>pip install cvlib

pip install Keras-Preprocessing

--------------------------------

## Ejecución:

### Entrenar el modelo

Tras realizar la carga de información e instalar las librerias  se debe entrenar el modelo, en este caso ya se encuenta entrenado, ya que existe el archivo **gender_detection.model**. Para entrenarlo se debe ejecutar el archivo **train.py**.

### Realizar predicción en tiempo real

Ya con el archvio **gender_detection.model** creado se puede realizar la ejecución del archivo **detect_gender_webcam.py**, el cual desplegará una ventana con la predicción de genero en tiempo real.