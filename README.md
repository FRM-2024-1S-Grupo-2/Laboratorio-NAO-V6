# Laboratorio-NAO-V6
Integrantes: Daniel Felipe Cantor Santana, Giovanni Obregon, Thomas Hernandez Ochoa, Andres Felipe Zuleta Romero

La idea de esta visita fue poder trabajar con robots humanoides, en específico con el robot NAO V6, disponible en las Universidad de la Sabana en Chia.  

## Descripción del laboratorio 
El laboratorio de la Universidad de la Sabana es bastante amplio, con 4 mesas para trabajo, conectores en la parte superior. Cuando llegamos habia un modelo de robot NAO por mesa a los cuales se les estaba reinstalado su software original.Se nos mostró otro robot movil, mucho mas sencillo, como el que se ve en la siguiente foto: 


<img src="https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-NAO-V6/blob/main/Anexos/Robot_2.jpg" alt="Robot_2" width="400">


Este robot no se programó o intentó mover, ya que el objetivo de la visita fue programar el robot NAO V6.

## Especificaciones Técnicas Robot NAO V6
- Altura: 58 cm
- Peso: 5.6 kg
- Grado de Libertad: 25
- Sensores: Cámara RGB, sensores de presión, giroscopio, acelerómetro, entre otros.
- Conectividad: Wi-Fi, Ethernet, USB

## Lenguajes de programación soportados:
El robot NAO, puede ser programado con C++, Python, Java o MATLAB. 
Durante la visita se usó el programa Choregraphe, para trabajar un entorno de programación gráfica. Dicho software posee un entorno de simulación para ver las rutinas de robot, ademas posee soporte para el trabajo con Scriptsde Python.

## Configuración Inicial
 Para comenzar a trabajar con el robot NAO V6, siga los siguientes pasos:

- Encendido: Asegurese de que el robot tiene la suficiente bateria para operar si no conecte el adaptador de corriente ubicado en la parte posterior del robot.
- Conexión a la red; Configure la conexión Wi-Fi o Ethernet para permitir la comunicación con el robot, al mantener presionado el botón del centro este dirá su dirección ip.
- Instalación del Software: Descargue e instale [Choregraphe](https://www.aldebaran.com/en/support/nao-6/downloads-softwares) el software proporcionado por el fabricante para programar y controlar el robot.

## Ejemplos de Uso

- Movimientos Prediseñados:
Choreographe proporciona una amplia gama de movimientos predefinidos que pueden ser fácilmente integrados en los comportamientos del robot. Estos movimientos incluyen acciones como caminar, girar, saludar, levantarse y sentarse, entre otros. Los usuarios pueden arrastrar y soltar estos comportamientos en una línea de tiempo para crear secuencias de movimientos complejas y coordinadas.
![image](https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-NAO-V6/assets/82681128/659c8986-2dc5-484c-b157-c3569e0eadea)


- Posturas Personalizadas:
Además de los movimientos predefinidos, Choreographe permite a los usuarios definir posturas personalizadas para el robot. Esto incluye ajustar la posición de las articulaciones del robot de manera precisa para crear expresiones faciales, gestos de las manos o posturas corporales específicas. Estas posturas personalizadas pueden ser luego utilizadas en combinación con los movimientos prediseñados para dar al robot una apariencia y comportamiento únicos.



https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-NAO-V6/assets/82681128/8a53a2b1-a928-4175-a50b-d7f0b5c5dd4e


- Uso de Sensores y Bocinas:
Choreographe también permite a los usuarios interactuar con los sensores y las bocinas del robot. Los sensores, como la cámara RGB, los sensores de presión y los giroscopios, pueden ser utilizados para detectar el entorno del robot y tomar decisiones basadas en la información recibida. Por otro lado, las bocinas pueden ser utilizadas para reproducir sonidos, música o mensajes de voz, lo que permite al robot comunicarse de manera auditiva con los usuarios.




https://github.com/FRM-2024-1S-Grupo-2/Laboratorio-NAO-V6/assets/82681128/664ecba5-35c5-4733-9e95-3bbb7235815e


## Análisis y reflexión 
- Pese a que se tengan muchos grados de libertad en el robot hay que tener presente que deben mantenerse limites para que este aun se mantenga en pie.
- Usar Choreographe está perfecto para un primer acercamiento a este tipo de robots, pero se pueden notar las limitaciones de dicho software, por lo que en un futuro podria intentarse el manejo del  robot a través de ROS u otras plataformas.

## Conclusión
### Experiencia
La visita al laboratorio de robótica fue una experiencia valiosa, proporcionando un conocimiento práctico del robot NAO V6 y algunas de sus capacidades. Nosotros aprendimos sobre la configuración inicial, programación en diagrama de bloques por medio de coreoghapy, y uso de algunos sensores del robot, ademas de experimentar con las posbles poses que realizaba este al mover manualmente sus articulaciones, ademas de interactuar con colegas de otra universidad que no aportaron algo de su conocimiento en este tema.

### Opiniones personales

- Daniel: Fue una salida muy interesante tener la posibilidad de poder trabajar con robots poco accesibles a nivel nacional, se me hizo una oportunidad única y de mucho aprendizaje. Pude entender con el uso de Choreographe el funcionamiento básico de los robots NAO y quedé con varias incógnitas y con muchas ganas de querer trabajar con estos robots a traves otras plataformas,es decir ¿que tan facil es su manejo a traves de ROS? ¿Existen limitacitaciones respecto al software? ¿El robot es viable para otro tipo de tareas?

- Giovanni: Para mi fue valioso tener un acercamiento con los robots caminadores, que presentan desafíos únicos en comparación con los robots con ruedas. Aprender que los robots NAO se pueden programar en diversos lenguajes, y no solo el que el fabricante nos da y en el que se realizo la practica. Tambien me intereso la flexibilidad en la programacion que debe tener el robot para realizar tareas complejas, como jugar un partido de fútbol, en competencias donde se debe pensar tanto grupal como individual.

- Thomás: Me pareció una salida enriquecedora porque se tuvo la oportunidad de conocer un laboratorio de otra institución, era la primera vez que trabajaba con robots humanoides lo cual resultó muy interesante, adicional a ello los estudiantes de la universidad de la sabana fueron muy cordiales y en todo momento nos brindaron su acompañamiento para desarrollar la actividad de manera adecuada, teniendo precaución en la manipulación de los robots

- Felipe: La experiencia fue muy interesante, ya que nunca había tenido la oportunidad de interactuar con robots humanoides como el NAO V6. Fue muy emocionante aprender a usar Choregraphe y ver cómo se pueden combinar los movimientos prediseñados para hacer tareas complejas

### Preguntas
- **¿Por qué es importante estudiar y trabajar con robots humanoides en el campo de la robótica?**
  <br>
Estudiar y trabajar con robots humanoides en el campo de la robótica es importante porque estos robots imitan la forma y los movimientos humanos, lo que facilita la interacción y colaboración con las personas. Los robots humanoides pueden ser utilizados en una variedad de aplicaciones, como asistencia en el hogar, terapia, educación y entretenimiento. Además, trabajar con robots humanoides permite a los investigadores y desarrolladores abordar desafíos complejos en áreas como la locomoción, la manipulación de objetos, el reconocimiento de voz y el procesamiento del lenguaje natural. Esto contribuye al avance de tecnologías que pueden ser aplicadas en otros tipos de robots y sistemas autónomos.


- **¿Qué características distintivas tienen los robots NAO que los hacen útiles para laenseñanza y la investigación?**
  <br>
  Los robots NAO tienen varias características distintivas que los hacen especialmente útiles para la enseñanza y la investigación. Primero, su diseño modular y sus capacidades de movimiento avanzadas permiten a los estudiantes y a los investigadores experimentar con una amplia gama de tareas y escenarios. Además, NAO es altamente programable y puede ser controlado mediante varios lenguajes de programación, incluyendo Python y C++, lo que lo hace accesible para personas con diferentes niveles de experiencia en programación. Su software Choregraphe proporciona una interfaz intuitiva para crear y probar comportamientos del robot, facilitando el aprendizaje práctico. Finalmente, NAO está equipado con sensores avanzados, cámaras y micrófonos, permitiendo estudios y proyectos en áreas como la visión por computadora, la inteligencia artificial y la interacción hombre-robot.


### Referencias:
- Robot NAO: https://revistaderobots.com/robots-y-robotica/robot-nao-caracteristicas-y-precio/?cn-reloaded=1





