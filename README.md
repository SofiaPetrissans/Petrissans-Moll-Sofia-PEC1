# Petrissans-Moll-Sofia-PEC1

## Resumen
El siguiente informe detalla el análisis de un dataset de metabolitos en pacientes que presentan caquexia y pacientes controles.
El proceso ha consitido en la elección de un dataset, la descarga de los datos y la creación de un contendeor de tipo `SummarizedExperiment`.

El análisis para obtener una visión general de los datos, ha consitido en la descripción de los datos y metadatos de nuestro objeto, seguido de una descripción de grupos. Un análisis de PCA para explorar la variabilidad de los datos junto a su visualización y por último, gráficos boxplot para observar la diferencia de los metabolitos medidos entre los dos grupos.

## Datos
Los datos fueron obtenidos del siguiente repositorio https://github.com/nutrimetabolomics/metaboData/. Los metadotos estaban incluidos en las primeras dos columnas (Patient.ID y Muscle.loss) del dataset por lo que, como se muestra en el scrip
'PEC_1.Rmd', primero se dividieron los datos que aportaban información cualitativa de los que aportaban información cuantitativa. Para más información de los datos puedes consular el archivo 'metadatos.Rmd'. 
