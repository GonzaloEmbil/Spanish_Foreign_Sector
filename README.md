# Analysis of the Spanish foreign sector between 1940 and 1959

En este repositorio se encuentran scripts y datasets que nos permiten analizar diferentes aspectos de la industria del aguacate en México, como su producción y exportación.

Se utilizaron distintas bases de datos abiertos:

* SIAP: Contiene información de la producción anual de diversos cultivos. (http://infosiap.siap.gob.mx/gobmx/datosAbiertos_a.php)

* INEGI (BCMM): Contiene información anual detallada de las exportaciones de México. (https://www.inegi.org.mx/programas/comext/#datos_abiertos)

* Banxico: Contiene información mensual simple de las exportaciones de México. (https://www.banxico.org.mx/SieInternet/consultarDirectorioInternetAction.do?sector=1&accion=consultarCuadro&idCuadro=CE37&locale=es)


## PIB

El aguacate es considerao por muchos como "el oro vede de México". En la siguiente gráfica podremos conocer su valor respecto al Producto Interno Bruto.

![PIB](Visuals/PIB_Spain_UnitedStates_GreatBritain_France.png)

Podemos notar que con el paso de los años, el valor del aguacate ha aumentado.

Un detalle importante de recordar es que el PIB está conformado por cientros de actividades económicas.

Veamos la misma gráfica pero ahora comparando solamente con la agricultura.


## Exports and Imports as % of PIB

Se dice que Michoacán es donde más se produce aguacate, y es verdad.

![%PIB](Visuals/Exports_Imports_as_%_of_PIB.png)

Durante el 2023, el estado de Michoacán fue responsable del 75.76% de toda la producción de aguacate en el país, lo que equivale a 3 de cada 4 aguacates.


## Structure

De acuerdo a las cifras del INEGI, durante el 2023 se exportaron 1.3 millones de toneladas de aguacate mexicano a 35 países y territorios.

![Imports Structure](Visuals/Imports_Structure.png)

El anterior gráfico se le conoce como un mapa binario, donde solo se muestran los países que recibieron aguacate, independientemente de la cantidad.

La cantidad de aguacate por país la concoeremos a continauación.

![Exports Structure](Visuals/Exports_Structure.png)

En 2023, Estados Unidos importó el 80% de todos los aguacates que México exportó.

Sin embargo, esto no fue siempre así, la distribución del 2004 está más equilibrada.


## Origins and Destinations

El precio del aguacate al consumidor final y el precio que recibe el productor no es el mismo.

De hecho la diferencia es bastante considerable.

![Precio medio rural](./imgs/precio_medio.png)

Los consumidores suelen pagar el doble (o aveces el triple) de lo que reciben los productores por cada kilgramo de aguacate.

![Precio](./imgs/precio_mensual.png)

La gráfica anterior nos muestra que el precio del aguacate es suceptible a estacionalidad y que ha llegado a tener valores muy altos en estos últimos años.

## Conclusión

En este proyecto traté de analizar la mayor cantidad de aspectos posibles con la información libremente disponible.

Aún hay mucho máas que explorar y aprender. Esa es la razón por la cual he compartido todo el código fuente.

Espero que les hayan gustado las visualzaciones y les sirvan como ejemplo para sus futuros análisis.
