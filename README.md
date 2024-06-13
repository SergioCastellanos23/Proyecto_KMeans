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
