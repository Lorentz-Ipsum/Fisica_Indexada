---
title: Res T3.
author: Lorentz Ipsum
date: 14 de agosto de 2020
print_background: true
export_on_save:
  html: true
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

---
# Resumen 3. Representación de grupos
[TOC]

---

## 3.1. Acciones de Grupos

- Def: Acción de Grupo
	- Props
	- Obs
- Defs: Órbita, Estabilizador
- Teo: Teorema Órbita-Estabilizador

## 3.2. Representaciones Lineales

- Def: Representación lineal de un grupo
- Def: Fiel
  - Proposiciones:
    - Representación no trivial de un grupo simple: Fiel
    - Representación fiel: O trivial, o no simple
- Def: Representación Matricial, Trivial, de Definición
- Proposiciones:
  - Cualquier representación del grupo cociente $H/G$, donde $H\triangleleft G$, también es representación de $G$, pero degenerada.
  - Toda representación no trivial de un **grupo simple** es **fiel**.

## 3.3. Representación conjugada y contragradiente

$$
\begin{array}{cc}
\bar{D}: \hspace{0.1cm} G \to GL(n \mathbb{C})  \\
g \to \bar{D}(g)=\overline{D(g)}
\end{array}
$$

$$
\begin{array}{cc}
\tilde{D}: \hspace{0.1cm} G\to GL(n, \mathbb{C})  \\
g \to \tilde{D}(g)=(D(g)^t)^{-1}
\end{array}
$$

## 3.4. Representaciones equivalentes

- Def: Representaciones equivalentes, Intertwiner

$$
D'(G)=AD(G)A^{-1}
$$

- Def: Carácter de una Representación
$$
\begin{array}{cc}
\mathcal{X}^D: \hspace{0.1cm} G \to \mathbb{C} \\
g \to \mathcal{X}^D(g)=Tr(D(g))
\end{array}
$$
  - Props:
  $$
  \mathcal{X}(g)=\mathcal{X}(hgh^{-1})
  $$

  $$
  \mathcal{X}(e)=Tr(\mathbb{I}_N)=N=dim V
  $$

## 3.5. Representaciones reducibles e irreducibles

- Def: Subspacio invariante
$$
D(G)V_1 \subset V_1
$$
	- Representacón reducible, irreducible
    	- Decimos que una representación D(G) en V es **irreducible** si V no contiene ningún subespacio invariante (no trivial) bajo D(G). En caso contrario es **reducible**.
	- Representacón descomponible
        - Una representación D(G) reducible es **descomponible** si V se puede descomponer como suma directa de dos subespacios no triviales (propios) invariantes bajo la acción de la propia representación.
$$
D(G)=D_1(G)\oplus D_2(G)
$$
	- Representacón completamente reducible
        - Una representación D(G) descomponible es **completamente reducible** si se descompone en suma directa de representaciones irreducibles.
- Def: Suma directa de representaciones
$$
dim (D_1\oplus D_2)=dim (D_1)+dim (D_2)
$$

$$
(D_1 \oplus D_2)(g)=\left (\begin{array}{cc}
D_1(g) & 0 \\
0 & D_2(g)
\end{array} \right)
$$

## 3.6. Unitariedad

- Def: Representación unitaria
$$
D(g)D(g)^{+}=D(g)^{+}D(g)=\mathbb{1}_{V}, \hspace{0.1cm} \forall g\in G
$$
$$
(u,v)=(D(g)u,D(g)v)\hspace{0.1cm} \forall u,v\in V
$$
    - Propiedad
      - Si una representación unitaria es reducible es completamente reducible.
- Teo: Teorema de Schur-Auerbach
	- Toda representación D(g) de un grupo finito G sobre un espacio vectorial V con producto escalar es equivalente a una representación unitaria.
- Teo: Teorema de Maschke
    - Todas las representaciones de un grupo finito o un grupo no finito pero compacto son completamente reducibles (pues las unitarias lo son). Basta con estudiar sus representaciones irreducibles.


## 3.7. Lemas de Schur

- Lema previo
  - Dadas D y D' tal que $AD(g)=D'(G)A \hspace{0.2cm} \forall  \hspace{0.1cm} g\in G$. Los subespacios ker(A) y A(V) son invariantes bajo D(G) y D(G') respectivamente.
- Lemas:
    1. Si dim(D)$\neq$ dim(D'), entonces A=0 forzosamente (no se pueden entrelazar)
    2. Si dim(D)=dim(D') entonces o bien A=0 o bien A es un isomorfismo en cuyo caso D es equivalente a D'.
    3. Si D=D', es decir, $AD(G)=D(G)A$ $\forall  \hspace{0.1cm} g\in G$ entonces A=$\lambda \mathbb{1}$ (multiplo de la identidad).
	- Proposiciones
    	1. Sea $D: G\to GL(V)$ una representación de un grupo G que es finito o compacto y supongamos que los únicos operadores lineales de V en V que conmutan con todos los operadores D(g) son los múltiplos de la identidad. Entonces D es irreducible.
        2. Una represemtación de un grupo abeliano es irreducible si y solo si es unidimensional.
    - Corolario
        - Todas las representaciones irreducibles de un grupo abeliano finito o compacto son unitarias.



## 3.8. Relaciones de ortonormalidad y completitud

- Relación de ortonormalidad
	- Grupos finitos
    $$
    \text{G finito:} \hspace{0.3cm} \frac{1}{|G|}\sum _g D_{ij}^\rho (g) \bar{D}_{i'j'}^{\rho '}(g)=\frac{1}{d \rho}\delta _{\rho , \rho '}\delta _{i, i'}\delta _{j,j'}
    $$
- Relación de completitud
	- Grupos finitos
    $$
    \text{G finito:} \hspace{0.3cm} \frac{1}{|G|}\sum _\rho d\rho \sum _{ij} \underbrace{D_{ij}^{(\rho)}\bar{D}_{ij}^{(\rho ')}(g')}_{\mathcal{X}^{(\rho)}(gg'^{-1})}=\delta _{\rho, \rho '}
    $$
	- Corolario
    $$
    \sum _\rho d\rho ^2 =|G|^2
    $$
- Th: Teorema de Peter-Weyl
  - Cualquier función $f:G\rightarrow \mathbb{C}$ continua o de cuadrado sumable se puede expandir en las funciones $D_{ij}^{(\rho)}(g)$:
  $$
  f(g)=\sum _{g'}\delta _{g,g'}f(g')=\sum _{\rho,i,j}D_{ij}^{(\rho)}(G)\sum _g \frac{1}{|G|}D_{ij}^{(rho)+}(g')f(g')=\sum _{\rho ,i, j} d\rho D_{ij}^{(\rho)}(g)f_{ij}^{(\rho)}
  $$

- Relaciones de ortonormalidad y completitud con caracteres
    $$
    \text{G finito:} \hspace{0.3cm} \frac{1}{|G|}\sum _g\mathcal{X}^{(\rho)}(g)\mathcal{X}^{(\rho ')}(g)=\delta _{\rho , \rho '}
    $$

    $$
    \frac{1}{|G|}\sum _{i=1}^m |e_i|\mathcal{X}_i^{(\rho)}(g)\bar{\mathcal{X}}_i^{\rho '}(g')=\delta _{\rho , \rho '}
    $$
    donde m es el numero de clases de conjugación, $|e_i|$ es el número de elementos en la clase $e_i$ y $\mathcal{X}_i^{(\rho)}$ el caracter de la representación.
- Tabla de caracteres
  - Propiedades
- Prob: Representación paridad

## 3.9. Producto tensorial de representaciones y coeficientes de Clebsch-Gordan

- Tensores
	- Def: Producto tensorial de operadores
	- Def: Producto tensorial de representaciones
	- Def: Descomposición de Clebsch-Gordan
		- Def: Multiplicidad
		- Proposicion
- Probs:
	- Representación irreducible unitaria de $D^{(2)}$
	- Tabla de caracteres de $S_3$
	- Representación bidimensional irreducible unitaria de $S_3$
- Def: Coeficientes de Clebsch-Gordan
	- Relaciones de ortogonalidad y completitud
	- Prob: Coeficientes de Clebsch-Gordan para $D^{(2)} \otimes D^{(2)}$

## 3.10. Teorema de Wigner-Eckart

- Def: Conjunto de operadores tensoriales irreducibles
- Th: Teorema de Wigner-Eckart

## 3.11. Representaciones del producto directo de grupos
