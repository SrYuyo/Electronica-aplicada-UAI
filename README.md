# **Electronica-aplicada-UAI**
Curso de electronica de lla UAI. En el hay codigos y teoria sobre Electronica y Arduino.

# Clase 14/08
La electricidad se define como el flujo de una carga eléctrica, mediante los electrones. 

El modelo atómico de Bohr es uno de los más enseñados. En él plantea 3 postulados.
  - Los electrones trazan órbitas circulares en torno al núcleo sin irradiar energía.
  - Las órbitas permitidas a los electrones son aquellas con cierto valor de momento angular. 
  - Los electrones emiten o absorben energía al saltar de una órbita a otra y al hacerlo emiten un fotón que presenta la diferencia de energía entre ambas órbitas. 

Modelos a lo largo de la historia

![image](https://github.com/user-attachments/assets/55bfd6f0-6c8c-405c-a8df-eca652aafbc9)

Algunos elementos, como los metálicos, poseen electrones fáciles de remover, por lo que son llamados conductores. En el caso contrario son denominados aislantes, como el aire, vidrio y goma.

Los electrones de valencia forman enlaces con otros átomos, en el caso de los metales, como no están cerca del núcleo, pueden separarse del átomo y dar propiedades eléctricas de los elementos. 

La conductividad de un material dependerá de la siguiente fórmula:

![image](https://github.com/user-attachments/assets/ca4c42da-53bb-4dc2-b1f8-a5cbf3431b92)

En donde Sigma es la conductividad del material y Rho es el coeficiente de resistividad. La cual depende del área y la resistencia propia del material.

**La electricidad estática** es producida en materiales no conductores. En este caso la carga inducida permanece en reposo, pues no puede moverse por ningún medio. Se puede generar una tensión eléctrica entre las partes. Se puede lograr mediante frotación, contacto o inducción.

**La electricidad dinámica** es el movimiento ordenado de cargas eléctricas en el interior de un conductor. 

**Voltaje** o diferencia de potencial es la fuerza necesaria para trasladar los electrones desde el polo positivo al negativo. Es decir la fuerza necesaria para el flujo de electrones. 

Cabe destacar que hay una confusión en el sentido del flujo de la corriente, esto debido a la definición de la corriente convencional. Aún así esto no afecta matemáticamente en las fórmulas, pero en algunos libros está de la forma convencional y en otros el flujo de electrones. 

La corriente se mide en amperes, es decir un coulomb por segundo.

La Ley de Ohm establece que el voltaje es igual a la resistencia por los amperios.

El cable tierra es una colección propia con la tierra, esto permite proteger ante cortocircuitos.

**Actividad circuito escalera**

![Incredible Maimu](https://github.com/user-attachments/assets/234d5a74-a1f9-4ee5-8b92-d68fe311cc32)

El circuito permite encender un led por uno de los dos interruptores. Es decir que si muevo uno de los switch y no está apagado el led este se encenderá, caso contrario si está encendido.

Otra forma sencilla de interpretarlo es: 

![image](https://github.com/user-attachments/assets/e0be8522-f022-431b-8ea3-0ef89c5bfeaa)

# **Clase 21/08**
Los sistemas numéricos son los conjuntos de símbolos y reglas que permiten representar datos numéricos. Nuestro sistema numérico (sistema decimal) es posicional, es decir que importa la posición de la cifra (unidad, decena, centena, etc). 


El sistema binario se basa en dos símbolos, esto lo hace esencial para la informática, pues es el nivel más básico posible con el que trabajar.

![image](https://github.com/user-attachments/assets/624c3bf2-f9e6-4c50-9acc-0a41a4ba60a0)

**Actividad**

![Sizzling Kasi](https://github.com/user-attachments/assets/81b2922f-caed-46db-a51b-dd776d268057)

En el circuito de simulación de lanzamiento se tienen al inicio dos conectores de tipo (y) lógicamente, pues ambos deben estar encendidos para que se pueda hacer la siguiente condición de tipo o. En esta al activar cualquiera de los interruptores se podrá completar el circuito. 

Existen dos tipos de corrientes, la alterna (AC) y la continua (DC).

**Actividad**
**Generación de Corriente Alterna (CA)**
La **corriente alterna (CA)** se genera mediante el uso de generadores eléctricos. En estos, un conductor (como una bobina de alambre) gira dentro de un campo magnético. Cuando el conductor corta las líneas del campo magnético, se induce una corriente eléctrica. La dirección de esta corriente cambia constantemente porque el generador rota en un eje, lo que crea una **onda alternante**. Es decir, la corriente fluye primero en una dirección y luego cambia a la dirección opuesta de manera continua.
**Ejemplo de uso:** La corriente alterna es la que se usa comúnmente en el suministro de electricidad para casas y edificios, ya que es más eficiente para transmitir a largas distancias.

**Conversión de CA a CC**

Para transformar la **corriente alterna en corriente continua (CC)**, se utiliza un **rectificador**. Un rectificador es un dispositivo que permite que la corriente solo fluya en una dirección. Existen diferentes tipos de rectificadores, pero los más comunes son los que utilizan **diodos**, que bloquean el flujo de corriente en una dirección y lo permiten en la otra, generando una corriente continua.
**Ejemplo de uso:** Los cargadores de teléfonos móviles convierten la corriente alterna de la red eléctrica en corriente continua para cargar la batería.
**Conversión de CC a CA**
Para transformar la corriente continua en corriente alterna, se utiliza un dispositivo llamado inversor. El inversor cambia la polaridad de la corriente continua a intervalos regulares para generar una onda alterna, imitando así la corriente alterna. Estos sirven para suministrar energía a dispositivos que requieren CA a partir de fuentes de energía que generan CC, como los paneles solares.
**Ejemplo de uso:** En los sistemas de energía solar, los inversores convierten la corriente continua generada por los paneles solares en corriente alterna para usarla en la red eléctrica doméstica.
**Circuitos resistivos**
Todos los cuerpos tienen la propiedad de oponerse en cierta forma al paso de la corriente eléctrica, es decir la resistencia eléctrica como propiedad. Según el valor de esta es como se clasifican los materiales entre conductores, semiconductores o aislantes.  Ahora bien los materiales semiconductores implica que el material se comporta como conductores bajo ciertas condiciones, en el caso contrario son aislantes. Algunos ejemplos son el germanio, el silicio y el arseniuro de galio.

![image](https://github.com/user-attachments/assets/2e573a1b-11ae-460d-9f39-50aea6515a17)

Los conductores a pesar de dar paso a la electricidad, aún así presentan cierta resistencia, esta es directamente proporcional a la longitud del mismo (L) y la resistividad del material, por lo tanto es inversamente proporcional al tamaño de su sección.

![image](https://github.com/user-attachments/assets/f47101a9-b265-48b5-b518-bfc56d6d22d1)

Un dato interesante es que los desfibriladores tienen entre 4 a 7 amperios. 

Como la electricidad es peligrosa existen distintas formas de protegernos de ella, para así utilizarla en el día a día. 

![image](https://github.com/user-attachments/assets/0ee081dd-bdc0-45a7-a849-be2bf8f8eb38)

![image](https://github.com/user-attachments/assets/299f0f51-b2f0-4cdc-8e3a-008a0b0a9c59)

Para el circuito en serie la corriente fluye a través de cada resistor, uno
tras otro, porque no tiene otros caminos a seguir. La corriente es igual en todos los componentes del circuito, pero los voltajes se dividen. 

![image](https://github.com/user-attachments/assets/40856af2-66a1-43a7-9079-57e28fd1e8c9)

Para el circuito paralelo los componentes o resistores van conectados juntos por ambos extremos de conexión. La corriente puede ir por cada resistor. el voltaje es igual en los componentes. 

![image](https://github.com/user-attachments/assets/03b87cbe-9109-4326-9e8d-a7e3800bb9ca)

# **Clase 28/08**
**Códigos de colores**

![image](https://github.com/user-attachments/assets/36d49ce9-a550-4504-a8c7-370590c52468)

![image](https://github.com/user-attachments/assets/7ea72ac7-a3f6-43ed-adf0-6877422ebbf4)

Las resistencias son componentes eléctricos que limitan el flujo de corriente en un circuito. Se utilizan para controlar la cantidad de corriente y proteger otros componentes. Las resistencias vienen en diferentes tamaños y valores, medidos en ohmios (Ω).

**Resistencias convencionales:**
Resistencias comunes: Tienen un cuerpo cilíndrico con dos terminales de metal y están codificadas por colores para indicar su valor de resistencia.
Materiales: Pueden estar hechas de carbono, metal u óxidos metálicos.

**Resistencia SMD (Surface-Mount-Device):**
Las resistencias SMD son componentes electrónicos muy pequeños y su valor de resistencia se indica mediante un código numérico impreso en su superficie, ya que no hay espacio suficiente para utilizar un código de colores como en las resistencias tradicionales.

Cómo leer el valor de una resistencia SMD: 

Código de 3 dígitos:
Los primeros dos números representan los dos primeros dígitos del valor de la resistencia. El tercer número indica cuántos ceros debes añadir al valor. 

Ejemplo: Si el código es 472, el valor será 47 seguido de dos ceros: 4700 ohmios (o 4.7 kΩ).

Código de 4 dígitos:
Los primeros tres números representan los tres primeros dígitos del valor de la resistencia. El cuarto número es el multiplicador, que indica cuántos ceros agregar.

Ejemplo: Si el código es 1001, el valor será 100 seguido de un cero: 1000 ohmios (o 1 kΩ).

Código de letras:
A veces, en valores muy bajos (menores de 10 ohmios), se utiliza una letra "R" para representar un punto decimal.

Ejemplo: Un código de 4R7 significa 4.7 ohmios.

**Ley de ohm**

![image](https://github.com/user-attachments/assets/116ab258-ad18-4a90-be1a-b9d4e9c95384)

**Uso de multimetro**

[https://youtu.be/OC0eJormJSQ]

**Baterías**

![image](https://github.com/user-attachments/assets/8a2bf7eb-4b0d-4311-b81f-269bce33bc96)

**Potencia eléctrica**
La **potencia eléctrica** es la cantidad de energía que un dispositivo o sistema eléctrico consume o genera en un periodo determinado. Se mide en **vatios (W)**, y se calcula utilizando la siguiente fórmula:

$$P=VI$$

Donde:
  - **P** es la potencia en vatios (W), 
  - **V** es el voltaje en voltios (V),
  -**I** es la corriente en amperios (A).
La potencia eléctrica representa la **velocidad a la que se consume o genera energía.** En términos simples, un dispositivo con mayor potencia consume más energía por segundo. Por ejemplo, un bombillo de 100 W consume más energía que uno de 60 W cuando están encendidos por el mismo tiempo.
**Leyes de kirchhoff** 
La ley de los nodos, o primera ley de Kirchoff establece que “En cualquier nodo, la suma de las corrientes que entran en ese nodo es igual a la suma de las corrientes que salen. De forma equivalente, la suma de todas las corrientes que pasan por el nodo es igual a cero” 

![image](https://github.com/user-attachments/assets/d3816bc4-c188-447f-91ac-a20ef8baa97d)

La suma de los voltajes alrededor de una trayectoria o circuito cerrado debe ser cero. Matemáticamente, está dada por:

![image](https://github.com/user-attachments/assets/86ed9efe-24fe-4772-9caf-57d18ffb3937)

**Divisor de tención**
Un divisor de tensión es una configuración de circuito eléctrico que reparte la tensión de una fuente entre una o más resistencias conectadas en serie.

![image](https://github.com/user-attachments/assets/0e434d86-e722-45e5-94c6-a27d105d1b7d)

[https://www.youtube.com/watch?v=1-ucOtWF4W0&ab_channel=Shakmuria]

**Clase 04/09**




