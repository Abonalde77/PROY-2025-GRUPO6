# PROY-2025-GRUPO6
Repositorio del grupo 6 para el proyecto del ramo *Proyecto Inicial* – 2025.

## 👥 Integrantes del grupo

| Nombre y Apellido | Usuario GitHub | Correo USM               | Rol          |
| ----------------- | -------------- | ------------------------ | ------------ |
| Ángel Bonalde     | Abonalde77     | abonalde@usm.cl          | 202530039-7  |
| Joaquín Muñoz     | JM20070305     | jmunozle@usm.cl          | 202530042-7  |
| Mattias Miranda   | Mirandaa06     | mmirandaa@usm.cl         | 202530029-k  |

---

## 📝 Descripción breve del proyecto

- El Proyecto consiste en detectar y transformar sonidos con distinta intensidad a patrones de vibraciones receptibles  por el usuario con el fin de informar a personas con discapacidad auditiva sobre posibles amenazas en su entorno.

---

## 🎯 Objetivos

- Objetivo general:
  - A traves de un microfono conectado a la raspberry pi pico w, detectar el sonido y dividirlo en diferentes niveles de intensidad para luego tranformar el sonido a vibraciones con un motor de vibracion el cual vibrara de acuerdo al nivel de sonido detectado.
- Objetivos específicos:
  - Conectar un microfono y un motor de vibracion para que funcionen en conjunto.
  - Dividir el sonido recibido por el microfono en diferentes niveles de intensidad.
  - Aplicar patrones de vibracion al motor a partir de los niveles de intensidad del paso anterior.

---

## 🧩 Alcance del proyecto

Lo que se escapa de nuestras manos es el no poder distingir cada tipo de sonido, ya que para lograr nuestro objetivo vamos a dividir la intensidad del sonido en distintos niveles para hacer más practica la deteccion del sonido, provocando que no podamos detectar cada tipo de sonido, dejandolos en ciertos rangos de intensidad.

---

## 🛠️ Tecnologías y herramientas utilizadas

- Lenguaje de programación:
  - Micropython
- Editor de codigo:
  - Thonny IDE (principal)
  - Visual studio code (secundario)
- Microcontrolador:
  - Raspberry Pi Pico W 2
- Accesorios:
  - Microfono (KY-038) y Motor de vibracion (PWM Switch DC)

---

## 📜Instrucciones de uso:

-Conectar la Raspberry Pi Pico al computador con el cable USB.

-Abrir Thonny IDE o cualquier otro entorno de programación compatible con Micropython.

-Asegúrate de que la Raspberry tenga el firmware de MicroPython cargado.

-Para cargar el código en la Raspberry Pi Pico:
  Pegar el código en Thonny.
  Guardar el archivo como main.py en la Raspberry.
  
-Una vez cargado el código y reiniciada la placa, el programa comenzará a ejecutarse automáticamente. Si se hizo correctamente, el dispositivo vibrará una vez.

Para armar el dispositivo seguir el siguiente diagrama:

 # Diagrama de conexión:
 
![Image](https://github.com/user-attachments/assets/085717fd-51fc-4301-b63a-51fa1488ac6c)

Observaciones: El microfono viene con un potenciometro (el cuadrado celeste con una cruz) el cual permite ajustar el umbral de sensibilidad del micrófono, esto ayuda a que el micrófono pueda percibir sonidos de mejor forma en diferentes situaciones, por lo cual dependiendo de la situación se puede ajustar a gusto. Si el microfono se le ajusta con la maxima sensibilidad, este detectara sonidos grandes y pequeños en un area grande, mientras que si se le ajusta con la sensibilidad minima, solo detectara ruidos muy fuertes en un area pequeña. El ajuste de sensibilidad lo dejaremos en un punto medio, pero se puede calibrar rotando la cruz en sentido horario para disminuir su sensibilidad y en sentido antihorario para aumentarla.

---

## 🗂️ Estructura del repositorio


│/PROY-2025-GRUPO6

├── [docs/](https://github.com/Abonalde77/PROY-2025-GRUPO6/tree/main/Documentación)            
├── [src/](https://github.com/Abonalde77/PROY-2025-GRUPO6/tree/main/CodigoFuente)                 
├── [test/](https://github.com/Abonalde77/PROY-2025-GRUPO6/tree/main/Pruebas)                     
└── [README.md](https://github.com/Abonalde77/PROY-2025-GRUPO6/tree/main/README.md)            


---

##  <ins>Metodología</ins>

 **La metodología del trabajo para desarrollar el proyecto consistirá de tres fases, las cuales serán explicadas a continuación:**

PRIMERA FASE (INVESTIGACIÓN):
Se basa en la investigación de las diferentes herramientas que se utilizarán para la creación del proyecto. En este caso, sería como tal la investigación de la misma Raspberry Pi Pico W. Además, también se investigará el lenguaje de programación con el que se hará el trabajo, que será "MicroPython", y por último, el entorno de desarrollo integrado en el que se trabajará, que será el programa "Thonny". En esta etapa se profundizará acerca de todo lo que nos servirá para poder llevar a cabo el proyecto mediante diferentes recursos como lo son: videos, documentos, manuales, etc.

SEGUNDA FASE (DESARROLLO):
Esta segunda fase se concentrará en el desarrollo del proyecto como tal, de modo que en esta fase se desarrollen los códigos de programación para nuestro proyecto, la implementación de los complementos para la Raspberry Pi Pico W, en este caso, el motor de vibración (PWM Switch DC) y el micrófono (KY-038), y las pruebas experimentales que se realizarán para detectar fallas en el proceso. Esta fase será la de más duración durante el tiempo, ya que contempla una gran exigencia de tiempo.

TERCERA FASE (PRESENTACIÓN):
Esta es la última fase del proyecto; consistirá en revisar los aspectos finales del dispositivo y dejarlos listos para su demostración final, acompañada de una presentación del proceso del trabajo. En caso que el proyecto no se hubiera podido completar o se hubiera completado de forma parcial, se mostraran los avances que se tengan hasta el momento.

---

## 📅 Cronograma de trabajo


[Carta Gantt](https://docs.google.com/spreadsheets/d/1LX-G_uqnHj18W3ZObbhTS2TRwiaP0gzFi_ikWV4aN8w/edit?usp=sharing)

---

## 📚 Bibliografía

-[Micrófono-Led](https://www.youtube.com/watch?v=hjuNL5xqxZg)

-[Pulsadores](https://www.youtube.com/watch?v=5T07X1IW9MU)

-[Micrófono](https://www.youtube.com/watch?v=dQW4oFJt9c8)

Uso de inteligencia artificial (chatgpt, google gemini, perplexity).

---

## 📌 Notas adicionales

# Posibles mejoras:</ins> 
Una vez terminado este proyecto pudimos concluir mejoras respecto a este, las cuales son las siguientes:

-Cambiar de microfono para obtener mejores resultados y poder hacer funcionar el codigo de los parametros.

-Incorporar una bateria al proyecto para que no dependa de la energia del computador.

-Añadir un led para identificar la funcionabilidad del proyecto.

-Añadir una pantalla para mostrar los sonidos a nivel visual.

-Añadir sonidos en especifico y que asi sea mucho mas especifico cada sonido y los dicrimine por ello.



# <ins>Consideraciones:</ins>
- Eramos 4 miembros pero una integrante se fue de la universidad en el transcurso del trabajo, por lo cual recayo más trabajo en el resto.
- Buscamos los componentes por muchas tiendas y nos respondian diciendo que pronto llegarian o que no los tenian en su tienda, debido a esto decidimos comprarlas por internet, esto provoco un atraso en el desarrollo del proyecto.
- El primer microfono que se compro vino defectuoso, por lo cual se tuvo que pedir otro y se perdio tiempo en la espera.
- Tras el cambio de micrófono, este seguía careciendo de la calidad suficiente para realizar detecciones precisas del nivel de sonido, por lo que la capacidad del proyecto se vio limitada. Aún asi se logró parcialmente el objetivo.
