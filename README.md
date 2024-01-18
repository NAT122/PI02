PI-02 Analisi de Siniestros viales en CABA 2016-2021

El trabajo consiste en el análisis de los siniestros viales ocurridos en CABA entre los años 2016 y 2021. Se toman los datos a partir de la información recopilada por la Secretaría de Transporte, Subsecretaría de Planificación de la Movilidad , y Observatorio de Movilidad y Seguridad Vial de Buenos Aires. (https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales). También se tomaron datos de población de CABA a partir de las proyecciones de la  Dirección General de Estadística y Censos (Ministerio de Hacienda GCBA), para los años 2010/2025.(https://www.estadisticaciudad.gob.ar/eyc/?p=28146).
En el desarrollo del proyecto, se utilizó Python para llevar a cabo un proceso de Análisis Exploratorio de Datos (EDA), haciendo uso de las librerías Matplotlib y Seaborn para las visualizaciones. También se llevó a cabo un proceso de Extracción, Transformación y Carga (ETL) para manejar los valores vacíos que aparecían como 'SD' en el archivo de datos, sustituyéndolos por nulos o por -1 según fuera necesario. Posteriormente, estos datos fueron cargados en una base de datos en SQL Workbench, la cual se conectó con Power BI.


 A partir del análisis de los datos se llega a la conclusión de que un factor determinante en la cantidad y frecuencia de accidentes es la cantidad de circulación en la zona, y el tipo de circulación con cruces de distintas vías, vehículos y peatones. Se observa a partir del análisis que predominan los accidentes en avenidas importantes internas y sus distintos cruces de estas, por sobre los ocurridos en autopistas o vías rápidas donde la circulación es más controlada. Por lo que se entiende que el mayor cantidad de accidentes son dentro de la ciudad, urbanos, en los espacios de mayor circulación de vehículos y personas. Al analizar las víctimas y los participantes de los siniestros se observa que en su mayoría las víctimas son motos (conductores) y peatones, involucrados en accidentes con automóviles. Siendo estos los grupos más vulnerables en los siniestros viales urbanos por la naturaleza de los vehículos y su circulación en la ciudad. Los principales acusados como causantes del siniestro son autos y peatones, indicando que la mayoría de estos accidentes ocurren en zonas de muchos tránsitos de distintas vías de circulación interna, vehículos y peatones.
  
 ![Captura de pantalla 2024-01-16 182328](https://github.com/NAT122/PI02/assets/126476995/5a54bee2-0a32-4df6-ae10-2e978f75eb59)

Se obserba como la mayor concentracion de accidentes ocurre en la zona de comuna 1 (barrios de Retiro, San Nicolás, Puerto Madero, San Telmo, Monserrat y Constitución) y la avenida 9 de Julio, una de las pricipales vias de circualcion de vehiculos, trasporte publico y cruces con otras vias y circulación de peatones.
![Captura de pantalla 2024-01-16 191833](https://github.com/NAT122/PI02/assets/126476995/96c601d8-8559-457e-9aa6-3b75e440b6f1)

Comparando la cantidad de accidentes anuales se ve que en años con menos cantidad de siniestros fue el 2020, coincidiendo con la menor circulación de gente en las calles por la cuarentena y aislamiento. Se observa también un descenso de los accidentes en los últimos años durante los meses de enero y febrero coincidiendo con el receso escolar, la menor cantidad de gente en la ciudad y el descenso de circulación de temporada. Concluyendo que al haber menos circulación en Caba se disminuyen los accidentes. 

KPI analizados:
 El KPI propuesto de reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses en comparación con la tasa de homicidios en siniestros viales del semestre anterior, fue alcanzado con éxito y superado. La tasa de siniestros viales se redujo un 15% más de lo propuesto por el kpi.
 
![Captura de pantalla 2024-01-16 182413](https://github.com/NAT122/PI02/assets/126476995/0664e69a-e609-4949-8cf3-2add4592a21c)

Por otro lado, el KPI propuesto reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, respecto al año anterior no sé alcanzó. Los accidentes totales  en comparación entre el 2020 y el 2021 aumentaron un 70%, particularmente a principios del año 2021. 

![Captura de pantalla 2024-01-16 182258](https://github.com/NAT122/PI02/assets/126476995/6661ab1d-8fb3-420a-8bba-1b0875182c9c)

Este aumento se debe relacionar con la disminución de la circulación del 2020 a raíz de las primeras medidas de aislamiento de ese año, y el cambio de estas en el transcurso del 2021.  También con la recepción de estas por parte del público, la cual se modificó desde el inicio del 2020 al final del año, y durante el 2021. Esto también explica la diferencia entre la cantidad de accidentes durante diciembre en ambos años. Si bien la cantidad total de accidentes anuales aumentó, particularmente en diciembre del 2021 los accidentes disminuyeron 19% más de lo esperado en comparación del mismo mes en 2020. Lo cual también explica la reducción de la tasa total de accidentes entre el primer semestre del año 2021 y el último. 

Entonces como análisis final se llega a la conclusión de que los factores más determinantes en la cantidad y frecuencia de los siniestros viales es la cantidad y el comportamiento de vehículos y peatones que circulan en la zona. Lo que se evidencia con el análisis del comportamientos de los KPIs, teniendo cantidades de accidentes mucho menores en 2020 y en momentos de restricción de la circulación que en otros momentos. 

