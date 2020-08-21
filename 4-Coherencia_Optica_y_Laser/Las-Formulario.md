
---
Title: Formulario Laser

---



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


#  T1:



---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---


# T2: Amplificación de la radiación



---
>.
> Intervalo Publicitario
>.
---


## 2.1 Principios básicos del láser

### 2.1.1. Amplificación de radiación

#### Dos Niveles

$$\frac { d I ( t ) } { d t } = c \left[ - n _ { 1 } ( t ) \sigma _ { 12 } ^ { a b s } + n _ { 2 } ( t ) \sigma _ { 21 } ^ { e m } \right] I ( t ) + \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } h v c \phi S _ { e m }$$

$$
\frac { d n _ { 2 } ( t ) } { d t } = \left[ n _ { 1 } ( t ) \sigma _ { 12 } ^ { a b s } - n _ { 2 } ( t ) \sigma _ { 21 } ^ { e m } \right] \frac { I ( t ) } { h v } - \frac { n _ { 2 } ( t ) } { \tau _ { 21 } }
$$

$$
n _ { T } = n _ { 1 } ( t ) + n _ { 2 } ( t )
$$

$$\boxed{ \begin{array}{ c }
B _ { 12 } = B _ { 21 }
&
 \sigma ^ { a b s } = \sigma ^ { \mathrm { em } } _ { 21 } = \sigma
 \\
 \\A _ { 21 } / B _ { 21 } = 8 h \pi \mathrm { v } ^ { 3 } / c ^ { 3 }
 & \mathrm { S } _ { 21 } ^ { \mathrm { em } } / \tau _ { 21 } = \mathrm { cte }  \end{array}}$$

Equilibrio térmico  $n _ { 1 } > > n _ { 2 }$
$$\frac { d I } { d z } = \left[ - n _ { 1 } + n _ { 2 } \right] \sigma I + \frac { n _ { 2 } } { \tau _ { 21 } } h v \phi S _ { e m }
$$

> No se amplifica. Hay que sacar al sistema del equilibrio térmico. Con 2  niveles no se puede

#### 3 Niveles

$$
\frac{d I(t)}{d t}=c\left[-n_{1}(t)+n_{2}(t)\right] \sigma I(t)+\frac{n_{2}(t)}{\tau_{21}} \phi h v c S_{e m}
$$

$$
\frac{d n_{3}(t)}{d t}=n_{1}(t) \sigma_{13}^{a b s} \frac{I_{13}(t)}{h v_{13}}-\frac{n_{3}(t)}{\tau_{32}^{n r}}
$$

$$
\frac{d n_{2}(t)}{d t}=\frac{n_{3}(t)}{\tau_{32}^{m r}}+\left[n_{1}(t)-n_{2}(t)\right] \sigma \frac{I(t)}{h v}-\frac{n_{2}(t)}{\tau_{21}}
$$

$$
n T=n_{1}(t)+n_{2}(t)+n 3(t)
$$

$$ \boxed{
c\left[n_{2}(t)-n_{1}(t)\right] \sigma I(t)>-\frac{n_{2}(t)}{\tau_{21}} \phi h v c S_{e m}
}$$

### 2.1.2. Inversión de población

### Bombeo

Solucion pequeña señal ($n_1, n_2$ no funcion de z)
$$
\frac { d I ( t ) } { d t } = c \left[ - n _ { 1 } ( t ) + n _ { 2 } ( t ) \right] \sigma I ( t ) + \frac { n _ { 2 } ( t ) } { \tau _ { 21 } } \phi h v c S _ { e m }
$$

$$
\frac { d I ( z ) } { d z } = \left[ - n _ { 1 } ( z ) + n _ { 2 } ( z ) \right] \sigma I ( z )
$$

> El termino de fluorescencia se desprecia.

$$
\boxed{ I ( z ) = I ( 0 ) e ^ { \sigma \left( n _ { 2 } - n _ { 1 } \right) z }}
$$

> 	Equivalente a la ley de Lambert-Beer


### Ganancia g o atenuación  $\alpha$

$$
e ^ { \sigma \left( n _ { 2 } - n _ { 1 } \right) z }
$$

$$
\begin{array} { l } { n _ { 2 } > n _ { 1 } \Rightarrow g = \sigma \left( n _ { 2 } - n _ { 1 } \right) ; g ( v ) = \sigma ( v ) \left( n _ { 2 } - n _ { 1 } \right) ; e ^ { g z } } \\ { n _ { 2 } < n _ { 1 } \Rightarrow \alpha = \sigma \left( n _ { 1 } - n _ { 2 } \right) ; \alpha ( v ) = \sigma ( v ) \left( n _ { 1 } - n _ { 2 } \right) ; e ^ { - \alpha z } } \end{array}
$$



---
>.
> Intervalo Publicitario
>.
---


## 2.2 Osciladores láser

### Resonadores ópticos

> Ver T3

### Condición umbral

#### 3 Niveles

$$
\frac{d I(t)}{d t}=c\left[-n_{1}(t)+n_{2}(t)\right] \sigma I(t)+\frac{n_{2}(t)}{\tau_{21}} \phi h v c S_{e m}
$$

$$
\frac{d n_{3}(t)}{d t}=n_{1}(t) \sigma_{13}^{a b s} \frac{I_{13}(t)}{h v_{13}}-\frac{n_{3}(t)}{\tau_{32}^{n r}}
$$

$$
\frac{d n_{2}(t)}{d t}=\frac{n_{3}(t)}{\tau_{32}^{m r}}+\left[n_{1}(t)-n_{2}(t)\right] \sigma \frac{I(t)}{h v}-\frac{n_{2}(t)}{\tau_{21}}
$$

$$
n_T=n_{1}(t)+n_{2}(t)+n 3(t)
$$

Luego:
$$
\frac{d I(t)}{d t}=c\left[-n_{1}(t)+n_{2}(t)\right] \sigma(v) I(v, t)+\frac{n_{2}(t)}{\tau_{21}} \phi h v c S_{e m}(v)\boxed{ -\frac{I(t)}{t_{c}}}
$$

> La ganancia tiene que ser superior a las pérdidas.

Ignorando fluorescencia:

$$
\sigma \left( n _ { 2 } - n _ { 1 } \right) _ { u } = \frac { 1 } { c t _ { c } } = \sigma \left( n _ { i } \right) _ { u } \Rightarrow \boxed{ n _ { i u } = \frac { 1 } { \sigma c t _ { c } } ; c = \frac { c _ { 0 } } { n } }
$$

> Recordar $t _ { c } = - \frac { n L } { c _ { 0 } \ln R }$

En estado estacionario
$$
n _ { 1 u } \frac { I _ { 13 } } { h v _ { 13 } } \sigma _ { 13 } ^ { a b s } + \left( n _ { 1 } - n _ { 2 } \right) _ { u } \sigma \frac { I } { h v } - \frac { n _ { 2 u } } { \tau _ { 21 } } = 0
$$

Bombeo Umbral:
$$\boxed{
\left( I _ { 13 } \right) _ { u } = \frac { n _ { i u } + n _ { T } } { n _ { T } - n _ { i u } } \frac { h v _ { 13 } } { \sigma _ { 13 } ^ { a b s } } \frac { 1 } { \tau _ { 21 } } }
 = \frac { n _ { T } + \frac { 1 } { \sigma c t _ { c } } } { n _ { T } - \frac { 1 } { \sigma c t _ { c } } } \frac { h v _ { 13 } } { \tau _ { 21 } \sigma _ { 13 } ^ { a b s } }
$$

Condición de Schawlow-Townes:
$$\boxed{
I_{b u}=\left(I_{13}\right)_{u}=\frac{h v_{13}}{\tau_{21} \sigma_{13}^{a b s}} \frac{n_{2 u}}{n_{1 u}}
}$$

#### 4 Niveles

$$
\frac{d n_{3}}{d t}=n_{0} \sigma_{03}^{a b s} \frac{I_{03}}{h v_{03}}-\frac{n_{3}}{\tau_{32}}
$$

$$
\frac{d n_{2}(t)}{d t}=\frac{n_{3}}{\tau_{32}}-\sigma\left[n_{2}-n_{1}\right] \frac{I}{h v}-\frac{n_{2}}{\tau_{21}}
$$

$$
\frac{d n_{1}(t)}{d t}=\frac{n_{2}}{\tau_{21}}+\sigma\left[n_{2}-n_{1}\right] \frac{I}{h v}-\frac{n_{1}}{\tau_{10}}
$$

Estado estacionario:
$$
n_{0} \sigma_{03}^{a b s} \frac{I_{03}}{h v_{03}}=\frac{n_{3}}{\tau_{32}}
$$

$$\boxed{
I_{b u}=I_{03 u}=\frac{1}{\tau_{21}} \frac{h v_{03}}{\sigma_{03}^{a b s}} \frac{n_{2 u}}{n_{0 u}}
}$$

$$\boxed{
n_{i u}=\frac{1}{\sigma c t_{c}}=-\frac{\ln R}{\sigma L}
}$$

Notas
$$\boxed{\begin{array}{c}
n_{2 u} \approx n_{2 u}-n_{1 u}=n_{i u}
\\ n_{0 u}=n_{T}-n_{2 u}=n_{T}-n_{i u}
\end{array}}$$



---
>.
> Intervalo Publicitario
>.
---


## 2.3 Dinámica temporal


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



---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---


# T3: Onda continua



---
>.
> Intervalo Publicitario
>.
---


## 3.1. Onda continua

### 2 Niveles

Ecuaciones de balance $((v_{21}=v_{0})$:

(1)
$$
{\frac{d n_{2}}{d t}=-\left(n_{2}-\frac{g_{2}}{g_{1}} n_{1}\right) \frac{\sigma_{21}}{h v_{0}} I-\left(\frac{1}{\tau_{21}}+p_{21}+p_{2 n}\right) n_{2}+p_{12} n_{1}+P_{2}}
$$


(2)
$$
\frac{d n_{1}}{d t}=\left(n_{2}-\frac{g_{2}}{g_{1}} n_{1}\right) \frac{\sigma_{21}}{h v_{0}} I+\left(\frac{1}{\tau_{21}}+p_{21}\right) n_{2}-\left(p_{12}+p_{1 n}\right) n_{1}+P_{1}
$$


(3)
$$
\frac{d n_{i}}{d t}=-\left(1+\frac{g_{2}}{g_{1}}\right) \frac{\sigma_{21}}{h v_{0}} n_{i} I-\left[\left(\frac{1}{\tau_{21}}+p_{21}\right)\left(1+\frac{g_{2}}{g_{1}}\right)+p_{2 n}\right] n_{2}+\left[\left(1+\frac{g_{2}}{g_{1}}\right) p_{12}+\frac{g_{2}}{g_{1}} p_{1 n}\right] n_{1}+P_{2}-\frac{g_{2}}{g_{1}} P_{1}
$$


(4)
$$
\frac{d n_{t}}{t}=P_{1}+P_{2}-p_{2 n} n_{2}-p_{1 n} n_{1}
$$


(5)
$$
n_{2}=\frac{1}{1+\frac{g_{2}}{g_{1}}}\left(\frac{g_{2}}{g_{1}} n_{t}+n_{i}\right)
$$


(6)
$$
n_{1}=\frac{1}{1+\frac{g_{2}}{g_{1}}}\left(n_{t}-n_{i}\right)
$$


(7)
$$
\begin{aligned} \frac{d n_{i}}{d t}=&-\left(1+\frac{g_{2}}{g_{1}}\right) \frac{\sigma_{21}}{h v_{0}} n_{i} I-\left[\frac{1}{\tau_{21}}+p_{21}+p_{12}+\frac{p_{2 n}+p_{1 n} g_{2} / g_{1}}{1+g_{2} / g_{1}}\right] n_{i}+\\ &+\left[-\frac{g_{2}}{g_{1}} \frac{1}{\tau_{21}}+p_{12}-\frac{g_{2}}{g_{1}} p_{21}+\frac{g_{2}}{g_{1}} \frac{p_{1 n}-p_{2 n}}{1+g_{2} / g_{1}}\right] n_{t}+P_{2}-\frac{g_{2}}{g_{1}} P_{1} \end{aligned}
$$


(8)
$$
\frac{d n_{t}}{d t}=\frac{p_{1 n}-p_{2 n}}{1+g_{2} / g_{1}} n_{i}-\frac{p_{2 n} g_{2} / g_{1}-p_{1 n}}{1+g_{2} / g_{1}} n_{t}+P_{2}+P_{1}
$$

### 3 Niveles

<center>Notas</center>

$$\boxed{ \begin{array}{c}
p_{32}>>\frac{1}{\tau_{21}}
\\ n_{3}<<n_{2}, n_{1}
\\n_{t}=n_{1}+n_{2}+n_{3} \approx n_{1}+n_{2}=n_{d}
\end {array}}$$


(9)
$$
\frac{d n_{t}}{d t}=P_{2}+P_{1}
$$


(10)
$$
\frac{d n_{3}}{d t}=P_{3}-p_{32} n_{3}=P_{3}-P_{2} \approx 0
$$


(11)
$$
\frac{d n_{t}}{d t}=0 \Rightarrow P_{1}=-P_{2}
$$

Inversión de población:
$$
n_{2}>\frac{g_{2}}{g_{1}} n_{1} \approx \frac{n_{d}}{2}
$$

(12)

(12)
$$
\frac{d n_{i}}{d t}=-\left(1+\frac{g_{2}}{g_{1}}\right) \frac{\sigma_{21}}{h v_{0}} n_{i} I-\left[\frac{1}{\tau_{21}}+p_{21}+p_{12}\right] n_{i}+\left[-\frac{g_{2}}{g_{1}} \frac{1}{\tau_{21}}+p_{12}-\frac{g_{2}}{g_{1}} p_{21}\right] n_{d}+P_{2}\left(1+\frac{g_{2}}{g_{1}}\right)
$$

(12')
$$
\frac{1}{\tau}=\frac{1}{\tau_{21}}+p_{21}+p_{12} \text { (12) }
$$

(13)
$$ ( 13) \quad
K=\left(\frac{g_{2}}{g_{1}} \frac{1}{\tau_{21}}-p_{12}+\frac{g_{2}}{g_{1}} p_{21}\right) n_{d}
$$

(14)

(14)
$$
P=-K+\left(1+\frac{g_{2}}{g_{1}}\right) P_{2}=-K+\left(1+\frac{g_{2}}{g_{1}}\right) P_{3}
$$


(15)
$$
\frac{d n_{i}}{d t}=-\left(1+\frac{g_{2}}{g_{1}}\right) \frac{\sigma_{21}}{h v_{0}} n_{i} I-\frac{1}{\tau} n_{i}+P
$$

### 4 Niveles

$$ \boxed{
n_{1} \approx 0 \quad p_{2 n} \approx 0 \quad n_{2}<<n_{0} \quad n_{0} \approx n_{d}
}$$


(16)
$$
\frac{d n_{2}}{d t} \stackrel{(1)}=  -\frac{\sigma_{21}}{h v_{0}} n_{2} I-\left(\frac{1}{\tau_{21}}+p_{21}\right) n_{2}+P_{2} \quad(16)
$$


(17)
$$
\frac{d n_{i}}{d t}=-\frac{\sigma_{21}}{h v_{0}} n_{i} I-\frac{1}{\tau} n_{i}+P
\quad (17)$$

Comparar con (15)

### Regímenes de trabajo

Cambio de régimen:
$$ (18)
\left.\begin{array}{l}{\left(1+\frac{g_{2}}{g_{1}}\right) \frac{\sigma_{21}}{h v_{0}} I_{0} \approx \frac{1}{\tau}(3 \text { niveles })} \\ {\frac{\sigma_{21}}{h v_{0}} I_{0} \approx \frac{1}{\tau}(4 \text { niveles })}\end{array}\right\}
$$

$$ (19)
I_{0}^{(3)}=\frac{h v_{0}}{\left(1+g_{2} / g_{1}\right) \sigma_{21} \tau}
$$

$$ (20)
I_{0}^{(4)}=\frac{h v_{0}}{\sigma_{21} \tau} \quad(20)
$$

$$ (21)
\frac{d n_{i}}{d t}=-\left(1+\frac{I}{I_{0}}\right) \frac{n_{i}}{\tau}+P \quad(21)
$$

$$
\frac{d n_{i}}{d t}=0 \quad(22)
$$

$$ (23)
n_{i}=\frac{P \tau}{1+I / I_{0}}
$$

$$
\alpha_{0} \approx P \tau \sigma_{21}
$$

Fórmula de Rigrod:
$$ (24)
\frac{d I}{d x}=\alpha I \Rightarrow \alpha=\frac{1}{I} \frac{d I}{d x}=\frac{\alpha_{0}}{1+I / I_{0}}
$$

$$ (25)
I+I_{0} \ln I ]_{I(0)}^{I(x)}=\alpha_{0} I_{0} x
$$


(26)
$$
\frac{I(x)}{I(0)}-1+\frac{I_{0}}{I(0)} \ln \frac{I(x)}{I(0)}=\alpha_{0} \frac{I_{0}}{I(0)} x
$$

$$ (27)
\frac{I(0)}{I_{0}}=\frac{\alpha_{0} x-\ln G(x)}{G(x)-1}
$$

En pequeña señal ((24)) se reduce a
(28)
$$(28)
\frac{d I}{d x}=\alpha_{0} I \Rightarrow I(x)=I(0) e^{\alpha_{0} x}
$$

### Nivel de ruido en el amplificador

Fracción de fluorescencia en  $\Delta \Omega \text { y } \delta v$
(29)
$$(29)
{\frac{d I_{R}}{d x}=\left(n_{i} \sigma_{21}-\alpha_{i}\right) I_{R}+\frac{n_{2}}{\tau_{21}} h v_{0} \frac{\Delta \Omega}{4 \pi} \frac{\delta v}{\Delta v}}
$$

Con ci. $I_{R}(0)=0$:
(30)
$$
{I_{R}(x)=\frac{\Delta \Omega}{4 \pi} \frac{\delta v}{\Delta v} \frac{h v_{0}}{\tau_{21}} \int_{0}^{x} e^{\left(n_{i} \sigma_{21}-\alpha_{i}\right) x^{\prime}} n_{2} d x^{\prime}}$$

Se amplificará:
(31)
$$
I_{R}(l)=\frac{\Delta \Omega}{4 \pi} \frac{\delta v}{\Delta v} \frac{h v_{0}}{\tau_{21}} n_{2} \frac{e^{\left(n_{i} \sigma_{21}-\alpha_{i}\right) l}-1}{n_{i} \sigma_{21}-\alpha_{i}}
$$

Desarrollando en serie y con $I_{e s p}(l)=N I_{e s p}\left(\frac{l}{N}\right)$ la ganancia del medio es:
(32)
$$
\frac{I_{R}(l)}{I_{e s p}(l)} \stackrel{\alpha_{0}=\sigma_{21} n_{i}}=\frac{e^{\left(\alpha_{0}-\alpha_{i}\right) l}-1}{\left(\alpha_{0-} \alpha_{i}\right) l}
$$

(33)
$$
I_{\text {esp total}}=N I_{e s p}(l / N)=\frac{h v_{0}}{\tau_{21}} l n_{2}
$$

(34)
$$
\frac{e^{\alpha_{0} l}-1}{\alpha_{0} l} \frac{\Delta \Omega}{4 \pi} \frac{\delta v}{\Delta v} \approx 1
$$

### Caracterización de un amplificador de raciación

#### Método de Silvfast-Deech

(33)
$$
\frac{I_{R}(l)}{I_{R}(l / 2)}=\frac{e^{\alpha_{0} l}-1}{e^{\alpha_{0} l / 2}-1}
$$

(34)
$$
e^{\alpha_{0} l}-\frac{I_{R}(l)}{I_{R}(l / 2)} e^{\alpha_{0} l / 2}+\frac{I_{R}(l)}{I_{R}(l / 2)}-1=0
$$

(34a)
$$
e^{\alpha_{0} l / 2}=\frac{I_{R}(l)}{I_{R}(l / 2)}-1 \Rightarrow \alpha_{0}=\frac{2}{l} \ln \left(\frac{I_{R}(l)}{I_{R}(l / 2)}-1\right) \quad(34 a)
$$

#### Método de amplificación relativa

(35)
$$
\frac{I(l)}{I(0)}=\exp \left(\alpha_{0} l\right) \exp \left(-\frac{I(l)-I(0)}{I_{0}}\right)
$$

(36)
$$
\frac{\Delta I}{I(0)}=\frac{I(l)-I(0)}{I(0)}=\frac{I(l)}{I(0)}-1=\exp \left(\alpha_{0} l\right) \exp \left(-\frac{I(l)-I(0)}{I_{0}}\right)-1
$$

En baja señal:
(37)
$$
\lim _{I(0) \rightarrow 0} \frac{I(l)}{I(0)} \stackrel{ (35) }=\exp \left(\alpha_{0} l\right)=\frac{d I(l)}{d I(0)}
$$

(38)
$$
\lim _{I(0) \rightarrow 0} \frac{\Delta I}{I(0)} \stackrel{ ( 36) }=\exp \left(\alpha_{0} l\right)-1
$$

(39)
$$
\frac{d}{d I(0)} \frac{\Delta I }{I(0)} \stackrel{(36)}=\exp \left(\alpha_{0} l\right) \exp \left(-\frac{I(l)-I(0)}{I_{0}}\right)\left(-\frac{1}{I_{0}} \frac{d I(l)}{d I(0)}+\frac{1}{I_{0}}\right) \quad \text { (39) }
$$

(40)
$$
\lim _{I(0) \rightarrow 0} \frac{d}{d I(0)} \frac{\Delta I}{I(0)}=-\frac{1}{I_{0}} \exp \left(\alpha_{0} l\right)\left(\exp \left(\alpha_{0} l\right)-1\right)
$$

(41)
$$
\frac{\exp \left(\alpha_{0} l\right)-1}{I_{m}} \stackrel{(40)}=\frac{1}{I_{0}} \exp \left(\alpha_{0} l\right)\left(\exp \left(\alpha_{0} l\right)-1\right)
$$



---
>.
> Intervalo Publicitario
>.
---


## 3.2. Pulsos en estado cuasiestacionario

Hasta alcanzar el umbral:
(1)
$$
\frac{d n_{i}}{d t}=-\frac{n_{i}}{\tau}+P(t)
$$

(2)
$$
n_{i}(t)=\int_{0}^{t} P\left(t^{\prime}\right) e^{-\frac{t-t^{\prime}}{\tau}} d t^{\prime}
$$

(3)
$$n_{i u}=\int_{0}^{t_{u}} P\left(t^{\prime}\right) e^{-\frac{t_{u}-t^{\prime}}{\tau}} d t^{\prime}=-\frac{1}{\sigma_{21} L}\left(\ln R-\alpha_{i} L\right)$$

(4)
$$\left(n_{i}\right)_{u} \approx \int_{0}^{t_{u}} P\left(t^{\prime}\right) d t^{\prime}$$

(5)
$$\frac{d n_{i u}}{d t}=-\frac{1}{\tau}\left(1+\frac{I}{I_{0}}\right) n_{i u}+P(t) \approx 0$$

(6)
$$I=I_{0}\left(\frac{\tau P(t)}{n_{i u}}-1\right) \quad(6)$$

(7)
$$I_{s 2}=\left(1-R_{2}\right) I_{+}(l)$$

(8)
$$I \approx I_{+}(l)+I_{-}(l)=I(l)$$

(9)
$$I_{+}(l) \approx \frac{I}{1+R_{2}}$$

(10)
$$I_{s 2} \approx \frac{1-R_{2}}{1+R_{2}} I \stackrel{(6)}=I_{0} \frac{1-R_{2}}{1+R_{2}}\left(\frac{\tau P(t)}{n_{i u}}-1\right) \quad(10)$$

Como $n_{i u}=\frac{\alpha_{i} L-\ln R}{\sigma_{21} L}$:
(11)
$$
I_{s 2}=I_{0} \frac{1-R_{2}}{1+R_{2}}\left(\frac{\tau P(t) \sigma_{21} L}{\alpha_{i} L-\ln R}-1\right)
$$

(12)
$$
I_{s 2} \approx I_{0} \frac{1-R_{2}}{1+R_{2}}\left(\frac{\alpha_{0}(t) L}{\alpha_{i} L-\ln R}-1\right)
$$

(13)
$$
e^{\alpha_{0} L-\left(\alpha_{i} L-\ln R\right)} \approx 1
$$

(14)
$$
\frac{d n_{i}}{d t}=-\frac{n_{i}}{\tau}+P(t) \quad(14)
$$

(15)
$$
n_{i}(t)=n_{i u} e^{-\frac{t-t f}{\tau}}+\int_{t_{f}}^{t} P\left(t^{\prime}\right) e^{-\frac{t-t^{\prime}}{\tau}} d t^{\prime} \quad(15)
$$



---
>.
> Intervalo Publicitario
>.
---


## 3.3. Optimización a la salida de un láser

(1)
$$
I_{s 2} \approx I_{0} \frac{1-R_{2}}{1+R_{2}}\left(\frac{\frac{2 \alpha_{0} L}{2 \alpha_{i} L}}{1-\frac{\ln R_{2}}{2 \alpha_{i} L}}-1\right)
$$

(2)
$$
y=\frac{1-x}{1+x}\left(\frac{\sigma}{1-\frac{\ln x}{\delta}}-1\right)
$$

(3)
$$
\frac{d y}{d x}=-\frac{2}{(1+x)^{2}}\left(\frac{\sigma}{1-\frac{\ln x}{\delta}}-1\right)+\frac{1-x}{1+x} \frac{\sigma}{\delta x} \frac{1}{\left(1-\frac{\ln x}{\delta}\right)^{2}}
$$

Sale la ecuación trascendente:
(4)
$$
-2\left[\sigma-\left(1-\frac{\ln x}{\delta}\right)\right]+\frac{\sigma}{\delta}\left(\frac{1}{x}-x\right) \frac{1}{1-\frac{\ln x}{\delta}}=0
$$

(5)
$$
1-\frac{\ln x}{\delta}=\sqrt{\sigma}
$$

(6)
$$
-2[\sigma-\sqrt{\sigma}]+\frac{\sigma}{\delta}\left[e^{(\sqrt{\sigma}-1) \delta}-e^{-(\sqrt{\sigma}-1) \delta}\right] \frac{1}{\sqrt{\sigma}} \approx 0
$$

(7)
$$
-2[\sigma-\sqrt{\sigma}]+\frac{\sigma}{\delta} 2(\sqrt{\sigma}-1) \delta \frac{1}{\sqrt{\sigma}} \approx 0
$$

(8)
$$
\left(R_{2}\right)_{o p t}=e^{-\left(\sqrt{\frac{a_{0}}{\alpha_{i}}}-1\right) 2 \alpha_{i} L}
$$

(9)
$$
\begin{array}{l}{y_{\max }=\frac{1-e^{-(\sqrt{\sigma}-1) \delta}}{1+e^{-(\sqrt{\sigma}-1) \delta}}\left(\frac{\sigma}{\sqrt{\sigma}}-1\right) \approx \frac{1}{2}(\sqrt{\sigma}-1)^{2} \delta=\left(\sqrt{\frac{\alpha_{0} L}{\alpha_{i} L}}-1\right)^{2} \alpha_{i} L=} \\ {=\alpha_{0} L\left(1-\sqrt{\frac{\alpha_{i} L}{\alpha_{0} L}}\right)^{2}=\frac{I_{\max }}{I_{0}} \quad(9)}\end{array}
$$

(10)
$$
I_{\max }=I_{0} \alpha_{0} L\left(1-\sqrt{\frac{\alpha_{i} L}{\alpha_{0} L}}\right)^{2}
$$

(11)
$$
\left(\alpha_{0}\right)_{u} L=\tau \sigma_{21} P_{u} L=\alpha_{i} L-\ln \sqrt{R_{2}}
$$

(12) Para otro valor $R'_2$:
$$
\tau \sigma_{21} P_{u}^{\prime} L=\alpha_{i} L-\ln \sqrt{R_{2}^{\prime}}
$$

(13)
$$
\alpha_{i} L=\frac{\ln \sqrt{R_{2}}-\frac{P_{u}}{P_{u}^{\prime}} \ln \sqrt{R_{2}^{\prime}}}{1-P_{u} / P_{u}^{\prime}}
$$

(14)
$$
\alpha_{0} L=\tau P \sigma_{21} L
$$

(15)
$$
\begin{aligned}\left(\alpha_{0}\right)_{u} L &=\tau P_{u} \sigma_{21} L=\alpha_{i} L-\ln \sqrt{R_{2}} \\ \tau \sigma_{21} L &=\frac{\alpha_{i} L-\ln \sqrt{R_{2}}}{P_{u}} \end{aligned}
$$

(16)
$$
\alpha_{0} L=\frac{P}{P_{u}}\left(\alpha_{i} L-\ln \sqrt{R_{2}}\right)
$$

(17)
$$
\left(R_{2}\right)_{o p t}=e^{-\left(\sqrt{\frac{\alpha_{0}}{\alpha_{i}}-1}\right) 2 \alpha_{i} L}
$$

(18)
$$
\frac{\alpha_{0} L}{\left(\alpha_{i} L-\ln \sqrt{R_{2}}\right)}=\frac{P}{P_{u}}
$$

(19)
$$
I_{s 2}=I_{0} \frac{1-R_{2}}{1+R_{2}}\left(\frac{P}{P_{u}}-1\right)
$$

(20)
$$
I_{0}=I_{s 2} \frac{1+R_{2}}{1-R_{2}} \frac{1}{\left(\frac{P}{P_{u}}-1\right)}
$$



---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---


# T4: Resonadores

> En el formulario qe hizo en clase rehacer poniendo las cosas en funcion de g1 y g2

Fabry-Perot:
$$
\mathscr{R}=\left(\mathscr{R}_{1} \mathscr{R}_{2}\right)^{1 / 2}
$$

$$
\mathscr{T}(v)=\frac{1}{1+\frac{4 \mathscr{R}}{(1-\mathscr{R})^{2}} \operatorname{sen}^{2}\left[2 \pi L \frac{\nu}{c_{0}} n\right]} \quad \text { Máximos en } 2 \pi n L \nu / c_{0}=p \pi, \quad p \in Z^{+}
$$

$$
{l}{\Delta v=v_{p+1}-v_{p}=\frac{c_{0}}{2 n L}}
$$

$$
\delta v=\frac{c_{0}}{2 \pi n L} \frac{(1-\mathscr{R})}{\sqrt{\mathscr{R}}}
$$



---
>.
> Intervalo Publicitario
>.
---


## 1. Tiempo de vida del fotón

$$
p_{\text { salir }}=1-\mathscr{R}
$$

Tiempo de vida en la cavidad:
$$
t_{C}=\frac{n L}{c_{0}(1-\mathscr{R})}=\frac{1}{2 \pi \delta v}
$$

Atenuación en i/v:
$$
R^{2} I_{0}
$$

$$
\frac{I_{0}}{e}=I_{0}(R)^{2 n_{c}} ; n_{c}=-\frac{1}{2 \ln R}
$$

$$
t_{c}=\frac{2 L n_{c}}{c}=-\frac{L}{c \ln R}=\frac{L}{c} \frac{1}{1-R}
$$

Con transmitancia interna $T_i$:
$$
t_{c}=-\frac{L}{c \ln \left(R T_{i}\right)}
$$



---
>.
> Intervalo Publicitario
>.
---


## 2. Factor de calidad

Energía en t / Energía en T
En un ciclo abandonan $n_{f} T / t_{c}$ fotones:
$$
Q=\frac{2 \pi t_{c}}{T}=2 \pi v_{e} t_{c}=2 \pi v_{e} \frac{n L}{c_{0}(1-\mathscr{R})} \approx \frac{v_{e}}{\delta v}
$$



---
>.
> Intervalo Publicitario
>.
---


## 3. Haces Gaussianos

1. Ecuación de ondas
2. Aproximación paraxial
3. Ondas esféricas en aproximación paraxial
4. Modos gaussianos
5. Propiedades de los haces gaussianos
6. Distribución transversal de energía
7. Estabilidad de un resonador
8. La función de transferencia de un sistema óptico
9. Frecuencia resonantes de los modos gaussianos
10. El perfil de los modos en un resonador Fabry-Perot

### 4.3.1. Ecuación de ondas

$$
(1) \Delta E-\frac{1}{c^{2}} \frac{\partial^{2} E}{\partial t^{2}}=0
$$

$$
\overline{E}=U(\overline{r}) e^{i(\omega t-k z)} \quad k^{2}=\omega^{2} / c^{2}
$$

$$
\Delta U-2 i k \frac{\partial U}{\partial z}=0
$$

### 4.3.2. Aproximación paraxial

$$
\frac{\partial^{2} U}{\partial z^{2}}<<\left|2 i k \frac{\partial U}{\partial z}\right| \Rightarrow \frac{\lambda}{4 \pi} \frac{\partial^{2} U}{\partial z^{2}}<<\frac{\partial U}{\partial z}
$$

$$
\frac{\partial^{2} U}{\partial x^{2}}+\frac{\partial^{2} U}{\partial y^{2}}-2 i k \frac{\partial U}{\partial z}=\Delta_{t} U-2 i k \frac{\partial U}{\partial z} \approx 0
$$

$$
\begin{array}{l}{\frac{\partial^{2} U}{\partial z^{2}}=-k^{2}(1-\cos \theta)^{2} U \approx k^{2} \frac{\theta^{4}}{4} U} \\ {\frac{\partial^{2} U}{\partial x^{2}}=-k^{2} \operatorname{sen}^{2} \theta U \approx-k^{2} \theta^{2} U}\end{array}
$$

### 4.3.3. Ondas esféricas en aproximación paraxial

$$
\overline{E}\left(\overline{r}, \overline{r}_{F}\right)=\frac{e^{-i k \rho\left(\overline{r}, \overline{r}_{F}\right)}}{\rho\left(\overline{r}, \overline{r}_{F}\right)}
$$

$$
\begin{array}{l}{\rho\left(\overline{r}, \overline{r}_{F}\right)=\left(z-z_{F}\right)\left[1+\frac{\left(x-x_{F}\right)^{2}+\left(y-y_{F}\right)^{2}}{\left(z-z_{F}\right)^{2}}\right]^{1 / 2}} \approx {\left(z-z_{F}\right)+\frac{1}{2} \frac{\left(x-x_{F}\right)^{2}+\left(y-y_{F}\right)^{2}}{\left(z-z_{F}\right)} \quad(8)}\end{array}
$$

$$
\begin{array}{ll}{\overline{E}\left(\overline{r}, \overline{r}_{F}\right)=\frac{1}{z-z_{F}} \exp \left[-i \frac{k}{2} \frac{\left(y-y_{F}\right)^{2}+\left(x-x_{F}\right)^{2}}{z-z_{F}}\right] \exp \left[-i k\left(z-z_{F}\right)\right]=} \\ {=U\left(\overline{r}-\overline{r}_{F}\right) \exp \left[-i k\left(z-z_{F}\right)\right] \quad(9)} & {\text { Esta U es solución de }(5)}\end{array}
$$

$$
\begin{array}{l}{\text { La fuente F está en } \overline{r}_{F}\left(x_{F}=y_{F}=0\right) \text { el eje }} \\ {R(z) \quad \text { Radio de curvatura }} \\ {\phi(z) \text { Fase transversa }} \\ {\text { En el punto } z_{0}}\end{array}
$$

#### Fase Transversa

$$
U\left(\overline{r}_{0}\right)=\frac{e^{-i \phi\left(r_{0}\right)}}{R\left(z_{0}\right)}
$$

$$
\phi\left(\overline{r}_{0}\right)=\frac{k}{2} \frac{x_{0}^{2}+y_{0}^{2}}{R\left(z_{0}\right)}
$$

Valen en z tambien. La posición de $z_o$ es arbitraria.

$$
(12) R(z)=z-z_{F}=z-\left[z_{0}-R\left(z_{0}\right)\right]
$$

$$
q_{r} \equiv R(z)=z-z_{F} \rightarrow q(z)=  \stackrel{z_{0}-q_{0}-R\left(z_{0}\right)= z_0 - q_0}{z-z_{0}+q_{0}=q_{o r}+z-z_{0}+i q_{0 i}}
$$

$$
\text { (14) } \frac{1}{q(z)}=\frac{1}{q_{o r}+z-z_{0}+i q_{0 i}}=\frac{q_{0 r}+z-z_{0}-i q_{0 i}}{\left(q_{0 r}+z-z_{0}\right)^{2}+q_{0 i}^{2}}=\frac{1}{R(z)}-i \frac{2}{k w^{2}(z)} \quad
$$

### Perfil de amplitud transverso

$$
\phi(\overline{r})=\frac{k}{2}\left(x^{2}+y^{2}\right)\left(\frac{1}{R(z)}-i \frac{2}{k w^{2}(z)}\right)
$$

$$
{l}{R(z)=\frac{\left(q_{o r}+z-z_{0}\right)^{2}+q_{0 i}^{2}}{q_{o r}+z-z_{0}}}
$$

$$
{w^{2}(z)=\frac{2}{k} \frac{\left(q_{o r}+z-z_{0}\right)^{2}+q_{0 i}^{2}}{q_{0 i}}} \text { Cintura del haz en z}
$$

## 4.3. Modos gaussianos

Ecuación:
$$
\frac{\partial^{2} U}{\partial x^{2}}+\frac{\partial^{2} U}{\partial y^{2}}-2 i k \frac{\partial U}{\partial z}=0 \quad \text { (15) }
$$

Solución:
$$
U_{n m}(\overline{r})=U_{n}(x, z) U_{m}(y, z)
$$

Desarrollo:
$$
{l}{\frac{\partial^{2} U_{n}}{\partial x^{2}}-2 i k \frac{\partial U_{n}}{\partial z}=f(z) U_{n} = \stackrel {f(z) = 0} 0}
$$

$$
{\frac{\partial^{2} U_{m}}{\partial y^{2}}-2 i k \frac{\partial U_{m}}{\partial z}=f(z) U_{m}=0 \quad(18)}
$$

Solución BIEN:
$$
(19) \quad U_{n}(x, z)=\left(\frac{2}{\pi}\right)^{1 / 4} \sqrt{\frac{e^{i(2 n+1)[\psi(z)-\psi(0)]}}{2^{n} n ! w(z)}} H_{n}\left(\frac{x \sqrt{2}}{w(z)}\right) e^{-\frac{x^{2}}{w^{2}(z)}} e^{-i \frac{k x^{2}}{2 R(z)}}
$$

DEF: Fase de Guoy:
$$
\tan \psi(z)=\frac{k w^{2}(z)}{2 R(z)}
$$

Polinomios de Hermite:
$$
(20) \quad H_{n}(\xi)=(-1)^{n} e^{\xi^{2}} \frac{\partial^{n}}{\partial \xi^{n}}\left[e^{-\xi^{2}}\right] \quad(20)
$$

$$
H_{0}=1, H_{1}=2 \xi \Rightarrow H_{n+1}=2 \xi H_{n}-2 n H_{n-1} \quad(22)
$$

Igual para $U_m$
$$
E(\overline{r})=\left( \begin{array}{c}{\sum_{n} C_{n m}(z) U_{n}(x, z) U_{m}(y, z) ) e^{-i k z} \quad(23)}\end{array}\right.
$$

$$
C_{n m}=\int_{-\infty}^{\infty} \int_{-\infty}^{\infty} U_{n}^{*}(x, z) U_{m}^{*}(y, z) E(\overline{r}) e^{i k z} d x d y
$$

Representando
$$
a_{n}=H_{n}\left(\frac{x \sqrt{2}}{w(z)}\right) \exp \left(-\frac{x^{2}}{w^{2}(z)}\right)
$$

Obtenemos modos TEM:
$$
(25)\quad E_{n m} \propto H_{n}\left(\frac{x \sqrt{2}}{w_{x}(z)}\right) H_{m}\left(\frac{y \sqrt{2}}{w_{y}(z)}\right) e^{-\frac{x^{2}}{w_{x}^{2}}-\frac{y^{2}}{w_{y}^{2}}-i \frac{k x^{2}}{2 R_{x}}} e^{-i \frac{k y^{2}}{2 R_{y}}} e^{-i k z}
$$

Cumpliendo:
(26)
$$
\frac{w(z)}{q(z)}=\frac{w(0)}{q(0)}
$$

### 4.3.5. Propiedades de los haces gaussianos

(27)
$$
q(z)=q_{0}+z
$$

(28)
$$
q(0)=i \frac{\pi w^{2}(0)}{\lambda}=i z_{R}
$$

(29)
$$
z_{R}=\frac{\pi w^{2}(0)}{\lambda}
$$

(30)
$$
R(z)=z\left[1+\left(\frac{z_{R}}{z}\right)^{2}\right]
$$

(31)
$$
w(z) = w(0)\left[1+\left(\frac{z}{z_{R}}\right)^{2}\right]^{1 / 2}
$$
$$
(z _R=\frac{\pi w^{2}(0)}{\lambda})
$$

(32)
$$
\tan \psi(z)\stackrel{(30)(31)}=\frac{k w^{2}(z)}{2 R(z)}=\frac{\pi}{\lambda} \frac{\lambda z_{R}}{\pi z} \frac{1+\left(z / z_{R}\right)^{2}}{1+\left(z / z_{R}\right)^{2}}=\frac{z}{z_{R}}
$$

(33)
$$
U_{00}(\overline{r})=\left(\frac{2}{\pi}\right)^{1 / 2} \frac{e^{i \psi(z)}}{w(z)} \exp \left(-\frac{x^{2}+y^{2}}{w^{2}(z)}\right) \exp \left(-i k \frac{x^{2}+y^{2}}{2 R(z)}\right)
$$

(34)
$$
b=2 z_{R}=\frac{2 \pi w_{0}^{2}}{\lambda}
$$

(35)
$$
\left.\begin{array}{l}{\lim _{z \rightarrow \infty} w(z)\stackrel{(31)}=w_{0} \frac{z}{z_{R}}=\frac{\lambda}{\pi} \frac{z}{w_{0}}} \\ {\lim _{z \rightarrow \infty} R(z)\stackrel{(30)}=z}\end{array}\right\}
$$

(36)
$$
w_{0}\stackrel{(29)}=\sqrt{\frac{\lambda z_{R}}{\pi}}=\sqrt{\frac{\lambda b}{2 \pi}}
$$

(37)
$$
2 w_{0}=\frac{\lambda}{\pi} \frac{2 f}{w(-f)}
$$

(38)


### 4.3.6. Distribución transversal de energía

(39)
$$
x_{n}(z) \approx \sqrt{n} w(z)
$$

(40)
$$
n_{\max } \leq\left(\frac{a}{w(z)}\right)^{2}
$$

Tamaño medio de los máximos:
(41)
$$
\Lambda_{n} \approx \frac{1}{2} \frac{x_{n}}{n} \approx \frac{1}{2} \sqrt{n} \frac{w}{n}=\frac{1}{2} \frac{w}{\sqrt{n}}
$$
Estructuras mínimas que pueden observarse:
$$
\Lambda_{\min }=\frac{1}{2} \frac{w^{2}}{a}
$$
En la cintura del haz de un resonador confocal:
$$
\Lambda_{\min }=\frac{1}{2} \frac{w_{0}^{2}}{a}=\frac{1}{2} \frac{\lambda b}{2 \pi a}=\frac{1}{2} \frac{a}{2 \pi N_{F}}
$$

### 4.3.7. Estabilidad de un resonador

(42)
$$
\begin{array}{l}{g_{1}=1-\frac{L}{R_{1}}} \\ {g_{2}=1-\frac{L}{R_{2}}}\end{array}
$$

(43)
$$
g_{1}=1+\frac{L}{z_{1}\left(1+z_{R}^{2} / z_{1}^{2}\right)}
$$

(44)
$$
g_{2}=1-\frac{L}{z_{2}\left(1+z_{R}^{2} / z_{2}^{2}\right)}
$$

(45)
$$
z_{R}^{2}=\frac{g_{1} g_{2}\left(1-g_{1} g_{2}\right)}{\left(g_{1}+g_{2}-2 g_{1} g_{2}\right)^{2}} L^{2}
$$

(46)
$$
w_{o}^{2}=\frac{L \lambda}{\pi} \sqrt{\frac{g_{1} g_{2}\left(1-g_{1} g_{2}\right)}{\left(g_{1}+g_{2}-2 g_{1} g_{2}\right)^{2}}}
$$

(47)
$$
w_{1}^{2}=\frac{L \lambda}{\pi} \sqrt{\frac{g_{2}}{g_{1}\left(1-g_{1} g_{2}\right)}}
$$

(48)
$$
w_{2}^{2}=\frac{L \lambda}{\pi} \sqrt{\frac{g_{1}}{g_{2}\left(1-g_{1} g_{2}\right)}}
$$

(49)
$$
1 \geq g_{1} g_{2} \geq 0 \quad(49)
$$

### 4.3.8. La función de transferencia de un sistema óptico


### 4.3.9. Frecuencia resonantes de los modos gaussianos

$$
U_{n m}(\overline{r})=\left(\frac{2}{\pi}\right)^{1 / 2} \frac{e^{i(n+m+1)[\psi(z)-\psi(0)]}}{2^{n+m} n ! m ! w(z)} H_{n}\left(\frac{x \sqrt{2}}{w(z)}\right) H_{m}\left(\frac{y \sqrt{2}}{w(z)}\right) e^{-\frac{x^{2}+y^{2}}{w^{2}(z)}} e^{-i \frac{k\left(x^{2}+y^{2}\right)}{2 R(z)}}
$$

$$
\begin{array}{l}{\text { Contribuciones a la fase del campo }} \\ {\text { longitudinal } e^{-i k z}} \\ {\text { transversa } e^{i[(n+m+1) \Delta \psi]}}\end{array}
$$

$$
\begin{array}{l}{\phi\left(z_{2}-z_{1}\right)=k\left(z_{2}-z_{1}\right)-(n+m+1)\left[\psi\left(z_{2}\right)-\psi\left(z_{1}\right)\right]=\frac{\omega}{c} L-(n+m+1)\left[\psi\left(z_{2}\right)-\psi\left(z_{1}\right)\right]} \\ {\omega_{q, n m}=\frac{\pi c}{L}\left[q+(n+m+1) \frac{\psi\left(z_{2}\right)-\psi\left(z_{1}\right)}{\pi}\right]}\end{array}
$$

$$
\begin{array}{l}{\tan \psi\left(z_{2}\right)=\frac{z_{2}}{z_{R}}=\frac{g_{1}\left(1-g_{2}\right)}{\sqrt{g_{1} g_{2}\left(1-g_{1} g_{2}\right)}}} \\ {\tan \psi\left(z_{1}\right)=\frac{z_{1}}{z_{R}}=-\frac{g_{2}\left(1-g_{1}\right)}{\sqrt{g_{1} g_{2}\left(1-g_{1} g_{2}\right)}}}\end{array}
$$

### 4.3.10. El perfil de los modos en un resonador Fabry-Perot
