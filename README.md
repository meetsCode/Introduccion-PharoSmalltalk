COMO TRABAJAR CON SEASIDE (PHARO VERSION)
Esta cuenta en Github (meetscode) las construí con la intención de poder colgar los resultados de los meetups a los que asisto del grupo de Software Craftmanship de Barcelona.
Siempre nos ponemos por parejas y no siempre programo con Smalltalk pero cuando lo hago me gusta compartir el trabajo conseguido así como el material que usé. Normalmente este material se reduce a los esquemas que hago a mano alzada para ordenar mis ideas. Para ese fin uso el programa GoodNotes en el iPad (varias veces recibí esa pregunta).

No es muy difícil poder disfrutar del código aquí ofrecido pero es muy distinto a como se está acostumbrado a trabajar, debido a las peculiaridades del entorno de programación Pharo. Por esa razón he construido este guión que explica cómo poder disfrutar de código. También puede usarse este guión como introducción a Pharo porque eso es en realidad.

Empezaré hablando de Pharo. Pharo es uno de los distintos sabores de Smalltalk. Es libre y gratuito desarrollado para la licencia del MIT. A diferencia de Squeak - que se desarrolló más para un uso infantil- Pharo está más orientado para el desarrollo profesional. Pharo es un fork de Squeak. En el momento de escribir estas líneas la versión 5 es la estable. Casi todo lo que describo para Pharo es válido para Squeak.

Smalltalk es un lenguaje de programación orientado a objetos puro. Fue el primer lenguaje que funcionó encima de una máquina virtual. Más tarde esto quedó popularizado por Java. Eso significa que para S.O. tendremos que bajar e instalar una máquina virtual. La ventaja de esto es que el resto de ficheros necesarios para hacer funcionar nuestro código es el mismo independientemente del S.O. o máquina que usemos. 

Pharo necesita para funcionar -además de la Máquina virtual- dos ficheros. Uno con la extensión .image y el otro con la extensión .changes Estos dos ficheros contienen el estado de la máquina en el último momento en que fue parado. los ficheros .image pueden pararse y ejecutarse en cualquier otra máquina. Impresiona ver como puedes llevarte el trabajo de una máquina a otra manteniendo todo el estado en el que estaba.

Podéis bajaros tanto la máquina virtual como los ficheros necesarios de este enlace:
http://pharo.org/download

Cuando se arranca Pharo se ve todo un sistema gráfico con sus propias ventanas. Para cargar un paquete se usa el programa Monticello. Para acceder a él basta con hacer click sobre el fondo del escritorio (en Squeak lo llaman World ) y una de las opciones es “Monticello Browser” Una vez abierto pulsáis el botón +Repository y allí elegís el directorio donde está el paquete que queréis absorber (debe tener extensión .mcz)

Para inspeccionar las clases se usa la opción “System Browser” que también aparece en el menú contextual del fondo de escritorio. En ese Browser podemos buscar una sola clase haciendo click en el botón derecho sobre los paquetes y seleccionando “Find Class…” Si conocemos el nombre del paquete (coincide con el nombre del fichero .mcz) podemos ponerlo en el recuadro bajo el botón “Scoped”

A la derecha del recuadro de los paquetes hay otros tres recuadros. En el primero de los tres veréis las clases del paquete seleccionado a la izquierda. Una vez seleccionada una clase veréis los protocolos y a continuación los métodos de esa clase. Bajo todos ellos veréis el código conforme lo seleccionéis.

Espero que sirva de ayuda. Este texto lo iré modificando en función de las consultas o consejos que me deis. Gracias