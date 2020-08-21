[TOC]
# a. Garay

## TEMA 2

$$
\left.\begin{aligned} \delta x ^ { \mu } & = i \left[ \left( \delta \omega ^ { i 0 } S _ { i 0 } + \frac { 1 } { 2 } \delta \omega ^ { i j } S _ { i j } \right) \boldsymbol { x } \right] ^ { \mu } \\ & = - i \left[ \left( \delta \zeta ^ { i } S _ { i 0 } + \frac { 1 } { 2 } \epsilon ^ { i j k } \delta \theta _ { k } S _ { i j } \right) \boldsymbol { x } \right] ^ { \mu } \\ & = - i \left[ \left( \delta \zeta ^ { i } K _ { i } + \delta \theta _ { k } S ^ { k } \right) \boldsymbol { x } \right] ^ { \mu } \\ & = - i [ ( \delta \dot { \zeta } \cdot \vec { K } + \delta \vec { \theta } \cdot \vec { S } ) x ] ^ { \mu } \end{aligned} \right.
$$

## TEMA 3

#### Densidad lagrangiana $\mathcal{L}$

$$
\frac{\delta x^\mu}{\delta\epsilon^a}
$$


________________
________________

# b. Carmelo

## TEMA 2

#### Particula newtoniana en V(x)

Le asociamos una accion:

$$
S = \int_{t_{1}}^{t_{2}} dt \mathcal{L} (\mathbf{x}(t), \partial_t\mathbf{x}(t))
$$

$$
\mathcal{L} = \frac{1}{2} m (\partial_t\mathbf{x}(t))^2 -V(x)
$$

$$
S = \int_{t_{1}}^{t_{2}} dt [\frac{1}{2} m (\partial_t\mathbf{x}(t))^2 -V(x)]
$$

Las trayectorias $\mathbf{x}(t)$ de la particula en el mundo físico son las que dejan la [[accion]] estacionaria.
Es decir, cuando

$$
\mathbf{x}(t) \rightarrow \mathbf{x}(t) + \delta \mathbf{x}(t)
$$

Con $\delta\mathbf{x}(t)$ arbitrario e infinitesimal ($\mathbf{x}(t_1)=\mathbf{x}(t_2)=0$)
Se cumplirá:

$$
\delta S = 0 + 0((\delta \mathbf{x})^2)
$$

*Vamos a demostrar que cuando [[x(t) deja S estacionaria]] es un x(t) tal que*

$$
\frac{d}{dt} \left ( \frac{\partial L}{\partial\dot{\mathbf x}} \right ) - \frac{\partial L}{\partial \mathbf x} = 0
$$

Empezamos con una pequeña variación de la acción:

$$
\delta S = S(\mathbf x+\delta\mathbf x,\dot{\mathbf x}+\delta \dot{\mathbf x})-S(\mathbf x,\dot{\mathbf x})
$$

El primer termino:


$$
S(\mathbf x+\delta\mathbf x,\dot{\mathbf x}+\delta \dot{\mathbf x}) =
\int_{t_{1}}^{t_{2}} dt \frac{1}{2} m [(\frac{d\mathbf{x}(t)}{dt}+\frac{d\mathbf{\delta x}(t)}{dt})^2 -V(\mathbf x+\mathbf{\delta x}(t))] =
$$

$$
= \int_{t_{1}}^{t_{2}} dt \frac{1}{2} m [(\frac{d\mathbf{x}(t)}{dt})^2+2\frac{d\mathbf{x}(t)}{dt}  \frac{d\mathbf{\delta x}(t)}{dt} + o((\delta \mathbf{\dot x})^2)-V(\mathbf x)-\nabla V(\mathbf x)\mathbf{\delta x}(t)+o((\delta \mathbf{x})^2)] =
$$

$$
= S(\mathbf x,\dot{\mathbf x}) + \int_{t_{1}}^{t_{2}} dt [m \frac{d\mathbf{x}(t)}{dt}\frac{d\mathbf{\delta x}(t)}{dt}-\nabla V(\mathbf x)\mathbf{\delta x}(t)+o((\delta \mathbf{x})^2)]
$$

$$
\Rightarrow \delta S = \int_{t_{1}}^{t_{2}} dt [m \frac{d\mathbf{x}(t)}{dt}\frac{d(\mathbf{\delta x}(t))}{dt}-\nabla V(\mathbf x)\mathbf{\delta x}(t)]
$$

$$
\Rightarrow \delta S = \int_{t_{1}}^{t_{2}} dt
[- m \frac{d}{dt}(\frac{d\mathbf{x}(t)}{dt})\mathbf{\delta x}(t) +  \frac{d}{dt}(m \frac{d\mathbf{x}(t)}{dt}\mathbf{\delta x}(t))  -  \nabla V(\mathbf x)\mathbf{\delta x}(t)]
$$

$$
 = \int_{t_{1}}^{t_{2}} dt
[- m \frac{d^2\mathbf{x}(t)}{dt}-  \nabla V(\mathbf x)]\mathbf{\delta x}(t) +  \int_{t_{1}}^{t_{2}} dt \frac{d}{dt}(m \frac{d\mathbf{x}(t)}{dt}\mathbf{\delta x}(t))  
$$

Donde el segundo término a su vez:

$$
 \int_{t_{1}}^{t_{2}} dt \frac{d}{dt}(m \frac{d\mathbf{x}(t)}{dt}\mathbf{\delta x}(t)) =  m \frac{d\mathbf{x}(t)}{dt}\mathbf{\delta x}(t)\int_{t_{1}}^{t_{2}} dt = 0
 $$

Ya que $\delta \mathbf x (t_i)=0$

Con lo que

$$
\delta S= -\int_{t_{1}}^{t_{2}} dt \mathbf{\delta x}(t) [m \frac{d^2\mathbf{x}(t)}{dt} + \nabla V(\mathbf x)] =  -\int_{t_{1}}^{t_{2}} dt \mathbf{\delta x}(t) [\frac{d\mathbf{p}(t)}{dt} + \nabla V(\mathbf x)] = 0
$$

$$ \Updownarrow $$

$$
\frac{d\mathbf{p}(t)}{dt} + \nabla V(\mathbf x) = 0
$$

Que es la ecuacion de movimiento de una particula Newtoniana.


#### Particula relativista

Todo esto era newton. AHora relativistamente buscamos lo mismo:
S estacionaria.

Pero lo que caracteriza a la curva es su parametro longitud de arco:

$$
S = cte \int_{t_{1}}^{t_{2}} dt \frac{d\tau}{dt} = cte \int_{t_{1}}^{t_{2}} dt \frac{c}{\gamma}
$$

Desarrollamos en taylor gamma para la velocidad

$$\gamma \approx $$

Y

$$
S = cte \cdot c\int_{t_{1}}^{t_{2}} t\cdot dt  -  cte \frac{c}{2}\frac{\mathbf v^2}{c^2}+o((\frac{\mathbf v^2}{c^2})^2)
$$

$$
S = cte \cdot c [{t_{2}}-{t_{1}}]  -  cte \frac{1}{2}\frac{\mathbf v^2}{c}+o((\frac{\mathbf v^2}{c^2})^2)
$$

Comparando con $S_{Newton}$ vemos que para que la accion no tenga unidades:

$$cte = -mc$$

$$
S = -mc \int_{\tau_{1}}^{\tau_{2}}  d\tau
$$

Invariante bajo boosts $ \Lambda ^{\mu} _{\,\,\nu}$

$$
S = \int_{t_{1}}^{t_{2}} dt (-mc ^2 \sqrt{1- \frac{\mathbf v^2}{c^2}})
$$


## TEMA 3: Cargas en campos EM

### Buscando la acción



# TEMA 3: Cargas en campos EM
## Espacios de configuración

$$
x^{\mu} \rightarrow \mathbf{E}(t,\mathbf{x}),\mathbf{B}(t,\mathbf{x}),
$$

$$
\mathbf{A}^{\mu}(t,\mathbf{x}),
$$

Espacio de configuración de la partícula
$$
x^{\mu} \rightarrow x'^{\mu} = \Lambda^{\mu}_{\,\,\nu} x^{\nu} + a^\mu,
$$

Espacio de configuración del campo EM
$$
\mathbf{A}^{\mu}(\mathbf{x}) \rightarrow \mathbf{A}'^{\mu}(\mathbf{x}') = \Lambda^{\mu}_{\,\,\nu} \mathbf{A}^{\nu}(\mathbf{x})
$$

$$
\mathbf{A}^{\mu}(\mathbf{x}) \leftrightarrow  \mathbf{A}^{\nu}(\mathbf{x})-\partial_\mu f(\mathbf{x})
$$

$$
F_{\mu \nu} = \partial _{\mu} A_{\nu} -\partial _{\nu} A_{\mu}
$$

$$
F_{\mu \nu} (A) = F_{\mu \nu} (A')
$$

$$
F_{\mu \nu} = - F_{\nu \mu}
$$


## Acción EM

$$
S_{EM} = - \frac{1}{16\pi c} \int dx^4 F_{\mu \nu} (x)F^{\mu \nu} (x)
$$

$$
\delta S_{EM} = 0 \Leftrightarrow \mathbf{A}^{\mu}(\mathbf{x}) \rightarrow \mathbf{A}^{\mu}(\mathbf{x}) + \delta \mathbf{A}^{\mu}(\mathbf{x})
$$

### Maxwell

$$
\partial_{\mu} F ^{\mu \nu} = 0
$$

$$
\mathbf{E} = F^{0i}
,
\mathbf{H} = - \frac{1}{2} \epsilon^{ijk}F^{jk}
$$

$$
A^{\mu}(x) =
\begin{pmatrix}
\phi (x) \\ A^i(x)
\end{pmatrix}
$$
___
$$
\left. \begin{array} { c }
\partial_{\mu} F ^{\mu \nu} = 0
\\ \Updownarrow \\
\nabla \cdot \mathbf{E} = 0, \quad \nabla \times \mathbf{H} = \frac {1}{c}\frac {\partial\mathbf{E}}{\partial t}
\end{array} \right.
$$
___
$$
\left. \begin{array} { c }
\epsilon^{\mu\nu\rho\sigma}\partial_{\mu} F _{\nu \rho} = \partial_{\mu} F _{\mu \rho} +\partial_{\nu} F _{\rho \mu} +\partial_{\rho} F _{\mu \nu} = 0
\\ \Updownarrow \\
\nabla \cdot \mathbf{H} = 0, \quad \nabla \times \mathbf{E} = - \frac {1}{c}\frac {\partial\mathbf{H}}{\partial t}
\end{array} \right.
$$
___
$$
\partial_{\mu} F ^{\mu \nu} = -\frac{4\pi}{c}\rho ^\nu
$$

$$
\nabla \cdot \mathbf{j} = -\frac{\partial\rho}{\partial t}
$$


________________
________________



# A. Landau, Lifshitz

## *I. Algo*
PDF Página

## *II. MECANICA RELATIVISTA*
PDF Página

### 8. Ppio minima acción

$$
S = - \alpha \int _ { a } ^ { b } d s
$$

$$
S = \int _ { t _ { 1 } } ^ { t _ { 2 } } L d t
$$

$$
S = - \int _ { i _ { 1 } } ^ { t _ { 2 } } \alpha c \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } d t
$$

$$
L = - \alpha c \sqrt { 1 - v ^ { 2 } / c ^ { 2 } }
$$

$$
L = - \alpha c \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } = - \alpha c + \frac { \alpha v ^ { 2 } } { 2 c }
$$

$$
S = - m c \int _ { a } ^ { b } d s
$$

$$
L = - m c ^ { 2 } \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } }
$$

### 9. Energia y momento

$$
\mathbf { p } = \frac { m \mathbf { v } } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } }
$$

$$
\frac { d \mathbf { p } } { d t } = \frac { m } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } \frac { d \mathbf { v } } { d t }
$$

$$
\frac { d \mathbf { p } } { d t } = \frac { m } { \left( 1 - \frac { v ^ { 2 } } { c ^ { 2 } } \right) ^ { \frac { 1 } { 2 } } } + \frac { d \mathbf { v } } { d t }
$$

*Aqui vemos la diferencia entre*

	\mathcal y \mathscr


$$
\mathcal E = \mathbf { p } \cdot \mathbf { v } - \boldsymbol { L }
$$

$$
\mathscr { E } = \frac { m c ^ { 2 } } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } }
$$

Para v peque $ ( v/c < < 1 ) $ expandiendo en potencias

$$
\mathscr { E } \approx m c ^ { 2 } + \frac { m v ^ { 2 } } { 2 }
$$

$$
\mathscr { H } = c \sqrt { p ^ { 2 } + m ^ { 2 } c ^ { 2 } }
$$

$$
\mathbf { p } = \mathscr{E} \frac { \mathbf { v } } { c ^ { 2 } }
$$

$$
P = \frac { \mathscr { E } } { c }
$$

$$
\delta S = - m c \delta \int _ { a } ^ { b } d s = 0
$$

$$
\delta S = - m c \int _ { a } ^ { b } \frac { d x _ { i } \delta d x ^ { i } } { d s } = - m c \int _ { a } ^ { b } u _ { i } d \delta x ^ { i }
$$

$$
\delta S = - m c u _ { i } \delta \left. x ^ { i } \right| _ { a } ^ { b } + m c \int _ { a } ^ { b } \delta x ^ { i } \frac { d u _ { i } } { d s } d s
$$

$$
\delta S = - m c u _ { i } \delta x ^ { \prime }
$$

$$
p _ { i } = - \frac { \partial S } { \partial x ^ { \prime } }
$$

$$
\left. \begin{array} { c } { p ^ { \prime } = ( \mathscr { E } / c , \mathbf { p } ) } \\ { p ^ { i } = m c u ^ { \prime } } \end{array} \right.
$$

$$
p _ { x } = \frac { p _ { x } ^ { \prime } + \frac { V } { c ^ { 2 } } \mathscr { E } ^ { \prime } } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } } , \quad p _ { y } = p _ { y } ^ { \prime } , \quad p _ { z } = p _ { z } ^ { \prime }
$$

$$
\mathscr { G } = \frac {  { \mathscr {E} } ^ { \prime } + V p _ { x } ^ { \prime } } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } }
$$

$$
p _ { i } p ^ { i } = m ^ { 2 } c ^ { 2 }
$$

Cuadrivector fuerza

$$
g ^ { i } = \frac { d p ^ { i } } { d s } = m c \frac { d u ^ { i } } { d s }
$$

$$
g _ { i } u ^ { i } = 0
$$

$$
\mathbf { f } = d \mathbf { p } / d t
$$

$$
g ^ { i } = \left( \frac { \mathbf { f } \cdot \mathbf { v } } { c ^ { 2 } \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } , \frac { \mathbf { f } } { c \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } \right)
$$

$$
\left. \begin{array} { c } { \frac { \partial S } { \partial x _ { i } } \frac { \partial S } { \partial x ^ { i } } \equiv g ^ { i k } \frac { \partial S } { \partial x ^ { i } } \frac { \partial S } { \partial x ^ { k } } = m ^ { 2 } c ^ { 2 } } \\ { \frac { 1 } { c ^ { 2 } } \left( \frac { \partial S } { \partial t } \right) ^ { 2 } - \left( \frac { \partial S } { \partial x } \right) ^ { 2 } - \left( \frac { \partial S } { \partial y } \right) ^ { 2 } - \left( \frac { \partial S } { \partial z } \right) ^ { 2 } = m ^ { 2 } c ^ { 2 } } \end{array} \right.
$$

$$
\left. \begin{array} { c } { S = S ^ { \prime } - m c ^ { 2 } t } \\ { \frac { 1 } { 2 m } \left[ \left( \frac { \partial S ^ { \prime } } { \partial x } \right) ^ { 2 } + \left( \frac { \partial S ^ { \prime } } { \partial y } \right) ^ { 2 } + \left( \frac { \partial S ^ { \prime } } { \partial z } \right) ^ { 2 } \right] - \frac { 1 } { 2 m c ^ { 2 } } \left( \frac { \partial S ^ { \prime } } { \partial t } \right) ^ { 2 } + \frac { \partial S ^ { \prime } } { \partial t } = 0 } \end{array} \right.
$$

$$
\delta \left( p ^ { \prime } p _ { i } - m ^ { 2 } c ^ { 2 } \right) = \delta \left( \left( p _ { 0 } \right) ^ { 2 } - \frac { \mathscr { g } ^ { 2 } } { c ^ { 2 } } \right) = \frac { c } { 2 \delta } \left[ \delta \left( p _ { 0 } + \frac { \chi } { c } \right) + \delta \left( p _ { 0 } - \frac { \gamma } { c } \right) \right]
$$


### 10. Transformacion de las funciones de distribución

### 11. Decay of particles

### 12. Invariant cross-section

### 13. Elastic collisions of particles

### 14. Angular momentum





## *III. Cargas en campos electromagnéticos*
PDF Pagina 56

### 15. Elementary particles in the theory of relativity

### 16. Four-potential of a field

$$
 -\frac{ e } { c } \int _ { a } ^ { b } A _ { i } d x ^ { i }
$$

Acción
$$
S = \int _ { a } ^ { b } \left( - m c d s - \frac { e } { c } A _ { i } d x ^ { i } \right)
$$

$$
A ^ { i } = ( \phi , \mathbf { A } )
$$

$$
S = \int _ { i _ { 1 } } ^ { b } \left( - m c d s + \frac { e } { c } \mathbf { A } \cdot d \mathbf { r } - e \phi d t \right)
$$

Usando
$$
d \mathbf { r } / d t = \mathbf { v }
$$

$$
\left. \begin{array} { c } { S = \int _ { i _ { 1 } } ^ { 2 } \left( - m c ^ { 2 } \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } + \frac { e } { c } \mathbf { A } \cdot \mathbf { v } - e \phi \right) d t }
\\ { L = - m c ^ { 2 } \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } + \frac { e } { c } \mathbf { A } \cdot \mathbf { v } - e \phi } \end{array} \right.
$$

$$
\partial L / \partial v = \mathbf { P } = \frac { m \mathbf { v } } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } + \frac { e } { c } \mathbf { A } = \mathbf { p } + \frac { e } { c } \mathbf { A }
$$

Del lagrangiano saca el hamiltoniano
$$
\left. \begin{array} { c } { \mathscr { F } = \mathbf { v } \cdot \frac { \partial L } { \partial \mathbf { v } } - L } \\ { \mathscr { R } = \frac { m c ^ { 2 } } { \sqrt { 1 - \frac { V ^ { 2 } } { c ^ { 2 } } } } + e \phi } \end{array} \right.
$$

Relaciones...
$$
\left. \begin{array} { l } { \left( \frac { \mathscr { H } - e \phi } { c } \right) ^ { 2 } = m ^ { 2 } c ^ { 2 } + \left( \mathbf { P } - \frac { e } { c } \mathbf { A } \right) ^ { 2 } } \\ { \mathscr { H } = \sqrt { m ^ { 2 } c ^ { 4 } + c ^ { 2 } \left( \mathbf { P } - \frac { e } { c } \mathbf { A } \right) ^ { 2 } } + e \phi } \end{array} \right.
$$

Baja velocidad:
$$
\left. \begin{array} { c } { L = \frac { m v ^ { 2 } } { 2 } + \frac { e } { c } \mathbf { A } \cdot \mathbf { v } - e \phi }
\\
{ \mathbf { p } = m \mathbf { v } = \mathbf { P } - \frac { e } { c } \mathbf { A } }
\\
{ \mathscr { K } = \frac { 1 } { 2 m } \left( \mathbf { P } - \frac { e } { c } \mathbf { A } \right) ^ { 2 } + e \phi } \end{array} \right.
$$

Hamilton-Jacobi:
$$
\left. \begin{array} { c }
\mathbf { P } \rightarrow\partial { S } / \partial \mathbf { r }
\\
\mathscr { H} \rightarrow - ( \partial S / \partial t )
\end{array} \right.
$$
$$
\left( \nabla S - \frac { e } { c } \mathbf { A } \right) ^ { 2 } - \frac { 1 } { c ^ { 2 } } \left( \frac { \partial S } { \partial t } + e \Phi \right) ^ { 2 } + m ^ { 2 } c ^ { 2 } = 0
$$




### 17. Equations of motion of a charge in a field

$$
\left. \begin{array} { c }
{ \frac { d } { d t } \left( \frac { \partial L } { \partial \mathbf { v } } \right) = \frac { \partial L } { \partial \mathbf { r } } }
\\
{ \frac { \partial L } { \partial \mathbf { r } } = \nabla L = \frac { e } { c } \operatorname { grad } \mathbf { A } \cdot \mathbf { v } - e \operatorname { grad } \phi }
\\
{ \text { grad } ( \mathbf { a } \cdot \mathbf { b } ) = ( \mathbf { a } \cdot \nabla ) \mathbf { b } + ( \mathbf { b } \cdot \nabla ) \mathbf { a } + \mathbf { b } \times \operatorname { curl } \mathbf { a } + \mathbf { a } \times \operatorname { curl } \mathbf { b } }
\\
{ \frac { \partial L } { \partial \mathbf { r } } = \frac { e } { c } ( \mathbf { v } \cdot \nabla ) \mathbf { A } + \frac { e } { c } \mathbf { v } \times \operatorname { curl } \mathbf { A } - e \operatorname { grad } \phi }
\\
\frac { d } { d t } \left( \mathbf { p } + \frac { e } { c } \mathbf { A } \right) = \frac { e } { c } ( \mathbf { v } \cdot \nabla ) \mathbf { A } + \frac { e } { c } \mathbf { v } \times \operatorname { curl } \mathbf { A } - e \operatorname { grad } \phi
\end{array} \right.
$$

Derivada total
$$
\frac { d \mathbf { A } } { d t } = \frac { \partial \mathbf { A } } { \partial t } + ( \mathbf { v } \cdot \mathbf { \nabla } ) \mathbf { A }
$$

Y asi...
$$
\frac { d \mathbf { p } } { d t } = - \frac { e } { c } \frac { \partial \mathbf { A } } { \partial t } - e \operatorname { grad } \phi + \frac { e } { c } \mathbf { v } \times \operatorname { curl } \mathbf { A }
$$

Maxwell
$$
\left. \begin{array}
{ c } { \mathbf { E } = - \frac { 1 } { c } \frac { \partial \mathbf { A } } { \partial t } - \operatorname { grad } \phi } \\ { \text { of the second type, per ur } }
\\
\mathbf { H } = \operatorname { curl } \mathbf { A } }
\end{array} \right.
$$

Ecuación de movimiento, bajas v
$$
m \frac { d \mathbf { v } } { d t } = e \mathbf { E } + \frac { e } { c } \mathbf { v } \times \mathbf { H }
$$

$$
\left. \begin{array} { c }
{ \frac { d \delta _ { \mathscr { E } _ { kin } } } { d t } = \frac { d } { d t } \left( \frac { m c ^ { 2 } } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } \right) }
\\
{ \frac { d \mathscr { C } _ { kin } } { d t } = \mathbf { v } \cdot \frac { d \mathbf { p } } { d t } }
\end{array} \right.
$$
Mathscr E arriba, mathcal E abajo
$$
\frac { d \mathcal { E } _ { \mathrm { kin } } } { d t } = e \mathbf { E } \cdot \mathbf { v }
$$

Bajo inversión temporal:
$$
\left. \begin{array} { c l }
{ t \rightarrow - t , } & { \mathbf { E } \rightarrow \mathbf { E } , \quad \mathbf { H } \rightarrow - \mathbf { H } }
\\
{ } & { \phi \rightarrow \phi , \quad \mathbf { A } \rightarrow - \mathbf { A } } \end{array} \right.
$$


#### 17. Problema



### 18. Gauge invariance

$$
A _ { k } ^ { \prime } = A _ { k } - \frac { \partial f } { \partial x ^ { k } }
$$

Término adicional en integral de acción:
$$
\frac { e } { c } \frac { \partial f } { d x ^ { k } } d x ^ { k } = d \left( \frac { e } { c } f \right)
$$

$$
\mathbf { A } ^ { \prime } = \mathbf { A } + \operatorname { grad } f , \quad \phi ^ { \prime } = \phi - \frac { 1 } { c } \frac { \partial f } { \partial t }
$$





### 19. Constant electromagnetic field

$$
\mathbf { E } = - \operatorname { grad } \phi
$$

$$
\varepsilon = \frac { m c ^ { 2 } } { \sqrt { 1 - \frac { v ^ { 2 } } { c ^ { 2 } } } } + e \phi
$$

Potencial escalar de E cte
$$
\left. \begin{array} { r }
{ \phi = - \mathbf { E } \cdot \mathbf { r } }
\\
{ \mathbf { E } = \text { const } \nabla ( \mathbf { E } \cdot \mathbf { r } ) = ( \mathbf { E } \cdot \nabla ) \mathbf { r } = \mathbf { E } }
\end{array} \right.
$$

Potencial vector de B cte
$$
\mathbf { A } = \frac { 1 } { 2 } \mathbf { H } \times \mathbf { r }
$$

$$
A _ { x } = - H y , \quad A _ { y } = A _ { z } = 0
$$

$$
\operatorname { curl } \operatorname { curl } ( \mathbf { H } \times \mathbf { r } ) = \mathbf { H } \operatorname { div } \mathbf { r } - ( \mathbf { H } \cdot \nabla \mathbf { r } = 2 \mathbf { H }
\\
{ ( \mathrm { div } \mathbf { r } = 3 ) }
$$

#### 19. Problema



### 20. Motion in a constant uniform electric field

### 21. Motion in a constant uniform magnetic field

#### 21. Problema

### 22. Motion of a charge in constant uniform electric and magnetic fields

#### 22. Problema

### 23. The electromagnetic field tensor

### 24. Lorentz transformation of the field

### 25. Invariants of the field

#### 25. Problema



## *IV. Las ecuaciones del campo electromagnético*
PDF página 80

### 26. The first pair of Maxwell's equations

### 27. The action function of the electromagnetic field

### 28. The four-dimensional current vector

### 29. The equation of continuity

### 30. The second pair of Maxwell equations

### 31. Energy density and energy flux

### 32. The energy-momentum tensor

Contravariante
$$
T ^ { i k } = - \frac { 1 } { 4 \pi } \frac { \partial A ^ { i } } { \partial x _ { i } } F _ { l } ^ { k } + \frac { 1 } { 16 \pi } g ^ { i k } F _ { l m } F ^ { l m }
$$

### 33. Energy-momentum tensor of the electromagnetic field

#### 33. Problema

### 34. The virial theorem

### 35. The energy-momentum tensor for macroscopic bodies

## *V. CONSTANT ELECTROMAGNETIC FIELDS*
PDF Página

### 36. Coulomb's law

## *VI. Búf*
PDF Página


---
---
# B. Garay



# Tema 1: Ecuaciones de Maxwell
## 1.1. Ecuaciones de Maxwell
### 1.1.1. Ecuaciones de Maxwell en el vacío
### 1.1.2. Condiciones de empalme en una superficie
## 1.2. Leyes de conservación
### 1.2.1. Conservación de carga
### 1.2.2. Conservación de energía. El teorema de Poynting
### 1.2.3. Conservación de momento. Tensor de tensiones de Maxwell
### 1.2.4. Propiedades de transformación
## 1.3. Ondas planas libres
### 1.3.1. Ecuación de onda para E y B
### 1.3.2. Ondas planas
### 1.3.3. Polarización
### 1.3.4. Flujo y densidad de energía
## 1.4. Potenciales electromagnéticos
### 1.4.1. Ecuación de onda para el potencial electromagnético
### 1.4.2. Condición de gauge de Lorenz
### 1.4.3. Solución de la ecuación de onda
#### 1.4.3.1. Funciones de Green
#### 1.4.3.2. Solución general
#### 1.4.3.3. Dispersión
## 1.5. Guías de ondas
### 1.5.1. Modos TEM
### 1.5.2. Modos TE y TM
### 1.5.3. Potencia y energía#

# Tema 2: Teoría especial de la relatividad
## 2.1. Relatividad especial y transformaciones de Lorentz
### 2.1.1. Postulados de la teoría especial de la relatividad
### 2.1.2. Transformaciones de Lorentz
### 2.1.3. Adición de velocidades
### 2.1.4. Elemento de línea
## 2.2. Espaciotiempo de Minkowski
### 2.2.1. Tensores lorentzianos
### 2.2.2. El pseudotensor de Levi-Civita
### 2.2.3. Derivación
### 2.2.4. Hipersuperficies espaciales
### 2.2.5. Integración
#### 2.2.5.1. Integración a lo largo de una curva
#### 2.2.5.2. Intregración sobre una superficie bidimensional
#### 2.2.5.3. Integración en una hipersuperficie
#### 2.2.5.4. Integración en un volumen cuadrimensional
#### 2.2.5.5. Generalizaciones de los teoremas de Gauss y de Stokes
### 2.2.6. Cuadrivelocidad y cuadriaceleración
## 2.3. Grupo de Poincaré
### 2.3.1. Grupo de traslaciones
### 2.3.2. Grupo de Lorentz
## 2.4. Dinámica relativista
### 2.4.1. Principio variacional
### 2.4.2. Cantidades conservadas. Teorema de Noether
#### 2.4.2.1. Cuadrimomento
#### 2.4.2.2. Momento angular
#### 2.4.2.3. Centro de inercia
#### 2.4.2.4. Invariantes de Casimir
### 2.4.3. Partícula libre

# Tema 3: Teoría clásica de campos
## 3.1. Leyes de transformación de Poincaré
### 3.1.1. Traslaciones
### 3.1.2. Transformaciones de Lorentz
#### 3.1.2.1. Campos escalares
#### 3.1.2.2. Campos vectoriales
#### 3.1.2.3. Campos tensoriales
### 3.1.3. Operadores de Casimir
## 3.2. Principio variacional
## 3.3. Teorema de Noether
### 3.3.1. Invariancia bajo traslaciones
### 3.3.2. Invariancia Lorentz
### 3.3.3. Invariancia Poincaré
### 3.3.4. Invariancia gauge abeliana
#### 3.3.4.1. Transformaciones gauge globales
#### 3.3.4.2. Transformaciones gauge locales
## 3.4. Partículas y campos
## 3.5. Formulación Hamiltoniana

# Tema 4: Partículas cargadas y campos electromagnéticos
## 4.1. Partícula en un campo electromagnético
### 4.1.1. Formulación lagrangiana
#### 4.1.1.1. Acción
#### 4.1.1.2. Invariancia gauge
#### 4.1.1.3. Ecuaciones de movimiento
### 4.1.2. Formulación canónica
### 4.1.3. Campo electromagnético
#### 4.1.3.1. Campo eléctrico y campo magnético
#### 4.1.3.2. Invariancia gauge
#### 4.1.3.3. Invariantes Lorentz
## 4.2. Cargas puntuales en campos electromagnéticos constantes
### 4.2.1. Campo eléctrico uniforme
### 4.2.2. Campo eléctrico de Coulomb
### 4.2.3. Campo magnético uniforme
### 4.2.4. Campo electromagnético uniforme
### 4.2.5. Invariantes adiabáticos
## 4.3. Dipolos en campos electromagnéticos constantes
### 4.3.1. Dipolo eléctrico en un campo eléctrico constante
### 4.3.2. Dipolo magnético en un campo magnético constante y uniforme
### 4.3.3. Precesión de Thomas
## 4.4. Dinámica del campo electromagnético
### 4.4.1. Ecuaciones de Maxwell
### 4.4.2. Leyes de conservación
### 4.4.3. Formulación hamiltoniana
### 4.4.4. Ecuación de onda
### 4.4.5. Lagrangiano de dos partículas hasta segundo orden

# Tema 5: Radiación electromagnética
## 5.1. Radiación por cargas en movimiento
### 5.1.1. Campo generado por una partícula cargada
### 5.1.2. Potencia radiada por una carga acelerada
#### 5.1.2.1. Partícula no relativista
#### 5.1.2.2. Partícula relativista
### 5.1.3. Distribución espectral y angular de la potencia
#### 5.1.3.1. Estimaciones
#### 5.1.3.2. Amplitud espectral y angular
## 5.2. Reacción de la radiación
### 5.2.1. Estimación de los efectos radiativos
### 5.2.2. Fuerza de reacción radiativa
### 5.2.3. Renormalización electrodinámica de la masa
## 5.3. Radiación multipolar
### 5.3.1. Radiación dipolar eléctrica
### 5.3.2. Radiación dipolar magnética y cuadrupolar eléctrica
### 5.3.3. Intensidad de radiación multipolar


_________
_________

# Tema 1: Ecuaciones de Maxwell
## 1.1. Ecuaciones de Maxwell
### 1.1.1. Ecuaciones de Maxwell en el vacío
### 1.1.2. Condiciones de empalme en una superficie
## 1.2. Leyes de conservación
### 1.2.1. Conservación de carga
### 1.2.2. Conservación de energía. El teorema de Poynting
### 1.2.3. Conservación de momento. Tensor de tensiones de Maxwell
### 1.2.4. Propiedades de transformación
## 1.3. Ondas planas libres
### 1.3.1. Ecuación de onda para E y B
### 1.3.2. Ondas planas
### 1.3.3. Polarización
### 1.3.4. Flujo y densidad de energía
## 1.4. Potenciales electromagnéticos
### 1.4.1. Ecuación de onda para el potencial electromagnético
### 1.4.2. Condición de gauge de Lorenz
### 1.4.3. Solución de la ecuación de onda
#### 1.4.3.1. Funciones de Green
#### 1.4.3.2. Solución general
#### 1.4.3.3. Dispersión
## 1.5. Guías de ondas
### 1.5.1. Modos TEM
### 1.5.2. Modos TE y TM
### 1.5.3. Potencia y energía#

# Tema 2: Teoría especial de la relatividad
## 2.1. Relatividad especial y transformaciones de Lorentz
### 2.1.1. Postulados de la teoría especial de la relatividad
### 2.1.2. Transformaciones de Lorentz
### 2.1.3. Adición de velocidades
### 2.1.4. Elemento de línea
## 2.2. Espaciotiempo de Minkowski
### 2.2.1. Tensores lorentzianos
### 2.2.2. El pseudotensor de Levi-Civita
### 2.2.3. Derivación
### 2.2.4. Hipersuperficies espaciales
### 2.2.5. Integración
#### 2.2.5.1. Integración a lo largo de una curva
#### 2.2.5.2. Intregración sobre una superficie bidimensional
#### 2.2.5.3. Integración en una hipersuperficie
#### 2.2.5.4. Integración en un volumen cuadrimensional
#### 2.2.5.5. Generalizaciones de los teoremas de Gauss y de Stokes
### 2.2.6. Cuadrivelocidad y cuadriaceleración
## 2.3. Grupo de Poincaré
### 2.3.1. Grupo de traslaciones
### 2.3.2. Grupo de Lorentz

Transformación de Lorentz infinitesimal en términos de rotaciones y traslaciones:
$$
\left.\begin{aligned} \delta x ^ { \mu } & = i \left[ \left( \delta \omega ^ { i 0 } S _ { i 0 } + \frac { 1 } { 2 } \delta \omega ^ { i j } S _ { i j } \right) \boldsymbol { x } \right] ^ { \mu } \\ & = - i \left[ \left( \delta \zeta ^ { i } S _ { i 0 } + \frac { 1 } { 2 } \epsilon ^ { i j k } \delta \theta _ { k } S _ { i j } \right) \boldsymbol { x } \right] ^ { \mu } \\ & = - i \left[ \left( \delta \zeta ^ { i } K _ { i } + \delta \theta _ { k } S ^ { k } \right) \boldsymbol { x } \right] ^ { \mu } \\ & = - i [ ( \delta \dot { \zeta } \cdot \vec { K } + \delta \vec { \theta } \cdot \vec { S } ) x ] ^ { \mu } \end{aligned} \right.
$$

## 2.4. Dinámica relativista
### 2.4.1. Principio variacional
### 2.4.2. Cantidades conservadas. Teorema de Noether
#### 2.4.2.1. Cuadrimomento
#### 2.4.2.2. Momento angular
#### 2.4.2.3. Centro de inercia
#### 2.4.2.4. Invariantes de Casimir
### 2.4.3. Partícula libre

# Tema 3: Teoría clásica de campos
## 3.1. Leyes de transformación de Poincaré
### 3.1.1. Traslaciones
### 3.1.2. Transformaciones de Lorentz
#### 3.1.2.1. Campos escalares
#### 3.1.2.2. Campos vectoriales
#### 3.1.2.3. Campos tensoriales
### 3.1.3. Operadores de Casimir
## 3.2. Principio variacional
## 3.3. Teorema de Noether
### 3.3.1. Invariancia bajo traslaciones
### 3.3.2. Invariancia Lorentz
### 3.3.3. Invariancia Poincaré
### 3.3.4. Invariancia gauge abeliana
#### 3.3.4.1. Transformaciones gauge globales
#### 3.3.4.2. Transformaciones gauge locales
## 3.4. Partículas y campos
## 3.5. Formulación Hamiltoniana

# Tema 4: Partículas cargadas y campos electromagnéticos
## 4.1. Partícula en un campo electromagnético
### 4.1.1. Formulación lagrangiana
#### 4.1.1.1. Acción
#### 4.1.1.2. Invariancia gauge
#### 4.1.1.3. Ecuaciones de movimiento
### 4.1.2. Formulación canónica
### 4.1.3. Campo electromagnético
#### 4.1.3.1. Campo eléctrico y campo magnético
#### 4.1.3.2. Invariancia gauge
#### 4.1.3.3. Invariantes Lorentz
## 4.2. Cargas puntuales en campos electromagnéticos constantes
### 4.2.1. Campo eléctrico uniforme
### 4.2.2. Campo eléctrico de Coulomb
### 4.2.3. Campo magnético uniforme
### 4.2.4. Campo electromagnético uniforme
### 4.2.5. Invariantes adiabáticos
## 4.3. Dipolos en campos electromagnéticos constantes
### 4.3.1. Dipolo eléctrico en un campo eléctrico constante
### 4.3.2. Dipolo magnético en un campo magnético constante y uniforme
### 4.3.3. Precesión de Thomas
## 4.4. Dinámica del campo electromagnético
### 4.4.1. Ecuaciones de Maxwell
### 4.4.2. Leyes de conservación
### 4.4.3. Formulación hamiltoniana
### 4.4.4. Ecuación de onda
### 4.4.5. Lagrangiano de dos partículas hasta segundo orden

# Tema 5: Radiación electromagnética
## 5.1. Radiación por cargas en movimiento
### 5.1.1. Campo generado por una partícula cargada
### 5.1.2. Potencia radiada por una carga acelerada
#### 5.1.2.1. Partícula no relativista
#### 5.1.2.2. Partícula relativista
### 5.1.3. Distribución espectral y angular de la potencia
#### 5.1.3.1. Estimaciones
#### 5.1.3.2. Amplitud espectral y angular
## 5.2. Reacción de la radiación
### 5.2.1. Estimación de los efectos radiativos
### 5.2.2. Fuerza de reacción radiativa
### 5.2.3. Renormalización electrodinámica de la masa
## 5.3. Radiación multipolar
### 5.3.1. Radiación dipolar eléctrica
### 5.3.2. Radiación dipolar magnética y cuadrupolar eléctrica
### 5.3.3. Intensidad de radiación multipolar

________________
________________
# WIKIPEDIA

## PPio minima accion

### Español

$$
S[q_i] = \int_{t_{1}}^{t_{2}} L(q_i(t), \dot{q}_i(t),t) dt,\qquad S:C^2(\R,\R^{2n})\to \R
$$

#### Para particulas

$$
0 = \delta\int_{t_{1}}^{t_{2}} L(q_i(t), \dot{q}_i(t),t) dt
$$

$$
\frac{d}{dt} \left ( \frac{\partial L}{\partial\dot{q}_i} \right ) - \frac{\partial L}{\partial q_i} = 0
$$

#### Para campos

$$
S[\phi,\partial_t\phi,\partial_\mathbf{x}\phi] = \int_{t_{1}}^{t_{2}} dt \int_V \mathcal{L} (\phi(\mathbf{x},t), \partial_t\phi(\mathbf{x},t), \partial_\mathbf{x}\phi(\mathbf{x},t),\mathbf{x},t)\ d^3\mathbf{x}
$$

$$
\mathcal{S} [\phi_r^\alpha] = \int_R {\mathcal{L}(\mathbf{x}, \phi_r^\alpha, \partial_\mu \phi_r^\alpha)  \ \mathrm{d}^4x}
$$

$$
\frac{\delta \mathcal{S}}{\delta\phi_r^\alpha} = \frac{\partial\mathcal{L}}{\partial\phi_r^\alpha} - \partial_\mu  \left(\frac{\partial\mathcal{L}}{\partial(\partial_\mu\phi_r^\alpha)}\right)=0
$$

#### Para particulas relativistas

$$
 S_m = - \int_L  mc \ ds =
-\int_{\tau_1}^{\tau_2} mc\ \sqrt{g_{\mu\nu}\frac{dx^\mu}{d\tau}\frac{dx^\nu}{d\tau}}\ d\tau
$$

$$
\frac{d^2 x^\mu}{d\tau^2} + \sum_{\sigma,\nu}
 \Gamma_{\sigma \nu}^{\mu} \frac{dx^\sigma}{d\tau}\frac{dx^\nu}{d\tau} = 0
 $$



### Ingles

$$
\mathcal{S}[\mathbf{q_1}(t_1),\mathbf{q_2}(t_2),\mathbf{q}(t)]
= \int_{t_1}^{t_2} L(\mathbf{q}(t),\mathbf{\dot{q}}(t), t) dt
$$

$$
\delta \int_{t_1}^{t_2} L(\mathbf{q}, \mathbf{\dot{q}},t) dt = 0
$$


> Written with [StackEdit](https://stackedit.io/).
