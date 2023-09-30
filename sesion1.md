<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 1 
Qué es Git
Rendimiento Seguridad Flexibilidad Control de versiones con Git
Hoy en día, Git es, con diferencia, el sistema de control de versiones moderno más utilizado del mundo. Git es un proyecto de código abierto maduro y con un mantenimiento activo que desarrolló originalmente Linus Torvalds, el famoso creador del kernel del sistema operativo Linux, en 2005. Un asombroso número de proyectos de software dependen de Git para el control de versiones, incluidos proyectos comerciales y de código abierto. Los desarrolladores que han trabajado con Git cuentan con una buena representación en la base de talentos disponibles para el desarrollo de software, y este sistema funciona a la perfección en una amplia variedad de sistemas operativos e IDE (entornos de desarrollo integrados).

Git, que presenta una arquitectura distribuida, es un ejemplo de DVCS (sistema de control de versiones distribuido, por sus siglas en inglés). En lugar de tener un único espacio para todo el historial de versiones del software, como sucede de manera habitual en los sistemas de control de versiones antaño populares, como CVS o Subversion (también conocido como SVN), en Git, la copia de trabajo del código de cada desarrollador es también un repositorio que puede albergar el historial completo de todos los cambios.

Además de contar con una arquitectura distribuida, Git se ha diseñado teniendo en cuenta el rendimiento, la seguridad y la flexibilidad.

Por qué utilizar Git en tu organización
Git para desarrolladores Git para marketing Git para gestión de productos Git para diseñadores Git para atención al cliente Git para recursos humanos Git para gestores de presupuestos
Pasar de un sistema de control de versiones centralizado a Git cambia la forma en que tu equipo de desarrollo crea software. Y si tu empresa depende de su software para aplicaciones críticas, la modificación del flujo de trabajo de desarrollo afecta a toda la empresa.

Desarrollo de la organización
En este artículo, analizaremos cómo Git beneficia a cada aspecto de tu organización, desde tu equipo de desarrollo hasta tu equipo de marketing y todo lo demás. Al final de este artículo, debería quedar claro que Git no es solo para el desarrollo de software ágil, sino también para las empresas ágiles.

Git para desarrolladores
Flujo de trabajo de rama de función
Una de las mayores ventajas de Git son sus capacidades de ramificación. A diferencia de los sistemas de control de versiones centralizados, las ramas de Git son baratas y fáciles de fusionar. Esto facilita el flujo de trabajo de ramas de función tan popular entre muchos usuarios de Git.

Flujo de trabajo de rama de función
Las ramas de función proporcionan un entorno aislado para cada cambio en tu código base. Cuando un desarrollador quiere empezar a trabajar en algo, sin importar lo grande o pequeño sea, crea una nueva rama. Esto garantiza que la rama principal siempre contenga código de calidad para producción.

El uso de ramas de función no solo es más fiable que editar directamente el código de producción, sino que además proporciona ventajas organizativas. Te permite representar el trabajo de desarrollo con la misma granularidad que tu backlog ágil. Por ejemplo, puedes implementar una política en la que cada ticket de Jira se aborde en su propia rama de función.

Desarrollo distribuido
En SVN, cada desarrollador obtiene una copia de trabajo que apunta a un único repositorio central. No obstante, Git es un sistema de control de versiones distribuido. En lugar de una copia de trabajo, cada desarrollador obtiene su propio repositorio local con un historial completo de confirmaciones.

Desarrollo distribuido
Disponer de un historial local completo agiliza el funcionamiento de Git, ya que no necesitas una conexión de red para crear confirmaciones, inspeccionar versiones anteriores de un archivo o comparar diferencias entre confirmaciones.

El desarrollo distribuido también facilita el escalado de tu equipo de ingeniería. Si alguien provoca que la rama de producción en SVN deje de funcionar, otros desarrolladores no pueden añadir sus cambios hasta que la rama se corrija. Con Git, este tipo de bloqueo no existe. Todos pueden seguir con su actividad en sus propios repositorios locales.

Además, de manera similar a las ramas de función, el desarrollo distribuido crea un entorno más fiable. Incluso si un desarrollador borra su propio repositorio, puede clonar el de otra persona y empezar de nuevo.

Pull-requests
Muchas herramientas de gestión de código fuente, como Bitbucket, mejoran la funcionalidad básica de Git con solicitudes de incorporación de cambios. Una solicitud de incorporación de cambios es una forma de pedirle a otro desarrollador que fusione una de tus ramas en su repositorio. Esto no solo permite a los responsables del proyecto realizar un seguimiento de los cambios más fácilmente, sino que además permite a los desarrolladores iniciar debates sobre su trabajo antes de integrarlo con el resto del código base.

Solicitudes de incorporación de cambios
Dado que son esencialmente un hilo de comentarios adjunto a una rama de funciones, las solicitudes de incorporación de cambios son muy versátiles. Cuando un desarrollador se queda atascado con un problema complejo, puede iniciar una solicitud de incorporación de cambios para pedir ayuda al resto del equipo. Por otra parte, los desarrolladores júnior pueden estar seguros de que no están destruyendo todo el proyecto al tratar las solicitudes de incorporación de cambios como una revisión formal del código.

Comunidad
En muchos círculos, Git se ha convertido en el sistema de control de versiones esperado para nuevos proyectos. Si tu equipo usa Git, lo más probable es que no tengas que formar a los nuevos empleados sobre tu flujo de trabajo, porque ya estarán familiarizados con el desarrollo distribuido.

Comunidad de Git
Además, Git es muy popular entre los proyectos de código abierto. Esto significa que es fácil aprovechar las bibliotecas de terceros y animar a otros a bifurcar tu propio código fuente abierto.

Ciclo de publicación más rápido
El resultado final de las ramas de función, el desarrollo distribuido, las solicitudes de incorporación de cambios y una comunidad estable es un ciclo de publicación más rápido. Estas capacidades facilitan un flujo de trabajo ágil en el que se anima a los desarrolladores a compartir cambios más pequeños con mayor frecuencia. A su vez, los cambios pueden aplicarse a través de la canalización de implementación más rápido que con las publicaciones monolíticas comunes con los sistemas de control de versiones centralizados.

Ciclo de publicación más rápido
Como es de esperar, Git funciona muy bien con entornos de integración continua y entrega continua. Con los hooks de Git puedes ejecutar scripts cuando ocurren ciertos eventos dentro de un repositorio, lo que te permite automatizar la implementación a tu gusto. Incluso puedes compilar o implementar código de ramas específicas en distintos servidores.

Por ejemplo, es posible que quieras configurar Git para implementar la confirmación más reciente de la rama de desarrollo en un servidor de prueba cada vez que alguien fusione una solicitud de incorporación de cambios en él. La combinación de este tipo de automatización de compilación con la revisión por pares significa que puedes confiar al máximo en tu código a medida que pasa del entorno de desarrollo al entorno de ensayo y a la producción.

Git para marketing
Para entender cómo el cambio a Git afecta a las actividades de marketing de tu empresa, imagina que tu equipo de desarrollo tiene tres cambios distintos programados para llevarse a cabo en las próximas semanas:

El equipo está terminando una función innovadora en la que ha estado trabajando durante los últimos 6 meses.
Mary está implementando una función más pequeña que no está relacionada y solo afecta a los clientes existentes.
Rick está realizando algunas actualizaciones muy necesarias en la interfaz de usuario.
Si utilizas un flujo de trabajo de desarrollo tradicional que se basa en un VCS centralizado, es probable que todos estos cambios se acumulen en una sola publicación. El equipo de marketing solo puede hacer un anuncio que se centre principalmente en la función innovador y, de hecho, el potencial de marketing de las otras dos actualizaciones se ignora.

El ciclo de desarrollo más corto que facilita Git hace que sea mucho más fácil dividirlas en publicaciones individuales. Esto les da a los expertos en marketing más de qué hablar y con más frecuencia. En la situación anterior, el equipo de marketing puede crear tres campañas que giren en torno a cada función y, por lo tanto, dirigirse a segmentos de mercado muy específicos.

Git para marketing
Por ejemplo, podrían preparar un gran envío de solicitudes de incorporación de cambios para la función innovadora, una entrada de blog corporativo y un blurb de boletín informativo para la función de Mary, así como algunas entradas de invitado sobre la teoría de Rick en cuanto a la experiencia de usuario subyacente para enviarlas a blogs de diseño externos. Todas estas actividades se pueden sincronizar con una publicación independiente.

Git para gestión de productos
Las ventajas de Git para la gestión de productos son prácticamente las mismas que para el marketing. Las publicaciones más frecuentes se traducen en comentarios más frecuentes de los clientes y actualizaciones más rápidas en respuesta a esos comentarios. En lugar de esperar a la próxima publicación dentro de 8 semanas, puedes enviar una solución a los clientes tan pronto como sus desarrolladores puedan escribir el código.

Flujo de trabajo de Git para la gestión de prioridades
El flujo de trabajo de la rama de función también proporciona flexibilidad cuando cambian las prioridades. Por ejemplo, si estás a mitad de un ciclo de publicación y quieres posponer una función en lugar de otra en la que el tiempo es crítico, no hay problema. Esa función inicial puede permanecer en su propia rama hasta que el equipo de ingeniería tenga tiempo de volver a ella.

Esta misma funcionalidad facilita la gestión de proyectos de innovación, pruebas beta y prototipos rápidos como códigos base independientes.

Git para diseñadores
Las ramas de función se prestan a la creación rápida de prototipos. Tanto si tus diseñadores de experiencia o interfaz de usuario quieran implementar un flujo de usuario completamente nuevo como si simplemente quieren reemplazar algunos iconos, al extraer una nueva rama conseguirán un entorno de espacio aislado con el que experimentar. De este modo, los diseñadores podrán ver qué aspecto tendrán los cambios en una copia de trabajo real del producto sin temor a que la funcionalidad deje de funcionar.

Control de versiones no destructivo de Git
La encapsulación de cambios en la interfaz de usuario como esta facilita la presentación de actualizaciones a otras partes interesadas. Por ejemplo, si el director de ingeniería quiere ver en qué ha estado trabajando el equipo de diseño, tan solo tiene que decirle al director que extraiga la rama correspondiente.

Las solicitudes de incorporación de cambios llevan esto un paso más allá y proporcionan un lugar formal para que las partes interesadas debatan sobre la nueva interfaz. Los diseñadores pueden hacer los cambios necesarios, y las confirmaciones resultantes aparecerán en la solicitud de incorporación de cambios. Esto anima a todos a participar en el proceso de iteración.

Quizás la mejor parte de la creación de prototipos con ramas es que es tan fácil fusionar los cambios en la producción como desecharlos. No hay presión por hacer ninguna de las dos cosas. Esto anima a los diseñadores y desarrolladores de interfaces de usuario a experimentar y, al mismo tiempo, garantizar que solo las mejores ideas lleguen al cliente.

Git para atención al cliente
Los equipos de atención al cliente y éxito del cliente suelen tener una perspectiva distinta de las actualizaciones que los gestores de productos. Cuando un cliente los llama, por lo general tienen algún tipo de problema. Si ese problema está causado por el software de tu empresa, es necesario enviar una corrección del error lo antes posible.

El ciclo de desarrollo optimizado de Git evita posponer las correcciones de errores hasta la siguiente publicación monolítica. Un desarrollador puede solucionar el problema aplicando un parche directamente en producción. Las correcciones más rápidas equivalen a clientes más satisfechos y menos tickets de asistencia repetidos. En lugar de quedarse atascado con un "Lo siento, nos ocuparemos de esto", el equipo de atención al cliente puede comenzar respondiendo con "¡Ya lo hemos arreglado!".

Git para recursos humanos
Hasta cierto punto, tu flujo de trabajo de desarrollo de software determina a quién contratas. Siempre ayuda contratar a ingenieros que estén familiarizados con tus tecnologías y flujos de trabajo, pero el uso de Git también proporciona otras ventajas.

Los empleados se sienten atraídos por las empresas que ofrecen oportunidades de crecimiento profesional, y entender cómo aprovechar Git tanto en organizaciones grandes como en pequeñas es una bendición para cualquier programador. Al elegir Git como tu sistema de control de versiones, estás tomando la decisión de atraer a desarrolladores con visión de futuro.

Git para gestores de presupuestos
Git se basa en la eficiencia. Para los desarrolladores, lo elimina todo, desde el tiempo perdido pasando confirmaciones a través de una conexión de red hasta las horas de trabajo necesarias para integrar los cambios en un sistema de control de versiones centralizado. Incluso hace un mejor uso de los desarrolladores júnior al brindarles un entorno seguro para trabajar. Todo esto afecta a los resultados de tu departamento de ingeniería.

Equipo distribuido de Git
Sin embargo, no olvides que estas eficiencias también se extienden fuera de tu equipo de desarrollo. Evitan que el equipo de marketing invierta energía en material publicitario para funciones que no son populares. Permiten a los diseñadores probar nuevas interfaces en el producto real con pocos gastos. Te permiten reaccionar a las quejas de los clientes de inmediato.

Ser ágil consiste en descubrir qué funciona lo más rápido posible, incrementar las labores que tienen éxito y eliminar las que no lo tienen. Git sirve como multiplicador de todas tus actividades empresariales y garantiza que cada departamento haga su trabajo con más eficiencia.

Algunas de las principales características de Git son:

Distribuido: Git es un sistema de control de versiones distribuido, lo que significa que cada desarrollador tiene una copia completa del repositorio en su máquina local. Esto permite a los desarrolladores trabajar de forma aislada en su propio entorno y fusionar los cambios de manera controlada.
Rápido y eficiente: Git está diseñado para manejar proyectos grandes y complejos de manera eficiente. Utiliza algoritmos de compresión y almacenamiento eficientes para minimizar el tamaño del repositorio y la velocidad de ejecución de las operaciones.
Gestión de ramas avanzada: Git permite crear y gestionar ramas fácilmente, lo que facilita el trabajo en paralelo y el desarrollo de nuevas funcionalidades sin afectar la rama principal del proyecto.
Integridad de los datos: Git utiliza un sistema de hash criptográfico para garantizar la integridad de los datos almacenados en el repositorio. Esto significa que cualquier cambio en el código fuente o en el historial de confirmaciones se detecta y se puede verificar.
Herramientas para la resolución de conflictos: Git proporciona herramientas para manejar y resolver conflictos cuando dos o más ramas tienen cambios conflictivos en el mismo archivo. Esto permite a los desarrolladores fusionar los cambios de manera controlada y resolver cualquier conflicto manualmente si es necesario.

¿Qué es Github y para qué sirve?
GitHub es una plataforma de desarrollo colaborativo que aloja proyectos en la nube utilizando el sistema de control de versiones llamado Git. Ayuda a los desarrolladores a almacenar y administrar el código llevando un registro de cambios. Generalmente el código es abierto, lo que permite realizar proyectos compartidos y mantener el seguimiento detallado de su progreso. La plataforma GitHub también funciona como red social conectando a los desarrolladores con los usuarios. Como usuario puedes descargar programas o aplicaciones, y de la misma manera puedes aportar a su desarrollo ofreciendo mejoras y discutir las cuestiones que te interesan en foros temáticos.


Fuente: Unsplash

¿Qué es el control de versiones?
El sistema de control de versiones (VCS) ayuda a rastrear modificaciones realizadas en el código fuente a medida que se desarrolla un proyecto, permite comparar y analizar cambios con la posibilidad de revertirlos si algo va mal. Gracias al acceso a versiones anteriores, el sistema minimiza riesgos de cometer errores y da la libertad de desarrollar proyectos sin preocupaciones.

¿Qué es Git?
Git es un software de control de versiones diseñado por Linus Torvalds, el creador de Linux. El propósito de Git es llevar un registro de cambios y coordinar el trabajo de varias personas en un repositorio compartido. Desde su creación en 2005, este software llegó a convertirse en uno de los VCS más populares: según la encuesta de Stack Overflow (en inglés), más del 90% de los desarrolladores usan Git en sus proyectos.

Git proporciona herramientas para un trabajo rápido y eficiente dentro de un equipo. El control de versiones permite a los desarrolladores descargar una copia del código fuente a sus repositorios locales (PC), realizar cambios y subir una versión nueva al repositorio compartido. Todas las modificaciones se guardan en versiones independientes, sin afectar el archivo original. Se pueden comparar cambios realizados, ver quién modificó el código y determinar en qué momento se introdujo un error para poder revertirlo. De esta forma todos los desarrolladores interesados en el proyecto tienen acceso al historial de modificaciones realizadas y pueden contribuir mejorando el código del software.

¿Cómo empezar con GitHub?
Para empezar a usar GitHub, tienes que registrarte. La plataforma te ofrece un plan básico gratuito con 500 MB de almacenamiento, acceso ilimitado a repositorios públicos y privados, y te permite colaborar con un máximo de tres usuarios. Si buscas una opción más avanzada, puedes escoger una suscripción GitHub Pro que te ofrece acceso ilimitado a todos los repositorios digitales, colaboradores ilimitados, estadísticas, wikis y más.

Cómo empezar con GitHub
Fuente: Freepik

Una vez tengas tu cuenta, inicia sesión con el nombre de usuario y la contraseña. Para empezar un proyecto, sigue estos pasos:

Crea un repositorio de GitHub
El repositorio es una ubicación donde se almacena toda la información de un proyecto. Puede contener uno o varios archivos de código, imágenes, texto, etc. Para crear uno, haz clic en el menú desplegable con el símbolo + en la parte superior derecha de la página y escoge New repository. Ahora tienes que rellenar los datos necesarios:

Asigna el nombre corto y claro a tu repositorio.
Escribe una breve descripción.
Selecciona el acceso público (para código abierto) o privado.
Agrega un archivo README con comentarios sobre tu proyecto.
Haz clic en Create repository para confirmar la creación de tu repositorio.
Crea una nueva rama (branch)
La ramificación te permite generar diferentes versiones de un proyecto sin afectar el código inicial. El repositorio tiene una rama principal llamada Main a partir de la cual puedes crear tus propias ramas adicionales creando una copia del proyecto para agregar nuevas características, hacer pruebas sin miedo a equivocarte y arruinar el trabajo realizado. Los cambios introducidos en las ramas se reflejarán en la rama principal solo después de confirmar y fusionarlos. Para generar una nueva rama:

Entra en tu repositorio y haz clic en la pestaña Code.
Pulsa el botón Main con una lista desplegable de archivos.
Introduce el nombre de tu nueva rama de características.
Haz clic en Create branch. Ahora puedes hacer cambios en la nueva rama.
Haz un commit para guardar cambios
En GitHub, las modificaciones se llevan a cabo mediante confirmaciones o commits. Para mantener los cambios hechos en una rama y guardarlos en tu repositorio, realiza los siguientes pasos:

Selecciona tu rama recién creada en el menú desplegable Main.
Escoge el archivo que quieres cambiar.
Haz clic en el icono del lápiz para editar.
Agrega una breve descripción de los cambios realizados.
Presiona el botón Commit changes para subir la nueva versión al repositorio.
Crea una solicitud de extracción (pull request)
Si quieres introducir al proyecto los cambios que acabas de hacer o proponer mejoras a otros desarrolladores, debes crear un pull request o una solicitud de extracción.

La solicitud de extracción es una herramienta esencial de colaboración en GitHub que te permite proponer cambios y requerir que alguien revise e integre tu contribución en su código o haga sugerencias. La solicitud de extracción muestra diferencias entre las ramas y refleja cambios, adiciones y sustracciones del contenido en varios colores. Si otros desarrolladores aprueban tu solicitud, pueden fusionar esos cambios con el proyecto principal.

Para aprender el flujo de GitHub antes de trabajar en proyectos con más colaboradores, puedes crear un pull request en tu propio repositorio, siguiendo estos pasos:

Abre la pestaña Pull requests en tu repositorio.
Haz clic en New pull request.
En el cuadro Compare changes, selecciona la rama que has creado para compararla con la rama Main.
Asegúrate de revisar tus cambios antes de enviar y haz clic en Create pull request.
En la nueva página, escribe el título de tu solicitud y agrega una breve descripción de los cambios que ofreces.
Confirma el envío presionando Create pull request.

Fuente: Unsplash

Fusiona los cambios
Después de revisar y aprobar la solicitud, el paso final será incorporar los cambios a la rama principal. Sigue estos pasos para fusionar tus cambios con el proyecto:

Haz clic en Merge pull request para incorporar los cambios en la rama Main.
Pulsa Confirm merge para confirmar la acción. Recibirás un mensaje avisando que los cambios se fusionaron con éxito.
Ahora que los cambios están incorporados en el código principal, puedes eliminar la rama con seguridad presionando Delete branch.
Si en algún momento quieres hacer más cambios en tu proyecto, siempre puedes crear una rama nueva y repetir el proceso.

Conclusión
Github es una plataforma de control de versiones gratuita que sirve para gestionar proyectos y permite colaborar con una gran comunidad de desarrolladores, aportando mejoras y comentarios. Puede ser útil no solo para manejar proyectos de desarrollo de software, sino también para organizar trabajo en equipo en diferentes industrias.

Si quieres aprender a sacar el máximo partido a Github y tener una carrera exitosa en el sector IT, inscríbete al curso online de Analista de Datos. Aprenderás los principios de programación para generar estadísticas, analizar y manejar datos, visualizar resultados y mucho más. Estudia y haz actividades prácticas a tu ritmo, con el feedback personalizado de un tutor. Al finalizar el curso, enriquece tu portafolio con un proyecto real y el certificado oficial de EBAC.

¿Qué es Python?
Python es un lenguaje de programación ampliamente utilizado en las aplicaciones web, el desarrollo de software, la ciencia de datos y el machine learning (ML). Los desarrolladores utilizan Python porque es eficiente y fácil de aprender, además de que se puede ejecutar en muchas plataformas diferentes. El software Python se puede descargar gratis, se integra bien a todos los tipos de sistemas y aumenta la velocidad del desarrollo.

¿Qué beneficios ofrece Python?
Los beneficios de Python incluyen los siguientes:

Los desarrolladores pueden leer y comprender fácilmente los programas de Python debido a su sintaxis básica similar a la del inglés. 
Python permite que los desarrolladores sean más productivos, ya que pueden escribir un programa de Python con menos líneas de código en comparación con muchos otros lenguajes.
Python cuenta con una gran biblioteca estándar que contiene códigos reutilizables para casi cualquier tarea. De esta manera, los desarrolladores no tienen que escribir el código desde cero.
Los desarrolladores pueden utilizar Python fácilmente con otros lenguajes de programación conocidos, como Java, C y C++.
La comunidad activa de Python incluye millones de desarrolladores alrededor del mundo que prestan su apoyo. Si se presenta un problema, puede obtener soporte rápido de la comunidad.
Hay muchos recursos útiles disponibles en Internet si desea aprender Python. Por ejemplo, puede encontrar con facilidad videos, tutoriales, documentación y guías para desarrolladores.
Python se puede trasladar a través de diferentes sistemas operativos de computadora, como Windows, macOS, Linux y Unix.
¿Cómo se utiliza Python?
El lenguaje Python se aplica a varios casos de uso en el desarrollo de aplicaciones, incluidos los ejemplos siguientes:

Desarrollo web del lado del servidor
El desarrollo web del lado del servidor incluye las funciones complejas de backend que los sitios web llevan a cabo para mostrar información al usuario. Por ejemplo, los sitios web deben interactuar con las bases de datos, comunicarse con otros sitios web y proteger los datos cuando se los envía a través de la red. 

Python es útil para escribir código del lado del servidor debido a que ofrece muchas bibliotecas que constan de código preescrito para crear funciones de backend complejas. Los desarrolladores también utilizan un amplio rango de marcos de Python que proporcionan todas las herramientas necesarias para crear aplicaciones web con mayor rapidez y facilidad. Por ejemplo, los desarrolladores pueden crear la aplicación web esqueleto en segundos porque no deben escribirla desde cero. Pueden probarla por medio de las herramientas de prueba del marco, sin depender de herramientas de prueba externas.

Automatización con scripts de Python
Un lenguaje de scripting es un lenguaje de programación que automatiza las tareas que suelen llevar a cabo las personas. Los programadores utilizan ampliamente los scripts de Python para automatizar muchas tareas diarias, como las siguientes:

Cambiar el nombre de una gran cantidad de archivos a la vez
Convertir un archivo en otro tipo de archivo
Eliminar palabras duplicadas de un archivo de texto
Llevar a cabo operaciones matemáticas básicas
Enviar mensajes por email
Descargar contenido
Efectuar análisis básicos de registros
Encontrar errores en varios archivos
Realizar tareas de ciencia de datos y machine learning
La consiste en extraer conocimientos valiosos a partir de los datos, mientras que el enseña a las computadoras a aprender automáticamente de los datos y a efectuar predicciones precisas. Los científicos de datos utilizan Python para realizar tareas de ciencia de datos, como las que se indican a continuación:

Corregir y eliminar datos incorrectos, lo que se conoce como limpieza de datos 
Extraer y seleccionar varias características de los datos
, que consiste en agregar nombres significativos a los datos
Buscar diferentes estadísticas a partir de los datos
Visualizar los datos mediante el uso de tablas y gráficos, como los gráficos de líneas, los de barras, los circulares y los histogramas
 
Los científicos de datos utilizan las bibliotecas de ML de Python para entrenar los modelos de ML y crear clasificadores que clasifiquen los datos con precisión. Las personas que trabajan en diferentes campos utilizan clasificadores basados en Python para efectuar tareas de clasificación, como la clasificación de imágenes, texto y tráfico de red; el reconocimiento de habla; y el reconocimiento facial. Los científicos de datos también utilizan Python para las tareas de aprendizaje profundo, una técnica avanzada de ML.
Desarrollo de software
Los desarrolladores de software suelen utilizar Python para realizar distintas tareas de desarrollo y aplicaciones de software, como las que se indican a continuación:

Realizar un seguimiento de los errores en el código del software
Crear el software de forma automática
Administrar los proyectos de software
Desarrollar prototipos de software
Desarrollar aplicaciones de escritorio por medio de las bibliotecas de interfaz gráfica de usuario (GUI)
Desarrollar juegos simples basados en texto a videojuegos más complejos
Automatización de pruebas de software
La prueba de software es el proceso de verificar si los resultados reales del software coinciden con los resultados esperados, para garantizar que el software esté libre de errores. 

Los desarrolladores utilizan marcos de prueba de unidad de Python, como Unittest, Robot y PyUnit, para probar las funciones que escriben. 
Los encargados de probar el software utilizan Python para escribir casos de prueba para diversos escenarios de prueba. Por ejemplo, lo utilizan para probar la interfaz de usuario de una aplicación web, los diversos componentes de software y las nuevas características. 
Los desarrolladores pueden utilizar varias herramientas para ejecutar scripts de prueba de manera automática. Estas herramientas se conocen como herramientas de integración e implementación continuas (CI/CD). Los encargados de probar el software y sus desarrolladores utilizan las herramientas de CI/CD, como Travis CI y Jenkins, para automatizar las pruebas. La herramienta de CI/CD ejecuta automáticamente los scripts de prueba de Python e informa los resultados de las pruebas cada vez que los desarrolladores presentan nuevos cambios de código.

¿Cuál es la historia de Python?
Guido Van Rossum, un programador de computación de los Países Bajos, creó Python. Python comenzó en 1989 en el Centrum Wiskunde & Informatica (CWI), en principio como un proyecto de afición para mantenerse ocupado durante las vacaciones de Navidad. El nombre del lenguaje se inspiró en el programa de televisión de la BBC “Monty Python’s Flying Circus” debido a que Guido Van Rossum era un gran aficionado del programa. 

Historial de lanzamientos de Python
Guido Van Rossum publicó la primera versión del código Python (versión 0.9.0) en 1991. Dicha versión ya incluía buenas características, como algunos tipos de datos y funciones para la gestión de errores. 
Python 1.0 se lanzó en 1994 con nuevas funciones para procesar fácilmente una lista de datos, como la asignación, el filtrado y la reducción.
Python 2.0 se lanzó el 16 de octubre de 2000, con nuevas características útiles para los programadores, como la compatibilidad con los caracteres Unicode y una forma más corta de recorrer una lista.
El 3 de diciembre de 2008, se lanzó Python 3.0. Incluía características como la función de impresión y más soporte para la división de números y la gestión de errores. 
¿Cuáles son las características de Python?
Las características siguientes del lenguaje de programación Python lo hacen único:

Un lenguaje interpretado
Python es un lenguaje interpretado, lo que significa que ejecuta directamente el código línea por línea. Si existen errores en el código del programa, su ejecución se detiene. Así, los programadores pueden encontrar errores en el código con rapidez.

Un lenguaje fácil de utilizar
Python utiliza palabras similares a las del inglés. A diferencia de otros lenguajes de programación, Python no utiliza llaves. En su lugar, utiliza sangría. 

Un lenguaje tipeado dinámicamente
Los programadores no tienen que anunciar tipos de variables cuando escriben código porque Python los determina en el tiempo de ejecución. Debido a esto, es posible escribir programas de Python con mayor rapidez.

Un lenguaje de alto nivel
Python es más cercano a los idiomas humanos que otros lenguajes de programación. Por lo tanto, los programadores no deben preocuparse sobre sus funcionalidades subyacentes, como la arquitectura y la administración de la memoria.

Un lenguaje orientado a los objetos
Python considera todo como un objeto, pero también admite otros tipos de programación, como la programación estructurada y la funcional.

¿Qué son las bibliotecas de Python?
Una biblioteca es una colección de códigos usados con frecuencia que los desarrolladores pueden incluir en sus programas de Python para evitar tener que escribir el código desde cero. De forma predeterminada, Python incluye la biblioteca estándar, que contiene una gran cantidad de funciones reutilizables. Además, más de 137 000 bibliotecas de Python están disponibles para diversas aplicaciones, incluidos el desarrollo web, la ciencia de datos y el machine learning (ML).

¿Cuáles son las bibliotecas de Python más populares?
Matplotlib
Los desarrolladores utilizan Matplotlib para trazar los datos en gráficos de dos y tres dimensiones (2D y 3D) de alta calidad. Por lo general, se utiliza en las aplicaciones científicas. Con Matplotlib, puede visualizar los datos mostrándolos en diferentes gráficos, como los gráficos de barras y los de líneas. También puede trazar varios gráficos de una sola vez, y estos se pueden trasladar a todas las plataformas.

Pandas
Pandas proporciona estructuras de datos optimizadas y flexibles que se pueden utilizar para manipular datos de serie temporal y datos estructurados, como las tablas y las matrices. Por ejemplo, puede utilizar Pandas para leer, escribir, combinar, filtrar y agrupar datos. Muchas personas lo utilizan para las tareas de ciencia de datos, análisis de datos y ML.

NumPy
NumPy es una conocida biblioteca que utilizan los desarrolladores para crear y administrar matrices, manipular formas lógicas y efectuar operaciones de álgebra lineal con facilidad. NumPy admite la integración a muchos lenguajes, como C y C++.

Requests
La biblioteca Requests proporciona funciones útiles que se necesitan para el desarrollo web. Puede usarla para enviar solicitudes HTTP; agregar encabezados, parámetros de URL y datos; y llevar a cabo muchas más tareas cuando se comunica con aplicaciones web. 

OpenCV-Python
OpenCV-Python es una biblioteca que los desarrolladores utilizan para procesar imágenes para las aplicaciones de visión artificial. Proporciona muchas funciones para las tareas de procesamiento de imágenes, como la lectura y la escritura simultáneas de imágenes, la creación de un entorno 3D a partir de uno 2D y la captura y el análisis de las imágenes de video.

Keras
Keras es la biblioteca de red neuronal profunda de Python que cuenta con un excelente soporte para el procesamiento de datos, su visualización y mucho más. Keras admite muchas redes neuronales. Posee una estructura modular que ofrece flexibilidad en la escritura de aplicaciones innovadoras.

¿Qué son los marcos de Python?
Un marco de Python es una colección de paquetes y módulos. Un módulo es un conjunto de código relacionado, y un paquete es un conjunto de módulos. Los desarrolladores pueden usar los marcos de Python para crear aplicaciones de Python más rápido debido a que no tienen que preocuparse por los detalles de nivel inferior, como la forma en que se producen las comunicaciones en la aplicación web o el modo en que Python hará que el programa sea más rápido. Python tiene dos tipos de marcos: 

El marco de pila completa incluye casi todo lo que se necesita para crear una aplicación grande.
El micromarco es un marco básico que proporciona funcionalidades mínimas para crear aplicaciones de Python simples. También proporciona extensiones si las aplicaciones necesitan funciones más sofisticadas.
¿Cuáles son los marcos de Python más conocidos?
Los desarrolladores pueden utilizar varios marcos de Python para que su desarrollo sea eficiente, incluidos los siguientes:

Django
Django es uno de los marcos web de Python de pila completa más utilizados para el desarrollo de aplicaciones web a gran escala. Proporciona varias características útiles, incluidos un servidor web para el desarrollo y las pruebas, un motor de plantillas para crear el sitio web de frontend y diversos mecanismos de seguridad.

Flask
Flask es un micromarco que se utiliza para el desarrollo de aplicaciones web pequeñas. Sus características incluyen un importante soporte de la comunidad, documentación bien escrita, un motor de plantillas, pruebas de unidad y un servidor web integrado. También proporciona extensiones para el soporte de validación, las capas de asignación de bases de datos y la seguridad web.

TurboGears
TurboGears es un marco diseñado para crear aplicaciones web con mayor rapidez y facilidad. Estas son algunas de sus características clave: 

Estructura específica de tabla de base de datos
Herramientas para la creación y la administración de proyectos
Motor de plantillas para crear las bases de datos
Motor de plantillas para crear el frontend
Mecanismos para manejar la seguridad web
Apache MXNet
Apache MXNet es un marco de aprendizaje profundo rápido, flexible y escalable que los desarrolladores utilizan para crear prototipos de investigación y aplicaciones de aprendizaje profundo. Admite múltiples lenguajes de programación, incluidos Java, C++, R y Perl. Proporciona un completo conjunto de herramientas y bibliotecas para brindar soporte al desarrollo. Por ejemplo, puede encontrar un libro interactivo de machine learning (ML), kits de herramientas de visión artificial y modelos de aprendizaje profundo para el procesamiento de lenguaje natural (NLP), que procesan este lenguaje, como el texto y el habla.

PyTorch
PyTorch es un marco para el machine learning que se ha creado sobre la biblioteca Torch, que es otra biblioteca de machine learning de código abierto.  Los desarrolladores lo utilizan para aplicaciones como las de NLP, robótica y visión artificial, para encontrar información significativa en las imágenes y los videos. También lo utilizan para ejecutar esas aplicaciones en las CPU y las GPU.

¿Qué son los IDE de Python?
Un entorno de desarrollo integrado (IDE) es un software que brinda a los desarrolladores las herramientas que necesitan para escribir, editar, probar y corregir código en un único lugar. 

¿Cuáles son los IDE de Python más conocidos?
PyCharm
JetBrains, una empresa checa que desarrolla herramientas de software, creó PyCharm. Cuenta con una edición comunitaria gratuita que es adecuada para pequeñas aplicaciones de Python, así como con una edición profesional de pago que es adecuada para crear aplicaciones de Python a gran escala, con el siguiente conjunto completo de características:

Compleción automática e inspección del código
Gestión de errores y correcciones rápidas
Limpieza del código sin necesidad de cambios de funcionalidad
Compatibilidad con los marcos de aplicaciones web, como Django y Flask
Compatibilidad con otros lenguajes de programación, como JavaScript, CoffeeScript, TypeScript, AngularJS y Node
Herramientas y bibliotecas científicas, como Matplotlib and NumPy
posibilidad de ejecutar, depurar, probar e implementar aplicaciones en máquinas virtuales remotas
un depurador para encontrar errores en el código, un creador de perfiles para identificar problemas de rendimiento en el código y un ejecutor de pruebas para llevar a cabo pruebas de unidad
Soporte para bases de datos
IDLE
El entorno integrado de desarrollo y aprendizaje (IDLE) es el entorno de desarrollo integrado (IDE) de Python instalado de forma predeterminada. Se ha desarrollado solo con Python por medio del kit de herramientas de GUI de Tkinter y ofrece las siguientes características:
 
Funcionamiento en muchos sistemas operativos, como Windows, Unix y macOS
Ventana de shell para ejecutar comandos y mostrar el resultado
un editor de textos de varias ventanas que proporciona resaltado de la sintaxis del código y compleción automática del código
posesión de su propio depurador 
Spyder
Spyder es un entorno de desarrollo integrado (IDE) de código abierto que utilizan numerosos científicos y analistas de datos. Proporciona una experiencia integral de desarrollo con características para el análisis avanzado de datos, su visualización y depuración. También incluye las siguientes características:

Editor completo de código que admite varios lenguajes
Consola interactiva de IPython
Depurador básico
Bibliotecas científicas, como Matplotlib, SciPy y NumPy
Posibilidad de explorar variables en el código
Posibilidad de visualizar documentación en tiempo real
Atom
Atom es un editor gratuito desarrollado por GitHub que admite la codificación en varios lenguajes de programación, incluido Python. Mediante el uso de Atom, los desarrolladores pueden trabajar directamente con GitHub, el sitio web en el que puede guardar su código de forma centralizada. Atom ofrece las siguientes características:

Posibilidad de utilizarlo con muchos sistemas operativos 
Instalación o creación fáciles de nuevos paquetes
Compleción automática de código más rápida
Posibilidad de buscar archivos y proyectos
Fácil personalización de la interfaz
¿Qué son los SDK de Python?
Un kit de desarrollo de software (SDK) es una colección de herramientas de software que los desarrolladores pueden utilizar para crear aplicaciones de software en un lenguaje particular. La mayoría de los SDK son específicos de diferentes plataformas de hardware y sistemas operativos. Los SDK de Python incluyen muchas herramientas, como bibliotecas, muestras de código y guías para desarrolladores, que estos encuentran útiles a la hora de escribir aplicaciones.

¿Qué es AWS PyCharm?
AWS Toolkit for PyCharm es el complemento para el entorno de desarrollo integrado (IDE) de PyCharm que facilita la creación, depuración e implementación de aplicaciones de Python en AWS. Mediante el uso del AWS Toolkit for PyCharm, los desarrolladores pueden comenzar fácilmente con el desarrollo de Python. Proporciona varias características útiles para los desarrolladores, incluidas guías de inicio, depuraciones paso a paso e implementaciones de IDE.

¿Qué es Boto3 en Python?
Boto3 es el AWS SDK para Python. Se puede utilizar para crear, configurar y administrar servicios de AWS, como , y . Boto3 también proporciona dos tipos de : las API de nivel inferior y las API de recursos para desarrolladores.

<!-- Su documentación aquí -->






