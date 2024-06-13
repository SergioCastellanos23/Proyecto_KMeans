# Proyecto_KMeans

### El siguiente proyeto es utilizado para agrupar o segmentar el portafolio de clientes en diferentes grupos con caracteristicas o comportamientos similares. 

- La base de datos es un dataset limitado al cual se le realizo un análsis de datos, manteniendo dicho análisis simple y sencillo, debido a que ya se habia indagado a profundidad en otro proyecto.
- Realizamos la limpieza de los datos mediante dos metodos para saber cual metodo era menos discriminantes.
  - Hicimos dos dataframes para esto, df1 y df2.
    - df1 fue con el metodo KNN
    - df2 fue con el metodo Isolation Forest
- Se decide proceder con el df1, debido a que no elimino tantos outliers como el metodo Isolation Forest.
- Posteriormente, utilizamos la libreria PCA para reducir las dimensiones.

### Comienza el desarrollo del modelo KMeans:

- Utilizando el codo de jambu para definir el numero optimo de cluster para nuestro conjunto de datos, se verifica que el numero optimo de cluster son 3.

### Analizando cada cluster para poder determinar o categorizar nuestros clientes y las tasas de intereses que podrían obtener por la adquisición de nuevos prestamos.

- Nos concentraremos en 3 variables que particularmente pueden determinar o son clave en nuestro estudio, sin embargo, se hará el analisis de las demás variables para evaluarlas:
  - DURATION
  - AMOUNT
  - AGE

#### CLUSTER 0:
- DURATION
  - Media: 14.72
  - Std: 5.94
  - Min: 4
  - 25%: 11
  - 50%: 12
  - 75%: 18
  - Max: 30

- AMOUNT
  - Media: 1865.40
  - Std: 979.15
  - Min: 276
  - 25%: 1206
  - 50%: 1577
  - 75%: 2404
  - Max: 7427
 
- AGE
  - Media: 27
  - Std: 7
  - Min: 19
  - 25%: 24
  - 50%: 28
  - 75%: 33
  - Max: 56
 
#### CLUSTER 1

- DURATION
  - Media: 15.62
  - Std: 6.92
  - Min: 4
  - 25%: 11
  - 50%: 12.5
  - 75%: 24
  - Max: 36

- AMOUNT
  - Media: 2011.36
  - Std: 1139.78
  - Min: 338
  - 25%: 1234.75
  - 50%: 1596
  - 75%: 2650.75
  - Max: 6761
 
- AGE
  - Media: 46.50
  - Std: 11.18
  - Min: 23
  - 25%: 37
  - 50%: 46
  - 75%: 54
  - Max: 75
 
#### CLUSTER 2

- DURATION
  - Media: 32.52
  - Std: 10.62
  - Min: 10
  - 25%: 24
  - 50%: 30
  - 75%: 36
  - Max: 60

- AMOUNT
  - Media: 4837.66
  - Std: 1692.76
  - Min: 1819
  - 25%: 3508
  - 50%: 4579.5
  - 75%: 6306.25
  - Max: 8065
 
- AGE
  - Media: 34.87
  - Std: 9.91
  - Min: 20
  - 25%: 27.75
  - 50%: 33
  - 75%: 40
  - Max: 75

 ## Conclusiones
 
