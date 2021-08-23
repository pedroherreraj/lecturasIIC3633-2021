## Comentario: Collaborative Filtering Recommender Systems

El texto trata sobre Collaborative Filtering, que es un proceso en que se evaluan y/o filtran elementos utilizando la opinión de otra gente. Es lo más parecido al proceso de recomendación de boca-en-boca, pero computarizado. El paper habla sobre los inicios de este sistema de recomendación en la web, como fue evolucionando, los usos que se le da, los distintos algoritmos que utiliza(*user-based nearest neighbor* y *item-based nearest neighbor*), como obtener ratings(implicitos y explicitos), los problemas que este sistema enfrenta,y finalmente cierra con preguntas importantes del tema sobre las cuales se estan realizando investigaciones.

Me gustó que hayan contado la historia de este sistema recomendador para entender porque esta así en este momento. 

Es clave que se mencione los distintos usos que se le puede a este sistema, como también las propiedades que tienen que tener los dominios en que se quiere aplicar para que funcione bien, ya que sino el paper sería incompleto. 

Me gusto también de que se hable un poco sobre el *content-based filtering*, ya unir ese sistema con el que presentan en el paper generaría un sistema recomendador sumamente robusto.

En mi humilde opinión, creo que el autor se equivoco al escribir una formula, y eso es algo sumamente grave. En la página 304, en la fórmula 6, está multiplicando la sumatoria por *R<sub>ui</sub>*, y debería ser *R<sub>uj</sub>*, ya que el *i* es el item que se estaba buscando predecir su rating.

Me hubiera gustado que el autor hubiera explicado porque el tamaño del modelo puede ser como máximo el cuadrado del número de elementos que posee(pag 305)

Me gustaron las preguntas de cierre, ya que me hacen reflexionar sobre el algoritmo y quizás como solucionar los problemas presentes en las preguntas

En resumen, el paper me gusto bastante, cubría ampliamente el tema del CF, pero me hubiera gustado quizás un poco más de explicación en ciertas partes del texto, como también que la fórmula mencionada más arriba no presentase un error
