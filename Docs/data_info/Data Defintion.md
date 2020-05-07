# Transformaciónes y caracteristicas de los datos.

Este documento provee la información de la fuente de los datos crudos, curados y para producción. Para cada conjunto de datos
(crudos, curados y producción) se realiza una tabla, donde cada registro muestra la información para un dataset perteneciente
al conjunto. 

Cada dataset se asocia a los scripts de transformación o movimiento que se le aplicaron. 


## Datos crudos


| Nombre dataset (raw)| Localización original   | Destino  | Scripts | link a reporte |
| ---:| ---: | ---: | ---: | -----: |
| Dataset 1 | link fuente | link s3 raw | [script1.py](link/to/python/script/file/in/Code) | [Dataset 1 Report](link/to/report1)|
| Dataset 2 | link fuente | link s3 raw | [script2.R](link/to/R/script/file/in/Code) | [Dataset 2 Report](link/to/report2)|


* Dataset1 summary. <Provide brief summary of the data, such as how to access the data. More detailed information should be in the Dataset1 Report.>
* Dataset2 summary. <Provide brief summary of the data, such as how to access the data. More detailed information should be in the Dataset2 Report.> 

## Datos procesados


| Nombre dataset (proces) | dataset(s) asociado(s)  | Scripts | link a reporte |
| ---:| ---: | ---: | ---: | 
| Processed Dataset 1 | [Dataset1](link/to/dataset1/report), [Dataset2](link/to/dataset2/report) | [Python_Script1.py](link/to/python/script/file/in/Code) | [Processed Dataset 1 Report](link/to/report1)|
| Processed Dataset 2 | [Dataset2](link/to/dataset2/report) |[script2.R](link/to/R/script/file/in/Code) | [Processed Dataset 2 Report](link/to/report2)|

* Processed Data1 summary. <Provide brief summary of the processed data, such as why you want to process data in this way. More detailed information about the processed data should be in the Processed Data1 Report.>
* Processed Data2 summary. <Provide brief summary of the processed data, such as why you want to process data in this way. More detailed information about the processed data should be in the Processed Data2 Report.> 

## Datos para producción

| Nombre dataset (prod) | dataset(s) asociado(s) | Scripts | link a reporte |
| ---:| ---: | ---: | ---: | 
| Feature Set 1 | [Dataset1](link/to/dataset1/report), [Processed Dataset2](link/to/dataset2/report) | [R_Script2.R](link/to/R/script/file/in/Code) | [Feature Set1 Report](link/to/report1)|
| Feature Set 2 | [Processed Dataset2](link/to/dataset2/report) |[SQL_Script2.sql](link/to/sql/script/file/in/Code) | [Feature Set2 Report](link/to/report2)|

* Feature Set1 summary. <Provide detailed description of the feature set, such as the meaning of each feature. More detailed information about the feature set should be in the Feature Set1 Report.>
* Feature Set2 summary. <Provide detailed description of the feature set, such as the meaning of each feature. More detailed information about the feature set should be in the Feature Set2 Report.> 
