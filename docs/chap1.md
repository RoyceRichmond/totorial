#Advanced Programming#

En esta sección se da una explicación mas amplia sobre la programación de los microcontroladores STM32, esto incluira teoría sobre los buses de infomacion, el funcionamiento, interfaces, registros, etc.

Si lo que requieres es un recordatorio de como usar las librerías HAL utiliza  ve al [Quick start Programming](chap2.md#Quick start Programming) para mas detalles.   

##¿Qué tiene que ver la navidad con las librerías HAL?##
ST implementa librerias llamadas HAL (Hardware Abstraction Layer) para los microcontroladores STM32.
Las librerias HAL permiten implementar funciones mas sencillas, que no dependen del hardware sobre el que se implementen, sin embargo el costo es un mayor tiempo de ejecución por instrucción.

Para aplicaciones con requerimientos de tiempo muy precisas es preferible utilizar los registros del microcontrolador STM utilizado.

