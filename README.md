![](https://github.com/viajatech/CIFAR10RUN/blob/main/Figure_1.png)
![](https://github.com/viajatech/CIFAR10RUN/blob/main/esquema%20CNN.png)

Este código hace lo siguiente:
Carga el modelo entrenado.
Define una función para preprocesar las imágenes.
Define una función para hacer predicciones.
Muestra un ejemplo de cómo usar el modelo con algunas imágenes del conjunto de prueba.
---------
Adjunto Archivo;
Modelo ya entrenado "H5" File .h5 (1.44MB) listo para usar. 
El modelo neuronal lo entrene con el conjunto de datos; The CIFAR-10 dataset (https://www.cs.toronto.edu/~kriz/cifar.html) 
Lo entrene con 10-epochs osea 10 épocas con las clases; 
['avión', 'automóvil', 'pájaro', 'gato', 'ciervo', 'perro', 'rana', 'caballo', 'barco', 'camión']

Estructura de la imagen:

La imagen muestra una cuadrícula de 5x5, con un total de 25 imágenes pequeñas.
Debajo de cada imagen hay un texto que indica dos cosas: la predicción del modelo y la etiqueta real (entre paréntesis).


Significado de los colores:

Texto verde: Indica que la predicción del modelo es correcta.
Texto rojo: Indica que la predicción del modelo es incorrecta.


Interpretación:

Cada imagen pequeña es una muestra del conjunto de datos CIFAR-10.
El modelo que entrenaste está intentando clasificar cada imagen en una de las 10 categorías posibles.
La palabra fuera del paréntesis es lo que el modelo predijo.
La palabra dentro del paréntesis es la categoría real de la imagen.


Ejemplos específicos:

Correctos (en verde):

Primera imagen: el modelo predijo "gato" y era realmente un gato.
Segunda imagen: el modelo predijo "barco" y era realmente un barco.


Incorrectos (en rojo):

Quinta imagen: el modelo predijo "ciervo" pero era realmente una rana.
Tercera imagen de la última fila: el modelo predijo "ciervo" pero era realmente un perro.




Rendimiento del modelo:

De las 25 imágenes mostradas, el modelo parece acertar en la mayoría de los casos (los textos en verde).
Sin embargo, hay varios errores (textos en rojo), lo que indica que el modelo no es perfecto.


Tipos de errores:

Algunos errores parecen más comprensibles que otros. Por ejemplo, confundir un ciervo con un perro podría deberse a similitudes en la forma o el entorno.
Otros errores son más notables, como confundir una rana con un barco.



Esta visualización es útil para entender cómo está funcionando tu modelo en la práctica. Te permite ver tanto sus aciertos como sus errores, lo que puede ayudarte a identificar áreas de mejora o entender las limitaciones del modelo.
