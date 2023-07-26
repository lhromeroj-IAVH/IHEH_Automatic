# IHEH_Automatic
Este es un ejercicio (en desarrollo) para automatizar el proceso de cálculo del Índice de Huella Espacial Humana siguiendo la metodología de Correa-Ayram et al. (2019)

# Introducción
El Índice de huella espacial humana fue creado para para evaluar la variación espacio-temporal de los impactos antrópicos en Colombia para los años 1970, 1990, 2000 y 2015. Este índice se compone principalmente de dos dimensiones espaciales: 1) la intensidad de uso de la tierra, y 2) el tiempo de intervención humana sobre los ecosistemas. La intensidad de uso de la tierra se define como el nivel de modificación del hábitat debido a la extracción de recursos y los usos de la tierra predominantes. Por otro lado, el tiempo de intervención humana es la duración del tiempo en que el paisaje ha sido sujeto de actividades humanas, estimado de mapas históricos de los años 1500, 1600, 1900 y mapas recientes de 1970 (Figura 1).


![Metodologia_IHEH](https://github.com/lhromeroj-IAVH/IHEH_Automatic/assets/84154963/ba0ec1d3-091d-4bbb-a97d-8a1fbc5f901e)


**Figura 1:** Metodología para el cálculo de Índice Legado de Huella Espacial Humana. Fint corresponde a la intensidad de uso de la tierra y Ftime al tiempo de intervención humana sobre los ecosistemas. LU: Land Use, PD: Population Density, DS: Distance to Settlements, DR: Distance to Roads, FI: Fragmentation Index, BI: Biomass loss index, TI: Time of Intervention.

# Contexto 
Este repositorio fue creado principalmente para identificar insumos actualizados con los que replicar el cálculo de la huella espacial humana, siguiendo la metodología de Correa-Ayram et al. (2019). La metodología de reclasificación a valores de huella de cada uno de sus componentes se replicó de acuerdo con la metdología original, pero se observan marcadas diferencias en los resultados obtenidos por esta modelación propuesta y los datos de la metodología original para el año 2018. Con esta primera versión del código se espera identificar las diferencias entre los métodos utilizados para el cálculo de la huella espacial humana, y así poder identificar estrategias para mejorar el proceso de automatización. 


