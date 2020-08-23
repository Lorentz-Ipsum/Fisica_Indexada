---
title: Enunciados
author: Lorentz Ipsum
date: 19 de agosto de 2020
print_background: true
export_on_save:
  html: true
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

---
# Enunciados de ejercicios de simetrías y grupos
[TOC]

---
# Ejercicios de clase del curso 2019-2020

---
## T2: Elementos generales


--------------------

        ████████╗    ██████╗
        ╚══██╔══╝    ╚════██╗
           ██║        █████╔╝
           ██║       ██╔═══╝
           ██║       ███████╗
           ╚═╝       ╚══════╝

---
### <span style="color:red">Ej 1.</span> Grupo cíclico

Probar que un grupo finito de orden n (primo) debe ser un grupo cíclico (generado por a).

$$
C_n=\lbrace a,a^2,...,a^{n-1},a^n=e\rbrace \cong Z_n
$$

---
### <span style="color:red">Ej 2.</span> Grupo cociente

Probar que $G=H_1\times H_2$ implica que $G/H_1\cong H_2$.

---
### <span style="color:red">Ej 3.</span> Isomorfismos

Construye un isomorfismo que demuestre que el grupo de reales positivos, con la regla de multiplicación de grupo dada por la suma usual de números, es decir $(\mathbb{R}^+, \cdot) \cong (\mathbb{R}, +)$


---
### <span style="color:red">Ej 4.</span> Grupos de órden 4

Probar que, salvo isomorfismos, solamente hay dos grupos diferentes de orden 4: el grupo cíclico $C_4$ y el grupo de reflexiones en el plano $V_4$ (también llamado grupo de Klein).

Demostrar también que el grupo de Klein es producto directo de $C_2$ consigo mismo.

---
### <span style="color:red">Ej 5.</span> Grupo diédrico

Consideremos el grupo diédrico $D_4$, que es el grupo de simetría de un cuadrado.
Si situamos el cuadrado en el plano $xy$, centrado en el origen de coordenadas y con sus lados paralelos a los ejes de coordenadas, entonces el grupo consiste en rotaciones en torno al centro y reflexiones con respecto a los ejes vertical, horizontal y diagonales de pendiente $\pm 1$.

Llamemos $e$ a la identidad, $g$ a la rotación de ángulo $\pi/2$ (en sentido antihorario) y $h$ a la reflexión con respecto a la diagonal $y = x$.

Demuestra que el grupo está generado por $g$ y $h$ y escribe su tabla de multiplicar.

---
## T3: Representaciones

--------------------

        ████████╗    ██████╗
        ╚══██╔══╝    ╚════██╗
           ██║        █████╔╝
           ██║        ╚═══██╗
           ██║       ██████╔╝
           ╚═╝       ╚═════╝

---
### <span style="color:red">Ej 1.</span> Representación sobre GL(n,C)

Dada una representación de un grupo sobre los complejos, los vectores de $\mathbb{C}$ que se transforman bajo la acción de D:

$$
D: \hspace{0.2cm} G \to GL(n,\mathbb{C})
$$

$$
\vec{x}\to \vec{x}'-D(g)\vec{x}
$$

Si consideramos funciones de $\mathbb{C}^n$ en $C$ tales como $f'(\vec{x})=f(\vec{x})$ tenemos que $f(D(g)\vec{x})=f(\vec{x})$ y concluimos que:

$$
f\longrightarrow f'
$$

$$
f'(\vec{x})=f(D^{-1}(g)\vec{x})[A]
$$

Demostrar que este mapa es un homeomorfismo en el espacio de funciones y que por tanto el conjunto de transformaciones [A] forman una representación del grupo sobre dicho espacio.

$$
\begin{array}{cc}
D: \hspace{0.2cm} \vec{x}\to \vec{x}'  \\
D': \hspace{0.2cm} f(\vec{x})\to f'(\vec{x})
\end{array} \hspace{2cm} \text{De forma que} \hspace{0.2cm} f'\equiv D'(f)
$$

---
### <span style="color:red">Ej 2.</span> Representación de S3

Consideramos la representación bidimensional irreducible de $S_3 \cong D_3$, denotada anteriormente por $D^{(2)}(S_3)$, y dos vectores en el espacio complejo de dos dimensiones de coordenadas $(x^1,y^1)$ y $(x^2,y^2)$ que se transforman independientemente bajo la acción de la representación D. Esta representación da lugar a una representación de dimensión 4 W($S_3$) dada por la envolvente lineal de los monomios $X^1x^1, x^1y^2,y^1x^2$ y $y^1y^2$.

Calcular las matrices de representación W(g) siendo g un elemento de $S_3$.

$$
f: \hspace{0.2cm} (x^1,x^2)\otimes (y^1,y^2) \to \mathbb{C}
$$

$$
\hspace{0cm} V_1 \hspace{0.5cm}\otimes \hspace{0.5cm} V_2
$$

Por ejemplo $\tau _3 \tau _1=\sigma _1$, $\sigma _1^{-1}=\sigma _2$, $\tau _1 \sigma _1=\tau _2$.


---
## T4:

--------------------

        ████████╗    ██╗  ██╗
        ╚══██╔══╝    ██║  ██║
           ██║       ███████║
           ██║       ╚════██║
           ██║            ██║
           ╚═╝            ╚═╝



---
## T5:

--------------------

        ████████╗    ███████╗
        ╚══██╔══╝    ██╔════╝
           ██║       ███████╗
           ██║       ╚════██║
           ██║       ███████║
           ╚═╝       ╚══════╝

---
## T6:

--------------------

        ████████╗     ██████╗
        ╚══██╔══╝    ██╔════╝
           ██║       ███████╗
           ██║       ██╔═══██╗
           ██║       ╚██████╔╝
           ╚═╝        ╚═════╝


---
## T7:

--------------------

        ████████╗    ███████╗
        ╚══██╔══╝    ╚════██║
           ██║           ██╔╝
           ██║          ██╔╝
           ██║          ██║
           ╚═╝          ╚═╝

---
```
    ___________       __                             ___.   .__
    \_   _____/ _____/  |________   ____   _________ \_ |__ |  |   ____   ______
     |    __)_ /    \   __\_  __ \_/ __ \ / ___\__  \ | __ \|  | _/ __ \ /  ___/
     |        \   |  \  |  |  | \/\  ___// /_/  > __ \| \_\ \  |_\  ___/ \___ \
    /_______  /___|  /__|  |__|    \___  >___  (____  /___  /____/\___  >____  >
            \/     \/                  \/_____/     \/    \/          \/     \/
```

---
# Entregables

---
## Curso 2019/2020

Tema de cada hoja:

> Hoja 1: Elementos generales de teoría de grupos
> Hoja 2: Representaciones de grupos
> Hoja 3: Grupos y álgebras de Lie y Rotaciones en $R^3$
> Hoja 4: Grupo de Lorentz

---
### <span style="color:red">Ej 1.1.</span> El grupo diédrico $D_4$

Consideremos el grupo diédrico $D_4$, que es el grupo de simetría de un cuadrado. Si situamos el cuadrado en el plano $x - y$, centrado en el origen de coordenadas y con sus lados paralelos a los ejes de coordenadas, entonces el grupo consiste en rotaciones en torno al centro y reflexiones con respecto a los ejes vertical, horizontal y diagonales de pendiente $\pm 1$. Llamemos $e$ a la identidad, $g$ a la rotación de ángulo $\pi/2$ (en sentido antihorario) y $h$ a la reflexión con respecto a la diagonal $y = x$. Entonces el grupo está generado por $g$ y $h$ de la siguiente manera

$$
D_4 = \{e, g, g^2, g^3, h, gh, g^2h, g^3h\}
$$

Con esta notación, tenemos que la reflexión con respecto al eje $x = 0$ es $gh$, la reflexión con respecto al eje $y = -x$ es $g^2 h$ y la reflexión con respecto al eje $y = -x$ es $g^3h$, mientras que obviamente $g^2$ es la rotación de ángulo $\pi$ en sentido antihorario, y $g^3$ es la rotación de ángulo $3\pi/2$ en sentido antihorario. La tabla de multiplicar del grupo es

$$
\begin{array}{lcclcccc}
e & g & g^{2} & g^{3} & h & g h & g^{2} h & g^{3} h \\
g & g^{2} & g^{3} & e & g h & g^{2} h & g^{3} h & h \\
g^{2} & g^{3} & e & g & g^{2} h & g^{3} h & h & g h \\
g^{3} & e & g & g^{2} & g^{3} h & h & g h & g^{2} h \\
h & g^{3} h & g^{2} h & g h & e & g^{3} & g^{2} & g \\
g h & h & g^{3} h & g^{2} h & g & e & g^{3} & g^{2} \\
g^{2} h & g h & h & g^{3} h & g^{2} & g & e & g^{3} \\
g^{3} h & g^{2} h & g h & h & g^{3} & g^{2} & g & e
\end{array}
$$

A partir de estos datos:

1. Construye las clases de conjugación de $D_4$.
2. Escribe todos los subgrupos de $D_4$, señala a qué grupos vistos en clase son isomorfos, y di cuáles de ellos son normales.
3. Identifica los grupos cociente, escribiendo sus elementos a partir de los cosets correspondientes, y diciendo a qué grupos vistos en clase son isomorfos.
4. Razona si $D_4$ es producto directo de dos de sus subgrupos.

---
### <span style="color:red">Ej 2.1.</span> Representación bidimensional irreducible de $S_3$

Consideremos la representación bidimensional irreducible de $S_3 \cong D_3$, que anteriormente denotamos como $D^{(2)}$, y que actúa sobre los vectores de $\mathbb{C}^2$ de coordenadas $(x, y)$. Esta representación da lugar a una representación $W(S_3)$ de dimensión 6 en el espacio funcional $V$ cuyos elementos son las funciones de la forma

(1)

$$
f(x, y) = ax2 + bxy + cy2 + dx + ey + h,
$$

donde $a, b, c, d, e, h$ son coeficientes complejos.

1. Calcula las matrices de representación $W(g), \forall g \in S_3$.
2. Identifica los subespacios de $V$ que son invariantes bajo $W(S_3)$, y reduce $W(S_3)$ en suma directa de representaciones irreducibles.

---
### <span style="color:red">Ej 3.1.</span> Eje de rotación y ángulo de giro

Calcular el eje de rotación y el ángulo de giro del siguiente elemento del grupo $SO(3)$:

$$
R=\frac{1}{9}\left(\begin{array}{rrr}
8 & 1 & -4 \\
-4 & 4 & -7 \\
1 & 8 & 4
\end{array}\right)
$$

### <span style="color:red">Ej 3.2.</span> Coeficientes de Clebsch-Gorban

Calcula los coeficientes de Clebsch-Gordan del producto directo (de representaciones irreducibles de $SU(2)$): $1 \otimes 1/2$.

### <span style="color:red">Ej 3.3.</span> Espacio vectorial de funciones escalares diferenciables

Considera el espacio vectorial de funciones escalares diferenciables $f(\vec{x})$ con $\vec{x} \in \mathbb{R}^3$.

Demuestra que, sobre este espacio, la representación de los generadores infinitesimales de SU(2) viene dada por $\vec{J} = -i \vec{x} \times \vec{\nabla}$, o equivalentemente $J_i = -i \epsilon_{ijk} x_j \frac{\partial}{\partial x_k}$.

Usando la actuación de estos $J_i$ sobre $f(\vec{x})$, comprueba además que estos generadores verifican el álgebra de $su(2)$: $[J_i, J_j] = i\epsilon_{ijk} J_k$, como debe ser.

### <span style="color:red">Ej 3.4.</span> Generadores infinitesimales de $SU(2)$

Sean los operadores $A_1$ y $A_2$ que verifican

$$
\left[J_{a}, A_{i}\right]=A_{j} \frac{\left[\sigma_{a}\right]_{j i}}{2}
$$

donde $J_a$ son los generadores infinitesimales de $SU(2)$ y $\sigma_a$ son las matrices de Pauli $(a = 1, 2, 3)$.

1. Demuestra que $A_1 = Q_{1 / 2}^{1 / 2}$ y que $A_2 = Q_{-1 / 2}^{1 / 2}$, es decir que Ai son las componentes de un operador tensorial irreducible que se transforma en la representación $1/2$ de $SU(2)$.
b) Conocido el elemento de matriz

$$
\left\langle\frac{3}{2},-\frac{1}{2}\left|A_{1}\right| 1,-1\right\rangle=B
$$

encuentra

$$
\left\langle\frac{3}{2},-\frac{3}{2}\left|A_{2}\right| 1,-1\right\rangle
$$

---
### <span style="color:red">Ej 4.1.</span>Transformaciones de Lorentz

Demuestra que cualquier transformación de Lorentz pura $L$ se pude obtener de combinar $L_3$ con una rotación $R\vec{n}$ que transforma el vector unitario en el eje z en el vector unitario genérico $\vec{n} = (n1, n2, n3)$, tal que $L = R_{\vec{n}} L_ 3 R^{-1}_{\vec{n}}$.

---
### <span style="color:red">Ej 4.2.</span> Homomorfismo entre SL(2,C) y el grupo de Lorentz ortocrono propio

Demuestra que la correspondencia entre $A \in SL(2, \mathbb{C})$ y $\Lambda \in \mathcal{L}^{\uparrow}_+$ dada por $\Lambda_\nu^\mu = \frac{1}{2} tr (\underline{\sigma}^\mu A \sigma_\nu A^{\dagger})$ es un homomorfismo.

---
### <span style="color:red">Ej 4.3.</span> Descomposición de las representaciones del grupo de Lorentz ortocrono propio

Demuestra que las bases de las representaciones irreducibles obtenidas en la descomposición

$$
D^{\left(\frac{1}{2}, \frac{1}{2}\right)} \otimes D^{\left(\frac{1}{2}, \frac{1}{2}\right)}=D^{(1,1)} \oplus D^{(1,0)} \oplus D^{(0,1)} \oplus D^{(0,0)}
$$

se corresponden respectivamente con un tensor simétrico sin traza, un tensor autodual, un tensor anti-autodual, y un escalar.

---
### <span style="color:red">Ej 4.4.</span> El grupo de Lorentz ortocrono propio sobre los espinores de Weyl

Se llama espinor de Weyl dextrógiro al campo $\psi_R(x)$ que bajo transformaciones del grupo de Lorentz ortocrono propio, $\Lambda: x^\mu \rightarrow(x^\mu)' = \Lambda^\mu_\nu x^\nu$, se transforma en la representación irreducible $(0, 1/2)$ de dicho grupo. Es decir, dada una transformación de Lorentz que conlleva una rotación de ángulo $\phi$ en torno al eje $\vec{n}$ y un boost en la dirección $\vec{u}$ de rapidez $\eta$, la ley de transformación de $\psi_R(x)$ es

$$
\psi_{R}^{\prime}\left(x^{\prime}\right)=e^{(i \phi \vec{n}-\eta \vec{u}) \frac{\vec{\sigma}^{*}}{2}} \psi_{R}(x)
$$

donde el asterisco denota conjugación compleja.
1. Calcula la representación de los generadores del grupo de Lorentz sobre $\psi_R$.
2. Si $\psi_R$ y $\chi_R$ son dos espinores de Weyl dextrógiros, ¿se transforma la combinación $v^{\mu}=\chi_{R}^{\dagger} {\sigma}^{\mu} \psi_{R}$ como un 4-vector?, ¿y $v^{\mu}=\chi_{R}^{\dagger} \underline{\sigma}^{\mu} \psi_{R}$?

---
## Curso 2018/2019

Tema de cada hoja:

> Hoja 1: Elementos generales de teoría de grupos
> Hoja 2: Representaciones de grupos
> Hoja 3: Grupos y álgebras de Lie y Rotaciones en $R^3$
> Hoja 4: Grupo de Lorentz

---
### <span style="color:red">Ej 1.1.</span> Matrices de Pauli

---
### <span style="color:red">Ej 2.1.</span> Representación bidimensional irreducible de $S_3$

---
### <span style="color:red">Ej 3.1.</span> Coeficientes de Clebsch-Gorban

Calcula los coeficientes de Clebsch-Gordan del producto directo (de representaciones irreducibles de $SU(2)$): $1 \otimes 1/2$.

---
### <span style="color:red">Ej 3.2.</span> Homomorfismo funciones multicomponente. $SO(3)$

---
### <span style="color:red">Ej 3.3.</span> Operadores tensoriales irreducibles. $SO(3)$

---
### <span style="color:red">Ej 3.4.</span> Representaciones de $SO(3)$

---
### <span style="color:red">Ej 3.5.</span> Representación 1/2 de $SU(2)$

---
### <span style="color:red">Ej 4.1.</span> Homomorfismo

---
### <span style="color:red">Ej 4.2.</span> Representaciones irreducibles

---
### <span style="color:red">Ej 4.3.</span> Algebra de Lie de $\mathcal{P}^{\uparrow}_+$

---
### <span style="color:red">Ej 4.4.</span> Transformaciones de Lorentz

---
```
    ___________
    \_   _____/__  ________    _____   ____   ____   ____   ______
     |    __)_\  \/  /\__  \  /     \_/ __ \ /    \_/ __ \ /  ___/
     |        \>    <  / __ \|  Y Y  \  ___/|   |  \  ___/ \___ \
    /_______  /__/\_ \(____  /__|_|  /\___  >___|  /\___  >____  >
            \/      \/     \/      \/     \/     \/     \/     \/
```

---
# Exámenes

---
## Diciembre 2019

---
### <span style="color:red">Ej 1.</span> Matrices de Pauli

---
### <span style="color:red">Ej 2.</span> Grupo de rotaciones del tetrahedro regular

---
### <span style="color:red">Ej 3.</span> Representación tridimensional de $S_3$

---
### <span style="color:red">Ej 4.</span> Representación de $SO(3)$ de espín $j$

---
### <span style="color:red">Ej 5.</span> Tensores autoduales en $\mathcal{L}^{\uparrow}_+$

---
## Enero 2019

---
### <span style="color:red">Ej 1.</span> Grupo diédrico $D_4$

Consideremos el grupo diédrico $D_4$, que es el grupo de simetría de un cuadrado. Si situamos el cuadrado en el plano $x - y$, centrado en el origen de coordenadas y con sus lados paralelos a los ejes de coordenadas, entonces el grupo consiste en rotaciones en torno al centro y reflexiones con respecto a los ejes vertical, horizontal y diagonales de pendiente $\pm 1$. Llamemos $e$ a la identidad, $g$ a la rotación de ángulo $\pi/2$ (en sentido antihorario) y $h$ a la reflexión con respecto a la diagonal $y = x$. Entonces el grupo está generado por $g$ y $h$ de la siguiente manera

$$
D_4 = \{e, g, g^2, g^3, h, gh, g^2h, g^3h\}
$$

De modo que su tabla de multiplicar es

$$
\begin{array}{lcclcccc}
e & g & g^{2} & g^{3} & h & g h & g^{2} h & g^{3} h \\
g & g^{2} & g^{3} & e & g h & g^{2} h & g^{3} h & h \\
g^{2} & g^{3} & e & g & g^{2} h & g^{3} h & h & g h \\
g^{3} & e & g & g^{2} & g^{3} h & h & g h & g^{2} h \\
h & g^{3} h & g^{2} h & g h & e & g^{3} & g^{2} & g \\
g h & h & g^{3} h & g^{2} h & g & e & g^{3} & g^{2} \\
g^{2} h & g h & h & g^{3} h & g^{2} & g & e & g^{3} \\
g^{3} h & g^{2} h & g h & h & g^{3} & g^{2} & g & e
\end{array}
$$

Usando la notación anterior para los elementos de $D_4$:

1. Di qué elemento se corresponde con la reflexión respecto

---
### <span style="color:red">Ej 2.</span> Representaciones de $D_4$

---
### <span style="color:red">Ej 3.</span> Isospín

---
### <span style="color:red">Ej 4.</span> Espinor de Weyl