# TratamientoDatos

Nombre: Jorge Sampedro

Clasificación de imágenes luego de procesarlas.

En este archivo se crea una red Red Neuronal Convolucional con Keras y Tensorflow utilizando Jupyter Notebook con el objetivo de reconocer y clasificar una base de datos.

Por el tipo de imágenes que posee la base de datos se consideró el CNN como el mejor método para llevarlo a cabo.
Debido a que por medio de las convoluciones nos permite tratar las imágenes como una matriz, a la vez segmentar y comparar segmentos de la imagen para buscar similitudes que para el ojo humano son imperceptibles.
Se hace una normalización para trabajar las imágenes con valores entre 0 y 1, de esta forma se cree que el modelo puede ser algo más efectivo y no causar overfitting al usar demasiados valores.
Con el modelo que se busca aplicar las primeras convoluciones se ocuparán de detectar características un poco básicas como líneas o curvas. Precisamente se escoge este modelo porque entre más convoluciones se hagan, características más complejas se podrán detectar.
Este método usa el comportamiento del ojo humano por lo que también se ha considerado útil para este proyecto.
