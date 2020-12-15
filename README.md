# LEYES DE KIRCHHOFF

1. OBJETIVOS



2. MARCO TEÓRICO 

Leyes de Kirchhoff

Para tratar circuitos complicados, se usan las reglas de Kirchhoff, establecidas por G. R. Kirchhoff (1824-1887) a mediados del siglo XIX. Son dos reglas y simplemente son aplicaciones convenientes de las leyes de conservación de la carga y la energía.

La primera regla de Kirchhoff, o regla de los nodos, se basa en la conservación de la carga eléctrica que ya se usó al deducir la regla para resistores en paralelo. Esa regla afirma que en cualquier punto de unión, la suma de todas las corrientes que entran al nodo debe ser igual a la suma de todas las corrientes que salen del nodo.

∑Iadentro=∑Iafuera

La segunda regla de Kirchhoff o Ley de voltaje de Kirchhoff nos dice que la suma de los voltajes alrededor de una malla es igual a cero.

∑Vsubida=∑Vbajada

La ley de voltaje de Kirchhoff tiene algunas propiedades simpáticas:

* Puedes trazar una malla que comience en cualquier nodo. Si caminas alrededor de la malla y terminas en el nodo inicial, la suma de los voltajes de la malla es igual a cero.
* Puedes recorrer la malla en cualquier dirección y la ley de voltaje de Kirchhoff conserva su validez.
* Si un circuito tiene múltiples mallas, la ley de voltaje de Kirchhoff es válida para cada una.

3. DIAGRAMAS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe1/blob/main/Im%C3%A1genes/Circuito%20Resistivo%20Mixto.png">
</p>
<p align="center">
  Diagrama 3.1: Circuito Resistivo Mixto
</p>

4. LISTA DE COMPONENTES

* 1 Fuente de Voltaje de C.D.
* 2 Multimetros Digitales.
* 1 Resistor de 1kΩ
* 2 Resistores de 2.2kΩ
* 1 Resistor de 1.8kΩ
* 1 Resistor de 3.9kΩ
* 1 Protoboard

5. PROCEDIMIENTO

5.1 Arme el circuito que se muestra en el Diagrama 3.1.
5.2 Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 5.1.

<p align="center">
  Tabla 5.1: Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe1/blob/main/Im%C3%A1genes/Resultados%20obtenidos%20de%20voltaje%20y%20corriente%2C%20en%20cada%20elemento%20del%20circuito..jpeg">
</p>

5.3 Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada, considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con signo negativo. Anote los resultados en la tabla 5.2.

<p align="center">
  Tabla 5.2: Verificación de la LVK.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe1/blob/main/Im%C3%A1genes/Verificaci%C3%B3n%20de%20la%20LVK..jpeg">
</p>

5.4 Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando con signo positivo las corrientes que entran al nodo y con signo negativo las que salen del nodo. Anote los resultados en la tabla 5.3.

<p align="center">
  Tabla 5.3: Verificación de la LCK.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe1/blob/main/Im%C3%A1genes/Verificaci%C3%B3n%20de%20la%20LCK..jpeg">
</p>

5.5 Compare los resultados medidos con los valores obtenidos al analizar el circuito analíticamente y concluya al respecto.

PROCEDIMIENTO 

<p align="center">
  Maya 1
</p>
<p align="center">
  10+1KI_1-3.9K(I_1-I_2)-1.8KI_2=0
</p>
<p align="center">
  10-6.7KI_1+3.9KI_2=0
</p>
<p align="center">
  6.7I_1-3.9I_2=10       (1)
</p>
<p align="center">
  Maya 2
</p>
<p align="center">
  -2.2KI_2-2.2KI_2-3.9K(I_2-I_1)=0
</p>
<p align="center">
  -8.3KI_2+3.9KI_2=0    (2)
</p>

Sistema de Ecuaciones con (1) y (2)

<p align="center">  
  {(6.7I_1-3.9I_2=10@3.9I_1-8.3I_2=0)
</p>
Resolviendo :
<p align="center">
  I_1=2.053 mA       Esta es la corriente que circula en la primera maya
</p>
<p align="center">
  I_2=0.965 mA       Esta es la corriente que circula en la segunda maya
</p>

Para encontrar los voltajes ocupamos la ley de Ohm

<p align="center">
  V=I*R
</p>
<p align="center">
  VR_1=2.053mA*1K
</p>
<p align="center">
  VR_1=2.053 V
</p>

Para encontrar el voltaje en la resistencia 2 debemos hacer una diferencia entre la 
corriente 1 y la corriente 2

<p align="center">
  IR_2=I_1-I_2 
</p>
<p align="center">
  IR_2=2.053 mA-0.965 mA
</p>
<p align="center">
  IR_2=1.088 mA
</p>
<p align="center">
  VR_2=1.088 mA*3.9K
</p>
<p align="center">
  VR_2=4.24V
</p>
<p align="center">
  VR_3=0.965 mA*2.2K
</p>
<p align="center">
  VR_3=2.12V
</p>
<p align="center">
  VR_4=0.965 mA*2.2K
</p>
<p align="center">
  VR_4=2.12V
</p>
<p align="center">
  VR_5=2.053mA*1.8K
</p>
<p align="center">
  VR_5=3.69 V
</p>

Para poder calcular el error debemos aplicar la siguiente formula 

<p align="center">
error%=(Valor teorico-Valor medido)/(Valor teorico) x 100%
</p>

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

En este punto se debe especificar las aplicaciones secundarias necesarias, la configuración del terminal, así como cualquier otra información necesaria para que pueda funcionar el proyecto, tanto en hardware como en software.

7. CONCLUSIONES

Se estable las conclusiones de cada asunto investigado, implicaciones para la teoría y resultados de las experiencias. Estos siempre estarán en relaciona los objetivos generales y específicos.

8. BIBLIOGRAFÍA

Douglas C. Giancoli. Física  para  ciencias  e  ingenierıa. Pearson, 2008.

9. ANEXOS

