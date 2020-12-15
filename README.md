# LEYES DE KIRCHHHOFF

#### RESUMEN

La practica de este laboratorio consiste en hacer la configuración en un circuito eléctrico con resistores organizados en serie y en paralelo, se calcula la corriente en puntos específicos y la corriente resultante por métodos, exclusivamente matemáticos y por medio de voltaje o voltímetro, para concluir compararamos los resultados verificar las leyes de Kirchhoff.

### 1.  OBJETIVOS

#### OBJETIVO GENERAL

- Realizar las mediciones de corrientes y voltajes en un circuito con tres fuentes de poder y comparar los valores obtenidos experimentalmente, con los obtenidos del cálculo aplicando las leyes de Kirchhoff.

- La experiencia de este laboratorio consiste en hacer la configuración en un circuito eléctrico con resistores organizados en serie y en paralelo, se calcula la corriente en puntos específicos y la corriente resultante por métodos, solamente matemáticos y por medio de voltaje o voltímetro, para finalmente comparar los resultados y comprobar las leyes de Kirchhoff.

#### OBJETIVOS ESPECÍFICOS

- Afianzar experimentalmente las leyes de conservación de la energía eléctrica y la Conservación de la carga.

- Verificar las leyes de Kirchhoff: Ley de Mallas y ley de Nodos.

### 2. MATERIALES Y EQUIPOS REQUERIDOS

| Cantidad | Material de Equipo |
| ------ | ------ |
| 1 | Fuente de Voltaje de C.D.|
| 2 | Multímetros de Dijítales
| 1| Resistor de 1 kΩ|
| 2 | Resistores de 2.2 kΩ |
| 1 | Resistor de 1.8  kΩ |
| 1 | Resistor de 3.9  kΩ |
| 1 | Protoboard |

### 3 MARCO TEÓRICO

Gustav Kirchhoff (1824-1887) fue un físico alemán nacido en marzo de 1824 en la entonces Prusia oriental. Durante su carrera científica realizó importantes contribuciones en campos como la electricidad, la espectroscopia o la medición de radiaciones de los cuerpos negros. 

En 1845 enunció las denominadas leyes de Kirchhoff, aplicables al cálculo de tensiones, intensidades y resistencias en el sí de una malla eléctrica; entendidas como una extensión de la ley de la conservación de la energía, se basaban en la teoría del físico Georg Simon Ohm, según la cual la tensión que origina el paso de una corriente eléctrica es proporcional a la intensidad de la corriente.

Las tres leyes de la espectroscopia de Kirchhoff

El científico elaboró un conjunto de leyes para describir cómo se comporta la emisión de luz por objetos incandescentes:

1- Un objeto sólido caliente produce luz en un espectro continuo.

2- Un gas tenue produce luz con líneas espectrales en longitudes de onda discretas que dependen de la composición química del gas.

3- Un objeto sólido a alta temperatura rodeado de un gas tenue a temperaturas inferiores produce luz en un espectro continuo con huecos en longitudes de onda discretas cuyas posiciones dependen de la composición química del gas.

Las tres leyes sobre la espectrografía de Kirchhoff fueron, más adelante, la base de la aparición de la mecánica cuántica.

La ley de Kirchhoff, constituyen la base de los análisis moderno de redes. Son aplicables a circuitos con una o más fuentes de tensión.

* Nodo: Punto de un circuito en el que se unen tres o más conductores.
* Rama: Parte del circuito unida por dos nodos.
* Malla: Recorrido cerrado dentro de un circuito.

1. Ley de nodos

 La suma algebraica de las corrientes en un nodo es igual a cero.      

I1 – I2 – I3 = 0

2. Ley de mallas 

 La suma de todas las caídas de tensión en un malla es igual a la suma de todas las tensiones aplicada

VAB = V1 + V2 + V3

Método de las mallas

Mediante el método de las mallas es posible resolver circuitos con varias mallas y fuentes. 
Consiste en plantear las corrientes de cada malla como su intensidad por su resistencia y sumar o restar las intensidades por las resistencias relacionadas con mallas adyacentes.

1). Se asigna un sentido arbitrario de circulación de corriente a cada malla (las que se quieren calcular). El sentido no tiene porqué ser el real (de hecho antes de calcularlo no se lo conoce). Si se obtiene como resultado alguna corriente negativa, el sentido real de la misma es al revés del utilizado para esa malla.

 V1 = I1 (R1 + R2) - I2 (R2)

2). Se plantea a la suma de las fuentes de cada malla como I por R de la malla y se le restan las ramas comunes con otras mallas. El signo que se les pone a las fuentes depende del sentido de circulación elegido para la corriente. Si se pasa a través de la fuente de negativo a positivo con el sentido elegido, se utiliza (+), de lo contrario (-).

 V2 = I2 (R2 + R3 + R4) – I1 (R2) – I3 (R4)

3). Los valores de resistencias y de tensiones se conocen, por lo tanto quedan 3 ecuaciones con 3 incógnitas (para 3 mallas interiores) en donde cada incógnita es la corriente de malla. Resolviendo el sistema se obtienen las corrientes. Si se obtiene alguna corriente negativa quiere decir que el sentido real es al revés del elegido.

 V3 = I3 (R4 + R5) – I2 (R4)

### 4. PROCEDIMIENTO

Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

| VARIABLE | VALOR CALCULADO | VALOR MEDIO |
| ------ | ------ | ------ |
| VR1 (V) | 2.05  | 2.05 |
| IR1 (mA) | 2.60   | 2.59 |
| VR2 (V) | 4.251 | 4.25 |
| IR2 (mA) | 3.57 | 3.57 |
| VR3 (V) | 2.11 | 2.12 |
| IR3 (mA) | 1.51 | 1.52 |
| VR4 (V) | 2.11 | 2.12 |
| IR4 (mA) | 1.51 | 1.52 |
| VR5 (V) | 3.69 | 3.70 |
| IR5 (mA) | 3.26 | 3.60 |

Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada,
considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con
signo negativo. Anote los resultados en la tabla 1.2.

Tabla 1.2. Verificación de la LVK.

| VOLTAJE | TRAYECTORIA 1 | TRAYECTORIA 2 |
| ------ | --- | -- | -- | -- |
| VT (V) |
| VR1   |     |
| VR2 (V) |     |     |
| VR3 (V)    |     |
| VR3 (V) |    |    |
| VR4 (V) |    |    |
| VR5 (V) |    |    |
| ∑ V |    |    |
| % ERROR |      


### 5. DIAGRAMA

### 10. CONCLUSIONES 

- Hemos descubierto de forma teórica los valores de la corriente y del voltaje que fluye por cada una de las resistencias del circuito, mediante del simulador online para lo cual usamos las reglas de Kirchhoff. 

- Costatamos que las leyes de Kirchhoff al acatar los valores adquiridos tanto de forma teórica como de forma experimental, visulizando que la diferencia entre estas es mínima, por lo tanto podríamos concluir en que las leyes de Kirchhoff se cumplen los valores arrojados de error porcentual de medición del teórico con respecto al experimental depende del instrumento (Resistencia interna,Precisión de medición).

- Los valores de corriente fueron también determinados a partir del método de mallas, y al tener nuestras ecuaciones con la ayuda matrices pudimos obtener los valores teóricos  
  de la corriente y por ende los voltajes, además y se puede apreciar que los valores casi son los mismos.

### 11. BIBLIOGRAFÍA 

https://www.lifeder.com/gustav-kirchhoff/

https://www.academia.edu/6820754/LABORATORIO_No_3_LEYES_DE_KIRCHOFF

https://www.ecured.cu/Leyes_de_Kirchhoff



