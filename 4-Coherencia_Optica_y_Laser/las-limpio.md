
---
Title: Apuntes Laser Limpio

---


![LasPortada](https://lh3.googleusercontent.com/4Gl8A8KEPNoS9YqhAgDXpZgVeJiwjOfftYZdLjeAxgP8xmKQkKZdkeACg87Lg2h4pfLqiE4cTmWu "LasPortada")



[TOC]


---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---

# Info Preliminar



---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---

# 1. Emisión en la materia



---
>.
> Intervalo Publicitario
>.
---


## 1.1. Cuerpo negro

Cavidad llena de medio homogeneo isotropo:

:	Densidad de energia electromagnetica emitida a cierta temperatura:
:	$$\rho = \frac { 1 } { 2 } \varepsilon E ^ { 2 } + \frac { 1 } { 2 } \mu H ^ { 2 } \quad ( 1.1 )$$

> Queremos calcular la **densidad espectral de energía por unidad de volumen e intervalo de frecuencias**: $\rho _ { \nu } ( \nu , T )$

  OJO! Hay distintas magnitudes parecidas, tanto por significado como por letra, que miden cosas distintas! [[EJEMPLOS]]:
> Densidad de energía por unidad de volumen: =
>  $$\rho ( T ) = \int _ { 0 } ^ { \infty } \rho _ { \nu } ( \nu , T ) d \nu \quad ( 1.2 )$$


Campos electromagnéticos deben cumplir la ecuacion de ondas:

:	$$\nabla ^ { 2 } \overline { E } - \frac { 1 } { c ^ { 2 } } \frac { \partial ^ { 2 } \overline { E } } { \partial t ^ { 2 } } = 0 \quad ( 1.3 ) \quad \overline { E } \times \overline { n } = 0 \quad ( 1.4 )$$
:	que se anula en las paredes de la cavidad, las cuales por cierto son completamente conductoras.


Proponemos como solución:

:	$$\overline { E } = \overline { U } ( x , y , z ) A ( t ) \quad} & { ( 1.5 )$$

:	Integramos por separacion de variables y obtenemos:
:	$$\begin{array} { l l } \\ { \nabla ^ { 2 } \overline { U } = - k ^ { 2 } \overline { U }  ( )) } & { \frac { \partial ^ { 2 } A } { d t ^ { 2 } } = - ( c k ) ^ { 2 } A }  { ( 1.6 b ) } } \end{array}$$

: Que lleva a las **soluciones**:
:	$$A ( t ) = A _ { 0 } \operatorname { sen } ( \omega t + \varphi ) \quad ( 1.7 ) \quad \omega = c k$$
:	$$\begin{aligned}  U _ { x } & = e _ { x } \cos k _ { x } x \sin k _ { y } y \sin k _ { z } z\ U _ { y } & = e _ { y } \sin k _ { x } x \cos k _ { y } y \sin k _ { z } z U _ { z } & = e _ { z } \sin k _ { x } x \sin k _ { y } y \cos k _ { z } z \end{aligned} \quad(1.8)$$
:	$$} \\ { k _ { x } ^ { 2 } + k _ { y } ^ { 2 } + k _ { z } ^ { 2 } = k ^ { 2 } }\quad ( 1.9 )$$

:	Donde:
:	$$ k _ { x } = \frac { l \pi } { 2 a } \quad k _ { y } = \frac { m \pi } { 2 a }   \quad k _ { z } = \frac { n \pi } { L }  \ l , m , n \in Z + \quad ( 1.10 )$$ Cavidad y longitudes de onda
.

¿Cuál será la distribucion de modos para esta cavidad?

:	La solución de la ecuación de onda en dicha cavidad con condiciones de contorno igual a 0 en los bordes.

:	Frecuencias que pueden oscilar:
:	$$\begin{array} { c } { \omega = c k = c \frac { 2 \pi } { \lambda } = 2 \pi \nu } \\ { \omega ^ { 2 } = c ^ { 2 } k ^ { 2 } = c ^ { 2 } \left[ \left( \frac { l \pi } { 2 a } \right) ^ { 2 } + \left( \frac { m \pi } { 2 a } \right) ^ { 2 } + \left( \frac { n \pi } { L } \right) ^ { 2 } \right] \quad ( 1.11 ) } \end{array}$$

:	Además
:	$$\nabla \cdot \overline { U } = 0 \Rightarrow \overline { e } \cdot \overline { k } = 0 \quad ( 1.12 )$$

:	Lo cual implica que hay dos polarizaciones

![Polarizaciones, modos](IMG)

---
#### Pregunta 1.1
##### Demostrar que la frecuencia minima depende del ratio entre 2a y L y que de (l m n) al menos dos deben ser distintos de cero. (Si no Ux Uy Uz son 0. Pej. si sólo l es distinto de 0 se anulan Uy y Uz)
[inp]
Nope, no hay solución aún.
Por no tener ni tengo un codigo simple de python que me reconozca los inp y out y los sustituya correctamente por
````
<details><summary>CLICK ME</summary>
<p>
#### yes, even hidden code blocks!
</p>
</details>
````

Tengo que trabajar en esto... Si le meto ecuaciones a este bloque me las renderizará?
[out]

---
### Densidad de modos

Calculemos la densidad de modos (contar modos en esa frecuencia):

:	![dldndm](tt)

:	$\wideha\rho } ( \nu )$ = número de modos por volumen y unidad de intervalo de frecuencia.

:	Consideremos un diferencial de volumen $dldndm$ en el espacio de modos como en la figura. Dentro habrá $dN = 2dldndm$ modos.

:	Usando (1.10) obtenemos que:

:	$$\begin{aligned} \text {dldmdn} = & \left( \frac { 2 a } { \pi } \right) ^ { 2 } \frac { L } { \pi } d k _ { x } d k _ { y } d k _ { z } & ( 1.13 ) \\ d N & = 2 \frac { ( 2 a ) ^ { 2 } L } { \pi ^ { 3 } } d k _ { x } d k _ { y } d k _ { z }  & ( 1.14 )\end{aligned}$$

:	En coordenadas esféricas:

:	$$d k _ { x } d k _ { y } d k _ { z } = k ^ { 2 } d k \sin \theta d \theta d \varphi = k ^ { 2 } d k d \Omega  \quad (1.15)$$

:	$$d N = 2 \frac { ( 2 a ) ^ { 2 } L } { \pi ^ { 3 } } \frac { L } { c ^ { 2 } } \frac { d \omega } { c } d \Omega = 2 \frac { ( 2 a ) ^ { 2 } L } { c ^ { 3 } } 2 ^ { 3 } \nu ^ { 2 } d \nu d \Omega \quad (1.16)$$

:	El número total de modos en ese volumen e intervalo de frecuencias se obtiene integrando:

:	$$\frac { 1 } { 8 } \int _ { 0 } ^ { 4 \pi } d N = 8 \pi \frac { \nu ^ { 2 } } { c ^ { 3 } } d \nu V$$

:	El 1/8 viene de que sólo integramo un cuadrante del espacio: $n,l,m\in Z^+Densidad de modos por unidad de volumen e intervalo de frecuencias:

:	$$\widehat { \rho } ( \nu ) = 8 \pi \frac { \nu ^ { 2 } } { c ^ { 3 } } \quad ( 1.18 )$$


Pero queremos densidad de energía!

:	$$\boxed{ > $\rho _ { \nu } ( \nu , T ) = \widehat { \rho } ( \nu ) < E > } \quad ( 1.19 )$$


Según la *eEstadística de Boltzman* la *Energía por modo* es:
:
:	$$< E > = \frac { \int _ { 0 } ^ { \infty } E \exp \left[ - \left( E / k _ { B } T \right) \right] d E } { \int _ { 0 } ^ { \infty } \exp \left[ - \left( E / k _ { B } T \right) \right] d E } = k _ { B } T \quad ( 1.20 )$$


Y así obtenemos la *ecuación de Rayleigh-Jeans*

:	$$\boxed{\rho _ { \nu } ( \nu , T ) = 8 \pi \frac { \nu ^ { 2 } } { c ^ { 3 } } k _ { B } T } \quad ( 1.21 )$$

:	Válida para altas T y bajas frecuencias

:	Implica una densidad total de energía infinita

### Densidad de energía

Hipótesis de Planck:
:	Cada modo tiene energía múltiplo entero de $h\nu$

:	$$< E > = \frac { \sum _ { 0 } ^ { \infty } n h \nu \exp \left[ - n h \nu / k _ { B } T \right] } { \sum _ { 0 } ^ { \infty } \exp \left[ - n h \nu / k _ { B } T \right] } = \frac { h \nu } { \exp \left( h \nu / k _ { B } T \right) - 1 } \quad ( 1.22 )$$

:	$$\boxed{\rho _ { \nu } ( \nu , T ) = \frac { 8 \pi \nu ^ { 2 } } { c ^ { 3 } } \frac { h \nu } { \exp \left( \frac { h \nu } { k _ { B } T } \right) - 1 } } \quad ( 1.23a )$$

:	$$h = 6.626 \times 10 ^ { - 34 } J _ { S }$$

Para tenerlo en $\omega$:
:	$$\rho _ { \omega } d \omega = \rho _ { \nu } d \nu \Rightarrow \boxed{ \rho _ { \omega } = \frac { \rho _ { \nu } } { 2 \pi } = \frac { \omega ^ { 2 } } { \pi ^ { 2 } c ^ { 3 } } \frac { \hbar \omega } { \exp \left( \frac { \hbar \omega } { k _ { B } T } \right) - 1 }} \quad ( 1.23 b )$$

Número de fotones (Ley de Planck):
:	$$\boxed { U _ { \nu } = \frac { \rho _ { \nu } } { h \nu } = \frac { 8 \pi \nu ^ { 2 } } { c ^ { 3 } } \frac { 1 } { \exp \left( \frac { h \nu } { k _ { B } T } \right) - 1 }} \quad (1.24)$$

:	Número de fotones a T por unidad de volumen y de intervalo de frecuencia.

:	$

Densidad de energía $\propto 8\pi \nu^3$
:	Número de forones $\propto 8\pi \nu^2$


Ejemplos para distintas T:
:	En el visible el número de fotones es pequeño
:	![U frente lambda](ulam)


---
#### Pregunta 1.2
##### Determinar el número medio de fotones en un modo de frecuendia $\nu$.
[in]
[out]

---


Luminancia:

:	Densidad de radiación en W/Sr

:	$L = \frac { c } { 4 \pi } \rho _ { \nu }$


En términos de $\lambda$:

:	Número de modos entre $\lambda$ y $d\lambda$ (usando $d \nu = \frac { c } { \lambda ^ { 2 } } d \lambda$):

:	$$N = 8 \pi \frac { \nu ^ { 2 } } { c ^ { 3 } } d \nu V= \frac { 8 \pi c ^ { 2 } } { c ^ { 3 } \lambda ^ { 2 } } \frac { c } { \lambda ^ { 2 } } d \lambda V = \frac { 8 \pi } { \lambda ^ { 4 } } V d \lambda = \rho _ { \lambda } V d \lambda$$

:	$$\rho _ { \lambda } ( \lambda , T ) = \rho _ { \lambda } \frac { h \frac { c } { \lambda } } { e ^ { h c / \left( \lambda k _ { B } T \right) } - 1 } = \frac { 8 \pi h c } { \lambda ^ { 5 } } \frac { 1 } { e ^ { h c / \left( \lambda k _ { B } T \right) } - 1 } \quad (1.25)$$

L _ { \lambda } ( \lambda , T ) = \frac { 2 h c ^ { 2 } } { \lambda ^ { 5 } } \frac { 1 } { e ^ { h c / \left( \lambda k _ { B } T \right) } - 1 } = \frac { C _ { 1 } } { \pi \lambda ^ { 5 } } \frac { 1 } { e ^ { C _ { 2 } / \lambda T } - 1 }$$




---
>.
> Intervalo Publicitario
>.
---


## 1.2. Probabilidades de transición

Estudiaremos primero un sistema de dos niveles, como la lámpara de sodio

:	[[IMAGEN]]

:	$\mathrm { N } _ { 1 } , \mathrm { N } _ { 2 }$ densidad de población de los niveles 1$\mathrm { y } 2$
:	$\mathrm { g } _ { 1 } , \mathrm { g } _ { 2 }$ degeneraciones
:	Radiación y materia en equilibrio

Queremos saber cual es la población de cada nivel[[IMAGEN]] U frente lambda

Densidad de radiación en W/Sr

Luminancia:$=L=$

En términos de $\lambda$: $$




---
>.
> Intervalo Publicitario
>.
---


## 1.2. Probabilidades de transición

Estudiaremos la lámpara de sodio as usual.

[[IMAGEN]]

Un cuerpo negro también debería poder estar en equilibrio.

> Einstein:
¡:	Contad!
:	Un cuerpo negro descrito por el formalismo cuántico debe ser capaz de estar en equilibrio con la radiación circundante.

Proporcion del número de fotones entre ambos niveles en equilibrio (teniendo en cuenta degeneración):

:	$$\frac { N _ { 2 } } { N _ { 1 } } = \frac { g _ { 2 } } { g _ { 1 } } e ^ { \left[ - \left( E _ { 2 } - E _ { 1 } \right) / k _ { B } T \right] } = \frac { g _ { 2 } } { g _ { 1 } } e ^ { \left[ - h \nu / k _ { B } T \right] } \quad ( 1.26 )$$

:	[[IMAGEN]]
Hay una probabilidad de absorción, una **sección eficaz**, no absorberá siempre.
:	Pro
### Coeficientes de Einstein

^rpbabilidad de absorción $\propto$ número de fotones que haya en el nivel.


### Coeficientes de Einstein

Coeficiente de Einstein para absorción

:	$$N _ { a b s } =B _ { 12 } \rho _ { \nu } N _ { 1 } \quad ( 1.27 )$$

$$

> Coeficiente de Einstein para absorción

También emitirá con cierta probabilidad, pero de manera espontánea, no dependerá de que haya radiación.

Coeficiente de Einstein para emisión

:	$$N _ { e s p } = A _ { 21 } N _ { 2 }\quad ( 1.28 )$$

> Veamos cuántas absorciones se producen en el estado fundamental (por unidad de tiempo) (la $\rho _ { \nu }$).

En equilibrio:

:	$$A _ { 21 } N _ { 2 } = B _ { 12 } \rho _ { \nu } N _ { 1 } \quad ( 1.29 )$$

:	$$\rho _ { \nu } = \frac { A _ { 21 } } { B _ { 12 } } \frac { N _ { 2 } } { N _ { 1 } } = \frac { A _ { 21 } g _ { 2 } } { B _ { 12 } g _ { 1 } e ^ { \left[ h \nu / k _ { B } T \right] } } \quad (1.30) $$

:	Es la densidad de radiación de un sistema cuántico en equilibrio que emite y absorbe.
Sigue la *Distribución de Boltzmann*, pero debería salir la ley de Planck.
**Algo falla**.


> Einstein dedujo que habrá más procesos:

Coeficiente de Einstein para emisión estimulada

:	Estado excitado + Fotones de fuera = Emisión estimulada

:	$$N _ { e s t } = B _ { 21 } \rho _ { \nu } N _ { 2 } \quad (1.31)$$

---

#### Duda 1.1
##### ¿Sólo afecta a los fotones con esa frecuencia?¿
		O si tienen otras afecta?
[inp]
Respuesta
:	Creo que sólo esos....
[out]

---

> Con esto, ahora tenemos:

En equilibrio:

:	$$A _ { 21 } N _ { 2 } + B _ { 21 } \rho _ { \nu } N _ { 2 } = B _ { 12 } \rho _ { \nu } N _ { 1 } \quad (1.32)$$

:	$$\frac { N _ { 2 } } { N _ { 1 } } = \frac { B _ { 12 } \rho _ { \nu } } { A _ { 21 } + B _ { 21 } \rho _ { \nu } } = \frac { g _ { 2 } } { g 1 } \exp \left[ \frac { - h \nu } { k _ { B } T } \right] \quad (1.33)$$

: Ahora sí:

:	$$\rho _ { \nu } = \frac { A _ { 21 } } { B _ { 21 } } \frac { 1 } { \frac { B _ { 12 } } { B _ { 21 } } \frac { g _ { 1 } } { g _ { 2 } } \frac { g _ { 1 } } { g _ { 2 } } e ^ { h \nu / k _ { B } T } - 1 } \quad (1.34)$$

#### Relación entre coeficientes de Einstein

Veamos ahora qué pasa cuando
Prob(Emisión estimulada) = Prob(Absorción)

$N _ { e s t } = B _ { 21 } \rho _ { \nu } N _ { 2 } \quad ( 1.31 )$

Coeficiente Einstein para emisión estimulada: $B _ { 21 }$

$A _ { 21 } N _ { 2 } + B _ { 21 } \rho _ { \nu } N _ { 2 } = B _ { 12 } \rho _ { \nu } N _ { 1 } \quad ( 1.32)$

$\frac { N _ { 2 } } { N _ { 1 } } = \frac { B _ { 12 } \rho _ { \nu } } { A _ { 21 } + B _ { 21 } \rho _ { \nu } } = \frac { g _ { 2 } } { g 1 } \exp \left[ \frac { - h \nu } { k _ { B } T } \right] \quad ( 1.33 )$

$$\rho _ { \nu } = \frac { A _ { 21 } } { B _ { 21 } } \frac { 1 } { \frac { B _ { 12 } } { B _ { 21 } } \frac { g _ { 1 } } { g _ { 2 } } e ^ { h \nu / k _ { B } T } - 1 } \quad (1.34)$$

Ley de Planck (Ahora sí)

Relaciones entre los coeficientes de Einstein
: $$\boxed{\frac { B _ { 12 } } { B _ { 21 } } = \frac { g _ { 2 } } { g _ { 1 } }} \quad ( 1.35 )$$

: $$\boxed{ \frac { A _ { 21 } } { B _ { 21 } } = \frac { 8 \pi h \nu ^ { 3 } } { c ^ { 3 } } } \quad ( 1.36 )$$

---
$$Desarrollo$$

#### Relación entre coeficientes de Einstein

Veamos ahora qué pasa cuando
Prob(Emisión estimulada) = Prob(Absorción)

$$
Ley de Planck (Ahora sí)

### Tiempos de vida.

Con la teoría cuántica + Ecuación de la Dinámica:
:	 A12 y B21 dependen de los momentos dipolares.

La teoría cuántica proporciona:

$$A _ { 21 } = \frac { 16 \pi ^ { 3 } \nu ^ { 3 } n | \mu | ^ { 2 } } { 3 h \varepsilon _ { 0 } C _ { 0 } ^ { 3 } } \quad (1.37)$$

$$g _ { 2 } B _ { 21 } = g _ { 1 } B _ { 12 } = \frac { 2 \pi ^ { 2 } } { 3 n ^ { 2 } \varepsilon _ { 0 } h ^ { 2 } } | \mu | ^ { 2 } \quad ( 1.38 )$$


$$Desarrollo$$

#### Relación entre coeficientes de Einstein

Veamos ahora qué pasa cuando
Prob(Emisión estimulada) = Prob(Absorción)

$$
Ley de Planck (Ahora sí)

### Tiempos de vida.

Con la teoría cuántica + Ecuación de la Dinámica A12 y B21 dependen de los momentos dipolares.

$H_{perturbación} = (-er)$

Teoría de perturbaciones entre estado final e inicial.
Obtenemos un $\mu = \int \varphi _ { 2 } ^ { * } ( r ) ( - e r ) \varphi _ { 1 } ( r ) d V \quad ( 1.39 )$

$$DES$$

Y se obtiene que $A_{21}$ se puede medir

: Tiempo de vida media (o de vida natural):

:	$$\boxed { \tau _ { 21 } = \tau _ { e s p } = 1 / A _ { 21 } } \quad (1.40)$$
$$DES$$

Y se obtiene que $A_{21}$ se puede medir:
> Tiempo de vida media (o de vida natural): = $\tau _ { 21 } = \tau _ { e s p } = 1 / A _ { 21 }$

B no es tan medible pero sí se puede deducir desde la sección eficaz en absorción.

#### Ejercicio 1.1
#####:
> Cuerpo negro a $T = 1000K$. Calcular la frecuencia para la cual la probabilidad de emisión espontánea es 10 veces mayor que la estimulada.

[[[ACABAR]]]



### Transiciones no radiativas. Eficiencia cuántica.

La forma de desexcitarse el estado si emite radiación se llama radiativa.
Si no emmite luz tenemos transiciones no radiativas. Pej. el fotón choca con una pared, por impacto electrónico, reajustes moleculares...
Hay diferentes vías de desexcitación.

Hay una eficiencia para devolver la radiación!

> Probabilidad total de desexcitación:

:	$$P = P _ { e m } ^ { n r } + P _ { e m } ^ { e s p{ n r } } + \frac { 1 } { \tau ^ { e s p } } = \frac { 1 } { \tau } \quad ( 1.41 ) = $$

> Eficiencia cuántica:

:	$$\phi = \frac { P _ { e m } ^ { e s p } } { P _ { e m } ^ { e p } + P _ { e m } ^ { n r } } = \frac { 1 / \tau ^ { e s p } } { 1 / \tau } = \frac { \tau } { \tau ^ { e s p } } < 1 \quad ( 1.42 ) = $$

> Eficiencia cuántica: = $$

La eficiencia cuántica siempre es menor que 1, es el ratio enrtre las probabilidades de radiación espontánea y la de desexcitación total.

$\phi$ y $\tau$ se pueden medir y deducir $\tau_{esp}$ y $\tau_{nr}$.

**EN EL SIGUIENTE CAPÍTULO!!**
: ¿Cómo evolucionan las poblaciónes en funciónd del tiempo?




---
>.
> Intervalo Publicitario
>.
---


## 1.3. Ecuaciones de balance

[[FALTAN TODAS LAS IMAGENES]]
Ecuaciones básicas para la evolución temporal de un sistema
Evoluciónd e  las poblaciones, o más bien de las densidades de población

### Dos niveles

Transiciones y probabilidades de transicion
n atoms/vol
$n , n _ { 1 } , n _ { 2 }$ densidades de población en volumen
$\rho = \rho _ { \nu }$

Absorción, sube: $- B _ { 12 } \rho n _ { 1 }$
Emisión, baja: $+ B _ { 21 } \rho n _ { 2 }$
Emisión espontánea, baja:  $+ A _ { 21 } n _ { 2 }$

Ecuaciones básicas para la evolución del sistema:

:	$$\frac { d n _ { 1 } } { d t } = - B _ { 12 } \rho n _ { 1 } + B _ { 21 } \rho n _ { 2 } + A _ { 21 } n _ { 2 }$$

:	$
$\frac { d n _ { 2 } } { d t } = B _ { 12 } \rho n _ { 1 } - B _ { 2 } \rho n _ { 2 } - A _ { 21 } n _ { 2 } \quad ( 1.43 )$$

:	$
$n = n _ { 1 } + n _ { 2 }$ $A _ { 21 } n _ { 2 }$

$\frac { d n _ { 1 } } { d t } = - B _ { 12 } \rho n _ { 1 } + B _ { 21 } \rho n _ { 2 } + A _ { 21 } n _ { 2 }$
$\frac { d n _ { 2 } } { d t } = B _ { 12 } \rho n _ { 1 } - B _ { 2 } \rho n _ { 2 } - A _ { 21 } n _ { 2 } \quad ( 1.43 )$
$n = n _ { 1 } + n _ { 2 }$

Densidad total es la suma de los niveles.

Con esto podemos ver los números de fotones en el sistema:
: Según lo que decae
: La estimulada será para láser. Aún no lo vemos en detalle

Surge pregunta: ¿Fotones por espontánea?

Para la radiación: q es el número de fotones por unidad de volumen:

$$\frac { d q } { d t } = A _ { 21 } n _ { 2 } \quad ( 1.44 )$$

Pero esto es un esquema demasiado simple para describir el láser: Necesitaremos al menos 3 o 4 niveles involucrados.

### Tres niveles

Entre cada pareja de niveles consideraremos sólo las contribuciones de las flechas que nos den.

¿¿El numero de flechas y su orden depende de la configuración atómica??

$$Desarrollo$$

### Cuatro niveles

Pondremos el nivel fundamental como 0 para conservar la transición interesante entre 1 y 2.

Las emisiones serán o de tipo 3 o 4.
La diferencia es si la emisiín radiativa es al fundamental (3) o n (4).

Habrá que reformular porque B y A no se miden, sino las **secciones eficaces** y los **tiempos de vida**.

$$Desarrollo$$

### Medida de### Tiempos de vida

Ejemplos de sistemas cuanticos en interacción con radiación.

¿Cómo podemos entender que se mida $\tau_{vida}$?

En dos niveles:
1. Movemos la población al nivel excitado, por ej con una lámpara.
Si A21 es potente no tengo xq poner la de absorción (si es pequeña respecto a emisión)
2. Viendo la ecvolución del sistema obtenemos información del tiempo de vida.

La potencia, la intensidad de luz, decae exponencialmente con el tiempo.

¿Pero y si hubiera puesto transiciones no radiativas?

Conoceriamos el tiempo total de decaimiento $\tau$.
Con la fórmula de la eficiencia cuántica:= $\phi = \frac{\tau}{\tau_r}=\tau A$


 Quien me da fotones es A.
 Ahora decaerá con $\tau$.

¿Quiero saber también $\tau_r$?
Mido $\phi$ por otro lado.

$$Desarrollo$$



---
>.
> Intervalo Publicitario
>.
---


## 1.4. Perfiles de línea

No existe la radiación coherente monocromátca. Todo tiene anchura.

Hay tres tipos de anchura:
: Natural
: Doppler
: Colisional

### Anchura y perfil natural de línea

Asociado a que los niveles que emiten son inestables, tienen un tiempo de vida.

La frecuencia de una onda monocromática perfeca va desde menos inf a mas inf. En la vida real eso implica inf tiempo emitiendo.
Nuestros laseres emiten durnte cierto tiempo y la onda resultante es una aproximación, por eso la frecuencia no es una delta perfecta, tiene una anchura natural.

Como hemos medido en un tiempo finito sale una composicion de frecuencias centrada en $\nu_0$ pero con otras cercanas a izquierda y derecha.

Origen: Un estado excitado es inestable

Tratamiento semiclásico: Pribabilidad de transición por emisión espontánea del nivel 2 al 1

$$S _ { r a d } \left( \nu , \nu _ { 0 } \right) = \frac { 2 } { \pi \delta \nu _ { r a d } } \frac { 1 } { 1 + \left( \frac { \nu - \nu _ { 0 } } { \delta \nu _ { r a d } / 2 } \right) ^ { 2 } } \quad (1.45)$$

$$\delta \nu _ { r a d } = \frac { 1 } { 2 \pi } A _ { 21 } \quad ( 1.46 )$$

![Perfiles](im)

-	Ensanchamiento homogéneo
-	Perfil Lorentziano: $$
	-	Un perfil debe estar normalizado.
	-	Mucha base, poca altura.
-	La anchura está relacionada con $A_{21}$ y $\tau_{esp}$
-	Ensanchamiento homogéneo
	-	Afecta por igual a todos los elementos del sistema
	-	Si midieramos fluorescencia de 1 atomo o de $N_{avog}$ atomos tendríamos el mismo perfil, cambiaría la amplitud, su intensidad.

	>Ejemplo: Laser- Gas Helio Neon (emite el Neón)
	$\lambda = 632,8nm$
	...
	Ancho de línea muy pequeño, parece monocromatico porque no se puede medir el ancho.

### Anchura y perfil Doppler de línea

Origen: Los átomos o moléculas se mueven.
En su SdR emiten en $\nu_0$, pero nosotros medimos otra frecuencia: $$
Se mide un decaimiento alrededor de $\nu_0$.

$$\nu = \nu _ { 0 } \left( 1 \mp \frac { v } { c } \right) \quad ( 1.47 )$$

Un átomo a temperatura tendrá una distribución $df(v)$ de velocidades proporcional a la distribución de Boltzmann.

$$d f ( v ) = \left( \frac { m } { 2 \pi k _ { B } T } \right) ^ { 1 / 2 } e ^ { - m v ^ { 2 } / \left( 2 k _ { B } T \right) } d v \quad ( 1.48 )$$

$v = c \left( \nu - \nu _ { 0 } \right) / \nu _ { 0 }$

$d v = \frac { c } { \nu _ { 0 } } d \nu$

$$d f _ { \nu } ( \nu ) = \frac { c } { \nu _ { 0 } } \left( \frac { m } { 2 \pi k _ { B } T } \right) ^ { 1 / 2 } e ^ { \frac { - m c ^ { 2 } \left( \nu - \nu _ { 0 } \right) ^ { 2 } } { 2 k _ { B } T \nu _ { 0 } ^ { 2 } } } d \nu \propto S _ { \text { Doppler } } \left( \nu , \nu _ { 0 } \right) d \nu \quad (1.49)$$

$$\boxed {\delta \nu _ { D o p p l e r } = \left( \nu _ { 0 } / c \right) \left( 2 k _ { B } T / m \right) ^ { 1 / 2 } }$$

Perfil Gaussiano:

:	$$S _ { \text { Doppler } } \left( \nu , \nu _ { 0 } \right) = \frac { 2 \sqrt { \ln 2 } } { \sqrt { \pi } \delta \nu _ { \text {Dopler} } } e ^ { - \left( \frac { \nu - \nu _ { 0 } } { \delta \nu _ { \text {Doppler} } / 2 } \right ) ^ { 2 } \ln 2} \quad ( 1.50 )$$

![Boltz](https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Maxwell-Boltzmann_distribution_1.png/300px-Maxwell-Boltzmann_distribution_1.png)
-	Asimétrico

El perfil de velocidades nos dará el perfil de frecuencias.
Al poner la distribuciónd e Bolzmann	de velocidades en función de las frecuencias obtendremos una gaussiana

-	Perfil Gaussiano
-	No homogéneo. Unos átomos emiten con una frecuencia por desplazamiento distinto a otros, ya que se mueven de forma diferente.
-	En realidad es un desplazamiento, no un ensanchamiento.
-	Sale gaussiano porque hay poca probabilidad de encontrar velocidades más altas o mas bajas que las de la gaussiana.

[[IMAGEN; Ccjto de picos dan gaussiana]] La envolvente de esto es el perfl gaussiano de doppler.

$$

Esto si es medible en el laboratorio (aunque no con un espectrómetro).

La anchura Doppler real medida es $$

### Anchura y perfil colisional de línea

-	Debido a impactos por otros electrones, con otros átomos o fotones.
-	El sistema intenta emitir a $\nu_0$, pero el fotón choca con algo cambia de fase [[IMG]]
-	tTiempo de colisión $\sim a/v$, $a$ tamaño del átomo.
-	Onda no monocroma, en cachos tiene $\nu_0$ ($\sim \tau_{col}$) con trozos de cambio de fase, con frecuencia mucho menor ($\sim t_{col}$)
-	Depende de la presion

$$v = \left( 3 k _ { B } T / m \right) ^ { 3 / 2 }$$

$$t _ { c o l } = a / v \sim 1 A / 1000 m s ^ { - 1 } \sim 10 ^ { - 11 } s$$

Campo emitido:

:	$$E ( t ) = E _ { 0 } e ^ { - i \omega _ { 0 } t }$$

:	$$E ( \omega ) = \mathfrak { F } ( E ( t ) ) = \int _ { - \infty } ^ { + \infty } E _ { 0 } e ^ { - i \omega _ { 0 } t } e ^ { i \omega t } d t$$

Idealmente:
:	$E ( \omega ) = E _ { 0 } \int _ { t _ { 0 } } ^ { t _ { 0 } + \tau } d t$
: $t(\lambda) = t_0 e^{-i\omega_0 t}$

Tendrñiamos que coger $E(t)$ y hacer la transformada de fourier para calcular la $E(\omega)$.

Pero como tenemos cachos incoherentes:

:	$
$E ( \omega ) = E _ { 0 } \int _ { t _ { 0 } } ^ { t _ { 0 } + \tau } e ^ { - i \left( \omega _ { 0 } - \omega \right) t } d t = E _ { 0 } \frac { e ^ { - i \left( \omega _ { 0 } - \omega \right) t } } { i \left. \left( \omega _ { 0 } - \omega \right) \right| _ { t _ { 0 } } } =$$
$$= E _ { 0 } \frac { e ^ { - i \left( \omega _ { 0 } - \omega \right) t _ { 0 } } \left[ e ^ { - i \left( \omega _ { 0 } - \omega \right) \tau } - 1 \right] } { - i \left( \omega _ { 0 } - \omega \right) } ( 1.51 )$$


Pero nosotros medimos luna intensidad que emite:

:	$
$I ( \omega , \tau ) = | E ( \omega ) | ^ { 2 } = I _ { 0 } \left| \frac { e ^ { - i \left( \omega _ { 0 } - \omega \right) \tau } - \left. 1 \right| ^ { 2 } } { i \left( \omega _ { 0 } - \omega \right) } \right| ^ { 2 } ( 1.52 )$$

Idealmente:
:	$E ( \omega ) = E _ { 0 } \int _ { t _ { 0 } } ^ { t _ { 0 } + \tau } d t$
: $t(\lambda) = t_0 e^{-i\omega_0 t}$

Tendrñiamos que coger $E(t)$ y hacer la transformada de fourier para calcular la $E(\omega)$.
Pero como tenemos cachos incoherentes
$E ( \omega ) = E _ { 0 } \int _ { t _ { 0 } } ^ { t _ { 0 } + \tau } e ^ { - i \left( \omega _ { 0 } - \omega \right) t } d t = E _ { 0 } \frac { e ^ { - i \left( \omega _ { 0 } - \omega \right) t } } { i \left. \left( \omega _ { 0 } - \omega \right) \right| _ { t _ { 0 } } } = E _ { 0 } \frac { e ^ { - i \left( \omega _ { 0 } - \omega \right) t _ { 0 } } \left[ e ^ { - i \left( \omega _ { 0 } - \omega \right) \tau } - 1 \right] } { - i \left( \omega _ { 0 } - \omega \right) } ( 1.51 )$

Pero nosotros medimos una intensidad
$I ( \omega , \tau ) = | E ( \omega ) | ^ { 2 } = I _ { 0 } \left| \frac { e ^ { - i \left( \omega _ { 0 } - \omega \right) \tau } - \left. 1 \right| ^ { 2 } } { i \left( \omega _ { 0 } - \omega \right) } \right| ^ { 2 } ( 1.52 )$

Eso sí, ¿Cuál será la distribución de colisiones?

:	Por teoría cinética de gases

:	Probabilidad de colisión:= $\rho(\tau)=\frac { e ^ { - \tau / \tau _ { c o l } } } { \tau _ { c o l } }$

:	$$I ( \omega ) = \frac { I _ { 0 } } { \pi } \frac { 1 / \tau _ { c o l } } { \left( \omega - \omega _ { 0 } \right) ^ { 2 } + \left( 1 / \tau _ { c o l } \right) ^ { 2 } } ( 1.54 )$$


Para el campo total, teniendo en cuenta todas las contribuciones:

:	$$I ( \omega ) = I _ { 0 } \int _ { 0 } ^ { \infty } \left| \frac { e ^ { - i \left( \omega _ { 0 } - \omega \right) \tau } - 1 } { i \left( \omega _ { 0 } - \omega \right) } \right| ^ { 2 }\frac { e ^ { - \tau / \tau _ { c o l } } } { \tau _ { c o l } } d \tau \quad ( 1.53 )$$


Si normalizamos para tenerlo en un perfil:

Perfil Lorentziano:

:	$$S _ { c o l } \left( \nu , \nu _ { 0 } \right) = \frac { 2 } { \pi \delta \nu _ { c o l } } \frac { 1 } { 1 + \left[ \frac { \nu - \nu _ { 0 } } { \delta \nu _ { c o l } / 2 } \right] ^ { 2 } } \quad ( 1.55 )$$

:	Ensanchamiento homogéneo: $1 / \tau _ { c o l } = 2 \pi \delta \nu _ { c o l } / 2$

:	$$\tau _ { c o l } = \frac { \text { recorrido libre medio } } { \text { velocidad media } } = \frac { ( \sigma n \sqrt { 2 } ) ^ { - 1 } } { \left( 3 k _ { B } T / m \right) ^ { 3 / 2 } }$$

:	$$\sigma \sim \pi ( 2 a ) ^ { 2 }$$

:	Depende de la presión: $n = \frac { p } { k _ { B } T }$

:	$$\tau _ { c o l } = \frac { \left( m k _ { B } T \right) ^ { 1 / 2 } } { \pi \sqrt { 6 } p ( 2 a ) ^ { 2 } } \quad ( 1.56 )$$

:	$$\delta \nu _ { c o l } \geqslant \mathrm { o } \leqslant \delta \nu _ { \text {Doppler} }$$
:	Depende de la presión: $n = \frac { p } { k _ { B } T }$

En sólidos los iones colisionan con los fonones de la red. La densidad de fonones aumenta con T.

:	[[IMG]]

:	¿cual sería el ensanchamiento colisional por los fonones de la red?

#### Ejemplo 1.4.1

$T=300K$
$\overline { \nu } = \frac { 1 } { \lambda ( \mathrm { cm } ) }$

Ruby

:	$$\Delta \overline { \nu } _ { c o l } = 11 \mathrm { cm } ^ { - 1 } \Rightarrow 330 \mathrm { GHz }$$


NeodimioYag

:	Los iones de __AA__ compuestos generan ensanchamientos grandes

:	$$\Delta \overline { \nu } _ { c o l } = 4 \mathrm { cm } ^ { - 1 } \Rightarrow 120 \mathrm { GHz }$$


### Si normalizamos para tenerlo en un perfil:

Perfil Lorentziano:
:	$S _ { c o l } \left( \nu , \nu _ { 0 } \right) = \frac { 2 } { \pi \delta \nu _ { c o l } } \frac { 1 } { 1 + \left[ \frac { \nu - \nu _ { 0 } } { \delta \nu _ { c o l } / 2 } \right] ^ { 2 } }$
:	Ensanchamiento homogéneo: $1 / \tau _ { c o l } = 2 \pi \delta \nu _ { c o l } / 2$
:	Depende de la presión: $n = \frac { p } { k _ { B } T }$

En sólidos los iones colisionan con los fonones de la red. La densidad de fonones aumenta con T. [[IMG]]
:	¿cual sería el ensanchamiento colisional por los fonones de la red?

NeodimioYag
:	Los iones d

Coeficientes integrales de Einstein:

:	Tienen más sentido integrando a varias frecuencias

$$A = \int _ { 0 } ^ { \infty } A S \left( \nu , \nu _ { 0 } \right) d \nu$$

$$B = \int _ { 0 } ^ { \infty } B S \left( \nu , \nu _ { 0 } \right) d \nu$$




---
>.
> Intervalo Publicitario
>.
---


## 1.5 Secciones eficaces

Area asociada a un atomo, tal que si el foton pasa cerca del atomo éste es excitado.

### Coeficientes diferenciales de Einstein

$$d A = A S \left( \nu , \nu _ { 0 } \right) d \nu$$

$$d B = B S \left( \nu , \nu _ { 0 } \right) d \nu$$


### Probabilidades de transición

¿Qúe le pasa a un medio cuando pasa radiación que puede absorber?

Las probabilidades de transición en el intervalo $d\mu$ son:

:	$$d p _ { e m } ^ { e s p } ( \nu ) = A S \left( \nu , \nu _ { 0 } \right) d \nu$$

:	$$d p _ { a b s } ^ { e s t } ( \nu ) = d p _ { e m } ^ { e s t } ( \nu ) = B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) d \nu$$

:	$$\int _ { 0 } ^ { \infty } S \left( \nu , \nu _ { 0 } \right) d \nu = 1$$


$\rho _ { \nu } ( \nu )$ es la densidad de energía por unidad de volumen e intervalo de frecuencia

---

#### Ejemplo 1.5.1
##### Medio dos niveles.

densidad de átomos $n _ { 1 }$ y $n _ { 2 }$


---
>.
> Intervalo Publicitario
>.
---


## 1.5 Secciones eficaces

Area asociada a un atomo, tal que si el foton pasa cerca del atomo éste es excitado.

### Coeficientes diferenciales de Einstein
### Probabilidades de transición

¿Qúe le pasa a un medio cuando pasa radiación que puede absorber?

Medio dos niveles.
: Un átomo absorbe $B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu )$

: Pero coo tenemos $n_1$ en el estado:

:	$$\frac { d N _ { a b s } ( \nu ) } { d V d t d \nu } = B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 }$$

:	Y por tanto, como la absorción altera la densidad de energía:

: $\frac { d N _ { a b s } ( \nu ) h \nu } { d V d \nu } = - d \rho _ { \nu } ( \nu ) \Rightarrow \frac { d \rho _ { \nu } ( \nu ) } { d t } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } h \nu$


¿Cuánta E se pierde entonces?

: Multiplico por hv

: $\frac { d \rho _ { \nu } ( \nu ) } { d t } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } h \nu$


Para estimulada igual:

: $\frac { d N _ { e m } ^ { e s t } ( \nu ) h \nu } { d V d \nu } = d \rho _ { \nu } ( \nu ) \Rightarrow \frac { d \rho _ { \nu } ( \nu ) } { d t } = B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 2 } h \nu$

> Esto es como la ecuación de q pero para $\rho$


Para secciones eficaces nos interesa en función de z:

: $d z = c d t$

: Atenuación por unidad de longitud:

:	$$\frac { d \rho _ { \nu } ( \nu , z ) } { d z } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } \frac { h \nu } { c }$$

Esto está en función $B*S*rho$
Pero para secciones no interesa

---

### Secciones eficaces

Es útil definir secciones eficaces para la absorción

![Cilindro Seccion Eficaz
](https://lh3.googleusercontent.com/7XIRGoPGRl4smvt2qU2uxdtEr0vuwkc5OkduKzDVB41iWFpCPRyCU3LBhBWf7JiASdiddlUSChZH "1.5 SeccEff")

Medio con densidades de átomos por unidad de volumen $n , n _ { 1 } , n _ { 2 }$

En el volumen $S d z$ hay $n _ { 1 } S d z$ átomos en el estado 1

Nº transiciones por unidad de tiempo = nº átomos x nº transiciones de absorción de un átomo por unidad de tiempo

$$n _ { a b s } = n _ { 1 } S d z \times I \sigma _ { a b s } / h \nu$$

La energía absorbida por unidad de área y tiempo es $E _ { a b s } = n _ { a b s } h \nu / S$

Y la intensidad de luz a la salida será:

$$I ( \nu , z + d z ) = I ( \nu , z ) - n _ { 1 } d z I ( \nu , z ) \sigma _ { a b s } ( \nu )$$

Por tanto

$$\frac { I ( \nu , z ) } { d z } = - n _ { 1 } I ( \nu , z ) \sigma _ { a b s } ( \nu )$$

Análogamente para la emision estimulada

$$\frac { d I ( v , z ) } { d z } = n _ { 2 } I ( v , z ) \sigma _ { e m } ( v )$$

En el volumen $S d z$ hay contenida la energía $I S d t = I S d z / c$
Y la energía por unidad de volumen es

$$\rho _ { \nu } ( \nu ) = I S d z / ( c S d z ) = I / c$$

Por tanto

$$\frac { \rho _ { \nu } ( \nu , z ) } { d z } = - n _ { 1 } \rho _ { \nu } ( \nu , z ) \sigma _ { a b s } ( \nu )$$

Comparando con

$$\frac { d \rho _ { \nu } ( \nu , z ) } { d z } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } \frac { h \nu } { c } \Rightarrow \sigma _ { a b s } ( \nu ) = \frac { h \nu } { c } B S ( \nu )$$

Y por la igualdad entre coeficientes $\mathrm { B }$ de Einstein

$$\sigma _ { e m } ^ { e s t } ( \nu ) = \frac { h \nu } { c } B S ( \nu )$$




---
>.
> Intervalo Publicitario
>.
---


## 1.6 Espectros de absorción y emisión

Determinación de $\sigma$ a partir de medidas de intensidad
Absorción:

![Absorción
](https://lh3.googleusercontent.com/N1FooYLOnWC6bElYZe_n_ktNnWlGKDZr89lkj4xbXA1xA-L7OO4EsKxzPxspzBCkQOF4dY92eqaF "1.6 Absorcion")

$$\int _ { I _ { 0 } } ^ { I } \frac { d I ( z ) } { I ( z ) } = \int _ { 0 } ^ { z } - n _ { 1 } \sigma _ { a b s } ( \nu ) d z \quad n _ { 1 } = \mathrm { ctell } !$$

 Ley de Lambert-Beer

:	$$\boxed{I ( \nu , z ) = I _ { 0 } ( \nu ) e ^ { - n _ { 1 } \sigma _ { a b s } ( \nu ) z } }$$

Para $z = L$ tenemos el espectro de absorción o absorbancia $A(\mu)$

$$A ( \nu ) = - \log \frac { I ( \nu , L ) } { I _ { 0 } ( \nu ) } = \sigma _ { a b s } ( \nu ) n _ { 1 } L \log e$$

Para la emisión estimulada, sabiendo que

$$\quad \frac { A } { B } = \frac { 8 \pi h \nu ^ { 3 } } { c ^ { 3 } }$$

$$\sigma _ { e m } ^ { e s t } ( \nu ) = \frac { c ^ { 2 } } { 8 \pi \nu ^ { 2 } } \frac { 1 } { \tau } S ( \nu )$$




---
>.
> Intervalo Publicitario
>.
---


## 1.7 Ecuaciones de balance

Consideremos sitema 4 niveles $\sigma _ { a b s }$ y la emisión estimulada $\sigma _ { e m }$

![
Sys4Nivel](https://lh3.googleusercontent.com/vUZ41c3RZMV91hF4H-amA-nuwHmZ_1aojEsWnQVE0UXsT-sEdJ8nCTgg9zt7CYwtuHARejfuirAd "1.7 Sys 4 Niveles")

$$
\frac { d I ( \nu , t ) } { d t } = c \left[ - n _ { 1 } ( t ) \sigma _ { 12 } ^ { a b s } ( \nu ) + n _ { 2 } ( t ) \sigma _ { 21 } ^ { e m } ( \nu ) \right] I ( \nu , t ) + \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } \phi h \nu c S _ { e m } ( \nu )
$$

$$\frac { d n _ { 3 } ( t ) } { d t } = n _ { 0 } ( t ) \sigma _ { 03 } ^ { a b s } ( \nu ) \frac { I _ { 03 } ( t ) } { h \nu _ { 03 } } - \frac { n _ { 3 } ( t ) } { \tau _ { 32 } ^ { n r } }$$

$$\frac { d n _ { 2 } ( t ) } { d t } = \frac { n _ { 3 } ( t ) } { \tau _ { 32 } ^ { n r } } + \left[ n _ { 1 } ( t ) \sigma _ { 12 } ^ { a b s } ( \nu ) - n _ { 2 } ( t ) \sigma _ { 21 } ^ { e m } ( \nu ) \right] \frac { I ( \nu , t ) } { h \nu } - \frac { n _ { 2 } ( t ) } { \tau _ { 21 } }$$

$$\frac { d n _ { 1 } ( t ) } { d t } = \left[ - n _ { 1 } ( t ) \sigma _ { 12 } ^ { a b s } ( \nu ) + n _ { 2 } ( t ) \sigma _ { 21 } ^ { e m } ( \nu ) \right] \frac { I ( \nu , t ) } { h \nu } + \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } - \frac { n _ { 1 } ( t ) } { \tau _ { 10 } ^ { n r } }$$

$$n _ { T } = n _ { 0 } ( t ) + n _ { 1 } ( t ) + n _ { 2 } ( t ) + n _ { 3 } ( t )$$



---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---




---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---


# 2. Amplificación de la radiación



---
>.
> Intervalo Publicitario
>.
---


## 2.1 Principios básicos del láser

### Amplificación de radiación

#### Dos Niveles

Uno no puede amlificar radiación con $\nu_{21}$. No se podrá poner más radiación en el sistema 2 que en el 1.
En equilibrio térmico no se puede.

$$\frac { d I ( t ) } { d t } = c \left[ - n _ { 1 } ( t ) \sigma _ { 12 } ^ { a b s } + n _ { 2 } ( t ) \sigma _ { 21 } ^ { e m } \right] I ( t ) + \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } h v c \phi S _ { e m }$$

$$
\frac { d n _ { 2 } ( t ) } { d t } = \left[ n _ { 1 } ( t ) \sigma _ { 12 } ^ { a b s } - n _ { 2 } ( t ) \sigma _ { 21 } ^ { e m } \right] \frac { I ( t ) } { h v } - \frac { n _ { 2 } ( t ) } { \tau _ { 21 } }
$$

$$
n _ { T } = n _ { 1 } ( t ) + n _ { 2 } ( t )
$$

$$
 B _ { 12 } = B _ { 21 }
$$

y por tanto

$$\sigma ^ { a b s } = \sigma ^ { \mathrm { em } } _ { 21 } = \sigma \mathrm { y } A _ { 21 } / B _ { 21 } = 8 h \pi \mathrm { v } ^ { 3 } / c ^ { 3 }
$$

y por tanto

$$
\mathrm { S } _ { 21 } ^ { \mathrm { em } } / \tau _ { 21 } = \mathrm { cte }
$$

En equilibrio térmico {} n _ { 1 } > > n _ { 2 } }

$$
\frac { d I } { d z } = \left[ - n _ { 1 } + n _ { 2 } \right] \sigma I + \frac { n _ { 2 } } { \tau _ { 21 } } h v \phi S _ { e m }
$$

No se amplifica la radiación

Hay que sacar al sistema del equilibrio térmico. Con 2  niveles no se puede



### Inversión de población

### Bombeo


#### Tres Niveles

Si el ritmo de subida es mayor que el ritmo de bajada, el 2 se me llena más rápido de lo que se vacía, y $n_2$ puede ser mayor que $n_1$

$$
\begin{array} { l } { \frac { d I ( t ) } { d t } = c \left[ - n _ { 1 } ( t ) + n _ { 2 } ( t ) \right] \sigma I ( t ) + \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } \phi h v c S _ { e m } } \\ { \frac { d n _ { 3 } ( t ) } { d t } = n _ { 1 } ( t ) \sigma _ { 13 } ^ { a b s } \frac { I _ { 13 } ( t ) } { h v _ { 13 } } - \frac { n _ { 3 } ( t ) } { \tau _ { 32 } ^ { n r } } } \end{array}
$$

$$
\begin{aligned} \frac { d n _ { 2 } ( t ) } { d t } & = \frac { n _ { 3 } ( t ) } { \tau _ { 32 } ^ { n r } } + \left[ n _ { 1 } ( t ) - n _ { 2 } ( t ) \right] \sigma \frac { I ( t ) } { h v } - \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } \\ n _ { T } & = n _ { 1 } ( t ) + n _ { 2 } ( t ) + n _ { 3 } ( t ) \end{aligned}
$$

$$
\begin{array} { l } { \text { Para que crezca la intensidad tiene que cumplirse que } \frac { d I } { d t } > 0 } \\ { c \left[ n _ { 2 } ( t ) - n _ { 1 } ( t ) \right] \sigma I ( t ) > - \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } \phi h v c S _ { e m } } \end{array}
$$



Solucion pequeña señal

:	$$
\frac { d I ( t ) } { d t } = c \left[ - n _ { 1 } ( t ) + n _ { 2 } ( t ) \right] \sigma I ( t ) + \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } \phi h v c S _ { e m }
$$

:	$$
\frac { d I ( z ) } { d z } = \left[ - n _ { 1 } ( z ) + n _ { 2 } ( z ) \right] \sigma I ( z )
$$

:	El termino de fluorescencia se desprecia por...

:	$$
\boxed{ I ( z ) = I ( 0 ) e ^ { \sigma \left( n _ { 2 } - n _ { 1 } \right) z }}
$$

:	Equivalente a la ley de Lambert-Beer


### Ganancia

$$
e ^ { \sigma \left( n _ { 2 } - n _ { 1 } \right) z } \quad \text { Ganancia g o atenuación } \alpha
$$

$$
\begin{array} { l } { n _ { 2 } > n _ { 1 } \Rightarrow g = \sigma \left( n _ { 2 } - n _ { 1 } \right) ; g ( v ) = \sigma ( v ) \left( n _ { 2 } - n _ { 1 } \right) ; e ^ { g z } } \\ { n _ { 2 } < n _ { 1 } \Rightarrow \alpha = \sigma \left( n _ { 1 } - n _ { 2 } \right) ; \alpha ( v ) = \sigma ( v ) \left( n _ { 1 } - n _ { 2 } \right) ; e ^ { - \alpha z } } \end{array}
$$

![Absorcion-Atenuacion](laser-21-2atenuaabsor.png)

$$
\begin{array} { l } { \sigma = 10 ^ { - 18 } \mathrm { cm } ^ { 2 } } \\ { \mathrm { n } _ { 2 } - \mathrm { n } _ { 1 } = 1.110 ^ { 20 } \mathrm { cm } ^ { - 3 } } \end{array}
$$

¡Puede ser sin espejos! ASE, (Amplified Spontaneous Emission)




---
>.
> Intervalo Publicitario
>.
---


## 2.2 Osciladores láser

### Resonadores ópticos

Los resonadores ópticos más sencillos son [Fabry-Perot](wiki)




La diapo tachada la veremos al final del tema, para entender algo mejor lo de coherencia.

#### Fabry-Perot

El Fabry-Perot trabaja como confinador de fotones.

Dependiendo del indice de refracción de los espejos se define el **tiempo de vida del fotón en la cavidad**

El fotón va hacia la derecha, tendrá probabilidades de salir (ser transmitido) y de volver (ser reflejado)

¿Cada cuñanto tiempo llegan fotones al espejo de la cavidad?

:	$nL/c_o$

:	Con lo que la probabilidad de que un fotón llegue al espejo es: $c _ { 0 } / n L$

:	Con lo que la probabilidad de que un fotón salga es: $( 1 - \mathscr { R } ) c _ { 0 } / n L$


Tiempo de vida del fotón en la cavidad
:	$$t _ { C } = \frac { n L } { c _ { 0 } ( 1 - \mathscr { R } ) } = \frac { 1 } { 2 \pi \delta v }$$


#### Otra forma

![Espejo R1R2](laser-21-3r1r2)

Sea $\quad R = \sqrt { R _ { 1 } R _ { 2 } }$


Después de i/v la intensidad ha cambiado $R ^ { 2 } I _ { 0 }$
Después de n recorridos $( R ) ^ { 2 n } I _ { 0 }$

> ¿Cuantos recorridos hacen falta para que la intensidad decaiga en $I_o/e$?

Sea $n _ { c }$ el nº de recorridos para que la intensidad se reduzca en 1$/ \mathrm { e }$

$$\frac { I _ { 0 } } { e } = I _ { 0 } ( R ) ^ { 2 n _ { c } } ;\quad n _ { c } = - \frac { 1 } { 2 \ln R }$$

El tiempo que permanece en la cavidad

:	$\quad t _ { c } = \frac { 2 L n _ { c } } { c } = - \frac { L } { c \ln R } =^{R\approx 1} \frac { L } { c } \frac { 1 } { 1 - R }$

:	No son la misma!

_	Es porque si desarrollas la del ln (que es la buena) en taylor para intensidades bajas llegas a la otra.

Si hay transmitancia interna $\mathrm { T } _ { 1 } \quad t _ { c } = - \frac { L } { c \ln \left( R T _ { i } \right) }$

#### Factor de calidad

$Q = 2 \pi$ energía en el instante t/ la que se pierde en un ciclo T


En un ciclo $\mathrm { T } = 1 / v _ { \mathrm { e } }$ abandonan la cavidad $n _ { f } T / t _ { c }$ fotones
y se pierde una energia (por ciclo) $n _ { f } T h v _ { e } / t _ { c }$

### Condición umbral

> ¿Cómo se me amplifica la radiación en un sistema con espejos?

 Tenemos que incorporar a la evolución de las poblaciones de los niveles el resonador de la cavidad, es decir, añadir que va perdiendo Intensidad según choca con las paredes

$-\frac{I}{t_c}$

Imaginemos que metemos una I, con tiempo de vida

En este caso no es suficiente con tener inversión de problación.

:	**Condición umbral**: La ganancia tiene que ser superior a las pérdidas.

Ignorando flurescencia:

$$
\sigma \left( n _ { 2 } - n _ { 1 } \right) _ { u } = \frac { 1 } { c t _ { c } } = \sigma \left( n _ { i } \right) _ { u } \Rightarrow \boxed{ n _ { i u } = \frac { 1 } { \sigma c t _ { c } } ; c = \frac { c _ { 0 } } { n } }
$$
Apreciar el subindice u de umbral en $(n_i)_u$

Recordar $t _ { c } = - \frac { n L } { c _ { 0 } \ln R }$

En estado estacionario

:	$$
n _ { 1 u } \frac { I _ { 13 } } { h v _ { 13 } } \sigma _ { 13 } ^ { a b s } + \left( n _ { 1 } - n _ { 2 } \right) _ { u } \sigma \frac { I } { h v } - \frac { n _ { 2 u } } { \tau _ { 21 } } = 0
$$

En el umbral I = 0m $n_1 = n_{1u},\quad n_2 = n_{2u}$

Bombeo Umbral:

:	$$
\left( I _ { 13 } \right) _ { u } = \frac { n _ { i u } + n _ { T } } { n _ { T } - n _ { i u } } \frac { h v _ { 13 } } { \sigma _ { 13 } ^ { a b s } } \frac { 1 } { \tau _ { 21 } } = \frac { n _ { T } + \frac { 1 } { \sigma c t _ { c } } } { n _ { T } - \frac { 1 } { \sigma c t _ { c } } } \frac { h v _ { 13 } } { \tau _ { 21 } \sigma _ { 13 } ^ { a b s } }
$$

#### Problema tipo 2.1
DATOS: [I, $\tau$,...]


 : Atenuación por unidad de longitud: $\frac { d \rho _ { \nu } ( \nu , z ) } { d z } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } \frac { h \nu } { c }$

Esto está en función B*S*rho
Pero para secciones no interesa

$X = \alpha_o$
: lol


$$
\frac{d n_{1}}{d t}=-\frac{n_{1}}{T_{10}}+\frac{n_{2}}{T_{21}}+\sigma\left(n_{2}-n_{1}\right) I
$$

$$
\frac{d n_{2}}{d t}=P-\frac{n_{2}}{T_{21}}+\sigma\left(n_{2}-n_{1}\right) I
$$

$$
n_{3} \approx 0
$$

$$
\frac{d I}{d t}=c \sigma\left(n_{2}-n_{1}\right) I+\frac{n_{2}}{T_{21}} \operatorname{ch} v-\frac{I}{T_{c}}
$$
