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

![]()   -   Mentefacto


* Desarrollo:

Ley de nodos:

 La suma algebraica de las corrientes en un nodo es igual a cero.      

I1 + I2 + I3 = 0 => valor de las corrientes en el NODO .

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

![](https://github.com/eddy90cg/Laboratorio_3/blob/main/img/simulado%20medicion%20de%20corriente.jpeg)

* Circuito Experimental y simulado para el analisis de malla, medidos con multímetro respectivo al voltaje de cada nodo:

![]()   -   Mendicion simuladao voltimetro 


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


![]()    - Tabla registrado los vlaores cada nodo


Para poder econtrar los valores de la corriente para cada malla se aplicaron los sigueintes calulos:

![]()    - calculos 


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
