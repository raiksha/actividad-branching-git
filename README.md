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