
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

![Logo](data:image/png;base64,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)


Figura 2.  sistemas acoplados


 ## 6. Ejercicios 
 
 📚 Hallar la funcion de transferencia 

![Logo]( https://sdmntprwestus.oaiusercontent.com/files/00000000-8288-6230-8e63-44d95d8a6718/raw?se=2025-04-13T19%3A51%3A42Z&sp=r&sv=2024-08-04&sr=b&scid=86343abb-54e1-53c1-b55b-a87a4886367e&skoid=acefdf70-07fd-4bd5-a167-a4a9b137d163&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-04-13T07%3A24%3A14Z&ske=2025-04-14T07%3A24%3A14Z&sks=b&skv=2024-08-04&sig=b5LcNXsP8yC8eHZpkfHmApReKmaaL87suR0nTU%2BsVMU%3D)

Figura 3. sistema masa resorte amortiguador amortiguador

𝑚
1
,
𝑚
2
m 
1
​
 ,m 
2
​
 : masas

𝑘
1
,
𝑘
2
k 
1
​
 ,k 
2
​
 : constantes de resorte

𝑏
1
,
𝑏
2
b 
1
​
 ,b 
2
​
 : coeficientes de amortiguamiento

𝑢
(
𝑡
)
u(t): fuerza de entrada aplicada a 
𝑚
1
m 
1
​
 

𝑥
1
(
𝑡
)
,
𝑥
2
(
𝑡
)
x 
1
​
 (t),x 
2
​
 (t): desplazamientos de 
𝑚
1
m 
1
​
  y 
𝑚
2
m 
2
​
### Ley de newton

$m_1 \ddot{x}_1 + (b_1 + b_2) \dot{x}_1 + (k_1 + k_2) x_1 - b_2 \dot{x}_2 - k_2 x_2 = u(t)$

 ## 6. Conclusion

El modelamiento de sistemas mecánicos mediante ecuaciones diferenciales es una herramienta fundamental en ingeniería y física para describir con precisión el comportamiento dinámico de estructuras y mecanismos. Al analizar fuerzas como la masa, el amortiguamiento y la rigidez, se obtienen ecuaciones que reflejan la relación entre entradas (como fuerzas aplicadas) y salidas (como desplazamientos o velocidades).

Este enfoque permite no solo comprender el funcionamiento del sistema, sino también predecir su respuesta ante diferentes condiciones, optimizar su diseño y desarrollar estrategias de control. La formulación matemática mediante ecuaciones diferenciales es, por tanto, una base esencial para la simulación, análisis y diseño de sistemas mecánicos complejos.


 ## 7. Referencias


 
