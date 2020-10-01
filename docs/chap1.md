#Quick start Programming#

##Aviso parroquial##
Si lo que buscas es aprender mas sobre los microcontroladores STM32 ve al [Advanced Programming](chap1.md#Advanced Programming#) para mas detalles. Si buscas algo rapido y sin mucha teoría quedate aquí.

![Screenshot](img/meme1.jpg){: style="height:200px;width:300px"}

Ahora si, a lo que te truje chencha.
#Programas de referencia.
##uso basico de GPIO.
Para escritura en los GPIO se utilizan las siguientes instrucciones.
```C
HAL_GPIO_WritePin (GPIO_TypeDef *GPIOx, uint16_t GPIO_Pin, GPIO_PinState PinState)
 	//Escribe un 1 o 0 logico al pin especificado

HAL_GPIO_TogglePin (GPIO_TypeDef *GPIOx, uint16_t GPIO_Pin)
 	//Cambia el estado de un pin.  	
```
Un ejemplo de escritura en el puerto D, pin 5 se ve a continuacion

```c
HAL_GPIO_WritePin (GPIOD, GPIO_PIN_5, GPIO_PIN_SET) //1 LOGICO.
HAL_GPIO_WritePin (GPIOD, GPIO_PIN_5, GPIO_PIN_RESET) //0 logico.
HAL_GPIO_TogglePin (GPIOD, GPIO_PIN_5) //cambio de estado.
```

Para la lectura en los GPIO se utiliza la instrucción.
```
HAL_GPIO_ReadPin (GPIO_TypeDef *GPIOx, uint16_t GPIO_Pin)
```
Un ejemplo de lectura en el puerto B, pin 5 se ve a continuacion
```c
HAL_GPIO_ReadPin (GPIOD, GPIO_PIN_5) //cambio de estado.
```
##ADC

##UART

##SPI





## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

| Method      | Description                          |
| :---------: | :----------------------------------: |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |

## Commands##

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
