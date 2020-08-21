## # Parte 1: Láser

[TOC]


# 1. Emisión en la materia

## 1.1. Cuerpo nero

Cavidad llena de medio homogeneo isotropo

Densidad de energia electromagnetica emitida a cierta temperatura: 
$\rho = \frac { 1 } { 2 } \varepsilon E ^ { 2 } + \frac { 1 } { 2 } \mu H ^ { 2 } \quad ( 1.1 )$

> Queremos calcular la densidad espectral de energía por unidad de volumen e intervalo de frecuencias: $\rho _ { \nu } ( \nu , T )$
>> OJO! Hay distintas magnitudes parecidas, tanto por significado como por letra, que miden cosas distintas! [[EJEMPLOS]]:
> Densidad de energía por unidad de volumen: = $\rho ( T ) = \int _ { 0 } ^ { \infty } \rho _ { \nu } ( \nu , T ) d \nu \quad ( 1.2 )$

CAmpos electromagnéticos deben cumplir la ecuacion de ondas 
$\nabla ^ { 2 } \overline { E } - \frac { 1 } { c ^ { 2 } } \frac { \partial ^ { 2 } \overline { E } } { \partial t ^ { 2 } } = 0 \quad ( 1.3 ) \quad \overline { E } \times \overline { n } = 0 \quad ( 1.4 )$ 
que se anula en las paredes de la cavidad, las cuales por cierto son completamente conductoras.

Integramos por separacion de variables y obtenemos: $\begin{array} { l l } { \quad \overline { E } = \overline { U } ( x , y , z ) A ( t ) } & { ( 1.5 ) } \\ { \nabla ^ { 2 } \overline { U } = - k ^ { 2 } \overline { U } } & { ( 1.6 a ) } & { \frac { \partial ^ { 2 } A } { d t ^ { 2 } } = - ( c k ) ^ { 2 } A } & { ( 1.6 b ) } \end{array}$

$$ \begin{array} { l } { A ( t ) = A _ { 0 } \operatorname { sen } ( \omega t + \varphi ) \quad ( 1.7 ) \quad \omega = c k } \\ { U _ { x } = e _ { x } \cos k _ { x } x \sin k _ { y } y \sin k _ { z } z } \\ { U _ { y } = e _ { y } \sin k _ { x } x \cos k _ { y } y \sin k _ { z } z } \\ { U _ { z } = e _ { z } \sin k _ { x } x \sin k _ { y } y \cos k _ { z } z } \\ { k _ { x } ^ { 2 } + k _ { y } ^ { 2 } + k _ { z } ^ { 2 } = k ^ { 2 } \quad ( 1.9 ) } \end{array}
\begin{array} { l } { k _ { x } = \frac { l \pi } { 2 a } } \\ { k _ { y } = \frac { m \pi } { 2 a } \quad ( 1.10 ) } \\ { k _ { z } = \frac { n \pi } { L } } \\ { l , m , n \in Z + } \end{array}$$

> Nta para U: $$

[[IMAGENES]]: Cavidad y longitudes de onda.

¿Cuál será la distribucion de modos para esta cavidad?
:	La solución de la ecuación de onda en dicha cavidad con condiciones de contorno igual a 0 en los bordes.

Frecuencias que pueden oscilar: $\begin{array} { c } { \omega = c k = c \frac { 2 \pi } { \lambda } = 2 \pi \nu } \\ { \omega ^ { 2 } = c ^ { 2 } k ^ { 2 } = c ^ { 2 } \left[ \left( \frac { l \pi } { 2 a } \right) ^ { 2 } + \left( \frac { m \pi } { 2 a } \right) ^ { 2 } + \left( \frac { n \pi } { L } \right) ^ { 2 } \right] \quad ( 1.11 ) } \end{array}$

Además $\nabla \cdot \overline { U } = 0 \Rightarrow \overline { e } \cdot \overline { k } = 0 \quad ( 1.12 )$:
Hay dos polarizaciones
[[IMAGEN]]: Polarizaciones, modos

#### ¡Pregunta 1!
	 Demostrar que la frecuencia minima depende del ratio entre 2a y L 
	 y que de (l m n) al menos dos deben ser distintos de cero. 
	 (Si no Ux Uy Uz son 0. 
	 Pej. si sólo l es distinto de 0 se anulan Uy y Uz)

$$

Calculemos la densidad de modos (contar modos en esa frecuencia): $\widehat { \rho } ( \nu )$ = número de modos por volumen y unidad de intervalo de frecuencia


[[IMAGEN]] dV

Esféricas:

$$Desarrollo$$

El 1/8 viene de que sólo integramo un cuadrante del espacio: $n,l,m\in Z^+$

Densidad de modos por unidad de volumen e intervalo de frecuencias: $\widehat { \rho } ( \nu ) = 8 \pi \frac { \nu ^ { 2 } } { c ^ { 3 } } \quad ( 1.18 )$

> Pero queremos densidad de energía!
> $\rho _ { \nu } ( \nu , T ) = \widehat { \rho } ( \nu ) < E > \quad ( 1.19 )$

Estadística de Boltzman:
:	$< E > = \frac { \int _ { 0 } ^ { \infty } E \exp \left[ - \left( E / k _ { B } T \right) \right] d E } { \int _ { 0 } ^ { \infty } \exp \left[ - \left( E / k _ { B } T \right) \right] d E } = k _ { B } T \quad ( 1.20 )$
:	Energía por modo

Ecuación de Rayleigh-Jeans
:	$\rho _ { \nu } ( \nu , T ) = 8 \pi \frac { \nu ^ { 2 } } { c ^ { 3 } } k _ { B } T \quad ( 1.21 )$
:	Válida para altas T y bajas frecuencias
:	Implica una densidad total de energía infinita

Hipótesis de Planck:
:	Cada modo tiene energía múltiplo entero de $h\nu$

:	$< E > = \frac { \sum _ { 0 } ^ { \infty } n h \nu \exp \left[ - n h \nu / k _ { B } T \right] } { \sum _ { 0 } ^ { \infty } \exp \left[ - n h \nu / k _ { B } T \right] } = \frac { h \nu } { \exp \left( h \nu / k _ { B } T \right) - 1 } \quad ( 1.22 )$
:	$\rho _ { \nu } ( \nu , T ) = \frac { 8 \pi \nu ^ { 2 } } { c ^ { 3 } } \frac { h \nu } { \exp \left( \frac { h \nu } { k _ { B } T } \right) - 1 } \quad ( 1.23a )$

Para tenerlo en $\omega$: $\rho _ { \omega } d \omega = \rho _ { \nu } d \nu \Rightarrow \rho _ { \omega } = \frac { \rho _ { \nu } } { 2 \pi } = \frac { \omega ^ { 2 } } { \pi ^ { 2 } c ^ { 3 } } \frac { \hbar \omega } { \exp \left( \frac { \hbar \omega } { k _ { B } T } \right) - 1 } \quad ( 1.23 b )$

Número de fotones: $U _ { \nu } = \frac { \rho _ { \nu } } { h \nu } = \frac { 8 \pi \nu ^ { 2 } } { c ^ { 3 } } \frac { 1 } { \exp \left( \frac { h \nu } { k _ { B } T } \right) - 1 }$

Densidad de energía $\propto 8\pi \nu^3$
Número de forones $\propto 8\pi \nu^2$

Ejemplos para distintas T: [[IMAGEN]] U frente lambda

Densidad de radiación en W/Sr

Luminancia:$=L=$

En términos de $\lambda$: $$


## 1.2. Probabilidades de transición

Estudiaremos la lámpara de sodio as usual.

[[IMAGEN]]

Un cuerpo negro también debería poder estar en equilibrio.

Einstein:
:	Contad!
:	Un cuerpo negro descrito por el formalismo cuántico debe ser capaz de estar en equilibrio con la radiación circundante.

[[IMAGEN]]
Hay una probabilidad de absorción, una **sección eficaz**, no absorberá siempre.

### Coeficientes de Einstein

^rpbabilidad de absorción $\propto$ número de fotone que haya

$$

> Coeficiente de Einstein para absorción

También emitirá con cierta probabilidad, pero de manera espontánea, no dependerá de que haya radiación.

> Coeficiente de Einstein para emisión

Para un sistema en equilibrio $$ g_1 g_2 para niveles degenerados
Distribución de Boltzmann

Veamos cuántas absorciones se producen en el estado fundamental (por unidad de tiempo)
$$

Es la densidad de radiación de un sistema cuántico en equilibrio que emite y absorbe.
PEro no es la ley de Plank! Y debería. Así que debe de estar mal.

Einstein dedujo que habrá más procesos:

> Coeficiente de Einstein para emisión estimulada

Estado excitado + Fotones de fuera = Emisión estimulada

$$

#### ¡Pregunta 2!
		¿Sólo afecta a los fotones con esa frecuencia?
		O si tienen otras afecta?
Respuesta
:	Creo que sólo esos....

$$Desarrollo$$

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
: $$\frac { B _ { 12 } } { B _ { 21 } } = \frac { g _ { 2 } } { g _ { 1 } } \quad ( 1.35 )$$

: $$\frac { A _ { 21 } } { B _ { 21 } } = \frac { 8 \pi h \nu ^ { 3 } } { c ^ { 3 } } \quad ( 1.36 )$$

$A _ { 21 } = \frac { 16 \pi ^ { 3 } \nu ^ { 3 } n | \mu | ^ { 2 } } { 3 h \varepsilon _ { 0 } C _ { 0 } ^ { 3 } } \quad (1.37)$

$g _ { 2 } B _ { 21 } = g _ { 1 } B _ { 12 } = \frac { 2 \pi ^ { 2 } } { 3 n ^ { 2 } \varepsilon _ { 0 } h ^ { 2 } } | \mu | ^ { 2 } \quad ( 1.38 )$

### Tiempos de vida.

Con la teoría cuántica + Ecuación de la Dinámica A12 y B21 dependen de los momentos dipolares.

$H_{perturbación} = (-er)$

Teoría de perturbaciones entre estado final e inicial.
Obtenemos un $\mu = \int \varphi _ { 2 } ^ { * } ( r ) ( - e r ) \varphi _ { 1 } ( r ) d V \quad ( 1.39 )$


Y se obtiene que $A_{21}$ se puede medir: 
> Tiempo de vida media (o de vida natural): = $\tau _ { 21 } = \tau _ { e s p } = 1 / A _ { 21 }$

B no es tan medible pero sí se puede deducir desde la sección eficaz en absorción.

#### Ejercicio 1.1:
> Cuerpo negro a $T = 1000K$. Calcular la frecuencia para la cual la probabilidad de emisión espontánea es 10 veces mayor que la estimulada.

[[[ACABAR]]]

### Transiciones no radiativas. Eficiencia cuántica.

La forma de desexcitarse el estado si emite radiación se llama radiativa.
Si no emmite luz tenemos transiciones no radiativas. Pej. el fotón choca con una pared, por impacto electrónico, reajustes moleculares...
Hay diferentes vías de desexcitación.

Hay una eficiencia para devolver la radiación!

> Probabilidad total de desexcitación: = $$

> Eficiencia cuántica: = $$

La eficiencia cuántica siempre es menor que 1, es el ratio enrtre las probabilidades de radiación espontánea y la de desexcitación total.

$\phi$ y $\tau$ se pueden medir.

**EN EL SIGUIENTE CAPÍTULO!!**
: ¿Cómo evolucionan las poblaciónes en funciónd del tiempo?


## 1.3. Ecuaciones de balance

[[FALTAN TODAS LAS IMAGENES]]
Ecuaciones básicas para la evolución temporal de un sistema
Evoluciónd e  las poblaciones, o más bien de las densidades de población

### Dos niveles

Transiciones y probabilidades de transicion
n atoms/vol

Absorción, sube: $- B _ { 12 } \rho n _ { 1 }$
Emisión, baja: $+ B _ { 21 } \rho n _ { 2 } $
Emisión espontánea, baja:  $ A _ { 21 } n _ { 2 }$

$\frac { d n _ { 1 } } { d t } = - B _ { 12 } \rho n _ { 1 } + B _ { 21 } \rho n _ { 2 } + A _ { 21 } n _ { 2 }$
$\frac { d n _ { 2 } } { d t } = B _ { 12 } \rho n _ { 1 } - B _ { 2 } \rho n _ { 2 } - A _ { 21 } n _ { 2 } \quad ( 1.43 )$
$n = n _ { 1 } + n _ { 2 }$

Densidad total es la suma de los niveles.

Con esto podemos ver los números de fotones en el sistema:
: Según lo que decae
: La estimulada será para láser. Aún no lo vemos en detalle

Surge pregunta: ¿Fotones por espontánea?
Para la radiación: q es el número de fotones por unidad de volumen:
$\frac { d q } { d t } = A _ { 21 } n _ { 2 } \quad ( 1.44 )$

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

### Tiempos de vida

Ejemplos de sistemas cuanticos en interacción con radiación.

¿Cómo podemos entender que se mida $\tau_{vida}$?

En dos niveles:
1. Movemos la población al nivel excitado, por ej con una lámpara.
Si A21 es potente no tengo xq poner la de absorción (si es pequeña respecto a emisión)
2. Viendo la evolución del sistema obtenemos información del tiempo de vida.

La potencia, la intensidad de luz, decae exponencialmente con el tiempo.

¿Pero y si hubiera puesto transiciones no radiativas?

Conoceriamos el tiempo total de decaimiento $\tau$.
Con la fórmula de la eficiencia cuántica:= $\phi = \frac{\tau}{\tau_r}=\tau A$

 
 Quien me da fotones es A.
 Ahora decaerá con $\tau$.

¿Quiero saber también $\tau_r$?
Mido $\phi$ por otro lado.

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

Los átomos se mueven.
En su SdR emiten en $\nu_0$, pero nosotros medimos otra frecuencia: $$
Se mide un decaimiento alrededor de $\nu_0$.

Un átomo a temperatura tendrá una distribución $df(v)$ de velocidades proporcional a la distribución de Boltzmann.
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

Si normalizamos para tenerlo en un perfil:

Perfil Lorentziano:
:	$S _ { c o l } \left( \nu , \nu _ { 0 } \right) = \frac { 2 } { \pi \delta \nu _ { c o l } } \frac { 1 } { 1 + \left[ \frac { \nu - \nu _ { 0 } } { \delta \nu _ { c o l } / 2 } \right] ^ { 2 } }$
:	Ensanchamiento homogéneo: $1 / \tau _ { c o l } = 2 \pi \delta \nu _ { c o l } / 2$
:	Depende de la presión: $n = \frac { p } { k _ { B } T }$

En sólidos los iones colisionan con los fonones de la red. La densidad de fonones aumenta con T. [[IMG]]
:	¿cual sería el ensanchamiento colisional por los fonones de la red?

NeodimioYag
:	Los iones de __AA__ compuestos generan ensanchamientos grandes

Coeficientes integrales de Einstein:
:	Tienen más sentido integrando a varias frecuencias

## 1.5 Secciones eficaces

Area asociada a un atomo, tal que si el foton pasa cerca del atomo éste es excitado.

### Coeficientes diferenciales de Einstein
### Probabilidades de transición

¿Qúe le pasa a un medio cuando pasa radiación que puede absorber?

Medio dos niveles.
: Un átomo absorbe $B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu )$
: Pero coo tenemos $n_1$ en el estado: $\frac { d N _ { a b s } ( \nu ) } { d V d t d \nu } = B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 }$
: $\frac { d N _ { a b s } ( \nu ) h \nu } { d V d \nu } = - d \rho _ { \nu } ( \nu ) \Rightarrow \frac { d \rho _ { \nu } ( \nu ) } { d t } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } h \nu$

¿Cuánta E se pierde entonces?
: Multiplico por hv
: $\frac { d \rho _ { \nu } ( \nu ) } { d t } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } h \nu$

Para estimulada igual:
: $\frac { d N _ { e m } ^ { e s t } ( \nu ) h \nu } { d V d \nu } = d \rho _ { \nu } ( \nu ) \Rightarrow \frac { d \rho _ { \nu } ( \nu ) } { d t } = B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 2 } h \nu$

> Esto es como la ecuación de q pero para $\rho$

Para secciones eficaces nos interesa en función de z:
: $d z = c d t$
: Atenuación por unidad de longitud: $\frac { d \rho _ { \nu } ( \nu , z ) } { d z } = - B S \left( \nu , \nu _ { 0 } \right) \rho _ { \nu } ( \nu ) n _ { 1 } \frac { h \nu } { c }$

Esto está en función B*S*rho
Pero para secciones no interesa 



## 1.6 Espectros de absorción y emisión

## 1.7 Ecuaciones de balance

# 2. Amplificación de la radiación
# 3. Dinámica láser
# 4. Resonadores ópticos

## # Parte 2: Coherencia. Óptica cuántica

# 1. Coherencia clásica
# 2. Coherencia en cuántica
# 3. Óptica cuántica: Operadores y estados
# 4. Óptica cuántica: Estadística y órden


![m'Lady](http://i.imgur.com/v8IVDka.jpg)

> Written with [StackEdit](https://stackedit.io/).