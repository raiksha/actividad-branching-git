# Reflexión Grupal




## Preguntas 

1.-¿Qué entendieron ahora por branching en Git?

Branching en Git se refiere a la creación de ramas dentro de un repositorio para trabajar de manera independiente en diferentes tareas sin alterar el código principal. Esto permite realizar cambios de forma paralela, sin afectar el proyecto original. Las ramas ayudan a organizar y aislar el trabajo, evitando conflictos con el código central hasta que los cambios sean validados y listos para integrarse.

2.- ¿Qué diferencia hay entre branch y fork?

Un branch es una rama dentro del mismo repositorio, utilizada para realizar cambios paralelos sin modificar el código principal. Un fork, en cambio, es una copia completa de un repositorio que se guarda en otra cuenta, lo que permite realizar modificaciones sin afectar el repositorio original. El fork es útil para proyectos colaborativos donde se trabaja en un repositorio ajeno.

3.-¿Por qué no conviene trabajar directo en main?

Trabajar directamente en la rama main puede generar problemas como la pérdida de datos o la afectación del proyecto completo en caso de cometer errores, ya que main es la versión estable del proyecto. Modificarla directamente puede causar conflictos con otros miembros del equipo, haciendo más difícil la integración y revisión del código.

4.- ¿Qué aporta el Pull Request al trabajo en equipo?

El Pull Request (PR) permite que los cambios sean revisados antes de ser integrados a la rama principal. Esto contribuye a evitar conflictos de código, errores y mejora la calidad del trabajo colaborativo. También ofrece una oportunidad para discutir y mejorar los aportes, asegurando que los cambios sean correctos y no interfieran con el trabajo de otros.

5.-¿Qué parte del proceso les pareció más difícil?

Las partes más difíciles fueron comprender el flujo de trabajo completo, como la creación de ramas, subir cambios y abrir Pull Requests. También fue complicado recordar los comandos correctos y evitar cometer errores durante el proceso. En general, el desafío estuvo en entender bien el propósito de cada paso y cómo estos se relacionan para no generar conflictos o sobrescribir información importante.

6.-¿Qué pasaría si varias personas editan lo mismo?

Cuando varias personas editan el mismo archivo, se genera un conflicto de merge, donde Git indica que hay diferencias que deben ser resueltas manualmente. Si no se maneja correctamente, podría perderse información o sobrescribirse el trabajo de otros, lo que puede afectar la integridad del proyecto y requiere una revisión detallada para decidir qué cambios deben prevalecer.

7.-¿Qué buenas prácticas aplicarían en un proyecto real?

Es fundamental actualizar siempre el repositorio antes de empezar a trabajar para evitar conflictos con versiones antiguas. Además, se deben usar nombres descriptivos para las ramas y commits claros que expliquen el propósito de cada cambio. Es importante trabajar siempre en ramas separadas de main y hacer revisiones de código con respeto y colaboración.

8.-¿Qué aprendieron del rol de quien revisa y acepta cambios?

El rol de quien revisa y acepta cambios es crucial, ya que tiene la responsabilidad de verificar que el código no genere conflictos o errores. Esta persona actúa como un filtro final antes de que los cambios se integren al proyecto, asegurándose de que todo funcione correctamente y de que los errores sean identificados a tiempo, además de proporcionar retroalimentación constructiva.
