# Taller-1-Gestion-de-Datos-

Integrantes:</br>
Ana Carolina Rubiano Manrique </br>
Nicolas Andres Rey Ospina</br>
Oscar Alexander Nope Saavedra</br>

</br>
Video: 
</br>

#**Taller 1** 
Univerisdad Javeriana  
August, 2022  

</br>
</br>

Datasets:   
1. Lesiones Personales
2. Violencia Intrafamiliar
3. Delitos Sexuales
4. Homicidios

</br>

**Punto 1.** 
**Seleccione al menos 4 conjuntos de datos y realice un perfilamiento de cada uno. Describa los hallazgos encontrados en cada conjunto de datos. No olvide mencionar su estructura y aspectos relevantes de calidad como campos nulos, departamentos mal escritos, formatos de fechas incorrectos, entre otros. Si no evidencia ningún problema de calidad de datos, también mencionelo.** </br>

R/ Para el desarrollo de este taller se escogen los siguientes dataframes: Lesiones Personales, Violencia Intrafamiliar, Delitos Sexuales y Homicidios Accidente de Transito. 

Para cada uno de estos data frames se tienen en su gran mayoría variables categoricas nominales y ordinales con la unica excepción de la 'CANTIDAD' la cual es la cantidad de delitos realizados (Variable escalar)

De igual manera se revisan cada uno de los campos tratando de identificar datos anomalos. Para estos se crean diccionarios especificos con el objetivo de reemplzar dichos valores. Para los datos nulos se reportan como "NO REPORTADO". 

Por ultimo, se estandariza el formato de la fecha. 

</br>
</br>

**Punto 2**
**Responda la siguientes preguntas para cada uno de los conjuntos de datos seleccionados:**

**2.1 ¿Cuáles han sido los departamentos (TOP 3) más afectados en términos de cantidad de delitos cometidos en los últimos 5 años?**</br>
</br>
R/ Para cada uno de los delitos escogidos, al analizar en un rango de los ultimos 5 años se encuentra que los principales departamentos, en cada una de estos delitos, son: CUNDINAMARCA, ANTIOQUIA y VALLE. 

**2.2 Para los casos en los que aplique, ¿cuál ha sido el arma o medio más común para cometer el delito?**</br>
</br>
R/ De los delitos escogidos se podía realizar el análisis acerca de solamente tres de ellos: Lesiones Personales, Violencia Familiar y Delitos Sexuales. 

* Para los data frame de Lesiones Personales se encuentra que las armas mayormente utilizadas en este tipo de delitos son armas contundentes.
* Para los delitos sexuales se encuentra que para la mayor cantidad de estos delitos fueron sin utilizar armas. 

**2.3 Para los casos en los que aplique, ¿cómo ha sido la proporción de géneros y grupos etarios que han estado involucrados en este tipo de delito? ¿Han variado con el paso de los años?**</br>
</br>
R/ Para cada uno de los dataframes analizados se evidencia que las personas del genero masculino han sido los mas involucrados en este tipo de delitos. Estos a lo largo de los años se han venido incrementando con la excepción que desde el año 2018 se evidencia una disminución. Este mismo comportamiento se evidencia con los ADULTOS con la variable de GRUPO ETARIO. 

**2.4 ¿Se evidencia alguna tendencia para cometer dicho delito en algún mes particular del año?**</br>
</br>
R/ Parece haber una tendencia en que estos tipos de delitos tienen su pico en el primer trimestre del año, aunque no es una diferencia muy grande comparado con los demas meses. 

Otro tema particular identificado es relacionado con los Homicidios por Accidente Transito, los cuales aparte de tener una mayor incidencia en la primera parte del año presentan un incremento en el mes de Diciembre siendo uno de sus meses mas altos. (Puede que este incremento se este dando por las fiestas de fin de año.

**2.5 Para los casos en los que se disponga del detalle del delito o de una descripción, como por ejemplo en delitos sexuales y secuestro, ¿cuáles son las descripciones o modalidades más comunes?**</br>
</br>

R/ ependiendo de los delitos se tienen las siguientes descripciones principales:
* Lesiones Personales
* Actos Sexuales con menores de 14 años
* Homicidio Culposo en accidente de transito

</br>
</br>

**Punto 3**</br>
**A partir de alguno de los conjuntos de datos seleccionados, visualice una serie de tiempo por año y mes que permita comparar la cantidad de delitos cometidos para los departamentos con mayor ocurrencia durante los últimos 5 años. Para que los resultados entre departamentos sean comparables, es importante que normalice las cantidades obtenidas por cantidad de habitantes. En este archivo puede encontrar la población por departamento para el año 2018. Asuma que la población no ha cambiado con el paso de los años.**
</br>
Del DataSet de delitos sexuales se observa que los departamentos con mayor cantidad de delitos son los siguientes:
Antioquia, Cundinamarca y Valle, esto se mantiene durante los últimos 5 años.
También podemos decir que en todos los departamentos la tendencia ha bajado en el último año.
</br>

**Punto 4**</br>
R/ En seguida los valores percapita de delitos en los municipios con población mayor o igual a 1'000.000 de habitantes para los delitos registrados en lo corrido del año 2022: 
* En el municipio de MEDELLÍN (CT), por cada 216 habitantes se presenta un delito.
* En el municipio de BARRANQUILLA (CT), por cada 167 habitantes se presenta un delito.
* En el municipio de CARTAGENA (CT), por cada 257 habitantes se presenta un delito.
* En el municipio de BARRANQUILLA (CT), por cada 285 habitantes se presenta un delito.

</br>
