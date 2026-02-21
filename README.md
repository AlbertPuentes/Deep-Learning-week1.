# Deep-Learning-week1.
Ejercicio practico: Entiende una neurona en 15 minutos (Red 'vainilla')
#Pregutas
El bias actúa como un "umbral de dificultad". RTA: Si el valor de b define un umbral para la neurona donde el valor mas cercano a 0 la neurona se activca mas facilmente y en valores que se alejan del 0 la neurona tiene mas dificultad para activarse.
Si el bias tiene un valor negativo muy bajo, para la neurona es mas dificil activarse. RTA: Si va a ser mas dificil activarse para la neurona
Si el bias es alto cerca al 0, para la neurona es mas facil activarse. RTA: La neurona se activa con mas facilidad.

Para una compuerta AND, la salida sera 1 solo cuando ambas entradas son de valor 1.

1. Valor de b = -0.5 
En este caso para cada entrada obtenemos la siguiente salida 
  Entrada=(0,0) z=-0.5 salida=0
  Entrada=(0,1) z=0.5 salida=1
  Entrada=(1,0) z=0.5 salida=1
  Entrada=(1,1) z=1.5 salida=1
Analisis de la respuesta: Para b = -0.5 no se obtiene aun el comportamiento de la compuerta AND, ya que con las entradas (1,0) y (0,1) tambien se obtiene de salida 1, por lo que con este valor de b, la neurona aun no se comporta como la Compuerta AND que se busca.

2. Valor de b = -1 
En este caso para cada entrada obtenemos la siguiente salida 
  Entrada=(0,0) z=-0.5 salida=0
  Entrada=(0,1) z=0.5 salida=1
  Entrada=(1,0) z=0.5 salida=1
  Entrada=(1,1) z=1.5 salida=1
Analisis de la respuesta: Para b = -1 no se obtiene aun el comportamiento de la compuerta AND, ya que con las entradas (1,0) y (0,1) tambien se obtiene como  salida 1, por lo que con este valor de b, la neurona aun no se comporta como la Compuerta AND que se busca.

3. Valor de b = -1.5
En este caso para cada entrada obtenemos la siguiente salida 
  Entrada=(0,0) z=-1.5 salida=0
  Entrada=(0,1) z=-0.5 salida=0
  Entrada=(1,0) z=-0.5 salida=0
  Entrada=(1,1) z=0.5 salida=1
Analisis de la respuesta: Para b = -1.5 se obtiene el comportamiento de la compuerta AND, por lo que con este valor de b, la neurona se comporta como la Compuerta AND que se busca.

4. Valor de b = -2 
En este caso para cada entrada obtenemos la siguiente salida 
  Entrada=(0,0) z=-2.0 salida=0
  Entrada=(0,1) z=-1.0 salida=0
  Entrada=(1,0) z=-1.0 salida=0
  Entrada=(1,1) z=0.0 salida=1
Analisis de la respuesta: Para b = -2 aun se obtiene el comportamiento de la compuerta AND, por lo que con este valor de b, la neurona se comporta como la Compuerta AND que se busca, y se evidencia que este es el valor limite en el que se obtiene este resultado.

5. Valor de b = -2.1 
En este caso para cada entrada obtenemos la siguiente salida 
  Entrada=(0,0) z=-2.1 salida=0
  Entrada=(0,1) z=-1.1 salida=0
  Entrada=(1,0) z=-1.1 salida=0
  Entrada=(1,1) z=-0.1 salida=0
Analisis de la respuesta: Para b = -2.1 ya no se obtiene el comportamiento de la compuerta AND, por lo que se confirma que el valor limite del comportamiento de la neurona como compuerta AND es -2.
