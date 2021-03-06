![LasPortada](https://lh3.googleusercontent.com/4Gl8A8KEPNoS9YqhAgDXpZgVeJiwjOfftYZdLjeAxgP8xmKQkKZdkeACg87Lg2h4pfLqiE4cTmWu "LasPortada")


# T1

## 1. Probabilidad de emisión espontánea y estimulada. Equilibrio térmico a $\mathrm { T } = 300 \mathrm { K }$ para la zona del visible $\mathrm { y }$ la zona de las microondas.

[Sol]

Emisión $\rightarrow  A$
Estimulada $\rightarrow B \rho$


$$\boxed{\frac { A} { B \rho } = \frac { 8 \pi h \nu ^ { 3 } } { c ^ { 3 } } \frac  { c ^ { 3 } }  { 8 \pi h \nu ^ { 3 } } (e ^ { h \nu / k _ { B } T } - 1 ) = e ^ { h \nu / k _ { B } T } - 1  } $$


### Visible


$$\nu = 3\cdot 10^{14} Hz$$


$$\frac { A} { B \rho } = 7,12 \cdot 10^{20}$$


$$\frac { B \rho } { A} << 1$$


> Muy pequeña, por eso no hay láseres ni se ven en el dia a dia la emisión estimulada.


### Microondas


$$\nu = \{ 300 MHz - 3000 GHz \}$$


300 GHz:
: $$\frac { A} { B \rho } = 4,8 \cdot 10^{-5}$$

: $$\frac { B \rho } { A} >> 1$$

3000 MHz:
: $$\frac { A} { B \rho } = 0,0492$$

: $$\frac { B \rho } { A} >> 1$$


> Hay mucha emisión, mucha radiación y por tanto también mucha estimulada. Por eso no hay que hacer nada para ver en micro en estimulada.
> Se llaman MASER, se ven en astro.
> Pej: MASER( agua) $$\{ 96 GHz - 22 GHz \}$$


[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 2. Considera una cavidad de paredes perfectamente conductoras y tamaño 2$\mathrm { a } \times 2 \mathrm { a } \times \mathrm { L }$ , con $\mathrm { L } > 2 \mathrm { a }$ . Calcula cuál será la frecuencia minima que puede oscilar dentro de la cavidad.

[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 3. Considera un sistema de dos niveles en que el nivel superior decae con tiempo de vida t, tiene una eficiencia cuántica $\phi$ y que en $t = 0$ tiene $n _ { 2 }$ átomos por unidad de volumen en el nivel $2 .$ Calcula el número de fotones que se habrán emitido entre $t = 0$ y un tiempo t.


[Sol]

$$\frac { dn_2} { dt} = -\frac { 1} { \tau } n_2 $$

$$n_2(t) = \int (-\frac { 1} { \tau } )n_2 dt = n_2(0) e^{-\frac { t} { \tau }}$$

![] Decaimiento Niveles


¿Pero qué les pasa a los fotones?
$\tau$ sólo mide cuánto tarda en bajar el nivel. Igual no emite un fot´çon cada unidad de tiempo. Necesitaremos $\tau_r$ así que usaremos $\phi$.

$$\frac {dq} {dt} = \frac {\phi} {\tau} n_2 = -\phi \frac { dn_2} { dt} = \frac {\phi} {\tau}n_2(0) e^{-\frac { t} { \tau }}$$
$$\frac {dq} {dt} \propto P.I$$ Decae exponencialmente
![qfrentet](IMG)

Hay que integrar de 0 a t.

$$
q(t)  = \int^t_0\frac {\phi} {\tau}n_2(0) e^{-\frac { t} { \tau }}dt = \frac {\phi} {\tau} (-\tau)n_2(0) e^{-\frac { t} { \tau }} ]^t_0
$$

$$
= -\phi n_2(0) (e^{-\frac { t} { \tau }}-1)= \phi n_2(0) (1-e^{-\frac { t} { \tau }})
$$

$\phi n_2(0)$ Asintótico

> $n_2$ es fotones emitidos por V y t, igual lo necesitamos en otro caso para todo un V.

[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 4. La eficiencia cuántica de la transición de emision singlete-singlete $\mathrm { S } _ { 1 } \Rightarrow \mathrm { S } _ { 0 }$ de la Rodamina 6$\mathrm { G }$ es 0.97 y el tiempo de vida del nivel correspondiente es 5 ns. Calcular los tiempos de vida radiativo y no radiativo del nivel $\mathrm { S } _ { 1 }$ .

[Sol]

$$\phi=\frac {\tau} {\tau_r} = 0,97$$

$$\tau_r=\frac {\tau} {0,97} =5,15ns$$

> Recordar que $\tau_r>\tau$ siempre

$$\frac {1} {\tau} = \frac {1} {\tau_{nr}} +\frac {1} {\tau_r}$$

$$\tau_{nr} = \frac {\tau\tau_r} {\tau_r - \tau} = 1,71 \cdot 10 ^ 2 ns$$

[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 5. Se quiere usar una barra de Nd:YAG como medio activo láser. En la siguiente figura se da el espectro de absorción de una barra dopada al 1$\%$ con iones de Nd $^ { 3 + } .$ Calcular cuál será la absorbancia y la transmitancia a 808$\mathrm { nm }$ de una barra de 3$\mathrm { cm }$ de longitud $\mathrm { y }$ 0.3$\mathrm { cm }$ de diámetro.


[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 6. Un medio con un esquema de 3 niveles es excitado con radiación de frecuencia $v _ { 13 }$ con una densidad de radiación $\rho _ { 13 } .$ Calcula cuáles serán *las poblaciones de cada nivel en estado estacionario* si se desprecian las probabilidades de transición estimuladas entre los niveles 2 y $1 .$ ¿Cuál será la *densidad de fotones emitidos por unidad de volumen y de tiempo* en estas condiciones?

![Niveles6](https://lh3.googleusercontent.com/Mmj8PHLwqpv-hyrUU_aeKVystEJ3MZBsf3ewtn9bzgLIf_FviCYEVj7Fc8-MWMROWZg47VszHDYR)

[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 7. Considera el esquema de niveles de la figura.
### a) Escribe las [ecuaciones de balance para las poblaciones] y la [ecuación para la intensidad de radiación entre los niveles 1 y 2] .
### b) Si $\tau _ { 32 } < < \tau _ { 21 } ,$ calcula cuál debe ser la intensidad de radiación de frecuencia $v _ { 13 }$ para que el nivel 2 se pueble con el 10$\%$ de la densidad de población total $n ,$ en estado estacionario, suponiendo que las secciones eficaces $\sigma _ { 12 } , \sigma _ { 21 }$ son pequeñas.
### c) Comenta el resultado

![Niveles7](https://lh3.googleusercontent.com/YEkLte7GALjcBF_fWLG79i9bgFrs16i2MdT3phYAutmv7Fr8efl1wt2JJUwd_MybdyiTBb0f-6bp)


[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 8. Considera el esquema de niveles de la figura, con los siguientes datos:
### $\sigma _ { 13 } = 2 \times 10 ^ { - 20 }$$\mathrm { m } ^ { 2 } ; \lambda _ { 13 } = 514 \mathrm { nm } ; \tau _ { 32 } = 1 \mathrm { ps } ; \sigma _ { 21 } = 6 \times 10 ^ { - 20 } \mathrm { m } ^ { 2 } ; \tau _ { 21 } = 50 \mathrm { ns } ; n _ { 1 } = 1 \times 10 ^ { 24 } \mathrm { m } ^ { - 3 } ; \lambda _ { 21 } = 600 \mathrm { nm } .$
### Calcular cuál debe ser la intensidad $\mathrm { I } _ { 13 }$ en la longitud de onda $\lambda _ { 13 }$ con que se irradia el sistema para que el sistema dé una intensidad $\mathrm { I } _ { 12 } = 10 \mathrm { Wm } ^ { - 2 }$ en la longitud de onda $\lambda _ { 21 }$ en estado estacionario.
![Niveles7](https://lh3.googleusercontent.com/YEkLte7GALjcBF_fWLG79i9bgFrs16i2MdT3phYAutmv7Fr8efl1wt2JJUwd_MybdyiTBb0f-6bp)

[Sol]



[Moon]



---
---
# TEMA 2

## 9. Considera un láser de 3 niveles no degenerados, como el de la figura, donde $\tau _ { 32 } < \tau _ { 21 }$ en una cavidad de longitud $L ,$ indice de refracción $n = 1$ y reflectividad $R .$ El sistema se bombea con radiación de intensidad $I _ { 13 }$ constante.
### a) Escribe las ecuaciones que describen la evolución de las poblaciones.
### b) Escribe las ecuaciones que describen la inversión de población en estado estacionario.
### c) Calcula la inversión de población que hay cuando la intensidad de luz emitida por el sistema en el estado estacionario dentro de la cavidad vale $I _ { a }$ y es grande respecto a la fluorescencia.

![Niveles7](https://lh3.googleusercontent.com/YEkLte7GALjcBF_fWLG79i9bgFrs16i2MdT3phYAutmv7Fr8efl1wt2JJUwd_MybdyiTBb0f-6bp)

[Pis]

## 9. Pista

$$\tau_ {32} << \tau_{12}$$

$\tau_{12}$ fluorescencia

$L, n = 1, R, \chi = \sqrt{RR_0}$

$I_{13}$ bombeo constante

Diremos que: $\nu_{21} = \nu ; I_{21} = I$
___

[Moon]

[Sol]

## 9. Solución

### a) Evolución de las poblaciones

$$\frac {dn_3}{dt} = n_1 \sigma _ {13} \frac {I_{13}}{h\nu_ {13}} - \frac {n_3}{\tau_{32}}$$

$$\frac {dn_2}{dt} = \frac {n_3}{\tau _{32}} + ( n_1 - n_2 ) \sigma _ {21} \frac {I_{21}}{h\nu_ {21}} - \frac {n_2}{\tau_{21}}$$

$$n_3 + n_2 + n_1 = n_T$$

Y sabemos:

$$\frac {dn_T}{dt} = 0 = \frac {dn_1}{dt} + \frac {dn_2}{dt} + \frac {dn_3}{dt}$$

$$\frac {dn_1}{dt} = - n_1 \sigma _ {13} \frac {I_{13}}{h\nu_ {13}} + \frac {n_3}{\tau _ {32}} -\frac {n_3}{\tau _ {32}} -  ( n_1 - n_2 ) \sigma \frac {I}{h\nu} - \frac {n_2}{\tau_ {21}}$$

Soluciones:

$$\frac {dn_1}{dt} = - n_1 \sigma _ {13} \frac {I_{13}}{h\nu_ {13}} -  ( n_1 - n_2 ) \sigma \frac {I}{h\nu} - \frac {n_2}{\tau_ {21}}$$

$$\frac {dn_2}{dt} = \frac {n_3}{\tau _{32}} + ( n_1 - n_2 ) \sigma _ {21} \frac {I_{21}}{h\nu_ {21}} - \frac {n_2}{\tau_{21}}$$

$$\frac {dn_3}{dt} = n_1 \sigma _ {13} \frac {I_{13}}{h\nu_ {13}} - \frac {n_3}{\tau_{32}}$$


### b) Inversión de población en estado estacionario

$n_b^* = n_2 - n_1 \quad  {d_t n_b^*} = {d_t(n_2-n_1)}$

$$d_t n_b^* = n_3 / \tau _{32} + (n_1 + n_2 ) \sigma I/h\nu - n_2/ \tau _{21}$$

### c) Inversión de población en estado estacionario grande respecto a fluorescencia



[Moon]





---
>.
> Intervalo Publicitario
>.
---


## 10. En un láser de 3 niveles, deduce cómo depende la intensidad umbral del láser de la reflectividad $R = \left( R _ { 1 } R _ { 2 } \right) ^ { 1 / 2 }$ del resonador. Aplicalo a un caso de cavidades con distinta reflectividad $( R = 0.1,0.2 \ldots 0.9 )$ manteniendo $L = 10 \mathrm { cm }$ y comenta el resultado.
### Datos: $\sigma _ { 21 } = 6 \times 10 ^ { - 24 } \mathrm { m } ^ { 2 } ; \sigma _ { 13 } = 2 \times 10 ^ { - 24 } \mathrm { m } ^ { 2 } ; \tau _ { 21 } = 5$ ns; $n _ { T } = 1 \times 10 ^ { 24 } \mathrm { m } ^ { - 3 } ; \lambda _ { 13 } = 514 \mathrm { nm }$; $\lambda _ { 12 } = 600 \mathrm { nm } .$


[Pis]

## 10. Pista

[Moon]

[Sol]

## 10. Solución

[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 11. Considera dos sistemas láser, uno de 3 niveles y otro de 4 niveles. La sección eficaz de absorción a 514 nm para la transición de bombeo es $\sigma _ { b } = 5 \times 10 ^ { - 18 } \mathrm { m } ^ { 2 } ,$ la densidad de centros $n = 1 \times 10 ^ { 22 } \mathrm { m } ^ { - 3 } .$ Emiten a 600$\mathrm { nm }$ con una sección eficaz de fluorescencia $\sigma _ { 21 } = 2 \times 10 ^ { - 18 } \mathrm { m } ^ { 2 }$ y tiempo de vida $\tau = 5$ ns. Ambos medios tienen indice de refracción $n = 1.5$ y están en un resonador de reflectividad $\mathrm { R } = 0.95$ y $\mathrm { L } = 5 \mathrm { cm }$ .
### a) Calcular la inversión de población umbral y la intensidad de bombeo umbral para cada caso.
### b) Calcular la población en los niveles láser en el umbral.

[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 12. En la figura se muestra un esquema típico de 3 niveles no degenerado. Dicho sistema se bombea ópticamente entre los niveles 1 y 3 con una intensidad $I _ { b }$ de frecuencia $v _ { b } .$ La sección eficaz de absorción para el bombeo es $\sigma _ { b } ,$ y la densidad de dopado es $n _ { \mathrm { T } }$ . La transición 32 se considera infinitamente rápida, $\tau _ { 21 }$ es el tiempo de vida del nivel láser superior y despreciamos las transiciones estimuladas entre 1 y 2 . Calcular:
### a) Las poblaciones $n _ { 1 } ( t )$ y $n _ { 2 } ( t )$ si el bombeo empieza en $t = 0$
### b) El instante en que $n _ { 1 } = n _ { 2 }$
### c) El valor mínimo de $I_b$ para que se puedan igualar $n _ { 1 }$ y $\mathrm { n } _ { 2 }$ en algún instante.

![Niveles12](https://lh3.googleusercontent.com/FsVbwTFYtr-lhNkKGUMAQo-yrmpnRoZdwLevYYvP4Besh2-FmX1a45s4ltGn9N7aIxju2UmH1Cae)

[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 13. Una varilla de Nd:YAG (láser de 4 niveles) de 5$\mathrm { mm }$ de diámetro, 5$\mathrm { cm }$ de largo, un dopado de iones de Nd de $n _ { \mathrm { T } } = 1.38 \times 10 ^ { 20 } \mathrm { cm } ^ { - 3 }$ y tiempo de vida $\tau = 230$ us, emite a 1064 nm cuando se bombea con una lámpara de Xe (emisión a 940$\mathrm { nm }$ en promedio). La energía de bombeo umbral medida en cierta cavidad láser es de $\mathrm { E } _ { \mathrm { u } } = 3.4 \mathrm { J }$ . Asumamos que la eficiencia de bombeo global es 3.5$\%$ y que la potencia emitida por la lámpara dura $100 \mu s$ y es constante en el tiempo.
### a) Calcular el ritmo de bombeo umbral R .
### b) Calcular la inversión de población umbral utilizando la ecuación de balance que incluye el ritmo de bombeo y el decaimiento espontáneo si el umbral se alcanza a los 100$\mu s$.
### c) Si la duración del flash es $300 \mu s$, y sigue siendo constante en el tiempo, calcular el nuevo ritmo de bombeo y la energia de bombeo para llegar al umbral a los $300 \mu s$.


[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 14. Un láser de YAG:Nd es bombeado transversalmente de manera aproximadamente homogénea con láseres de diodo en la longitud de onda $\lambda_{b}=800 \mathrm{nm},$ en la cual la sección eficaz de absorción de los iones $\mathrm{Nd}^{3+}$ es $\sigma_{\mathrm{b}}=3 \times 10^{-20} \mathrm{cm}^{2}$ y es bombeado con una intensidad $\mathrm{I}_{\mathrm{b}}=50 \mathrm{W} \mathrm{cm}^{-2} .$ El láser de YAG:Nd funciona con un esquema de 4 niveles, el tiempo de vida radiativo del nivel superior es $\tau_{21}=230 \mu$ s, la sección eficaz de emisión estimulada es $\sigma_{21}=2.8 \times 10^{-19} \mathrm{cm}^{2},$ la longitud de onda de emisión $\lambda_{21}=1.064 \mu \mathrm{m}$ y el indice de refracción del cristal a esa longitud de onda es $1.85 .$ El medio está dopado con una densidad de iones $n_{T}=1.4 \times 10^{20} \mathrm{cm}^{-3} \mathrm{y}$ tiene una longitud de $5\mathrm{cm}$. Calcular:
### a) La inversión de población $n_{i}$ producida por el bombeo.
### b) La ganancia en pequeña señal $\alpha_{0} \mathrm{L}$ .
### c) La intensidad de saturación $I_{0 .} $
### d) La intensidad de salida si se inyecta radiación de 1064 nm de intensidad 1 $\mathrm{W} / \mathrm{cm}^{2}$

[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 15. Un sistema láser de 3 niveles está operando sin pérdidas internas. Considera un resonador de longitud L y reflectividades $R_{1}=1, R_{2}=1$ y que el medio láser ocupa todo el resonador.
### a) Calcular cuál debe ser la intensidad de saturación para que pueda lasear con una potencia de bombeo $\mathrm{P}$ dada proporcionando una intensidad de salida deseada $\mathrm{I}_{52}$ .
### b) Calcular también cuál será la potencia de bombeo en el umbral.

[Sol]



[Moon]




---
>.
> Intervalo Publicitario
>.
---


## 16. Considera un láser de YAG:Nd con los datos del problema $14 . $
### a) Calcula la proporción de ruido que amplificaria una varilla de 2.5 $\mathrm{cm}$ respecto a la de 5 $\mathrm{cm}$.
### b) Si ahora el medio de longitud $\mathrm{L}=5 \mathrm{cm}$ se encuentra dentro de un resonador de longitud $1=10 \mathrm{cm}$ y reflectividades $\mathrm{R}_{1}=1, \mathrm{R}_{2}=0.9$ y tiene pérdidas internas $\alpha_{i} L=0.02$. Calcular cuál será la intensidad máxima de salida si se bombea con un pulso de forma gaussiana $P(t)=P_{0} e^{-\left(\frac{t-t_{0}}{\Delta t}\right)^{2}}, \operatorname{con} P_{0}=2 P_{\mathrm{u}} \quad \mathrm{y} \Delta \mathrm{t}=1 \mathrm{ms}, t_{0}=5 \mathrm{ms}$. ¿A qué tiempo se alcanza ese máximo?

[Sol]



[Moon]

---
---
