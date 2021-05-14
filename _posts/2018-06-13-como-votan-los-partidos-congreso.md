---
layout: post
title: '¿Cómo votan los partidos en el Congreso?'
summary: 'Análisis del histórico de votos en el Congreso de los Diputados. 
Dinámicas y alianzas entre partidos en la etapa Rajoy (legislaturas X, XI y XII: 2001--2018).'
thumbnail: thumbnail-correlacion.png
image: thumbnail-correlacion.png
showimage: false
category: datos
type: articulo
---

El Marianato ha sido una etapa que ha pasado por una primera legislatura de mayoría absoluta,
una segunda legislatura de bloqueo institucional y una tercera de estreno del
multipartidismo. ¿Cómo se han posicionado los diferentes partidos políticos? ¿Cómo han cambiado las alianzas?
¿Qué han hecho el PNV y CiU/PDCat en este periodo tan tenso en cuanto al debate territorial? 
Para coger un poco de perspectiva de lo que ha pasado, he descargado
los datos del congreso (2011-2018) para analizarlos. 

### **¿Cómo votan los diputados?**

La primera figura muestra lo que ha votado cada diputado en cada una de las votaciones
que han tenido lugar en el congreso. Los votos están ordenados cronológicamente. 
Sin sorpresas, constatamos que los diputados suelen votar en bloque. 
La XI legislatura pone fin al bipartidismo e inaugura el cuatripartidismo con la entrada
de Podemos --que se integra en el mismo grupo que Izquierda Unida-- y de Ciudadanos --que remplaza
a UPyD (en las gráficas, etiquetado como Cs) y amplía el bloque del Partido Popular. 

En la XII legislatura el bloque del PP se amplía no sólo con Ciudadanos sino con la adhesión
del PNV, que hasta entonces se había mantenido en una posición de abstenciones. Esta estrategia
de abstenciones también la seguía CiU más moderadamente.

<figure>
   <img src="{{ site.baseurl }}/assets/fig20_matriz_votos_legislaturas_wsj.png" width="100%">
    <figcaption>Fig.1 - Votaciones entre 2011 y 2018. Se muestran los nombres de uno de cada cinco diputados.</figcaption>
</figure>

### **Absentismo en las votaciones**
Las pequeñas zonas negras de la figura anterior corresponden a votaciones donde el diputado no estuvo
presente. El absentismo es una de las críticas que se hace a los diputados. Sin embargo,
a menudo el absentismo no tiene mayor importancia y se debe a que el diputado 
está participando en otras reuniones cuando su voto no es decisivo. 
Mariano Rajoy, por ejemplo, ha sido uno de los mayores absentistas durante su mandato.
La siguiente figura muestra los mayores absentistas de la etapa Rajoy.


<figure>
   <img src="{{ site.baseurl }}/assets/fig23_absentismo_parlamentario100.png" width="100%">
  <figcaption>Fig.2 - Los 75 diputados con mayor tasa de absentismo.</figcaption>
</figure>



### **¿Cómo votan los partidos?**
Veamos ahora un análisis a nivel de partido. Considerando que un partido vota *sí*
cuando la mayoría de sus diputados votan *sí* (igualmente para no y abstención), podemos dibujar una matriz
de votos similar a la que hicimos para los diputados:

<figure>
   <img src="{{ site.baseurl }}/assets/fig21_matriz_votos_partidos_legislaturas.png" width="100%">
   <figcaption>Fig.3 - Votaciones entre 2011 y 2018 por partidos.</figcaption>
</figure>

Finalmente, la prueba del algodón. Veamos, para cada legislatura, 
cuál ha sido la correlación entre los partidos en cuanto a su comportamiento de voto:
<figure>
   <img src="{{ site.baseurl }}/assets/fig22_matriz_votos_partidos_correlacion.png" width="100%">
  <figcaption>Fig.4 - Similitud de voto entre los diferentes partidos.</figcaption>
</figure>

En la X legislatura, el PP gobernaba con mayoría absoluta y sin aliados. 
Su partido más cercano era UPyD (aquí marcado como Cs) con un 40% de coincidencias de voto.
La XI legislatura, con sólo 27 votaciones, se centra en la discusión sobre el presidenciable
y no se llegan a crear alianzas claras. El PSOE coincide al 90% con todos menos con el PP, el
PP se acerca a Ciudadanos (70%), a CiU (ya entonces PDCat, 60%) y al PNV (50%).
Finalmente, en la XII legislatura, el PP amplía su bloque con las alianzas del PNV y de Ciudadanos, más la de miembros del
Grupo Mixto como Coalición Canaria.

Con estas alianzas, el apoyo del PNV a la moción de censura del PSOE estaba de todo menos garantizado.

#### **Metodología y notas**

*Para facilitar el análisis entre las diferentes legislaturas, he etiquetado a UPyD 
(presentes en la X legislatura) como Ciudadanos (XI y XII legislaturas).
Los miembros de CiU, Democràcia i Llibertat también van bajo la etiqueta CiU, a pesar
de que en la XII legislatura están en el grupo mixto. Izquierda Unida y las Mareas van bajo la etiqueta de 
Unidos Podemos (UP) a pesar que que Podemos no está presente en la X legislatura.*
 
*En el análisis de correlaciones, no he tenido en cuenta las abstenciones, ya que estas tienen una interpretación ambigua.
Así, sólo se cuenta cuando dos partidos votan sí a la vez o no a la vez.*

*Los datos y el código R para descargarlos, analizarlos y reproducir los gráficos están disponibles [aquí](https://github.com/alumbreras/rtransparency)*

