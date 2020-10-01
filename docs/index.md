#Getting started#
##Antes de empezar##
* * *
La programación de los microcontroladores STM32 puede realizarse en una variedad de IDEs, para simplificar el proceso de programación, mantenimiento de versiones y unificar las librerias que se utilizan, se opta por utilizar la IDE CubeMX, anteriormente conocida como Atollic True Studio.

CubeMX cuenta con un configurador al que se ingresan las funciones deseadas, como puede ser la velocidad del oscilador, los perifericos que se desean inicializar, esto incluye las interfaces de comunicacion (I2C, UART, SPI, I2S...), interrupciones, uso de timers entre otras funciones.

Este configurador se encarga de generar el codigo apropiado para inicializar las opciones seleccionadas. De esta forma el programador solo se encargara de implementar el codigo que desee.
##Pequeña nota##
Todas las funciones implementadas por el configurador de CubeMX se utilizan con punteros, un repaso del uso de punteros en C es una buena idea.
##CubeMX y dependencias##
Descargar CubeMX IDE
CubeMx IDE puede descargarse de la [pagina oficial](https://www.st.com/content/st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-ides/stm32cubeide.html "Title").

Tambien se debe descargar e instalar el configurador de CubeMx de la [pagina oficial](https://www.st.com/en/development-tools/stm32cubemx.html "Title").

Dentro del archivo Zip se encuentran los archivos para poder instalarlo en Windows, Ios o Linux.

