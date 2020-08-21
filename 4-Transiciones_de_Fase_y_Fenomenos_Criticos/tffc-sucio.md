# Transiciones de fase

# DIA 1

## Conceptos generales

H_2O Liquido puede pasar a hielo o vapor

Pero son las mismas moléculas interaccionando con el mismo potencial.
Las propiedades microscopicas no cambian, sino el estado maccroscopico asiciado.

Según la física estadística el hamiltoniano del sistema no cambia.
Luego el hamiltoniano no da información del estado de agregación.

>Anomalías del agua:
>:	En fase sólida es más denso que el líquido. [phyStackEx](https://physics.stackexchange.com/questions/72841/besides-water-which-substances-are-less-dense-as-solids-than-as-liquids) [quimstackEx](https://chemistry.stackexchange.com/questions/51278/are-there-any-other-elements-that-get-less-dense-in-their-solid-state)
>: La densidad no es directamente proporcional a T. Hay un máximo de 1000 kg/l en 4ºC.
>: En realidad hay muchos tipos de hielo.

___

Nuestro hamiltoniano será el normal:

$$H =  \sum^N \frac { p^2 } { 2m } + \frac {1}{2}\sum_{i =\neq j} V (|\overline{q}_i - \overline{q}_j |) $$

Si $i =\neq j$ añado el 1/2 para no repetir.

$$\dot{q}_i = \frac { \partial H } { \partial p_i } \quad \dot{p}_i = - \frac { \partial H } { \partial q_i }$$

Estas ecuaciones nos describirán los distintos estados de la materia.

Condiciones iniciales: Las energías y temperatura iniciales, el volumen, la gravedad, campos electromagnéticos...

La energía inicial será función de la temperatura inicial, el volumen, etc..

> q y p restringidas al volumen y demás CI.
____
¿Cómo será el potencial $V()$? En general:
: Parte atractiva
: Parte repulsiva
$$r_{ij} = |q_i -q_j| = r$$
![Potencial](https://lh3.googleusercontent.com/4pMmpzQAEHDSD93__LFeJPT88rvhVU7c_Q3ve13sKKi4PEaQMs0rcar9CYofFOMAPQ8oGUTyhsDB)

Si no hay parte atractiva no habrá transición de fase.

Los potenciales reales no son isótropos, dependen de la dirección además de la distancia:
P.ej: Agua, copos de nieve.

![Hielo no isotropo](https://lh3.googleusercontent.com/5NRane3Pq_ciFyXv7QSbwJ7GN2ezzyUYF_M9MMVLDf95fV39gPC0jyfjT-nYtbtvmkMZW1QVx2sy)

___
El hecho de que existan transiciones de fase no depende del potencial, son un fenómeno universal.

> Emergen leyes universales cuando expresamos la física en términos de **magnitudes adimensionales**.
> P.ej: Teoría de Debye de los sólidos está todo en función de variables adimensionales.

Veremos que hay tres tipos fundamentales de transiciones de fase.

En general se tratará de minimizar o maximizar la Energía, la Entropía o algún Potencial Termodinámico.

> Estudiaremos en particular el Hexafloruro de Azufre

___
## Fases del Agua

### Vapor

![enter image description here](https://lh3.googleusercontent.com/GZb0TZ-8Zr356ddLQjH2VloO2JE1_Qxz7B8za6MstnfyJdZormRICYaqYeLRbv2GQXPgFnXCZ1Pn =200x200)

-	Moléculas separadas. Distandia media $l$.
-	Densidad baja. $\rho \sim0.6 kg m^{-3} | 100º C, 1atm$
-	Baja P $\Rightarrow l$ grande (distancia intermolecular) respecto a $r_o$ (distancia del potencial.
-	 $l$ alta implica T alta que implica E alta
-	$l$ determinada (que no proporcional, sino caracterizada) por el volumen (escala $l^3$).
-	Movilidad alta ( fluidez )
![enter image description here](https://lh3.googleusercontent.com/q9tdaj-xPZVIEom31u4eLZURvPUsGNKRTbcEu91ZmSoTHemmbehRG9-vaDzPZssejD9iU4C1Tp_F)

### Líquido

-	Densidad más alta.
-	$l$ sigue siendo mayor o igual a $r_o$, pero ya no caracterizada por V.
-	Todavía hay alta movilidad.
-	Densidad alta
	-	$\rho \sim958 kg m^{-3} | 100º C, 1atm$
	-	$\rho \sim999 kg m^{-3} | 0º C, 1atm$
-	Aún hay atracción entre las moléculas.

### Sólido

-	En general no mucho más densos que los líquidos ( el agua es la excepción ).
-	No gran diferencia con el líquido en densidad
	-	$\rho \sim916 kg m^{-3} | 0º C, 1atm$
	-	En realidad, en general la densidad del agua es bastante más grande que la del hielo, comparando con otros elementos.
-	Mobilidad baja
-	Red cristalina: $l\approx r_o$
-	Pueden vibrar un poco.

![enter image description here](https://lh3.googleusercontent.com/G41ENygTpMF3TyrrWZimgikeAdvaDE2YGC58Q7WXd8b9libV4acj8saaLp4aJPh7rxsl437gjzXq)

## Describir las transiciones

-	$\rho$ es un buen parámetro para distinguir liquido de vapor pero no para sólido y líquido.
-	La movilidad es un buen parámetro para distinguir sólido y líquido pero no líquido y gas.
	-	Relacionado con cristalinidad
		-	Parámetro de órden
		-	Variación de la posición atómica

## ¿Pero cómo se produce la transicion de fase?

Cojo agua en fase vapor y la meto en una caja con un émbolo.

![Caja con piston](https://lh3.googleusercontent.com/z68ugxv8elx4mEavxFnehkwvxxwTZPxh1JkTcwTXFrHFyErnfdNnpbq1Xy6tmec9sSByhKEuJUlR)

> El agua es un mal ejemplo porque es rara y no puedo congelarla con un émbolo, pero lo normal es que si.

Recordemos: La presión es el parámetro conjugado del volumen, lo normal es que crezca.

Vamos apretando y apretando y la presión va subiendo y de repente PUF. Aparece una gotita de agua. Una región del espacio de repente tiene una densidad más alta que el resto.

![enter image description here](https://lh3.googleusercontent.com/bmA8E37YQXHDe_EyK-fOcxnR53CbJeUv7sNtwrUIEQ25hlIeZ0F8WlEIK8dQPacWg4nJYG9TwL4w)

Se ha formado una nueva fase. Una homogeneidad!

Coexisten las dos fases: en una las moléculas siguen separadas y en la otra se juntan mucho.

Lo curioso es que en el intervalo de volumen ( recordemos que estamos comprimiendo el pistón a velocidad constante ) en que aparece la gota, la presión permanece constante.

![enter image description here](https://lh3.googleusercontent.com/9u2Ov77h_0PxET1esJLxKZq5rVVvbrgQYeB0I0BppX8fosNmB50mcYbhqp5wPXCJLEouzEXGHlO4)
![enter image description here](https://lh3.googleusercontent.com/KpV3zCw7MtT_kCdGa4_t9n2YYpIy-iJOVeq0Z1R_DJF0hswvHFrzk2h7FdrMH7K_Mfb5HWnOlQtT)

Las densidades no cambian, y la presión tampoco. Pero seguimos comprimiendo.
WHAT IS HAPPENIN?

![DiagFasePiston](https://lh3.googleusercontent.com/xhucs3fm3SdU8VkADQRB2S2vtbVfWQFSgH19yzW-ea2gQYthn2l7BD92Pzo7apZ8qQxQ7jUoPIEm)

La cantidad de espacio ocupada por la fase líquida, su volumen, va aumentando. Sigue así hsata que llena todo el espacio y no queda vapor.
Entondes es cuando la presion vuelve a aumentar.

Si siguieramos así aparecería el sólido de la misma forma (en el agua no).

Veamos más a fondo el diagrama de fases ![DFasPist](https://lh3.googleusercontent.com/SUwPl2PqcX0cRZWCYUm0Jtd-JiQ9_jwEl7LalNuYQ3GVjtSzwYT9iqawC8Bp5C1U3fHYHkYfDSn5)

---
Podríamos hacer el experimento a otras temperaturas y veríamos que hay una $T_c$ a partir de la cual no hay discontinuidad en el diagrama de fases.
Tenemos una curva $p-\rho$ con un punto singular, en el que la pendiente se hace infinito, eso si. Pero la curva es contínua.

Esto se da en otros fenómenos también como en la condensación de Bose-Einstein.

---




# DIA 2

![enter image description here](https://lh3.googleusercontent.com/5HEGxeaW8_CeP9FWplXtwue844Gk8wEdtkXnbyz3_N_H4jr-HXne9Ju09sJgabxFUnKppcXqYUky)
___
Potencial macrocanónico
Pensión discontinua implicaNúmero de micro estados discontinuos
Primero derivada de omega discontinuaParámetro que describe la transiciónTeorema de texto primer ordenOrdeneVariableContinuasNomenclaturaContinuasPorque no hay contenido propiamente es difícil decir que ordenar estaQue orden estaPara los contenidos del diagramaLa discontinuidad del diagrama de fasesProviene de la diferencia entre los de niveles energíaVerga si el líquidoDel gasDel gas y del líquidoEn este caso estamos en constanteEn presión constanteEnergía es en tal píaCómo escribir la transición de faseQué parámetro de la describeRecibimos preferiblemente uno que cambió bastante de una fase otra
Parámetro de orden

Sigue siendo no analítico, pero tenemos una transición continua
Es el parámetro determinante para que ocurre la transición de fase

En este caso es escalar pero dependiendo de la transición vectorial tensorial

Función de onda a número complejo

Desde me definiremos conjunto de exponentes críticos
Existen muchas familias de estos definen clases de universalidad
Permiten agrupar las transiciones grandes familias

No tiene por que, pero la discontinuidad en el agua se va acortando
En la temperatura crítica desaparece

Puntos críticos muy especialEs el punto inicial para decir las clases de universidad los exponentes críticos etcéteraNo. Crítico el sistema sincroniza las moléculas auto simpatizanSin agitarSigue siendo no analítico, pero tenemos una transición continua

Curvas suaves pero las transicionesLo extraño es que la naturaleza ocurre la transición discontinuaEntre líquidos y vaporPorque Esencialmente son la misma fase

Estamos a temperatura constante

Campana donde el valsEstas ISO termas no pueden obtenerse de un hamiltoniano ideal

Gas ideal + Termino de interacción

Esto sí que escribe una transición de faseTenemos que para líquido vapor el potencial será atractivo

Transicion condensación de bosones es la única que ocurre con un hamiltoniano ideal

Movilidad

:	Derivada del órden cristalino

:	Liquido: Alta

:	Sólido: Baja $\rightarrow$ cristal de Debye

El parámetro de órden líquido sóolido es m: la viscosidad
Tensorial

En un sistema isótropo tiene dos partes

:	Cizalla
:	Volumen

Por ejemplo un flluido no newtoniano tiene más componentes.

Un cristal tiene baja entropía

Por ejemplo es invariante bajo traslaciones

Transición líqiudo solido

:	Desorden $\rightarrow$ Orden

:	Disminuye la entroía

:	El calor de transición es entrópico

A presión infinita también tenemos ruptura de simetría. No puede romperse a medias.

En el agua la curva se desvía hacia la derecha, por eso no se puede congelar agua aumentando la presión.

Hay muchos tipos de hielo, con sus propias transiciones de fase dentro de la fase sólida.

:	Aunque no se sabe bien cuantas hay. ¿Son estables, metaestables...?
:	Cada una tiene un parámetro cristalino diferente
:	¿Qué parámetro de órden distingue estas fases?
:	Diagramas de difracción de Von-Laue
:	Hay mucha simulación numérica en este campo. Hay un grupo en la facultad de quimicas.


#	Sistemas magnéticos

Modelo de Ising. Onsager

## Trransición ferromagnética

Tiene imanación permanente.

Gas de spines. Origen magnético, de momento orbital, de spin, da igual.

Orientación aleatoria
:	Imanación total = 0

![randm](https://lh3.googleusercontent.com/FEtcdmYBSjt5E7tj-mTfidj3TwrUOqgM6qWKFJcnoG4FsnFsd0YhkjgUEJOt9c2MeDEdfBn2cBRO "randm")

Orientación en cierto sentido
:	Imanación total $=\neq$ 0
:	Aportan un sentido
:	Se orienta uno, altera a los cercanos, alteran a los demás.
![sens](https://lh3.googleusercontent.com/ldQTvMsf3gkyOgVrASuVVB1TkdFWaAQRktbNvRaofh1q_0-Cz_eEpkpGRHt0H9Haimb5CKHtLqry "sens")

Hay un hamiltoniano ideal (que no produce transición de fase) que será el primero que veamos.
:	Magnetismo inducido por campo magnético externo

### Transición de fase paramagnético-ferromagnético

Ocurre si tenemos campo magnético cero pero imanación distinta de cero.
Se denomina imanación espontánea.

El hamiltoniano ideal no produce nunca esto. Sólo describe la interacción del sistema de espines con el campo externo. Describe un imán ferromagnético clásico o cuántico.

![](https://lh3.googleusercontent.com/tgQoGXkuz-3PXdfd80-sjvvBCjgh9gHFKzx6IY1QgcG1pia9-9tc1KixhF4l56N_3Kcxz7ZHWkLf)

![enter image description here](https://lh3.googleusercontent.com/6lP3g6Gy4-ohCV1Do9dyJpM8pb87cjWBh6r85B_XnGEN2LMq-kJ5tX_0wGhRVW7-_ns5EVERYTe8)

![enter image description here](https://lh3.googleusercontent.com/7UgJaf12UWlZdHyIQbH8d_DdQIydwdZ-tG_Xt0LRK526sIvbVF8LYKJ28eEVP3xEEoZoW7USPHLx)

Los espines se van paralelizando.

Fenómeno cooperativo.

Ferromagnético
Paramagnético
Diamagnético

El momento magnético total es un promedio sobre la colectividad correspondiente de todos los espines y por tanto, proporcional al número de partículas

![enter image description here](https://lh3.googleusercontent.com/PfT1RRyAqZRVkYAM9NzOnJt8A-k4sr9PY56bkBJbYYihhBwKP5tF7hPnQZxf5VClQwdS6y_47hov)

Vamos a resolverlo con el hamiltoniano ideal de todas formas:

$$M= n \mu_B \text{tanh}(\beta \mu_B B) \quad \beta = 1/(k_B T)$$

Si bajo la temperatura la pendiente crece.

Pero en el experimento no ocurre esto:
:	A muy altas T si.
:	A bajas T aparece un salto simétrico.
:	El salto es más grande para T menores.

![enter image description here](https://lh3.googleusercontent.com/WhdO7QJhsklwaBsKQEMztK1FuPqqOdduHMN4F8nsyBLk_82ML3SDQXOqwhH117PZqh6_nomQUcbq)

![enter image description here](https://lh3.googleusercontent.com/hQPmtR5K00jI4tFowKssNkg7Sdyj-f__7QiiK3cLpRX03qVGXwmkn--qqTwo0w6aWgy0wqwGIPkL)

 La discontinuidad está causado por.......

# Dia 3. J14F


Solo a altas temperaturas
:	$$M= n \mu_B \text{tanh}(\beta \mu_B B) \quad \beta = 1/(k_B T)$$

![Discontinuidad MB](https://lh3.googleusercontent.com/XwHjf7qCK1pct-0hW2zXgJeVosrx6pfT3rARqtNXsVBLnpCfbbvMqS-9LNJeXsLGH9z6xwfmSkpP)

![
M frente T
](https://lh3.googleusercontent.com/98XG5Qt0ub_Dc589OyedCtaA-BxhKk8fttgGey2Hb4UY8XbcJ-zqXSmuKi57-pT9QLcI0AtO-V-4)

$$M=<M> \pm \sigma = o(N) + o (\sqrt{N} = \alpha(1\pm 1/\sqrt{N}) = \alpha(N \pm \sqrt{N})$$

> Cuando N tiende a infinito el error es muy pequeño ($\sqrt{N} \rightarrow 0$)

50% probabilidades de que se imane positiva o negativamente.
Una vez adquiere una imanación, permanece en el tiem`p con esa imanación.

![
Imanacion permanente
](https://lh3.googleusercontent.com/svAos6xEywMUhIj68vixlVeeWqZZQfHsAuheR6NPxMJYZO7gcO-9yVGRmGUIGuHF_PzQ65-YuUtl)

![
Probabilidades imanación
](https://lh3.googleusercontent.com/cqYV-gsVuVFfwx5DlUJItFsoY48jV9Kb2bYAIF-Qzpvk4rtDopeRZxO8-NBtotgbYYJqxUK4Grl6)

EL espaio de fases de las trauectorias de las moleculas por tanto se "rompe" en dos.

![enter image description here](https://lh3.googleusercontent.com/uQmif7w4H3SDw5cBACwOOHI9PfdgjQchzLVM3GcCNg9XsaYYjejVA5sAyOHn9lbT2JIasqWYtLsz)

Además por simetría sabemos que las trayectorias de ambos subespacios son las mismas.

Cuando se produce una transición (pasar de un espacio de fases al otro) se produce una ruptura de simetría ( se rompe la isotropía)

P ej: Condensación de Bose Einstein:

![
](https://lh3.googleusercontent.com/0aLXWY26DR7iKHs6F6oivxeoUWx9GdbzCs6tDiPRoIz5UimkhcW9P6vyrhI4Olpe4FZOVwGha5ZM)

![
](https://lh3.googleusercontent.com/Cp5khuJzfaaCs124QJMKjcEVx4-Ore12CjE48psER3sz-TyCLAORcgfoXOFZ1npRgCGZYcU5_aKN)

## Cristales líquidos (Soft matter)

Moléculas alargadas, pej Butano

![
](https://lh3.googleusercontent.com/KdKBb9sWF4PzK3zWrG-05QOkex_01pYSgLezbC0ykm9J0KsIs8aahyX-TBFUhDyy2qlc48Lrdg8t)


Dos órdenes:
:	Traslacional: Lo lejos que están los centros de las moléculas unos de otros (líquido-sólido)
:	Orientacional

---
Muchas fases:
:	Fase sólida: Orden traslacional y orientacional
:	fase neumática: Orden orientacional pero no traslacional. $<\theta_i> \neq 0$
:	Fase smectica: Orden orientacional en capas
:	Fase fluida o isótropa: Sin orden traslacional ni orientacional

## Antiferromagnéticos

Ferromagnéticos:
$$\uparrow \uparrow  E_-; \quad \uparrow \downarrow  E_+; \quad E_- <E_+$$

Antiferromagnéticos

$$\uparrow \downarrow  E_-; \quad  \uparrow \uparrow E_+; \quad E_- > E_+$$


## Transición Paramagnético-Ferromagnético

Paramagnético
:	$M=0$ si $B=0$ y $M\neq 0$ si $B \neq 0$


Ferromagnético
:	$M\neq 0$ aunque $B = 0$
---

$$\mu_i = g \mu _ B S_ { z_i } \Rightarrow H_i = - \overline{\mu_i } \overline { B } ( r_i ) = - \overline{\mu_i } \overline { B_i }$$

Si el campo magnético lo orientamos en OZ:
$$ H_i = - \mu _ i B _ i $$

Cuando los espiness están alineados con $B_i$ la energía es menor.

Es decir, energéticamente están favorecidos los momentos magnéticos paralelos al campo.

Ahora veamos el hamiltoniano del sistema

### Campo externo $B_i$en interacción

$$ H_i = - \mu _ i B _ i  \Rightarrow H = \sum_i H_i = - \sum \mu _ i B \Rightarrow N = N\mu_B g \text{tanh}(\theta)$$

$$\theta = \frac { g \mu _ B B } { k _B T }$$

### Campo interno $B_j$

Producido por $\mu_j$.

$$ \overline {B}_i = \mu _ j f(|r_i - r_j | )$$

$$H_i = -\mu _ i \mu _ j f(|r_i - r_j | ) = -J_{ij} S_i S_j$$

### Hamiltoniano total

Cambio de escala $\mu_i \leftrightarrow S_i$

$$ H_i  =- g_L \mu_B B \sum_i S_i   -J \sum_{ij} S_i S_j $$



$$ H_i  =-  B S_i   -\sum_{j} J_{ij} S_i S_j $$


Donde $\sum_{ij} J_{ij} S_i S_j$ es la parte que produce el cambio de fase.

En el modelo de Ising se desprecian aquellos que no son vecinos próximos de $S_i$:


$$-\sum_{ij} J_{ij} S_i S_j = -J\sum_{<ij>} S_i S_j  $$

$$ \boxed { H = - B\sum_i S_i -\sum_{<i,j>} J_{ij} S_i S_j \approx  - B \sum_i S_i -J\sum_{<i,j>} S_i S_j } $$

# DIA 4. j21f

## Repaso

Los B y los J suelen ir con un factor 1/2 dentro.

Transición...
Imanación...
Energía no cambia

Normalmente, antes de coger B=0, se hace al revés!

$$-kT \frac {\partial \text{ln}Z(B)}{\partial B} \rightarrow lim(
)
a{}$$

## Transición líquido-vapor

## Aleaciones

## Ferromagnetismo

## Ising 1D

### Argumento de Peierls


# DIA 5. j28f

## 1D

Método de matriz de transferencia		<- Solución exacta

No hay transición de fase excepto $T_C=0$

Cambio de la energía libre en la transición orden - dominios magnéticos.

$$F_{orden}>F_{dominios}$$

$$E_{orden}=E_{dominios}$$

$$S_{orden}<S_{dominios}$$

Este argumento vale para 1, 2 y 3 vecinos.

## 2D

Método de matriz de transferencia		<- No funciona
(Aunque Onsager resuelve con matriz de transferencia infinita-dimensional)

Solución: TF en B=0:
