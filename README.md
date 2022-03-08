# Informe De Trabajo Extra Tutorial de programación de Pines IO de una Arduino a través de BlocklyDuino 


1. OBJETIVO GENERAL 

* Construir y comprender la programacion en bloques la cual nos permite una forma mas interactiva y didactica de programar remplazando asi ala progrmacion por texto.

1.2. OBJETIVOS ESPECIFICO 

* Detallar y explicar la elaboracion de la progrmacion en bloques.

* Definir e indentificar el uso especifico de cada uno de los bloques para programar.

2. MARCO TEÓRICO 


![image](https://user-images.githubusercontent.com/93899720/157250617-6c23a733-b285-4dac-8eaf-f41537d13476.png)
![image](https://user-images.githubusercontent.com/93899720/157250647-230f5127-70ff-4707-ba29-95ba0ea744d4.png)



3. EXPLICACIÓN DEL PROCEDIMIENTO

MATERIALES: 

* Computadora 
* Internet 

MATERIALES DENTRO DEL SIMULADOR: 

* PAGINA WEB DE EL SIMULADOR BLOVKDUINO 
* BLOQUES DE PROGRMACION 
* ARDUINO UNO 
* SERVO MOTOR 
* PULSADOR 
* CONEXIONES MEDIANTE SOFTWARE

1- 

 Primer paso explicamos cual va ser el circuito que se va a progrmar en este caso es un servomotorel cual regulara su accion de movimineto con un pulsador que estan conectados de la siguiente manera 
 
 https://blocklyduino.github.io/BlocklyDuino/blockly/apps/blocklyduino/
 
 ![image](https://user-images.githubusercontent.com/93899720/157210720-f8899071-fb5e-47e4-9560-77d648e71a85.png)

2- 

Abrimos nuestro navegador de preferencia y escribimos Blocky Duino seleccionamos la primera pagina la cual nos llevara directo ala plataforma donde programaremos nuestro circuito.

![image](https://user-images.githubusercontent.com/93899720/157211383-ac83c535-9fbc-41e6-94b1-ff6341d29985.png)

![image](https://user-images.githubusercontent.com/93899720/157211443-7579ec6b-6051-4a54-b9dc-f972a9b2f4fa.png)

![image](https://user-images.githubusercontent.com/93899720/157211517-04b37f1d-1592-486c-a823-17de1b1a6e2f.png)

3-
 Prestamos atencion al meno dopciones que tenemos en nuestro lateral izquiero ya que estos son las familias de bloquees por los cuales programaremos nuestro circuito entonces comenzamos creando un lector digital el cual lea cuando mi pulsadormr esta siendo aplastado y cuando no.
 
![image](https://user-images.githubusercontent.com/93899720/157211987-806d5433-2b43-48ca-86a9-404747fbcaef.png)
![image](https://user-images.githubusercontent.com/93899720/157212157-b18e2944-f946-4b20-a8aa-05f8a2489e90.png)

3- 
Seguido de esto y ya teniendo un lector de una señal ahora podemos añadir un control para etsa misma señal por lo que nos vamos alas opciones de control la localizamos y el bloque corrspondiente a este control podemos darle una accion matematica por lo que vamos a las opciones matematicas selcccionando la correcta le damos una funcion matematica correspondiente.

![image](https://user-images.githubusercontent.com/93899720/157212802-1c51ca04-6461-4a5d-92f4-26687fd96545.png)
![image](https://user-images.githubusercontent.com/93899720/157212851-5e6a4212-7d32-44c5-ab33-4cf6104fb88c.png)

4- 
A este control le añadimos la accionde poder mover el servomotor por lo que nos vamos a sus opciones y y selccionamos la cual nos permita moder un servomotor en los grados requeridos .

![image](https://user-images.githubusercontent.com/93899720/157213352-f4b83a20-6605-4b55-978a-d5819be13d12.png)
![image](https://user-images.githubusercontent.com/93899720/157213430-b51f9331-0217-488a-a6af-4a7d09078750.png)

5-
Ahora debajo del control de movimiento del servomotor colocamos un delay el cual nos permite controlar el tiempo que demorara cada accion en este caso el tiempo sera de 3 segundos.

![image](https://user-images.githubusercontent.com/93899720/157213808-980ad4b9-9115-482b-a43c-d47413335e11.png)


6-
Ahora coon la parte del movimiento ya programado nos falta programar la parte de regreso al grado 0 del servomotor por lo que repetimos los pasos anteriores sacamos un bloque que nos ayude con la accion de dictar movimiento al arduino pero esta vez desde el angulo de 90 a el angulo . De igual manera colocamos un delay para que nos ayude a controlar el tiempo de esta accion que de igual forma seria 3 segundos.

![image](https://user-images.githubusercontent.com/93899720/157214314-993e22fb-ce01-449d-8fa4-046ae2714be2.png)

![image](https://user-images.githubusercontent.com/93899720/157214512-d57a214d-fa9e-458a-882c-c07a571c6805.png)

7-
Verificamos si hay errores en el codigo que se nos haya pasado por alto antes de ejecutarlo y pasarlo a tinkercad para comprobar. Si es de nuestra necesidad prodemos agregar bloques de comentarios para cuando se revise codigo se tenga una nocion mas clara de lo que se esta haciendo.

![image](https://user-images.githubusercontent.com/93899720/157214893-5128933b-23e6-4fec-aefc-9a1278d6beab.png)

8- 
Ya revisado el codigo y viendo que todo esta programado correctamente procedemos a copiar nuestro codigo y pegarlo en tinkercad en donde nuestro circuito esta armado y esperando el codigo para que este pueda funcionar.

![image](https://user-images.githubusercontent.com/93899720/157215223-2c4970a5-8c2e-4ef0-9ef1-a784feaa72ed.png)
![image](https://user-images.githubusercontent.com/93899720/157215295-d6c43acd-a3cd-454f-adcf-1eba7c999972.png)

Como podemos ver el circuito se ejecuta sin ningun problema por lo que la programacion en bloques fue hecha correctamente.


Ahora se procede a realizar el circuito en fisico, como primer paso colocamos el pulsador en el protoboard.


![WhatsApp Image 2022-03-08 at 2 20 34 PM](https://user-images.githubusercontent.com/93899720/157313520-7ef0d062-fd4f-4261-b146-1f318932ccee.jpeg)
![WhatsApp Image 2022-03-08 at 2 20 34 PM (1)](https://user-images.githubusercontent.com/93899720/157313571-db40e594-d192-4e62-a694-6055faaa5987.jpeg)


Hacemos las conexiones pertinentes con las entradas del pulsador. 


![WhatsApp Image 2022-03-08 at 2 20 34 PM (2)](https://user-images.githubusercontent.com/93899720/157313776-486d4315-8658-4ea5-a431-c3bb3828661e.jpeg)


Como el circuito no es complejo se procede a conectar el pulsador con el servomotor y esto se conecta al arduino.


![WhatsApp Image 2022-03-08 at 2 20 35 PM](https://user-images.githubusercontent.com/93899720/157313927-dca7d594-96fc-4777-bfcc-7cef36b2cb42.jpeg)

Proceso de contruccion fisica del circuito.

1-

Colocamos nuestro pulsador de la misma forma que en nuestro simulador.

![WhatsApp Image 2022-03-08 at 2 20 34 PM](https://user-images.githubusercontent.com/93899720/157329239-5b0824e4-7675-42c6-8a73-fa954c221b13.jpeg)

2-

Conectamos las resistencias correspondientes que en este caso es una resistencia de 1 kilohmio y de igual manera conectamos el polo positivo y negtivo de nuestro pulsador.

![image](https://user-images.githubusercontent.com/93899720/157329427-ba4c9066-4d0e-4abe-b0cf-81d339da313e.png)

3- 

Conectamos los cables positivo y negativo de nuestro servomotor ala protoboard y de igual manera los puenteamos para que esten interconectados con el pulsador ahora conectaremos el arduino en sus respetivos pines de la siguiente manera 

![image](https://user-images.githubusercontent.com/93899720/157330239-31fe0136-203b-46ff-ae76-198bd633390c.png)

4-

Conectamos el sensor de nuestro servomotor en el pin 9 de nuestro arduino como lo vemos en la siguiente imagen .

![image](https://user-images.githubusercontent.com/93899720/157330966-140b6134-5e64-4cf9-ac61-e8c1996868da.png)

5-

Sacamos un cable del pin 4 que se conectara en al pulsador para tener la señal que active su movimiento.

![image](https://user-images.githubusercontent.com/93899720/157331498-8265dea3-7b6f-4bf0-8585-40d139a4c7eb.png)

6-

Ahora copiamos nuestro codigo ejecutado con anterioriridad y lo grabamos en nuestro arduino lo que queda de la siguiente manera.

![image](https://user-images.githubusercontent.com/93899720/157331885-a4d043ec-3719-43a9-9e3b-8beaa6de7e65.png)


4. RESPUESTA A INTERROGANTES 

Que progrmacion es mas efectiva la programacion por texto o la programacion por bloques que es la revisada en este proyecto ?

La programacion por bloques nos ayuda a tener una interfaz mas didactica que la que tenemos en un progrmador por texto aparte que la progrmacion poe bloques nos ayuda a mantener un orden especifisco al momento de programar ya que no puedes emter bloques donde ne encajen puesto que todo esta diseñado para que vaya en una secuencia y se acomode perfectamente cpn los demas bloques.

5. VIDEO

https://youtu.be/5rx0Bzr42X8

6. CONCLUSIONES

* Se llega a la conclusión de que la programación por bloques es mucho mas interactiva que la programación habitual por texto lo cual ayuda de manera inmensa a la comprensión de   la lógica de programación. 

* Se concluye que la programación por bloques es programación de alto nivel ya que se puede hacer los mismo que la programación en texto, pero con ciertas limitaciones.

7. BIBLIOGRAFÍA

* Pines digitales de Arduino, lo que nadie se atreve a contar. (s. f.). Programar fácil con Arduino. Recuperado 22–03-08, de https://programarfacil.com/blog/arduino-blog/pines-   digitales-de-arduino/

* Pines Arduino UNO Configuración. (s. f.). HETPRO/TUTORIALES. Recuperado 22–03-08, de https://hetpro-store.com/TUTORIALES/pines-arduino/

* Arduino Uno a fondo. Mapa de pines. (s. f.). Aprendiendo Arduino. Recuperado 22–03-08, de https://aprendiendoarduino.wordpress.com/2016/06/27/arduino-uno-a-fondo-mapa-de-       pines-2/
