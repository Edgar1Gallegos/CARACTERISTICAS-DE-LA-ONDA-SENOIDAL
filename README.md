# CARACTERISTICAS-DE-LA-ONDA-SENOIDAL

1. PLANTEAMIENTO DEL PROBLEMA 


2. OBJETIVOS


3. MARCO TEÓRICO 

Las ondas senoidales son patrones de ondas que matemáticamente pueden ser descritas mediante las funciones seno y coseno. Describen acertadamente eventos naturales y señales variables en el tiempo, tales como los voltajes generados por centrales eléctricas y luego utilizados en hogares, industrias y calles. Elementos eléctricos como resistencias, condensadores e inductancias, que se conectan a entradas de voltaje sinusoidal, producen respuestas también sinusoidales. Las matemáticas que se utilizan en su descripción son relativamente sencillas y han sido minuciosamente estudiadas.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal1.jpg)
Figura 1(Una onda senoidal con algunas de sus principales características espaciales: amplitud, longitud de onda y fase.)

Partes:

Período: Una función periódica como las mencionadas, la cual se repite a intervalos regulares, cumple siempre la siguiente propiedad:
f (t) = f (t+ T) = f (t + 2T) = f (t + 3T) = ….
Donde T es una cantidad denominada período de la onda, y es el tiempo que tarda en repetirse una fase de la misma. En unidades de Sistema Internacional, el período se mide en segundos.

Amplitud: De acuerdo a la expresión general de la onda senoidal v (t) = vm sen (ωt+φ), vm es el valor máximo de la función, que ocurre cuando sen (ωt+φ)= 1 (recordando que el mayor valor que admite tanto la función seno como la función coseno es 1). Este valor máximo es justamente la amplitud de la onda, también conocida como amplitud pico. En caso de tratarse de un voltaje se medirá en Voltios y si es una corriente será en Amperios. En la onda senoidal mostrada la amplitud es constante, pero en otros tipos de onda la amplitud puede variar.

Ciclo: Es una parte de la onda contenida en un período. En la figura anterior se tomó el período midiéndolo desde dos cimas o crestas consecutivas, pero puede comenzar a medirse desde otros puntos de la onda, mientras estén limitados por un período. Obsérvese en la siguiente figura como un ciclo abarca desde un punto hasta otro con el mismo valor (altura) y la misma pendiente (inclinación).

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal2.JPG)
Figura 2(En una onda senoidal, un ciclo siempre transcurre durante un período. Lo importante es que el punto de inicio y el final estén a la misma altura.)

Frecuencia: Es la cantidad de ciclos que ocurren en 1 segundo y se encuentra vinculada al argumento de la función seno: ωt. La frecuencia se denota como f y se mide en ciclos por segundo o Hertz (Hz) en Sistema Internacional.

La frecuencia es la cantidad inversa del período, por lo tanto:
f = 1/T
Mientras que la frecuencia f está relacionada con la frecuencia angular ω (pulsación) como:
ω = 2πf
La frecuencia angular se expresa en radianes /segundo en el Sistema Internacional, pero los radianes son adimensionales, así la frecuencia f y la frecuencia angular ω tienen las mismas dimensiones. Obsérvese que el producto ωt da radianes como resultado, debiendo tenerse en cuenta a la hora de utilizar la calculadora para obtener el valor de sen ωt.

Fase: Se corresponde al desplazamiento horizontal experimentado por la onda, respecto a un tiempo tomado como referencia. En la siguiente figura la onda verde está adelantada respecto a la roja en un tiempo td. Dos ondas sinusoidales están en fase cuando su frecuencia y su fase son las mismas. Si la fase difiere, entonces están en desfase. Las ondas de la figura 2 también están desfasadas.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal6.JPG)
Figura 3(Ondas senoidales desfasadas.)

Generador de onda senoidal, hay muchas formas de obtener una señal en forma de onda senoidal. Las tomas de corriente caseras las proporcionan.

1) Aplicación de la ley de Faraday
Una forma bastante simple de obtener una señal senoidal es haciendo uso de la ley de Faraday. Esta indica que en un circuito cerrado de corriente, por ejemplo una espira, colocado en medio de un campo magnético, se genera una corriente inducida cuando el flujo de campo magnético a través de ella cambia en el tiempo. En consecuencia se genera igualmente un voltaje inducido o fem inducida. El flujo del campo magnético varía si la espira se hace girar con rapidez angular constante en medio del campo creado entre los polos N y S del imán mostrado en la figura.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal3.JPG)
Figura 4(Generador de onda basado en la Ley de inducción de Faraday.)

La limitación de este dispositiva es la dependencia que tiene el voltaje obtenido con la frecuencia de rotación de la espira, como se verá con mayor detalle en el ejemplo 1 de la sección de ejemplos más adelante.

2) Oscilador de Wien
Otra forma de obtener una onda senoidal, esta vez con electrónica, es mediante el oscilador de Wien, que requiere de un amplificador operacional en conexión con resistencias y condensadores. De esta forma se obtienen ondas senoidales cuya frecuencia y amplitud el usuario puede modificar según su conveniencia, mediante el ajuste con interruptores. En la figura se muestra un generador de señales senoidales, con el cual también se pueden obtener otras formas de onda: triangulares y cuadradas entre otras.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal4.JPG)
Figura 5( Un generador de señales.)

¿Cómo calcular las ondas senoidales?

Para realizar cálculos que involucren ondas senoidales se utiliza una calculadora científica que disponga de las funciones trigonométricas seno y coseno, así como sus inversas. Estas calculadoras disponen de modos para trabajar los ángulos ya sea en grados o en radianes, y es sencillo convertir de una forma a la otra. El factor de conversión es:

180 º = π radianes.

Según el modelo de la calculadora, deberá navegar mediante la tecla MODE para encontrar la opción DEGREE, que permite trabajar las funciones trigonométricas en grados, o bien la opción RAD, para trabajar directamente los ángulos en radianes.

Por ejemplo sen 25 º = 0.4226 con la calculadora puesta en modo DEG. Al convertir 25 º a radianes se obtiene 0.4363 radianes y sen 0.4363 rad = 0.425889 ≈ 0.4226.

El osciloscopio es un aparato que permite visualizar en una pantalla señales de voltajes y corrientes tanto alternas como directas. Tiene perillas para ajustar el tamaño de la señal sobre una cuadrícula como se muestra en la siguiente figura:

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/onda-senoidal5.JPG)
Figura 6(Una señal sinusoidal medida con un osciloscopio.)

A través de la imagen que provee el osciloscopio y conociendo el ajuste de la sensibilidad en ambos ejes, es posible calcular los parámetros de la onda que se describieron anteriormente.

En la figura se muestra la señal de voltaje senoidal en función del tiempo, en la cual cada división del eje vertical vale 50 milivoltios, mientras que en el eje horizontal, cada división vale 10 microsegundos.

La amplitud pico a pico se encuentra contando las divisiones que abarca la onda en lo vertical, ayudándose con la flecha roja:

Se cuentan 5 divisiones con ayuda de la flecha roja, entonces el voltaje pico-pico es:

Vpp = 5 divisiones x 50 mV/división = 250 mV.

El voltaje pico Vp se mide a partir del eje horizontal, siendo de 125 mV.

Para encontrar el período se mide un ciclo, por ejemplo el delimitado por la flecha verde, que abarca 3.2 divisiones, entonces el período es:

T = 3.2 divisiones x 10 microsegundos/división = 32 microsegundos = 32 μs


4. DIAGRAMAS

Circuito Eléctrico


Fig 2. Circuito eléctrico

Descripción del circuito

* En el diagrama se observa dos fuentes independientes de voltaje, conectadas a los extremos del circuito.
* Además, dentro del circuito se aprecia 4 resistencias medidas en KOhms y Ohms.
* Al momento de unir dos elementos eléctricos, se forman nodos que para el caso del circuito de la práctica reconocemos 3 nodos principales.
* Se tiene que la resistencia de 1 KOhm forma nodo con las resistencias de 820 Ohm y 2.2 KOhm. La resistencia de 820 Ohm forma un nodo con las resistencias de 470 Ohm y con la segunda fuente de voltaje. Como nodo de referencia o tierra es toda la sección de abajo del circuito eléctrico.
* Además se puede identificar 3 mallas, que para el análisis se denotará como I1, I2, I3 todas en sentido de las manecillas del reloj(Anexos).



5. LISTAS DE COMPONENTES



Fig 7. Descripción de los componenetes usados en el simulador Tinkercad.

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Abrimos el sitio web "tinkercad" y creamos una cuenta.

* Hacemos clic izquierdo en "Circuits" y comenzamos con la práctica.

* Seleccionamos una placa de pruebas pequeñas (Protoboard).

* Se selecciona y se conecta al protoboard los suministros de energía asignándole el valor de 20 y 12 V.

* Escogemos cinco resistencias y las conectamos siguiendo el diagrama visto en el archivo de la práctica, que en este caso son 4 de valores de 1 KOhm, 0.47 KOhm, 2.2 KOhm y 0.82 KOhm.

* Haciendo clic izquierdo en los pines del protoboard conectamos con cables las resistencias y pasamos corriente a donde hace falta.

* Colocamos un multímetro y conectamos en paralelo con el circuito, el color negro es el negativo mientras que el color rojo es el positivo. 

* Realizamos las mediciones de volatje y resistencia, aplicando el teorema de superposición, pedidas en la guía.

* Anotamos los valores obtenidos en las tablas de la guía de laboratorio.

* Guardamos y salimos.

7. TABLAS DE MEDICIONES Y CÁLCULOS 

            

8. PORCENTAJE DE ERROR.



9. CONCLUSIONES 


10. RECOMENDACIONES 



11. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/Edgar1Gallegos/CARACTERISTICAS-DE-LA-ONDA-SENOIDAL/blob/master/img/Cronograma.png)


12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
