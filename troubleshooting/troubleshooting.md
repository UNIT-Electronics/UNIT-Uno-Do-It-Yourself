# ERRORES COMUNES ❌

## La tarjeta no enciende al conectarla por USB o fuente externa

- Revisa que tu cable USB C no sea la causa del problema.

- Si es por fuente externa, revisa el cable de alimentación y que la polaridad sea la correcta.

- Verifica que no haya componentes faltantes dentro de tu UNIT UNO, también asegúrate que colocaste los componentes de forma correcta.

- Inspecciona tu soldadura, no debe de haber uniones o cortos entre los pines, tampoco debe faltar soldadura, tiene que unirse al pad.


## No puedo programar mi UNIT UNO DIY

- Revisa que tu ATMEGA328P este colocado de forma correcta en la PCB.

- Asegúrate que tu cable USB C tenga soporte de datos.

- El microcontrolador que utilices debe tener instalado el Bootloader, de lo contario el ARDUINO IDE no reconocerá tu tarjeta.

- Verifica que tu computadora tenga instalado el driver CH34X y que este reconociendo el puerto COM. Puedes hacerlo desde tu computadora en el ADMINISTRADOR DE DISPOSITIVOS -> Puertos (COM y LPT).

- Si no aparece que está conectada tu tarjeta te recomendamos instalar un nuevo Driver.


## ERROR: EL PUERTO SELECCIONADO NO EXISTE O TU PLACA NO ESTA CONECTADA

Si este error te aparece dentro del IDE de Arduino, debes de realizar lo siguiente:
- Da clic en ARCHIVO -> PREFERENCIAS -> AJUSTES
 
- Busca la opción VERIFICAR CÓDIGO DESPUÉS DE SUBIR y quita la paloma del cuadro, da clic en ok.
 ![]()
- Vuelve a subir el código a la tarjeta de desarrollo, el error ya no debe aparecer


## Ya subí mi programa a la UNIT UNO DIY, pero no enciende el led

- Verifica la polaridad del led, que este soldado a la tarjeta de forma correcta.

- Inspecciona tu soldadura, los componentes deben estar firmemente unidos al pad de la tarjeta, si presenta movimiento es necesario volver a soldar esa parte.

- Los valores de resistencia deben ser R3 = 1K y R4 = 10K.
