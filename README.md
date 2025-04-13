
# Modelamiento de sistemas mecanicos acoplados y verticales

El modelamiento de sistemas mecánicos permite analizar el comportamiento dinámico de estructuras y mecanismos sometidos a fuerzas externas e internas. 

En particular, los sistemas mecánicos acoplados y verticales son comunes en aplicaciones como vehículos, estructuras de múltiples pisos, y maquinaria industrial, donde múltiples masas interactúan entre sí a través de elementos como resortes y amortiguadores.

## 1. Introduccion

Introduccion a modelamiento de sistemas mecanico acoplados y verticales


## 2. Aplicaciones típicas
Sistemas de suspensión automotriz (con masas representando ruedas y carrocería).

Estructuras de edificios ante sismos (pisos representados como masas).

Sistemas robóticos de múltiples grados de libertad.






## 3. Definiciones

🔑 **Ley de hooke** la deformación elástica que sufre un cuerpo es proporcional a la fuerza que produce tal deformación, siempre y cuando no se sobrepase el límite de elasticidad.


🔑 **resorte** Un componente mecánico que almacena y libera energía. También se le conoce como muelle.

🔑**Sistema mecánico**
Conjunto de cuerpos (masas, resortes, amortiguadores, etc.) que interactúan mediante fuerzas mecánicas, y cuyo comportamiento se estudia usando las leyes del movimiento.

🔑**Acoplamiento**
Condición en la cual el movimiento de una parte del sistema afecta a otra debido a la conexión mediante elementos como resortes o amortiguadores.

🔑 **Grado de libertad (GDL)**
Número de variables independientes que describen el movimiento del sistema. Un sistema con 
𝑛
n masas tiene típicamente 
𝑛
n grados de libertad.

🔑 **Ecuación diferencial**
Relación matemática que describe cómo varía el movimiento (posición, velocidad, aceleración) de las masas con el tiempo.

🔑 **Matriz de rigidez (K)**
Matriz que relaciona los desplazamientos del sistema con las fuerzas elásticas. Depende de las constantes de los resortes.

🔑 **Matriz de amortiguamiento (C)**
Matriz que representa la disipación de energía del sistema debido a los amortiguadores.

🔑 **Matriz de masas (M)**
Matriz diagonal que contiene las masas del sistema, usada para calcular las aceleraciones.

🔑 **Vibración**
Movimiento oscilatorio de una masa alrededor de una posición de equilibrio, característico en sistemas con resortes.

##4. Sistemas mecanicos acoplados y verticales

Los elementos básicos de todo sistema mecánico son la masa, el resorte y el amortiguador. El estudio del movimiento en sistemas mecánicos se corresponde con el análisis de sistemas dinámicos.

### 4.1 sistemas verticales 

En los sistemas verticales, la dirección del movimiento es afectada por la gravedad, lo cual modifica el equilibrio estático del sistema. En este caso, las ecuaciones diferenciales incluyen el peso de las masas (
𝑚
𝑔
mg) como parte de las fuerzas externas. Sin embargo, si se considera el análisis respecto a la posición de equilibrio, el término gravitacional se puede eliminar, simplificando el análisis dinámico.

![Logo](https://masam.cuautitlan.unam.mx/dycme/dsf/wp-content/uploads/sites/11/2021/07/masaresamor.svg)


Figura 1. sistemas verticales 

### 4.2 sistemas acoplados
El modelamiento de sistemas acoplados consiste en representar y analizar sistemas mecánicos en los que dos o más elementos (como masas) están conectados de forma que el movimiento de uno influye en el otro. Estas conexiones se dan a través de resortes, amortiguadores u otros elementos, y el objetivo es describir el sistema mediante ecuaciones diferenciales que predicen su comportamiento dinámico.



Figura 2.  sistemas acoplados


 ## 6. Ejercicios 
 
 📚 Hallar la funcion de transferencia 

![Logo](https://virtual.cuautitlan.unam.mx/intar/ime/wp-content/uploads/sites/15/2021/06/Sist2Orden.jpg)

Figura 3. sistema masa resorte amortiguador amortiguador


### Ley de newton

### Ecuación para la masa m1

$m_1 \ddot{x}_1 + (b_1 + b_2) \dot{x}_1 + (k_1 + k_2) x_1 - b_2 \dot{x}_2 - k_2 x_2 = u(t)$

### Ecuación para la masa m2

$m_2 \ddot{x}_2 + b_2 \dot{x}_2 + k_2 x_2 - b_2 \dot{x}_1 - k_2 x_1 = 0$

 ## 6. Conclusion

El modelamiento de sistemas acoplados y verticales permite analizar cómo interactúan múltiples componentes mecánicos, considerando fuerzas como resortes, amortiguadores y gravedad. A través de ecuaciones diferenciales y técnicas como la transformada de Laplace, se puede predecir y controlar el comportamiento dinámico del sistema. Esta herramienta es clave en el diseño de estructuras, máquinas y sistemas de control.

 ## 7. Referencias


 

