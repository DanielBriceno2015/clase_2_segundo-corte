
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

![Logo](ChatGPT Image 13 abr 2025, 03_27_14 p.m..png)

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

 ## 6. Conclusion

El modelamiento de sistemas mecánicos mediante ecuaciones diferenciales es una herramienta fundamental en ingeniería y física para describir con precisión el comportamiento dinámico de estructuras y mecanismos. Al analizar fuerzas como la masa, el amortiguamiento y la rigidez, se obtienen ecuaciones que reflejan la relación entre entradas (como fuerzas aplicadas) y salidas (como desplazamientos o velocidades).

Este enfoque permite no solo comprender el funcionamiento del sistema, sino también predecir su respuesta ante diferentes condiciones, optimizar su diseño y desarrollar estrategias de control. La formulación matemática mediante ecuaciones diferenciales es, por tanto, una base esencial para la simulación, análisis y diseño de sistemas mecánicos complejos.


 ## 7. Referencias


 
