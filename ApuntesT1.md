Lenguajes de programación

¿Qué diferencia existe entre los lenguajes declarativos y los imperativos?. Nombra al menos 2 de cada tipo.

Los lenguajes declarativos no requieren de que se les indique el proceso. En estos simplemente se declara el resultado deseado y este se obtiene por métodos internos.(Haskell y SQL)

En los lenguajes imperativos se requiere la especificación de los pasos a seguir para obtener un resultado. (Java y C#)


¿Explica qué es compilar? ¿Explica qué es interpretar?

	Compilar es el proceso de obtención de código objeto en que se realiza la interpretación de todo el código antes que la ejecución del mismo. 
	
	Interpretar es el proceso de ejecución de código por fragmentos que posteriormente son eliminados de la memoria.

Ventajas de los lenguajes compilados.
	
	Son lenguajes muy eficientes en ejecución pues no es necesario crear el código objeto antes de cada ejecución

Ventajas de los lenguajes interpretados.

	El código se interpreta directamente así que es más rápido realizar cambios al programa

Nombra 2 lenguajes compilados y otros 2 interpretados.

	Compilados: C++ y C
	Interpretados: CSS y JavaScript

¿Puede considerarse código objeto el bytecode generado en Java tras la compilación? Explica la respuesta.
	
	Si se puede considerar código objeto al ser producto de la compilación y objeto de la interpretación de un intérprete. Con la salvedad de que ese intérprete es específico para Java.





Pon un ejemplo de lenguaje de los siguientes tipos:

Bajo nivel. Lenguaje máquina
Nivel medio. Ensamblador
Alto nivel. Python

¿Qué paradigma de programación siguen los siguientes lenguajes?

C Imperativo
C++ Imperativo
SQL Declarativo
Java Imperativo
Javascript Multiparadigma
Lisp Multiparadigma
Prolog Imperativo
Puedes consultar el siguiente enlace:

https://es.wikipedia.org/wiki/Paradigma_de_programaci%C3%B3n

Explica qué criterios pueden seguirse a la hora de elegir un lenguaje de programación para el desarrollo software.
	
	Campo de aplicación, si se utiliza en tu área de trabajo
 	Experiencia previa, si has trabajado con lenguajes similares
Herramientas de desarrollo, , si tienes acceso a las herramientas necesarias para trabajar con él
Documentación disponible,  la cantidad de documentación y sitios de consulta disponibles
Base de usuarios, la cantidad de usuarios con los que poder trabajar o a los que realizar consultas
Reusabilidad, pues eso
Portabilidad, dependiendo del área es más o menos importante
Imposición del cliente, si pone la pasta y se encabezona, decide el lenguaje


Ciclo de vida del sofware

Define "Ciclo de vida del software".

	Número de modificaciones que soporta un software hasta que este se vuelve obsoleto y sus errores insolucionables

Nombra las fases principales del desarrollo de software y explica brevemente que se hace en cada una de ellas.
	
	Recopilación de datos
	Diseño de software
	Realización de pruebas
	Explotación del software

Explica brevemente en qué consiste el modelo en cascada cuando hablamos de desarrollo de software.

	Se desarrolla cada una de las siguientes fases en orden y sin comunicación de los procesos intermedios de cada fase. (Análisis, diseño, codificación, pruebas y mantenimiento)

 Ventajas e inconvenientes del modelo en cascada.
	
	Las principales ventajas son la predictibilidad de costes al poder llevar a cabo tu diseño original atendiendo a las necesidades expresadas por el mismo en la primera y única reunión.

	El inconveniente principal, por otro lado, es que el cliente no tiene conocimiento del avance del desarrollo del producto y probablemente se encuentre descontento con el resultado debido a la gran falta de comunicación entre el cliente y el conjunto de desarrolladores

 ¿Qué se entiende por verificación? ¿Y por validación?
	
	La verificación alude al cumplimiento de los requisitos, funcionales y no funcionales, que solicita el cliente, mientras que la verificación alude al cumplimiento de las expectativas del cliente sobre el producto. Respectivamente responden a las preguntas: ¿Estamos construyendo el producto correctamente? y ¿Estamos construyendo el producto correcto?

 Explica cómo funciona el modelo de desarrollo mediante creación de prototipos.
	
	Tras un primer análisis de los requisitos solicitados por el cliente se crea un prototipo, desechable o no, y se muestra al cliente para que este lo pruebe y decida sobre posibles modificaciones, que, tras ser comunicadas, pasan a ser analizadas de nuevo y se crea, en base a ellas, otro prototipo. Repitiendo este proceso cuantas veces sea necesario
	
    
 Qué cuatro principios rigen el desarrollo ágil expresados en el Manifiesto Ágil?

Individuos e interacciones sobre procesos y herramientas
Software funcionando sobre documentación extensiva 
Colaboración con el cliente sobre negociación contractual 
Respuesta ante el cambio sobre seguir un plan

 ¿Qué es una historia de usuario? Consulta el siguiente enlace:
        https://es.wikipedia.org/wiki/Historias_de_usuario

	Una historia de usuario es un item a conseguir en el desarrollo de un proyecto, dado por un usuario. Esta está expresada con un lenguaje común y, si bien por sí misma no tiene capacidad contractual, pero combinada con una conversación con el cliente si que es de obligado cumplimiento en la realización del proyecto

    
SCRUM. Explica como funciona Scrum. Consulta los siguientes enlaces:
        https://proyectosagiles.org/que-es-scrum/
        https://proyectosagiles.org/como-funciona-scrum/

	Scrum se basa en la realización de pequeñas partes del proyecto mediante procesos iterativos. Sus elementos fundamentales son el cliente(Product owner), el facilitador(Scrum master); que actúa como intermediario y el equipo de desarrollo(Team).

	En cuanto al desarrollo, las tareas se registran en una pizarra(task dashboard), representando esta los procesos necesarios para el cumplimiento de los requisitos del cliente para el producto(product backlog). En la pizarra las tareas se dividen en realizadas, por realizar y en proceso de realización. Sin embargo, solo aparecen en ella las pertinentes a cada fase del desarrollo.

	Las fases del desarrollo son los sprints, ciclos de 2 a 4 semanas en que se desarrolla un determinado apartado del proyecto y se le enseña al cliente en reuniones entre el facilitador y este. 

	Durante el desarrollo se dan constantes. En concreto se dan una al comienzo de cada sprint para planificarlo, otra al final del mismo para comprobar que se cumplen con las propiedades solicitadas, y finalmente, otra reunión diaria rutinaria para comprobar los posibles problemas de días presentes y anteriores, así como repasar el trabajo de días futuros.

	


SCRUM. Define los siguientes términos:

        Product backlog.

	Conjunto de requisitos del producto


        Sprint backlog.
	
	Conjunto de tareas a realizar del sprint para cumplir unos requisitos específicos del product backlog


SCRUM. En la terminología Scrum qué términos se utilizan como sinónimo de:

        Jefe de proyecto. Scrum master

        Cliente. Product owner

        Equipo de desarrollo. Team

SCRUM. Haz un resumen de los requisitos para poder utilizar Scrum. Consulta el siguiente enlace:
        https://proyectosagiles.org/requisitos-de-scrum/

	El principal requisito para la aplicación de dicha metodología es la comunicación y la capacidad de colaboración. Desde el equipo directivo, que debe intentar comunicar posibles problemas con antelación, hasta desde dentro de los miembros de diversos equipos que han de ser capaces de comunicarse entre sí para sacar adelante de forma colaborativa proyectos que cambian a menudo y en que la capacidad de adaptación es fundamental.
