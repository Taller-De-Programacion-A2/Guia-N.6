# Guia-N.6
Guia Numero 6 Codigos Hilos y Procesos

## Preguntas Orientadoras
¿Cuáles fueron los aprendizajes obtenidos al realizar esta guía?, liste como mínimo 3 aprendizajes y relaciónelos con su futuro quehacer profesional.
  - Entender los procedimientos de procesos y el uso de hilos para desarrollar procesos simultáneos.
  - Entender métodos utilizados para correr los procesos como el Run ().
  - Entender que es un Buffer para compartir hilos y que estos se comuniquen entre si empleando diferentes métodos.

¿Dónde presentó mayor dificultad resolviendo la guía? ¿Cómo lo resolvieron? ¿Cuáles fueron las estrategias de la solución?
  - Se presento mayor dificultad en entender los diferentes nuevos métodos y la utilización de los hilos, en la parte del modelo consumidor y productor para generar datos y otro para recibirlos, se solucionó investigando en diferentes bibliografías, además de videos entre otros.

Sesión N°1
  1. ¿Qué es el paralelismo de datos?
  Es una técnica utilizada en la computación paralela donde grandes conjuntos de datos se dividen en partes más pequeñas y se distribuyen entre varios procesadores para ser procesados simultáneamente. Cada procesador realiza la misma tarea o conjunto de instrucciones sobre diferentes porciones de datos en paralelo. Es común en aplicaciones de análisis de datos masivos, como el procesamiento en la nube o en redes neuronales profundas.
  2. ¿Qué es el paralelismo de tareas?
  Implica dividir un problema en varias tareas diferentes que pueden ejecutarse de manera simultánea en distintos procesadores. Cada procesador ejecuta una tarea distinta que es parte del mismo proceso general. Este enfoque es útil cuando las tareas son independientes entre sí y se pueden realizar en paralelo, como en sistemas multiproceso o la división de funciones en un juego o aplicación compleja.

Sesión N°2
  2. Consulte acerca de los potenciales problemas en el paralelismo de datos y de tareas
Problemas en el paralelismo de datos:
1. Desbalanceo de carga: Si los datos no están distribuidos equitativamente entre los procesadores, algunos podrían tener más trabajo que otros, lo que resulta en ineficiencia.
2. Contención de recursos: Si los procesos acceden a recursos compartidos (como memoria o archivos), pueden producirse cuellos de botella, ya que deben sincronizar su acceso.
3. Overhead de comunicación: Dividir los datos y combinarlos nuevamente puede generar un overhead significativo, especialmente si los datos son muy grandes o los procesadores están en diferentes nodos de una red.
Problemas en el paralelismo de tareas:
1. Interdependencia entre tareas: Si las tareas dependen entre sí, los procesos pueden bloquearse esperando que otro complete su parte, lo que reduce el paralelismo.
2. Condiciones de carrera: Si múltiples tareas intentan acceder y modificar un mismo recurso al mismo tiempo, pueden ocurrir condiciones de carrera, lo que lleva a resultados incorrectos o inesperados.
3. Bloqueo mutuo (Deadlock): Puede ocurrir cuando dos o más hilos indefinidamente por un recurso que otro hilo está utilizando, lo que paraliza todo el sistema. Para evitar esto, es crucial un buen diseño de la sincronización.

Enlaces
  Enlace de video con explicación del uso de los códigos:
  https://youtu.be/SsmJxEoa7fU






