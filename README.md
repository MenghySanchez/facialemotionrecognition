# Reconocimiento Facial con OpenCV y Python

Este es un pequeño programa para el reconocimiento facil usado Jupiter Lab y la libreria de OpenCV

El sistema de divide en varias partes de forma escalable, cada carpeta contine un funcionalidad que va aumentando su utilidad. 

## Carpetas del repositorio

  ### Detección de rostros
    Esta carpeta contine el algoritmo base para hacer una detección del rostro a partir de una imagen cargada

  ### Save face of picture
    En esta otra caprta se aumenta la funcionalidad de almacenar el rostro detectado en una imagen, en una carpeta adicional.

  ### Face detection in video
    En esta se agrego la capacidad de extraer rostros de un video en vivo, o un video precargado; 
    las imagenes de los rostros detectados seran almacenados en otra carpeta


## Modo de Ejecución

Para su ejecución es necesario instalar Conda o en su version de Windows Anaconda3 : https://anaconda.org/ 
tambien es necesario instalar la libreria OpenCV para anaconda, puedes usar la guia de Conda: https://anaconda.org/search?q=opencv , puedes seleccionar la version que se adapte a tu instalación, yo utilice esta version: https://anaconda.org/conda-forge/opencv

Una vez tengas instalado los requerimientos, ya podras descargar el repositorio y ejecutar el archivo con la extención: ipynb

Complentado la primera parte y una vez comprendido el funcionamiento basico del programa ya podemos hacernos de la idea de como se debe continuar. 
Para esto es necesario el usar un metodo de aprendizaje automativo que nos permita obtener un modelo de reconocimiento de emociones, en este caso entrenamos nuestro modelo con la ayuda de una herramienta online como lo es Google Colab, en donde haremos el entrenamiento del modelo. 

***Los archivos o codigos de esta parte del proyecto se encuentran en la carpeta: Reconocimiento_emociones*** , en ella estan las instrucciones de como replicar el proceso y tambien encontraran el codigo de reconocimiento de emociones. 

Para esta ultima parte sera necesario crear un nuevo entorno de trabajo virtual. ![image](https://user-images.githubusercontent.com/47823011/134160534-70cb3463-22f1-44c3-a940-571df499d189.png),  en mi caso lo desgine Emotion_recognition y dentro de ese entorno instale las siguiente librerias: 

Es importante mencionar que el nuevo entorno que creemos debe poseer la version 3.7 de python para no tener problemas: ![image](https://user-images.githubusercontent.com/47823011/134160917-1900c898-ea7b-4611-8814-2540d94d658f.png)

~~~
pip install tensorflow==2.4.1
pip install keras==2.4.3
pip install imutils opencv-python h5py
pip install matplotlib == 3.2.2
~~~

Una vez que se instalaen las librerias podemos proceseguir con las intrucciones dentro de la carpeta mencionada

