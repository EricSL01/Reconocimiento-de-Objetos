# Reconocimiento-de-Objetos
El presente proyecto tiene la finalidad de crear un programa que reconozca componentes de la computadora a traves de la camara web usando el lenguaje de python

### Objetivos
El programa desarrollado tiene el objetivo de tener una ayuda visual y primer acercamiento al lenguaje de programación, ademas de los distintos componentes de una computadora asi como su evolución a lo largo del tiempo. Este tema es parte de la Unidad II del curso de Taller de computo. Esta unidad se enfoca en:

    * Explicar como fue la evolución del hardware y software de la computadora.

    * Identificar las características de los distintos tipos de computadoras.

    * Describir el hardware de acuerdo con su función y características.

    * Explicar la representación y cuantificación de la información en los diferentes dispositivos digitales.

    * Ver las características de los distintos sistemas operativos.

    * Describir los elementos del ambiente de trabajo de distintos sistemas operativos y administracion de archivos y carpetas.

    * Dar a conocer las características de propiedad, distribución y libertad de uso del software.

    * Identificar cuales pueden ser los riesgos del uso de software y explicar los daños que con lleva el hardware.

### Problema que se resuelve 
Cuando se inicia en el area de la programación y la computación el alumno, desconoce como los distintos lenguajes puede interactuar con cada componente de una computadora. Por lo tanto se ha dado la tarea de que exista un primer acercamiento con el lenguaje de python haciendo un pequeño programa que interactue con los 
alumnos viendo como pueden ser manipulados los diferentes perifericos de la computadora para darles un uso distinto, en este caso se usaria la camara web.

### Mención sobre los lenjuage(s) utilizado(s)
Se decidio el uso del lenguaje de Python por su sencillo manejo y comprension a la hora de sere aprendido, ademas de que tiene la ventaja de usar menos lineas de
codigo para ejecutar las tareas.

### Argumentación sobre la elección de este lenguaje
Python ofrece una sintaxis clara y legible que permite desarrollar aplicaciones con menos líneas de código que Java u otros lenguajes, lo que acelera el proceso de desarrollo. Además, Python es versátil y ampliamente utilizado en campos como ciencia de datos, inteligencia artificial y desarrollo web, lo que proporciona acceso a una gran comunidad de apoyo y una amplia variedad de bibliotecas y frameworks listos para usar.

## Ejemplo Basico de como usar el programa
Este programa una vez ejecutado comenzara por desplegar un menu de opciones con las opciones 1/2/3/4 como se ve en la siguiente imagen:
![](https://github.com/EricSL01/Reconocimiento-de-Objetos/blob/f5b425b2eeb90433a5ef980ac72c2153c293fd46/1.jpeg)

Las opciones 1 y 2 generaran las muestras para el reconocimiento de objetos siendo la opcion 1 las muestras positivas y la opcion 2 las muestras negativas.
Una vez que se elija una de las opciones, el programa se ejecuta y para tomar la muestra se pulsa la tecla "s" y se creara una carpeta en donde se aloja el 
programa que se ejecuta siendo la carpeta "p" para positivas y "n" para negativas

![](https://github.com/EricSL01/Reconocimiento-de-Objetos/blob/5e422cd1077fd816dd416c960a0362574975220d/2.jpeg)

Se recomienda tomar una muestras de 50/100 positivas y 300/500 negativas
Una vez tomadas las muestras se ejecuta el programa de entrenamiento cascade el cual generara un archivo xml que tendra dentro el comportamiento del objeto a
reconocer

![](https://github.com/EricSL01/Reconocimiento-de-Objetos/blob/01805950fdc7daf8dbc74116369536e4baecb0d6/3.jpeg)

Este programa se puede descargar de su pagina oficial: https://amin-ahmadi.com/cascade-trainer-gui/

El programa generado se llama: cascade.xml y se debe guardar en la misma carpeta donde alojamos nuestro programa principal
Una vez hecho esto podemos ejecutar la opción 3 que es la que se dedicara a reconocer el objeto.
Para finalizar se puede salir de cada una de las opciones dejando presionada la tecla ESC por 10 segundos o eligiendo la opcion 4 para finalizar todo el programa.


