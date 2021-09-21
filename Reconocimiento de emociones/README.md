# Dectector de emociones con Python 

El siguiente entorno se desarrollo con las librerias 

- Tensorflow 2.4.1
- Keras 2.4.3

a continuacion indicare como realizar la preparación del entorno, en este caso puede usar la opcion directamente desde el conda navigator para crear un nuevo entorno virtual 

puedes llamarlo como tu prefeieras, si lo haces desde la consola deberias seguir los sigueinte pasos

### Creamos el entorno de trabajo 

***Esta parte no es necesaria si lo creas con el conda navigator, pero recuerda que debes usar la version de python 3.7***
~~~
conda create -n FaceEmotion
conda activate FaceEmotion
conda install python=3.7
~~~

### Instalación de las librerias

~~~
pip install tensorflow==2.4.1
pip install keras==2.4.3
pip install imutils opencv-python h5py
pip install matplotlib == 3.2.2
~~~

### Entrenamiento de la red neuronal

para entrenar el reconocedor, es necesario realizar los pasos que se encuentran en el archivo ***faceEmot.ipynb***, aunque ya en este caso no es necesario, puedo que el proceso de entrenamiento ya esta realizado y listo para usar, sin embargo puedes usar google colab para poder volver a entrenarlo o puedes usar tu computador, en lo personal recomiendo google colab, debido al proceso de computo que te facilita. 

con esto el modelo ya entrenado es el archivo ***modelFEC.h5*** , ya con esto el unico archivo que importa es el ***reconcimiento_emocion.ipynb*** el cual es el que contiene todo el proceso de detección de emociones, este ultimo archivo lo que hace es llamar a las caracteristicas para reconocimiento facial que estan en la carpeta face_detector. 

