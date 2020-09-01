---
title: Enunciados
author: Lorentz Ipsum
date: 19 de agosto de 2020
print_background: true
toc: true
export_on_save:
  html: true
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

---
# Enunciados de ejercicios de simetrías y grupos
[TOC]

---
Para identificar de forma única cada problema voy a probar usando un código de 6 dígitos hexadecimales:

1. Indica si el problema es dicho en clase (C), de una hoja de problemas (P), o si aparece en entregables (H) o exámenes (X).
2. Indica el tema al que pertenece el problema.
3. Si tiene número en la hoja en que aparezca, aparecerá aquí.
2. En qué parte del tema aparece (la subsección).
3. Para indicar si hay más problemas en dicha sección. Los que aparezcan primero van antes. En caso de duda, da igual el órden.
4. Será una letra de la A a la C. Indica la dificultad del problema. A = Más duro.

Los problemas marcados (los de exámen o entregable) se identifirarán alternativamente por un codigo especial: X ó H segun el caso, el año, el número de hoja o exámen (1 = Ordinaria, 2 = Recuperación) y el número de problema.

Ejemplos:

```
211B
5.4.3.D.X = X.19.1.4
```

---
# Ejercicios de clase del curso 2019-2020

---
## T2: Elementos generales

--------------------
```
    ████████╗    ██████╗
    ╚══██╔══╝    ╚════██╗
       ██║        █████╔╝
       ██║       ██╔═══╝
       ██║       ███████╗
       ╚═╝       ╚══════╝
```

---
### <span style="color:red">Ej 1.</span> Isomorfismos

Construye un isomorfismo que demuestre que el grupo de reales positivos, con la regla de multiplicación de grupo dada por la suma usual de números, es decir $(\mathbb{R}^+, \cdot) \cong (\mathbb{R}, +)$


---
### <span style="color:red">Ej 2.</span> Grupos de órden 4

Probar que, salvo isomorfismos, solamente hay dos grupos diferentes de orden 4: el grupo cíclico $C_4$ y el grupo de reflexiones en el plano $V_4$ (también llamado grupo de Klein).

Demostrar también que el grupo de Klein es producto directo de $C_2$ consigo mismo.

---
### <span style="color:red">Ej 3.</span> Grupo diédrico

Consideremos el grupo diédrico $D_4$, que es el grupo de simetría de un cuadrado.
Si situamos el cuadrado en el plano $xy$, centrado en el origen de coordenadas y con sus lados paralelos a los ejes de coordenadas, entonces el grupo consiste en rotaciones en torno al centro y reflexiones con respecto a los ejes vertical, horizontal y diagonales de pendiente $\pm 1$.

Llamemos $e$ a la identidad, $g$ a la rotación de ángulo $\pi/2$ (en sentido antihorario) y $h$ a la reflexión con respecto a la diagonal $y = x$.

Demuestra que el grupo está generado por $g$ y $h$ y escribe su tabla de multiplicar.

---
### <span style="color:red">Ej (S)</span> Grupo cíclico

Probar que un grupo finito de orden n (primo) debe ser un grupo cíclico (generado por a).

$$
C_n=\lbrace a,a^2,...,a^{n-1},a^n=e\rbrace \cong Z_n
$$

---
### <span style="color:red">Ej (S)</span> Grupo cociente

Probar que $G=H_1\times H_2$ implica que $G/H_1\cong H_2$.

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
f\xrightarrow{g} f'
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
### <span style="color:red">Ej (S)</span> Representaciones

Sea $G=S^1 \cong U(1)$ demostrar que la aplicación

$$
\begin{array}{cc}
D: S^1 \to GL(2,\mathbb{C})  \\
e^{i\theta} \to D(e^{i\theta})
\end{array}
$$

con $D(e^{i\theta})= \left (\begin{array}{cc}
cos \theta   & -sen \theta  \\
sen \theta   & cos \theta
\end{array} \right )=R( \theta), \hspace{0.1cm} \theta \in \mathbb{R}$ es una representación de $S^1$.

Hacer lo mismo para:

$$
\begin{array}{cc}
D: S^1 \to GL(3,\mathbb{C})  \\
e^{i\theta} \to D(e^{i\theta})
\end{array}
$$

con $D(e^{i\theta})= \left (\begin{array}{ccc}
cos \theta   & -sen \theta  & 0\\
sen \theta   & cos \theta & 0 \\
0 & 0 & 1
\end{array} \right )=R( \theta), \hspace{0.1cm} \theta \in \mathbb{R}$.

---
### <span style="color:red">Ej (S)</span> Representación no trivial de $S_3 / A_3$

Construir una representación no trivial de $S_3 / A_3$ y demuestra que es una representación no fiel de $S_3$.

---
### <span style="color:red">Ej (S)</span> Representación reducible de $G=(\mathbb{C},+)$

Sea $G=(\mathbb{C},+)$ y sea la aplicación

$$
D(z)=\left ( \begin{array}{cc}
1 & z \\
0 & 1
\end{array} \right ) \hspace{0.1cm} \forall z\in \mathbb{C}
$$

Demostrar que D es una representación reducible de G. ¿Es descomponible?

---
### <span style="color:red">Ej (S)</span> Representaciones irreducibles de $C_3$

Consideremos el grupo cíclico de tres elementos $C_3$ cuya tabla de multiplicar es:

$$
\begin{array}{ c | c c c}
& e & a & a^2  \\
\hline
e & e & a & a^2 \\
a & a & a^2 & e  \\
a^2 & a^2 & e & a
\end{array}
$$


Una representación de este grupo es $D: C_3\to GL(3, \mathbb{C})$:

$$
D(e)=\left (\begin{array}{ccc}
1 & 0 & 0  \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array} \right ) \hspace{1.5cm} D(a)=\left (\begin{array}{ccc}
0 & 0 & 1  \\
1 & 0 & 0 \\
0 & 1 & 0
\end{array} \right ) \hspace{1.5cm} D(a^2)=\left (\begin{array}{ccc}
0 & 1 & 0  \\
0 & 0 & 1 \\
1 & 0 & 0
\end{array} \right )
$$

Como no es unidimensional y el grupo es abeliano ha de ser reducible, además por los teoremas de Maschke y los lemas de Schur podemos afirmar que es completamente reducible. Es decir, se puede descomponer en la suma directa de 3 representaciones irreducibles unidimensionales y unitarias.

Demostrarlo.

---
### <span style="color:red">Ej (S)</span> Representación de $S^1$

Dada la representación del grupo bidimensional

$$
\begin{array}{cc}
D: S^1 \to DL(2, \mathbb{C})  \\
e^{i\Theta}\to D(e^{i\Theta})= \left (\begin{array}{cc}
cos \theta  & -sen \theta  \\
sen \theta  & cos \theta
\end{array}\right )
\end{array}
$$

encontrar un operador A que conmute con $\mathbb{R}(\theta)$ y que no sea la identidad (tal A existe pues D no es irreducible en $V=\mathbb{C}$). Encontrar los subespacios de $\mathbb{C}^2$ invariantes bajo D y descomponer D en suma directa de representaciones irreducibles.

---
### <span style="color:red">Ej (S)</span>

Da una representación no trivial de $S_3/A_3$ y demuestra que es una representación no fiel de $S_3$

---
### <span style="color:red">Ej (S)</span>

Sea $G = (\mathbb{C}, +)$, y sea la aplicación $D(z)= \begin{pmatrix} 1&z \\ 0 &1 \end{pmatrix}, \forall z\in \mathbb{C}$.

Demostrar que D es una representacion reducible de G. ¿Es descomponible?

---
### <span style="color:red">Ej</span> Suma directa de representaciones irreducibles

Dada la representación irreducible unitaria $D^{(2)}$ de $S_3$, construye $D^{(2)}\otimes D^{(2)}$ y descomponlas en suma directa de representaciones irreducibles (recordar que eran: la identidad, $D^{(0)}$; la paridad $D^{(1)}$ y la que teniamos que contruir para el ejercicio $D^{(2)}$).

$$
D^{(2)}\otimes D^{(2)}=m_{(0)}D^{(0)}+m_{(1)}D^{(1)}+m_{(2)}D^{(2)}
$$

---
### <span style="color:red">Ej (S)</span>

Dada la representación

$$
\begin{array}{cc}
D: S^1 \to GL(2,\mathbb{C})  \\
e^{i\theta} \to D(e^{i\theta})
\end{array}
$$

con $D(e^{i\theta})= \left (\begin{array}{cc}
cos \theta   & -sen \theta  \\
sen \theta   & cos \theta
\end{array} \right )=R( \theta), \hspace{0.1cm} \theta \in \mathbb{R}$ , encuentra un ooperador A que conmuta con $R( \theta) \forall \theta \in \mathbb{R}$, y que no sea múltiplo de la identidad. Tal A existe porque D no es reducible en $V=\mathbb{C}$.

Encuentra los subespacios de $\mathbb{C}^2$ invariantes bajo D, y descompon D en suma directa de representaciones irreducibles.

---
### <span style="color:red">Ej (S)</span> Tabla de caracteres de $S_3$

Construir la tabla de caracteres de $S_3$.

---
### <span style="color:red">Ej</span> Representación bidimensional irreducible y unitaria

Construir la representación bidimensional irreducible y unitaria de $S_3$.

---
### <span style="color:red">Ej (S)</span> Coeficientes de CG

Calcular los coeficientes de CG para $D^{(2)}\otimes D^{(2)}$

---
## T4: Grupos y álgebras de Lie

--------------------

    ████████╗    ██╗  ██╗
    ╚══██╔══╝    ██║  ██║
       ██║       ███████║
       ██║       ╚════██║
       ██║            ██║
       ╚═╝            ╚═╝

---
### <span style="color:red">Ej (S)</span> Compacidad

Decir cuáles de estos grupos son compactos y cuáles no.

---
### <span style="color:red">Ej (S)</span> Conexidad de O(n) y U(n)

¿Son O(n) y U(n) grupos conexos?

---
### <span style="color:red">Ej (S)</span> Conexidad de SO(2) y SU(2)

¿Son SO(2)$\simeq$ U(1) y SU(2) simplemente conexos?

---
### <span style="color:red">Ej (S)</span> Compacidad de SO(1,1)

Justificar por qué el grupo SO(1,1) no es compacto

Pista: SO(1,1) es isomorfo a los reales con la operación de suma.

---
### <span style="color:red">Ej (S)</span> Recubridor universal de U(1)

Acabamos de ver que SO(2) $\simeq$ U(1) $\simeq S^1$  no es simplemente conexo. ¿Qué grupo es su recubridor universal? Buscar el grupo normal de G (H) tal que $S^1 \simeq G/H$ (el grupo cociente es el círculo).

Pista: la dimensión de $S^1$ es 1. Su recubridor universal tendrá también dimensión 1.

---
### <span style="color:red">Ej (S)</span> Álgebra de Lie $so(2)$

Caracteriza el álgebra de Lie so(2) de SO(2), busca una base y muestra que los elementos de SO(2) se obtienen por exponenciación del álgebra.

---
## T5: Rotaciones en $R^3$: Los grupos $SO(3)$ y $SU(2)$

--------------------

    ████████╗    ███████╗
    ╚══██╔══╝    ██╔════╝
       ██║       ███████╗
       ██║       ╚════██║
       ██║       ███████║
       ╚═╝       ╚══════╝

---
### <span style="color:red">Ej (S)</span> Matriz de rotación y ángulos de Euler

Obtener la expresión explícita de la matriz $R(\alpha , \beta , \gamma)$ y escribe los ángulos $\phi, \theta , \psi$ como funciones de $\alpha , \beta , \gamma$.

---
### <span style="color:red">Ej (S)</span> Matrices de rotación

Comprobar que $R_{\vec{n}}(\omega)R_{\vec{x}}(\psi)R^{-1}_{\vec{n}}(\omega) = R_{\vec{x}'}(\psi)$ con $\vec{x}' = R_{\vec{n}}(\omega)\vec{x}$

---
### <span style="color:red">Ej (S)</span> Correspondencia entre SO(3) y SU(2)

Demostrar esta igualdad: $cos \frac{\psi}{2} \mathbb{I} -isen \frac{\psi}{2} \vec{n} \vec{\sigma} = e^{-i\frac{\psi}{2}\vec{n}\vec{\sigma}}$

---
### <span style="color:red">Ej (S)</span> Matrices unitarias

Demostrar $X' = U_{\vec{n}}(\psi)X U^{+}_{\vec{n}}(\psi) = [cos\psi\vec{x}  + (1-cos\psi)(\vec{x} \cdot \vec{n})\vec{n} + sin\psi (\vec{x} \times \vec{\sigma})] \cdot \vec{\sigma}$ con $X = \vec{x} \cdot \vec{\sigma}$

---
### <span style="color:red">Ej (S)</span>

Demostrar $[\vec{J}^2 , J_z] = [\vec{J}^2 , J_{\pm}]=0$ sabiendo que $[J_z , J_{\pm}] = \pm J_{\pm} ,\quad [J_+ , J_-] = 2J_z,\quad \vec{J}^2= J_z^2 + J_z + J_- J_+$

---
### <span style="color:red">Ej (S)</span>

Comprobar que para $j = 1/2$, tenemos que $J_3 = \left (\begin{array}{cc}
1/2   & 0  \\
0   & -1/2
\end{array} \right )$, $J_+ = \left (\begin{array}{cc}
0   & 1  \\
0   & 0
\end{array} \right )$, $J_+ = \left (\begin{array}{cc}
0   & 0  \\
1  & 0
\end{array} \right )$ en la base $\left\{ |1/2, -1/2\rangle  = \begin{pmatrix}0 \\ 1 \end{pmatrix}, | 1/2, 1/2 \rangle = \begin{pmatrix}1 \\ 0 \end{pmatrix} \right\}$

---
### <span style="color:red">Ej (S)</span>

Demostrar que $\vec{J} = i \vec{x}\times \vec{\nabla}$, o, de manera equivalente, $J_i = -i \epsilon_{ijk} x_j \partial / \partial x_k$, da una representación del álgebra de $su(2)$ sobre el espacio vectorial formado por funciones escalares diferenciables $f(x)$ con $\vec{x} \in \mathbb{R}^3$.

---
### <span style="color:red">Ej (S)</span>

Sean $\xi$ y $\eta$ dos variabldes complejas sobre las que matrices $U=\begin{pmatrix}a &c\\b&d \end{pmatrix} \in SU(2)$ actuan de acuerdo con $\xi'=a\xi + c\eta$, $\eta' = b\xi + d\eta$.

En otras palabras, $\begin{pmatrix}\xi \\ \eta \end{pmatrix}^{\prime} = U \begin{pmatrix}\xi \\ \eta \end{pmatrix}$, donde $\begin{pmatrix}\xi \\ \eta \end{pmatrix}$ son vetores de la representación de espín $j=2$.

Consideremos ahora los polinomios homogéneos de grado $2j$ en las variables $\xi$ y $\eta$, para los que una base está formada por los $(2j+1)$ polinomios

$$
P_{jm} = \frac{\xi^{j+m}\eta^{j-m}}{\sqrt{(j+m)!(j-m)!}} \qquad m = -j,...,j
$$

Este espacio vectorial da lugar a una realización explícita de la representación de espín $j$ de $SU(2)$, es decir:

$$
P_{jm}(\xi',\eta') = \sum_{m'} P_{jm'}(\xi,\eta)D_{mm'}^j(U)
$$

Obtén de aquí la expresión explícita de $D_{mm'}^j(U)$ con $U=\begin{pmatrix}a &c\\b&d \end{pmatrix}$.

---
### <span style="color:red">Ej (S)</span>

Un tensor $T$ se transforma bajo SO(3) según

$$
T \xrightarrow{R} T' = RTR^{-1}
$$

Si $\{T_{ij}: i,j=1,2,3\}$ son las componentes de un tensor de rando 2, demuestra que:

1. $Tr(T) = \delta^{ij}T_{ij}$ es un escalar (no se transforma bajo SO(3)).
2. $\hat{T} _{ij} = \frac{T _{ij} \mp T_{ji}}{2}$ se mantiene antisimétrico bajo una rotación SU(3) simétrica.
3. $\hat{T}_k ) \epsilon_{kij} T_{ij}/2$ se transforma como un vector. ($\hat{T} =*T$ Hodge Dual)
4. Las 5 componentes independientes de $\tilde{T} _{ij} = \frac{T _{ij} \mp T_{ji}}{2}$ se transforman en la representación $D^2$ bajo rotaciones si $\delta^{ij}\tilde{T}_{ij} = 0$. En otras palabras: un tensor simétrico y sin traza, se transforma bajo $SO(3)$ de acuerdo con la representación de espín $j=2$.

---
### <span style="color:red">Ej (S)</span>

Calcular $d^{1/2}(\beta)$ y $D^{1/2}(\alpha, \beta,\gamma)$.

---
### <span style="color:red">Ej (S)</span> Coeficientes de CG

Calcular la descomposición y coeficientes de CG de $\frac{1}{2}\otimes \frac{1}{2}$.

---
## T6: El grupo de Lorentz

--------------------
```
    ████████╗     ██████╗
    ╚══██╔══╝    ██╔════╝
       ██║       ███████╗
       ██║       ██╔═══██╗
       ██║       ╚██████╔╝
       ╚═╝        ╚═════╝
```

---
### <span style="color:red">Ej</span> Grupo de Lorentz

Demuestra que el subgrupo de Lorentz ortocrono propio no solo es subgrupo si no que es subgrupo normal.

---
## T7: El grupo de Poincaré

--------------------

    ████████╗    ███████╗
    ╚══██╔══╝    ╚════██║
       ██║           ██╔╝
       ██║          ██╔╝
       ██║          ██║
       ╚═╝          ╚═╝

---
# Entregables

---
```
'||''''|            ||                                 '||     '||`
 ||   .             ||                                  ||      ||
 ||'''|  `||''|,  ''||''  '||''| .|''|, .|''|,  '''|.   ||''|,  ||  .|''|, (''''
 ||       ||  ||    ||     ||    ||..|| ||  || .|''||   ||  ||  ||  ||..||  `'')
.||....| .||  ||.   `|..' .||.   `|...  `|..|| `|..||. .||..|' .||. `|...  `...'
                                            ||
                                         `..|'
```

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
f(x, y) = ax^2 + bxy + cy^2 + dx + ey + h,
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

---
### <span style="color:red">Ej 3.2.</span> Coeficientes de Clebsch-Gorban

Calcula los coeficientes de Clebsch-Gordan del producto directo (de representaciones irreducibles de $SU(2)$): $1 \otimes 1/2$.

---
### <span style="color:red">Ej 3.3.</span> Espacio vectorial de funciones escalares diferenciables

Considera el espacio vectorial de funciones escalares diferenciables $f(\vec{x})$ con $\vec{x} \in \mathbb{R}^3$.

Demuestra que, sobre este espacio, la representación de los generadores infinitesimales de SU(2) viene dada por $\vec{J} = -i \vec{x} \times \vec{\nabla}$, o equivalentemente $J_i = -i \epsilon_{ijk} x_j \frac{\partial}{\partial x_k}$.

Usando la actuación de estos $J_i$ sobre $f(\vec{x})$, comprueba además que estos generadores verifican el álgebra de $su(2)$: $[J_i, J_j] = i\epsilon_{ijk} J_k$, como debe ser.

---
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

Las matrices de Pauli se definen de la forma:

$$
\sigma_{1}=\left(\begin{array}{cc}
0 & 1 \\
1 & 0
\end{array}\right) \quad, \quad \sigma_{2}=\left(\begin{array}{cc}
0 & -i \\
i & 0
\end{array}\right) \quad, \quad \sigma_{3}=\left(\begin{array}{cc}
1 & 0 \\
0 & -1
\end{array}\right)
$$

1. Demuestra que todos los posibles productos generados por $\sigma_1$ y $\sigma_2$ forman un grupo G de orden 8, y escribe la tabla de multiplicar de dicho grupo.
2. Di de qué orden es cada elemento de G (llamamos orden de un elemento al orden del subgrupo cíclico que genera
dicho elemento).
3. Construye las clases de conjugación de G.
4. Escribe los subgrupos normales de G y sus correspondientes grupos cociente.
5. Demuestra que G es isomorfo al grupo de simetrías del cuadrado, el grupo dihédrico $D_4$.

---
### <span style="color:red">Ej 2.1.</span> Representación bidimensional irreducible de $S_3$

Consideremos la representación bidimensional irreducible de $S_{3} \cong D_{3}$, que anteriormente denotamos como $D^{(3)}$, y dos vectores de $\mathbb{C}^{2}$ de coordenadas $\left(x^{1}, y^{1}\right)$ y $\left(x^{2}, y^{2}\right)$ que se transforman independientemente bajo $D^{(3)}\left(S_{3}\right)$.
Esta representación da lugar a una representación de dimensión 4 en el espacio funcional $V$ dado por la envolvente lineal de los monomios $\left|x^{1} x^{2}\right\rangle,\left|x^{1} y^{2}\right\rangle,\left|y^{1} x^{2}\right\rangle,\left|y^{1} y^{2}\right\rangle .$ Llamemos a esta representación $W\left(S_{3}\right)$

1. Calcula las matrices de representación $W(g), \forall g \in S_{3},$ y demuestra que $W\left(S_{3}\right)=D^{(3)}\left(S_{3}\right) \otimes D^{(3)}\left(S_{3}\right)$.
2. Buscando los subespacios de $V$ que son invariantes bajo $W\left(S_{3}\right)$, reduce $W\left(S_{3}\right)$ en suma directa de representaciones irreducibles.
3. Dada la anterior descomposición de Clebsch-Gordan de $D^{(3)}\left(S_{3}\right) \otimes D^{(3)}\left(S_{3}\right),$ evalua los coeficientes de Clebsch-Gordan.

---
### <span style="color:red">Ej 3.1.</span> Coeficientes de Clebsch-Gorban

Calcula los coeficientes de Clebsch-Gordan del producto directo (de representaciones irreducibles de $SU(2)$): $1 \otimes 1/2$.

---
### <span style="color:red">Ej 3.2.</span> Homomorfismo funciones multicomponente. $SO(3)$

Demuestra que la transformación $\phi_{m^{\prime}}^{\prime}(\vec{x})=D_{m^{\prime} m}^{j}(R) \phi_{m}\left(R^{-1} \vec{x}\right)$ es un homomorfismo en el espacio de funciones multicomponente $\left\{\phi_{m}, m=-j, \cdots, j\right\},$ y que por tanto el conjunto de dichas transformaciones forman una representación de $S O(3)$ sobre este espacio de funciones.

---
### <span style="color:red">Ej 3.3.</span> Operadores tensoriales irreducibles. $SO(3)$

El conjunto de $(2 j+1)$ operadores $Q_{m}^{j}$ forma un conjunto de operadores tensoriales irreducibles de rango $j$ si dichos operadores se transforman de acuerdo a la representación $D^{j}(R)$ bajo la rotación $R$ de $S O(3)$ :

$$
U(R) Q_{m}^{j} U(R)^{-1}=\sum_{m^{\prime}} Q_{m^{\prime}}^{j} D_{m^{\prime} m}^{j}(R)
$$

A partir de una rotación infinitesimal, demuestra que

$$
{\left[J_{3}, Q_{m}^{j}\right]=m Q_{m}^{j}}
$$

$$
{\left[J_{\pm}, Q_{m}^{j}\right]=\sqrt{j(j+1)-m(m \pm 1)} Q_{m \pm 1}^{j}}
$$

$$
\sum_{i=1}^{3}\left[J_{i},\left[J_{i}, Q_{m}^{j}\right]\right]=j(j+1) Q_{m}^{j}
$$

---
### <span style="color:red">Ej 3.4.</span> Representaciones de $SO(3)$

Un operador tensorial irreducible que se transforma en la la representación de espín 1 es un operador vectorial. Como la representación $D^{1}$ es equivalente a la representación de definición $R$ de $S O(3),$ hay dos clases de componentes para los operadores vectoriales:

$$
U(R) Q_{m}^{1} U(R)^{-1}=\sum_{m=1}^{1} Q_{m^{\prime}}^{1} D_{m^{\prime} m}^{1}(R)
$$

como acabamos de ver, y

$$
U(R) V_{i} U(R)^{-1}=\sum_{j=1}^{3} V_{j} R_{j i}
$$

que vimos en clase. $Q_{m}^{1}$ se llaman las componentes esféricas y $V_{i}$ se llaman las componentes rectangulares o cartesianas.

1. Calcula la relación entre ambos conjuntos de componentes.
2. A partir de las relaciones de conmutación

$$
\begin{array}{l}
{\left[J_{3}, Q_{m}^{1}\right]=m Q_{m}^{1}} \\
{\left[J_{\pm}, Q_{m}^{1}\right]=\sqrt{2-m(m \pm 1)} Q_{m \pm 1}^{1}}
\end{array}
$$

calcula las relaciones de conmutación $\left[J_{i}, V_{j}\right]$.

---
### <span style="color:red">Ej 3.5.</span> Representación 1/2 de $SU(2)$
Sea $Q_{i}$ con $i=1,2$ un operador tensorial irreducible que se transforma en la representación $1 / 2$ de $S U(2)$ según

$$
\left[J_{a}, Q_{i}\right]=Q_{j} \frac{\left[\sigma_{a}\right]_{j i}}{2}
$$

donde $\sigma_{a}$ son las matrices de Pauli $(a=1,2,3)$.

Conocido el elemento de matriz

$$
\left\langle\frac{3}{2},-\frac{1}{2}\left|Q_{1}\right| 1,-1\right\rangle=A
$$

encuentra

$$
\left\langle\frac{3}{2},-\frac{3}{2}\left|Q_{2}\right| 1,-1\right\rangle
$$

---
### <span style="color:red">Ej 4.1.</span> Homomorfismo

Demuestra que la correspondencia entre $A \in S L(2, \mathbb{C})$ y $\Lambda \in \mathcal{L}_{+}^{\uparrow}$ dada por $\Lambda_{\nu}^{\mu}=\frac{1}{2} \operatorname{tr}\left(\underline{\sigma}^{\mu} A \sigma_{\nu} A^{\dagger}\right)$ es un homomorfismo.

---
### <span style="color:red">Ej 4.2.</span> Representaciones irreducibles

Demuestra que las bases de las representaciones irreducibles obtenidas en la descomposición

$$
D^{\left(\frac{1}{2}, \frac{1}{2}\right)} \otimes D^{\left(\frac{1}{2}, \frac{1}{2}\right)}=D^{(1,1)} \oplus D^{(1,0)} \oplus D^{(0,1)} \oplus D^{(0,0)}
$$

se corresponden respectivamente con un tensor simétrico sin traza, un tensor autodual, un tensor anti-autodual, y un escalar.

---
### <span style="color:red">Ej 4.3.</span> Algebra de Lie de $\mathcal{P}^{\uparrow}_+$

A partir del álgebra de Lie de $\mathcal{P}_{+}^{\uparrow}$ calcula el conmutador $\left[M_{\mu \nu}, W_{\rho}\right],$ con $W_{\mu}=\frac{1}{2} \epsilon_{\mu \nu \sigma \tau} M^{\nu \sigma} P^{\tau}$

---
### <span style="color:red">Ej 4.4.</span> Transformaciones de Lorentz

Demuestra que transformaciones de Lorentz de la forma $U(0, \Lambda)=e^{-i n_{\mu} W^{\mu}},$ donde $n$ es un 4 -vector arbitrario, dejan los autovalores $p_{\mu}$ del operador $P_{\mu}$ invariantes.

---
# Exámenes

---
```
'||''''|
 ||   .
 ||'''|  \\  //  '''|.  '||),,(|,  .|''|, `||''|,  .|''|, (''''
 ||        ><   .|''||   || || ||  ||..||  ||  ||  ||..||  `'')
.||....| //  \\ `|..||. .||    ||. `|...  .||  ||. `|...  `...'
```

---
## Diciembre 2019

---
### <span style="color:red">Ej 1.</span> Matrices de Pauli

Las matrices de Pauli se definen de la forma:

$$
\sigma_{1}=\left(\begin{array}{cc}
0 & 1 \\
1 & 0
\end{array}\right) \quad, \quad \sigma_{2}=\left(\begin{array}{cc}
0 & -i \\
i & 0
\end{array}\right) \quad, \quad \sigma_{3}=\left(\begin{array}{cc}
1 & 0 \\
0 & -1
\end{array}\right)
$$

1. Demuestra que todos los posibles productos generados por $\sigma_1$ y $\sigma_2$ forman un grupo G de orden 8, y que éste es isomorfo al grupo de simetrías del cuadrado, es decir el grupo diédrico $D_4$
2. Escribe los subgrupos normales de G y di a qué grupos conocidos son isomorfos.
3. Identifica los grupos cociente, escribiendo sus elementos a partir de los cosets correspondientes y su tabla de multiplicar. ¿A qué grupos conocidos son isomorfos?

---
### <span style="color:red">Ej 2.</span> Grupo de rotaciones del tetrahedro regular
Sea $T$ el grupo de rotaciones que dejan el tetrahedro regular invariante, que es subgrupo del grupo $S_{4}$ de permutaciones de 4 elementos.
$T$ está formado por las cuatro clases de conjugación: $\mathcal{E}=\{\mathrm{e}\}, \mathcal{C}_{2}=$ $\{(12)(34),(13)(24),(14)(23)\}, \mathcal{C}_{3}=\{(123),(421),(134),(432)\}, \mathcal{C}_{4}=\{(321),(124),(431),(234)\} .$
Además $T$ tiene un subgrupo normal, el grupo $N=\mathcal{E} \cup \mathcal{C}_{2},$ al que le corresponde el grupo cociente $T / N=\{N,(123) N,(321) N\} \cong C_{3}$

1. ¿Cuántas representaciones irreducibles (no equivalentes) tiene $T$?
2. ¿Cuáles son sus dimensionalidades?

---
### <span style="color:red">Ej 3.</span> Representación tridimensional de $S_3$

Consideremos la siguiente representación tridimensional $W$ del grupo $S_{3}$ de permutaciones de tres elementos:

$$
W\left(S_{3}\right)= \begin{array}{ccc}
\left\{
W(e)=\left(\begin{array}{ccc}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right),
W\left(\sigma_{1}\right)=\left(\begin{array}{ccc}
0 & 0 & 1 \\
1 & 0 & 0 \\
0 & 1 & 0
\end{array}\right),
W\left(\sigma_{2}\right)=\left(\begin{array}{ccc}
0 & 1 & 0 \\
0 & 0 & 1 \\
1 & 0 & 0
\end{array}\right)\right. \\ \\ \left.
W\left(\tau_{1}\right)=\left(\begin{array}{ccc}
1 & 0 & 0 \\
0 & 0 & 1 \\
0 & 1 & 0
\end{array}\right),
W\left(\tau_{2}\right)=\left(\begin{array}{ccc}
0 & 0 & 1 \\
0 & 1 & 0 \\
1 & 0 & 0
\end{array}\right),
W\left(\tau_{3}\right)=\left(\begin{array}{ccc}
0 & 1 & 0 \\
1 & 0 & 0 \\
0 & 0 & 1
\end{array}\right)\right\}
\end{array}
$$

Aquí $\sigma_{1}=(123), \sigma_{2}=(321), \tau_{1}=(23), \tau_{2}=(13), \tau_{3}=(12)$

1. $i$ En qué representaciones irreducibles de $S_{3}$ se descompone $W$ ?
2. ¿Sobre qué subespacios de $\mathbb{R}^{3}$ actúan cada una de las anteriores representaciones irreducibles?

---
### <span style="color:red">Ej 4.</span> Representación de $SO(3)$ de espín $j$

Sea $R$ cualquier elemento de $S O(3)$ y $D^{j}(R)$ la matriz de representación de $R$ en la representación irreducible de $S O(3)$ de espín $j$.
Demuestra que la transformación $\phi_{m^{\prime}}^{\prime}(\vec{x})=D_{m^{\prime} m}^{j}(R) \phi_{m}\left(R^{-1} \vec{x}\right)$ es un homomorfismo en el espacio de funciones multicomponente $\left\{\phi_{m}, m=-j, \cdots, j\right\},$ y que por tanto el conjunto de dichas transformaciones forman una representación de $S O(3)$ sobre este espacio de funciones.

---
### <span style="color:red">Ej 5.</span> Tensores autoduales en $\mathcal{L}^{\uparrow}_+$

Sea $T_{\mu \nu}$ un tensor de rango 2 en el espacio de Minkowski, y sea $T_{\mu \nu}^{D} \equiv \frac{1}{2} \epsilon_{\mu \nu \sigma \tau} T^{\sigma \tau}$ su dual.
Decimos que dicho tensor es autodual si $T_{\mu \nu}=T_{\mu \nu}^{D},$ y que es anti-autodual si $T_{\mu \nu}=-T_{\mu \nu}^{D}$.

Comprueba que el grupo de Lorentz ortocrono propio no mezcla el espacio de tensores autoduales con el espacio de tensores anti-autoduales, es decir, que deja invariantes tanto el espacio de tensores auto-duales como el espacio de tensores anti-autoduales.

(Nota: de hecho esos espacios proporcionan representaciones irreducibles del grupo de Lorentz ortocrono propio).

Ayuda: $\frac{1}{2} \epsilon_{\mu \nu \sigma \tau} \epsilon^{\sigma \tau \rho \lambda}=\delta_{\mu}^{\rho} \delta_{\nu}^{\lambda}-\delta_{\nu}^{\rho} \delta_{\mu}^{\lambda}, \quad \epsilon_{\gamma \delta \rho \sigma}=\Lambda_{\gamma}^{\alpha} \Lambda_{\delta}^{\beta} \Lambda_{\rho}^{\mu} \Lambda_{\sigma}^{\nu} \epsilon_{\alpha \beta \mu \nu}$


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

1. Di qué elemento se corresponde con la reflexión respecto al eje horizontal y = 0, cuál se corresponde con la
reflexión respecto al eje vertical x = 0, y cuál se corresponde con la reflexión respecto a la diagonal y = −x.
2. Construye las clases de conjugación de D4.
3. Escribe todos los subgrupos de D4, señala a qué grupos conocidos (vistos en clase) son isomorfos, y di cuáles de
ellos son normales.
4. Identifica los grupos cociente, escribiendo sus elementos a partir de los cosets correspondientes, y diciendo a qué
grupos conocidos (vistos en clase) son isomorfos. ¿Es D4 producto directo de dos de sus subgrupos?

---
### <span style="color:red">Ej 2.</span> Representaciones de $D_4$

Consideremos de nuevo el grupo D4, y los resultados del ejercicio anterior.

1. ¿Cuántas representaciones irreducibles tiene D4? Demuestra que tiene una representación irreducible bidimen-
sional, y que el resto son unidimensionales.
2. A partir de la representación no trivial de los grupos cociente de D4 de orden 2, construye las representaciones
no triviales unidimensionales de D4.
3. Construye la representación bidimensional de D4, es decir representa los elementos del grupo como matrices
2 x 2 actuando sobre los vectores del plano x − y.
4. Consideremos el producto tensorial de la representación irreducible bidimensional consigo misma. ¿Qué rep-
resentaciones irreducibles y con qué multiplicidad aparecen en la descomposición de Clebsch-Gordan de este
producto directo?

---
### <span style="color:red">Ej 3.</span> Isospín

Asumamos simetría de isoespín exacta en la interacción entre nucleones (N) y piones (π). En la región de la
resonancia ∆(1232) (que tiene isoespín I = 3/2) la componente de isoespín 3/2 domina la amplitud πN. Despreciando
la contribución de I = 1/2, calcula el cociente entre la sección eficaz de la transición $\pi^{+} p \rightarrow \pi^{+} p$ y la sección eficaz de
la transición $\pi^{-} p \rightarrow \pi^{-} p$.

Ayuda: $\left|p, \pi^{-}\right\rangle=\frac{1}{\sqrt{3}}\left(\left|\frac{3}{2},-\frac{1}{2}\right\rangle-\sqrt{2}\left|\frac{1}{2},-\frac{1}{2}\right\rangle\right)$

---
### <span style="color:red">Ej 4.</span> El grupo de Lorentz ortocrono propio sobre los espinores de Weyl

Se llama espinor de Weyl dextrógiro al campo $\psi_R(x)$ que bajo transformaciones del grupo de Lorentz ortocrono propio, $\Lambda: x^\mu \rightarrow(x^\mu)' = \Lambda^\mu_\nu x^\nu$, se transforma en la representación irreducible $(0, 1/2)$ de dicho grupo. Es decir, dada una transformación de Lorentz que conlleva una rotación de ángulo $\phi$ en torno al eje $\vec{n}$ y un boost en la dirección $\vec{u}$ de rapidez $\eta$, la ley de transformación de $\psi_R(x)$ es

$$
\psi_{R}^{\prime}\left(x^{\prime}\right)=e^{(i \phi \vec{n}-\eta \vec{u}) \frac{\vec{\sigma}^{*}}{2}} \psi_{R}(x)
$$

donde el asterisco denota conjugación compleja.
1. Calcula la representación de los generadores del grupo de Lorentz sobre $\psi_R$.
2. Si $\psi_R$ y $\chi_R$ son dos espinores de Weyl dextrógiros, ¿se transforma la combinación $v^{\mu}=\chi_{R}^{\dagger} {\sigma}^{\mu} \psi_{R}$ como un 4-vector?, ¿y $v^{\mu}=\chi_{R}^{\dagger} \underline{\sigma}^{\mu} \psi_{R}$?
