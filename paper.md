## Introduccion
nos hable del valor para el pais

## Estudio del area
aqui se mesiona con mayor enfais los siclos del arroz

## Datos usados
los datos del radar; banda, polarizacion ejm HH, el angulo, el area cubierta por el swath, y el ancho del pixel, la epoca que se adquirio 

## Preprocesamiento
datos de la descarga desarrollo del preproceso 

## calsificaicion 
las areas de arroz no  arroz fueron clasificadas basadas en un analisis temporal de la retrodispersion SAR. 
el arroz recien transplantado tiene una baja retrodispersion devido a la refleccion especular del estado del agua presnte en el campo
las plantas se van desarrollando los tallos, la retrodispersion del radar aumenta 
el rango dentro de este estudio esta ente -17 y- 6 dB 
y en el caso de no agua edificios superficies suavizadas el arango es de 21 dB
la parte urbano retorna al rededor de -6 a -2 dB
con esto se define el modelo 

## Clasificacion 
fue basada en la verda terreno y la clasoficacion supervisada fue utilizada y crando mascaras
y se genero la matiz para difernciar las diferentes cubiertas

###############################################################################################################

entre las metas que se quieren lograr es la de estandarizar in situ  son los procedimientos de medicion de variables esceciale apra el arrozaz
(arrroz no arroz, altura de la planta, campos,etc) selecioanndo los puntos para validar

|  |  |
| -- | -- |
| ID Pruducción/Inforamcion | Descripcion|
|P1 Siembra del arroz /cosecha areas y mappas | Cultivos en el area (todo el año) progresos del cultivo (todos los meses surante la temporada de crecimiento |
| CAlendario del cultivo / crecimiento del cultivo | tiempo de siembrea, dearrollo y cosecha; estatus del crecimiento, (y en lo posible el estado fenologico)   
| Evalucaion de daños del cultivo | Deteccion de inundacioens y otros desastres de impacato en el area; agrometeorología, deteccion de areas impacatadad por sequias o intrucion de agua consalinidad,   deteccion de plagas  y enfermedaes)|
| Información agrometeorológica | Anomalias agro meteorológicas (ej. precipitaciones, radiacion solar y alta o baja temperatura); animalias del cultivo por alertas tempranas, perspectivas de crecimiento, e impactos en el rendimiento futuro |
| Rendimeinto / producción Estimación* y pronostico | Estimación de modelos empiricos - estadísticos; simulación de modelos estimados de crecimientode cultivo |  [2,pag 7](http://asia-rice.org/files/2016_Asia-RiCE_Phase2_Work_Plan_v1.0.pdf)

generaremos un algoritmo propuesto pro Toan et al. 1997 para evaluar la clasificación exacta y umbrales basados en el dato de la tierra de cada paracela enlas areas de cultivo, también conmparamos los resultados  de las polarizaciones VV y VH, adempas los umbrales mínimos 

![arroz](https://github.com/HWMuyulema/RADAR/blob/master/img/estadios_arroz.png)



# Bibliografia
[Analisis temporal 2004](https://www.dropbox.com/home/RADAR%20RICE?preview=10.1007%252FBF03030862.pdf)

ASIA-RICE[2](http://asia-rice.org/files/2016_Asia-RiCE_Phase2_Work_Plan_v1.0.pdf)


