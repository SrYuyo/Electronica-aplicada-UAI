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

$V=L*dL/dT$

**V** es la tensión inducida (voltaje) en voltios (V)

**L** es la inductancia en henrios (H)

$dI/dt$ es la tasa de cambio de la corriente en amperios por segundo (A/s)


Esta fórmula indica que el voltaje inducido en el inductor es proporcional a la rapidez con la que cambia la corriente.

**Conexiones en serie y paralelo**

![image](https://github.com/user-attachments/assets/df7ec98d-e40f-424f-9055-6b6b8cb27670)

**Interruptores**

![image](https://github.com/user-attachments/assets/0a8634d2-ed91-4de3-8bef-4d0018d29725)

![image](https://github.com/user-attachments/assets/e842efb0-bc14-4f2a-bcb1-5ac66378f54b)

**Fuentes de alimentación**

![image](https://github.com/user-attachments/assets/e890ca17-733c-409c-b847-12c632d3962b)

# **Clase 11/09**

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


**Actividad:**

![image](https://github.com/user-attachments/assets/32b1e006-8edc-452f-b59c-fbd09e890602)

En el circuito original, utilizamos un generador de función para alimentar el circuito con una onda sinusoidal de 10 Hz y una amplitud de 5V. La amplitud de 5V significa que la señal oscilará entre +5V y -5V. La resistencia de 10 kΩ se conecta como carga en este circuito:

**Funcionamiento del Circuito:**

  - Cuando el generador suministra la onda sinusoidal, la resistencia permite el paso de corriente eléctrica. El osciloscopio se utiliza para medir el voltaje sobre la resistencia. Este voltaje variará en función de la forma de onda suministrada por el generador.

  - Durante el ciclo positivo de la onda, la corriente fluye a través de la resistencia, y el voltaje sobre ella será positivo. En el ciclo negativo, la corriente cambia de dirección y el voltaje sobre la resistencia será negativo.

Al modificar el circuito agregando un condensador de 100 µF en paralelo con la resistencia de 10 kΩ:
![image](https://github.com/user-attachments/assets/5d6cd8eb-89cd-4fa6-9a99-6b1942ffb732)

Efecto del Condensador:

El condensador, al estar en paralelo, se carga durante el ciclo positivo de la onda. A medida que el voltaje aumenta, el condensador se carga y almacena energía.
Cuando la señal pasa al ciclo negativo, el condensador comienza a descargar su carga. Esto significa que el voltaje medido sobre la resistencia cambiará de manera más gradual, manteniendo ciertos niveles positivos de voltaje incluso cuando la señal de entrada del generador cambia a negativo.

Observación en el Osciloscopio:

Al observar el osciloscopio después de la modificación, el voltaje sobre la resistencia no cae tan drásticamente como lo hacía anteriormente. En su lugar, hay un relleno que mantiene el voltaje positivo un poco más de tiempo, debido a la descarga del condensador. Este fenómeno es el que produce una respuesta más suavizada en el voltaje sobre la resistencia.

Ciclo Positivo de la Onda:

Durante el ciclo positivo de la onda sinusoidal, la corriente fluye desde el generador de función hacia la resistencia y hacia el condensador. A medida que el voltaje alcanza su pico positivo, el condensador se carga, aumentando el voltaje sobre la resistencia.

Ciclo Negativo de la Onda:

En el ciclo negativo, la corriente cambia de dirección. La corriente fluye ahora desde el condensador hacia la resistencia. Como resultado, el condensador comienza a descargar su carga, suministrando corriente a la resistencia incluso cuando la señal del generador se vuelve negativa. Esto mantiene el voltaje sobre la resistencia más alto durante una parte del ciclo negativo.

El álgebra de Boole es una herramienta esencial en la electrónica moderna, ya que proporciona un marco matemático para el diseño y análisis de circuitos lógicos. Su capacidad para simplificar expresiones lógicas y realizar operaciones binarias es fundamental para el funcionamiento de dispositivos digitales, computadoras y sistemas de control, y su relevancia sigue creciendo con el avance de la tecnología.

![image](https://github.com/user-attachments/assets/18b3f34c-5e7c-4d07-9487-1e6abc298b4c)


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

# **Clase 25/09**

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

![image](https://github.com/user-attachments/assets/957fdeb2-78dc-4ce4-a515-0411da3a9641)

En el sigueinte codigo es una señal de SOS o pestañeo de un led. De todas formas eiste un chip que hace esta función. Cabe destacar que se uso una placa Arduino uno R3 y una versión de Arduino IDE 2.3.3

```cpp
void setup() {
  pinMode(8, OUTPUT);


}

void loop() {
  //Letra O
  digitalWrite(8, HIGH); //Punto
  delay(300);           
  digitalWrite(8, LOW); //Pausa
  delay(300);
  digitalWrite(8, HIGH); //Punto
  delay(300);           
  digitalWrite(8, LOW); //Pausa
  delay(300);
  digitalWrite(8, HIGH); //Punto

  //Pausa Larga
  delay(900);
  //Letra S
  digitalWrite(8, HIGH); //Punto
  delay(900);           
  digitalWrite(8, LOW); //Pausa
  delay(300);
  digitalWrite(8, HIGH); //Punto
  delay(900);           
  digitalWrite(8, LOW); //Pausa
  delay(300);
  digitalWrite(8, HIGH); //Punto

  //Pausa Larga
  delay(900);
 
  //Letra O
  digitalWrite(8, HIGH); //Punto
  delay(300);           
  digitalWrite(8, LOW); //Pausa
  delay(300);
  digitalWrite(8, HIGH); //Punto
  delay(300);           
  digitalWrite(8, LOW); //Pausa
  delay(300);
  digitalWrite(8, HIGH); //Punto

  //Pausa Larga
  delay(900);
}
```

Otro posible codigo eficiente puede ser el siguiente:

```cpp
const int ledPin = 8;   //pin del LED
const int duracionP = 300;     // duración del punto
const int pausa = 900;     // duración de la pausa larga

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  SOS('O');
  delay(pausa); 
  SOS('S'); 
  delay(pausa); 
  SOS('O');
  delay(pausa);
}

void SOS(char letter) {
  switch (letter) {
    case 'O':
    
      for (int i = 0; i < 3; i++) {
        digitalWrite(ledPin, HIGH); 
        delay(duracionP);          
        digitalWrite(ledPin, LOW);  
        delay(duracionP);          
      }
      break;

    case 'S':

      for (int i = 0; i < 3; i++) {
        digitalWrite(ledPin, HIGH); 
        delay(duracionP);          
        digitalWrite(ledPin, LOW);  
        delay(duracionP);          
      }
      break;

    default:
      break;
  }
}

```

SOS variable
![image](https://github.com/user-attachments/assets/e55d0759-9b3c-4a24-859e-797b1ccab8cb)



![image](https://github.com/user-attachments/assets/a092e44a-793f-43ad-86c0-79fe3fc0cd3a)

```cpp
void setup() {
  pinMode(8, OUTPUT); //rojo
  pinMode(7, OUTPUT); //verde

}

void loop() {
  //Verde
  digitalWrite(8, HIGH); //rojo
  delay(4000);        
  digitalWrite(8, LOW);
  digitalWrite(7, HIGH); //verde
  delay(4000);

  //parpadeo
  digitalWrite(7, HIGH);
  delay(2000);           
  digitalWrite(7, LOW);
  delay(1000);
  digitalWrite(7, HIGH);
  delay(500);
  digitalWrite(7, LOW);
  delay(200);
  digitalWrite(7, HIGH);
  delay(200);
  digitalWrite(7, LOW);

  digitalWrite(8, HIGH);
}
```

```cpp
void setup() {
  //semaforo 1
  pinMode(8, OUTPUT); //rojo
  pinMode(7, OUTPUT); //amarillo
  pinMode(6, OUTPUT); //verde

  //semaforo 2
  pinMode(13, OUTPUT); //rojo
  pinMode(12, OUTPUT); //amarillo
  pinMode(11, OUTPUT); //verde

}

void loop() {
  
  //estado incial
  digitalWrite(8, HIGH); //rojo semaforo 1
  digitalWrite(11, HIGH); //verde semaforo 2
  delay(4000);
  
  //transición
  digitalWrite(11, LOW); //verde semaforo 2
  digitalWrite(12, HIGH); //amarillo semaforo 2
  delay(1000);
  digitalWrite(12, LOW); //amarillo semaforo 2
  digitalWrite(13, HIGH); //rojo semaforo 2
  digitalWrite(8, LOW); //rojo semaforo 1
  digitalWrite(6, HIGH); //verde semaforo 1
  delay(4000);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH); //amarillo semaforo 1
  delay(1000);
  digitalWrite(7, LOW); //amarillo semaforo 1
  digitalWrite(13, LOW);

}

```

![image](https://github.com/user-attachments/assets/be2f7106-80a3-4664-b3e8-26f76f38e732)


Arduino cuenta con 13 pines configurables como entradas o salidas, siendo entradas por defecto. Es recomendable mantener las entradas en un estado conocido, utilizando resistencias de pull-up (conectadas a +5V) o pull-down (conectadas a tierra), siendo una resistencia de 10K un buen valor. Cuando un pin se configura como salida, puede proporcionar un máximo de 40 mA sin dañarse, lo cual es suficiente para encender un LED (junto con una resistencia en serie), pero no para la mayoría de los relés, solenoides o motores. En caso de un cortocircuito en uno de los pines, este puede dañarse mientras que el resto del microcontrolador seguirá funcionando, por lo que se recomienda usar una resistencia de 470 ohmios o 1K ohmios para limitar la corriente.


Para un pulsador tenemos qeu conectarlo a una resistencia pull-up o pull-down para darle un valor definido a la entrada del Arduino cuando no esté pulsado. 

![image](https://github.com/user-attachments/assets/7b954343-ede3-4427-9496-7bbb609ad523)

Cuando un pulsador en un circuito con Arduino, es crucial emplear una resistencia pull-up o pull-down para garantizar que la entrada tenga un estado definido cuando el pulsador no está presionado. 

Resistencia Pull-Up: Se conecta entre el pin de entrada y el voltaje positivo (+5V). Cuando el pulsador está abierto, el pin está en estado alto (HIGH). Al presionar el pulsador, se conecta a tierra (GND), cambiando el pin a estado bajo (LOW).

Resistencia Pull-Down: Se conecta entre el pin de entrada y tierra (GND). Sin presionar el pulsador, el pin está en estado bajo (LOW). Al presionar el pulsador, se conecta a +5V, llevando el pin a estado alto (HIGH).

Generalmente se utilizan resistencias de 10K ohmios. En Arduino, también se pueden habilitar resistencias pull-up internas con el comando pinMode(pin, INPUT_PULLUP). Esto evita la necesidad de resistencias externas.

**Conexión de pulsadores tipo push**

![image](https://github.com/user-attachments/assets/e387765d-430c-43e7-80e6-fe267a1cbb00)


![image](https://github.com/user-attachments/assets/56e352f6-4d7b-4220-93c2-d2d05c5f0fc1)


```cpp
//Se establece el modo como INPUT
pinMode(pin, INPUT);

//Se lee el valor del pin con digitalRead() y se almacena la lectura en una //variable previamente declarada. La lectura será 1 (HIGH) o 0 (LOW).

int lectura;
lectura = digitalRead(pin);
```


**Estructura if else**

```cpp
if (temperatura > 30){
  irPlaya();
}

else if (temperatura < 5){
  meterseCama();
}

else {
  estudiarElectronica();
}

```

**Actividad**
![image](https://github.com/user-attachments/assets/4c69e9ea-4bb2-4bad-ac33-8ade613b2332)

# **Clase 02/10**

El microcontrolador Atmega en Arduino cuenta con un conversor analógico-digital (A/D) de 6 canales. Este conversor tiene una resolución de 10 bits, lo que permite obtener valores enteros entre 0 y 1023. Aunque su función principal es leer sensores, los pines analógicos también pueden utilizarse como entradas o salidas discretas de propósito general (GPIO), al igual que los pines numerados del 0 al 13.

Codigo de lectura para pines analogicos

```cpp
//No es necesario establecer el modo del pin analógico.
//Se lee el valor del pin con analogRead() y se almacena la lectura en una
//variable int previamente declarada. La lectura será un valor entre 0 y 1023

int lectura_analogica
lectura_analógica = analogRead(pin);

/*
¿Por qué analogRead() va de 0 a 1023?
Porque el convertidor análogo-digital de Arduino tiene 10 bits, y por
lo tanto hay 210 (=1024) valores posibles
*/

```

Aprovechemos la ventaja del Pin Analógico para hacer la lectura de varios botones. Como sabes, el valor analógico varía de 0 a 1023, lo que significa un rango de entrada de 0 a 5V. Utilizando el método del divisor de voltaje para cada botón, diferentes caídas de voltaje debido a diferentes valores de resistencias a través de cada botón tendrán diferentes salidas de voltaje, por lo tanto, cada botón puede ser identificado usando solo un pin analógico. En la placa Arduino UNO, el Pin Analógico ocupado para la función de botón está fijado en A0.


![image](https://github.com/user-attachments/assets/73334d55-f8d1-428b-963a-450914b4317d)

![image](https://github.com/user-attachments/assets/11837640-94d2-42ba-86b7-3c37314e8857)

**Actividad** HACER!!!

![image](https://github.com/user-attachments/assets/697c8115-4b85-4822-a732-3841b1032a96)

![image](https://github.com/user-attachments/assets/1e962a08-150f-4c34-a692-599cfabcd32e)


**Interfaz de arduino**
![image](https://github.com/user-attachments/assets/dcf6d12d-9b5c-4901-95dc-f987d4ac6e68)

```cpp
//Se inicializa la conexión Serial en el setup().
//El argumento es la velocidad de transmisión de datos (baud rate)

void setup(){
  Serial.begin(9600);
}

void loop () {

  int variable
  variable = analogRead(pin);
  Serial.print(variable); //Muestra un valor en el Monitor Serial
  Serial.println(variable); //Muestra en una línea nueva
}


```

**Serial Plotter** es una herramienta en Arduino IDE que permite graficar datos enviados por el puerto serial en tiempo real, facilitando así la visualización de datos analógicos, como lecturas de sensores. Para utilizar Serial Plotter, se debe abrir el menú "Herramientas", seleccionar "Serie" y luego hacer clic en "Monitor de serie". En el Monitor de serie, se debe hacer clic en el botón "Plotter" en la esquina superior derecha. Una vez abierto, se pueden enviar datos al monitor de serie utilizando la función `Serial.println()`. Por ejemplo, si hay un sensor conectado al pin analógico A0, se puede leer su valor y enviarlo al monitor de serie usando un código apropiado.

Además de esto se pueden graficar distintas variables de la siguiente manera en el codigo:

```cpp
int valor;
void setup (){
  Serial.begin(9600);
}

void loop(){
  valor = analogRead(A0);
  Serial.print(valor);
  Serial.print(",");
  Serial.println(valor/2);
}
```

# **Clase 9/10**

Actividad
![image](https://github.com/user-attachments/assets/4833a13c-0e04-4b2e-be3d-8e05e8ec0ebb)

![image](https://github.com/user-attachments/assets/3ee9d2f0-4a02-4237-89ba-d13f936b8234)

```cpp
void setup() {
  Serial.begin(9600); 
}

void loop() {
  int potV = analogRead(A0); 
  Serial.println(potV); 
  delay(500); 
}
```

**Actividad**

![image](https://github.com/user-attachments/assets/346ecd4f-253c-4131-9e68-6ccaa587c0ac)

![image](https://github.com/user-attachments/assets/f42ad981-9b7e-4fb7-bd4f-ce70d75b970e)

```cpp
void setup() {
  Serial.begin(9600);
}

void loop() {
  int potV = analogRead(A0);

   float voltage = potV * (5.0 / 1023.0);

  Serial.print("Voltaje: ");
  Serial.print(voltage);
  Serial.println(" V");  
}
```

**Función map**
La función map() en Arduino es una función que permite transformar un número de un rango a otro, escalando el valor de entrada según los nuevos límites definidos. Esta función se usa donde es necesario convertir valores, como leer la entrada de sensores, y combinarlos con otras escalas que requieran un rango específico.

La escritura de la función es la siguiente:

long map(long x, long in_min, long in_max, long out_min, long out_max);

  - x: El valor que deseas mapear.
  - in_min: El límite inferior del rango de entrada.
  - in_max: El límite superior del rango de entrada.
  - out_min: El límite inferior del rango de salida.
  - out_max: El límite superior del rango de salida.

Para un ejemplo aplicado podemos suponer un potenciómetro que produce un valor entre 0 y 1023 (rango de entrada, in_min = 0, in_max = 1023) y queremos mapear ese valor a un rango entre 0 y 255 (rango de salida, out_min = 0, out_max = 255) para controlar el brillo de un LED.

Un codigo con la función seria el siguiente: 

```cpp
const int potPin = A0; // Pin donde se conecta el potenciómetro
const int ledPin = 9;  // Pin donde se conecta el LED

void setup() {
  Serial.begin(9600);
  pinMode(ledPin, OUTPUT); // Inicializa el pin del LED como salida
}

void loop() {
  int potValue = analogRead(potPin); // Lee el valor del potenciómetro
  int brillo = map(potValue, 0, 1023, 0, 255); // Mapea el valor de 0-1023 a 0-255

  analogWrite(ledPin, brillo); // Ajusta el brillo del LED
  Serial.print("Potenciómetro: ");
  Serial.print(potValue);
  Serial.print(" - Brillo LED: ");
  Serial.println(brillo);
}
```

Ahora bien una observación es que la función map() devuelve un valor de tipo long, se debe considerar que podría haber pérdida de precisión al trabajar en un contexto en el cual se requieran números en punto flotante.


**Actividad**

![image](https://github.com/user-attachments/assets/6bcbf09d-bf4d-4516-baba-2b777a6dc322)

![image](https://github.com/user-attachments/assets/1d5cc0e1-eb15-45fd-81e3-1a7526284198)

```cpp
const int sensorPin = A0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  int sensorV = analogRead(sensorPin);
  float vol = sensorV * (5 / 1023);
  float tempC = (vol - 0.5) * 100;
  float tempF = (tempC * 9 / 5) + 32;

  Serial.print("Temperatura = ");
  Serial.print(tempC);
  Serial.print("°C) ");
  Serial.print(tempF);
  Serial.print("°F)\n");
  
  Serial.print(tempC);
  Serial.print(",");
  Serial.println(tempF);

}
```

![image](https://github.com/user-attachments/assets/4cf14a97-d562-4c14-9a04-1a2a2b9423ae)

**Salida PWM**

![image](https://github.com/user-attachments/assets/bb52ca60-292c-453d-8633-4509096b830f)

El PWM esta disponible en los pines # 3, 5, 6, 9, 10, y 11 de la placa arduino UNO R3. Además el convertidor análogo-digital de Arduino tiene 10 bits, y por lo tanto hay 210 (=1024) valores posibles, y el PWM tiene solo 8 bits y por lo tanto solo hay 28 (=256) valores posibles.


**Actividad**

![image](https://github.com/user-attachments/assets/237926ae-ae39-4427-aa1b-579392ca81e5)

![image](https://github.com/user-attachments/assets/ec0dfaa4-2372-46ab-aed7-92e6c187c0df)

```cpp
const int ledPin = 9;
int nivel[] = {0, 64, 128, 255};

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  for (int i = 0; i < 4; i++) {
    analogWrite(ledPin, nivel[i]);
    delay(500);
  }
}
```

**Actividad**

![image](https://github.com/user-attachments/assets/9f38735e-beb7-4b8f-837a-68a6130e7726)

![image](https://github.com/user-attachments/assets/88ba56bd-c7e8-4cc8-a561-2bc1f1020109)

```cpp
const int potPin = A0;
const int ledPin = 9;

void setup() {
  Serial.begin(9600);
  pinMode(ledPin, OUTPUT);
}

void loop() {
  int potValue = analogRead(potPin);
  int ledValue = map(potValue, 0, 1023, 0, 255);
  analogWrite(ledPin, ledValue);
  
  Serial.print("Valor Potenciómetro: ");
  Serial.print(potValue);
  Serial.print(" | Valor PWM del LED: ");
  Serial.println(ledValue);
}
```

**Ciclos for**

 Los ciclos for en Arduino son estructuras de control que permiten ejecutar un bloque de código repetidamente un número específico de veces. La sintaxis general de un ciclo for es:

for (inicialización; condición; incremento) {
    // Código a ejecutar en cada iteración
}

![image](https://github.com/user-attachments/assets/1c9686c1-4d9c-4d36-88f4-fd54b7167f38)

Un ejemplo en codigo es el siguiente:

```cpp
const int ledPin = 9;

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  for (int i = 0; i < 10; i++) {
    digitalWrite(ledPin, HIGH);
    delay(500);
    digitalWrite(ledPin, LOW);
    delay(500);
  }
  return 0;
}
```

**Actividad**

Desarrolle un sketch utilizando un ciclo for que incremente y decremente lentamente el brillo de un LED desde el mínimo al máximo con todos los niveles posibles (255)

![image](https://github.com/user-attachments/assets/421d00d4-d19c-47a3-bc0f-296274ca4a29)

```cpp
const int ledPin = 9;

void setup() {
  pinMode(ledPin, OUTPUT);
}

void loop() {
  for (int brightness = 0; brightness <= 255; brightness++) {
    analogWrite(ledPin, brightness);
  }
  
  for (int brightness = 255; brightness >= 0; brightness--) {
    analogWrite(ledPin, brightness);
  }
}
```

![image](https://github.com/user-attachments/assets/4b4e551e-9bf9-48af-8ffa-8c326ce870d6)

Este código intenta realizar un ciclo que imprime el número 5 diez veces, pero debido a que i se restablece a 5 en cada iteración, el ciclo nunca termina, lo que causa que el código permanezca en un bucle infinito, imprimiendo repetidamente el número 5 y nunca llegando a la línea que dice "for loop over". Para que el ciclo imprimiera el número de 0 a 9 (es decir, diez números en total), la línea i = 5; debería eliminarse del ciclo for. El código corregido quedaría así:


```cpp
void setup() {
  Serial.begin(9600);
}

void loop() {
  for (int i = 0; i < 10; i++) {
    Serial.println(i);
  }
  Serial.println("for loop over\n");
  while (true);
}
```

# **Clase 16/10**


Los ciclos while en Arduino son estructuras de control que permiten ejecutar un bloque de código repetidamente mientras se cumpla una condición específica. La sintaxis general de un ciclo while es:

```cpp
while (condición) {
    // Código a ejecutar mientras la condición sea verdadera
}
```

Un ejemplo más aplicado en codigo puede ser el siguiente:

```cpp
const int ledPin = 9;
const int buttonPin = 2;

void setup() {
  pinMode(ledPin, OUTPUT);
  pinMode(buttonPin, INPUT);
}

void loop() {
  while (digitalRead(buttonPin) == HIGH) {
    digitalWrite(ledPin, HIGH);
    delay(500);
    digitalWrite(ledPin, LOW);
    delay(500);
  }
}
```
El ciclo while comprueba si el botón conectado al pin digital 2 está presionado (HIGH). Mientras eso sea cierto, el LED en el pin 9 parpadea. Cuando el botón se suelta (LOW), el ciclo termina.


**Puerto serial**

![image](https://github.com/user-attachments/assets/eac78bc9-78e3-4b83-88d8-36c6dd4a54ee)

![image](https://github.com/user-attachments/assets/16f33342-29d8-4bdb-b475-30d4f37fd13d)

La función Serial.read() en Arduino se utiliza para leer datos que han sido enviados a través del puerto serie. Esta función permite recibir datos como caracteres individuales o bytes desde un dispositivo conectado, como un ordenador o un módulo de comunicación.

En este ejemplo, el Arduino lee y muestra en el monitor serial un carácter enviado desde la computadora.

```cpp
void setup() {
  Serial.begin(9600);
}

void loop() {
  if (Serial.available() > 0) { // Verifica si hay datos disponibles
    char incomingByte = Serial.read(); // Lee un byte
    Serial.print("He recibido: ");
    Serial.println(incomingByte); // Muestra el carácter en el monitor serial
  }
}
```

Recordar que un byte es una unidad de medida de datos que consta de 8 bits. Un bit es la unidad más pequeña de datos en informática, que puede tener un valor de 0 o 1. Por lo tanto, un byte, al ser un conjunto de 8 bits, puede representar 256 diferentes valores.


![image](https://github.com/user-attachments/assets/88656cd4-f2d9-491b-838d-d4983fb1363e)


![image](https://github.com/user-attachments/assets/3cf083e5-ad18-40fc-acc8-cfd97b791dbc)

Es importante tener en cuenta que la función Serial.read() devuelve un valor entero, que puede ser convertido a un valor de carácter utilizando la función char(). Por ejemplo:

```cpp
void setup() {
}
Serial.begin(9600); // Inicializar el puerto serial a 9600 baudios
void loop() {
  if (Serial.available() > 0) { // Si hay datos en el buffer del puerto serial int datos
  Serial.read(); // Leer un byte de datos del puerto serial
  char caracter = char (datos); // Convertir el valor entero a un carácter
  Serial.println(caracter); // Imprimir el carácter en el monitor serial
```

Este código lee un byte de datos del puerto serial y lo imprime en el monitor serial. La función Serial.available() se utiliza para verificar si hay datos disponibles en el buffer del puerto serial antes de leerlos. Para escribir datos en el puerto serial en Arduino, se utiliza la función Serial.write(). Esta función envía un byte de datos al buffer de salida del puerto serial. La función acepta un argumento que puede ser un número, un carácter o una cadena de caracteres.

```cpp

void setup() {
  Serial.begin(9600); // Inicializar el puerto serial a 9600 baudios
}
void loop() {
  Serial.write(65); // Enviar el número 65 al puerto serial
  Serial.println("Hola mundo!"); // Enviar la cadena de caracteres "Hola mundo!"
  delay(1000); // Esperar un segundo
}
```


![image](https://github.com/user-attachments/assets/9075e00a-dc88-4041-b899-235b166517ca)

**Actividad**

Crea un código en Arduino en el cual cuando se envíe un número entre 1 a 9 a través del monitor serial, la placa haga parpadear el LED integrado (pin 13) el número de veces indicado.

![image](https://github.com/user-attachments/assets/8a1c9b36-2754-42fe-bb2e-6b17f5b4fed5)

```cpp
int ledPin = 13;

void setup() {
  pinMode(ledPin, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  if (Serial.available() > 0) {
    char valor = Serial.read();
    int num = valor - '0';

    if (num >= 1 && num <= 9) {
      for (int i = 0; i < num; i++) {
        digitalWrite(ledPin, HIGH);
        delay(500);
        digitalWrite(ledPin, LOW);
        delay(500);
      }
    } else {
      Serial.println("Por favor, ingresa un número entre 1 y 9.");
    }
  }
}
```

**Funciones definidas por el usuario**

Las funciones definidas por el usuario en Arduino son bloques de código que permiten realizar tareas específicas y reutilizarlas en diferentes partes del programa. Estas funciones ayudan a organizar el código, hacerlo más legible y manejable, además de facilitar la reutilización de código.

```cpp
tipo_de_retorno nombre_de_la_función(parámetros) {
  // Cuerpo de la función
}
```

Un ejemplo de las funciones del usuario es este ejemplo ilustra cómo utilizar funciones para leer un sensor de temperatura (simulado en este caso) y mostrar el resultado:


```cpp
const int sensorPin = A0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  float temperatura = leerTemperatura();
  Serial.print("Temperatura: ");
  Serial.println(temperatura);
  delay(1000);
}

float leerTemperatura() {
  int valorAnalogico = analogRead(sensorPin);
  float voltage = valorAnalogico * (5.0 / 1023.0);
  return (voltage - 0.5) * 100; // Conversión a grados Celsius
}
```

Al dividir el código en funciones que realizan tareas específicas, se facilita la lectura, el mantenimiento y la reutilización del código, lo que resulta en un desarrollo más eficiente y menos propenso a errores.

# **Clase 21/10**

**Switch case**
La estructura switch-case en Arduino es una forma de controlar el flujo del programa mediante la evaluación de una expresión en comparación con múltiples casos posibles. Es especialmente útil cuando se tienen varias condiciones que dependen del valor de una única variable, lo que puede hacer que el código sea más fácil de leer y mantener en comparación con múltiples declaraciones if-else.


**Arreglos bidimensionales**

![image](https://github.com/user-attachments/assets/492146e0-8f97-4693-b487-efc2fbeb5466)

**Relays**

![image](https://github.com/user-attachments/assets/09e5e8ce-5863-4bdf-9a58-273ac4243bbf)

Los relés son dispositivos electromecánicos que actúan como interruptores controlados eléctricamente. En el contexto de Arduino, los relés se utilizan para controlar dispositivos de mayor potencia, como motores, luces, electrodomésticos y otros aparatos eléctricos, que no se pueden manejar directamente desde las salidas digitales del Arduino, debido a que estos dispositivos suelen requerir más corriente o voltaje del que el Arduino puede proporcionar.

Componentes de un Relé:
  - Bobina: Un componente electromagnético que, cuando se energiza, genera un campo magnético.
  - Contacto Normalmente Abierto (NO): Un contacto que se cierra (conecta) cuando el relé está activado.
  - Contacto Normalmente Cerrado (NC): Un contacto que se abre (desconecta) cuando el relé está activado.
  - Cámara de Conmutación: Donde se encuentran los contactos y que permite el paso de corriente.
  - Funcionamiento Básico: Cuando se aplica corriente a la bobina del relé, se activa el electromagnetismo, lo que hace que el contacto NO se cierre y, si corresponde, el NC se abra. Al cortar la corriente, el relé regresa a su estado normal, desconectando el circuito.

Vídeo relays: [https://youtu.be/D73p_r_M70Q?t=54]

![image](https://github.com/user-attachments/assets/29b7c56b-a946-421a-b271-e019cc041fa0)


Vídeo transistores como interruptores: [https://youtu.be/sRVvUkK0U80]

**Motores de CC**

Los motores de corriente continua (CC) son dispositivos electromecánicos que convierten la energía eléctrica de una corriente continua en movimiento mecánico. Son ampliamente utilizados en diversas aplicaciones debido a su simplicidad, facilidad de control y versatilidad.

Características Principales de los Motores de CC:
  - Construcción: Generalmente, un motor de CC tiene dos partes principales: el rotor (o armadura), que es la parte giratoria, y el estator, que puede ser un imán permanente o una bobina que produce el campo magnético. Al aplicar un voltaje al motor, se crea un campo magnético que hace girar el rotor.

  - Tipos de Motores de CC:
    * Motores de CC con Escobillas: Utilizan escobillas para conducir corriente eléctrica hacia el rotor. Son simples y baratos, pero pueden requerir mantenimiento debido al desgaste de las escobillas.
    * Motores de CC Sin Escobillas (BLDC): No utilizan escobillas, lo que aumenta la eficiencia y reduce el mantenimiento. Son ideales para aplicaciones de alta eficiencia y larga duración, aunque suelen ser más complejos y costosos.
      
  - Control de Velocidad: La velocidad de un motor de CC se puede controlar variando el voltaje aplicado en sus terminales. Usualmente, se utilizan métodos como la modulación de ancho de pulso (PWM) para controlar la velocidad de manera eficiente.

  - Dirección de Giro: Cambiar la polaridad del voltaje aplicado al motor invierte el campo magnético y hace que el motor gire en la dirección opuesta.


Video Motores CC: [https://www.youtube.com/watch?v=CWulQ1ZSE3c]

**Puente H**

![image](https://github.com/user-attachments/assets/50648309-5539-494a-b3e2-468200e337a9)

![image](https://github.com/user-attachments/assets/200675c8-3909-4463-8f3c-aaba5d2e77f0)

**Driver L293**

El driver L293 es un módulo de controlador de motor que se utiliza para controlar motores de corriente continua (CC) y motores paso a paso. Permite a los microcontroladores, como el Arduino, controlar la dirección y la velocidad de los motores sin sobrecargar sus pines de salida, ya que el L293 puede manejar mayores voltajes y corrientes.

Características Principales del L293:
  - Puentes H (H-Bridge): El L293 utiliza una configuración de puente H, lo que permite controlar la dirección de un motor. Esto significa que puedes hacer que el motor gire en ambas direcciones (hacia adelante y hacia atrás).

  - Voltaje de Alimentación: El L293 puede trabajar con voltajes de entrada de 4.5V a 36V, lo que lo hace compatible con una amplia gama de motores.

  - Corriente: Cada canal del L293 puede suministrar hasta 600 mA continuo, y picos de hasta 1.2 A, lo que lo hace adecuado para motores de pequeñas y medianas aplicaciones.

  - Seguridad: Está diseñado con diodos de protección que evitan daños en el circuito por retrocesos de corriente, lo que es común cuando se detienen motores.

  - Control de Velocidad: Al usar modulación de ancho de pulso (PWM), se puede controlar la velocidad del motor, variando el ciclo de trabajo de la señal de control.


![image](https://github.com/user-attachments/assets/1e15e632-928f-426f-9712-24da77de7c49)


**Librerías**

Las librerías de Arduino son colecciones de código preescrito que facilitan la programación al proporcionar funciones y clases específicas para controlar hardware y realizar tareas comunes. Estas librerías permiten a los programadores ahorrar tiempo y esfuerzo, ya que encapsulan la complejidad de las interacciones con dispositivos específicos, como sensores, motores, pantallas, y comunicación, entre otros.

![image](https://github.com/user-attachments/assets/d917a614-ec26-480f-a018-89561fa3692c)

![image](https://github.com/user-attachments/assets/d702c4eb-0066-49c7-8a11-6d5f353e9ea5)

**Servo motores**

Vídeo: [https://www.youtube.com/watch?v=mk9UkQCeENc]

**Actividad**

![image](https://github.com/user-attachments/assets/8faf8f56-6b70-47c5-b5f0-b025acbcbaec)


![image](https://github.com/user-attachments/assets/8ed19994-69d2-4b60-ac30-d29b8afb7cbf)

```cpp
const int motorPin = 9;      
const int switchPin = 7;     
bool motorEnabled = false;   

void setup() {
  pinMode(motorPin, OUTPUT);                
  pinMode(switchPin, INPUT_PULLUP);         
  Serial.begin(9600);                       
}

void loop() {
  
  if (digitalRead(switchPin) == LOW) {
    motorEnabled = true; 
    Serial.println("Motor Activado");
  } else {
    motorEnabled = false; 
    digitalWrite(motorPin, LOW); 
    Serial.println("Motor Desactivado");
  }


  if (motorEnabled && Serial.available() > 0) {
    int speed = Serial.parseInt();

    if (speed < 0) {
      speed = 0;
    } else if (speed > 255) {
      speed = 255;
    }

    analogWrite(motorPin, speed);
    Serial.print("Velocidad del motor ajustada a: ");
    Serial.println(speed);
  }
}
```

**Actividad**

![image](https://github.com/user-attachments/assets/00846621-96c6-44f1-8e7f-a892e11d0612)


![image](https://github.com/user-attachments/assets/5342434d-71a5-4f10-ab09-4f7080d6e2d4)


```cpp
#include <Servo.h>
Servo myServo; 

const int potPin = A0;

void setup() {
  myServo.attach(9);
}

void loop() {
  int potValue = analogRead(potPin);
  int angle = map(potValue, 0, 1023, 0, 180);
  
  myServo.write(angle);
}
```

**Motores Stepper**

![image](https://github.com/user-attachments/assets/095d123e-1db8-4763-9fc0-81c93a821d3d)


Los motores paso a paso (o stepper motors) son un tipo de motor eléctrico que divide una rotación completa en múltiples pasos discretos. Este diseño les permite proporcionar un control preciso del movimiento, lo que los hace ideales para aplicaciones en las que se requiere un posicionamiento exacto, como en robots, impresoras 3D, sistemas CNC y cámaras.


Características de los Motores Paso a Paso:
  - Control de Posición: Los motores paso a paso pueden ser controlados para moverse en incrementos fijos, lo que permite el posicionamiento preciso sin necesidad de un sistema de retroalimentación (feedback).

  - Tipos de Motores Paso a Paso:
    * Motores de paso unipolares: Tienen un devanado adicional que permite simplificar el control, pero son menos eficientes.
    * Motores de paso bipolares: Tienen dos devanados y ofrecen más torque y eficiencia, pero requieren un controlador más complejo para invertir la corriente.

  - Paso Completo y Paso Fraccionado: Los motores pueden ser controlados en modo de "paso completo", donde el motor se mueve de un paso a otro, o en modo de "paso fraccionado", lo que permite un movimiento más suave y más posiciones intermedias.

  - Torque y Velocidad: Los motores paso a paso proporcionan un buen torque a bajas velocidades, pero con un torque que decae a medida que aumenta la velocidad.

  - Controladores: Los motores paso a paso normalmente requieren un controlador que pueda enviar las señales adecuadas para hacer que el motor gire. Estos controladores pueden ser ICs especiales diseñados para el control de motores, como el A4988 o DRV8825.
    
  - Ventajas de los Motores Paso a Paso:
    * Precisión: Se puede controlar su posición y velocidad de manera precisa.
    * Simplicidad en el Diseño: A menudo no requieren sistemas de retroalimentación, lo que simplifica el diseño del control.
    * Estabilidad: Mantienen su posición incluso cuando no están alimentados si se les aplica un torque.

  - Desventajas de los Motores Paso a Paso:
    * Limitaciones de Velocidad: No son ideales para aplicaciones de alta velocidad.
    * Calor: Pueden calentarse si se utilizan en condiciones de funcionamiento continuas.
    * Requerimiento de Controlador: Necesitan controladores especiales, lo que añade complejidad al circuito.


![image](https://github.com/user-attachments/assets/3a57e345-4348-4e68-8763-d6d7cf11c61f)


# **FINAL**

![image](https://github.com/user-attachments/assets/9ae17e35-38fe-4e63-8a74-882f59c68ae6)

**Origen de la Idea Creativa:**

Nuestra idea surgió a través del funcionamiento de una torreta que observamos en una página web. Quisimos replicarla, implementando mejoras que consideramos necesarias para optimizar su rendimiento y estabilidad. El proyecto se basa en componentes electrónicos que nos permiten controlar los movimientos de una torreta, así como disparar proyectiles de espuma de manera precisa y remota.

El diseño incluye una estructura robusta que permite la inclinación y rotación de la torreta mediante dos servomotores. Estos servos reciben órdenes desde un microcontrolador Arduino Nano, lo que garantiza un control eficiente y ágil. La implementación de estos motores asegura un movimiento fluido y preciso, permitiendo apuntar a objetivos específicos con facilidad.

**Disparo de Proyectiles:**

El sistema de disparo de proyectiles está diseñado para ser no solo efectivo, sino también seguro. Este se lleva a cabo mediante dos motores de corriente continua (DC) que giran rodillos, los cuales son responsables de propulsar los dardos de espuma. Además, un tercer servomotor se encarga de empujar los proyectiles hacia los rodillos al recibir la señal de disparo del controlador. Esto permite que la torreta dispare con rapidez y precisión, garantizando un rendimiento óptimo en cada acción.

**Alimentación y Control:**

Todo el sistema funciona con una fuente extarna de 12V, que se regula mediante un convertidor de la placa arduino UNO R3 los voltajes sean estables y dentro del rango adecuado para cada componente. La comunicación con el controlador se realiza a través de un módulo Bluetooth HC-05, que facilita el control inalámbrico desde el PC para nuestro caso. Esta característica permite gestionar tanto los movimientos de la torreta como las acciones de disparo de manera remota.

**Mejoras Implementadas:**

Inicialmente, planeamos realizar modificaciones en la base de la torreta, ya que observamos que presentaba cierta inestabilidad. Después de varias iteraciones y errores, como la quema de motores, logramos mejorar la estabilidad general del sistema, aunque aún persistieron algunos problemas menores. Aun así, la torreta se mostró más estable que en el video que utilizamos como referencia.

Adicionalmente, decidimos incluir un láser como parte del sistema. Esta mejora proporciona una herramienta de puntería visual que permite al usuario apuntar con mayor facilidad y precisión. La incorporación del control a través de Bluetooth también fue un gran avance en el proyecto, ya que esto facilitó un manejo dinámico y en tiempo real de todas las funciones de la torreta.

**Conclusión:**

Este proyecto no solo refleja nuestra capacidad para innovar y adaptarnos a los desafíos de la ingeniería y la programación, sino que también representa un aplicación práctica de la tecnología en un sistema interactivo. Con la combinación de electrónica, programación y diseño, hemos logrado construir una torreta controlada de manera remota que ofrece una experiencia de usuario única y entretenida. Las lecciones aprendidas a lo largo del desarrollo del proyecto han sido valiosas, fortaleciendo nuestras habilidades y conocimientos en el campo de la robótica y el control de sistemas.


Link presentación: [https://www.canva.com/design/DAGY8OLufIo/3aoQtVRZf8LsBnGeHJ20_A/edit?utm_content=DAGY8OLufIo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton]

Link proyecto guía: [https://www.littlefrenchkev.com/bluetooth-nerf-turret]

**Codigo utilizado**

```cpp
#include <Servo.h>

Servo recoil_servo;
Servo pan_servo;
Servo tilt_servo;

const byte pan_limit_1 = 0;
const byte pan_limit_2 = 180;
const byte tilt_limit_1 = 65;
const byte tilt_limit_2 = 180;
const byte recoil_rest = 180;    
const byte recoil_pushed = 125; 


byte byte_from_app;
const byte buffSize = 30;
byte inputBuffer[buffSize];
const byte startMarker = 255;
const byte endMarker = 254;
byte bytesRecvd = 0;
boolean data_received = false;


bool is_firing =  false;
bool can_fire =  false;
bool recoiling = false;

unsigned long firing_start_time = 0;
unsigned long firing_current_time = 0;
const long firing_time = 150;

unsigned long recoil_start_time = 0;
unsigned long recoil_current_time = 0;
const long recoil_time = 2 * firing_time;

const byte motor_pin =  12;
boolean motors_ON = false;



void setup()
{
  
  pinMode(motor_pin, OUTPUT);
  digitalWrite(motor_pin, LOW);

  
  recoil_servo.attach(9);
  pan_servo.attach(10);
  tilt_servo.attach(11);


  recoil_servo.write(recoil_rest);
  pan_servo.write(90);
  delay(1000);
  tilt_servo.write(105);


  Serial.begin(9600);
}


void loop()
{
  getDataFromPC();
  set_motor();
  if (data_received) {
    move_servo();
    set_recoil();
    set_motor();
  }
  fire();
}



void getDataFromPC() {

  if (Serial.available()) { 

    byte_from_app = Serial.read();  

    if (byte_from_app == 255) {    
      bytesRecvd = 0;                  
      data_received = false;
    }

    else if (byte_from_app == 254) {   
      data_received = true;            
    }

    else {                          
      inputBuffer[bytesRecvd] = byte_from_app;   
      bytesRecvd++;                               
      if (bytesRecvd == buffSize) {    
        bytesRecvd = buffSize - 1;  
      }
    }
  }
}

void move_servo() {
  
  byte pan_servo_position = map(inputBuffer[0], 0, 253, pan_limit_2, pan_limit_1);
  pan_servo.write(pan_servo_position); 
  byte tilt_servo_position = map(inputBuffer[1], 0 , 253, tilt_limit_2, tilt_limit_1);
  tilt_servo.write(tilt_servo_position);
}


void set_recoil() {

  if (inputBuffer[3] == 1) {        
    if (!is_firing && !recoiling) {
      can_fire = true;            
    }
  }
  else {                  
    can_fire = false;    
  }
}

void set_motor() {

  if (inputBuffer[2] == 1) {                
    digitalWrite(motor_pin, HIGH);      
    motors_ON = true;
  }
  else {                                   
    digitalWrite(motor_pin, LOW);       
    motors_ON = false;

  }
}

void fire() {

  if (can_fire && !is_firing && motors_ON) {

    firing_start_time = millis();
    recoil_start_time = millis();
    is_firing = true;
  }

  firing_current_time = millis();
  recoil_current_time = millis();

  if (is_firing && firing_current_time - firing_start_time < firing_time) {
    recoil_servo.write(recoil_pushed);
  }
  else if (is_firing && recoil_current_time - recoil_start_time < recoil_time) {
    recoil_servo.write(recoil_rest);
  }
  else if (is_firing && recoil_current_time - recoil_start_time > recoil_time) {
    is_firing = false;
  }
}

```
