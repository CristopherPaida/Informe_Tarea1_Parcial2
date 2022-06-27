# Informe_Tarea1_Parcial2

Universidad de las Fuerzas Armadas - ESPE

Fundamentos de Circuitos Eléctricos

1. Objetivo

Objetivo General

Comprender el funcionamiento de los circuitos en serie-paralelo y sus teoremas por medio de artículos y libros para la correcta aplicación en la resolución de ejercicios.

Objetivos Específicos

•	Investigar el concepto de circuitos en serie-paralelo y sus derivados para la correcta resolución de los ejercicios propuestos.

•	Investigar los teoremas de circuitos y conversiones para la correcta aplicación en la resolución de circuitos eléctricos.

2. Marco teórico

Según Zapata, un circuito en serie-paralelo o mixto es aquel que contiene elementos conectados tanto en serie como en paralelo, de forma que, al cerrar el circuito, se establecen distintas tensiones y corrientes en cada uno de ellos. (Zapata, 2021)

Es de gran importancia identificar la forma en que se disponen los elementos en un circuito en función de sus relaciones en serie y paralelo, como en la siguiente imagen:

![image](https://user-images.githubusercontent.com/105565670/175976305-6e00dc03-6425-4381-a831-d1fada4d010d.png)

En donde se observa que R1 y R4 están en serie con la combinación en paralelo de R2 y R3.

En análisis de un circuito en serie-paralelo se puede abordar de distintas maneras dependiendo la información que se necesite, siendo estos los siguientes:

Resistencia total: Para encontrar la resistencia total de una combinación en serie-paralelo, se deben definir las relaciones serie-paralelo, una vez realizado esto, se procede al cálculo de la resistencia total aplicando su fórmula con los datos obtenidos.

Corriente total: Para encontrar la corriente total de una combinación en serie-paralelo, se puede utilizar la Ley de Ohm, divisor de corriente o la Ley de corriente de Kirchhoff, una vez definido las relaciones y valores.

Caídas de voltaje: Para encontrar el voltaje en ciertas partes de un circuito en serie-paralelo, se puede utilizar la Ley de Ohm, divisor de voltaje o la Ley del voltaje de Kirchhoff una vez definido las relaciones y valores.

Según Floyd, una red en escalera es un tipo especial de circuito en serie-paralelo, se utiliza comúnmente para reducir voltajes a ciertos valores ponderados para conversión de digital a analógica. (Thomas, 2007)

Un ejemplo de una red en escalera de un circuito en serie-paralelo sería:

![image](https://user-images.githubusercontent.com/105565670/175976421-8af7ce3b-b2e5-4556-a0d8-06f5e1cbb45b.png)

El puente Wheatstone

El circuito puente Wheatstone se utiliza para medir con precisión la resistencia, siendo este un puente equilibrado y desequilibrado.

![image](https://user-images.githubusercontent.com/105565670/175976467-7bf72294-12b3-4383-b669-87c0fab0725c.png)

En un análisis de circuitos, en ocasiones es de gran utilidad convertir una fuente de voltaje en una fuente de corriente equivalente, o viceversa.

El proceso para la conversión de una fuente de voltaje a corriente o viceversa, se puede visualizar en la siguiente tabla:

![image](https://user-images.githubusercontent.com/105565670/175976584-f20a8104-8798-4edd-9d25-b37413f1d397.png)

El teorema de superposición

Según Floyd, el método de superposición es una forma de determinar corrientes en un circuito con múltiples fuentes dejando una fuente a la vez y reemplazando las demás fuentes por sus resistencias internas.

Los pasos para aplicar el método de superposición son:

•	Paso 1: dejar una fuente de voltaje (o de corriente) a la vez en el circuito y reemplazar cada una de las demás fuentes de voltaje (o de corriente) con su resistencia interna. Para fuentes ideales, un corto representa resistencia interna de cero y una abertura representa resistencia interna infinita.

•	Paso 2: determinar la corriente (o el voltaje) particular que se desea justo como si hubiera sólo una fuente en el circuito.

•	Paso 3: tomar la siguiente fuente que haya en el circuito y repetir los pasos 1 y 2. Hacer esto con cada una de las fuentes.

•	Paso 4: sumar algebraicamente las corrientes producidas por cada fuente individual para encontrar la corriente real en una rama dada. (Si las corrientes están en la misma dirección, se suman. Si están en direcciones opuestas, se restan y la dirección de la corriente resultante será la misma que la presentada por la cantidad más grande de las cantidades originales.) Una vez determinada la corriente, ya se puede calcular el voltaje mediante la ley de Ohm.

Teorema de Thevenin

Según Floyd, el teorema de Thevenin proporciona un método para simplificar un circuito a una forma equivalente estándar. (Thomas, 2007)

La forma Thevenin equivalente de cualquier circuito consta de una fuente de voltaje equivalente y una resistencia equivalente, siendo:

![image](https://user-images.githubusercontent.com/105565670/175976788-eaf26b2a-6a34-4943-a1ab-b58f3c3b7efb.png)

Teorema de Norton

Según Floyd, el teorema de Norton es un método empleado para simplificar un circuito lineal de dos terminales en un circuito equivalente con sólo una fuente de corriente en paralelo con un resistor. (Thomas, 2007)

Para aplicar el teorema de Norton, se debe determinar la fuente de corriente equivalente y la resistencia equivalente, siendo:

![image](https://user-images.githubusercontent.com/105565670/175976869-6030c980-bb40-452f-ad43-47979a93e5ed.png)

Pasos para aplicar el teorema de Norton:

•	Paso 1: poner con cortocircuito las dos terminales entre la cuales se desea determinar el circuito equivalente de Norton.

•	Paso 2: determinar la corriente (IN) a través de las terminales puestas en cortocircuito.

•	Paso 3: determinar la resistencia (RN) entre las dos terminales abiertas con todas las fuentes reemplazadas por sus resistencias internas (fuentes de voltaje ideales en cortocircuito y fuentes de corriente ideales abiertas). RN = RTH.

•	Paso 4: Conectar IN y RN en paralelo para producir el circuito equivalente de Norton completo para el circuito original.

El teorema de transferencia de potencia máxima es importante cuando se tiene que conocer el valor de la carga con la cual la fuente suministra la máxima potencia. La potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

Conversiones Delta a Y y Y a Delta

![image](https://user-images.githubusercontent.com/105565670/175977067-c6266706-ffa1-425b-855a-1890dc433a13.png)

3. Resolución de ejercicio -> Capítulo 7 y 8


