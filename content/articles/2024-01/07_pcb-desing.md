---
title: Diseño de PCBs, primeros comentarios y futuras ideas.
date: 2024-01-07
images:
- /images/2024/01/07_pcbdesign_1.jpg
---

Recientemente he empezado mi travesía en la creación de un sistema de radar de bajo costo, esto con el fin de poder hacer pequeñas investigaciones respecto a sus aplicaciones y posible uso para la solución de problemas del día a día de nuestra sociedad.

Esto me llevó inevitablemente a encontrarme con el diseños de PCB como alternativa de bajo costo, pero que sin duda plantea un reto de ingenio mucho mayor.

### Antecedentes

Cierto es que recientemente cursé la clase de Diseño Electrónico en mi universidad, pero esto no fue más que un curso introductorio para un tema tan complejo como lo es la ingeniería en diseño de PCBs.

Esto me deja con el inevitable (pero emocionante) reto de aprender acerca de este tema por mis propios medios. Como buen estudiante de ingeniería, he decido dividir este reto en pequeñas partes y crear un learning path adecuado para mis propósitos. Antes de ahondar más en el tema me he decido auxiliar en ciertos contenidos.

### Recursos

Tener una guía me parece esencial para empezar con el pie derecho en el camino, por lo que he decidido auxiliarme en un principio en videos de Youtube que me dieran una buena inducción, encontrando así, el día de ayer, el video de `How to Learn PCB Design` del canal _Phil's Lab_:

{{<youtube aODkA2mrimQ>}}

También encontré la gran clase Rick Hartley sobre `How to Achieve Proper Grounding`:

{{<youtube ySuUZEjARPY>}}

Sumado al PDF `PCB Design Tutorial by David Jones` (Adjunto [link](https://www.scs.stanford.edu/~zyedidia/docs/pcb/pcb_tutorial.pdf)) y a la lista de lectura recomendada por Rick Hartley constituye una gran cantidad de contenido para aventurarse en el mundo del diseño de PCB para un estudiante que no puede gastar más de lo que tiene para la comida del mes. Les dejo la [lista de recomendaciones de Rick](https://resources.altium.com/p/reading-list-emi-noise-control).

### Learning Path

Con esto se constituye lo que considero yo el learning path adecuado para las necesidades de un estudiante de ingeniería eléctrica. El proceso de diseños de PCB se puede subdividir en tres partes:

- Simulación.
- Diseño Electrónica Automatizado (EDA).
- Prototipo.

Cada una de estas etapas constituyen su reto específico y para mis fines me estaré centrando principalmente en dos la etapa de Diseño Electrónico Automatizado (maquetado) y creación de prototipo. La etapa de simulación la tengo bastante trabajada ya que esto es lo que principalmente realizamos en la clase de Diseño Electrónico.

#### EDA 

Este constituye parte clave de mis futuros proyectos. En el diagrama de flujo del diseño electrónico se muestra que en caso de que el prototipo presente defectos, se debe volver a la simulación, luego al maquetado y de nuevo al prototipo. Sin embargo, esto no es posible para un estudiante de ingeniería en un país del tercer mundo donde el costo de los componentes son muy altos. Por lo tanto, el dedicarle el tiempo adecuado al maquetado es clave para que no se eviten la mayor cantidad de errores posibles previo al diseño final.

Con este fin, he decido en primera instancia leer el PDF de David Jones y realizar los ejercicios propuestos en el software de EDA **KiCAD** (software de Open Source que fue introducido a mi persona en primera instancia gracias a la clase de diseño electrónico). Una vez familiarizado con KiCad, pienso moverme a libros más siguiendo la lista de recomendación de Rick poniendo en práctica estos nuevos conocimientos en el re-diseño de viejos proyectos que en un futuro subiré en este Digital Garden.

#### Prototipo.

En esta parte tengo que prestar especial atención, esto debido a que la soldadura (como muchos de los trabajos manuales que requieren precisión) sin lugar a duda no es mi fuerte. Tendré que comprar el equipo necesario para trabajar con componentes SMT como podría ser pistola de calor, flux apropiado y estaño apropiado.
Realizar ejercicios de soldadura y de-soldadura serán claves para mejorar. Tengo que buscar recursos que me ayuden en esta tarea.

### Conclusión.

El cúlmine (al menos de la primera etapa) de este learning path será la correcta creación de un radar que estaré discutiendo en futuros posts.

Por el momento esto es todo :smile:.
