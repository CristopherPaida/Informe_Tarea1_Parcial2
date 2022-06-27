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

Capítulo 7

2. Visualice y trace los siguientes circuitos en serie-paralelo:

(a) Una combinación en paralelo de tres ramas, cada rama con dos resistores en serie

![image](https://user-images.githubusercontent.com/105565670/175977418-06f00711-bf21-494c-a9b3-97ed98acd62a.png)

(b) Una combinación serie de tres circuitos en paralelo, cada circuito con dos resistores

![image](https://user-images.githubusercontent.com/105565670/175977445-8a3a5594-2ed7-439e-abe6-df4438a0e13f.png)

4. En cada uno de los circuitos de la figura 7-63, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente.

![image](https://user-images.githubusercontent.com/105565670/175977507-d3e212e8-f96c-4194-afb5-f58327ac528c.png)

![image](https://user-images.githubusercontent.com/105565670/175977573-bfff41de-9ed9-489e-aee6-c2c89e098623.png)

6. Desarrolle un diagrama esquemático de la tarjeta de circuito impreso de doble cara mostrada en la figura 7-65, y marque los valores de resistor.

![image](https://user-images.githubusercontent.com/105565670/175977614-7f12332f-b373-4339-a256-b08aad894364.png)

![image](https://user-images.githubusercontent.com/105565670/175977637-fcdfae37-98fd-4a50-8ce4-bd2bf45255a0.png)

8. Un cierto circuito se compone de dos resistores en paralelo. La resistencia total es de 667 Ω. Uno de los resistores es de 1.0 kΩ. ¿Cuál es el otro resistor?

![image](https://user-images.githubusercontent.com/105565670/175977688-d1bfdfb3-f5bb-4167-a1b7-9434590e7a14.png)

10. Repita el problema 9 para cada uno de los circuitos mostrados en la figura 7-63. (Determine la resistencia total)

![image](https://user-images.githubusercontent.com/105565670/175977807-2ccc2b07-8d72-47ec-9171-cfbc9ee8d7b3.png)

Para el circuito a: 

![image](https://user-images.githubusercontent.com/105565670/175977849-3c10b07b-1696-4675-b81a-01bc6e390ece.png)

Para el circuito b:

![image](https://user-images.githubusercontent.com/105565670/175977912-4e213b84-f0c3-4061-a649-d63519eb0b6e.png)

Para el circuito c:

![image](https://user-images.githubusercontent.com/105565670/175977954-e3b35f86-61b4-43d6-8886-3af575ce4bba.png)

12. Determine la corriente a través de cada resistor en cada circuito de la figura 7-63; luego calcule cada caída de voltaje. 

![image](https://user-images.githubusercontent.com/105565670/175977990-4f552051-7dd2-457b-8062-6ff12f7cf004.png)

Para el circuito a: 

![image](https://user-images.githubusercontent.com/105565670/175978065-f814628f-2ffd-4a2c-8378-fbbe6e2811d5.png)

Para el circuito b:

![image](https://user-images.githubusercontent.com/105565670/175978098-6cfb8c99-c894-4506-8647-0904013e91f1.png)

Para el circuito c:

![image](https://user-images.githubusercontent.com/105565670/175978369-9540c3aa-0757-4419-abfe-cbe5eb972cf5.png)

![image](https://user-images.githubusercontent.com/105565670/175978400-783ad158-16f6-4518-82cd-329c50fb99a1.png)

14. Determine la resistencia entre A y B en la figura 7-67 sin la fuente.

![image](https://user-images.githubusercontent.com/105565670/175978437-988f3cea-098f-4a72-8601-3a735375c8e5.png)

![image](https://user-images.githubusercontent.com/105565670/175978454-2c8cffa9-011b-411c-9ee1-22ec9788cea7.png)

16. Determine el voltaje en cada nodo con respecto a tierra en la figura 7-68.

![image](https://user-images.githubusercontent.com/105565670/175978600-77ff14c4-8cf6-4a5e-9b44-2681590c92db.png)

Para el nodo A:

![image](https://user-images.githubusercontent.com/105565670/175978642-5c8ba28e-d220-4175-bcd8-52d13fcf9418.png)

Para el nodo B:

![image](https://user-images.githubusercontent.com/105565670/175978671-82424eac-26c1-4e2d-ac96-009d7cab5c49.png)

Para el nodo C:

![image](https://user-images.githubusercontent.com/105565670/175978702-bb22d35c-f99f-4bf9-981b-14ed924fe804.png)

Para el nodo D:

![image](https://user-images.githubusercontent.com/105565670/175978741-7c523ca3-6cef-400f-bb8a-5d2913349e78.png)

18. Determine la resistencia del circuito mostrado en la figura 7-67 como se ve desde la fuente de voltaje

![image](https://user-images.githubusercontent.com/105565670/175978792-e3817889-8d72-4b20-aa41-9e788b0876b8.png)

![image](https://user-images.githubusercontent.com/105565670/175978824-549e50ca-e4c0-4f17-9cf9-1e704613e959.png)

20. Determine el voltaje, VAB, en la figura 7-69.

![image](https://user-images.githubusercontent.com/105565670/175978859-7c3f8bb9-7dc4-41c8-a75f-3bf36dd3e140.png)

Rama derecha:

![image](https://user-images.githubusercontent.com/105565670/175978885-99ad8283-47ab-491e-8cf3-ecfd512b5dec.png)

Rama izquierda:

![image](https://user-images.githubusercontent.com/105565670/175978917-3c58f1a5-dabf-4891-955f-1197ce93f488.png)

Resistencia total:

![image](https://user-images.githubusercontent.com/105565670/175978946-511e76e9-f3c3-4d58-8d71-317d6e72040f.png)

Corriente total:

![image](https://user-images.githubusercontent.com/105565670/175978971-52eff62d-c247-4608-954d-7d38e5067671.png)

Corriente en la rama derecha:

![image](https://user-images.githubusercontent.com/105565670/175978999-5df3b7db-ee82-428c-b21c-53d45d273958.png)

Corriente en la rama izquierda:

![image](https://user-images.githubusercontent.com/105565670/175979020-9a1d2280-3c53-4b29-b9d7-aa063ada8d6d.png)

![image](https://user-images.githubusercontent.com/105565670/175979062-26801a11-0529-4420-894f-14c56c9971bc.png)

22. En la figura 7-71, determine la resistencia entre el nodo A y cada uno de los demás nodos (RAB, RAC, RAD, RAE, RAF, y RAG).

![image](https://user-images.githubusercontent.com/105565670/175979141-496e164f-befb-48d2-a199-653915ae0299.png)

![image](https://user-images.githubusercontent.com/105565670/175979177-a64440be-aa45-4ed2-93ed-6ef58cb4991f.png)

![image](https://user-images.githubusercontent.com/105565670/175979194-93227f33-3116-491f-a020-b73915b0cb93.png)

24. Determine el valor de cada resistor mostrado en la figura 7-73.

![image](https://user-images.githubusercontent.com/105565670/175979223-78b66b86-36a5-48dd-ba86-88c07cbe1a4a.png)

Voltajes y corrientes de cada resistor:

![image](https://user-images.githubusercontent.com/105565670/175979243-a7366956-94fb-4c17-8ce8-7d2207bb52ea.png)

Datos:

![image](https://user-images.githubusercontent.com/105565670/175979289-bebe4a50-87c2-4816-8904-a208d4a9ae5a.png)

Resistencias (ley de ohm):

![image](https://user-images.githubusercontent.com/105565670/175979331-c01e2495-5968-4c99-8c27-69be882b25f0.png)

26. La salida de una batería de 12 V se divide para obtener dos voltajes de salida. Se utilizan tres resistores de 3.3 kΩ para proporcionar dos tomas. Determine los voltajes de salida. Si se conecta una carga de 10 kΩ a la más alta de las salidas, ¿cuál será su valor con carga?

![image](https://user-images.githubusercontent.com/105565670/175979384-b54d28da-c72b-4c43-bbf7-59b489eb09f9.png)

![image](https://user-images.githubusercontent.com/105565670/175979413-0e5001c0-cc6d-42a6-8c21-471c46c1b021.png)

![image](https://user-images.githubusercontent.com/105565670/175979442-b0512470-efb3-4e65-9354-f287ac559d11.png)

28. En la figura 7-74, determine el voltaje de salida sin carga entre las terminales de salida. Con una carga de 100 kΩ conectada de A a B, ¿cuál es el voltaje de salida?

![image](https://user-images.githubusercontent.com/105565670/175979537-8dc1810c-59ce-460d-8ebc-0db940f91598.png)

![image](https://user-images.githubusercontent.com/105565670/175979583-d986cefd-417c-4cc7-b441-16bfa306f67f.png)

30. En la figura 7-74, determine la corriente continua extraída de la fuente sin carga entre las terminales de salida. Con una carga de 33 kΩ, ¿cuál es la corriente extraída?

![image](https://user-images.githubusercontent.com/105565670/175979625-957bb075-407f-4dfc-a6d3-745e5b2a847e.png)

![image](https://user-images.githubusercontent.com/105565670/175979660-917337df-36c0-411c-9fd7-289bb72fa8d9.png)

32. El divisor de voltaje de la figura 7-75 tiene una carga controlada por interruptor. Determine el voltaje en cada toma (V1, V2 y V3) para cada posición del interruptor.

![image](https://user-images.githubusercontent.com/105565670/175979682-41e2fecd-4fc3-411f-bcc5-3fd91c6291ca.png)

![image](https://user-images.githubusercontent.com/105565670/175979700-e54754d6-c4a9-4f10-8e18-6b9ab3fad2bb.png)

![image](https://user-images.githubusercontent.com/105565670/175979722-61400b06-817a-42b4-bd61-70d6df2ae872.png)

![image](https://user-images.githubusercontent.com/105565670/175979743-04837175-a841-4958-ab1b-4e9e77325c1a.png)

34. Diseñe un divisor de voltaje que produzca una salida de 6 V sin carga y un mínimo de 5.5 V entre los extremos de una carga de 1.0 kΩ. El voltaje de fuente es de 24 V y la corriente extraída sin carga no debe exceder de 100 mA.

![image](https://user-images.githubusercontent.com/105565670/175979798-7608d8a2-6eef-4c40-97dd-9856cd3266f0.png)

36. Determine la resistencia interna de un voltímetro de 20,000 Ω/V en cada uno de los siguientes ajustes de intervalo.

![image](https://user-images.githubusercontent.com/105565670/175979841-dbca99c5-146b-4cbf-b9d5-00b8afa60f9d.png)

38. Repita el problema 37 si se utiliza el voltímetro para medir voltaje entre los extremos de R4 en el circuito de la figura 7-62(b).

![image](https://user-images.githubusercontent.com/105565670/175979880-0b7dc986-eb17-4667-ba8e-7d36507669cd.png)

![image](https://user-images.githubusercontent.com/105565670/175979907-65eaac60-0b52-47b6-a2fa-2ac947d23593.png)

Por tanto, respondiendo a los literales:

![image](https://user-images.githubusercontent.com/105565670/175979944-ed2f26fb-ec04-4f02-890d-6d603531a97a.png)

40. Determine la resistencia total y el voltaje en los nodos A, B y C de la red en escalera mostrada en la figura 7-78

![image](https://user-images.githubusercontent.com/105565670/175979988-bdd021e7-178c-45a0-b02b-df6b6ce0fa70.png)

![image](https://user-images.githubusercontent.com/105565670/175980037-6c845f64-0fda-4601-aff1-be5a4e1863de.png)

![image](https://user-images.githubusercontent.com/105565670/175980062-c4b83c1c-404a-43ea-8fd1-ff28c1a483f8.png)

![image](https://user-images.githubusercontent.com/105565670/175980109-dcbf6069-3fe1-417e-97d9-8f107800d2af.png)

42. En la figura 7-79, ¿cuál es el voltaje entre los extremos de cada resistor con 10 V entre A y B?

![image](https://user-images.githubusercontent.com/105565670/175980175-e966f46b-cefd-4905-bd38-6fc2f4e6a227.png)

Para medir los voltajes en los extremos de cada resistor se requiere la corriente total e individual, cuyos valores fueron obtenidos del ejercicio 41, siendo:

![image](https://user-images.githubusercontent.com/105565670/175980206-a99d6065-3b7d-4259-b3eb-876bc1c00283.png)

Con estos datos se puede determinar el voltaje de cada resistencia, siendo:

![image](https://user-images.githubusercontent.com/105565670/175980260-f612036a-c5a6-4604-8418-d4dd63a8545f.png)

44.

![image](https://user-images.githubusercontent.com/105565670/175980320-c833bb97-9ca8-4d62-a6f9-945135198afd.png)

![image](https://user-images.githubusercontent.com/105565670/175980345-0597080e-6ec6-482a-b7bd-4eb55726380c.png)

46.

![image](https://user-images.githubusercontent.com/105565670/175980590-822a8372-5ff7-4614-b9ff-ecd921f7aeeb.png)

48. Determine el voltaje de salida para el puente desequilibrado mostrado en la figura 7-83 a una temperatura de 60 °C. La característica de resistencia según la temperatura del termistor se muestra en la figura 7-60.

![image](https://user-images.githubusercontent.com/105565670/175980621-52396abf-9872-4210-81e9-ae0e9fbb1ff7.png)

![image](https://user-images.githubusercontent.com/105565670/175980630-88fabed4-2269-4416-9bf6-02b88ce8fb1a.png)

![image](https://user-images.githubusercontent.com/105565670/175980660-37c2ed7a-57f2-431d-87e4-d277c7b3cb92.png)

50. ¿Son correctas las lecturas del medidor mostrado en la figura 7-85?

![image](https://user-images.githubusercontent.com/105565670/175980691-7a28a2c8-222e-4b1d-b3ff-1429407ba6d8.png)

Para verificar si las lecturas son correctas, se deben analizar, por tanto:

![image](https://user-images.githubusercontent.com/105565670/175980729-3fefd2de-ac52-4b6d-9205-3bade4ee3a6c.png)

Conclusión:

Las lecturas de los medidores son correctas.

52. Vea los medidores ilustrados en la figura 7-87 y determine si hay una falla en el circuito. Si la hay, identifíquela.

![image](https://user-images.githubusercontent.com/105565670/175980792-14f4c2f4-03e3-465a-996f-62b48f70e2e5.png)

![image](https://user-images.githubusercontent.com/105565670/175980827-be963f38-026e-4f54-ba40-65700e943759.png)

La lectura medida es incorrecta, el valor calculado es 56.25V mientras que en la figura es 81.8V, por tanto, la lectura es incorrecta.

Por tanto, la falla más probable es una resistencia abierta de 12kΩ, haciendo que el voltaje sea más alto de lo que debería ser. Entonces para calcular se asume una resistencia abierta de 12kΩ

![image](https://user-images.githubusercontent.com/105565670/175980865-71da6b93-4240-48bf-b08b-9374d106f08f.png)

54. Si en la figura 7-89 R_2 se abre, ¿qué voltajes se leerán en los puntos A, B y C?

![image](https://user-images.githubusercontent.com/105565670/175980884-bb4868bf-1659-403e-931c-b863ccbfd47a.png)

![image](https://user-images.githubusercontent.com/105565670/175980906-0fc08dc8-82bb-4d0b-9de1-c7a243037f20.png)

Capítulo 8

2. Convierta las fuentes de voltaje prácticas de la figura 8-67 en fuentes de corriente equivalentes.

![image](https://user-images.githubusercontent.com/105565670/175981094-476638f2-edad-4b50-9c34-f797f36a2d98.png)

![image](https://user-images.githubusercontent.com/105565670/175981117-cefd78ca-0ea4-4349-bdae-f35279687059.png)

4. Trace los circuitos equivalentes de fuentes de voltaje y corriente para la batería tipo D del problema 3.

![image](https://user-images.githubusercontent.com/105565670/175981138-d1b90839-8a57-4011-9a60-0af87a2d19db.png)

6. Convierta las fuentes de corriente prácticas de la figura 8-68 en fuentes de voltaje equivalentes.

![image](https://user-images.githubusercontent.com/105565670/175981182-29bedf5f-797a-4818-b94f-8c318723b90a.png)

![image](https://user-images.githubusercontent.com/105565670/175981212-139b711b-60a8-4b9e-a4bf-7ce503379015.png)

8. Use el teorema de superposición para determinar la corriente a través, y el voltaje entre, los extremos de la rama R2 de la figura 8-69.

![image](https://user-images.githubusercontent.com/105565670/175981260-1daa457f-6bb2-41ff-b8aa-a0c52a5533e3.png)

Por el problema 7, sabemos que:

![image](https://user-images.githubusercontent.com/105565670/175981277-5341b46e-ed3b-4769-82a9-80d9b378bddb.png)

![image](https://user-images.githubusercontent.com/105565670/175981318-c64ad479-3a35-4051-8880-169d719fdb5e.png)

10. Con el teorema de superposición, determine la corriente de carga en cada uno de los circuitos mostrados en la figura 8-71.

![image](https://user-images.githubusercontent.com/105565670/175981334-b0b49b92-5b10-4a9f-b2b1-ed417a57ec60.png)

Para el circuito a:

![image](https://user-images.githubusercontent.com/105565670/175981360-61aec69e-8069-4ea2-8cd9-8830c0340d62.png)

![image](https://user-images.githubusercontent.com/105565670/175981389-a3e1f04e-d4d1-4c7a-ae03-25ce5aca2ae6.png)

Para el circuito b:

![image](https://user-images.githubusercontent.com/105565670/175981426-4d62dc62-3cb5-4d3d-b182-9e4608d5bb9a.png)

![image](https://user-images.githubusercontent.com/105565670/175981486-198cfa54-7318-4757-91b4-273eaff24ca1.png)

12. Repita el problema 11 si R2 es de 10 kΩ.  En la figura 8-72 se muestra un circuito comparador. El voltaje de entrada, VENTRADA, se compara con el voltaje de referencia, VREFERENCIA, y se genera una salida negativa si VREFERENCIA > VENTRADA; de lo contrario es positiva. El comparador no carga a una u otra entrada. Si R2 es de 10 kΩ, ¿cuál es el intervalo del voltaje de referencia?

![image](https://user-images.githubusercontent.com/105565670/175981530-789a95a1-88a5-4905-be9d-53014b6fef9d.png)

![image](https://user-images.githubusercontent.com/105565670/175981563-934c8072-02d4-4d83-85b3-bbb037eb6ada.png)

14. Los interruptores mostrados en la figura 8-74 se cierran en secuencia, SW1 primero. Determine la corriente a través de R4 después del cierre de cada interruptor.

![image](https://user-images.githubusercontent.com/105565670/175989246-36823a28-8e0f-4cdc-b37e-ebc3fb69e0e3.png)

![image](https://user-images.githubusercontent.com/105565670/175989259-4be0c95d-697b-4f36-b211-90c4b37b59a2.png)

SW1 cerrado:

![image](https://user-images.githubusercontent.com/105565670/175989289-3eed93ba-036e-4e85-a8c4-e7b880cb0332.png)

SW1 y SW2 cerrado, con 12 V:

![image](https://user-images.githubusercontent.com/105565670/175989331-681b074e-c273-4098-bc5c-b7f645711970.png)

SW1 y SW2 cerrado, con 6 V:

![image](https://user-images.githubusercontent.com/105565670/175989363-2a7cd856-d0a4-4edf-b887-e704fdbb0cb3.png)

Corriente total en R_L para SW1 y SW2 cerrados:

![image](https://user-images.githubusercontent.com/105565670/175989411-2c39043d-c26f-4de5-9498-548010ef3d96.png)

SW1, SW2 y SW3 cerrados, con 12 V:

![image](https://user-images.githubusercontent.com/105565670/175989465-ab1ce8a1-30c0-4336-b3ef-70bd5a1f0b94.png)

![image](https://user-images.githubusercontent.com/105565670/175989480-e02dc814-b1f3-42e2-973f-db7738660e52.png)

SW1, SW2 y SW3 cerrados, con 6 V:

![image](https://user-images.githubusercontent.com/105565670/175989545-c3cbb2eb-ade3-4e9e-ac58-5645764d514c.png)

![image](https://user-images.githubusercontent.com/105565670/175989557-c8fce6d0-e001-4cf9-8e17-2b74c0ecf2cf.png)

SW1, SW2 y SW3 cerrados, con 9 V:

![image](https://user-images.githubusercontent.com/105565670/175989676-c20fe5a4-9102-4dd3-aa4a-27218e30855b.png)

![image](https://user-images.githubusercontent.com/105565670/175989753-d5ede568-7698-4b5c-8548-3c7f74cfb9bb.png)

16. Para cada uno de los circuitos de la figura 8-76, determine el equivalente de Thevenin como se ve desde las terminales A y B.

![image](https://user-images.githubusercontent.com/105565670/175989773-30dd62e9-92c6-407b-8ebd-b4b9bb264450.png)

![image](https://user-images.githubusercontent.com/105565670/175989831-be1fa58b-08a7-469b-afcc-79fdb9960ad6.png)

18. Con el teorema de Thévenin, determine el voltaje entre los extremos de R4 en la figura 8-78.

![image](https://user-images.githubusercontent.com/105565670/175989868-2068b2e2-986e-4371-a9fb-8b5a78ad6478.png)

![image](https://user-images.githubusercontent.com/105565670/175989875-e2d17306-c4d0-4407-a766-99dd2aefacb4.png)

![image](https://user-images.githubusercontent.com/105565670/175989957-ab2e391b-3228-4d44-ad29-9b6c8d6a10ec.png)

![image](https://user-images.githubusercontent.com/105565670/175989988-00ab21c0-fdcf-48e0-af0c-ea07e7800d42.png)

20. Determine la corriente que se dirige al punto A cuando R_8 es de 1.0 kΩ, 5 kΩ, y 10 kΩ en la figura 8-80

![image](https://user-images.githubusercontent.com/105565670/175990828-085b0529-9468-46b2-99d5-92059ccbdb4e.png)

![image](https://user-images.githubusercontent.com/105565670/175990853-2ada7dd2-a8cb-45f1-b11b-a52a73aef3a0.png)

![image](https://user-images.githubusercontent.com/105565670/175990923-418c82e6-df9f-4709-842a-1a0a53e786dd.png)

![image](https://user-images.githubusercontent.com/105565670/175990957-47e804f6-baa7-4485-9725-f178caa66ccb.png)

![image](https://user-images.githubusercontent.com/105565670/175990977-9638b96e-90c6-485d-8e3e-d8b8cc367531.png)

22. Determine el equivalente de Thévenin del circuito mostrado en la figura 8-82 visto desde las terminales A y B

![image](https://user-images.githubusercontent.com/105565670/175991006-6bacfd46-0759-4455-a000-5971f16467ee.png)

![image](https://user-images.githubusercontent.com/105565670/175991069-81bc22fc-29e0-40f8-ba77-632bf5653b61.png)

![image](https://user-images.githubusercontent.com/105565670/175991080-3de8e98a-f23f-47bc-a1db-3b5ccea5fa55.png)

24. Con el teorema de Norton, determine la corriente que circula a través del resistor de carga R_L en la figura 8-77

![image](https://user-images.githubusercontent.com/105565670/175991105-a39376a5-c72e-46d7-b685-0feb523652f5.png)

![image](https://user-images.githubusercontent.com/105565670/175991120-2b52f738-d198-47f7-92c5-f304755a6722.png)

![image](https://user-images.githubusercontent.com/105565670/175991142-4eae67c4-3c7f-42c3-85e6-6f3df25a0375.png)

![image](https://user-images.githubusercontent.com/105565670/175991164-1f7f49ab-6a84-4fec-8c5d-b1d68f84dabe.png)

26. Con el teorema de Norton, determine la corriente que circula a través de R_1 en la figura 8-80 cuando R_8 = 8 kΩ  

![image](https://user-images.githubusercontent.com/105565670/175991282-839684fb-b181-4d73-9398-9169e3479e15.png)

![image](https://user-images.githubusercontent.com/105565670/175991310-b6197247-6165-46a3-93ae-3916b7a21cd9.png)

![image](https://user-images.githubusercontent.com/105565670/175991402-8ead0800-28b7-46c7-96aa-0d4b2baf3aee.png)

![image](https://user-images.githubusercontent.com/105565670/175991415-21f55d6f-9c77-427c-a126-0db503f10c45.png)

28. En la figura 8-83, reduzca el circuito entre las terminales A y B a su equivalente Norton

![image](https://user-images.githubusercontent.com/105565670/175991440-258cb1bb-240a-4ede-8b72-cd76a20e0012.png)

![image](https://user-images.githubusercontent.com/105565670/175991480-caa1ddce-ad31-4047-8bdb-f3aa83e32949.png)

![image](https://user-images.githubusercontent.com/105565670/175991497-e3605991-9313-4afa-995a-213d42d6318d.png)

![image](https://user-images.githubusercontent.com/105565670/175991516-ff4bc7a3-959d-4f1a-aa58-917351fd6e83.png)

30. En cada circuito mostrado en la figura 8-85, se tiene que transferir potencia máxima a la carga R_L. Determine el valor apropiado de R_L en cada caso

![image](https://user-images.githubusercontent.com/105565670/175991581-e21ac9b1-1509-4909-9c9e-ddd63e2706c1.png)

32. ¿Cuánta potencia se suministra a la carga cuando R_L es un 10% más alta que su valor para transferencia de potencia máxima en el circuito de la figura 8-86?

![image](https://user-images.githubusercontent.com/105565670/175991612-c62d7283-9fb2-427f-b3cd-30c909b8bccb.png)

![image](https://user-images.githubusercontent.com/105565670/175991658-a7ec8892-6913-42fd-aae9-650e6a68a410.png)

![image](https://user-images.githubusercontent.com/105565670/175991689-5c194b78-ddc7-4c32-ad53-2e8cb2967059.png)

34. En la figura 8-88, convierta cada red delta en una red Y

![image](https://user-images.githubusercontent.com/105565670/175991725-c894d426-94ac-486f-950e-235a91d6874e.png)

![image](https://user-images.githubusercontent.com/105565670/175991758-936dc69c-bc55-4dd8-8e7c-e8b363e24433.png)

36. Determine todas las corrientes que circulan en el circuito de la figura 8-90

![image](https://user-images.githubusercontent.com/105565670/175991779-309627fc-734d-4f99-a5ac-f3c4b4bf316c.png)

Redibujando el circuito para sus cálculos, sería:

![image](https://user-images.githubusercontent.com/105565670/175991807-7ce0a873-a758-4ff1-9934-8eb3f04dea9b.png)

![image](https://user-images.githubusercontent.com/105565670/175991843-8c32455a-b1a2-4738-b85c-86b7a27afc73.png)

Para encontrar las demás corrientes, se calculan en base al circuito original

![image](https://user-images.githubusercontent.com/105565670/175991869-bae84c4f-5ee6-4d6a-8ca7-485269cf0747.png)

4. Video

Link del video:

5. Conclusiones

•	Los circuitos en serie-paralelo se caracterizan por tener sus elementos conectados en serie y paralelo que dependiendo la información que se requiera determinar, se lo puede realizar por medio del análisis de relación y datos que nos provee el circuito eléctrico.

•	Los teoremas de circuitos proporcionan métodos para simplificar un circuito a una forma estándar haciendo fácil su análisis y cálculo de valores, mientras que las conversiones son de gran utilidad para el análisis de un circuito y aplicaciones especializadas.

6. Bibliografía

Thomas, F. (2007). Principios de circuitos eléctricos. Octava edición. México: Pearson Educación.

Zapata, F. (21 de Mayo de 2021). lifeder. Obtenido de https://www.lifeder.com/circuito-electrico-mixto/
