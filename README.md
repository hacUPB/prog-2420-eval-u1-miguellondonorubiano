[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ZHlrD2sU)


# **Partes principales de un computador moderno** 

![Organizador Grafico Partes de un computador moderno](1.png)

![Graficas Adjuntas](2.png)



## **Preguntas a responder**
- **1.¿Cuál es la función principal de cada componente investigado?**
Según su clasificación van a desempeñar una tarea distintita, ya que cada componente está especializado en algo especifico, pero de manera general.
El Hardware se divide en periféricos, que son los encargados de extender y facilitar la interacción con el usuario, la memoria que es la encargada de almacenar la información, y el procesamiento que se encarga de interpretar las instrucciones de los programas a través de operaciones lógicas aritméticas.


- **2.¿Cómo interactúa el hardware con el software, cuál es la función de cada uno?**
Tanto el Software como el Hardware trabajan en conjunto para un correcto funcionamiento de la máquina, a través del sistema operativo, Drivers y aplicaciones.

-  Hardware: Estos son los componentes físicos y tangibles de la máquina, entre ellos la CPU, la memoria RAM, el disco duro, la placa base, la tarjeta gráfica, etc. Su función es ejecutar las instrucciones y almacenar los datos necesarios para el funcionamiento del software.
- Software: Son aquellas cosas intangibles lógicas que se encuentran en la máquina, como los programas y sistemas operativos que controlan y coordinan el hardware para realizar tareas específicas. 


-**3.¿Cuál es la función de la CPU y cuáles son sus partes más importantes?**
La CPU (Unidad Central de Procesamiento) es un elemento que actúa como el cerebro de la máquina. Su función principal es ejecutar instrucciones de programas mediante operaciones aritméticas, lógicas, de control y de entrada/salida (I/O).
-Unidad de Control (CU): Dirige todas las operaciones de la CPU, decodificando las instrucciones y señalando a los demás componentes lo que deben hacer.

-Unidad Aritmeticológica (ALU): Realiza operaciones matemáticas y lógicas.
-Registros: Son pequeñas áreas de almacenamiento rápido dentro de la CPU que guardan datos temporales y las instrucciones que se están ejecutando.
-Caché: Memoria de alta velocidad que almacena datos e instrucciones a las que se necesita acceder rápidamente.
-Buses: Sistemas de comunicación que transfieren datos entre la CPU y otros componentes del ordenador.


- **4.¿Qué es la velocidad de la CPU, también conocida como velocidad del reloj?**
La velocidad de la CPU es aquella que determina cuántos ciclos de instrucciones puede ejecutar la CPU por segundo. Un reloj de CPU de 3 GHz, por ejemplo, puede ejecutar 3 mil millones de ciclos por segundo. Esta velocidad influye directamente en el rendimiento y la rapidez con la que la CPU puede procesar datos y ejecutar instrucciones.

- **5.¿Cuál es la secuencia de pasos que ocurre, desde el momento en que presionas el botón de encendido de la computadora, hasta que se muestra el sistema operativo listo para funcionar? Describe todos los elementos involucrados y el paso a paso.**
1. Botón de Encendido:
•	Al presionar el botón de encendido, la fuente de alimentación (PSU) envía energía eléctrica a todos los componentes del sistema.
2. POST (Power-On Self-Test):
•	La BIOS/UEFI realiza una serie de pruebas para asegurarse de que el hardware básico (memoria, teclado, discos, etc.) funciona correctamente.
3.  Cargar la BIOS/UEFI:
•	La BIOS/UEFI inicializa y configura los componentes de hardware y prepara el sistema para arrancar. Luego busca un dispositivo de arranque (disco duro, SSD, USB, etc.).
4.  Carga del Bootloader:
•	Una vez que se identifica el dispositivo de arranque, la BIOS/UEFI carga el bootloader (como GRUB para Linux o el Boot Manager de Windows) desde el dispositivo de arranque en la memoria RAM.
5.  Carga del Sistema Operativo:
•	El bootloader carga el núcleo del sistema operativo (kernel) en la memoria RAM y transfiere el control al sistema operativo.
6.  Inicialización del Sistema Operativo:
•	El sistema operativo inicializa sus componentes, carga los controladores de dispositivos y configura el entorno de usuario.
7.  Pantalla de Inicio de Sesión:
•	Una vez que el sistema operativo está completamente cargado y configurado, muestra la pantalla de inicio de sesión o el escritorio, listo para que el usuario comience a utilizar la computadora.

-**6.Comenta algo que no sabías y que descubriste en esta actividad**
A pesar de estar cursando nuevamente la materia, hay cosas que desconocía, como lo es la velocidad reloj, conocer esto , nos ayuda a desarrollar mejores componentes , así mismo el saber que comprar a la hora de armar un computador a base de componentes; así mismo había partes en el proceso de encendido de una computadora que desconocía.


### ***Bibliografias***

![Bibilografias](3.png)



# **Actividad 2: Sistemas numéricos**

## Diagrama de bloques 
A continuacion se presenta el diagrama de bloques , enfocado en como opera el sistema de control de una aeronave.


![Diagrama de bloques](bloq.png)

## Tres casos de aplicación.

![Pagina 1](pag1.png)
![Pagina 2](pag2.png)
![Pagina 3](pag3.png)

## Conclusiones de la actividad. 
-	El realizar correctamente diagramas de bloques, nos permite ver y entender la estructura, así como el funcionamiento de un sistema, en este caso modular, de una manera mucho más clara y ordenada. Además, este tipo de mapa ayuda a identificar las principales etapas del proceso y las interacciones entre los componentes, facilitando la comprensión por pasos del sistema.
-	El implementar un bit de paridad en cada uno de los datos, nos pude ayudar a ser más precisos a la hora de trabajar con grandes cantidades de estos, al permitir verificar errores en la codificación o variación de estos.
-	El computador solo va a entender lo que le hagamos entender, el solamente entiende binario, así mismo, sus componentes solo entienden este lenguaje, por esto es necesario la transcripción a binario.
-	Así mismo el nombrar datos o etiquetarlos, me permite identificar en que parte del proceso están estos. 




# Actividad 3: Algoritmos

Se pide resolver una serie de problemas utilizando algoritmos, dos de ellos a libre elección del estudiante y el problema número 6 de manera obligatoria.

Para resolver estos problemas, utilizamos un ejemplo dado por el docente, que nos servirá de guía para resolver los ejemplos propuestos ,el ejemplo consiste en calcular el gasto de energía eléctrica de una persona en un mes:

Inicio

    Definir gasto_total como 0
    Definir costo_kWh como 0.15
    Leer el número de días en el mes (n)
    Para cada día desde 1 hasta n hacer
        Leer lectura_dia
        Sumar lectura_dia a gasto_total
    Fin Para
    Multiplicar gasto_total por costo_kWh
    Imprimir gasto_total
Fin

## Problema 1: Determinar el promedio de calificaciones de un estudiante y si ha aprobado o no
Ana quiere saber si ha aprobado sus exámenes finales. Tiene una lista de sus calificaciones y necesita calcular el promedio. Para aprobar, debe tener un promedio de al menos 3.0.

Inicio

    Definir suma como 0
    Definir promedio como 0.0
    Leer el número de calificaciones que tiene Ana (n)
    Para cada i desde 1 hasta n hacer
        Leer calificación
        Sumar calificación a suma
    Fin Para
        Dividir suma entre n para calcular el promedio
     Si promedio >= 3.0 entonces
        Imprimir "Aprobado"
    Si no
        Imprimir "No aprobado"
Fin

## Problema 4: Determinar la distancia total recorrida por un vehículo con registros de velocidad y tiempo
María tiene un registro de las velocidades a las que ha conducido su vehículo y el tiempo que ha mantenido cada velocidad. Quiere calcular la distancia total recorrida.

Inicio

    Definir distancia total como 0
    Definir velocidad como 0
    Definir tiempo como 0
    Leer el número de Velocidades/registros que tiene Ana (n)
    Para cada registro desde 1 hasta n hacer:
        Leer velocidad
        Leer tiempo
        Calcular distancia parcial de un viaje = velocidad * tiempo
        Sumar distancia parcial de un viaje a distancia total 
    Fin Para
    Imprimir "La distancia total recorrida por María a lo largo de sus viajes es: " + distancia total
Fin

## Problema 6 (obligatorio): Calcular la edad de una persona a partir de su fecha de nacimiento y la fecha actual
Descripción del Problema: Se desea saber cuántos años, meses y días tiene actualmente una persona, basándose en su fecha de nacimiento. Además, le gustaría saber si ya ha cumplido años este año o aún no, y si hoy es su cumpleaños para celebrarlo. Cada una de las fechas está conformada por 3 variables: día, mes y año

Inicio

    Leer día nacimiento
    Leer mes nacimiento
    Leer año de nacimiento 

    Leer día actual
    Leer mes actual
    Leer año actual

    Edad en años =Año actual-Año de nacimiento

    Condicionales:
    Si (mes actual< mes nacimiento) o (mes actual = mes de nacimiento y día actual <día nacimiento) entonces 
        Edad en años =edad en años-1
    Fin si

    Meses totales=(año actual – año nacimiento)*12 +mes actual -mes nacimiento
    Días totales =(año actual – año nacimiento)*365 +(mes actual -mes nacimiento)*30+dia actual – día nacimiento
    Si (mes actual = mes nacimiento y día actual = día nacimiento) entonces 
        Imprimir: “Feliz Dia, hoy es tu cumpleaños”
    Fin si
    Imprimir “Edad en años” + Edad en años 
    Imprimir “Edad en meses” + meses totales
    Imprimir “Edad en días” + días totales

 Fin
