---
title: Ejercicios resueltos
author: Lorentz Ipsum
date: 19 de agosto de 2020
print_background: true
export_on_save:
  html: true
---

---
# Ejercicios resueltos de simetrías y grupos
[TOC]

--------------------

        ████████╗    ██████╗
        ╚══██╔══╝    ╚════██╗
           ██║        █████╔╝
           ██║       ██╔═══╝
           ██║       ███████╗
           ╚═╝       ╚══════╝

---
# T2: Elementos generales

---
### <span style="color:red">Ejercicio:</span> 1. Grupo cíclico

Probar que un grupo finito de orden n (primo) debe ser un grupo cíclico (generado por a).

$$
C_n=\lbrace a,a^2,...,a^{n-1},a^n=e\rbrace \cong Z_n
$$

---
<span style="color:darkcyan">Solución:</span>

Por el teorema de Lagrange el orden de un subgrupo H de un grupo G debe ser divisor de orden n de G. Por otra parte, cada elemento del grupo genera un subgrupo cíclico y llamamos orden del elemento al orden m del subgrupo cíclico que genera. Por el teorema de Lagrange m debe ser divisor de n y como m es primo $m=\lbrace 1,n\rbrace$.

Si n es primo entonces el orden de los elementos de G ($m_g, \hspace{0.1cm} \forall g\in G$) debe ser n (a excepción de la identidad) y el subgrupo cíclico que generan es el mismo grupo G.

---
Deducimos también que dos grupos cualesquiera cuyos órdenes sean el mismo número primo son isomorfos e isomorfos al grupo cíclico de ese orden.

\\

---
<span style="color:violet">Observaciones:</span> Nota

Definiendo el isomorfismo:

$$
C_n\cong Z_n, \hspace{2cm} \begin{array}{c}
\phi : Z_n \to C_n \\
m \to \phi (m)=a^m
\end{array}
$$

$$
m_1+m_2 \to \phi(m_1+m_2)=a^{m_1+m_2}=\phi(m_1)\phi (m_2)
$$

\\

\\\\

---
### <span style="color:red">Ejercicio:</span> 2. Grupo cociente

Probar que $G=H_1\times H_2$ implica que $G/H_1\cong H_2$.

---
<span style="color:darkcyan">Solución:</span>

Por ser G producto directo de los otros dos grupos, estos son normales y tiene sentido construir los grupos cociente. $G/H_1$ es grupo con respecto a la multiplicación de cosets. Tenemos que:

$$
G/H_1=\lbrace gH_1\rbrace=\lbrace h_1h_2H_1 \rbrace=\lbrace (h_1H_1)(h_2H_1)\rbrace=\lbrace (e,H_1)(h_2H_1)\rbrace=\lbrace h_2 H_1\rbrace
$$

Concluimos que los cosets de $H_1$ generados por los elementos de $H_2$ son los únicos elementos del grupo cociente $G/H_1$. Esto sugiere la correspondencia natural uno a uno dada por:

$$
\left . \begin{array}{c}
\phi : H_2 \to G/H_1\\
h_2 \to \phi (h_2)=h_2H_1
\end{array} \right | G/H_1\cong H_2
$$

Además:

$$
\phi (hh')=hh'H_1=(hH_1)(h'H_1)=\phi (h) \phi (h') \hspace{0.1cm}\forall h,h' \in H_2
$$

\\\\

---
### <span style="color:red">Ejercicio:</span> 3. Isomorfismos

Construye un isomorfismo que demuestre que el grupo de reales positivos, con la regla de multiplicación de grupo dada por la suma usual de números, es decir $(\mathbb{R}^+, \cdot) \cong (\mathbb{R}, +)$

---
<span style="color:darkcyan">Solución:</span>

\\\\

---
### <span style="color:red">Ejercicio:</span> 4. Grupos de órden 4

Probar que, salvo isomorfismos, solamente hay dos grupos diferentes de orden 4: el grupo cíclico $C_4$ y el grupo de reflexiones en el plano $V_4$ (también llamado grupo de Klein).

Demostrar también que el grupo de Klein es producto directo de $C_2$ consigo mismo.

---
<span style="color:darkcyan">Solución:</span>

$$
C_4=\lbrace  a,a^2,a^3,A^4=e\rbrace
$$

$$
V_4=\lbrace e,\sigma ,\tau ,\rho \rbrace
$$

$$
e: \begin{array}{c}
x\to x  \\
y\to y
\end{array}; \hspace{0.5cm} \sigma : \begin{array}{c}
x\to -x  \\
y\to y
\end{array}; \hspace{0.5cm} \rho : \begin{array}{c}
x\to x  \\
y\to -y
\end{array}; \hspace{0.5cm} \tau : \begin{array}{c}
x\to -x  \\
y\to -y
\end{array};
$$

---
La tabla de $V_4$ es (se ve que es un grupo abeliano):

$$
\begin{array}{ c | c c c c }
V_4 & e & \sigma  & \tau  & \rho \\
\hline
e & e & \sigma  & \tau  & \rho  \\
\sigma  & \sigma  & e & \rho  & \tau  \\
\tau  & \tau  & \rho  & e & \sigma  \\
\rho  & \rho  & \tau  & \sigma  & e
\end{array}
$$

---
Para demostrar que solo hay estos grupos de orden 4 sabemos que sus elementos generan subgrupos cíclicos. Por el teorema de Lagrange los ementos de G solo pueden ser o de orden 4 o de orden 2 (divisores de 4). Si G tiene al menos un elemento de orden 4 entonces ese elemnto genera $C_4$ y como $C_4 \in G \to G \cong C_4$.

Si G no tiene ningún elemento de orden 4 entonces todos sus elementos son de orden 2, llamémoslos $\lbrace e,\sigma ,\tau ,\rho \rbrace$, con e identidad y los cuadrados de todos iguales a la identidad pues generan $C_2$. Nos falta conocer como pueden ser los productos cruzados. Por ejemplo $\sigma \tau =\rho$ necesariamente, ya que $\sigma \tau \neq e$ pues $\sigma \sigma =e$; $\sigma \tau \neq \sigma$ pues $\tau \neq e$ y $\sigma \tau \neq \tau$ pues $\sigma \neq e$. Ocurre lo mismo con el resto de cruzados lo que implica que solo hay esta tabla (este grupo abeliano) y por tanto solo dos grupos de orden 4; el cíclico y el abeliano.

---
Para la demostración de que $V_4\cong C_2 \times C_2$, sabemos que $V_4=\mathbb{Z}_2 \times \mathbb{Z}_2$. Sabemos que $C_2\cong \mathbb{Z}_2$ y que son subgrupos normales pues $V_4$ es abeliano. Además, es única (salvo conmutación ya que es abeliano) pues dados los subgrupos normales $\lbrace e, \sigma \rbrace$ y $\lbrace e, \tau \rbrace$ su producto directo genera $V_4$ de forma única (genera $\rho$ únicamente bajo el producto $\tau \sigma$ o $\sigma \tau$ al ser abeliano).

\\\\

---
### <span style="color:red">Ejercicio:</span> 5. Grupo diédrico

Consideremos el grupo diédrico $D_4$, que es el grupo de simetría de un cuadrado.
Si situamos el cuadrado en el plano $xy$, centrado en el origen de coordenadas y con sus lados paralelos a los ejes de coordenadas, entonces el grupo consiste en rotaciones en torno al centro y reflexiones con respecto a los ejes vertical, horizontal y diagonales de pendiente $\pm 1$.

Llamemos $e$ a la identidad, $g$ a la rotación de ángulo $\pi/2$ (en sentido antihorario) y $h$ a la reflexión con respecto a la diagonal $y = x$.

Demuestra que el grupo está generado por $g$ y $h$ y escribe su tabla de multiplicar.

---
<span style="color:darkcyan">Solución:</span>

Sean las rotaciones:

$$
R=\lbrace  g,g^2,g^3,g^4=e\rbrace
$$

$$g: \hspace{0.1cm} \text{giro de} \hspace{0.1cm} \pi/2; \hspace{0.5cm} g^2: \hspace{0.1cm} \text{giro de} \hspace{0.1cm} \pi; \hspace{0.5cm} g^3: \hspace{0.1cm} \text{giro de} \hspace{0.1cm} 3\pi /2; \hspace{0.5cm} g^4 :  \hspace{0.1cm} \text{giro de} \hspace{0.1cm} 2\pi=e$$

Y las reflexiones:

$$H=\lbrace h_1, h_2, h_3, h_4 \rbrace$$

$$h_1: \hspace{0.1cm} y=x; \hspace{0.5cm} h_2: \hspace{0.1cm} y=-x; \hspace{0.5cm} h_3: \hspace{0.1cm} x=0; \hspace{0.5cm} h_4: \hspace{0.1cm} y=0$$

La combinación de R con $h_1$ genera el grupo $D_4=R\times H$, lo vemos en su tabla de multiplicar:

---
$$
\begin{array}{c| cccccccc }
D_4 & e & g & g^2 & g^3 & h & gh & g^2h & g^3h \\
\hline
e & e & g & g^2 & g^3 & h & gh & g^2h & g^3h \\
g & g & g^2 & g^3 & e & gh & g^2h & g^3h & h \\
g^2 & g^2 & g^3 & g & e & g^2h & g^3h & h & gh \\
g^3 & g^3 & e & g & g^2 & g^3h & h & gh & g^2h \\
h & h & g^3h & g^2h & gh & e & g^3 & g^2 & g \\
gh & gh & h & g^3h & g^2h & g & e & g^3 & g^2 \\
g^2h & g^2h & gh & h & g^3h & g^2 & g & e & g^3\\
g^3h & h^3h & g^2h & gh & h & g^3 & g^2 & g & e
\end{array}
$$

\\\\

---
Que se ve bien como se ha construido la tabla representándolo gráficamente.

--------------------

        ████████╗    ██████╗
        ╚══██╔══╝    ╚════██╗
           ██║        █████╔╝
           ██║        ╚═══██╗
           ██║       ██████╔╝
           ╚═╝       ╚═════╝

--------------------

---
# T3: Representaciones

---
### <span style="color:red">Ejercicio:</span> 1. Representación sobre GL(n,C)

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
<span style="color:darkcyan">Solución:</span>

Para demostrar que este mapa define una representación del grupo G debemos probar que respeta la estructura de grupo, es decir, que si $g=g''g'$ entonces $f\overset{g}{\longrightarrow} f''$ coincide con la composición de $f \overset{g'}{\longrightarrow} f'$ con $f'\overset{g''}{\longrightarrow}f''$. Tenemos que:

$$
f'(\vec{x})=f(D^{-1}(g),\vec{x})
$$

$$f''(\vec{x})=f'(D^{-1}(g), \vec{x})=f(D^{-1}(g')D^{-1}(g''),\vec{x})=f(D(g''g')^{-1},\vec{x})=f(D((g)^{-1},\vec{x})
$$

Como queríamos demostrar.

\\\\

---
### <span style="color:red">Ejercicio:</span> 2. Representación de S3

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
<span style="color:darkcyan">Solución:</span>

Partiendo de $D^{(2)}(\tau _1)=\left ( \begin{array}{cc}-1  & 0 \\0 & 1\end{array}\right)$ y $D^{(2)(\tau _3)}=\frac{-1}{2}\left ( \begin{array}{cc}-1  & \sqrt{3} \\\sqrt{3} & 1\end{array}\right)$.

Con estas dos podemos construir $W(\tau _1)$ y $W(\tau _3)$, y con ellas podemos construir todas las demás mediante la tabla de multiplicación:

$$
\tau _1: \begin{array}{cc}
x^1\to -x^1 & x^2\to -x^2  \\
y^1\to y^1 & y^2 \to y^2
\end{array}
$$

$$
x^1x^2\overset{\tau _1}{\to} (x^1x^2)^1=x^1x^2
$$

$$
x^1y^2\overset{\tau _1}{\to} (x^1y^2)^1=-x^1y^2
$$

$$
y^1x^2\overset{\tau _1}{\to} (y^1x^2)^1=-y^1x^2
$$

$$
y^1y^2\overset{\tau _1}{\to} (y^1y^2)^1=y^1y^2
$$

$$
V=lin\lbrace x^1x^2,x^1y^2,y^1x^2,y^1y^2 \rbrace; \hspace{1cm} f'(\vec{x})=W(\tau _1)f(\vec{x})=f(W(\tau _1)^{-1}\vec{x})
$$

Ahora tomando la base ortonormal más sencilla:

$$
x^1x^2=\left( \begin{array}{c}
 1  \\
 0 \\
 0 \\
 0
\end{array} \right ); \hspace{0.2cm} x^1y^2=\left( \begin{array}{c}
 0  \\
 1 \\
 0 \\
 0
\end{array} \right ); \hspace{0.2cm} y^1x^2=\left( \begin{array}{c}
 0  \\
 0 \\
 1 \\
 0
\end{array} \right ); \hspace{0.2cm} y^1y^2=\left( \begin{array}{c}
 0  \\
 0 \\
 0 \\
 1
\end{array} \right )
$$

Queda la representación:

$$
W(\tau _1)=\left (\begin{array}{cccc}
1  & 0 & 0 & 0 \\
0  & -1 & 0 & 0 \\
 0 & 0 & -1 & 0 \\
 0 & 0 & 0 & 1
\end{array} \right)
$$

Ahora, para $W(\tau _3)$ tenemos que sigue la siguiente relación:

$$
\left ( \begin{array}{c}
 x^{(i)^1}  \\
   y^{(i)^1}
\end{array}\right) = D^{(2)} \left ( \begin{array}{c}
 x^{(i)}  \\
   y^{(i)}
\end{array}\right)=\frac{-1}{2}\left ( \begin{array}{cc}
-1 & \sqrt{3} \\
   \sqrt{3} & 1
\end{array}\right)\left ( \begin{array}{c}
 x^{(i)}  \\
   y^{(i)}
\end{array}\right)= \left ( \begin{array}{cc}
 \frac{x^{(i)}}{2} & \frac{-\sqrt{3}}{2}y^{(i)}  \\
 \frac{-\sqrt{3}}{2}y^{(i)}  & \frac{-1}{2}y^{(i)}
\end{array}\right)
$$

Por lo que las transformaciones son del estilo:

$$
x^1x^2 \overset{\tau _3}{\longrightarrow} (x^1 x^2)^1=\left ( \frac{x^1}{2}-\frac{\sqrt{3}}{2}y^1 \right) \left ( \frac{x^2}{2}-\frac{\sqrt{3}}{2}y^2 \right)
$$

Y los elementos de la base se transforman a:

$$
(x^1x^2) \longrightarrow (x^1x^2)^1
$$

$$
\left( \begin{array}{c}
 1  \\
 0 \\
 0 \\
 0
\end{array} \right )\longrightarrow \frac{1}{2} \left( \begin{array}{c}
 1  \\
 -\sqrt{3} \\
 -\sqrt{3}\\
 3
\end{array} \right )
$$

Repitiendo este procedimiento podemos hallar la transformación para cada elemento de la base de V. Por tanto, es posible hallarnos $W(\tau _3)$ y con ella obtener $W(\tau _2)$, $W(\sigma _1)$ y $W(\sigma _2)$ mediante el producto adecuado de matrices.

\\\\
