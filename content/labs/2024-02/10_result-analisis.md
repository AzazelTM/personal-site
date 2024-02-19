---
title: Analisis de Resultados, La guia del estudiante.
date: 2024-02-18
images:
- /images/2024/02/18_portada.jpg
---

Siempre me hacen la pregunta clave: _Como se hace un buen análisis de resultados?_.
Aquí veremos cómo. Atentos.

### Definición

Les dejo la que más me gusto :smile: :

> Análisis de resultados es el proceso de examinar y evaluar datos obtenidos de experimentos, investigaciones o pruebas para extraer conclusiones significativas y tomar decisiones informadas.

Fuente: Enciclopedia Británica.

### Tipos

Realmente existen muchos tipos de análisis de resultados, pero los más usados en los laboratorios son dos:

- Análisis Cualitativo.
- Análisis Cuantitativo.

**Analisis Cualitativo**: 

> Explora y analiza datos no numéricos, como textos, entrevistas, o respuestas abiertas en encuestas. Se centra en patrones de significado, temas y conceptos emergentes.

Este se suele utilizar cuando se estudian características de un fenómeno particular, como podría ser condiciones generales de encendido de un led, o la relación entre el cambio de estado de un componente dentro de un circuito (ejemplo: un botón) con respecto al resto del susodicho.

**Análisis Cuantitativo**: 

> Examina datos numéricos mediante técnicas estadísticas y matemáticas. Incluye el uso de medidas cuantitativas para describir y comparar fenómenos.

El más común de encontrar entre nuestros laboratorios. Se usa cuando existe un proceso de adquisición de datos mediante instrumentos.

### Análisis cualitativo, cómo se hace?

Pasos:

1. **Familiarización con los Datos.**

Lee o escucha los datos en su totalidad para familiarizarte con el contenido. Toma notas preliminares y reflexiona sobre las impresiones iniciales.

2. **Categorización de Datos.**

Identifica unidades de significado en los datos y asigna categorías descriptivas a estas unidades. Las categorías son etiquetas que resumen temas o conceptos clave. Estos conceptos claves tienen que ir relacionados directamente con los objetivos del experimento o práctica.

Ejemplo: En un experimento de comportamiento de un Transistor usado como conmutador de un LED vs. Encendido de LED sin conmutador con semiconductor; las categorías serían:

- Estado de LED.
- Disipación de calor de resistencia en serie de LED.
- Corriente asociada a cada fenómeno.

También se pueden agregar categorías tales como costo económico asociado, y complejidad del circuito.

3. **Muestreo de Datos**

Selecciona muestras específicas de datos para un análisis más detallado. Puedes enfocarte en casos extremos, casos típicos o ejemplos que ilustren ciertos patrones.

4. **Matriz de Cualitativa**

Crea una matriz de codificación que relacione las categorías con segmentos específicos de datos. Esto facilitará la organización y referencia cruzada durante el análisis.

Para el ejemplo previamente mencionado, se tendría que realizar una matriz para cada estado del LED de cada circuito.

Video recomendado:

{{<youtube 4VPbs5tnOY4>}}

5. **Identificación de Patrones y Tendencias.**

Busca patrones, tendencias o relaciones en las categorías y temas identificados. Pregúntate cómo estos patrones contribuyen a la comprensión de tu investigación.

6. **Elaboración de Narrativa.**

Construye narrativas o explicaciones que resuman y den sentido a los resultados. Destaca ejemplos específicos para respaldar tus conclusiones.


Otros videos recomendados:

{{<youtube w8UD6lRAF0E>}}


#### Análisis Cuantitativo

1. **Familiarización con los Datos.**

Lee o escucha los datos en su totalidad para familiarizarte con el contenido. Toma notas preliminares y reflexiona sobre las impresiones iniciales.

2. **Muestreo de Datos.**

Selecciona muestras específicas de datos para un análisis más detallado. Puedes enfocarte en casos extremos, casos típicos o ejemplos que ilustren ciertos patrones.

3. **Visualización de Datos.**

Crea gráficos y visualizaciones, como histogramas, diagramas de dispersión o gráficos de barra, para representar la distribución de los datos y detectar patrones visuales.

Mirar videos: 

{{<youtube 5Zg-C8AAIGg>}}

{{<youtube c2Al5e8yzQQ>}}
 

4. **Tratamiento de Datos.**

- *MEAN SQUARED ERROR*

Una de las funciones primordiales a tener dentro de nuestro repertorio, y que se presenta de gran utilidad al hacer correlación entre datos medidos y calculados, es la *función de Error Cuadrático Promedio* (MSE por sus siglas en inglés):

![imagen](/images/2024/02/18_errorabsolutopromedio.png)

La cual lo definimos como el promedio de las diferencias entre el valor real y el calculado elevados al cuadrado. Entre más grande sea este valor, menos exacto son nuestras predicciones, y, por lo tanto, se debe justificar esa diferencia.

*Caso de uso:* Esta herramienta estadística es muy útil cuando analizamos curvas características de componentes y el cambio de una variable dentro de nuestro experimento con respecto a otra. En el caso de que los valores obtenidos durante un experimento no sea posible calcularlos, debemos investigar en la hoja de datos de los componentes por si existe una tabla o gráfico que nos permita comparar. 

Video útil:

{{<youtube beIgcdf0YDE>}}

- *ERROR RELATIVO.*

Si nuestro experimento consta únicamente de un dato tomado, o, que nuestro interés sea analizar únicamente un tan solo dato, podemos usar la *función Error Relativo*: 

![imagen](/images/2024/02/18_errorrelativo.png)

Esta función nos da un valor porcentual que nos dice que tan desviada está nuestra medición del valor calculado.

- *REGRESIONES*

Puede también ser de gran ayuda tener siempre a la mano métodos de regresión para utilizar en el caso sea necesario. Esto nos ayuda a obtener una función que describa el comportamiento de nuestro fenómeno y a hacer futuras predicciones.

Regresión lineal:

{{<youtube znzV1cyH5Gs>}}

Regresión exponencial:

{{<youtube s85-2syA52A>}}

Existen muchas regresiones, por lo que se debe ver cuál es la más adecuada para describir nuestro fenómeno.

5. **Elaboración de Narrativa.**

Construye narrativas o explicaciones que resuman y den sentido a los resultados. Destaca ejemplos específicos para respaldar tus conclusiones.


### Conclusión.

El análisis de resultados es el paso con mayor relevancia dentro de las prácticas de laboratorio, ya que es este el que les da sentido a los datos, y relaciona la teoría con la práctica.
