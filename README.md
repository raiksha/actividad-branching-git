# Actividad Branching Git

## Integrantes
- [María Riquelme](https://github.com/raiksha)
- [Angela Galleguillos](https://github.com/AngieG-dev)
- [Matias Flores](https://github.com/MatRoig)
- [Zuelem Chanillao](https://github.com/zuelem)
- [Dafne Mandujano](https://github.com/DMandujano)
- [Valentina Llanten](https://github.com/CodeMochi-dev)
- [Arantxa Fischer](https://github.com/a-scarfisch)
- [Pablo Fuentes](https://github.com/PabloDesk)


## Objetivo
Practicar branching, fork, pull request y merge.

----------------------------

## Aporte Alumno 1 - Constanza

## Tema investigado

¿Qué es una rama en Git?

## Definición

Una rama en Git (en inglés: Git branch) es una **línea de desarrollo** dentro del historial de un repositorio, representada como una **secuencia de commits**, que permite trabajar en cambios de forma **separada** de la línea principal (main) para evitar conflictos y desorden en el código.

## Explicación propia

Una rama es como un “camino” dentro del proyecto. Todo el código va avanzando a través de cambios (commits), y cada rama sigue su propio camino dentro de ese historial. Puedes tener varias ramas al mismo tiempo, cada una con su propio progreso, sin que interfieran directamente entre sí hasta que se unan.

## Ejemplo

Imagina que varias personas están trabajando en una tesis grupal. Existe un **documento principal** que contiene la versión oficial del trabajo. En lugar de que todos editen ese mismo archivo al mismo tiempo, cada integrante trabaja en su **propia copia del documento**, donde desarrolla sus ideas, hace cambios y corrige partes.

Luego, el grupo se reúne para revisar esos avances y decidir qué cambios se **integran** al documento principal.

En esta analogía:

* El documento principal representa la **rama `main`**
* Las copias individuales de cada persona representan las **ramas secundarias**
* La reunión donde se integran los cambios corresponde al proceso de **unir ramas (merge)**


## Respuestas

1. **¿Qué es una rama en Git?**
   Es una línea de desarrollo dentro del historial del repositorio, formada por una secuencia de commits.

2. **¿Por qué las ramas ayudan a ordenar el trabajo?**
   Porque permiten separar distintas tareas (como nuevas funciones o correcciones) en líneas de desarrollo distintas, evitando mezclar cambios de forma desordenada.

3. **¿Qué riesgo existe si todos trabajan en `main`?**
   Se pueden mezclar cambios sin control, generar errores en la versión principal y provocar conflictos frecuentes entre los aportes de distintos desarrolladores.

## Conclusión personal

Las ramas son una forma de estructurar el desarrollo de un proyecto, permitiendo trabajar en distintas partes del código de manera organizada. Sin ellas, el trabajo sería más caótico y propenso a errores, especialmente cuando participan varias personas.

-----------------------------

## Aporte Alumno 2 - Angie

## Investigación diferencia entre branch y fork

### Investigación general

**Definiciones**

Branch: o traducido al español como rama, es una línea de desarrollo que se separa de la linea original del proyecto, pero se trabaja de forma paralela al original. En ella se pueden hacer cambios y arreglos sin afectar la sección original y más estable del proyecto.

Fork: o conocido como bifurcación en español, es la acción de crear la copia exacta de un repositorio en la cuenta propia, ésta copia es independiente y no modifica el repositorio original hasta que se hace una solicitud al dueño del repositorio original o _pull request._

**Explicación**

Branch es tal como se traduce al español, rama, es el hacer un muñeco de pruebas del proyecto original, se encuentra en el mismo repositorio pero no modifica el proyecto original, en el branch se pueden probar nuevas funciones o arreglar bugs

Fork es una copia exacta pero que pertenece a un usuario distinto al dueño del proyecto original, el fork no se encuentra en el mismo repositorio que el original, ahora hay dos repositorios iguales, pero independientes en su totalidad.

**Ejemplos**

Para ejemplificar branch

Eres un cuidador de bonsai, quieres ser arriesgado con el estilo de tu bonsai pero no quieres arruinar de forma permanente tu arbol miniatura, asi que creas un holograma que es identico a tu bonsai, en él puedes probar todo lo que quieras sin arruinar tu bonsai, si te gustas, lo incorporas a tu obra maestra, y si no te gusta, solo apagas el holograma.


Para ejemplificar fork

Imagina que tienes una vaca, y un amigo quiere tu vaca para probarle un nuevo corte de pelo, tú no estas muy seguro de que lo hará bien, así que clonas tu vaca. Ahora hay dos vacas identicas, pero una la tienes tú, la original, y la clon la tendrá tu amigo en su granja, y los cambios que haga a su vaca no afectará a la tuya a menos que tu decidas incorporar los cambios
Preguntas

⦁	¿Qué es una branch?
Branch es una linea de desarrollo que nace del proyecto original, se pueden hacer modificaciones que no afecten al proyecto original
⦁	¿Qué es un fork?
Es una función de Git que permite crear una copia de un repositorio pero en tu propio perfil, es total y absolutamente independiente del proyecto original.

⦁	¿Cuál es la diferencia entre ambos?
La diferencia entre ambos llase en que branch se encuentra en el mismo repositorio que el proyecto original, mientras que fork es una copia del repositorio que pertenece ahora a otro usuario.

## Conclusión

Tanto como branch como fork con funciones importantes dentro de git, que permiten que varias personas trabajen a la vez en distintas áreas de un mismo proyecto sin afectar la versión más estable, incluso probar nuevas funciones, pero hay diferencias fundamentales en ambas, siendo que fork es una copia identica de un repositorio en otro perfil distinto al dueño del proyecto, mientras que branch sigue perteneciendo al mismo repositorio original.

-------

## Aporte Alumno 3 - Matías

## Tema Investigado `main`

**Definición: ¿Que es `main`?**

`main` (o master en repositorios antiguos) es la rama principal y por defecto de un repositorio en Git. Actúa como el tronco central del proyecto, donde se encuentra el código más estable y funcional. Es el punto de partida para desarrollar nuevas características y el destino final donde se integran todos los cambios aprobados, representando así la versión oficial y lista para usar del software en cada momento.

**En mis palabras:**

Para mi, `main` representa el proyecto en si mismo de forma tangible. Es la versión consensuada que usaremos como referencia para implementar cambios a traves de "copias" de esta version, y a medida que estos cambios se aprueben, se irán incorporando a a esta "versión consensuada" lo que nos permitirá ir actualizandola y avanzando hasta el resultado final del proyecto.

**Respuestas**

1. ¿Qué representa `main` en un proyecto?
Como mencioné anteriormente, `main` representa el "core" del proyecto, la vision consensuada, aprobada y que usamos de referencia para implementar cambios, mantendiendo así un orden de trabajo en el equipo

2. ¿Por qué no debería usarse para cambios directos?

No debería usarse ya que pondría es peligro la estabilidad del codigo
Usar directamente `main` puede generar diversos problemas con la sincronización del equipo al trabajar en simultaneo: si dos personas trabajar en simultaneo, algun error de uno de ellos puede afectar al otro u otros compañeros de equipo.
Además haría mucho más dificil hacer seguimiento a lo que cada integrante desarrolla y aporte.

3. ¿Por qué es importante mantenerla estable?

Mantener el método `main` estable es crucial porque es el punto de partida de la aplicación, por ende al fallar, falla todo hacia delante.
Tambien nos va a permitir el uso correcto de ramificaciones, permitir que estas sean revisadas y así actualizar el `main`, asegurandose de mantener esta estabilidad.
Nos facilitará el trabajo ya que no habra que volver a corregir errors en `main` y podremos dedicarnos a trabajar en nuevas características

## Conclusión

`main` es una parte fundamental de nuestros proyectos, nos ayuda a mantenernos organizados, trabajar en equipo, evitar errores y trabajo innecesario y nos incita a trabajar de manera limpia y ordenada. Es la parte más importante del proyecto, y que hay que cuidar


-------

## Aporte Alumna 4 Zuelem

Tema investigado
 ¿Qué es un commit y por qué es importante?
 
## Definición
[Un commit en Git es un objeto que representa una instantánea (snapshot) del estado completo del repositorio en un momento específico. Este objeto incluye metadatos (autor, fecha, mensaje) y una referencia a un árbol (tree) que describe la estructura y contenido de los archivos versionados]
 
## Explicación propia
EL commit representa una versión completa del proyecto hasta el momento en que este es nombrado, guardando cada una con un título diferenciado. Idealmente debe ser  escrito según la connveción para compartir facilmente con otros la información. La ventaja de hacer varios commits pequeños es que cada uno guarda una versión que nos deja volver atrás en caso de ser necesario y revisar los cambios.
El commit otorga el historial de trabajo, de manera ordenada y simple , al seguir el conventional commits que nos ayudan a automatizar, aclarar y colaborar en el proyecto.   
 
## Ejemplo
EL commit es como un marcapáginas de un libro, haciendo esta analogía . El marcapáginas representa el lugar en el que quedamos, si queremos volver atrás podemos hacerlo para releer además de revisar donde quedamos y lo que estaba escrito con anterioridad al ir avanzando.


## Conclusión personal
Los commits son un herramienta en forma de  que permite organizar los cambios en nuestro Git, esto es vital para realizar un trabajo grupal y que todos puedan entenderlo. Además de guardar una "copia" de nuestro trabajo hasta el momento, en el caso de que hayamos cometido un error podemos volver atrás y revisar nuestro trabajo anterior.

---
## Aporte Alumno 5 - Dafne
## Tema investigado
¿Qué es push y qué relación tiene con GitHub?

## Definición

- **Trabajar local:** Realizar cambios en el proyecto desde tu propio computador, usando una copia del repositorio.

- **Remoto:** Es el repositorio que está en internet (GitHub).

- **push:** Subir tus cambios desde tu computador al repositorio remoto.

- **¿Por qué no aparecen los cambios automáticamente?:** Porque Git no los sube por sí solo; es necesario ejecutar el comando push para enviarlos al repositorio remoto.

## Explicación propia

Trabajar local es trabajar desde tu propio computador en vez de la web, para luego subir los cambios a GitHub. En cambio, trabajar remoto es trabajar directamente desde la web.

Para subir los cambios desde tu computador a la web se utiliza el comando push, que envía los cambios hechos en el repositorio local al remoto.

Git no sube los cambios automáticamente para evitar errores, por lo que la única manera de subirlos es usando el comando push.

## Ejemplo

Cuando realicé mi proyecto de título, tuve que trabajar con varias personas en un mismo código y, para evitar conflictos, cada uno trabajaba desde su computador en el repositorio local y luego subíamos los cambios al repositorio remoto usando push.

El hecho de que los commits no se subieran automáticamente nos permitía tener más control sobre los cambios que hacíamos, ya que, si no revisábamos bien el código, podríamos afectar la rama main y hacer fallar el programa.

## Respuestas

1. **¿Qué diferencia hay entre local y remoto?**

- La diferencia es que local se trabaja desde el computador, mientras que remoto es trabajar desde la web (GitHub).

2. **¿Qué hace git push?**

- git push permite subir los cambios hechos en el repositorio local al remoto.

3. **¿Por qué un commit local no siempre aparece en GitHub?**

- Porque si no se usa el comando push, ningún commit hecho en local aparecerá en GitHub. Esto permite tener mayor control sobre los cambios antes de subirlos.

## Conclusión personal

Cuando se trabaja en un equipo grande en un mismo programa, usar un repositorio local permite que todos trabajen al mismo tiempo sin afectar la rama main. De esta forma, los cambios se pueden revisar antes de subirlos y así evitar errores en el código. Luego, se utiliza push para subirlos al repositorio remoto, lo que permite tener un mayor control sobre los cambios que realiza cada persona del equipo.

---
## Aporte Alumno 6 Valentina 

## Tema investigado
**¿Qué es un Pull Request (PR)?**
 
## Definición
Es una petición formal en GitHub para integrar los cambios realizados en una rama de trabajo hacia la rama principal del proyecto. Es el paso previo donde el código queda "en espera" para ser revisado y aprobado por el equipo antes de unirse al código oficial.
 
## Explicación propia
Para mí, un **Pull Request** es el espacio de conversación y seguridad del equipo. Es la forma de avisar: *"He terminado mi parte, por favor revisen mi código antes de sumarlo al resto"*. Como segunda revisora, entro al PR para comparar los cambios con la versión original y asegurar que todo esté ordenado, sin errores técnicos y listo para el **merge**.
 
## Ejemplo
Supongamos que un compañero termina una función en **JavaScript** y abre un Pull Request. Mi proceso en GitHub sería:
1. Entrar al PR y revisar en la pestaña de cambios qué líneas se agregaron o borraron.
2. Verificar que aparezca el "check verde" de GitHub (que indica que no hay conflictos).
3. Revisar que la lógica de la función sea clara y no tenga errores de escritura.
4. Comentar: *"Todo ok, la lógica es clara y no rompe nada. Listo para subir"*.
 
## Respuestas

1. **¿Qué es un Pull Request?** Es una herramienta de GitHub para pedir permiso antes de integrar cambios. Es el momento en que un desarrollador le dice al equipo: *"He terminado mi parte en mi rama, por favor revisen si mi código está bien para sumarlo al proyecto oficial"*.

2. **¿Para qué sirve en trabajo colaborativo?** Sirve para mantener el orden. Permite que varias personas trabajen en el mismo repositorio sin sobrescribir el trabajo de otros por error, facilitando que el equipo revise y discuta las mejoras antes de que sean definitivas.

3. **¿Por qué es importante revisar antes de hacer merge?** Es fundamental para atrapar errores antes de que afecten a todo el grupo. Al revisar, nos aseguramos de que el código sea de calidad, que no rompa lo que ya funciona y que la versión principal del proyecto en GitHub siempre esté estable y limpia.
 
## Conclusión personal
Aprender a usar los **Pull Requests** me ha permitido ver el código desde otra perspectiva. Detectar posibles errores antes del merge no solo cuida la estabilidad de la app, sino que me ayuda a crecer como desarrolladora al compartir conocimientos y asegurar que entreguemos un trabajo profesional como equipo.

----------------

## Aporte alumna 7 Arantxa

# ¿Qué es un merge?

Un merge (o fusión) es el proceso de unir dos ramas de código, una secundaria y la principal. 

## Definición simple
Básicamente, significa unir dos ramas de un código. Pueden entrar en conflicto cuando se modifica la misma línea de código por dos personas distintas o en momentos distintos. Es un problema porque se rompe la lógica del código, o se pierden los cambios. Además, si se espera mucho tiempo para sincronizar a la rama principal, puede crear muchos errores al ser códigos tan diferentes. Se puede solucionar comunicándose con el equipo y con la sincronización del fork.  

## Ejemplo

Una analogía de este proceso, es lo que ocurre en el universo cinematográfico de Marvel, y las repercusiones de las Infinity Stones, que causaron la bifurcación del universo al ser usadas por personas de una linea de tiempo distinta, resultando en un multiverso, problema que (SPOILER)  se resolvió cuando Loki creo el árbol del multiverso, o Yggdrasil. 

## Conclusión personal

El merge es un paso importante en la creación del código y el trabajo en equipo, ya que permite avanzar más rápido en la creación de código, pero se debe hacer con cuidado para no afectar el main. 

---

## Aporte Alumno 8 Pablo

## Tema investigado 
**Buenas prácticas al trabajar con ramas**
 
## Definición
Una **Rama** (o **Branch**) constituye un entorno de trabajo independiente derivado de una versión específica del código base. En este ecosistema, la **Rama Principal** (**Main** o **Master**) funciona como el repositorio del código estable, validado y preparado para producción. Paralelamente, se emplean **Ramas de Funcionalidad** (**Feature Branches**) para la implementación de nuevas características o la resolución de errores técnicos, permitiendo que el desarrollo progrese sin comprometer la integridad del tronco principal. Este modelo garantiza la seguridad del proyecto, ya que cualquier experimento fallido puede descartarse eliminando la rama afectada sin impacto alguno en el código fuente. Asimismo, optimiza la colaboración técnica, permitiendo que múltiples desarrolladores trabajen de forma simultánea y aislada en distintos requerimientos sobre un mismo proyecto, evitando conflictos de integración. 

Para trabajar con ramas de manera profesional, es fundamental mantener un flujo ordenado basado en tres pilares: **mensajes de commit claros**, que actúan como un mapa histórico para entender el porqué de cada cambio; **ramas de vida corta**, que evitan conflictos técnicos masivos al integrar pequeñas funcionalidades de forma constante; y la **revisión de código antes de fusionar** (**merge**), que funciona como un **filtro de calidad** esencial para detectar errores y compartir conocimientos entre el equipo antes de que el código llegue a producción. Además, resulta indispensable la implementación de **Commits Atómicos**, una práctica que consiste en **registrar cambios frecuentes** y granulares que representen **una única unidad lógica funcional**. Este enfoque optimiza la trazabilidad del historial y permite una reversión precisa de errores, minimizando el riesgo de perder horas de trabajo. Al fragmentar el desarrollo en aportes indivisibles, se reducen significativamente los conflictos de integración, sustituyendo las entregas masivas por un flujo colaborativo más ágil, seguro y auditable. Finalmente se realiza la **revisión previa al merge**, esto constituye un filtro crítico de control de calidad que permite detectar errores lógicos o vulnerabilidades antes del despliegue en producción. Este proceso no solo garantiza la estandarización y mantenibilidad del proyecto bajo lineamientos técnicos uniformes, sino que también fomenta la transferencia de conocimiento y la responsabilidad compartida, fortaleciendo la cohesión técnica y la fiabilidad del software.

## Explicación propia
Para mi, Una **Rama** o **Branches** es simplemente un espacio separado de trabajo que nace a partir de una versión específica de un código. Se encuentran la **Rama Main** (**Master** o **Principal**) donde reside el código que funciona perfectamente y que está listo para producción. Después están **Ramas de Funcionalidad** (**Feature Branches**) que se usan cuando se necesita agregar algo nuevo, por ejemplo un botón o corregir un error en el codigo. Esto permite trabajar sin afectar al equipo ni al código main. Se usan por seguridad si un experimento sale mal, simplemente se borra la rama y se crea otra nueva mientras que la rama main sigue estando intacta. También se usa para la **Colaboración**, ya que diez personas pueden trabajar en diez ramas distintas al mismo tiempo sobre el mismo proyecto sin estorbarse.

## Preguntas
### 1. ¿Cómo deberían nombrarse las ramas?
- Primero tiene que haber una **rama main**, para después crear las demás con sus **funciones especificas**, ademas de especificar las funciones que tendrán mas adelante cuando se agreguen a main.

### 2. ¿Cómo debería escribirse un commit claro?
- Para redactar un commit claro y profesional, la clave es utilizar el estándar de Conventional Commits, que consiste en asignar un prefijo al mensaje según el tipo de cambio (como **feat**: para funciones, **fix**: para errores o **refactor**: para mejoras técnicas). El mensaje debe escribirse en modo imperativo y ser lo más específico posible dentro de una extensión breve, **por ejemplo: feat: agregar validación de formulario**. Este enfoque no solo facilita la lectura del historial, sino que permite que cualquier desarrollador entienda de inmediato qué se hizo y cuál es el propósito del cambio sin necesidad de revisar el código línea por línea.

### 3. ¿Qué buenas prácticas ayudan a trabajar mejor en equipo?
- Para trabajar con ramas de manera profesional se necesita mensajes de **commit claros** que sirven como historial de cambios, **ramas de vida corta** para evitar conflictos técnicos al integrar, y la **revisión de código antes del merge**, como filtro esencial de calidad. Además, es indispensable realizar **Commits frecuentementes** registrando cambios que representen una única unidad lógica. Este enfoque optimiza la trazabilidad y permite revertir errores con precisión sin perder horas de trabajo, sustituyendo las entregas masivas por un flujo colaborativo mucho más ágil, seguro y fácil de auditar.

## Ejemplo
Produzco una nueva rama llamada feature/documents donde se enfocara en generar documentaciones de los procesos hechos en el proyecto, ademas de instrucciones, cargos, y posibles tareas a futuro del proyecto en Github. Con esto puedo trabajar de forma separada de la Main, mientras mis compañeros colaboran en sus respectivas ramas sin preocuparse de que arruine el código principal.

## Conclusión Propia
