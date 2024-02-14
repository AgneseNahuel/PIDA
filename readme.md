#   Proyecto PI DATA ANALYTIC

Proyecto basado en Siniestros Viales!, se busca entender y sacar informacion util con un DataSet .xlsx, a lo largo del trabajo se transforman, acomodan los datos y su utilizacion en PowerBI, leer atentamente el readme.md va a dar al que analiza el Trabajo Practico un paneo general de lo que hice y lo que quise hacer.

#   ETL-EDA

El proyecto fue empezado por la descarga de los archivos .xlsx, el archivo fue leido con Pandas e investigado, primero el ETL, me fue necesario hacer algunas partes del EDA dentro para poder limpiar los datos y hacer un "merge" entre los DataFrames. El EDA fue sencillo, vi que tal estaban los datos y despues pase directo a hacer graficos que me den informacion, mayormente centrado en la variables de "Num víctimas", series de tiempo y la edad...
Todo el ETL fue guardado en un .csv para su utilizacion en PowerBI.


#   PowerBI

El problema de hacer el Dashboard fue con los KPIs, quise contar una historia centrada en las victimas y en el entorno, por eso los mapas que use con las coordenadas, tuve problemas con los datos pero los solucione dentro del programa.
Al no poder hacer el KPI desde metricas decido hacer un KPI desde Visual Studio en una tabla diferente, este me funciona para hacer un tipo de grafico que muestra la tasa de los 3 KPIs que hice.
Consigo hacer con metricas los KPIs despues de mucho esfuerzo, me doy cuenta que los puedo presentar en Tasas o en suma de victimas, el segundo me parecia mas facil de explicar pero el primer KPI pedia la tasa y no la reduccion de victimas como el segundo, asique me mantengo a las consignas y hago el primero con la tasa y los otros 2 con la suma de victimas.

#                                       CONCLUSIONES

- Las victimas en su mayoria son 1 sola.
- En el año 2020 la pandemia afecto positivamente, no habia tantos siniestros por la falta de personas en la calle.
- El 75% de las victimas es menor a 55 años.
- Los hombres victimas son en gran parte desde 20 a 40 años y las mujeres rondando los 60.
- Las Avenidas son los lugares donde mas siniestros hay.
- Los autos son los mas peligrosos.
- El 75% de las victimas son hombres, el 25% mujeres mas o menos.