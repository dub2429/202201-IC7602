# Prueba Corta #1

 <font size="4"> 
 
1. Un usuario de telefonía móvil se encuentra en un auto en movimiento a 30 kms por hora, el mismo cruza el límite de una celda y de pronto la llamada actual se detiene de forma repentina, asumiendo que todo el sistema se encuentra funcionando de forma adecuada, ¿Por qué razón la llamada se detiene?

En cualquier instante, cada teléfono móvil se encuentra practicamente en una celda específica y bajo el con trol de la estación base de esa celda. Cuando un teléfono móvil sale fisicamente de una celda, su estación base detecta que la señal telefónica se desvanece y pregunta a todas las estaciones base circundantes cuánta potencia están recibiendo de ese teléfono. Al recibir las respuestas, la estación base transfiere la propiedad a la celda que está recibiendo la señal más fuerte. Por esto la llamada se detiene, hasta conectar con la celda más cercana, en la mayoria de las condiciones es la celda en la que se encuentra el teléfono en ese momento. A continuación se informa al teléfono sobre su nuevo jefe y, si hay una llamada en progreso, se le pide que cambie a un nuevo canal, ya que el anterior no se reutiliza en ninguna de las celdas adyacentes. Este proceso es el handoff y tarda cerca de 300 milisegundos. 

2. ¿Explique de forma concisa porqué la transmisión de ondas de baja frecuencia no es práctica en medios inalámbricos?

A veces es conveniente usar un rango de frecuencias que no empiece en cero para enviar información a través de un canal. En los canales inalámbricos no es práctico enviar señales de muy baja frecuencia. ya que el tamaño de la antena necesita ser de una fracción de la longitud de onda de la señal, por lo que llega a ser grande. 

Una mayor frecuencia implicaría tener una mayor capacidad para transmitir datos. Una buena heuristica aqui es que cada estación móvil transmita a la estación base con una magnitud de potencia inversa a la que recibe de la estación base. Es decir, una estación móvil que reciba una señal débil de la estación base utilizará más potencia que una que reciba una señal fuerte.

3. Ante una crisis como conflicto bélico o un desastre natural, que daña o afecta los canales de comunicación o infraestructura de un país, ¿Qué tipo de transmisión recomendaría a ese país para mantener comunicación con el resto del mundo? Explique.

Mantener antenas que trabajen con frecuencias de Amplitud Modulada, ya que este tipo de frecuencia es muy usada actualmente para cadenas de emergencia. Una emisora de AM es mucho mas útil que una de FM para transmitir en zonas de terreno montañoso, dado al tamaño de la onda y la forma de propagación que esta tiene.

AM es el medio preferido por los radiodifusores internacionales para cualquier parte del mundo con costos muy bajos. Una gran ventaja de AM es que su demodulación es muy simple y, por consiguiente los receptores son sencillos y baratos. Si fuese necesario ante una crisis, varias torres pueden ayudar para comunicar con el exterior. Igualmente si se lograra implementar por medio de satélites, pero este último puede salir mas complicado y costoso. 

La frecuencia AM es usada en la radiofonía, en las ondas medias, ondas cortas y también se puede en ondas de largo alcance. Utiliza la variación de amplitud de las señales eléctricas para transportar el audio, empleando ondas sonoras cortas, medias y largas que se propagan mediante tierra y aire. Por lo anterior la cobertura que brinda este sistema es muy amplia y permite llegar a grandes distancias, aunque a menor potencia, que eso podría ser parte de sus desventajas.

4. Explique el concepto ancho de banda en telecomunicaciones.

El rango de frecuencias que se transmiten sin atenuarse con fuerza se conoce como ancho de banda. En la práctica, el corte en realidad no es abrupto, por lo que con frecuencia el ancho de banda ofrecido va desde 0 hasta la frecuencia en la que el valor de la amplitud es atenuado a la mitad de su valor original. 

El ancho de banda es una propiedad física del medio de transmisión y por lo general depende de la construcción, grosor y longitud de dicho medio. En algunos casos, se introduce un filtro en el circuito para limitar la cantidad de ancho de banda disponible para cada cliente.  

El ancho de banda realmente se ha vuelto más un asunto de marketing que otra cosa. En telecomunicaciones por ejemplo un cable de teléfono podría tener un ancho de banda de 1 MHz para distancias cortas, pero las compañías de teléfono agregan un filtro que restringe a cada cliente a aproximadamente 3100 Hz. Este ancho de banda es adecuado para el lenguaje inteligible y mejora la eficiencia del sistema al limitar a los usuarios en el uso de los recursos. 

5. Explique las diferencias entre conmutación de paquetes y conmutación de circuitos.

La conmutación de circuitos busca una trayectoria física que vaya desde el dispositivo (un teléfono) al del receptor. La red telefónica usa redes de cables que se interconectan entre si para crear una sola línea de comunicación, toda la información se mueve de forma segura sin perder datos por medio de un canal de transmisión conmutada. Una llamada pasa por una oficina de conmutación, se establece una conexión física (en forma conceptual) entre la línea por la que llegó la llamada y una de las líneas de salida En la conmutación de circuitos es la necesidad de establecer una trayectoria de un extremo a otro antes de que se pueda enviar cualquier dato.

Con la conmutación de paquetes, en conmutación de mensajes, no hay límite para el tamaño de los bloques, lo que significa que los enrutadores (en un sistema moderno) deben tener discos para almacenar en forma temporal los bloques grandes. También significa que un solo bloque puede acaparar una línea de enrutador a enrutador durante minutos, lo que hace inútil la conmutación de mensajes para el tráfico interactivo La conmutación de paquetes hace referencia al modo en que los datos de dividen para ser enviados, estos paquetes se envían de forma independiente a través de cualquier tipo de ruta, y son reconstruidos en el punto de destino, esto puede generar más tiempo a la hora de envíos de datos.

La conmutación de paquetes utiliza transmisión de almacenamiento y reenvío. Un paquete se almacena en la memoria del enrutador y luego se reenvía al siguiente enrutador. Con la conmutación de paquetes los bits simplemente fluyen de manera continua a través del cable. La técnica de
almacenamiento y reenvío agrega un cierto retardo.

Otra diferencia es que la conmutación de circuitos requiere que un circuito se establezca de extremo a extremo antes de que comience la comunicación. En cambio la conmutación de paquetes no requiere un establecimiento previo, ya que el primer paquete puede simplemente enviarse tan pronto como esté disponible. El resultado del establecimiento de conexión mediante la conmutación de circuito es la reserva de ancho de banda que se realiza desde el emisor hasta el receptor.

 
</font> 