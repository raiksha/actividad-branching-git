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

## Aporte alumna 7 Arantxa

# ¿Qué es un merge?

Un merge (o fusión) es el proceso de unir dos ramas de código, una secundaria y la principal. 

## Definición simple
Básicamente, significa unir dos ramas de un código. Pueden entrar en conflicto cuando se modifica la misma línea de código por dos personas distintas o en momentos distintos. Es un problema porque se rompe la lógica del código, o se pierden los cambios. Además, si se espera mucho tiempo para sincronizar a la rama principal, puede crear muchos errores al ser códigos tan diferentes. Se puede solucionar comunicándose con el equipo y con la sincronización del fork.  

## Ejemplo

Una analogía de este proceso, es lo que ocurre en el universo cinematográfico de Marvel, y las repercusiones de las Infinity Stones, que causaron la bifurcación del universo al ser usadas por personas de una linea de tiempo distinta, resultando en un multiverso, problema que (SPOILER)  se resolvió cuando Loki creo el árbol del multiverso, o Yggdrasil. 

## Conclusión personal

El merge es un paso importante en la creación del código y el trabajo en equipo, ya que permite avanzar más rápido en la creación de código, pero se debe hacer con cuidado para no afectar el main. 