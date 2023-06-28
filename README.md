# Detección de humanos y trackeo para DeepAgro

Las librerias necesarias para el funcionamiento son:

NumPy

OpenCV

dlib

imutils

Se utilizan las técnicas de Object Detection y Object Tracking
La primer técnica para detectar el objeto, que se corre cada x cantidad de frames para que sea computacionalmente lo más eficiente posible
Y la segunda para trackear o seguir el objeto detectado durante los frames en los que la detección está pausada.



Para la detección usaremos un modelo SSD, MobileNet Single Shot Detector (SSD) y para el trackeo las librerías de OpenCV y dlib
Para el trakeo usaremos la box proporcionada por la detección para determinar el centro

![image](https://github.com/MMontagna1109/DeepAgro/assets/79583734/2c25e69b-6a77-4788-973e-ef7c619906aa)
