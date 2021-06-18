### ANÁLISIS DE NODOS


### INTEGRANTES: EDISON CADENA - STEVEN FLORES - WILLIAM MOSQUERA


1. OBJETIVOS


OBJETIVO GENERAL:

* Comprobar experimentalmente el Análisis de Nodos

* La experiencia de este laboratorio consiste en hacer la configuración en un circuito eléctrico para saber voltajes de cada nodo.

OBJETIVOS ESPECÍFICOS: 

* Afianzar experimentalmente las leyes de conservación de la energía eléctrica y la medicon de voltaje atra ves de aplicacion teorica.

* Verificar las leyes de Kirchhoff: Ley de Mallas, ley de Nodos para econtrar el voltaje de cada nodo.


2. MARCO TEÓRICO 


* Resumen:

El análisis de nodos de circuitos eléctricos, el análisis de nodos, o método de tensiones nodales es un método para determinar la tensión de uno o más nodos.

* Introducción:

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/Mentefacto.jpg)

* Desarrollo:

Ley de nodos:

 La suma algebraica de las corrientes en un nodo es igual a cero.      

I1 + I2 + I3 = 0 => valor de las corrientes en el NODO .

Ley de ohm: 

V = I/R -> asi econtramos el valor de la corriente en cada voltaje hallado de cada nodo.

Ley de mallas: 

La suma de todas las caídas de tensión en un malla es igual a la suma de todas las tensiones aplicada

VAB = V1 + V2 + V3

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/circuito%20marco%20teorico.jpg)


* Procedimiento para aplicar el análisis de Nodos :


1.  Localice los segmentos de cable conectados al circuito. Estos serán los nodos que se usarán para el método.

2.  Seleccione un nodo de referencia (polo a tierra). Se puede elegir cualquier nodo ya que esto no afecta para nada los cálculos; pero elegir el nodo con más conexiones podría simplificar el análisis.

3.  Identifique los nodos que están conectados a fuentes de voltaje que tengan una terminal en el nodo de referencia. En estos nodos la fuente define la tensión del nodo. Si la fuente es independiente, la tensión del nodo es conocida. En estos nodos no se aplica la LCK.

4.  Asigne una variable para los nodos que tengan tensiones desconocidas. Si la tensión del nodo ya se conoce, no es necesario asignarle una variable.

5.  Para cada uno de los nodos, se plantean las ecuaciones de acuerdo con las Leyes de Kirchhoff. Básicamente, sume todas las corrientes que pasan por el nodo e iguálelas a 0. Si el número de nodos es (n), el número de ecuaciones será por lo menos (n-1) porque siempre se escoge un nodo de referencia al cual no se le elabora ecuación.

6.  Si hay fuentes de tensión entre dos tensiones desconocidas(entre dos nodos desconocidos), una esos dos nodos como un supernodo, haciendo el sumatorio de todas las corrientes que entran y salen en ese supernodo. Las tensiones de los dos nodos simples en el supernodo están relacionadas por la fuente de tensión intercalada.

7.  Resuelva el sistema de ecuaciones simultáneas para cada tensión desconocida.

Diagrama de Nodos Teórico:

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/diagrama%20nodos%20teorico.jpg)


3. DIAGRAMAS

* Figura, Circuito Teórico para el análisis de nodos:

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/diagrama.jpeg)

* Circuito Experimental y simulado para el analisis de malla, medidos con multímetro respectivo a la corrriente de cada elemento:

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/Medicion%20de%20Corriente.jpeg)

* Circuito Experimental y simulado para el analisis de malla, medidos con multímetro respectivo al voltaje de cada nodo:

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/Medicion%20de%20Voltaje.jpeg)

4. LISTA DE COMPONENTES

Lista de Materiales y componetes necesarios para desarrollar el circuito expirementalmente y simularlo:

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/materiales%20o%20euipo%20lab%203.jpg)


5. EXPLICACIÓN


* Implemente el circuito que se presenta en la figura.

* Mida cada una de los volatajes de nodo y anote los resultados en la tabla.

* Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito
de la figura, en este caso es simulado con el software tinkercad obteniendo los valores de las corrientes de malla. Anote los resultados
en la tabla.

* Compare los valores de la tabla  y realice sus respectivas conclusiones.


6. APORTACIONES


Tabla de Registro de datos tomandos del Experimento:


![]()    - Tabla registrado los valores cada nodo


Para poder econtrar los valores de la corriente para cada nodo se aplicaron los sigueintes calulos:

Primero tomamos el nodo B para analizar y obtener ecuaciones:

<img src="https://latex.codecogs.com/svg.latex?I_1&plus;I_2&plus;I_3&space;=&space;0&space;\\&space;\\&space;\frac{V_1}{R_1}&space;&plus;&space;\frac{V_2}{R_2}&space;&plus;&space;\frac{V_3}{R_3}&space;=&space;0A&space;\\&space;\\&space;\\&space;\frac{V_A&space;-&space;V_B}{R_1}&space;&plus;&space;\frac{0V&space;-&space;V_B}{R_2}&space;&plus;&space;\frac{V_C&space;-&space;V_B}{R_3}&space;=&space;0A&space;\\&space;\\&space;\\&space;\frac{VF_1&space;-&space;V_B}{R_1}&space;&plus;&space;\frac{0V&space;-&space;V_B}{R_2}&space;&plus;&space;\frac{V_C&space;-&space;V_B}{R_3}&space;=&space;0A&space;\\" title="I_1+I_2+I_3 = 0 \\ \\ \frac{V_1}{R_1} + \frac{V_2}{R_2} + \frac{V_3}{R_3} = 0A \\ \\ \\ \frac{V_A - V_B}{R_1} + \frac{0V - V_B}{R_2} + \frac{V_C - V_B}{R_3} = 0A \\ \\ \\ \frac{VF_1 - V_B}{R_1} + \frac{0V - V_B}{R_2} + \frac{V_C - V_B}{R_3} = 0A \\" />

Realizamos el mismo proceso para el nodo C:

<img src="https://latex.codecogs.com/svg.latex?I_3&plus;I_4&plus;I_5&space;=&space;0&space;\\&space;\\&space;\frac{V_3}{R_3}&space;&plus;&space;\frac{V_4}{R_4}&space;&plus;&space;\frac{V_5}{R_5}&space;=&space;0A&space;\\&space;\\&space;\\&space;\frac{V_B&space;-&space;V_C}{R_3}&space;&plus;&space;\frac{0V&space;-&space;V_C}{R_4}&space;&plus;&space;\frac{V_D&space;-&space;V_C}{R_5}&space;=&space;0A&space;\\&space;\\&space;\\&space;\frac{V_B&space;-&space;V_C}{R_3}&space;&plus;&space;\frac{0V&space;-&space;V_C}{R_4}&space;&plus;&space;\frac{VF_2&space;-&space;V_C}{R_5}&space;=&space;0A&space;\\" title="I_3+I_4+I_5 = 0 \\ \\ \frac{V_3}{R_3} + \frac{V_4}{R_4} + \frac{V_5}{R_5} = 0A \\ \\ \\ \frac{V_B - V_C}{R_3} + \frac{0V - V_C}{R_4} + \frac{V_D - V_C}{R_5} = 0A \\ \\ \\ \frac{V_B - V_C}{R_3} + \frac{0V - V_C}{R_4} + \frac{VF_2 - V_C}{R_5} = 0A \\" />

Factorizamos las expresiones y obtenemos 

<img src="https://latex.codecogs.com/svg.latex?Nodo\&space;B&space;=&space;VF_1&space;\left(\frac{1}{R_1}&space;\right)&space;&plus;&space;V_C\left(\frac{1}{R_3}\right)&space;&plus;&space;V_B\left(\frac{1}{R_1}&space;&plus;&space;\frac{1}{R_2}&space;&plus;&space;\frac{1}{R_3}\right)&space;=&space;0A" title="Nodo\ B = VF_1 \left(\frac{1}{R_1} \right) + V_C\left(\frac{1}{R_3}\right) + V_B\left(\frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3}\right) = 0A" />

<img src="https://latex.codecogs.com/svg.latex?Nodo\&space;C&space;=&space;V_B&space;\left(\frac{1}{R_3}&space;\right)&space;&plus;&space;VF_2\left(\frac{1}{R_5}\right)&space;&plus;&space;V_C\left(\frac{1}{R_3}&space;&plus;&space;\frac{1}{R_4}&space;&plus;&space;\frac{1}{R_5}\right)&space;=&space;0A" title="Nodo\ C = V_B \left(\frac{1}{R_3} \right) + VF_2\left(\frac{1}{R_5}\right) + V_C\left(\frac{1}{R_3} + \frac{1}{R_4} + \frac{1}{R_5}\right) = 0A" />

Reemplazamos los valores conocidos

<img src="https://latex.codecogs.com/svg.latex?Nodo\&space;B&space;\Rightarrow&space;0.000666A&space;&plus;&space;V_C(0.000454)&space;-&space;V_B(0.00313)&space;=&space;0A&space;\\&space;\Rightarrow&space;V_C(0.000454)&space;-&space;V_B(0.00313)&space;=&space;-0.000666A" title="Nodo\ B \Rightarrow 0.000666A + V_C(0.000454) - V_B(0.00313) = 0A \\ \Rightarrow V_C(0.000454) - V_B(0.00313) = -0.000666A" />

<img src="https://latex.codecogs.com/svg.latex?Nodo\&space;C&space;\Rightarrow&space;V_B(0.000454)&space;&plus;&space;0.00533A&space;-&space;V_C(0.00137)=&space;0A&space;\\&space;\Rightarrow&space;V_B(0.000454)-&space;V_C(0.00137)=&space;-0.00533A" title="Nodo\ C \Rightarrow V_B(0.000454) + 0.00533A - V_C(0.00137)= 0A \\ \Rightarrow V_B(0.000454)- V_C(0.00137)= -0.00533A" />

Para encontrar las incógnitas despejamos <img src="https://latex.codecogs.com/svg.latex?V_B" title="V_B" /> en las ecuaciones anteriores:

<img src="https://latex.codecogs.com/svg.latex?Nodo\&space;B&space;\Rightarrow&space;V_B&space;=&space;\frac{0.00666&space;&plus;&space;V_C(0.000454)}{0.00313}&space;=&space;2.12V&space;&plus;&space;V_C(0.14)" title="Nodo\ B \Rightarrow V_B = \frac{0.00666 + V_C(0.000454)}{0.00313} = 2.12V + V_C(0.14)" />

<img src="https://latex.codecogs.com/svg.latex?Nodo\&space;C&space;\Rightarrow&space;V_B&space;=&space;\frac{-0.00533&space;&plus;&space;V_C(0.00137)}{0.000454}&space;=&space;-11.74V&space;&plus;&space;V_C(3.02)" title="Nodo\ C \Rightarrow V_B = \frac{-0.00533 + V_C(0.00137)}{0.000454} = -11.74V + V_C(3.02)" />

Y luego igualamos las mismas para encontrar <img src="https://latex.codecogs.com/svg.latex?V_C" title="V_C" /> primero:

<img src="https://latex.codecogs.com/svg.latex?2.12&space;&plus;&space;V_C(0.14)&space;=&space;-11.74&space;&plus;&space;V_C(3.02)\\&space;V_C(0.14&space;-&space;3.02)&space;=&space;-11.74&space;-&space;2.12&space;\\&space;V_C(-2.88)&space;=&space;-13.86&space;\\&space;\\&space;V_C&space;=&space;\frac{-13.86}{-2.88}&space;=&space;4.81&space;V" title="2.12 + V_C(0.14) = -11.74 + V_C(3.02)\\ V_C(0.14 - 3.02) = -11.74 - 2.12 \\ V_C(-2.88) = -13.86 \\ \\ V_C = \frac{-13.86}{-2.88} = 4.81 V" />

Una vez obtenida <img src="https://latex.codecogs.com/svg.latex?V_C" title="V_C" /> reemplazamos el valor en el nodo C para encontrar <img src="https://latex.codecogs.com/svg.latex?V_B" title="V_B" /> 

<img src="https://latex.codecogs.com/svg.latex?V_B&space;=&space;-11.74V&space;&plus;&space;(4.81)(3.02)&space;\\&space;V_B&space;=&space;2.79&space;V" title="V_B = -11.74V + (4.81)(3.02) \\ V_B = 2.79 V" />

Finalmente encontramos los valores de voltaje

<img src="https://latex.codecogs.com/svg.latex?V_1&space;=&space;V_A&space;-&space;V_B&space;=&space;12&space;-&space;2.79&space;=&space;9.21\&space;V&space;\\&space;\\&space;V_2&space;=&space;V_B&space;-&space;0V&space;=&space;2.79\&space;V&space;\\&space;\\&space;V_3&space;=&space;V_B&space;-&space;V_C&space;=&space;-2.02\&space;V&space;\\&space;\\&space;V_4&space;=&space;V_C&space;-&space;0V&space;=&space;4.81\&space;V&space;\\&space;\\&space;V_5&space;=&space;V_C&space;-&space;V_D&space;=&space;-3.19\&space;V" title="V_1 = V_A - V_B = 12 - 2.79 = 9.21\ V \\ \\ V_2 = V_B - 0V = 2.79\ V \\ \\ V_3 = V_B - V_C = -2.02\ V \\ \\ V_4 = V_C - 0V = 4.81\ V \\ \\ V_5 = V_C - V_D = -3.19\ V" />

Y los valores de la corriente

<img src="https://latex.codecogs.com/svg.latex?I_1&space;=&space;\frac{9.21V}{1800&space;\Omega}&space;=&space;5.11\&space;mA&space;\\&space;\\&space;I_2&space;=&space;\frac{2.79V}{470&space;\Omega}&space;=&space;5.94\&space;mA&space;\\&space;\\&space;I_3&space;=&space;\frac{-2.02V}{2200&space;\Omega}&space;=&space;-918\&space;\mu&space;A&space;\\&space;\\&space;I_4&space;=&space;\frac{4.81V}{3900&space;\Omega}&space;=&space;1.23\&space;mA&space;\\&space;\\&space;I_5&space;=&space;\frac{-3.19V}{1500&space;\Omega}&space;=&space;-2.13\&space;mA" title="I_1 = \frac{9.21V}{1800 \Omega} = 5.11\ mA \\ \\ I_2 = \frac{2.79V}{470 \Omega} = 5.94\ mA \\ \\ I_3 = \frac{-2.02V}{2200 \Omega} = -918\ \mu A \\ \\ I_4 = \frac{4.81V}{3900 \Omega} = 1.23\ mA \\ \\ I_5 = \frac{-3.19V}{1500 \Omega} = -2.13\ mA" />




![]() - calculo del error


7. CONCLUSIONES

* Aplicamos la ley de Kirchhoff en nodos, al acatar los valores adquiridos tanto de forma teórica como de forma experimental, visulizando que la diferencia entre estas es mínima, por lo tanto podríamos concluir en que las leyes de Kirchhoff se cumplen los valores arrojados de error porcentual de medición del teórico con respecto al experimental depende del instrumento (Resistencia interna,Precisión de medición).

* Los valores de voltaje lo pudimos eocntrar midiendo con multimetro de manera experimentalemente simulada y asi comprobar los calculos correspondientes.

* A las corrientes de lazo o corrientes de malla se les puede asignar una dirección arbitraria.

* A cada malla esencial –o “ventana”- que tenga el circuito debe asignársele una corriente.

* la cantidad de nodos se puede determinar poir la cnatidad delementos conectados en un solo nodo.


8. BIBLIOGRAFÍA

Rodríguez, H. (19 de Octubre de 2017). lifeder. Obtenido de

     https://www.lifeder.com/leyes-kirchhoff/

Pérez, A. (12 de enero de 2015). Electrónica Completa. Obtenido de

     https://electronicacompleta.com/leyes-de-kirchhoff/
     

9. Anexos

Calculo del error: 


![](https://github.com/eddy90cg/Laboratorio_3/blob/main/Anexos/calculo%20del%20error.jpg)
