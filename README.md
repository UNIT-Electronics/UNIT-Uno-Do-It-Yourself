
![Logo](https://uelectronics.com/wp-content/uploads/2021/05/Logo-UNIT_Web-04-800x182.png)
# UNIT Uno Do It Your Self

Tarjeta de desarrollo basada en el ATMEGA328P compatible con el IDE de Arduino y con las shields y hardware diseñados para Arduino UNO el cual tiene como característica que puede ser armado por ti mismo.

Todos sus componentes son Through Hole, por lo que es ideal para personas que están comenzando a soldar o interesadas en el funcionamiento interno de una tarjeta de desarrollo, ya que conocerás las partes que conforman una tarjeta UNO convencional.
![](https://github.com/UNIT-Electronics/UNIT-Uno-Do-It-Yourself/blob/a01beced4e7fb894552f9791e0f5ee3087b31a74/UNIT%20UNO%20DIY.jpg)

## Manual

Consulta y descarga el manual de ensamblaje y programación completo en el siguiente [enlace](https://github.com/UNIT-Electronics/UNIT-Uno-Do-It-Yourself/blob/main/manual.pdf)

## ¿Qué incluye este kit? 🔧

| Parte             | Valor       |Descripción          |
| ----------------- | ------------|---------------------|
|C1|330nF|Capacitor Cerámico|
|C2|	100nF|	Capacitor Cerámico|
|C3|	100nF|	Capacitor Cerámico|
|C4|	100nF|	Capacitor Cerámico|
|C5|	22pF|	Capacitor Cerámico|
|C6|	22pF|	Capacitor Cerámico|
|C7|	100nF|	Capacitor Cerámico|
|C8|	100nF|	Capacitor Cerámico|
|C9|	100nF|	Capacitor Cerámico|
|C10|	1uF|	Capacitor Cerámico|
|C11|	47uF|	Capacitor Electrolítico 16V| 
|C12|	47uF|	Capacitor Electrolítico 16V|
|[CH340E](https://uelectronics.com/producto/unit-ch340e-modulo-usb-a-ttl-5v-3-3v-dtr/)|		|Convertidor CH340E con USB tipo C|
|D1|	1N4007|	Diodo 1A DO41|
|D2|	1N5819|	Diodo 1A DO41|
|IC1|	5V|	L7805CV Regulador 5V 1.5A|
|IC2|	3V3|	LD1117AL-33 Regulador 3.3V 1A|
|J1|	DC|	Conector Dc Power Jack|
|J2|	8 pin|	Tira Header Hembra 2.54mm 8 Pin|
|J3|	6 pin|	Tira Header Hembra 2.54mm 6 Pin|
|J4|	28 pines slim|	Base Socket 28 Pines |
|J5|	2 x 3 pin|	Pines Header Macho 2.54mm|
|J6|	10 pin|	Tira Header Hembra 2.54mm 10 pin|
|J7|	8 pin|	Tira Header Hembra 2.54mm 8 Pin|
|LED1|	Rojo|	Led de 3mm|
|LED2|	Verde|	Led de 3mm|
|LED3|	Verde|	Led de 3mm|
|LED4|	Amarillo|	Led de 3mm|
|Q1|	60V 200mA|	2N7000 Transistor Mosfet 60V 200mA Canal N|
|R1|	1K|	Resistencia 1/4W 5%|
|R2|	1K|	Resistencia 1/4W 5%|
|R3|	1K|	Resistencia 1/4W 5%|
|R4|	10K|	Resistencia 1/4W 5%|
|R5|	10K|	Resistencia 1/4W 5%|
|R6|	1K|	Resistencia 1/4W 5%|
|R7|	1K|	Resistencia 1/4W 5%|
|R8|	4K7|	Resistencia 1/4W 5%|
|SW1|	4 pin|	Push Button 4 pines|
|X1|	16MHz|	Oscilador Cristal Cuarzo HC-49S|
|[ATMEGA328](https://uelectronics.com/producto/atmega328p-atmel-microcontrolador/)|  |ATMEGA328P-PU Atmel Microcontrolador|

Así como la tarjeta de circuito impreso:
![](https://github.com/UNIT-Electronics/UNIT-Uno-Do-It-Yourself/blob/main/PCB.png)


## Materiales requeridos  📋

-	[Cautín tipo lápiz](https://uelectronics.com/categoria-producto/equipo-laboratorio/herramientas/)
-	[Soldadura de estaño](https://uelectronics.com/categoria-producto/equipo-laboratorio/material-general/)
-	[Cable USB tipo C](https://uelectronics.com/categoria-producto/componentes/cables/)
-	IDE de Arduino o compilador equivalente

## Conocimientos previos 🧠

-	Medición y lectura de resistencias, capacitores y diodos.
-	Polaridades dentro de un componente

## ¿Cómo soldar correctamente? ♨️

Te compartimos una infografía que te puede ser util al momento de soldar y de revisar que tu soldadura se la correcta 💯
![](https://github.com/UNIT-Electronics/UNIT-Uno-Do-It-Yourself/blob/a01beced4e7fb894552f9791e0f5ee3087b31a74/Soldadura.jpg)

## Características técnicas

USB tipo C
Voltaje de salida:
-	5V, 2 A por USB
-	5V, 800mA por conector Jack (Se requiere disipación)
-	3.3V, 800mA (Se requiere disipación)
  
Voltaje de entrada:
-	5V USB
-	7V – 12V Power Jack (sugerido 7V a 9V)
  
Microcontrolador: ATmega328

Pines Digitales I/O: 14 (de los cuales 6 son PWM)

Entradas Analógicas: 6 entradas

Corriente Directa por Pin: 40mA

Voltaje por Pin: 5V

Memoria Flash: 32 KB;de los cuales 0.5 KB son usados por el bootloader

SRAM: 2 KB

EEPROM: 1 KB

Frecuencia de Trabajo :16 MHZ

## Programación
Instala el driver [CH340E](http://www.wch.cn/download/CH341SER_EXE.html) en tu computadora y un compilador como Arduino IDE.

Ejecuta el código [blink](https://github.com/UNIT-Electronics/UNIT-Uno-Do-It-Yourself/blob/main/blink) y observa como el LED de tu tarjeta comienza a parpadear cada segundo.

¡Felicidades y bienvenido al maravilloso mundo de la programación de microcontroladores!

´´´
La guía completa de programación puedes encontrarla en el manual.pdf
´´´

## ERRORES COMUNES ❌

#### La tarjeta no enciende al conectarla por USB o fuente externa

- Revisa que tu cable USB C no sea la causa del problema.

- Si es por fuente externa, revisa el cable de alimentación y que la polaridad sea la correcta.

- Verifica que no haya componentes faltantes dentro de tu UNIT UNO, también asegúrate que colocaste los componentes de forma correcta.

- Inspecciona tu soldadura, no debe de haber uniones o cortos entre los pines, tampoco debe faltar soldadura, tiene que unirse al pad.


#### No puedo programar mi UNIT UNO DIY

- Revisa que tu ATMEGA328P este colocado de forma correcta en la PCB.

- Asegúrate que tu cable USB C tenga soporte de datos.

- El microcontrolador que utilices debe tener instalado el Bootloader, de lo contario el ARDUINO IDE no reconocerá tu tarjeta.

- Verifica que tu computadora tenga instalado el driver CH34X y que este reconociendo el puerto COM. Puedes hacerlo desde tu computadora en el ADMINISTRADOR DE DISPOSITIVOS -> Puertos (COM y LPT).

- Si no aparece que está conectada tu tarjeta te recomendamos instalar un nuevo Driver.


#### ERROR: EL PUERTO SELECCIONADO NO EXISTE O TU PLACA NO ESTA CONECTADA

Si este error te aparece dentro del IDE de Arduino, debes de realizar lo siguiente:
- Da clic en ARCHIVO -> PREFERENCIAS -> AJUSTES
 
- Busca la opción VERIFICAR CÓDIGO DESPUÉS DE SUBIR y quita la paloma del cuadro, da clic en ok.
 ![](https://github.com/UNIT-Electronics/UNIT-Uno-Do-It-Yourself/blob/main/ERROR.PNG)
- Vuelve a subir el código a la tarjeta de desarrollo, el error ya no debe aparecer


#### Ya subí mi programa a la UNIT UNO DIY, pero no enciende el led

- Verifica la polaridad del led, que este soldado a la tarjeta de forma correcta.

- Inspecciona tu soldadura, los componentes deben estar firmemente unidos al pad de la tarjeta, si presenta movimiento es necesario volver a soldar esa parte.

- Los valores de resistencia deben ser R3 = 1K y R4 = 10K.

## Autores ✒️

```
Material compilado por el equipo de UNIT Electronics
```
- [UNIT Electronics](https://uelectronics.com/)
- [Federico Hidalgo](https://github.com/fede-hidalgo)

