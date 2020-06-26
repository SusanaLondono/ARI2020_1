# Data preparation

En esta carpeta se encuentran los archivos de preparación de datos:

1. A0-carga-archivoRaw.ipynb
   Carga archivo en pyspark, realiza algunas transformaciones (eliminación de registros < 2016, elimina y renombra columnas), guarda el nuevo archivo en .csv, se vuelve a leer con pandas y se guarda en la carpeta Data/Processed/T0_ECV_161718.csv
2. A1-data_prep.ipynb   
   Realiza todas las transformaciones necesarias para el análisis posterior de los datos. Lee el archivo T0_ECV_161718.csv y genera el archivo Data/Processed/T1_ECV_prep.csv
3. A2-outliers.ipynb
   Realiza el análisis y la eliminación de *outliers*. Lee el archivo Data/Processed/T1_ECV_prep.csv y genera los archivos Data/Processed/T2_ECV_sindum_sinout.csv y   Data/Processed/T2_ECV_sindum_conout.csv
4. A3-dummies.ipynb
   Introduce el bloque de variables ficticias (*dummies*). Lee el archivo Data/Processed/T2_ECV_sindum_conout.csv y genera los archivos Data/Processed/T2_ECV_condum_sinout.csv y   Data/Processed/T2_ECV_condum_conout.csv
