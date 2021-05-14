---
layout: post
title: Estadística para tecnócratas
date: 2010-08-16 17:21:06.000000000 +02:00
type: articulo
categories:
- política
---
<p>La minería de datos (<em>data mining</em> para los ingleses y para los <em>guays</em>) es una rama de la ciencia que utiliza la estadística y la computación para extraer información relevante, a veces no apreciable a simple vista, de grandes cantidades de datos. Como toda ciencia o tecnología tiene sus aplicaciones buenas y sus no tan buenas. Entre las buenas se encuentran el estudio del ADN -se puede saber si eres más o menos propenso a padecer cierta enfermedad- o las recomendaciones de libros. Entre las no tan buenas están las aplicaciones que les dan seguros y bancos para no darte un crédito o cobrarte más de la cuenta.</p>
<p>El tema es que es una herramienta muy potente que la humanidad utiliza más con fines puramente capitalistas de maximización de beneficio que para fines más bien sociales. Si bien es cierto que la maduración de las técnicas en uno de los frentes puede beneficiar a todos, es ciertamente triste ver como ingenierios, científicos, y otros enseres capacitados se autoaplican el guía burros para no ver -o prospeccionar- qué <em>más</em> se puede hacer.</p>
<p>La última fantástica aplicación viene de las mentes semipensantes de las <a href="http://www.enriquedans.com/2010/08/bienvenidos-al-departamento-de-precrimen.html">cárceles de Philadelphia y de Balimore</a>, que han confundido la estadística con la clarividencia, despachando las  libertades condicionales en función de lo que diga el oráculo sobre el futuro comportamiento del reo.</p>
<p>Vamos a ver cómo explicamos que esto es, matemáticamente hablando, una <em>gilipollez</em>.</p>
<p>Lo que se hace en estos casos es  elegir un conjunto de variables que modelan al preso, tales como edad,  número de delitos cometidos y su gravedad, sus estudios, su  profesión, su barrio, su estado civil, y una serie de variables  socioeconómicas relevantes que lo <em>caracterizan</em>. Una vez tenemos los ingredientes hay que cocinarlos. Para ello los metemos como entrada en una función matemática que nos da como resultado la probabilidad de que el preso se porte mal en el futuro.</p>
<p>¡Atención! tenemos la primera cagada: el resultado es una <em>probabilidad</em> -o algo parecido- que nunca será del 100% puesto que nunca se puede estar seguro de nada. Pero sigamos.</p>
<p>El cómo creamos esa función, que viene a ser nuestro oráculo, es irrelevante para el caso, aunque de ello sacaríamos las siguientes cagadas en el planteamiento de nuestros amigos. Digamos que a esa función se la <em>entrena</em> con presos antiguos de los que sabemos sus datos y si reincidierion o no. Matemáticamente tendríamos algo así:</p>

$$
y = f(x) 
$$

<p style="text-align: justify;">Donde  <em><strong>x</strong></em> es el conjunto de datos del preso, <strong><em>f(x)</em></strong> nuestra función mágica que actua sobre esos datos, e <em><strong>y</strong></em> el veredicto final, que será un número entre 0 y 1 interpretable como la probabilidad de que el preso delinca.</p>
<p style="text-align: justify;">Imaginemos, como han hecho nuestros amigos, que aplicamos esta función a cada preso actual y que no le dan la libertad condicional a aquellos con <em><strong>y</strong></em> mayor de 0,5.</p>
<p style="text-align: justify;">Enhorabuena, es usted la reencarnación del mismísimo Tomás de Torquemada.</p>
<p style="text-align: justify;">¿Qué hemos hecho mal? Pues olvidar el <em>libre albedrío</em>. Confiar en la ecuación anterior significa aceptar el determinismo como rector del universo y creer que nuestra función <strong><em>f(x) </em></strong>es capaz de captar su incomputable complejidad, hasta el movimiento del último átomo. Así que para lidiar con esta aleatoriedad la introducimos en nuestra ecuación:</p>

$$
y = f(x) + \varepsilon 
$$

<p style="text-align: justify;">La <strong>epsilon</strong> representa, por lo tanto, ese factor, que es una variable aleatoria  que en ingeniería se conoce como <em>ruido</em> y en matemáticas como <em>error</em>.  Dependiendo de lo que la ecuación represente, el error puede ser el  ciudadano que miente en una encuesta, la mariposa que agita sus alas, el  pánico en bolsa tras la noticia de un ataque terrorista  a una planta petrolífera, o simplemente la suma de infinitos factores  que afectan a <em><strong>f(x)</strong></em> pero que no podemos moldelar porque su comportamiento  es aparentemente caótico. Por muy buena que sea nuestra <em><strong>f(x)</strong></em>, hay una parte de ese error, la del libre albedrio, que nos la tenemos que comer por que no hay una máquina que pueda predecir con total exactitud si voy a seguir escribiendo o me voy a tirar por la ventana para demostrar que estoy en lo cierto. En definitiva,  ese factor puede girar la tortilla y hacer que un preso decida pasarse <em> al otro lado</em> ante la sorpresa de nuestro oráculo que no supo ni pudo predecirlo, como tampoco sería capaz de predecir la aparición de un nuevo Hitler en Alemania.</p>
<p style="text-align: justify;">Por  ello obviar el libre albedrio equivale a considerarnos un ejército de  robots cien por cien predecibles y cien por cien idénticos.  Si la  sociedad es la suma de individuos <em><strong>f(x) + epsilon</strong></em> que se organizan en para  maximizar y distribuir la felicidad, sacrificar el libre albedrío  implica no solo negar nuestra realidad como personas sino implosionar  la definición de sociedad, que quedaría en una triste, insípida, gris y determinista <em><strong>f(x)</strong>.</em></p>
<p style="text-align: justify;">Por reducción al absurdo, por tanto, <em>quod erat demonstrandum.</em></p>
<p><em><em><a href="http://albertolumbreras.com/wp-content/uploads/2010/08/ROTOmates.jpg"><img class="aligncenter size-medium wp-image-339" title="ROTOmates" src="{{ site.baseurl }}/assets/ROTOmates-300x225.jpg" alt="" width="356" height="267" /></a></em></em></p>
