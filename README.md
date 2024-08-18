# FDS-2024-1-CC53
# Objetivo del proyecto.
El presente proyecto se llevará a cabo debido a que una consultora tiene la intención de desarrollar un proyecto de analítica destinado a estudiar las tendencias de los videos en YouTube. Esta iniciativa responde a la necesidad de una empresa de marketing de obtener información específica para satisfacer sus requisitos. Se utilizarán datos procedentes de 4 países con el fin de analizar y responder a preguntas clave sobre las tendencias observadas en cada uno de esos mercados.

# Nombre de los alumnos participantes.
* U20201F678 - Joaquin Sebastian Ruiz Ramirez
* U202218811 - Andrés Eduardo Carbajal Rojas
* U20201F576 - Jimena Alexsandra Quintana Noa
* U20221C488 - Freddy Alejandro Cuadros Contreras
* U202211514 - Juan Pablo Julian Guija Solis

# Breve descripción del conjunto de datos (se puede adjuntar el archivo PDF).
| **Nombre**|**Descripcion**|
|-----------|---------------|
| `video_id`         | identificador del video      |
| `trending date`    | fecha del video cuando entró en tendencia |
| `title`            | título del video             |
| `channel_title`    | nombre del canal de youtube  |
| `category_id`      | identificador del video      |
| `publish_time`     | fecha cuando se publicó el video |
| `tags`             | temáticas que se relacionan con el video |
| `views`            | cantidad de vistas           |
| `likes`            | cantidad de likes            |
| `dislikes`         | cantidad de dislikes         |
|`dislikes`|cantidad de dislikes|
|`comment_count`|cantidad de comentarios|
|`thumbnail_link`|	url de la miniatura|
|`comments_disabled`	|comentarios habilitados|
|`ratings_disabled`|	si el video no puede recibir puntaciones|
|`video_error_or_removed`|	si el video a sido removido o tiene errores|
|`description`|	descripcion del video|
|`state`	| nombre del estado perteneciente al país|
|`lat`|	latitud geografica|
|`lon`|	longitud geografica|
|`geometry`|coordenadas geometricas|
# Requerimientos
1.	¿Qué categorías de videos son las de mayor tendencia?
![](/img/Pregunta1.png)
2.	¿Qué categorías de videos son los que más gustan? ¿Y las que menos te gustan?
![](/img/Pregunta2.png)
3.	¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”?
![](/img/Pregunta3.png)
4.	¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” / “Comentarios”?
![](/img/Pregunta4.png)
5.	¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?
![](/img/Pregunta5.png)
6.	¿Qué canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?
![](/img/Pregunta6.png)
7.	¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?
![](/img/Pregunta7.1.png)
![](/img/Pregunta7.2.png)
![](/img/Pregunta7.3.png)
8.	¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta”?
![](/img/Pregunta8.png)
9.¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?
![](/img/Pregunta9.png)
# Conclusiones.
La categoría de música domina en YouTube en los cuatro países analizados (Canadá, Francia, Gran Bretaña y Alemania), liderando en vistas, "me gusta" y tendencias. Esto indica una clara preferencia de la audiencia por este tipo de contenido y sugiere que las estrategias de marketing deberían enfocarse en esta categoría para maximizar el alcance y la interacción.

En 2018, se observó una disminución en la cantidad de videos que alcanzaron tendencia en YouTube. Sin embargo, esta tendencia no fue constante, ya que hubo picos de recuperación a lo largo del tiempo, lo que indica que, aunque hubo una disminución general, el interés por los videos en tendencia se mantuvo en ciertos momentos del año.

La categoría "Mascotas y Animales" se destaca por tener la proporción más alta de "Me gusta" en comparación con "No me gusta", lo que sugiere que este tipo de contenido es bien recibido por la audiencia y genera una respuesta positiva.

En cuanto a la relación entre "Vistas" y "Comentarios", la categoría "Shows" lidera, indicando que este tipo de contenido, aunque popular en términos de visualizaciones, no genera tantos comentarios como otras categorías, lo que podría ser relevante para entender la participación de la audiencia y la interacción con este tipo de videos.

El análisis de los datos revela que el número de vistas de un video influye significativamente en la cantidad de "me gusta", "no me gusta" y comentarios que recibe. Además, se observa una relación positiva entre los "me gusta" y los comentarios, lo que sugiere que los videos que reciben más "me gusta" tienden a generar más comentarios, mientras que los "no me gusta" tienen una relación negativa con los comentarios.

En cuanto a la predicción de métricas, el modelo más preciso es el de "no me gusta", lo que indica que esta variable es más predecible en comparación con las vistas, comentarios y "me gusta". Esto podría ser útil para identificar patrones y factores que influyen en la respuesta negativa de la audiencia hacia ciertos videos.


# Licencia de uso.
