# Planificación de Proyectos

## Proceso de Diseño

Se buscan satisfacer necesidades insatisfechas.

* Ser único
* Ser complejo
* Cumplir con una organización temporaria/un plan preestablecido
* Tener objetivos relacionados con la satisfacción de las necesidades
* Satisfacer requerimientos específicos

Los requerimientos son la base de las especificaciones

### Propósito

Se define primero el propósito, el cual es la razón de ser o el significado más
profundo del proyecto.

### Objetivo

Es la meta concreta y tangible que se busca alcanzar, basada en el propósito.

### Alcance

Teniendo bien claro el propósito y el objetivo del proyecto, el alcance define
los límites y fronteras del proyecto. Es la suma de todos los requerimientos y
las restricciones.

## Pensamiento de Diseño (Design Thinking)

El pensamiento de diseño es una metodología que se aplica en el diseño de
productos, esta metodología esta centrada en las personas, ya que se basa en
entender las necesidades del usuario, generando ideas, prototipando soluciones y
probándolas corrigiéndolas y volviendo a empezar, esto ultimo notando el
comportamiento iterativo de la metodología.


![Proceso de Diseño](./proceso_de_diseno.png)

![Proceso de Diseño](./definicion_de_producto.png)

### Etapas del pensamiento de diseño

1. Empatizar
2. Definir
3. Idear
4. Prototipar
5. Evaluar

#### Empatizar

##### Mapas de Empatía

Es una herramienta que ayuda a sintetizar la información obtenida del usuario
(en etapas previas, como entrevistas, o mediante observación, etc) de manera tal
que resulte mas fácil identificar descubrimientos (insights) que no se obtienen
solo con datos.

La estructura típica de un mapa de empatía es:

1. Dice
2. Piensa
3. Siente
4. Hace
5. Esfuerzos
6. Necesidades

## Work Breakdown Structure (WBS)

En el WBS se incluye (o se plasma) el alcance y los requerimientos del proyecto.
Se incluyen todos los entregadles y trabajos intermedios necesarios para
completar el proyecto.

## Activity on Node (AON)

En el AON se muestran todas las actividades necesarias para completar el
proyecto en un diagrama de nodos y flechas, de manera que se pueda ver las
dependencias de cada actividad y se pueda estimar tiempos.

El camino critico es el camino de actividades que de retrasarse, se retrasa todo
el proyecto, es el de mayor duración, o de holgura nula. La holgura es el tiempo
que puede retrasarse (en iniciar o finalizar) sin que se retrasen otras
actividades dependientes de esa.

## Metodologías Ágiles

La metodología ágil es un enfoque flexible para la gestión de proyectos que se
centra en la colaboración, la comunicación y la entrega de valor de manera
iterativa y continua. En lugar de planificar exhaustivamente al inicio, las
metodologías ágiles permiten adaptarse a los cambios en los requisitos y
prioridades a lo largo del proyecto


### Metodología Scrum

Es una forma de organizar el trabajo en equipo en ciclos cortos y repetitivos
llamados Sprints, con el objetivo de entregar valor rápidamente, adaptarse a
cambios y mejorar continuamente.

#### Roles en Scrum

* Product Owner (Dueño del Producto): Representa al cliente y prioriza el
  trabajo (Product Backlog).
* Scrum Master: Facilita el proceso Scrum, elimina obstáculos y guía al equipo.
* Equipo de desarrollo: Grupo auto-organizado que lleva a cabo el trabajo
  técnico.

#### Product Backlog

Lista priorizada de requisitos del producto (historias de usuario).

#### Sprint Backlog

Conjunto de tareas seleccionadas para el Sprint actual.

#### Incremento

Producto potencialmente entregable al final de cada Sprint.

#### Historias de Usuario

Las historias de usuario son una forma de describir lo que el usuario
necesita de manera simple, clara y centrada en el valor que aportará esa
funcionalidad o característica.

El formato mas común de historia de usuario es Como **\<usuario>** Quiero **\<lo que
desea>** Para **\<beneficio o valor>**

* Se crean y priorizan en el Product Backlog.
* Se seleccionan en la planificación del Sprint.
* El equipo las desarrolla e implementa durante el Sprint.
* Card: cada historia de usuario se reduce hasta hacerla fácil de memorizar y de
sintetizar en una tarjeta o post-it. La tarjeta sirve como recordatorio y
promesa de una conversación posterior.
* Conversation: el equipo de desarrollo y el propietario del producto añaden
criterios de aceptación a cada historia poco antes de su implementación. Los
cambios son bienvenidos en agilidad, por lo que no tiene sentido profundizar en
estos detalles antes. La situación puede variar mucho desde el momento en el que
se sintetiza la funcionalidad en la tarjeta hasta que se implementa.
* Confirmation: el propietario del producto o usuario de negocio confirma que el
equipo de desarrollo ha entendido y recogido correctamente sus requisitos
revisando los criterios de aceptación. A veces se pueden presentar transformados
en escenarios de pruebas.

#### Temas, Epicas y Tareas

* Epic: es una historia de usuario de gran tamaño o alta granularidad, y que
  tiene por tanto un mayor grado de incertidumbre. Marcar una historia como epic
  implica que no puede completarse de una sola vez o en un único sprint. Lo
  normal es que el equipo de desarrollo lo descomponga cuando se acerque el
  momento de su implementación. Las historias de usuario resultantes estarán
  íntimamente relacionadas y su menor tamaño permitirá gestionarlas de forma
  ágil, estimando mejor el tiempo requerido para completarlas y siguiendo su
  avance con detalle.
* Tema: una colección de epics e historias de usuario relacionadas que describen
  un sistema o subsistema. Se trata de un elemento que forma parte de la visión
  del producto, más que una funcionalidad. Por ejemplo: en un sistema de
  software para gestión contable, el conjunto de epics «altas, bajas y
  mantenimiento de clientes», «facturaciones puntuales y recurrentes»,
  «consultas de navegación y acciones de fidelización», «pedidos»
  y«devoluciones» se podrían denominar como el tema de la «gestión de clientes».
* Tareas: están por debajo de las historias de usuario. Describen cómo construir
  en lugar de qué. Resultan de la descomposición de las historias de usuario en
  unidades de trabajo adecuadas pare gestionar y seguir el avance de su
  ejecución.

### Riesgos

Los riesgos son cualquier "evento" que altera la planificación original de
objetivos y planes del proyecto.

#### Gestión de riesgos

La gestión de riesgo implica identificar los riesgos, sus efectos y tratar de
reducir sus consecuencias. Esto **no elimina** los riesgos, pero maximiza la
chance de éxito a pesar de los problemas.

Establecer planes de contingencia para todos los riesgos implica el incremento
de costos. Debemos decidir cuáles riesgos serán mitigados en base a distintos
criterios los cuales deben ser correctamente explicados y conocidos por todos los
interesados e involucrados en el proyecto.

Para definir si se debe contar con un plan de mitigación de un riesgo se lo
puede;
- Clasificar de acuerdo a la probabilidad de ocurrencia; utilizando una métrica
  de 0 a 100% y la etiqueta agrupadora de “siempre”, “frecuentemente”,
  “ocasionalmente”, “raramente”, “nunca”.
- Clasificar de forma ordinal: esto es; primero el riesgo más probable, luego el
  segundo, ý así sucesivamente.
- Clasificar en forma relativa; por ejemplo, “el riesgo A es dos veces más
  probable que el riesgo B” “Siempre se debe entender el impacto del riesgo en
  el proyecto y el impacto en la calidad del proyecto”

1. Identificar los riesgos: determinar que aspectos del plan o del proyecto
   podrían cambiar.
2. Estimar las consecuencias de esos riesgos: evaluar qué podría pasar si esos
   aspectos cambian.
3. Elaborar planes para mitigar sus efectos: determinar cómo se puede proteger
   el proyecto ante los riesgos.
4. Seguir el estado de los riesgos: su probabilidad de ocurrencia, la aparición
   de nuevos riesgos, etc.
5. Informar a todos los interesados sobre los riesgos.

Para detectar cuál riesgo conviene mitigar primero se puede utilizar el “RPN”;
en inglés, “Risk Priority Number”. 

$$ RPN = Prob. de Ocurrencia * Factor de Severidad * (1 – Prob. de Detección)$$

Siendo "Prob. de Ocurrencia": Probabilidad que ocurra ese evento; Factor de
Severidad: Indicador del daño potencial que podría generar. (Valoración
subjetiva de 0 a 1) y Probabilidad de Detección: la probabilidad de detectar la
ocurrencia del evento con anticipación.
