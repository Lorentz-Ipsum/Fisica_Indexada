

# Atomica-Examen Feb2016

## 1. Configuración ns np
> Para la configuración $3s3p$
a) Indicar su degeneración, la de su término $^3P$, la de su determinante de Slater $(0^- 0^+)$ y la de su nivel $3s3p\ ^3P_1$
b) Escribir explícitamente el determinante $(0^- 0^+)$ en términos de $R_{nl},Y_{lm}\chi_{\sigma}$
c) Calcular en términos de las integrales radiales la diferencia de energía entre los términos $3s3p\ ^1D$ y $^3P$ debido a la interación electrostática residual.
### 1. SOLUCIÓN:
#### a) Degeneración
$3s3p \rightarrow$ degeneración $g = \begin{pmatrix} 2(2l_1+1) \\ \nu_1 \end{pmatrix}\begin{pmatrix} 2(2l_2+1) \\ \nu_2 \end{pmatrix} =\begin{pmatrix} 6 \\ 1\end{pmatrix} \begin{pmatrix} 2 \\ 1\end{pmatrix} = 12$

$3s3p: l_1=0,l_2=1\rightarrow L=1,M_L=1,0,-1;S=\pm 1/2, M_S=1,0,-1$

$$
\left. \begin{array} { | c | c | c | c | } \hline M_S \backslash M_L & { 1 } & { 0 } & { -1 } \\ \hline 1 & { (1^+0^+)} & { (0^+0^+) } & { (-1^+0^+) } \\ \hline 0 & { (1^+0^-)
(1^-0^+)} & { (0^+0^-)(0^-0^+) } & { (-1^+0^-)(-1^-0^+) } \\ \hline -1 & { (1^-0^-) } & { (0^-0^-) } & { (-1^-0^-) }  \\ \hline \end{array} \right.
$$

Degeneración $(0^-0^+)\rightarrow 2$
Nivel $3s3p ^3P_1$

Degeneración de un término $g = (2L+1)(2S+1) = 9$

#### b) Determinante de Slater
$(1^+0^+)= |^3 P\ 1\ 1\rangle\rightarrow$ aplicamos $L_-, S_-$
$(0^+0^-)= |^3 P\ 0\ 0\rangle$

$S_- |^3 P\ 1\ 1\rangle = (S_{1-}+S_{2-})(1^+0^+)\Rightarrow$
$\sqrt{1\cdot 2 - 1\cdot 0} |^3 P\ 1\ 0\rangle = \sqrt{1/2 \cdot 3/2 - 1/2 \cdot (-1/2)} (1^- 0^+) +  \sqrt{1/2 \cdot 3/2 - 1/2 \cdot (-1/2)} (1^+ 0^-)$
$\Rightarrow  |^3 P\ 1\ 0\rangle=1/\sqrt{2} (1^- 0^+) + 1/\sqrt{2} (1^+ 0^-)$

$L_- |^3 P\ 1\ 0\rangle = (l_{1-}+l_{2-})\cdot1/\sqrt{2}[(1^-0^+)+(1^+0^-)]\Rightarrow$
$\sqrt{2} |^3 P\ 0\ 0\rangle =$

>>>FALTA COMPLETAR


#### c) Energía e integrales radiales

En cada caja de $M_L,M_S$ dada:
$$
\sum_i\sum_{detSlater} m_{l_i} m_{s_i} \xi_{n_i l_i} = M_L M_S \sum_{termElectr} A( ^S L)
$$
Tenemos:
$$
L = 1, S = 1;\\ l_1 = 1, l_2 = 0 \rightarrow M_L = 1, 0, -1;\ m_{l_1} = 1, 0;\\ s_1 = 1/2 \rightarrow M_S = 1, 0, -1;\ m_{s} = \pm 1/2
$$

**Caso $3s3p(^3 P)$**
$$
\left. \begin{array} { | c | c | c | } \hline M_S \backslash M_L & { 1 } & { 0 } \\ \hline 1 & { (1^+0^+)} & {  }  \\ \hline 0 & { } & { } \\ \hline \end{array} \right.
$$
$\xi_p \cdot 1\cdot1/2 = 1 \cdot 1 \cdot A(^3 P)$
$\xi_p \cdot1/2 = \cdot A(^3 P)$


**Caso $3p3s(^1 P)$**
$$
\left. \begin{array} { | c | c | c | } \hline M_S \backslash M_L & { 1 } & { 0 } \\ \hline 1 & { } & {  }  \\ \hline 0 & { (1^+0^- )(1^-0^+)} & { } \\ \hline \end{array} \right.
$$
$^1 P \Rightarrow S=0, L = 1;\ M_S = 0, M_L = 1$

$\xi_p \cdot 1\cdot1/2 = 1 \cdot 0 \cdot A(^0 P)$
$\xi_p \cdot1/2 = 0$

$\Delta E(^3 P ) = \langle 1^+ 0^- |1/r_{12}|...\rangle = F^0 -1/3 G^1 = ...$
$\Delta E(^1 P )+\Delta E(^3 P ) =\Delta E(^1 P )+ F^0 -1/3 G^1 = F^0 +F^0$
$\Delta E(^1 P )= F^0 + 1/3 G^1$
$\Delta (^1 P ) = \langle 1^+ 0^- |1/r_{12}|1^+ 0^-\rangle  + \langle 1^+ 0^- |1/r_{12}|1^- 0^+\rangle  = F^0_{sp} +1/3 G^1$
$\Delta E(^1 P ) - \Delta E(^3 P ) =2/3 G^1$

## 2. Diagrama de niveles
>[Diagrama]
a) ¿Justifica lo obtenido en el apartado anterior que el término $^3 P$ esté más bajo que el $^1$?
b) ¿Son aplicables las reglas de Hund para la configuración $3p^2$?
c) ¿Cabe sospechar que haya acoplamiento intermedio en los términos de la configuración $3p^2$?
d) Calcular la constante $A$ para dos términos $^3P$ del diagrama en función de integrales radiales. ¿La separación J debe ser la misma o diferente?
### 2. Solución
#### a) Energía de niveles
Lo justifica ya que hemos visto que $E(^1P) > E ( ^ 3 P )$

#### b) Reglas de Hund
$3p^2$
$l_1 = 1 , l_2 = 1;\ L = 2 , 1 , 0; S = 0 , 1; \ L + S = par$
Si $^1 S, ^3 P, ^1 D$
No $^3 S, ^1 P, ^3 D$

Reglas Hund:
: Maximo S -> Menor E
: De entre ellos mayor L -> Menor E

Seguno esto. $^3P$ es el de menor E -> No se cumplen las reglas de Hund, pues muestran que $^1 D$ es el de menor E.

#### c) Acoplamiento intermedio
Acoplamiento intermedio:
: $\Delta H_{el} \approx \Delta H_{SO}$

La aproximacion de Rusell-Saunders no se cumple del todo -> Tiene que existir algun tipo de acoplamiento intermedio.

#### d) Constante de acoplamiento
$$
\sum_i\sum_{detSlater} m_{l_i} m_{s_i} \xi_{n_i l_i} = M_L M_S \sum_{termElectr} A( ^S L)
$$


**Caso $3p^2(^3 P)$**
$$
\left. \begin{array} { | c | c | c | } \hline M_S \backslash M_L & { 1 } & { 0 } \\ \hline 1 & { (1^+0^+)} & {  }  \\ \hline 0 & { } & { } \\ \hline \end{array} \right.
$$
$0 \cdot1/2 +\xi_{3p} \cdot 1\cdot1/2 = 1 \cdot 1 \cdot A(^3 P)$
$\xi_{3p} \cdot1/2 = A(^3 P)$


**Caso $3s3p(^3 P)$**
$$
\left. \begin{array} { | c | c | c | } \hline M_S \backslash M_L & { 2 } & { 1 } \\ \hline 1 & { } & { (1^+0^+) }  \\ \hline 0 & { } & { } \\ \hline \end{array} \right.
$$
$0 \cdot1/2 +\xi_{sp} \cdot 1\cdot1/2 = 1 \cdot 1 \cdot A(^3 P)$
$\xi_{sp} \cdot1/2 = A(^3 P)$
A es la misma

$\Delta E_{SO}(J =0 ) =1/2 A [-2-2]=-2A$
$\Delta E_{SO}(J =1 ) =1/2 A [2 -2-2]=-A$
$\Delta E_{SO}(J =2 ) =1/2 A [6 -2-2]=A$

#### c) Acoplamiento intermedio
#### d) Constante de acoplamiento

## 3. Aproximación dipolar eléctrica
>Para el diagrama de niveles $P_{IV}$
=Diagrama=
a) Identificar las transiciones dipolares eléctricas
b) Sabiendo que la energía de los $3s3p\ ^3 P$ con $J=0$ y $J=1$ es $67918 cm^{-1}$ y $68146 cm^{-1}$ respecto al estado fundamental, calcular la longitud de onda que se emitiría si cayera al estado fundamental $^1 S$.
c) En aproximación dipolar eléctrica: ¿estaría permitida alguna de las transiciones sugeridas en el apartado anterior? ¿Sería posible alguna de ellas al pasar de estar prohibida?
d) Suponiendo permitidas las transiciones entre el término $^3 S$ y alguno de los $^3 P$, determinar en qué proporción se debería conservar la intensidad correspondiente a las líneas.
### 3. Solución
#### a) Transiciones dipolares eléctricas
#### b) Decaimiento al estado fundamental
#### c) Transiciones permitidas
#### d) Intensidad de las transiciones


## 4. Campos magnéticos externos
> Considere un efecto de $B = 10 \ T$ sobre $3s3p\ ^3P_1$ para el que más arriba se ha proporcionado la energía.
a) ¿En cuántas componentes se desdobla?
b) Explicar si debe usarse la aproximación de Zeeman o la de Paschen-Back
c) Calcular la separación que ese B provoca entre las componentes $M_J = 1$ y $M_J = 0$

### 4. Solución
#### a) Desdoblamiento de niveles
#### b) Zeeman vs. Paschen-Back
#### c) Separacion de componentes

## 5. Molecular
> Considere el estado electrónico $X^2 \ ^2\Pi_{\frac{1}{2}}$ de la molécula $AsS$ y sus parámetros espectroscópicos en la tabla:
$\left. \begin{array} { | c | c | c | c | c | } \hline E_e & { h\omega_e  } & { \hbar \chi_e \omega_e } & { B_r } & { \alpha_e (cm^{-1}) } \\ \hline 0 & { 562,32 } & { 2,01 } & { 0,184 } & { 8,3 \cdot10^{-3} }
\\ \hline \end{array} \right.$
a) Explicar el significado de $X, ^2 \Pi, E_e, h\omega_e, \hbar\chi_e\omega_e, B_r, \alpha_e$.
b) Calcular la energía del nivel vibracional con $v=1$ y $J = 1/2$.
c) Distancia internuclear de equilibrio. $S: 32\ uma, As: 74,9\ uma$.
d) Para el espectro vibrorrotacional $v'' = 0 \rightarrow v'=1$ de la molécula $X^2 \ ^2\Pi_{\frac{1}{2}}$. Determinar la energía que se encontrará en el centro del espectrómetro y qué ramas presentará-

### 5. Solución
#### a) Signos




#### b) Espectro vibracional
#### c) Distancia internuclear
#### d) Espectro vibrorrotacional


## 6. Modos normales en moléculas
> ¿Cuántos modos normales de vibración tiene la molécula lineal $C_2H_2$?
### 6. Solución
