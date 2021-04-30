# Rastreo en tiempo real para rehabilitación virtual

## Equipo: Dream Power

### Planteamiento

Actualmente el Kinect brinda mucha información con sus sensores, estas pueden ser transformadas en distintas estructuras de datos y se leen para convertir la realidad en un modelo digital. Con este modelo y con un sistema de reconocimiento de gestos, se puede reconocer que tipo de cosas o movimientos se están realizando.

Gracias a este tipo de reconocimiento de movimientos, se decidió hacer un videojuego que funcione como un metodo de entretenimiento y también como un metodo de rehabilitación. Para lograr lo anterior, se planea hacer un prototipo de esto.

El prototipo consistirá en un compilador de instrucciones de gestos que reconocerá el Kinect. Sobre esas instrucciones de movimientos el modelo del jugador se verá afectado y realizará las acciones correspondientes. Este tipo de rehabilitación está pensada para sesiones en las que no sea indispensable consultar al médico directamente y que este mismo, pueda dejar como trabajo en casa pasar algún nivel o reto.

Para lograr eso, el tiempo de respuesta del Kinect y del juego tiene que ser muy corto y también tiene que ser eficiente, ya que no nos podemos dar el lujo de que se ejecute en computadoras de último modelo. Se necesita correr en un amplio rango de computadoras o consolas. Por lo cual, se requiere reducir el tiempo de repuesta en donde se pueda.

Un área de oportunidad que se observó fue en el manejo de datos del Kinect. Debido a que este para hacer ciertas cosas para las que está diseñado, no requiere de todos sus componentes. Entonces lo que se desea resolver es verificar que datos del Kinect nos son útiles, cuales procesa y como poder evitar el proceso o la captura de los demás datos para así ahorrar tiempo de respuesta y tiempo de procesamiento en el procesador.

La hipótesis que se tiene es que el tiempo de recolección de datos y procesamiento para este proyecto, puede ser reducido. Para lograr esta reducción, se plantea solo utilizar los sensores indispensables del Kinect para la funcion que se desea que tenga. En este caso, se propone que solamente utilizando el emisor IR y el sensor de profundidad IR, se va a poder lograr la lectura deseada, evitando así el procesamiento de los demás datos e información. Con esto se mejorará el rendimiento en tiempo de ejecución y hará más eficaz el procesamiento de datos.
