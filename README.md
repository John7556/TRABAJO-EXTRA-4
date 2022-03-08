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
 
 ![image](https://user-images.githubusercontent.com/93899720/157210720-f8899071-fb5e-47e4-9560-77d648e71a85.png)

2- 

Abrimos nuestro navegador de preferencia y escribimos Blocky Duino seleccionamios la primera pagina la cual nos llevara directo ala plataforma donde programaremos nuestro circuito.

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

4. RESPUESTA A INTERROGANTES 

Que progrmacion es mas efectiva la programacion por texto o la programacion por bloques que es la revisada en este proyecto ?

La programacion por bloques nos ayuda a tener una interfaz mas didactica que la que tenemos en un progrmador por texto aparte que la progrmacion poe bloques nos ayuda a mantener un orden especifisco al momento de programar ya que no puedes emter bloques donde ne encajen puesto que todo esta diseñado para que vaya en una secuencia y se acomode perfectamente cpn los demas bloques.

5. VIDEO

https://youtu.be/5rx0Bzr42X8

6. CONCLUSIONES

*

* 

7. BIBLIOGRAFÍA

* Pines digitales de Arduino, lo que nadie se atreve a contar. (s. f.). Programar fácil con Arduino. Recuperado 22–03-08, de https://programarfacil.com/blog/arduino-blog/pines-   digitales-de-arduino/

* Pines Arduino UNO Configuración. (s. f.). HETPRO/TUTORIALES. Recuperado 22–03-08, de https://hetpro-store.com/TUTORIALES/pines-arduino/

* Arduino Uno a fondo. Mapa de pines. (s. f.). Aprendiendo Arduino. Recuperado 22–03-08, de https://aprendiendoarduino.wordpress.com/2016/06/27/arduino-uno-a-fondo-mapa-de-       pines-2/
