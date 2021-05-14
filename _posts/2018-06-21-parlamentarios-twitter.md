---
layout: post
title: 'La red social de los parlamentarios'
summary: 'Análisis del las redes sociales en Twitter de los concejales de Badalona, los diputados del Parlament y los diputados del Congreso.'
thumbnail: thumbnail-twitterUE.png
image: thumbnail-twitterUE.png
showimage: false
category: datos
type: articulo
---

Los parlamentos son, en principio, lugares donde los representantes de la ciudadanía debaten
sobre lo público y votan normas o leyes en consecuencia. En la versión más naíf de esta teoría podríamos pensar
que, en las redes sociales, estos representantes se siguen entre ellos para leer, y quizás intercambiar, sus opiniones 
en el día a día. En realidad, los parlamentos no son espacios de debate sino espacios donde los partidos actuan como bloques que 
exponen sus posiciones ya pre-fijadas (y en el mejor de los casos también debatidas) internamente. Así, podemos esperar que las redes sociales de los 
parlamentarios reproduzcan este fenómeno de bloques.

En este post vamos a ver las redes sociales de Twitter de cuatro parlamentos a cuatro niveles: municipal, autonómico, estatal y Europeo.

### **Badalona**

la primera figura muestra quién sigue a quién entre los concejales del ayuntamiento de Badalona. Vemos
que a nivel de ciudad no se aprecia una marcada tendencia a crear bloques, 
probablemente por el reducido número de concejales y la facilidad de seguirse los unos a los otros.
Aún así, los concejales del mismo partido tienden a seguirse entre sí con algunas excepciones en el PP. 
A veces los agujeros en la matriz, cuando están donde no deberían, pueden revelar información útil.
**¿Por qué el brazo derecho de Albiol, Juan Fernández, y la benjamina 
del grupo, Cristina Agüera, no se siguen entre ellos?**
¿Competencia entre los posibles relevos generacionales? ¿No se tragan? ¿O por nada en especial? 

<figure>
   <img src="{{ site.baseurl }}/assets/fig24_matriz_adj_BDN.png" width="100%">
    <figcaption>Fig.1 - Matriz de adyacencia en Badalona.</figcaption>
</figure>


### **Catalunya**

En el Parlament de Catalunya la estructura de bloques emerge con claridad.
Lo primero que llama la atención es cómo los bloques de Junts per Catalunya y ERC tienden
a difuminarse entre ellos. Los segundo, que a los de Ciutadans no les sigue casi nadie. 
Cuando dos grupos no se tragan, lo que hacen a menudo es seguir al menos a su líder, en este caso Arrimadas.
**El resto de miembros de Ciudadanos obtiene sus seguidores casi exclusivamente del PSC.**

<figure>
   <img src="{{ site.baseurl }}/assets/fig25_matriz_adj_CAT.png" width="100%">
  <figcaption>Fig.2 - Matriz de adyacencia en Catalunya.</figcaption>
</figure>



### **España**

La vida en Madrid es más dura. Los partidos viven en sus burbujas, con la excepción de
Unidos Podemos (IU, Podemos, mareas...) y ERC.
<figure>
   <img src="{{ site.baseurl }}/assets/fig26_matriz_adj_ES.png" width="100%">
   <figcaption>Fig.3 -Matriz de adyacencia en España.</figcaption>
</figure>


### **Europa**

Finalmente, en el Parlamento Europeo hay una doble estructura. Por un lado,
la estructura de bloques más fuerte es a nivel de partido estatal. Los del PP siguen a los del PP,
los del PSOE a los del PSOE, etc. En un segundo nivel, los europarlamentarios tienden a seguir a los miembros de
su mismo eurogrupo. Hay, parece, un tercer nivel donde a veces parlamentarios de un país siguien a parlamentarios
de su mismo país aunque sean de otros partidos.
 
<figure>
   <img src="{{ site.baseurl }}/assets/fig27_matriz_adj_UE.png" width="100%">
   <figcaption>Fig.3 -Matriz de adyacencia en Europa. Entre paréntisis, algunos de los partidos miembros de cada eurogrupo.</figcaption>
</figure>

*Si los ciudadanos vivimos en burbujas de información y cámaras de eco, nuestros representantes... también.*

#### **Metodología y notas**

El código Python para bajar los datos de Twitter está [aquí](https://github.com/alumbreras/twitter-followers-graph).
El código R para el análisis y visualización está [aquí](https://github.com/alumbreras/rtransparency).

