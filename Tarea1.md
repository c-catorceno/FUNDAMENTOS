# TAREA 1: Definiciones Git y Metodologías
## Git push
Comando que lleva y actualiza los cambios confirmados hacia el repositorio remoto.

git push actualiza el repositorio remoto con las confirmaciones realizadas localmente en una rama. (GitHub Docs)

## Git pull
Comando que sirve para llevar los cambios que se hayan realizado en el repositorio remoto hacia el respositorio local.

git pull actualiza la línea de desarrollo local con actualizaciones de sus contrapartes remotas. Los desarrolladores utilizan este comando si un compañero de equipo hizo confirmaciones en una rama en un repositorio remoto y quieren reflejarlos en su ambiente local. (GitHub Docs)

## Git branch
Es un comando que nos muestra una lista con todas las ramas creadas.

git branch muestra las ramas en las que se trabaja localmente. (Github Docs)

## Git checkout
Comando que permite el cambio o desplazamiento a la rama específicada.

En términos de Git, "checkout" (extraer) es el acto de cambiar entre diferentes versiones de una entidad objetivo. El comando git checkout opera sobre tres entidades distintas: archivos, confirmaciones y ramas. En el tema sobre cómo deshacer cambios, explicamos cómo puede usarse git checkout para ver confirmaciones antiguas. (Atlassian)

## Git fork
Sirve para crear o copiar un respositorio ya existente como uno nuevo en tu cuenta.

Una bifurcación es un nuevo repositorio que comparte la configuración de visibilidad y código con el repositorio “acendente” original. Las bifurcaciones se utilizan a menudo para iterar ideas o cambios antes de que se propongan de nuevo al repositorio ascendente, como en proyectos de código abierto o cuando un usuario no tiene acceso de escritura al repositorio ascendente. (Github docs)
### Git merge
Este comando mezcla los cambios de una rama dentro de otra, para esto se debe estar en la rama donde se desean fusionar los cambios.

El comando git merge permite tomar las líneas independientes de desarrollo creadas por git branch e integrarlas en una sola rama. Ten en cuenta que todos los comandos presentados a continuación se fusionan en la rama actual.  (Atlassian).

## QA
Es la persona encargada de evaluar la calidad del producto, así detectando principalmente errores que pueda tener el producto antes de que se publique.

En un modelo tradicional de "garantía de calidad", los objetivos de un miembro del equipo de control de calidad son bastante claros: probar el trabajo de los desarrolladores antes de que se publique, detectar errores, comunicar los hallazgos y abogar por que se solucionen los problemas. (Atlassian). Un analista de control de calidad, o QA (por sus siglas en inglés), es un profesional que se encarga de garantizar la calidad final de un producto o servicio, ya sea un software, hardware, aplicaciones móviles, web, y mucho más. Su principal función es prevenir errores o defectos en el producto. (EDteam)

## Testing o pruebas
Es un proceso que forma parte del ciclo de vida de un software en el que se verifica que el producto tenga el comportamiento esperado, funcione correctamente y cumpla con los objetivo propuestos al principio.

Las pruebas de software son un proceso organizativo dentro del desarrollo de software en el que se verifica la corrección, la calidad y el rendimiento del software crítico para el negocio. Las pruebas de software se utilizan para garantizar que los sistemas empresariales esperados y las características del producto se comporten correctamente como se espera. Las pruebas de software pueden ser un proceso manual o automatizado. (Atlassian)

## Debugging o Depuración
La depuración es el proceso de encontrar y corregir los errores del código.

El término depuración puede significar una gran cantidad de cosas diferentes, pero literalmente significa quitar errores del código. Sin embargo, hay muchas formas de hacerlo. Por ejemplo, puede examinar el código en busca de errores tipográficos o usar un analizador de código. También podría depurar el código mediante un generador de perfiles de rendimiento. O bien, puede usar un depurador. Un depurador es una herramienta de desarrollo muy especializada que se asocia a la aplicación en ejecución y permite inspeccionar el código. (Microsoft) La depuración le permite detectar, diagnosticar y eliminar errores de tiempo de ejecución en un programa. (IBM)


## Metodologías de proyectos
Las metodologías de proyectos son una serie de pasos que se deben seguir durante el desarrollo de un proyecto de tal manera que cumpla los objetivos que supone.

La metodología de gestión de proyectos: un conjunto de reglas, principios y procesos para gestionar un proyecto. (Atlassian) En el ámbito de la gestión de proyectos, se puede definir una metodología como de técnicas, métodos y procedimientos que se deben seguir durante el desarrollo de un proyecto para la producción de los productos o servicios que supone. También puede entenderse como competencias estratégicas ya que les permite a las organizaciones vincular los resultados del proyecto con los objetivos del negocio lo que lleva a la empresa a mejorar y afianzar la participación o posición en el mercado. (Julieth Aguirre Barrera, Stephanny Aguirre Barrera, 2020)

## Metodología en cascada
La metodología en casada es comunmente usado en proyectos con años de duración y con objetivos no cambiantes, debido a que el ciclo del proyecto se realiza solo una vez a lo largo de esos años y una fase empieza cuando termina la otra, es decir secuencial. Por lo tanto, no se tiene muestras del avance del producto hasta la hora de su publicación.

Con este método, se divide el proyecto en diferentes fases. Cuando una fase termina, comienza la siguiente, es decir, no hay solapamiento entre ellas. Cuándo utilizar este método: en proyectos largos que requieran un cronograma único y un orden secuencial. (Atlassian)

## Metodologías ágiles
Las metodologías ágiles consisten en dividir los trabajos de proyecto en plazos más pequeños comunmente de entre dos a cuatro semanas, lapsos en lo que se va cumpliendo en cada una el ciclo de un proyecto, así evaluando continuamente el trabajo realizado para verificar que se este cumpliendo con los objetivos y también analizar si sigue siendo lo mejorar continuar de esa manera o si el proyecto deba cambiar de rumbo. Este método permite que el proyecto este lo más actualizado posible al contexto en el que se encuentra y también una mayor comunicación entre el cliente y el desarrollador, por lo tanto el producto puede cumplir un mejor objetivo funcional a la hora de publicarse. Sin embargo, muchas veces el proyecto puede tender a nunca acabar.

La gestión de proyectos ágil es un enfoque iterativo y mucho más flexible que la gestión de proyectos en cascada. Es una práctica recomendada de DevOps que consiste en dividir los proyectos en fragmentos de trabajo que se abordan en periodos cortos, llamados "sprints". Después de cada sprint, el equipo reevalúa el trabajo que se está realizando para aplicar los cambios oportunos y asegurarse de que se está cumpliendo el objetivo. (Atlassian)

## Iteración
La iteración consiste en repetir varias veces una serie de instrucciones o pasas con el fin de mejorar o perfeccionar el producto. A la hora de repetir del ciclo se parte del último estado del producto en el ciclo previo.

La iteración es el proceso coordinado de repetir una serie de pasos o tareas con el objetivo de mejorar un producto, servicio o proyecto a lo largo del tiempo. En este caso, la repetición de un programa informático para corregir errores y perfeccionar cada uno de sus elementos. Para ello, los informáticos e informáticas ejecutan ciclos repetitivos, en cada uno de los cuales realizan actividades planificadas, recopilan información y se toman las decisiones para mejorar continuamente. Cada ciclo ayuda a avanzar hacia el objetivo final. (Blog Universitat Carlemany)

Github docs:
- https://docs.github.com/es/get-started/using-git/about-git
- https://docs.github.com/es/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#

Atlassian: 
- https://www.atlassian.com/es/git/glossary#commands
- https://www.atlassian.com/inside-atlassian/software-QA-skills
- https://www.atlassian.com/continuous-delivery/software-testing
- https://developer.atlassian.com/platform/forge/debugging/
- https://www.atlassian.com/es/work-management/project-management

Julieth Aguirre Barrera, Stephanny Aguirre Barrera:
- https://repository.unicatolica.edu.co/bitstream/handle/20.500.12237/2037/ARTÍCULO_METODOLOGÍAS_PARA_DESARROLLO_PROYECTOS.pdf

EDteam:
- https://ed.team/blog/que-es-y-que-hace-un-analista-qa

Microsoft:
- https://learn.microsoft.com/es-es/visualstudio/debugger/what-is-debugging?view=vs-2022

IBM:
- https://www.ibm.com/docs/es/i/7.5?topic=handling-debugging-programs

Blog Universitat Carlemany:
- https://www.universitatcarlemany.com/actualidad/blog/que-es-la-iteracion/
