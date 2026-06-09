# Diseño de un sistema de reconocimiento de gestos faciales y su relación con la innovación en la interacción de los videojuegos interactivos

**Documento base para tesis de sustentación**  
**Nivel:** Tercero de Bachillerato  
**Especialización:** Técnico Informático  
**Proyecto aplicado:** MoodVision AI / PlayFace  

## Nota de Formato APA

Este documento está redactado tomando como referencia una estructura académica compatible con normas APA. Para pasarlo a un documento final, se recomienda usar letra Times New Roman o Arial tamaño 12, interlineado doble, márgenes de 2,54 cm, sangría en la primera línea de cada párrafo y referencias ordenadas alfabéticamente al final.

Las citas colocadas en el texto siguen el estilo autor-año, por ejemplo: (Picard, 1997). Las referencias incluidas al final pueden servir como base para el documento final de tesis.

## Introducción

En la actualidad, la tecnología ha cambiado la manera en que las personas se comunican, aprenden y se entretienen. Los videojuegos, que antes dependían únicamente de botones, teclados o controles físicos, han evolucionado hacia nuevas formas de interacción más naturales e innovadoras. Dentro de este contexto, el reconocimiento de gestos faciales representa una alternativa interesante, porque permite que el rostro del usuario se convierta en una forma de control dentro de un entorno digital.

El presente trabajo de investigación se titula **“Diseño de un sistema de reconocimiento de gestos faciales y su relación con la innovación en la interacción de los videojuegos interactivos”**. El tema se enfoca en analizar cómo un sistema informático puede reconocer expresiones y movimientos faciales mediante una cámara web, para luego utilizar esa información dentro de una aplicación interactiva. ~~Esta propuesta se relaciona directamente con el proyecto MoodVision AI / PlayFace, el cual permite detectar emociones, visualizar datos en un dashboard y controlar un videojuego mediante gestos faciales.~~

La importancia de este tema se encuentra en que los sistemas de interacción tradicionales no siempre ofrecen experiencias accesibles, novedosas o adaptadas al comportamiento natural del usuario. Por esta razón, el uso de la inteligencia artificial y la visión por computadora puede aportar nuevas posibilidades en el desarrollo de videojuegos interactivos. Según Picard (1997), la computación afectiva estudia cómo los sistemas pueden reconocer y responder a aspectos relacionados con las emociones humanas. Esta idea se vincula con el propósito del proyecto, ya que el sistema no solo recibe acciones del usuario, sino que también interpreta señales faciales.

El proyecto permite comprender de forma práctica cómo se combinan varias áreas de la informática: desarrollo frontend, desarrollo backend, base de datos, inteligencia artificial, cámara web, procesamiento de imágenes y diseño de experiencia de usuario. Todo esto nos da como resultado una forma innovadora de interacción que puede ser comprendida y utilizada en un contexto educativo.

Por tanto, esta investigación busca explicar de manera clara cómo el reconocimiento de gestos faciales puede relacionarse con la innovación en videojuegos interactivos. El estudio se desarrolla desde un enfoque descriptivo y aplicado, adecuado para un estudiante de tercero de bachillerato técnico informático, ya que permite observar, explicar y demostrar el funcionamiento de una solución tecnológica real.

# Capítulo I

# Diseño de la Investigación

## 1.1 Antecedentes de la Investigación

El reconocimiento de gestos faciales se relaciona con diferentes áreas de estudio, como la inteligencia artificial, la visión por computadora, la computación afectiva y la interacción humano-computadora. Estas áreas han permitido que los sistemas informáticos puedan interpretar imágenes, detectar rostros, reconocer expresiones y responder de forma más natural a las acciones del usuario.

Un primer antecedente importante se encuentra en el estudio de las emociones humanas. Ekman (1992) planteó que existen expresiones faciales básicas que pueden relacionarse con emociones como alegría, tristeza, enojo, sorpresa, miedo y disgusto. Este aporte es relevante para la presente investigación porque el sistema propuesto trabaja con expresiones faciales para identificar emociones o gestos que luego pueden utilizarse dentro de una aplicación interactiva.

Un segundo antecedente se relaciona con la computación afectiva. Picard (1997) explicó que las computadoras pueden diseñarse para reconocer, interpretar y responder a estados emocionales humanos. Esta idea es fundamental para el proyecto, porque MoodVision AI / PlayFace no se limita a mostrar una cámara, sino que intenta interpretar señales del rostro y convertirlas en datos visibles para el usuario.

Un tercer antecedente corresponde a la visión por computadora. Viola y Jones (2001) presentaron un método de detección de objetos que fue muy importante para el reconocimiento de rostros en imágenes digitales. Aunque las tecnologías actuales han avanzado mucho más, este tipo de investigaciones permitió que los sistemas modernos puedan detectar rostros de manera más rápida y eficiente.

Un cuarto antecedente se encuentra en la interacción humano-computadora. Esta área estudia cómo las personas se comunican con los sistemas digitales. En los videojuegos, la interacción ha evolucionado desde teclados y controles tradicionales hacia pantallas táctiles, sensores de movimiento, realidad virtual y reconocimiento facial. Esto demuestra que la innovación en videojuegos no depende únicamente de mejores gráficos, sino también de nuevas formas de participación del usuario.

Finalmente, el desarrollo actual de tecnologías web permite ejecutar modelos de inteligencia artificial directamente en el navegador. Herramientas como TensorFlow.js y face-api.js hacen posible analizar imágenes de la cámara sin depender completamente de un servidor externo. Esta característica se relaciona con el proyecto porque el reconocimiento facial y emocional se ejecuta principalmente desde el frontend, permitiendo una experiencia más inmediata e interactiva.

En conjunto, estos antecedentes muestran que el reconocimiento de gestos faciales no es una idea aislada, sino el resultado de avances en emociones humanas, inteligencia artificial, visión por computadora e interacción digital. Por esa razón, el diseño de un sistema de este tipo puede aportar una propuesta innovadora dentro de los videojuegos interactivos.

## 1.2 Planteamiento del Problema

Los videojuegos interactivos han formado parte importante del entretenimiento digital durante muchos años. Sin embargo, la mayoría de ellos todavía dependen de métodos de control tradicionales, como teclado, mouse, mandos o pantallas táctiles. Aunque estos dispositivos son útiles, también limitan la forma en que el usuario puede interactuar con el juego, ya que requieren contacto físico directo y no aprovechan completamente las expresiones naturales del cuerpo humano.

En la actualidad, las personas buscan experiencias digitales más dinámicas, accesibles y novedosas. Los avances tecnológicos han permitido que los sistemas puedan reconocer voz, movimiento corporal, ubicación, imágenes y rostros. A pesar de ello, en muchos proyectos educativos o videojuegos básicos, el reconocimiento facial todavía no se aprovecha como una forma principal de interacción. Esto genera una oportunidad de investigación, especialmente en el área técnico informática, donde se pueden crear prototipos que demuestren nuevas formas de comunicación entre el usuario y la aplicación.

El problema principal se encuentra en que la interacción tradicional en videojuegos no siempre permite una experiencia suficientemente innovadora ni natural. Por ejemplo, para mover un personaje normalmente se presionan teclas o botones. Sin embargo, el rostro humano puede expresar intención mediante gestos como mirar hacia un lado, abrir la boca, sonreír o levantar las cejas. Si estos gestos se reconocen correctamente, podrían utilizarse como comandos dentro de un videojuego.

El proyecto MoodVision AI / PlayFace surge como una propuesta para explorar esta situación. La aplicación usa la cámara web para detectar el rostro del usuario, reconocer emociones y obtener información facial. Además, incluye un juego en el que los gestos del rostro pueden servir para controlar acciones del personaje. Esto demuestra que la cámara no solo puede funcionar como un accesorio visual, sino como un medio de interacción.

No obstante, el reconocimiento de gestos faciales también presenta dificultades. La precisión puede depender de la iluminación, la calidad de la cámara, la posición del rostro, la distancia del usuario y la capacidad del sistema para interpretar correctamente los puntos faciales. Además, al trabajar con cámara e imágenes, también se deben considerar aspectos de privacidad, consentimiento y uso responsable de los datos. Estos elementos hacen que el tema no sea únicamente técnico, sino también educativo y ético.

Desde el punto de vista académico, el problema se puede expresar de la siguiente manera: existe la necesidad de estudiar y diseñar un sistema que permita reconocer gestos faciales para mejorar la interacción en videojuegos, demostrando si esta forma de control puede considerarse una innovación frente a los métodos tradicionales. Esta necesidad se relaciona con la formación técnica informática, porque permite aplicar conocimientos de programación, inteligencia artificial, diseño web, bases de datos y análisis de sistemas.

Por lo tanto, la pregunta central de esta investigación es:

**¿De qué manera el diseño de un sistema de reconocimiento de gestos faciales puede relacionarse con la innovación en la interacción de los videojuegos interactivos?**

A partir de esta pregunta, se busca analizar cómo un prototipo funcional puede reconocer gestos mediante una cámara web y utilizarlos para mejorar la experiencia de interacción en un videojuego. La investigación no pretende afirmar que los controles tradicionales deben desaparecer, sino demostrar que los gestos faciales pueden convertirse en una alternativa innovadora, especialmente para proyectos educativos, demostraciones tecnológicas y experiencias interactivas.

## 1.3 Justificación del Estudio

La presente investigación se justifica porque permite estudiar una forma moderna de interacción entre las personas y los videojuegos. En lugar de usar únicamente controles físicos, el sistema propone utilizar gestos faciales detectados por una cámara web. Esta idea resulta importante porque acerca la tecnología a una forma más natural de comunicación humana.

### Justificación teórica

Desde el punto de vista teórico, el estudio aporta al entendimiento de la relación entre inteligencia artificial, visión por computadora e interacción humano-computadora. La investigación permite explicar cómo un sistema puede detectar el rostro, interpretar expresiones y convertirlas en acciones dentro de un entorno digital. Esto se relaciona con los estudios sobre reconocimiento facial, computación afectiva y diseño de interfaces inteligentes.

Además, el proyecto permite comprender que la innovación en videojuegos no depende solamente de gráficos avanzados o historias complejas, sino también de la manera en que el jugador interactúa con el sistema. Un videojuego puede ser innovador cuando ofrece una experiencia diferente, como controlar un personaje mediante gestos del rostro. De esta forma, el estudio contribuye a explicar cómo la tecnología puede ampliar las posibilidades de participación del usuario.

### Justificación práctica

Desde el punto de vista práctico, el proyecto MoodVision AI / PlayFace sirve como un prototipo funcional que demuestra la aplicación real de los conceptos investigados. El sistema permite activar la cámara, reconocer emociones, mostrar información en pantalla, guardar datos en un backend y utilizar gestos faciales dentro de un juego. Esto convierte la investigación en una propuesta aplicada, no solamente teórica.

Para un estudiante de tercero de bachillerato técnico informático, esta investigación es útil porque integra conocimientos aprendidos durante la formación académica. El proyecto combina programación web, manejo de datos, consumo de APIs, diseño de interfaz, inteligencia artificial y lógica de videojuegos. Por lo tanto, permite demostrar competencias técnicas de una manera visual y comprensible.

También tiene valor educativo porque puede motivar a otros estudiantes a explorar nuevas formas de interacción digital. Al observar que una cámara puede reconocer gestos y convertirlos en acciones dentro de un videojuego, se evidencia que la informática puede crear soluciones creativas, accesibles e innovadoras.

Finalmente, el estudio es importante porque promueve una reflexión sobre el uso responsable de tecnologías que trabajan con imágenes del rostro. Esto permite incluir en la investigación aspectos como privacidad, consentimiento y seguridad, los cuales son necesarios cuando se desarrollan sistemas que interactúan con datos personales.

## 1.4 Objetivos del Estudio

Los objetivos de la investigación permiten orientar el desarrollo del trabajo y mantener el enfoque en el tema principal. En este caso, todos los objetivos se relacionan con el diseño de un sistema de reconocimiento de gestos faciales y su relación con la innovación en videojuegos interactivos.

## 1.4.1 Objetivo General

Diseñar un sistema de reconocimiento de gestos faciales que permita analizar expresiones del usuario mediante una cámara web y relacionar dicha información con nuevas formas de interacción en videojuegos interactivos.

Este objetivo busca demostrar cómo los gestos del rostro pueden convertirse en comandos digitales dentro de un prototipo funcional, utilizando tecnologías web e inteligencia artificial.

Además, pretende explicar de qué manera esta propuesta representa una innovación frente a los métodos tradicionales de control en videojuegos.

Finalmente, el objetivo general permite integrar conocimientos técnicos de programación, diseño de interfaces, backend, base de datos y visión por computadora.

## 1.4.2 Objetivos Específicos

1. Identificar las características principales del reconocimiento de gestos faciales y su aplicación dentro de un sistema interactivo basado en cámara web.

2. Describir cómo el prototipo MoodVision AI / PlayFace utiliza inteligencia artificial, frontend, backend y base de datos para mejorar la interacción en un videojuego controlado por gestos faciales.

3. Analizar la relación entre el uso de gestos faciales y la innovación en la experiencia del usuario dentro de videojuegos interactivos.

4. Reconocer los beneficios, limitaciones y cuidados necesarios al utilizar tecnologías que procesan imágenes faciales en tiempo real.

## 1.5 Aspectos Metodológicos de la Investigación

Los aspectos metodológicos explican la forma en que se desarrolla la investigación. En este trabajo se toma como base un proyecto tecnológico aplicado, por lo que el estudio se orienta a describir, analizar y demostrar el funcionamiento de un sistema de reconocimiento de gestos faciales.

El trabajo no se limita a recopilar teoría, sino que también se apoya en un prototipo funcional. Esto permite observar cómo se comporta el sistema cuando el usuario activa la cámara, realiza gestos faciales y participa en una experiencia interactiva.

## 1.5.1 Tipo de Estudio

El tipo de estudio es **descriptivo y aplicado**.

Es descriptivo porque busca explicar las características del sistema, sus componentes, su funcionamiento y su relación con la interacción en videojuegos. La investigación describe cómo la aplicación detecta el rostro, interpreta gestos, muestra información visual y permite controlar acciones dentro de un juego.

Es aplicado porque se basa en el diseño y uso de un prototipo real. El proyecto MoodVision AI / PlayFace no se queda solamente en una idea, sino que presenta una aplicación funcional donde se integran cámara web, inteligencia artificial, dashboard, backend, base de datos y juego facial.

También puede considerarse una investigación tecnológica, ya que se orienta a resolver una necesidad práctica mediante el uso de herramientas informáticas.

## 1.5.2 Método de Investigación

El método de investigación utilizado es **analítico-descriptivo**.

Es analítico porque el proyecto se estudia por partes: primero se analiza la detección facial, luego la interpretación de emociones y gestos, después la comunicación con el backend y finalmente la aplicación de estos datos en un videojuego interactivo. Esta separación permite comprender mejor cómo funciona el sistema completo.

Es descriptivo porque se explica el comportamiento del prototipo tal como se observa durante su funcionamiento. Por ejemplo, se describe qué ocurre cuando el usuario activa la cámara, cómo se detecta el rostro, cómo se muestran los datos en pantalla y cómo los gestos pueden convertirse en acciones dentro del juego.

El método también incluye observación práctica, ya que el sistema puede probarse directamente para revisar si reconoce gestos, si muestra información correctamente y si la interacción resulta comprensible para el usuario.

## 1.5.3 Fuentes y Técnicas para la Recolección de Información

Para desarrollar esta investigación se pueden utilizar fuentes documentales, técnicas y prácticas.

### Fuentes documentales

Las fuentes documentales corresponden a libros, artículos, documentación técnica y referencias académicas relacionadas con inteligencia artificial, reconocimiento facial, computación afectiva, interacción humano-computadora y videojuegos interactivos.

Entre las fuentes principales se consideran investigaciones sobre emociones faciales, computación afectiva y visión por computadora. Estas fuentes ayudan a fundamentar el tema desde una perspectiva teórica.

### Fuentes técnicas

Las fuentes técnicas corresponden a la documentación de las herramientas utilizadas en el proyecto, como React, Vite, face-api.js, TensorFlow.js, Phaser, Node.js, Express y MySQL. Estas fuentes permiten comprender cómo se construye el sistema y qué función cumple cada tecnología.

También se considera como fuente técnica el README del proyecto MoodVision AI / PlayFace, donde se describe que la aplicación permite detectar emociones, usar la cámara, mostrar estadísticas, guardar datos y controlar un juego mediante gestos faciales.

### Técnicas de recolección

Las técnicas de recolección de información recomendadas son:

- **Observación directa:** probar la aplicación y observar cómo responde ante distintos gestos faciales.
- **Revisión documental:** estudiar fuentes académicas y documentación técnica relacionada con el tema.
- **Prueba funcional:** verificar si el sistema detecta rostro, emociones, puntos faciales y acciones del juego.
- **Registro de resultados:** anotar qué gestos funcionan correctamente, cuáles presentan dificultad y qué condiciones afectan la detección.
- **Análisis del prototipo:** revisar cómo se relacionan frontend, backend, base de datos e inteligencia artificial dentro del sistema.

Estas técnicas permiten obtener información suficiente para explicar el proyecto de manera clara y fundamentada durante la sustentación.

## Puntos Claves Para No Perder El Enfoque De La Tesis

Durante todo el documento se recomienda mantener presente que el tema central no es solamente la detección de emociones, sino la relación entre los gestos faciales y la innovación en videojuegos interactivos.

Los puntos más importantes son:

- El rostro puede convertirse en una forma de control digital.
- La cámara web permite capturar gestos sin usar dispositivos especiales.
- La inteligencia artificial ayuda a interpretar expresiones faciales.
- El videojuego se vuelve más interactivo cuando responde al rostro del usuario.
- La innovación está en cambiar la forma tradicional de jugar.
- El proyecto demuestra una aplicación real desde la especialización técnico informática.
- La privacidad debe considerarse porque el sistema utiliza cámara e imágenes.

## Glosario Básico

| Término | Explicación sencilla |
|---|---|
| Inteligencia artificial | Tecnología que permite a un sistema realizar tareas que normalmente requieren razonamiento o interpretación. |
| Visión por computadora | Área que permite a una computadora analizar imágenes o video. |
| Reconocimiento facial | Proceso mediante el cual un sistema detecta un rostro en una imagen o video. |
| Gestos faciales | Movimientos o expresiones del rostro, como sonreír, abrir la boca o mirar hacia un lado. |
| Videojuego interactivo | Juego donde el usuario participa activamente y sus acciones modifican lo que ocurre en pantalla. |
| Frontend | Parte visual de la aplicación que usa el usuario. |
| Backend | Parte interna que procesa y guarda información. |
| Base de datos | Sistema donde se almacena información para consultarla después. |

## Referencias

Ekman, P. (1992). An argument for basic emotions. *Cognition and Emotion, 6*(3-4), 169-200. https://doi.org/10.1080/02699939208411068

Google. (s. f.). *TensorFlow.js*. https://www.tensorflow.org/js

Justadudewhohacks. (s. f.). *face-api.js*. GitHub. https://github.com/justadudewhohacks/face-api.js

MDN Web Docs. (s. f.). *MediaDevices: getUserMedia() method*. https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia

Phaser. (s. f.). *Phaser: HTML5 game framework*. https://phaser.io/

Picard, R. W. (1997). *Affective computing*. MIT Press.

React. (s. f.). *React documentation*. https://react.dev/

Viola, P., & Jones, M. (2001). Rapid object detection using a boosted cascade of simple features. *Proceedings of the 2001 IEEE Computer Society Conference on Computer Vision and Pattern Recognition*, 1, I-511-I-518. https://doi.org/10.1109/CVPR.2001.990517
