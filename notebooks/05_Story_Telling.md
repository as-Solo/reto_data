## INTERPRETANDO LOS DATOS

#### Lo primero fue ver la relación que podría haber entre los distintos datos ofrecidos por el csv y el consumo, queríamos ver, cómo se relacionaban entre sí y en concreto cómo se relacionaban con el consumo.
![correlaciones](https://github.com/as-Solo/reto_data/blob/main/img/correlaciones.jpg)


#### Para hacernos una idea mejor decidimos ver cómo se distribuían los consumos atendiendo a la velocidad y a la temperatura exterior, que fueron dos fuentes de datos que mayor influencia mostraron en un análisis exploratorio previo con respecto al consumo. Al darnos cuenta de que esta distrubución podía segmentarse en rangos tanto para la velocidad como para la temperatura, creamos nueva información en rangos para ambos valores y mostramos los resultados en gráficos. Se llegó a la conclusión de que las temperaturas exteriores por debajo de los diez grados y las velocidades inferiores a 30 km/h, afectaban al consumo de manera negativa, haciendo que estuviesen por encima de la media. Observamos los fenómenos climáticos y descubrimos que la nieve era un factor muy relevante, siempre que se usase el climatizador del coche, pero que éste, el climatizador, no afectaba en otros momentos como la lluvia o el sol de manera desproporcionada, por lo que descartamos el uso del aire acondicionado o de la calefacción como un factor determinante. Además calculamos la media de emisiones de CO2 atendiendo a la velocidad y pudimos corroborar que estaban dentro de los mágenes legales y de buen funcionamiento de los motores.
![consumos](https://github.com/as-Solo/reto_data/blob/main/img/Consumos.jpg)
Hicimos una comparativa del consumo medio por rangos de velocidad atendiendo al tipo de combustible. En ambos casos, los dos combustibles tenían un comportamiento muy similar, aunque el combustible E10 se comportaba de manera más regular, pese a consumir más en la franja de 30 a 60 km/h. Los máximos y los mínimos de consumo se encontraban en la gráfica del combustible SP98. Y mientras en la franja habitual el combustible E10 generaba más consumo, en el resto de franjas estaba por debajo de los valores del SP98.
![consumo_velocidad](https://github.com/as-Solo/reto_data/blob/main/img/Consumo_velocidad_combustible.jpg)

Quisimos ver en qué se traducía ese consumo en gasto, y obviamente al ser un combustible más barato el rendimiento del E10 resultaba mucho más ventajoso en todos los aspectos, compensando la posible diferencia que pudiese haber en la franja más común de velocidad que era la de 30 a 60 km/h.
![gasto_velocidad](https://github.com/as-Solo/reto_data/blob/main/img/Gasto_velocidad_combustible.jpg)

También por curiosidad nos fijamos en el gasto real, no el gasto medio, que se había hecho con ambos combustibles. Y descubrimos que en viajes largos, donde la velocidad es mayor puede dispararse con el combustible E10.
![gasto_absoluto_velocidad](https://github.com/as-Solo/reto_data/blob/main/img/Gastoabs_velocidad_combustible.jpg)

Para poder dar valor a la conjetura anterior, medimos la distancia total que se había recorrido a distintas velocidades con ambos carburantes. Nos dimos cuenta de que no había un exceso de distancia en velocidades superiores a los 60 km/h que justificase la gráfica anterior, por lo que verificamos que los trayectos con nieve y climatizador, factor que había aumentado el consumo en gráficas anteriores, se había realizado con el combustible E10.
![relacion_tiempo](https://github.com/as-Solo/reto_data/blob/main/img/Relacion_tiempo.jpg)

Por último quisimos cerciorarnos de cuánto tiempo estaban los coches de la flota circulando en los distintos rangos de velocidad, para poder determinar qué combustible sería el idóneo para la labor de los coches.
![relacion_distancia](https://github.com/as-Solo/reto_data/blob/main/img/Relacion_distancia.jpg)

Con los datos reflejados y teniendo en cuenta el comportamiento de la flota, si se quiere apostar por el uso de combustible en situaciones ideales se aconsejaría utilizar SP98, los trayectos son en su mayoría dentro de la franja de los 30-60 km/h y éste combustible da unos resultados mejores en esta franja de velocidades.

Una postura más conservadora, donde te asegures que el margen de gasto no se va a disparar sería usar el carburante E10, no sólo se comporta de manera más regular, independientemente de las velocidades, de manera muy notable en velocidades bajas (los atascos son frecuentes en las grandes ciudades), sino que además al ser el precio inferior hace que el gasto total quede dentro de una horquilla razonable.
