## Semana 1:

Asistente Van Rossum
Un asistente de conocimiento para resolver las dudas del entrenamiento del clan Van Rossum.

Problema que resuelve
Los coders del clan preguntan una y otra vez lo mismo (horarios, temas, entregas) y a veces reciben respuestas distintas según a quién le pregunten. 
El asistente responde rápido y de forma consistente, usando solo la información oficial del entrenamiento.

¿Quién lo usa?
Los coders del clan Van Rossum.

¿Qué le preguntan?
Temas de cada semana.
Entregas: qué, cuándo y cómo se entrega
Indicaciones y avisos de los TL.

¿De dónde saca la información?
Solo de dos fuentes:
La información que entregan los TL (Team Leaders) del clan.
Las fechas publicadas en Moodle.
Si algo no está en esas fuentes, no lo responde.

¿Qué NO debe hacer?
Inventar datos (fechas, horarios, reglas).
Dar o estimar notas.
Decidir por el TL (prórrogas, excepciones, aprobaciones).
Responder temas ajenos al entrenamiento.
Cuando no sabe.
Lo dice claramente: «No encuentro eso en la información del clan».

Ejemplos para probarlo
Dentro del alcance «¿Cuándo es la próxima entrega?»
Fuera del alcance «¿Qué nota voy a sacar?» o «¿Puedo entregar tarde?». 

## Semana 2:

Límites del modelo y cómo los cubre el asistente

| Límite | Cómo se cubre |

Puede alucinar (inventar datos o fuentes) | **Fuentes:** solo responde con lo que está en la información de los TL y en Moodle, e indica de cuál salió. Si no está, dice "No encuentro eso en la información del clan".
Tiene fecha de corte | **Fuentes:** no usa lo que "sabe" por su cuenta; las fechas y horarios salen siempre de Moodle o de los TL. Se indica la fecha de la última actualización de la información. |
Puede repetir sesgos | **Control humano:** no opina sobre personas, no da notas ni evalúa. Esos temas se redirigen al TL. 
Responde distinto a la misma pregunta | **Avisos:** da respuestas cortas, con el mismo formato y citando la fuente.

Diseño del asistente: fuentes, avisos y control humano

- **Fuentes:** responde solo con documentos del clan (TL y Moodle) y dice de dónde sale cada dato.
- **Avisos:** advierte que puede equivocarse y que la información depende de la última actualización.
- **Control humano:** las decisiones, las notas y las excepciones las toman el TL nunca el asistente.