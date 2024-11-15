# Evaluacion AED3
Leer con atención teniendo en cuenta la condición de entrega y cada punto detallado. De no cumplirse esto, la entrega será inválida y se evaluará con un 1 (uno). Tendrán todo lo necesario para resolver esta evaluación en este mismo repositorio, por lo que las búsquedas en la Web estarán completamente prohibidas. Sin nada más que agregar les deseo suerte y éxitos (espero). 😇

# Metodología
Esta evaluación es un tanto particular como se darán cuenta. La misma consiste en realizar una librería para el MPU6050, un módulo que contiene un acelerómetro y un giróscopo de 3 ejes, además de un sensor de temperatura. Cada función que deban crear estará especificada tambien con su nombre, pero el tipo lo deberán determinar ustedes. 
Como último, deberán crear un código de ejemplo con la utilización de dicha librería donde se muestre el uso de sus funciones.
Una aclaración no menor es que no podrán utilizar nada por fuera de lo que brinda este repositorio. Cualquier otra búsqueda realizada o página abierta será de sanción y tendrá un 1(uno) en la evaluación. Quitando la posibilidad de poder rendir el recuperatorio.

# Giróscopo y Acelerómetro
Un giróscopo es un dispositivo que mide la velocidad angular de un objeto, esto quiere decir que mide que tan rápido rota o gira alrededor de un eje. Importante para saber la orientacion por ejemplo, o para ver rotaciones o giros.
Un acelerómetro es un dispositvo capaz de medir la aceleración lineal que actúa sobre un objeto en uno o mas ejes. Esto quiere decir que mide la aceleración que se le aplica al objeto en cualquiera de los tres ejes. Sirviendo ver inclinaciones.

# Consignas
Realizar una librería llamada *"MPU6050"* para el módulo MPU6050 que contenga estas funciones:
* *MPU6050_Init()*: Inicializa el módulo, como así también se inicializará todo lo necesario para el correcto funcionamiento del módulo y la placa.
* *MPU6050_AcelX()*: Esta función proporcionará la componente X del acelerómetro.
* *MPU6050_AcelY()*: Esta función proporcionará la componente Y del acelerómetro.
* *MPU6050_AcelZ()*: Esta función proporcionará la componente Z del acelerómetro.
* *MPU6050_GiroX()*: Esta función proporcionará la componente X del giroscopio.
* *MPU6050_GiroY()*: Esta función proporcionará la componente Y del giroscopio.
* *MPU6050_GiroZ()*: Esta función proporcionará la componente Z del giroscopio.
* *MPU6050_Temp()*: Esta función devolverá el valor de temperatura en grados Celcius.

Además deberán realizar una solucion programable en la que, al pasar el umbral que se especifica al final de la consigna se deberán encender diferentes leds (tres en total) en los que se indique si se paso ese umbral (encendido) o no (apagado) para saber si un objeto fue inclinado.

*UMBRALES: X:400 ; Y:200 ; Z:550*.

Esto último sería el código de ejemplo a adjuntar.

# Método de entrega
Al finalizar la clase (a eso de las 17hs), se habilitará el uso de internet para la subida de la librería a un repositorio de GitHub. Dicho repositorio será subido a la tarea *"Evaluación 2° Cuatrimestre"* dentro de nuestro Classroom. Dentro del repositorio tienen que encontrarse tres archivos. Dos para la librería y uno del código de ejemplo. Se valorará la sintáxis y orden del código, como así también las partes aclaradas (comentarios).

# Aclaraciones finales
* Se prodrán usar las librerías brindadas en este repositorio para los diferentes protocolos de comunicación.
* Utilizar *define* para todos los comandos, modos y/o pines utilizados, especificando en su nombre lo que hace y siempre en mayúscula.
* Cada función valdrá medio punto. Los puntos restantes los darán la prolijidad y su habilidad para programar, además del código de ejemplo.
* Librería que esté completamente desordenada penalizará puntos, por lo que podría ser causante de desaprobación.
* 
* Si las compus llegan a tener Windows 7 descargar el siguiente VSCode: https://update.code.visualstudio.com/1.70.2/win32-x64-user/stable 
