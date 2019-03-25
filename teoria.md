Las variables agronómicas más importantes de los cultivos que pueden ser
monitoreadas con sistemas SAR son: 1) el contenido de agua de los cultivos, 2) el índice de área
foliar, 3) la biomasa, (Ferrazzoli P. 2002; Kim et al. 2013), estas variables son importantes porque
son inputs para modelos de estimación de rendimiento (Steduto et al. 2009). 

Es muy probable que los clasificadores
parámetricos (que requieren que los valores a clasificar sigan una distribución normal)
presenten una menor precisión global en la clasificación de una imagen SAR en comparación
con los clasificadores no parámetricos, dado que estos últimos no requieren que los valores a
clasificar presenten distribución normal. [gulicDiPaolo](http://www.famaf.unc.edu.ar/wp-content/uploads/2017/08/45-Gulich-Di-Paolo.pdf)

Finalmente, cabe destacar que dentro de las bandas SAR típicas más utilizadas X, C y L,
todas ellas han presentado buenos desempeños en clasificaciones de cultivos (Tian et al. 2010;

En la presente tesis, se utilizará el concepto de “clasificación de cultivos” para referir a
una clasificación digital de coberturas terrestres donde las clases predominantes son los cultivos.
El resultado de la clasificación de cultivos se verá reflejada en un mapa. El tipo de clasificación
utilizada en esta tesis será del tipo supervisada, es decir, se utilizaran muestras de
entrenamiento para “entrenar” a un algoritmo, el cual servirá posteriormente para la predicción
de una clase
Skriver et al. 2011).

 El clasificador generará en una primera etapa una función que vincule los datos de
entrada y salida (etapa de entrenamiento). En una segunda etapa el algoritmo clasificador
utilizará esa función para predecir valores de salida a partir de un nuevo universo de valores de
entrada (etapa de clasificación). Las muestras de entrenamiento, surgen de un dato de campo,
o “verdad de campo”, ese dato de campo posee una componente geográfica y una etiqueta. De
esa ubicación geográfica se extrae un conjunto de valores digitales del set de imágenes
satelitales utilizadas, y se asocia a ese conjunto de valores la etiqueta o clase registrada en la
“verdad de campo”. Esa clase se corresponde con una cobertura terrestre observada en el
terreno. De manera que una “muestra de entrenamiento” puede ser caracterizada como un
conjunto de vectores, donde cada uno acumula una serie de valores obtenidos a partir de un
set de imágenes satelitales y una etiqueta que identifica cada vector con una cobertura del
terreno. Para llevar a cabo un control de las clasificaciones, se utiliza un conjunto de vectores
llamado “muestra de control” compuesta por vectores independientes de la “muestra de
entrenamiento [gulicDiPaolo](http://www.famaf.unc.edu.ar/wp-content/uploads/2017/08/45-Gulich-Di-Paolo.pdf)

En la presente tesis, el control de las clasificaciones se llevará a cabo con los
siguientes indicadores: Precisión global de la clasificación, error de comisión, y el error de
omisión que surgen de una matriz de confusión. La matriz de confusión es una tabla de doble
entrada, N x N, donde N es la cantidad de clases definidas por el usuario, las columnas
corresponden a los valores observados y los de las filas a los predichos por la clasificación. [gulicDiPaolo p13](http://www.famaf.unc.edu.ar/wp-content/uploads/2017/08/45-Gulich-Di-Paolo.pdf)


El objetivo de las rutinas es "entrenar" a una máquina digital o algoritmo la relación funcional
entre una variable de entrada (input) y una variable de salida (output). Cuando la máquina es 
14
capaz de predecir una variable de salida cualitativa, entonces produce una "clasificación".
Cuando la máquina predice valores cuantitativos el resultado es llamado "regresión".
Normalmente, las máquinas de entrenamiento supervisadas, funcionan en dos fases, la primera
de entrenamiento, en la cual se genera un modelo predictivo, y la segunda de clasificación de
un conjunto de vectores de entrada. El operador, deberá posteriormente calcular la precisión y
los errores de la clasificación mediante la utilización de matrices de confusión. [gulicDiPaolo p13-14](http://www.famaf.unc.edu.ar/wp-content/uploads/2017/08/45-Gulich-Di-Paolo.pdf)
