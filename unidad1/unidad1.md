# Unidad 1. Introducción a los sistemas operativos

# Introducción

TIC es la abreviatura para las Tecnologías de la Información y las Comunicaciones, es decir, todas esas tecnologías que nos permiten
acceder, producir, guardar, presentar y transferir información

Son los ordenadores, televisores, teléfonos móviles, reproductores de audio y video, consolas de videojuegos, tabletas e Internet

Las TICs sirven para divertirnos, aprender, mantenernos en contacto, dar nuestra opinión y conocer lo que los demás opinan.....

El término Informática procede de la unión de dos términos: **INFOR**mación y Auto**MÁTICA**.

Se define la Informática como la ciencia que estudia el procesamiento automático de la información mediante computadoras

En los países de habla inglesa no se utiliza la palabra informática, sino el término Computer Science, o Ciencia de la Computación.

# Sistema informático (SI)

Entendemos por sistema informático el conjunto de elementos físicos y lógicos que se encargan de recibir, guardar y procesar datos para luego entregarlos en forma de resultados. El esquema de un sistema informático engloba todo aquello que contiene una parte tangible o física (hardware) y otra intangible  o lógica (software).​

* **Hardware:** recoge todas las partes físicas del SI, es decir, todo lo que se puede tocar. En el caso de un ordenador, estos elementos del sistema informático serían: la pantalla, el teclado, ratón, almacenamiento....​

* **Software:** se refiere a la parte lógica de todo sistema informático, lo intangible. Es el conjunto de programas incluyendo datos, instrucciones, aplicaciones, etc, que permiten al usuario comunicarse con el hardware para poder realizar diversas tareas.​

* **Personal informático:** toda persona que utiliza de alguna manera el sistema, entre ellos, los creadores de software, los programadores o los usuarios en general.​

  ![image](https://github.com/user-attachments/assets/664a2ae1-8825-47d1-8166-5395d128f893)

# Representación de la información

La transmisión de información entre el ser humano y la computadora puede hacerse de muchas formas:​

* Mediante caracteres alfanuméricos (letras {a, b, ..., z} y números {0, 1, ..., 9}). Por ejemplo, los introducidos al ordenador mediante un teclado.​

* Mediante sonidos: como los introducidos al ordenador a través de un micrófono, o que salen del ordenador por los altavoces.​

* Mediante vídeos: como las imágenes obtenidas a través de una cámara de vídeo.​

* Mediante gráficos e imágenes: por ejemplo, una imagen introducida por un escáner, o fotografías descargadas de una cámara de fotos digital.​

* En general, cualquier tipo de dato enviado por un periférico del ordenador capaz de tomar datos de cualquier tipo y enviarlo al ordenador, o a la inversa.​

En cada caso el canal es diferente, y para proceder a la comunicación de los datos es necesario cambiar la forma en que estos se representan. Por lo tanto, los datos deben ser traducidos o codificados. La traducción o codificación es necesaria cuando los códigos utilizados por el emisor, el canal y el receptor son diferentes.​

## Sistemas de numeración

Se define **sistema de numeración** como el conjunto de símbolos o dígitos utilizados para la representación de cantidades, así como las reglas que rigen dicha representación.​

Un sistema de numeración se distingue por su base, que es el número de símbolos que utiliza, y se caracteriza por ser el coeficiente que determina cuál es el valor de cada símbolo dependiendo de su posición (peso).​

- Símbolos → Dependen de la base del sistema:​

- Sistema decimal → 10 símbolos → {0,1,2...9}​

- Sistema binario → 2 símbolos→ {0,1}​

- Sistema octal → 8 símbolos → {0,1,...7}​

- Sistema hexadecimal →16 símbolos →{0,1,...9,A,B,C,D,E,F}​​

## Sistema de numeración decimal

**Base=10**

El sistema de numeración decimal, es un sistema de numeración posicional en el que las cantidades se representan utilizando como base aritmética el número diez. ​

Es el sistema de numeración que utilizamos normalmente y utiliza diez dígitos o símbolos: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9​

![image](https://github.com/user-attachments/assets/e465d908-8889-43a2-b6e9-873c01bacca3)

## Sistema de numeración binario

**Base=2**

El sistema de numeración binario utiliza sólo dos dígitos (0 y 1) para representar cantidades, por lo que su base es 2. Cada dígito de un número representado por este sistema se denomina bit (binary digit).​

Los bits tienen distinto valor dependiendo de la posición que ocupan; por eso este sistema también es posicional. Estos valores vienen determinados por una potencia de base 2 que la vamos a llamar peso.

![image](https://github.com/user-attachments/assets/30f2fbd4-f864-4f60-8dfb-0367883f2390)

### Conversión binario a decimal 

![image](https://github.com/user-attachments/assets/fe9c391d-4391-4d18-900e-b75b47d2d89f)

### Conversión decimal a binario.

Para representar un número decimal  en binario, realizaremos divisiones sucesivas por 2 hasta obtener un cociente menor de 2.​ El número resultante será el último cociente y tras él los restos obtenidos en cada una de las divisiones, empezando por el último.​

![image](https://github.com/user-attachments/assets/1fe2a142-c188-48c1-9874-020eb2e28482)


![image](https://github.com/user-attachments/assets/926b216f-0514-4c97-b057-c0926b9e2e7d)

## Sistema de numeración hexadecimal

**Base=16**

La notación Hexadecimal se utiliza para reducir grandes cadenas de números binarios en conjuntos de cuatro dígitos, que se pueden de esta forma comprender fácilmente.

![image](https://github.com/user-attachments/assets/d17c9672-c4dd-4134-8543-9f9c581c1959)

### Conversión hexadecimal a decimal

![image](https://github.com/user-attachments/assets/74f3275e-b89c-4e2d-b348-40a6050e074a)

### Conversión decimal a hexadecimal

![image](https://github.com/user-attachments/assets/21d6eb8f-8f72-4dab-8689-1a2df6e3be90)

# Unidades de medida de la información.

Un byte es la unidad de información fundamental usada en informática y telecomunicaciones. Está compuesta por 8 bits contiguos, razón por la que también se le denomina octeto. Para representarlo usamos la B MAYÚSCULA.​ 

**1 Byte=8 bits // 1B=8b**



* Para pasar de Bytes a bits solamente tendremos que multiplicar el valor por 8.​

100 Bytes = 100*8 = 800 bits


* Para pasar de bits a Bytes tendremos que dividir el valor.​

256 bits = 256/8 = 32 bytes

## kilobyte VS kibibyte.​

Los prefijos empleados para los múltiplos del byte normalmente son los mismos del **Sistema internacional**, pero también se utilizan los **prefijos binarios**, existiendo diferencias entre ellos, ya que según el tipo de prefijo utilizado los bytes resultantes tienen valores diferentes.​ Esto se debe a que los prefijos del SI se basan en base 10 (sistema decimal), y los prefijos binarios se basan en base 2 (sistema binario), por ejemplo:​

![image](https://github.com/user-attachments/assets/b42f074d-96be-4de9-ab06-1f7a559ada44)

### Unidades Sistema internacional

![image](https://github.com/user-attachments/assets/22308a20-9fd7-46b3-b301-ef9f5516f7c0)

### Unidades Sistema Binario

![image](https://github.com/user-attachments/assets/884d16d6-3e97-4630-bab1-24fd230f181a)

### Conversiones de Sistema internacional a Sistema Binario

Para convertir en Sistema Binario es necesario multiplicar o dividir por 2^10 o lo que es lo mismo por 1024 por cada salto de unidad.

* 2 MiB = 2 * 210=2*1024 = 2048 KiB (1 salto)​

* 2TiB =2* 230 = 2* 1024*1024*1024 = 21.47.483.648 KiB (3 saltos)​

* 6.000.000 KiB = 6.000.000/1024 = 6.000.000/210  = 5859,375 MiB (1 salto)​

* 6.000.000 KiB = 6.000.000 /1024/1024/1024/1024= 6.000.000 / 240= 5,45*10-7 PiB (4 saltos)

### Espacio en disco
Un fabricante nos dice que un SSD tiene 500 GB que según el SI son 500.000.000.000 Bytes​

A nivel binario, 1 KiB equivale a 1024 Bytes y no 1000 Bytes, por tanto un MiB son 1024 KB y un GiB son 1024 MB. Así, el cálculo siguiendo el ejemplo del SSD de 500 GB es que tendremos 500.000.000.000 dividido entre (1024 x 1024 x 1024), y el resultado nos da 465.66GiB y no 500 GB.​

500,000,000,000 / 1024/1024/1024 = 465.66 GiB​

Para pasar 465.66 GiB a B.​

De la tabla anterior tenemos que 1 GiB = 230 =  1 073 741 824  bytes​

Por tanto 465GiB = 465*1 073 741 824  = 499.289.948.160 bytes​

# Hardware

## Cajas


La **caja o chasis o carcasa** es la parte del ordenador que sirve de soporte y de esqueleto para alojar las piezas básicas de un ordenador (placa base, dispositivos de almacenamiento, fuente de alimentación, etc...). El tamaño ha de ser lo suficientemente grande para que albergue los diferentes componentes del ordenador. 

El  material  con  el que están construidas es aluminio o aleaciones de aluminio, metacrilato o plástico, pudiendo ser cartón hasta fibra pasando por titanio, kevlar,.......

![image](https://github.com/user-attachments/assets/c5388d6a-3ff8-4f67-b282-17fd01ecfafa) ![image](https://github.com/user-attachments/assets/7bf17240-05eb-49b8-b207-149c1b358b25) ![image](https://github.com/user-attachments/assets/73225955-2d65-4d59-bf84-5dc468d6dc44)



### Partes de la caja.

![image](https://github.com/user-attachments/assets/fcb8f849-cf4b-4c10-b074-9e64319e0ff5)


* **Chasis**   . Parte interna metálica (generalmente de aluminio) donde se fija la placa base.  

* **Cubierta**   . Parte exterior de la caja. Normalmente las cubiertas se pueden desmontar para acceder al interior del ordenador

* **Panel frontal**   . Parte delantera de la caja (suele ser de plástico).

* **Panel posterior**   . Donde saldrán al exterior todas las conexiones habituales para elementos externos, así como la salida de ventilación y corriente de la fuente de alimentación.
  
![image](https://github.com/user-attachments/assets/a9a85268-48c9-47d9-8ed5-53b3ee66503f)


* **Bahías para unidades**   . Espacios para alojar las unidades de almacenamiento (DVD, ..) 

* **Interruptor, pulsador y luces**   . Conjunto de indicadores y botones que le alojan en el panel frontal  para su uso e información (encendido, reset, luz HDD, ...).


![image](https://github.com/user-attachments/assets/2d099d1c-21a4-4309-9c46-59ee1f89907c)



### Tornilleria utilizada en el montaje de los ordenadores

![image](https://github.com/alexlopezprofe/MyM/assets/148449360/283bb5be-9303-445b-bb28-9daf30a446db)](https://hardzone.es/tutoriales/mantenimiento/tipos-tornillos-mantenimiento-pc/)

### Tipos de cajas.

La clasificación se hace normalmente por su tamaño dependiendo de las placas base que soportan. Las más usuales  son: 

* **Caja  SFF (Small Form Factor).**    Tamaño pequeño. Mini-ITX

* **Caja de sobremesa** **(Desktop)** Usada en formato horizontal para poder ubicar el monitor encima.  Micro-ATX

* **Caja  minitorre (Mini Tower).** Usada  en  formato  vertical  para  placas  Micro-ATX. Entre 32-40 cm. Podemos encontrarla como microtorre

* **Semitorre (Mid Tower).**   ATX. Entre 45-55 cm

* **Gran  torre (Full Tower.)** EATX. Entre 55-72cm. 

* **Caja rack.** Usada para servidores industriales o para montar servidores en armarios rack (19”).

![image](https://github.com/user-attachments/assets/b741b218-2bd7-418f-9892-56221e271224)

![image](https://github.com/user-attachments/assets/5c747dc9-2ef3-48cc-a176-47eb00db2d11)

![image](https://github.com/user-attachments/assets/8e90a3ef-a90c-41d7-b19a-9a6ffca540e7)

## Fuente de alimentación

La fuente de alimentación o Power Supply (PS) es el dispositivo que proporciona al ordenador (o a cualquier otro aparato electrónico) la energía que necesita para funcionar.

Vatios (W) = Voltios (V) x Amperios (A).

La fuente de alimentación de un ordenador de sobremesa se encuentra en el interior de la carcasa, es una caja metálica rectangular dotada, normalmente, de un ventilador. De ella sale un grupo de cables de colores que van a parar a los distintos dispositivos dentro de la carcasa. Los conectores que vienen incluidos en la fuente de alimentación están **normalizados.**
Los componentes del interior de PC funcionan con corriente continua (DC) y la red eléctrica funciona con corriente alterna (AC) → La fuente de alimentación convierte la corriente alterna (230V AC) en continua (+12V, +5V y +3,3V DC) para que el PC pueda utilizarla.

![image](https://github.com/user-attachments/assets/f30a0b36-a81c-431f-a805-812fcf758213)

## Placas base

La placa base (mainboard) o placa madre (motherboard) es el elemento principal del ordenador; a ella se conectan todos los demás dispositivos, como pueden ser el disco duro, la memoria o el microprocesador, y hace que todos estos componentes funcionen en equipo. De ella, dependerán los componentes que podremos instalar y las posibilidades de ampliación del ordenador.

Físicamente, es una placa de material sintético formada por un circuito impreso, en la que se halla un conjunto de chips, el chipset, la BIOS, los puertos del ratón y del teclado, los conectores IDE y SATA, el zócalo del microprocesador, los zócalos de memoria, los puertos paralelo, serie, USB.

## Factor de forma de placas base

El factor de forma son los estándares que definen algunas características físicas de las placas base. Existen diferentes tamaños y tipos de placas base. El factor de forma de la placa base determina el tamaño y orientación de la placa con respecto a la caja, el tipo de fuente de alimentación necesaria y dicta los periféricos que pueden integrarse en la placa.

Hasta la fecha se han definido (y comercializado) diversos  **form factor**. 

Los más importantes son:

* **ATX (305 x 244 mm) y Micro-ATX** ((244 x 244 mm)) los más extendidos actualmente

* **Mini-ITX** (170 x 170 mm) , Nano-ITX y Pico-ITX** . Formatos muy reducidos de VIA Technologies y compatibles con ATX.

* **Extended ATX** (300 x 330 mm) . Factor de forma de mayor tamaño Están pensadas para configurar equipos de grandes prestaciones.

### El socket

El socket o zócalo es el conector de la placa base en el que se inserta el microprocesador, existen de varios tipos:

- **PGA** (Pin Grid Array): el socket solo tiene taladros mientras que, los pines, se encuentran en el procesador.

![image](https://github.com/user-attachments/assets/c0573ee3-21f6-4971-aca6-8811223f0495)

![image](https://github.com/user-attachments/assets/77bfc7d2-74b3-49f8-9907-93e8f661703e)



- **LGA** (Land Grid Array): Los pines se encuentran en la placa base. Intel siempre utiliza sockets LGA

![image](https://github.com/user-attachments/assets/eb08071b-ae2a-4b5b-a3de-b57f63086785)

![image](https://github.com/user-attachments/assets/3a612201-4512-473e-86d0-ca29581c3603)


- **BGA** (Ball Grid Array): En este tipo de sockets se suelda el procesador a la placa base


> Ampliamente utilizado en portátiles.


## PROCESADOR

Es el componente principal del ordenador, dirige y controla el resto de componentes, decodifica y ejecuta las instrucciones de los programas cargados en la RAM. Es un circuito integrado o chip, formado por millones de [ transistores](https://en.wikipedia.org/wiki/Transistor) .

No solo se encuentra en ordenadores, también se encuentra en teléfonos móviles, electrodomésticos, consolas, etc.

![image](https://github.com/user-attachments/assets/caff1c03-a8a9-4859-aa8f-0b9a14790edf)

### Núcleos

Los procesadores antiguos eran  **single core** , en los microprocesadores modernos suelen existir más de un núcleo ( **core** ) de procesamiento. Cada núcleo es un pequeño microprocesador independiente dentro del mismo microprocesador.

Cada núcleo se compone de su propia Unidad de Control (UC), Unidad Aritmético-lógica(ALU), Unidad de Punto Flotante (UPF), Registros y los primeros niveles de Memoria Caché (L1 y L2).

Gracias a los núcleos, el microprocesador será capaz de realizar a la vez una tarea (ciclo de instrucción) por cada núcleo que posea. De esta manera el sistema responderá de manera más cómoda aunque una tarea monopolice uno de los núcleos. Como regla general, a mayor número de núcleos, los microprocesadores presentan mejores prestaciones.

> ¿Núcleo físico VS núcleo lógico?
> [Simultaneous Multi Threading (SMT) de AMD vs  Hyper Threading de Intel](https://hardzone.es/reportajes/comparativas/intel-hyperthreading-amd-smt/)
> [https://hardzone.es/2018/08/11/importante-no-confundir-hilos-nucleos/](https://hardzone.es/2018/08/11/importante-no-confundir-hilos-nucleos/)

**No confundir varios cores con sistemas multiprocesador**

![image](https://github.com/user-attachments/assets/fb351da2-9f38-4f8a-9a00-0f521b3126f1)

### Velocidad de reloj

![](assets/img/Unidad04/u47.png)

También llamada frecuencia de funcionamiento, se refiere al número de operaciones que la CPU puede realizar en un solo segundo.

Viene dada por la velocidad del reloj y se mide en megahercios o gigahercios (1 GHz = 1000 MHz).

Por ejemplo una CPU con una velocidad de reloj de 3,2 GHz ejecuta 3.200 millones de ciclos por segundo.


[![](https://img.youtube.com/vi/7d1eyZBpLn8/hqdefault.jpg)](https://www.youtube.com/watch?v=7d1eyZBpLn8)

[![](https://img.youtube.com/vi/TtuUANbaEFI/hqdefault.jpg)](https://www.youtube.com/watch?v=TtuUANbaEFI)

### Litografía

El proceso de fabricación o  **litografía**  se mide en  **nanómetros**  (para poneros en perspectiva de lo pequeño que es esto, un nanómetro son 10^-7 centímetros, o lo que es lo mismo, 0,0000001 centímetros), y es precisamente  **el tamaño de los transistores** . Así pues, un proceso de 14 nm significa que cada transistor mide 14 x 10^-7 centímetros.

Esto significa que en comparación, en el proceso de 7 nm se puede meter literalmente el doble de transistores que con el proceso de 14 nm en la misma unidad de superficie. EL efecto de poder meter un mayor número de transistores en el mismo espacio repercute en el rendimiento y en la eficiencia energética, así que tener una litografía menor implica que el procesador será  **más potente y más eficiente** .


[![](https://img.youtube.com/vi/7d1eyZBpLn8/hqdefault.jpg)](https://www.youtube.com/watch?v=7d1eyZBpLn8)

[![](https://img.youtube.com/vi/TtuUANbaEFI/hqdefault.jpg)](https://www.youtube.com/watch?v=TtuUANbaEFI)

### Thermal Design Power. TDP

La **Potencia de Diseño Térmico  o TDP** representa la potencia media, en vatios, que el procesador disipa cuando funciona a Frecuencia Base con todos los núcleos activos bajo una carga de trabajo de alta complejidad.

Un procesador con un TDP de 95W, se espera que genere un valor de 95W de calor cuando está en 100% de su uso.

El TDP no es una medida directa de cuánta potencia consumirá un componente, pero si que es una buena aproximación.

### Refrigeración. Disipación de calor en las CPU.

#### Refrigeración por aire

![image](https://github.com/user-attachments/assets/c360fa67-d250-4b14-93ff-d183ddc9ceb0)


#### Refrigeración líquida

![image](https://github.com/user-attachments/assets/645364dd-35d6-4dc9-bcbe-7ff58f2c2140)

#### Pasta térmica

Es el elemento que mayor resistencia térmica hace en el conjunto del disipador. Es muy importante tener una buena pasta térmica en chips potentes, ya que su **conductividad** será mayor. La función de la pasta térmica es mejorar todo lo posible, la unión entre el IHS y DIE (método difícil de aplicar) y entre  el IHS bloque frío del disipador(método fácil)

![image](https://github.com/user-attachments/assets/942737ac-9a67-4710-87a3-1180fb4535ef)

## Memoria RAM

La RAM o memoria de acceso aleatorio (en inglés: Random Access Memory), es la memoria principal de un equipo microinformático y se encarga de almacenar de manera _temporal_ tanto las instrucciones como los datos que ejecuta el microprocesador.

Es una memoria volátil, es decir, la información se pierde al interrumpirse el flujo eléctrico (apagar el ordenador).

Se denominan «de acceso aleatorio» porque se puede leer o escribir en una posición de memoria con un tiempo de espera igual para cualquier posición.

Físicamente es un conjunto de chips soldados sobre una PCB, a este conjunto de chips, se le denomina **módulo** de memoria RAM.

Los fabricantes tienen que fabricar los módulos de memoria siguiendo los estándares marcados por **JEDEC** (Joint Electron Device Engineering Council)
(https://www.jedec.org/)

![image](https://github.com/user-attachments/assets/9ac52d20-8845-4641-bcb3-d8004cdee3fd)

![image](https://github.com/user-attachments/assets/7e515cb1-6aec-4da5-9496-a5edc204694c)

### Estructura módulo memoria RAM

![image](https://github.com/user-attachments/assets/49ee5028-1374-490e-9e9c-789dee501980)


## Dispositivos de almacenamiento


Los dispositivos de almacenamiento de un equipo microinformático, también conocidos como memoria secundaria, es el lugar donde se almacenan permanentemente los programas y datos con los que se trabaja en el mismo. Se caracteriza por tener gran capacidad de almacenamiento, ser no volátil y por un tiempo de acceso más lento que el acceso a la memoria principal.

https://github.com/alexlopezprofe/MyM/blob/main/https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/


Actualmete los dispositivos de almacenamiento de un equipo microinformático y donde se suele instalar el sistema operativo, además de tener la posibilidad de almacenar programas y datos son los **discos duros magnéticos o HDD (Hard Disk Drive)** y las **unidades de estado sólido o SDD (Solid State Drive)**

### Disco duro magnético. Estructura mecánica

https://github.com/alexlopezprofe/MyM/blob/main/https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06//Unidad066.png)

### **SSD (Solid State Drive - Unidad de Estado Sólido)** utilizan memorias de tipo **flash NAND**.

**Ventajas:**

* Velocidad o Tasa de transferencia de datos. Tanto en la búsqueda de los datos como en las lecturas posteriores. En una unidad de este tipo el tiempo que tienes que esperar hasta obtener los datos es siempre el mismo (similar a la RAM). 
* Mayor resistencia a golpes. Al no tener componentes móviles responden mejor tanto a las vibraciones como a los golpes.
* Menor consumo de energía. Necesitan menos potencia para funcionar al no disponer de partes móviles
* Menor ruido. Otra ventaja más de no tener partes móviles.
* No tiene fragmentación.

**Inconvenientes:**

* Precio por bit mayor.
* Menor capacidad.
* Sus celdas pueden reescribirse un número limitado de veces.

# Dispositivos de almacenamiento en red

## NAS
El almacenamiento conectado en red, Network Attached Storage (NAS), es el nombre dado a una tecnología de almacenamiento dedicada a compartir la capacidad de almacenamiento de un computador/ordenador (servidor) con computadoras personales o servidores clientes a través de una red (normalmente TCP/IP), haciendo uso de un sistema operativo optimizado para dar acceso con los protocolos CIFS, NFS, FTP o TFTP.

Suelen tener varios discos y se pueden configurar en *[RAID](https://es.wikipedia.org/wiki/RAID)*

Hay discos duros exclusivos para NAS que tienen más durabilidad.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0667.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0668.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0669.png)

## Cabina de discos. Servidores de almacenamiento

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0670.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0671.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0672.png)

*[https://www1.la.dell.com/ue/es/gen/Empresarial/pvaul_md1000/pd.aspx?refid=pvaul_md1000&s=gen](https://www1.la.dell.com/ue/es/gen/Empresarial/pvaul_md1000/pd.aspx?refid=pvaul_md1000&s=gen)*

# RAID

Un RAID es un grupo de discos duros independientes configurados para funcionar como uno solo, ya sea sumando su espacio total, mejorando la velocidad de lectura y escritura o configurados para duplicar la información para estar seguros de que, en caso de que uno de los discos duros se rompa, no vamos a perder los datos.

Existen varios tipo de RAID

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0673.png)

## RAID 0

En esta configuración todos los discos duros funcionan como un único volumen, y su espacio total es la suma del espacio de todos los discos duros.

Doble velocidad de lectura y escritura.

No hay paridad de datos ni volumen de respaldo.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0674.png)

## RAID 1

Es uno de los tipos de RAID más utilizados para quienes buscan duplicidad de los datos para estar seguros de que los datos nunca se pierden. En este tipo de RAID, los datos se duplican en los discos duros como si fuese un espejo.

Mayor velocidad de lectura. Sin mejora en la velocidad de escritura.

Un disco duro espejo. Si falla uno de los discos duros se puede reemplazar sin perder datos.

Perdemos el 50% del espacio total de los discos. El espacio total de un RAID 1 es la mitad del espacio total de los discos duros. Por ejemplo, si hacemos un RAID 1 con dos discos duros de 4 TB solo tendremos un espacio total de 4 TB.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0675.png)

## RAID 5

La información se distribuye a lo largo de todos los discos duros, aunque se reserva dicho espacio (el tamaño de una de las unidades) para paridad. Esta paridad, además, se reparte entre todos los discos duros.

Si fallan dos discos se pierde absolutamente toda la información del RAID.

La mejora de velocidad de lectura es también X-1 veces el número de discos usados.

El espacio total de los discos es X-1, El espacio total de un RAID 5 es el espacio de todos los discos duros menos 1, es decir, si vamos a usar 4 discos duros de 4 TB el espacio total será de 12 TB.

Si falla uno de los discos duros, cualquiera de ellos, se puede reemplazar y recuperar todos los datos.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0676.png)

## RAID 6

Prácticamente igual que el RAID 5, pero añade un segundo nivel de paridad, lo que nos permite que fallen hasta dos discos duros del RAID y poder sustituirlos. Si fallan 3, entonces toda la información del RAID se pierde.

El espacio total de los discos es X-2, igual que la mejora de la velocidad de lectura. A cambio de esta doble paridad incluida en el RAID 6 se pierde el espacio total de dos de los discos duros. Por ejemplo, en una configuración de 4 discos duros de 4 TB, el espacio total que tendríamos es de 8 TB, con el doble de velocidad de lectura.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0677.png)

# Almacenamiento en la nube

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad0678.png)

Un sistema de almacenamiento en la nube o Cloud Storage es un modelo de almacenamiento de datos basado en redes de ordenadores donde nuestros datos están alojados en espacios de almacenamiento virtualizados. Por lo tanto, el espacio no se encuentra en el propio equipo físico del usuario, sino en uno o varios servidores ofrecidos por la compañía que contratemos el servicio.

## Ventajas 

### Rentabilidad

Con el almacenamiento en la nube, no hay que comprar hardware, ni aprovisionar almacenamiento, ni utilizar capital adicional para los picos de la empresa. Puede agregar o eliminar capacidad de almacenamiento bajo demanda, cambiar rápidamente las características de rendimiento y retención, y pagar solo por el almacenamiento que realmente utiliza. A medida que se accede a los datos con poca frecuencia y en contadas ocasiones, puede incluso trasladarlos automáticamente a un almacenamiento de menor costo, con lo que se consigue un ahorro de costos aún mayor. Al trasladar las cargas de trabajo de almacenamiento de las instalaciones a la nube, puede reducir el costo total de propiedad al eliminar el exceso de aprovisionamiento y el costo de mantenimiento de la infraestructura de almacenamiento.

### Mayor agilidad

Con el almacenamiento en la nube, los recursos están a un solo clic. Se reduce el tiempo para poner esos recursos a disposición de su organización de semanas a solo minutos. Esto se traduce en un aumento espectacular de la agilidad de su organización. El personal se libera en gran medida de las tareas de adquisición, instalación, administración y mantenimiento. Y como el almacenamiento en la nube se integra con una amplia gama de herramientas de análisis, su personal puede ahora extraer más información de sus datos para impulsar la innovación.

### Despliegue más rápido

Cuando los equipos de desarrollo están listos para comenzar, la infraestructura nunca debería ralentizarlos. Los servicios de almacenamiento en la nube permiten al Departamento de TI suministrar rápidamente la cantidad exacta de almacenamiento que se necesita, cuando y donde sea necesario. Los desarrolladores pueden centrarse en resolver problemas complejos de las aplicaciones en vez de tener que administrar los sistemas de almacenamiento.

### Administración eficiente de los datos

Al utilizar políticas de administración del ciclo de vida del almacenamiento en la nube, puede realizar potentes tareas de administración de la información, incluida la separación por niveles automatizada o el bloqueo de datos para cumplir con los requisitos de conformidad. También puede utilizar el almacenamiento en la nube para crear un almacenamiento multirregional o global para sus equipos distribuidos mediante el uso de herramientas como la replicación. Puede organizar y administrar los datos de manera que admitan casos de uso específicos, creen eficiencias de costos, refuercen la seguridad y cumplan con los requisitos de conformidad.

### Escalabilidad 
El almacenamiento en la nube ofrece una capacidad de almacenamiento casi ilimitada, lo que le permite escalar verticalmente tanto y tan rápido como necesite. Esto elimina las limitaciones de la capacidad de almacenamiento local. Puede escalar o desescalar verticalmente de forma eficaz el almacenamiento en la nube según sea necesario para los análisis, los lagos de datos, copias de seguridad o aplicaciones nativas de la nube. Los usuarios pueden acceder al almacenamiento desde cualquier lugar y en cualquier momento, sin preocuparse de los complejos procesos de asignación de almacenamiento ni de esperar a que haya nuevo hardware


# Estructura lógica de los discos

La estructura de partición . Se encarga de definir cómo se organiza la información en el disco duro. Independientemente del hardware o del sistema operativo, todas las computadoras se inician utilizando MBR (BIOS) o GPT (UEFI) .

Espacio particionado . Es el espacio del disco que ha sido asignado a alguna partición. Una partición es una división del disco duro, de forma que el sistema operativo la considera como si fuera una unidad totalmente independiente. Algunos usuarios prefieren tener particiones independientes para los datos personales, los programas y los archivos del sistema operativo.

Espacio sin particionar. Es espacio no accesible del disco ya que todavía no ha sido asignado a ninguna partición y está sin formatear.

## MBR (Master Boot Record)

* En discos duros que tienen tabla de particiones con el esquema MBR, cuando se crean las particiones, se graba dicha información en el sector de arranque del disco (MBR). Básicamente, el MBR es un tipo especial de sector de arranque que se encuentra en el comienzo de los dispositivos de almacenamiento de datos particionados, como un disco duro fijo o una unidad de almacenamiento externa, y que contiene una tabla de particiones que indica el lugar del disco donde se encuentran las particiones. Normalmente, en dicha tabla se guarda información sobre:
    * el tipo de partición,
    * el tamaño de la partición (se indica dónde empieza y dónde acaba cada partición),
    * si es o no la partición activa (que es la que está configurada para arrancar).
* De esta forma, cuando arranca un ordenador la BIOS intenta localizar el MBR donde identifica la partición definida como activa y se inicia el proceso de arranque. Dicho de otra forma, el MBR apunta a la partición activa y el equipo comenzará a cargar el sistema operativo almacenado en esa partición activa o un menú de arranque que permita elegir el sistema operativo (si tiene varios instalados) a arrancar.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06124.png)

* Tamaño de 512 bytes
* Consta de tres partes
    * Master Boot Code o cargador de arranque (446 bytes). Contiene códigos y datos que la BIOS necesita para iniciar la carga del sistema operativo (SO).
    * Tabla de particiones (64 Bytes). Posee información sobre las distribuciones del disco duro. Información de hasta 4 particiones de 16 bytes cada una.
    * Firma (2 bytes) → 0x5AA. Los sistemas operativos utilizan la firma de disco para identificar y diferenciar diferentes dispositivos de almacenamiento de datos y unidades de disco duro en la computadora para el acceso a los datos.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06125.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06126.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06127.png)

## GPT (GUID Partition Table)

** GPT (GUID Partition Table)** es un nuevo estándar para colocar tablas de particiones en medios de almacenamiento. Forma parte de la (UEFI).

GPT se localiza al comienzo del disco duro ( *[Primary GUID](https://es.wikipedia.org/wiki/Tabla_de_particiones_GUID)* ), al igual que el MBR, pero no en el primero, sino en el segundo sector. El primer sector todavía está reservado para MBR (Protective MBR) por motivos de seguridad y para conservar la compatibilidad con sistemas más antiguos.

Los datos críticos para el funcionamiento de la plataforma se almacenan en particiones en lugar de hacerlo en sectores ocultos o no particionados (como en el caso de MBR). Además, los discos GPT incluyen tablas de partición principales redundantes (Primary GUID) y de copia de seguridad (Backup GUID) a fin de mejorar la integridad de la estructura de datos de la partición.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06128.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06129.png)

MBR &rarr; BIOS // GPT &rarr; UEFI

![image](https://github.com/alexlopezprofe/MyM/assets/148449360/a87824f1-d580-4b4d-9680-04bb863b2291)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06130.png)

> ¿Qué pasa si se corrompe MBR?

> ¿Qué pasa si se corrompe GPT?

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06131.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06132.png)

## Tipos de particiones

### Partición primaria.

Puede ser reconocida como una partición de arranque y puede contener un sistema operativo que realice el arranque del equipo. Una de las particiones primarias se llama la partición activa y es la de arranque. El ordenador busca en esa partición activa el arranque del sistema. Cuando hay varios sistemas operativos instalados la partición activa tiene un pequeño programa llamado gestor de arranque que presenta un pequeño menú que permite elegir qué sistema operativo se arranca. Los sistemas operativos detectarán las particiones primarias y les asignará una unidad. Límite de 4 en MBR y 128 en GPT.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06133.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06134.png)

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06135.png)

### Partición extendida.

También conocida como partición secundaria, sirve para contener múltiples unidades lógicas en su interior. Fue ideada para romper la limitación de 4 particiones primarias en un solo disco físico por tanto sólo se utiliza en MBR. Solo puede existir una partición de este tipo por disco, y solo sirve para contener particiones lógicas. Por lo tanto, es el único tipo de partición que style="color:#333333"> *no* style="color:#333333"> soporta un sistema de archivos directamente. No se puede instalar un sistema operativo en ella. style="color:#333333"> *Solo aplicable a MBR.*

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06136.png)

Disco duro con tres particiones primarias y una extendida.

### Partición lógica.

Ocupa una porción de la partición extendida o la totalidad de la misma, y se puede formatear con un sistema de archivos diferente (FAT32, NTFS, ext3, ext4, etc.) y se le asignan una unidad, así el sistema operativo reconoce las particiones lógicas o su sistema de archivos. **Solo aplicable a MBR.**

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06137.png)

Disco duro MBR con tres particiones primarias y una extendida con cuatro lógicas

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06138.png)

**Disk Management - Administrador de discos**

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06139.png)

# Sistema de archivos

El sistema de archivos o File System es un método para el almacenamiento y organización de archivos y los datos que estos contienen, para hacer más fácil la tarea encontrarlos y acceder a ellos.

Para ello, el sistema operativo utiliza las famosas “carpetas” o “directorios” con el fin de organizar todas las rutas y localizar la información contenida en el disco duro.

La estructura de directorios suele ser jerárquica, ramificada o en árbol invertido.

![](https://github.com/alexlopezprofe/MyM/blob/main/assets/img/Unidad06/Unidad06140.png)

Los principales tipos sistemas de archivos que encontramos son los siguientes:

* NTFS (New Technology File System).
* HPFS (High Performance File System).
* EXT (Extended file System).
* HFS+ (Hierarchical File System).
* APFS (Apple File System).
* FAT (File Allocation Table).
* exFAT (Extended File Allocation)
* FAT32.
* ReFS
