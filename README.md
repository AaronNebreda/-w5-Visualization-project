# w5-Visualization-project

![imagen](https://github.com/AaronNebreda/-w5-Visualization-project/blob/main/img/portada.jpg)
“Copyright CRDO Ribera del Duero”


## Objetivo


El objetivo principal de este proyecto es realizar una visualización de la información más relevante de los datos obtenidos en la ETL del proyecto anterior o de una nueva.


## Desarrollo

Para este proyecto se fijo el objetivo concreto de crear un dashboard mediante **Power BI**, en el que se muesta un análisis de la producción vitícola en la Ribera del Duero.

1️⃣ Se realizó un pequeño proceso ETL:

   1. ⛏  Extración de la información de la web https://www.riberadelduero.es/ 
   2. ⚙  Transformación de las tablas para facilitar el manejo de los datos. [preparacion.ipynb](https://github.com/AaronNebreda/-w5-Visualization-project/blob/main/src/preparacion.ipynb)
   3. 💾 Guardar los datos en ficheros para poder cargarlos en Power BI.
   
   
2️⃣ Se cargó la información en Power BI, y se creo el dashboard que presenta las estadísticas extraidas. [ribera_duero.pbix](https://github.com/AaronNebreda/-w5-Visualization-project/blob/main/presentacion/ribera_duero.pbix)

   
3️⃣ Puede seguir el dashboard a través del siguiente texto que describe el *storytelling.


## Storytelling

##### 📈 PÁGINA 1

La denominación de origen Ribera del Duero es una de las más importantes de las 96 D.O. de vinos que existen en España. Se encuentra en Castilla y León dentro de una franja de la cuenca del río Duero, donde confluyen las provincias de Burgos, Valladolid, Soria y Segovia.
En el año 2021  comprende una superficie de viñedo inscrita de 25.035 ha repartidas en 109 municipios. Como se puede observar la mayoría está en Burgos con casi  3/4 partes de la superficie total de viñedo.

*(en está página se puede filtrar por provincia o explorar de forma interactiva a traves del mapa o la gráficas)


##### 📊 PÁGINA 2

Si estudiamos la evolución en materia de superficie inscrita a lo largo de los últimos 25 años, se observa una tendencia ascendente. Aunque se puede ver una disminución progresiva del número de viticultores desde el año 2014. Una posible causa es que los pequeños viticultores están abandonando el campo en favor de los grandes viticultores, es decir, la tendencia es que se reparten el campo entre menos viticultores.

En la Ribera hay 6 variedades de uva diferentes, todas ellas tinta excepto la albillo mayor. Pero entre todas las variedades la más predominante es la tinta del país o tempranillo.

Si observamos la evolución para cada una de ellas destaca la clara tendencia negativa de la garnacha tinta, y la casi desaparición de cualquier otra variedad de uva fuera de estas 6, ya que a principio de siglo existía una considerable proporción de otras variedades.

*(en esta página se puede filtrar por años y por variedad de uva para ver como evoluciona cada una de ellas)


##### 📉 PÁGINA 3

Por último, la producción de uva durante los 30 últimos años describe una tendencia ascendente aunque existe una gran oscilación interanual, así como ocurre con el rendimiento de cada año. Probablemente estas oscilaciones se deban a otras variables como las condiciones climatológicas, sería interesante analizarlo con más detalle.

Si se observa la producción por cada variedad de uva, también muestran estas oscilaciones interanuales, aunque no todas lo hacen de la misma  manera. Sería interesante ver qué variables se correlacionan con esas oscilaciones y ver cómo afecta a cada variedad de uva.

*(en esta página se puede filtrar por años y por variedad de uva para ver la producción de cada una de ellas)

