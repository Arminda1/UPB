---
title: " TENDENCIAS PRE Y POST PANDEMIA EN LAS EMPRESAS DE TELEFONIA EN BOLIVIA"
author: "GRUPO 2"
output:
  pdf_document:
    toc: yes
    toc_depth: '3'
  html_document:
    theme: cosmo
    highlight: monochrome
    toc: yes
    toc_depth: 3
    toc_float: yes
    fig_caption: yes
---
## TRABAJO FINAL DE MODULO.

## GRUPO 2

## Integrantes

Los integrantes que forman parte del grupo 2 son:

1. Arminda Caero <armicaero@gmail.com>
2. Emily Herbas <emily.herbas.l@gmail.com>
3. Jonathan Jordan <j.jordan.sainz@gmail.com>
4. Marco Guillen <ma.guillenroman@gmail.com>

# TELECOMUNICACIONES & COVID EN BOLIVIA.

### Resumen

En Bolivia, el sector de telecomunicaciones generó una participación del 2.57% del producto interno bruto (PIB). A finales del año 2021 se tenia el registro de 223 operadores a nivel nacional. La competencia mas importante del mercado esta centrada tres operadores principales: TIGO (antes TELECEL), ENTEL y Nuevatel (VIVA).
Los servicios de telecomunicaciones móviles iniciaron sus operaciones el año 1990 con la empresa TELECEL (Telefónica Celular), la empresa estatal ENTEL inicio su línea de negocio de telefonía móvil el 6 años después. Posteriormente iniciando operaciones mediante la tecnología GSM ingreso un tercer operador bajo el nombre comercial VIVA GSM el año 2000. Desde entonces y a la fecha, se presento una evolución interesante en los servicios brindados por estas operadoras como ser servicios de voz y datos GSM, WCDMA, LTE, servicios de acceso a internet banda ancha FTTH, servicios de Televisión Digital, billetera móvil, etc. El año 2013 fue lanzado a orbita el satélite TKSAT-1 (Túpac Katari) siendo el primer satélite de propiedad del estado y el año 2020, la empresa ENTEL inauguró su propia conexión de fibra óptica al Pacífico con el objetivo es mejorar la calidad y bajar los precios de Internet. Sin embargo, a pesar del crecimiento interesante en relación al sector la pandemia COVID-19, los problemas político sociales en el país generaron un decremento en los ingresos económicos generados por el sector.

## Situación Problema

Durante los últimos años se presentaron distintos eventos históricos en el mundo; esto provoco que diferentes sectores presenten variados comportamientos relacionados a sus tendencias e indicadores de crecimiento. En el caso particular de Bolivia, durante los últimos 5 años se presentaron distintos eventos político sociales y posteriormente la crisis sanitaria (debido a la pandemia); eventos que sin duda generaron efectos considerables en distintos rubros.

En el presente articulo se realizo el desarrollo del estado del sector de telecomunicaciones en Bolivia, debido a los eventos mencionados.

## Marco teórico

## DIAGRAMA DE PARETO

El Diagrama de Pareto, es una técnica gráfica sencilla para clasificar aspectos en orden de mayor a menor  frecuencia. Está basado en el principio de Pareto.

Este diagrama, también es llamado curva cerrada o Distribución A-B-C, es una gráfica para organizar datos de forma que estos queden en orden descendente, de izquierda a derecha y separados por barras.

Este diagrama:

* Permite asignar un orden de prioridades.
* Permite mostrar gráficamente el principio de Pareto (pocos vitales, muchos triviales), es decir, que hay muchos problemas sin importancia frente a unos pocos muy importantes. 
Mediante la gráfica colocamos los «pocos que son vitales» a la izquierda y los «muchos triviales» a la derecha.
* Facilita el estudio de las fallas en las industrias o empresas comerciales, así como fenómenos sociales o naturales psicosomáticos.
Hay que tener en cuenta que tanto la distribución de los efectos como sus posibles causas no es un proceso lineal, sino que el 20% de las causas totales hace que sean originados el 80% de los efectos y rebotes internos del pronosticado.

El principal uso que tiene el elaborar este tipo de diagrama es para poder establecer un orden de prioridades en la toma de decisiones dentro de una organización. Evaluar todas las fallas, saber si se pueden resolver o mejor evitarlas.

### ¿Qué es el principio de Pareto y quién es Pareto?

El principio de Pareto es también conocido como la regla del 80-20, distribución A-B-C, ley de los pocos vitales o principio de escasez del factor.

Recibe uno de sus nombres en honor a Vilfredo Pareto, quien lo enunció por primera vez,  basándose en el denominado conocimiento empírico. Estudió que la gente en su sociedad se dividía naturalmente entre los «pocos de muchos» y los «muchos de poco»; se establecían así dos grupos de proporciones 80-20 tales que el grupo minoritario, formado por un 20 % de población, ostentaba el 80 % de algo y el grupo mayoritario, formado por un 80 % de población, el 20 % de ese mismo algo.

En concreto, Pareto estudió la propiedad de la tierra en Italia y lo que descubrió fue que el 20 % de los propietarios poseían el 80 % de las tierras, mientras que el restante 20 % de los terrenos pertenecía al 80 % de la población restante.

### ¿Cuándo utilizar un diagrama de Pareto?
Para analizar los datos sobre la frecuencia de problemas o de causas en un proceso.
Cuando son muchos problemas o causas y se desea centrarse en los más importantes.
Cuando se desea analizar las causas de un problema enfocándose en sus componentes específicos.
Para comunicarse con otros a través de datos (de manera visual).

### ¿Cómo se hace un diagrama de Pareto?
a) Seleccionar los aspectos que se van a analizar. ¿Cuál es el problema y las causas que se van a tratar?

b) Seleccionar la unidad de medida para el análisis: la cantidad de ocurrencias, los costos u otra medida de influencia.

c) Seleccionar el período de tiempo para el análisis de los datos, por ejemplo: un ciclo de trabajo, un día completo, una semana, etc.

d) Relacionar los aspectos de izquierda a derecha en el eje horizontal en el orden de magnitud decreciente de la unidad de medida. Las categorías que contienen la menor cantidad de aspectos pueden combinarse en «otra» categoría, la cual se debe colocar en la extrema derecha).

e) Encima de cada aspecto, se dibuja un rectángulo cuya altura represente la magnitud de la unidad de medida para cada aspecto.

f) Construir la línea de frecuencia acumulativa sumando las magnitudes de cada aspecto de izquierda a derecha.

g) Utilizar el Diagrama de Pareto para identificar los aspectos más importantes para el mejoramiento de la calidad.



## Experimentación

Acorde proyecciones del Instituto Nacional de Estadista de Bolivia, el país contaría con una población aproximada de 12 millones de habitantes para el año 2022; donde mas del 70% de la población se encontraría distribuida (principalmente), en tres de sus nueve departamentos. Donde el departamento de Santa Cruz albergaría aproximadamente el 28.5%, La Paz el 25.4% y del departamento de Cochabamba con un 17.6% de la población.

```{r}
library(readr)
PoblacionBolivia2012a2022 <- read_csv("PoblacionBolivia2012a2022.csv")
View(PoblacionBolivia2012a2022)
print(PoblacionBolivia2012a2022)

```

![UDS](C:\Users\arcaero\Desktop\Arminda\Maestria Telecom\M16\TrabajoFinal\Imagenes\Poblacion.jpeg)


Fuente: https://www.ine.gob.bo/index.php/censos-y-proyecciones-de-poblacion-sociales/

En lo que respecta a las redes de telecomunicaciones móviles en el país, se tiene presencia de tres operadoras principales; la empresa nacional de telecomunicaciones ENTEL, y los operadores privados TIGO (miembro de la corporación MILLICOM) y Nuevatel (empresa que opera bajo el nombre comercial VIVA).

Acorde una publicación realizada por el diario El Deber (basado en un informe brindado por la calificadora de riesgo Pacific Credit Rating), a septiembre del año 2019 la participación del marcado correspondiente a la empresa ENTEL contaba con una participación aproximada del 45,4%, la operadora TIGO con una participación de 37,6% y Nuevatel con el restante 16,9%.

```{r}
library(readr)
Participacion_en_el_Mercado_Sept2019 <- read_csv("Participacion en el Mercado Sept2019.csv")
View(Participacion_en_el_Mercado_Sept2019)
print(Participacion_en_el_Mercado_Sept2019)
```

![UDS](C:\Users\arcaero\Desktop\Arminda\Maestria Telecom\M16\TrabajoFinal\Imagenes\Participacion.jpeg)

Fuente: https://eldeber.com.bo/economia/telefonicas-mantienen-dinamismo-pese-a-desaceleracion-economica_161123

Las consecuencias del COVID-19 cambiaron en distintos aspectos el uso (hasta entonces habituales) del consumo de productos y servicios por parte de la población a nivel mundial.
En lo particular; en Bolivia, el sector de Telecomunicaciones fue parte de los sectores que mediante una serie de promulgaciones de Decretos Supremos (D.S.) de parote del Gobierno Central tuvo que cumplir y asumir una serie de mandatos. En mayo del año 2020 se promulgo el D.S. Nro. 4250 que tenia como objetivo establecer condiciones y medidas para la continuidad de los servicios de telecomunicaciones y postales, durante la cuarentena nacional, cuarentena condicionada y cuarentena dinámica. Estableciendo distintos escenarios en beneficio del usuario, donde entre otros artículos emitidos se resaltaron los siguientes beneficios para los usuarios que presentaron distintas dificultades en el pago por servicios:

 - Se estableció el Servicio Gratuito "Mantengámonos Conectados" para telefonía fija, móvil, distribución de señales y acceso a internet.
 - No se realizó el corte del servicio a los clientes post-pago o pre-pago con deudas.
 - Para la red móvil (telefonía móvil e internet móvil) se brindo el servicio de WhatsApp ilimitado (solo mensajería). Llamadas ilimitadas a dos números, uso de 10 minutos libres, consumo de 500 MB y 10 SMS sin costo.
 - Para el servicio de distribución de señales (Televisión por suscripción) se brindó el servicio ce emisión gratuito para toda la grilla de canales nacionales y cuatro canales internacionales.
 - Para el servicio de acceso a internet fijo se brindó al menos una velocidad de 1 Mbps o el 10% de la capacidad contratada.

En este mismo decreto, se declaro la modificación del Articulo Nro. 36 del Decreto Supremo Nro. 4206; correspondiente al capítulo IV (Telecomunicaciones y tecnologías de información), deonde se instruyo:

 - “ ARTÍCULO 36.- (PROHIBICIÓN DE CORTE DE LOS SERVICIOS DE TELECOMUNICACIONES Y TECNOLOGÍAS DE INFORMACIÓN).
I. Se prohíbe a los operadores y proveedores de servicios de telecomunicaciones y tecnologías de información, el corte del servicio y la imposición de sanciones a los usuarios por falta de pago por el tiempo que dure la declaratoria de emergencia por la pandemia del Coronavirus (COVID-19).
II. Los operadores o proveedores de servicios de telecomunicaciones y tecnologías de información, a solicitud de los usuarios, deberán generar planes de pago de hasta seis (6) meses.”

Parte de estos factores mas el decremento del uso de algunos servicios por parte de las operadoras (como ser telefonía fija, servicios de larga distancia, etc), provocaron que el sector presentara un decremento en la Evolución de los Ingresos Netos acorde los registros de la Memoria Institucional 2020 publicada por el ente regulador ATT (Autoridad de Regulación y Fiscalización de Telecomunicaciones y Transportes):

```{r}
library(readr)
IngresosNetosv3 <- read_csv("IngresosNetosv3.csv")
View(IngresosNetosv3)

```
![UDS](C:\Users\arcaero\Desktop\Arminda\Maestria Telecom\M16\TrabajoFinal\Imagenes\Ingresos.jpeg)


## Interpretación de resultados

Con lo citado y mencionado; se puede evidenciar que el decremento de ingresos en el sector de telecomunicaciones en Bolivia a causa de la crisis social, política y debido a la pandemia Covod-19; presenta un efecto similar al de los ingresos en relación a la generación de recursos. 

Al ser una sector basado en una serie de etapas que implica la contratación de distintos rubros para la puesta en servicio de sus redes como ser: alquiler de espacios para infraestructura, construcción de obras civiles, provisión de equipamiento especializado en transmisión y telecomunicaciones, tendido de fibra óptica, provisión de servicios de instalación, provisión de servicios de configuración de equipamiento, provisión de servicios de mantenimiento operativo, etc.; no cabe duda que el impacto económico es considerable a distintos niveles.

El golpe económico es sin duda considerable en el sector, reflejando el recorte de personal, generando políticas de austeridad y ahorro y creando la urgente necesidad del planteamiento de nuevas estrategias de fidelización, retención y captación de clientes potenciales con la finalidad de mantener la operatividad de sus operaciones.

## Referencias Bibliográficas

* https://www.bbv.com.bo/Media/Default/InformacionBursatil/Informes/BLP_TCB2_E1_PCR.pdf

* https://www.bbv.com.bo/Media/Default/InformacionBursatil/Informes/VTD_PTL_PCR.pdf

* https://siip.produccion.gob.bo/repSIIP2/formPib.php

* https://www.ine.gob.bo/index.php/censos-y-proyecciones-de-poblacion-sociales/

* https://eldeber.com.bo/economia/telefonicas-mantienen-dinamismo-pese-a-desaceleracion-economica_161123

* https://www.att.gob.bo/content/att-en-el-marco-del-decreto-supremo-n%C2%B0-4250-de-28-de-mayo-de-2020-con-relaci%C3%B3n-al-pago-de-la

* https://att.gob.bo/sites/default/files/archivospdf/Memoria%20Institucional%202020.pdf

* https://datos.bancomundial.org/indicator/IT.CEL.SETS?end=2020&locations=BO&start=1975&view=chart

* https://aprendiendocalidadyadr.com/diagrama-de-pareto/ Fecha:13-02-2022

Ultima vez que se modifico el archivo domingo 202202131844

