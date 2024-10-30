# **Electronica-aplicada-UAI**
Curso de electrónica de la UAI. En él hay códigos y ejercicios sobre electrónica además de Arduino.

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

# **Clase 04/09**
Cuando calculo el Voltaje en un punto veo cuanto cayó en ese punto y se debe restar con el voltaje total.

**Actividad**

Led conectado con una resistencia en serie con una resistencia de 1kohm. Tiene una iluminación normal, en cierta forma.

![image](https://github.com/user-attachments/assets/aa8c53b5-face-4e64-9da5-86187eeb84d8)

Ahora si la resistencia cambia a 100 ohms sale una advertencia, pues la cantidad de energía que pasa puede quemar el LED.

![image](https://github.com/user-attachments/assets/1bef0a36-89b1-4bed-8f28-33569fc11bc5)

La resistencia es tan baja (10m ohms) que el led se quema dada la cantidad de corriente que pasa.

![image](https://github.com/user-attachments/assets/27f65f22-6ef1-4dcd-a786-9b80c35e3433)

Al conectar una foto resistencia podemos regular la intensidad en la que se ilumina el led y además el voltaje se regula en base a la cantidad de luz que recibe la fotorresistencia de forma inversa. Este circuito es útil para luces automáticas.

![image](https://github.com/user-attachments/assets/7d578496-4378-4193-ab48-231381d3081a)

Al momento de agregar un motor con la foto resistencia hacemos que el voltaje se disminuya en base a la cantidad de luz recibida por la resistencia. En el caso de que haya mucha luz el motor recibe menos voltaje, por lo que mantiene la misma corriente y permite que gire más rápido, caso contrario el motor gira más lento, pero tiene más fuerza.

![image](https://github.com/user-attachments/assets/dba23a43-8df8-4e80-b58c-c49c2750e4b8)

**Como entender un circuito**

Un diagrama de bloques te proporciona una visión general de cómo funcionan juntos los circuitos individuales en un sistema. Verás cada circuito representado como un "bloque" (rectángulo u otra forma, según la aplicación). Las líneas de interconexión, a veces con flechas en uno o ambos extremos, muestran cómo los circuitos se combinan para formar el sistema completo y cómo fluyen las corrientes y señales entre esos circuitos.

![image](https://github.com/user-attachments/assets/4abcd1ee-dc61-44cb-83b3-4408d1c2cc7b)

Un **diagrama esquemático** (a menudo simplemente llamado esquemático) muestra cada componente en un circuito. Cada  componente tiene su propio símbolo especial. Las líneas entre los componentes revelan cómo se conectan entre sí y a una fuente de alimentación, para que realicen una función u operación específica.

![image](https://github.com/user-attachments/assets/66a9e7f1-6e32-4ea1-882f-81a89e9ee9a5)

Un **diagrama pictórico** (a veces llamado layout diagram) muestra la disposición física de los componentes en una placa de circuito o chasis para que puedas identificarlos para su instalación, prueba o reemplazo. Algunos de estos "diagramas" son fotografías reales. Sin embargo, ten en cuenta que las imágenes rara vez revelan los eventos eléctricos que ocurren en un circuito o sistema. 

![image](https://github.com/user-attachments/assets/f6feb8a6-faf4-48f9-ab0e-eb3ea65194af)

**Condensadores**

![image](https://github.com/user-attachments/assets/bbd60027-8ce3-40fb-bf89-5a01e4365d26)

El condensador es otro componente electrónico, este permite almacenar energía en pequeñas cantidades para devolverla cuando sea necesario. 

En su interior hay dos placas metálicas (armadura) y un material aislante (dieléctrico) en medio. Al haber tensión en el circuito se almacena carga en estas placas. 

**Capacitancia:**

La capacitancia (C) es la capacidad de un condensador para almacenar carga eléctrica. Se mide en faradios (F), y representa cuánta carga puede almacenar el condensador por cada voltio aplicado. La fórmula básica de la capacitancia es:

$C=Q/V$

**C** es la capacitancia en faradios (F),
**Q** es la carga almacenada en el condensador en culombios (C),
**V** es la diferencia de potencial (voltaje) entre las dos placas en voltios (V).

La energía almacenada en un condensador puede calcularse por: 

$E=(1/2)*CV^2$

**E** es la energía almacenada en julios (J)
**C** es la capacitancia en faradios (F)
**V** es el voltaje aplicado en voltios (V)

**Conexiones en serie y paralelo**

![image](https://github.com/user-attachments/assets/13799fd3-51a2-41ee-a3c3-cd25ee523228)

![image](https://github.com/user-attachments/assets/12ed1a64-7fcc-461d-aaf5-55ff815246df)

**Indutores**

Un inductor es un componente pasivo que almacena energía en forma de campo magnético cuando una corriente eléctrica fluye a través de él. Se construye generalmente con una bobina de alambre enrollada, y su principal característica es la inductancia, que mide su capacidad para resistir cambios en la corriente. Losinductores se utilizan en muchos circuitos eléctricos,especialmente en filtros y fuentes de alimentación.

La **inductancia** (L) es la propiedad del inductor que determina la cantidad de energía que puede almacenar en su campo magnético para una corriente dada. Se mide en henrios (H). La inductancia depende del número de vueltas de la bobina, el área de la sección transversal y el tipo de material alrededor del inductor.

La fórmula básica que describe la inductancia es:

$V=L dL/dT$

**V** es la tensión inducida (voltaje) en voltios (V)
**L** es la inductancia en henrios (H)
$**dI/dt**$ es la tasa de cambio de la corriente en amperios por segundo (A/s)

Esta fórmula indica que el voltaje inducido en el inductor es proporcional a la rapidez con la que cambia la corriente.

**Conexiones en serie y paralelo**

![image](https://github.com/user-attachments/assets/df7ec98d-e40f-424f-9055-6b6b8cb27670)

**Interruptores**

![image](https://github.com/user-attachments/assets/0a8634d2-ed91-4de3-8bef-4d0018d29725)
![image](https://github.com/user-attachments/assets/e842efb0-bc14-4f2a-bcb1-5ac66378f54b)

**Fuentes de alimentación**

![image](https://github.com/user-attachments/assets/e890ca17-733c-409c-b847-12c632d3962b)

# **11/09**

![image](https://github.com/user-attachments/assets/7f046d13-4286-4e1b-baee-48fce6c30e55)

Los transistores son dispositivos semiconductores fundamentales en la electrónica moderna, utilizados para amplificar y conmutar señales eléctricas. Desempeñan un papel crucial en casi todos los dispositivos electrónicos, desde radios hasta computadoras.

Los transistores tienen una amplia variedad de aplicaciones en la electrónica, que incluyen:

**Amplificación de Señales:** Los transistores pueden amplificar señales débiles, lo que es esencial en radios, televisores y equipos de audio.

**Conmutación:** Se utilizan para encender o apagar dispositivos eléctricos, como en fuentes de alimentación, sistemas de control y computadoras.

**Circuitos Integrados:** Forman la base de los circuitos integrados, que son fundamentales en microprocesadores y microcontroladores.

**Osciladores:** En combinación con otros componentes, los transistores pueden generar señales de frecuencia, utilizadas en transmisores y receptores.

**Reguladores de Voltaje:** Pueden usarse para mantener un voltaje constante en circuitos eléctricos.

**Sensores:** Algunos transistores se usan en sensores que detectan cambios en condiciones ambientales, como temperatura y luz.

**Transistores Bipolares (BJTs):** Tienen tres capas de material semiconductor, formando dos uniones p-n. Los tipos más comunes son:

  - Transistor NPN: Compuesto por una capa de material tipo p (positiva) entre dos capas tipo n (negativas).

  - Transistor PNP: Compuesto por una capa tipo n entre dos capas tipo p.

![image](https://github.com/user-attachments/assets/54c77e86-6c13-46f4-8ad4-a7734b133632)

Estos transistores poseen 3 terminales: Base, colector y emisor. 

<https://www.youtube.com/watch?v=dIV5l9cx_ck&ab_channel=Electr%C3%B3nicaFP>
<https://www.youtube.com/watch?v=zh7PeHAZRLY&ab_channel=MentalidadDeIngenier%C3%ADa>

**Actividad**

![image](https://github.com/user-attachments/assets/cabd6d35-9a35-4c8f-ac9d-dbe8c71e817a)

La conclusión es que al agregar un condensador de 100 μF en paralelo con la resistencia de 10 kΩ, el voltaje sobre la resistencia se mantiene más constante durante el ciclo negativo de la onda sinusoidal. Esto sucede porque el condensador se carga durante el ciclo positivo y luego ayuda a suministrar voltaje a la resistencia cuando la tensión de la fuente baja, suavizando así las fluctuaciones en el voltaje.

![image](https://github.com/user-attachments/assets/9db274b6-9e9f-4a72-bb62-d7325efe5fba)

**Breadboard**

![image](https://github.com/user-attachments/assets/86a4c683-4a40-411c-8794-8bfede58e3ff)

**Actividad esquematicos**

![image](https://github.com/user-attachments/assets/fdc9f709-2fb8-4704-8123-b63e1da5588f)

![image](https://github.com/user-attachments/assets/0a8d730f-bb2a-465f-821d-70e887612814)

![image](https://github.com/user-attachments/assets/e83ee150-b2cf-488c-b520-403d5fe65395)

![image](https://github.com/user-attachments/assets/e43dcf52-e41a-450a-8acc-62162baece81)

![image](https://github.com/user-attachments/assets/e6482cd9-8b9f-480f-8981-3800fcaec27e)

**Circuitos integrados**

Los circuitos integrados (CI) son dispositivos electrónicos que combinan múltiples componentes, como transistores y resistencias, en una sola pieza de material semiconductor, típicamente silicio. Permiten realizar funciones electrónicas complejas de manera compacta y eficiente. Sus características principales incluyen miniaturización, que reduce el tamaño de los dispositivos electrónicos; eficiencia, al integrar múltiples funciones y mejorar el rendimiento; costo, ya que su fabricación en masa reduce los costos; y velocidad, debido a que las conexiones cercanas facilitan la rápida transferencia de señales. Los tipos de circuitos integrados son analógicos, que manejan señales continuas; digitales, que operan con señales discretas (0 y 1); y mixtos, que combinan funciones analógicas y digitales.

![image](https://github.com/user-attachments/assets/11e1f97f-17da-4d7c-bca7-aa66e04b7334)

En modo estable, el temporizador 555 actúa como un oscilador que genera una onda cuadrada. La frecuencia de la onda se puede ajustar cambiando los valores de dos resistencias y un condensador conectado al chip.

**Circuito blink**

![image](https://github.com/user-attachments/assets/9608ec46-eec7-469d-8bd9-05dff8d89c0e)

R1: 4.7k Ohm
R2: 4.7k Ohm
R3: 1k Ohm
C1: 100 μF capacitor

Los valores de R1, R2 y C1 afectan la velocidad del parpadeo. Los valores más altos harán que el LED parpadee más lentamente, mientras que los valores más pequeños harán que el LED parpadee más rápido. La resistencia R3 está ahí para limitar la corriente al LED para que no se queme. Si desea establecer el parpadeo a una cierta velocidad, puede usar la fórmula al principio de este artículo para calcular la resistencia o capacitancia que necesita.


**Blink controlado por potenciometro**

![image](https://github.com/user-attachments/assets/f002e78b-e910-40b3-a572-10bcbce5bb0f)

R1: 4.7k Ohm
R2: 10k Ohm potenciómetro
R3: 1k Ohm
C1: 100 μF capacitor

El ajuste del potenciómetro cambiará la velocidad del parpadeo del LED.

**Blick Controlado por un fotoresistor**

![image](https://github.com/user-attachments/assets/1640fec0-0ba4-4457-9f27-329c995040b3)

R1: 4.7k Ohm
R2: Fotoresitor
R3: 1k Ohm
C1: 100 μF capacitor

La resistencia de un fotorresistor disminuye a medida que le incide más luz, por lo que el LED parpadea más rápidamente cuando se exponga a más luz.

# **25/09**

Hernando Barragán creador del código base de arduino

Arduino es una plataforma de hardware y software de código abierto que facilita la creación y desarrollo de proyectos electrónicos interactivos. Diseñada para ser accesible tanto para principiantes como para expertos, Arduino ha ganado popularidad en el ámbito de la educación, la robótica, las instalaciones artísticas y el desarrollo de prototipos. La flexibilidad de la plataforma permite a los usuarios programar, experimentar y construir dispositivos que pueden interactuar con el entorno físico, lo que la convierte en una herramienta clave en el movimiento de hardware libre. 


**Parte del hardware**

El hardware de Arduino consiste en una serie de placas de desarrollo que contienen un microcontrolador y diversas interfaces de entrada y salida. La placa más conocida es la Arduino Uno, que incluye: 
  
  - Microcontrolador: El corazón de la placa, generalmente un ATmega328, que ejecuta el código que el usuario carga en el dispositivo.

  - Pines de Entrada/Salida (I/O): Permiten la conexión de sensores y actuadores. Estos pines pueden ser digitales (para encender/apagar) o analógicos (para leer voltajes variables).

  - Conectividad: Muchas placas Arduino ofrecen conectividad USB para la programación y la alimentación del microcontrolador, así como opciones para comunicación inalámbrica o por medio de módulos adicionales (como WiFi o Bluetooth).

  - Alimentación: Las placas pueden estar alimentadas por diferentes fuentes, como USB, fuentes externas de corriente o baterías, lo que las hace adecuadas para una variedad de proyectos.


**Parte de software**

El software de Arduino se basa en el IDE (Entorno de Desarrollo Integrado), que permite a los usuarios escribir y cargar código a la placa. Este software incluye:

Lenguaje de Programación: El lenguaje utilizado por Arduino es una variante simplificada de C/C + +, lo que permite a los usuarios programar lógicamente sus dispositivos con un conjunto de funciones y bibliotecas específicas que facilitan la manipulación del hardware. 

Bibliotecas: Arduino incluye una gran variedad de bibliotecas que permiten a los usuarios interactuar fácilmente con componentes como motores, sensores, pantallas y más, ahorrando tiempo y esfuerzo en la codificación. 

Sketch: El código que se escribe se conoce como "sketch", y se compila y carga en la placa a través del IDE. Esto permite que la placa ejecute automáticamente las instrucciones cada vez que se enciende. 

Comunicación Serial: El software permite la comunicación serial entre el ordenador y la placa, lo que es útil para la depuración y para enviar o recibir datos de dispositivos externos.


**Placa arduino UNO R3**

![image](https://github.com/user-attachments/assets/22046ba9-9176-40d9-bd36-f0399d084ce5)

**Variables**

Las variables se utilizan para almacenar datos que pueden ser utilizados y manipulados durante la ejecución de un programa (sketch). 

int: Utilizada para almacenar números enteros, máximo de 16 bits.

float: Números decimales.

char: Caracteres. Utilizar ’’ para almacenar información. Apostrofe o comilla simple.

boolean: Almacena true o false.

byte: Almacena números enteros de 0 a 255.

String: Almacena texto. Utilizar “”. Comillas dobles.

**Links de referencia:**

[https://www.arduino.cc/reference/es/ ]

[https://arduino.cl/introduccion-a-los-tipos-de-dato-con-arduino/]

**Funciones**

setup(): Esta función se ejecuta una vez al inicio del programa y se utiliza para configurar los parámetros iniciales, como definir los modos de los pines (entrada o salida). 

loop(): Esta función se ejecuta en un ciclo continuo después de la función setup(). Aquí es donde se coloca el código que debe ejecutarse repetidamente.

**Estas dos funciones están si o si en el sketch**

Definidas por el usuario:  Permite realizar tareas personalizadas. Permiten agrupar código relacionado y pueden tomar parámetros y devolver valores.

```cpp
int suma(int a, int b) {
  return a + b; // Retorna la suma de a y b
}

```

Funciones de programa: Arduino incluye muchas bibliotecas que proporcionan funciones adicionales para trabajar con componentes como sensores y motores. Por ejemplo, la biblioteca Servo proporciona funciones para controlar servomotores. 

```cpp
#include <Servo.h> // Incluir la biblioteca Servo

Servo miServo; // Crear un objeto Servo

void setup() {
  miServo.attach(9); // Conectar el servomotor al pin 9
}

void loop() {
  miServo.write(90); // Mueve el servo a 90 grados
  delay(1000);       // Espera 1 segundo
  
  miServo.write(0);  // Mueve el servo a 0 grados
  delay(1000);       // Espera 1 segundo
}
```

**pinMode(). digitalWrite**

La función pinMode() indica si un pin es utilizado como entrada o como salida. Para utilizarla le entregas el número del pin a configurar y la constante INPUT o OUTPUT. Cuando un pin es configurado como entrada, el puede detectar el estado de un sensor. Una salida, puede controlar a un actuador como por ejemplo un LED.

La función digitalWrite() cambia el valor de un pin. Por ejemplo, en la siguiente línea configura el ledPin (pin 13) como HIGH, es decir 5 Volts. Si cambiamos por un LOW el pin entregará 0 Volts.

**Analogo v/s digital**

![image](https://github.com/user-attachments/assets/e436163d-a3f6-4ec4-b8e4-e98d3e8bccad)

**Actividad SOS o blink**


