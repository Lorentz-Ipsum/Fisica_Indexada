# TEMA 1
## Chapter 1 Landau
### 6 Cuadrivectores
1. Encuentra la ley de transformacion de las componentes de un tensor simétrico $A^{ik}$ bajo transformaciones de Lorentz
> Solucion:
Considerando las componentes del tensor como las componenetes de dos cuadrivectores:

$A ^ { 00} = \frac { 1 } { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } \left( A ^ { \prime 00 } + 2 \frac { V } { c } A ^ { \prime 01 } + \frac { V ^ { 2 } } { c ^ { 2 } } A ^ { \prime 11 } \right)$

$A ^ { 1  1 } = \frac { 1 } { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } \left( A ^ { \prime 11 } + 2 \frac { V } { c } A ^ { \prime 01 } + \frac { V ^ { 2 } } { c ^ { 2 } } A ^ { \prime 00 } \right)$

$A ^ { 12 } = \frac { 1 } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } } \left( A ^ { \prime 12 } + \frac { V } { c } A ^ { \prime 02 } \right)$

$A ^ { 22 } = A ^ { \prime 22 } , \quad A ^ { 23 } = A ^ { \prime 23 }$

$A ^ { 01 } = \frac { 1 } { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } \left[ A ^ { \prime 01 } \left( 1 + \frac { V ^ { 2 } } { c ^ { 2 } } \right) + \frac { V } { c } A ^ { \prime 00} + \frac { V } { c } + A ^ { \prime 11 } \right]$

$A ^ { 02 } = \frac { 1 } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } } \left( A ^ { \prime 02 } + \frac { V } { c } A ^ { \prime 12 } \right)$

Y fórmulas análogas para $A^{33}, A^{13} y A^{03}$

2. Lo mismo para el tensor antisimétrico $A^{ik}$
> Solución:
Ya que las coordenadas $x^2 y x^3$ no cambian, la componente $A^{23}$ tampoco.
Las componentes $A^{12},A^{13},A^{02} y A^{03}$ transforman como $x^1 y x^0$:
$A ^ { 23 } = A ^ { \prime 23 } , \quad A ^ { 12 } = \frac { A ^ { 12 } + \frac { V } { c } A ^ { \prime 02 } } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } } , \quad A ^ { 02 } = \frac { A ^ { \prime 02 } + \frac { V } { c } A ^ { \prime 12 } } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } }$
Y similar para $A^{13}yA^{03}$.
Con respecto a rotaciones en el plano bidimensional coordenado $x^0 x^1$ (que son las que estamos considerando) las componentes $A^{01} = -A^{10},A^{00}=A^{11}=0$ forman un tensor antisimetrico de rango dos, igual al numero de dimensiones espaciales. Por tanto dichas componentes no cambian por las transformaciones: $A^{01}=A^{\prime 01}$
### 7 Cuadrivelocidad

Determinar el movimiento relativista uniformemente acelerado, es decir: el movimiento rectilineo para el que la aceleración w en el SdR propio permanece constante.
> Solución:
En  el SdR en el que la velocidad de la partícula es 0 las componentes de la cuadriaceleración $w^i =(0,w/c^2,0,0)$ (donde w es la aceleracion ordinaria).
La condicion de invariante relativista para aceleración uniforme se expresa por:
$$w^i w_i = cte = -\frac{w^2}{c^4}$$
En el SdR fijo, dicha expresió resulta en la ecuación:
$\frac { d } { d t } \frac { v } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } = w ,$ ó $\frac { v } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } = w t + \mathrm { const. }$
Si v=0 en t=0 resulta const=0. Con lo que:
$$v = \frac { w t } { \sqrt { 1 + \frac { w ^ { 2 } t ^ { 2 } } { c ^ { 2 } } } }$$
Integrando otra vez y haciendo que x=0 para t=0:
$$x = \frac { c ^ { 2 } } { w } \left( \sqrt { 1 + \frac { w ^ { 2 } t ^ { 2 } } { c ^ { 2 } } } - 1 \right)$$
Para $wt<<c$ estas formulas resultan en la expresión clásica. Para $wt \rightarrow \infty$ la velocidad tiende a c.
El tiempo propio de la particula uniformemente acelerada viene dado por:
$$\int _ { 0 } ^ { t } \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } d t = \frac { c } { w } \sinh ^ { - 1 } \left( \frac { w t } { c } \right)$$
Cuando $t\rightarrow\infty$ aumenta mucho más lentamente que t, de acuerdo con la ley $c/w \ ln(2wt/c)$.

# TEMA 2
## Chapter 2 Landau
### 11
1. Una partícula moviendose con V se desintegra en vuelo en dos partículas.
Determinar la relacion entre angulos de emergencia y energias de estas dos particulas.
> Solución:

2. Hallar la distribucion energetica de las particulas de desintegracion en el sistema-L.
> Solución:

3. Determinar el intervalo de valores, en el sistema L, del ángulo formado por las trayectorias de dos partículas de desintegracion (su angulo de separacion) para el caso de la desintegracion en dos particulas identicas.
> Solución:

4. Hallar la distribución angular en el sistema L de partículas de desintegración de masa nula.
> Solución:

5. Hallar la distribucion de los angulos de separacion en el sistema L para una desintegracion en dos particulas de masa nula.
> Solución:

6. Determinar la energia maxima que puede llevarse una de las particulas de desintegracion cuando una particula de masa en reposo M se desintegra en tres particulas de masas m1, m2 y m3.
> Solución:
>


### 12 Secciones eficaces invariantes
Hallar el elemento de longitud en el espacio de las velocidades relativista.
> Solucion:
$$
d l _ { v } ^ { 2 } = \frac { ( d \mathrm { v } ) ^ { 2 } - ( \mathbf { v } \times d \mathbf { v } ) ^ { 2 } } { \left( 1 - v ^ { 2 } \right) ^ { 2 } } = \frac { d v ^ { 2 } } { \left( 1 - v ^ { 2 } \right) ^ { 2 } } + \frac { v ^ { 2 } } { 1 - v ^ { 2 } } \left( d \theta ^ { 2 } + \sin ^ { 2 } \theta \cdot d \phi ^ { 2 } \right)
$$
$$
d l _ { v } ^ { 2 } = d \chi ^ { 2 } + \sinh ^ { 2 } \chi \left( d \theta ^ { 2 } + \sin ^ { 2 } \theta \cdot d \phi ^ { 2 } \right)
$$

### 13

# TEMA 3
## Chapter 3 Landau

# TEMA 4
## Chapter 4 Landau
## 33
Encuentra la ley de transformacion de la densidad de energia, la densidad de flujo de energía y las componentes del tensor de tensiones bajo una transformación Lorentz.
> Solución:
Supongamos que el SdR K' se mueve relativo a K con velocidad V en el eje X.
Aplicando las fórmulas
[del priblema 6]
al tensor simétrico $T^{ik}$ obtenemos:
$W = \frac { 1 } { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } \left( W ^ { \prime } + \frac { V } { c ^ { 2 } } S _ { x } ^ { \prime } - \frac { V ^ { 2 } } { c ^ { 2 } } \sigma _ { x x } ^ { \prime } \right)$
$S _ { x } = \frac { 1 } { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } \left[ \left( 1 + \frac { V ^ { 2 } } { c ^ { 2 } } \right) S _ { x } ^ { \prime } - V W ^ { \prime } - V \sigma _ { x x } ^ { \prime } \right]$
$S _ { y } = \frac { 1 } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } } \left( S _ { y } ^ { \prime } - V \sigma _ { x y } ^ { \prime } \right)$
$\begin{array} { r l } { \sigma _ { x x } } & { = \frac { 1 } { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } \left( \sigma _ { x x } ^ { \prime } - 2 \frac { V } { c ^ { 2 } } S _ { x } ^ { \prime } - \frac { V ^ { 2 } } { c ^ { 2 } } W ^ { \prime } \right) } \\ { \sigma _ { y y } } & { = \sigma _ { y y } ^ { \prime } , \sigma _ { z z } = \sigma _ { z z } ^ { \prime } , \sigma _ { y z } = \sigma _ { y x } ^ { \prime } } \\ { \sigma _ { x y } } & { = \frac { 1 } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } } \left( \sigma _ { x y } ^ { \prime } - \frac { V } { c ^ { 2 } } s _ { y } ^ { \prime } \right) } \end{array}$
Y de forma similar para Sz y $\sigma_{xz}$

# TEMA 5
## Chapter 5 Landau
### 38
Determinar la fuerza (en el sistema K) entre dos cargas moviendose con la misma velocidad V
> Solución:
[inp]
Determinaremos la fuerza F calculando la que actúa sobre una de las cargas $e_1$ en el campo producido por la otra $e_2$.
Usando $\mathbf { H } = \frac { 1 } { c } \mathbf { V } \times \mathbf { E }$ tenemos:
$$\mathbf { F } = e _ { 1 } \mathbf { E } _ { 2 } + \frac { e _ { 1 } } { c } \mathbf { V } \times \mathbf { H } _ { 2 } = e _ { 1 } \left( 1 - \frac { V ^ { 2 } } { c ^ { 2 } } \right) \mathbf { E } _ { 2 } + \frac { e _ { 1 } } { c ^ { 2 } } \mathbf { V } \left( \mathbf { V } \cdot \mathbf { E } _ { 2 } \right)$$
Sustityendo $\mathbf { E } _ { 2 }$ por $\mathbf { E } = \frac { e \mathbf { R } } { R ^ { 3 } } \frac { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } { \left( 1 - \frac { V ^ { 2 } } { c ^ { 2 } } \sin ^ { 2 } \theta \right) ^ { 3 / 2 } }$ obtenemos las componentes de la fuerza en la dirección de movimiento y perpendicular:
$$F _ { x } = \frac { e _ { 1 } e _ { 2 } } { R ^ { 2 } } \frac { \left( 1 - \frac { V ^ { 2 } } { c ^ { 2 } } \right) \cos \theta } { \left( 1 - \frac { V ^ { 2 } } { c ^ { 2 } } \sin ^ { 2 } \theta \right) ^ { 3 / 2 } } , \quad F _ { y } = \frac { e _ { 1 } e _ { 2 } } { R ^ { 2 } } \frac { \left( 1 - \frac { V ^ { 2 } } { c ^ { 2 } } \right) ^ { 2 } \sin \theta } { \left( 1 - \frac { V ^ { 2 } } { c ^ { 2 } } \sin ^ { 2 } \theta \right) ^ { 3 / 2 } }$$
Siendo R el vector de $e_2$ a $e_1$ y $\theta$ el angulo entre R y V.
[out]
### 39
1. Determinar el ángulo de deflexión de una carga pasando por un campo de Coulomb repulsivo $(a>0)$
> Solución:

2. Determinar la sección eficaz de scattering para angulos pequeños de partículas en un campo de Coulomb.
> Solución:
### 41

Determinar el momento cuadrupolar de un elipsoide uniformemente cargado respecto a su centro.
> Solución:




# TEMA 6
## Chapter 6 Landau


# TEMA 7
## Chapter 8 Landau


# TEMA 8
## Chapter 9 Landau
