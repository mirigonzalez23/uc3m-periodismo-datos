# Creación de gráficos desde Datawrapper

Base de datos: Suicidios por comunidades y ciudades autónomas de defunción, sexo y edad. 

Enlace: https://datos.gob.es/es/catalogo/ea0010587-suicidios-por-comunidades-y-ciudades-autonomas-de-defuncion-sexo-y-edad-ecm-identificador-api-t15-p417-a2020-l0-06004-px

## Procedimiento gráfico 1:

En la base de datos seleccionada  se  muestran los datos de suicidio por ciudades y comunidades autónomas de defunción a partir de una segregación de la edad y el sexo de los afectados. 
En el gráfico final se pretende hacer una comparativa entre los suicidios de hombres y mujeres en las distintas ciudades y comunidades autónomas. Por este motivo, lo primero que hacemos es eliminar los datos del total nacional. (editar filas, marcar la estrella de las celdas vinculadas al total nacional y eliminamos coincidentes.)

Así bien, en el gráfico compararemos  los suicidios entre hombres y mujeres en las distintas comunidades autónomas. De esta forma,  es conveniente eliminar la casilla de ambos sexos. (faceta por texto, “ambos sexos”,eliminar filas coincidentes)

Por otro lado, aplicamos otra faceta de texto para eliminar las celdas referidas a los rangos de edad. Para ello realizamos la misma mecánica (faceta por texto, “todas las edades”, esta vez clicamos en invertir para eliminar las contrarias y, por último, eliminamos coincidentes)

Una vez segregados los datos, tenemos que modificar los nombres de las celdas para evitar que en el gráfico salgan duplicadas las comunidades autónomas y, al mismo tiempo, conseguir diferenciar textualmente los datos de hombres de los datos de mujeres. Para ello utilizamos la faceta de texto en la columna de sexo y ponemos “hombres”. Tras esto “unimos celdas” y añadimos la palabra “hombres'' a la celda de la comunidad autónoma. (En este paso separamos el contenido de ambas celdas con un guión (“-”)).  Posteriormente, repetimos la misma operación con las mujeres. Tras haber unido el contenido de las dos columnas, elimanos la columna de sexo.
En la columna de ciudad y comunidad autónoma creamos una nueva faceta de texto y buscamos “mujeres”. En las celdas vinculadas a las cifras de suicidios en mujeres dejamos únicamente las letras iniciales de las distintas comunidades autónomas .
Volvemos a utilizar una nueva faceta de texto en la misma columna, esta vez para buscar a los hombres. Ahora bien, al contrario que en las celdas de las mujeres, en las de los hombres mantendremos el nombre completo de la comunidad autónoma y dejamos solo la “h·” de hombre.
Llegados a este punto, realizamos nuestro gráfico en Datawrapper.  En donde escogemos un gráfico de columnas para facilitar la comparativa entre los datos de hombres y mujeres. En la pestaña de “refinar” personalizamos los colores de las columnas. (Rosa para los datos de mujeres y azul para los datos de los hombres.)
En la pestaña de “Anotar” añadimos el título y la descripción a nuestro gráfico. Por último,  destacamos la cifra más alta de suicidios en la casilla de “elementos destacados”.  (Los hombres andaluces, 591). Este dato será explicado en una nota a pié de gráfico.

## Explicación gráfico 1:

![Gráfico 1](https://github.com/mirigonzalez23/uc3m-periodismo-datos-miriam/blob/fd6e9a1239d816b4342a6026f9497cd7354cb8d5/imagenes/Gr%C3%A1fico%201.%20El%20suicidio%20en%20Espa%C3%B1a%20a%C3%B1o%202020.png)

Tal y como hemos mencionado en el procedimiento, este gráfico tiene la intención de mostrrar la disparidad de las cifras de suicidio entre las distinas comunides y ciudades autónomas de España en función del sexo de los afectados .

Por este motivo, las columnas de las mujeres suceden a las columnas de los hombres de su misma comunidad autónoma. Esto hace que sea más sencilla la comparación de las cifras referentes a la misma ciudad o comunidad autónoma.
Entre tanto, la presencia de todos los datos en una misma gráfica facilita la comprensión total de la situación de España en materia de suicidios.
El tipo de gráfico escogido en un gráfico de columnas. Considero que este gráfico es el idóneo para la representación de las cifras disponibles ya que permite visualizar el dato concreto, así como interpretar la situación particular de cada comunidad, a partir de una comparativa con el resto de las columnas del gráfico.
También quería que el gráfico destacara el grupo poblacional que más se suicidó en España en el año 2020. Tal y como se aprecia en el gráfico, este grupo es el de los hombres andaluces.
Finalmente, los colores escogidos son el azul y el rosa. Son los colores asignados como estereotípicos del género masculino y femenino respectivamente. Por lo que la comprensión de este gráfico por parte de la ciudadanía será rápida y sencilla.


## Procedimiento gráfico 2:

En primer lugar, llevaremos a cabo el mismo procedimiento que en el gráfico primero a la hora de realizar la limpieza de datos. En esta ocasión eliminaremos los datos de “ambos sexos”, así como los de las distintas comunidades autónomas mediante la herramienta de “faceta” que nos ofrece openrefine. (faceta por texto y eliminar coincidentes). 

Los datos seleccionados se refieren al total nacional por edad tanto de hombres como de mujeres en función de los distintos grupos de edad.

Así bien, la opción de editar columnas permite ordenar más fácilmente los datos disponibles. De este modo, hemos movido las distintas columnas antes de traspasar los  datos a datawrapper, esto  favorecerá la visualización de datos. 

Una vez ordenados los datos, en datawrapper escogeremos un gráfico de tipo “barras apiladas” para facilitar la comparación de los datos. En la pestaña  de “refinar” seleccionamos el formato numérico de 1,000 para una mejor presentación de las cifras. Finalmente, en la pestaña “anotar” escribimos el título y la descripción del gráfico

## Explicación gráfico 2:

![Gráfico 2](https://github.com/mirigonzalez23/uc3m-periodismo-datos-miriam/blob/2e187c0165ef865182d2778f216633080635ec7e/imagenes/Gr%C3%A1fico%202.%20Las%20cifras%20del%20suicidio%20en%20Espa%C3%B1a.png)

Este segundo gráfico contrasta las cifras totales de suicidio en España en hombres y mujeres según los distintos grupos de edad.

El gráfico de tipo “barras apiladas” no solo muestra las crifras de suicidio en los distintos grupos de edad, sino que también permite contrastar la diferencia en cantidad de suicidios entre hombres y mujeres en función de la amplitud de las 2 barras contrapuestas. Esta doble función ha hecho que considere a este modelo de representación como el idóneo para representar los datos seleccionados.

La visualización de las cifras de suicidio en España según los distintos grupos de edad, es, desde mi punto de vista, algo muy importante. Puesto que esto es una información muy valiosa a nivel sociológico. Ya que sabiendo quienes son los grupos de edad que más se suicidan, podemos comenzar un estudio sobre las distintas problemáticas sociales que promueven estos suicidios.

Por otro lado, esta vez ha sido la intención estética lo que ha guiado la selección de los colores del gráfico. El hecho de escoger dos tonalidades diferentes de azul impide realizar una asociación directa entre el  color y el grupo que representa, por lo que he considerado imprescindible la utilización de una leyenda.

Por último, en contraposición al gráfico de columnas, en este caso no vemos cómo ascienden los datos a una determinada cifra, por lo que la presencia de los datos dentro de las distintas barras favorece la comprensión de la situación y aportar valor al gráfico.

