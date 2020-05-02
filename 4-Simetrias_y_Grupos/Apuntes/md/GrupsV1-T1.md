<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> 

# Introducción a las simetrías en física
## La importancia de las simetrías en física

Llamaos simetrías de un sistema físico a aquellas propiedades del sistema que se preservan bajo alguna transformación. Las simetrías van de la mano a leyes de conservación (ver teorema de Noether) de las ecuaciones que describen estos sistemas.

Hasta el siglo XX se estudiaban las simetrías a partir de las ecuaciones de los sistemas, a partir de Einstein y la revolción de la relatividad se cambia el foco y nos empezamos a fijar directamente en las simetrías (no en las ecuaciones), derivando más tarde las ecuaciones de los sistemas asociadas a tales simetrías.

## Relación entre simetría y teoría de grupos

La herramienta fundamental para el estudio de las simetrías es la teoría de grupos. Las transformaciones matemáticas asociadas a cada simetría poseen las propiedades de los grupos algebraicos. Por tanto, para el estudio de las simetrías es necesario conocer teoría de grupos.

Así, por ejemplo, las transformaciones de simetría de la relatividad especial dorman el grupo de Poincaré (traslaciones espacio-temporales, rotaciones espaciales y rotaciones espacio-temporales).

## Tipos de simetrías

### Locales y globales
Decimos que una simetría es local si las transformaciones de simetría cambian de punto a punto del espacio-tiempo ($\mathcal{X}(\vec{x},t)$). Las globales por tanto son aquellas invariantes de punto a punto del e-t. Son importantes en teorías gauge.

### Discretas y contínuas

Una simetría es discreta si su ley de transformación no es contínua (como las simetrías de los cristales o las rotaciones de los poliedros), un ejemplo de gran importancia es la simetría CPT de la cuántica de campos. Las simetrías contínuas son aquellas que sí pueden ser descritas por una transformación contínua (por ejemplo la simetría de rotación del círculo).

\smallskip
En dinámica clásica las consecuencias de las simetrías contínuas se hacen evidentes a través del principio de mínima acción. Una simetría de un sistema clásico deja invariante la acción bajo su aplicación sobre la misma y por tanto no modifica las ecuaciones del movimiento.

## Simetría en mecánica cuántica

En mecánica cuántica las transformaciones de simetría son lineales y existe principio de superposición, provocando que las simetrías tengan profundas consecuencias.

Sea $\mid\upsilon\rangle$ el estado del sistema y $\mathcal{R}$ un operador lineal unitario que representa una transformación.

$$\mathcal{R}:\mid\nu\rangle\longrightarrow \mathcal{R}\mid\upsilon\rangle\in \mathcal{H}$$

El estado $\mathcal{R}\mid\upsilon\rangle$ representa también un estado del sistema si $\mathcal{R}$ es una transformación unitaria (preserva la norma). Por ejemplo, una representación del singlete de rotaciones sería, si $\mathcal{R}=R$ representa el operador rotación $\mid\phi\rangle$ el estado del sistema y $\mid\upsilon\rangle$ un estado que puede ser mezcla:

$$\mid\phi\rangle = \sum_R R\mid\upsilon\rangle \hspace{1cm} \text{Invariancia bajo rotaciones}$$

$$R\mid\phi\rangle=\sum_{R'}R'R\mid\upsilon\rangle \hspace{1cm} \text{Como R es grupo, RR'=R'' -otra rotación-}$$

$$R\mid\phi\rangle= \sum_{R''}R''\mid\upsilon\rangle=\sum_R R\mid\upsilon\rangle=\mid\phi\rangle \hspace{1cm} \text{El estado $\mid\phi\rangle$ es invariante bajo rotaciones}$$

La teoría de representaciones de grupos discretos y continuos es muy importante en mecánica cuántica para derivar las consecuencias de las simetrías. Las leyes de selección que gobiernan los espectros atómicos son, por ejemplo, consecuencia de la simetría de rotaciones.

Reveló la simetría también la existencia de los fermiones y los bosones, partículas con distinta transformación frente al cambio de partículas idénticas.

## Transformaciones globales
La aplicación de una transformacion de simetría global da lugar a una situación física diferente en la que las observaciones son invariantes bajo dichas transformaciones.

$$\vec{x}\longrightarrow \vec{x}+\vec{v}t$$

Siendo $\vec{v}t\neq \vec{v}t(\vec{x})$ una transformación global.


## Simetrías gauge
La aplicación de la transformación gauge solo cambia la descripción de una misma situación física. La primera vez que aparece es en electrodinámica, donde los campos EM pueden presentarse en un potencial cuadrivector $A_\mu=(\phi, \vec{A})$ que se transforma según:

$$A_\mu \longrightarrow A_\mu +\partial \mu \phi (x)$$

Donde $\partial_\mu \phi (x)=\frac{\partial \phi (x)}{\partial x_\mu}$.

Transformación que deja completamente invariantes los campos $\vec{E}$ y $\vec{B}$. A partir de los años 70 las teorías gauge van a tener una posición central en el estudio de las teorías fundamentales de la naturaleza. Son la base del modelo estándar de partículas, afectando por ejemplo a la dinámica y fuerza de partículas o forzando la existencia de otras tales como el famoso bosón de Higgs (se dice que la simetría dicta la interacción).

## Ejemplo de aplicación de las simetrías a un caso sencillo

Sea una partícula en una red periódica unidimensional, su hamiltoniano es del tipo $H=\frac{p^2}{2m}+\phi (x)$ con $\phi (x)$ un potencial periódico con periodicidad $\phi (x)=\phi (x+nb) \hspace{0.1cm} \forall n\in \mathcal{Z}$.

\smallskip
$\bullet$ Por tener esta periodicidad existe simetría de traslación en la red (pues tanto la parte cinética como la potencial tienen la simetría).

\begin{equation
    x\longrightarrow x+nb
    \label{traslacion
\end{equation

\smallskip
$\bullet$ Dos sistemas relacionados por (\ref{traslacion}) tienen el mismo comportamiento.

\smallskip
$\bullet$ Dos observadores relacionados por (\ref{traslacion}) ven las mismas propiedades del sistema (punto de vista activo/pasivo).

En mecánica cuántica tenemos un estado $\mid\upsilon\rangle$ en $\mathcal{H}=L^2(\mathds{R},dx)$ que se traslada según el operador unitario $\mathcal{T}=T$ que cumple:

$$\mathcal{T}: \mid\upsilon\rangle\longrightarrow T\mid\upsilon\rangle=\mid\upsilon '\rangle$$

$\mathcal{T}$ es una transformación lineal que deja \textbf{invariantes los observables}. Es decir, si $\mathcal{O}$ es un observable:

$$O\mid\upsilon\rangle=O\mid\upsilon '\rangle$$

Dado que los obserbables se expresan como $\braket{\phi|\upsilon}$, el operador T debe preservar este producto escalar. T debe ser un operador \textbf{unitario autoadjunto}.

El conjunto de simetrías de la red está representado por el conjunto de operadores unitarios en $\mathcal{H}$. Es decir, forma una representación de transformaciones de simetría del hamiltoniano. Vemos pues que deben transformar también los observables. Hallemos el valor esperado del operador unitario A:

$$\braket{\phi |A|\upsilon}=\braket{\phi |T^{-1}TAT^{-1}T|\upsilon}=\braket{\phi '|TAT^{-1}|\upsilon '}=\braket{\phi '|A'|\upsilon'}$$

Luego vemos que bajo la acción de T:

$$A\longrightarrow TAT^{-1}=A'$$

Volviendo ahora a nuestro sistema, sea $\midx\rangle$ un estado del sistema en representación de posición, el operador traslación:

$$T\midx\rangle=\midx+nb\rangle=\midx'\rangle$$

Es evidente ver que H es invariante bajo traslación:

$$THT^{-1}=T\left( \frac{P^2}{2m}+\phi (x)\right)T^{-1}=T \frac{P^2}{2m}T^{-1}+\phi (x+nb)$$

Dado que $\phi (x)=\phi (x+nb)$ solo debemos comprobar que el operador momento lineal en mecánica cuántica se traslade adecuadamente. Sea $P^2=\partial ^2_x\frac{1}{2m}$ la expresión de este operador en la base de posiciones, tenemos:

$$T\frac{\partial ^2}{\partial x^2}\frac{1}{2m}T^{-1}\midx\rangle=T\frac{\partial ^2}{\partial x^2}\frac{1}{2m}\midx-nb\rangle=\frac{T}{2m}\left ( \frac{\partial ^2}{\partial x^2}\midx-nb\rangle\right)$$

Dado que $\frac{\partial ^2}{\partial x^2}\midx\rangle=\frac{\partial ^2}{\partial x^2}\midx-nb\rangle$, decimos que la parte cinética es invariante bajo traslaciones [H,T]=0 y la base de posiciones que hemos utilizado sería una buena base de autoestados para el hamiltoniano.

\newpage
### Representación de operadores de traslación discreta
La simetría que presenta este sistema es la del grupo de operadores de traslación discreta. Cumplen una serie de propiedades:

\begin{itemize

\item T(n)T(m)=T(n+m)

\item T(0)=$\mathds{1}$

\item T(-n)=$T(n)^{-1}$

\end{itemize

La primera propiedad es la de grupo abeliano y la segunda la de unitario. ¿Cómo implementamos entonces esta simetría?

Escogemos una base de autoestados de T(n) (que conmuten para todo n) que sea base para todo n. Es decir:

$$T(n) \midu(\xi)\rangle=t_n(\xi)\midu(\xi)\rangle$$

La base $\midu(\xi)\rangle$ tiene unos autovalores $t_n(\xi)$ que guardan información sobre n y $\xi$. Estos autovalores tienen una serie de propiedades:

\begin{itemize
    \item $t_n (\xi) t_m(\xi) = t_{n+m}(\xi)$
    \item $t_0(\xi)=1$
    \item $t_{-n}(\xi)=\frac{1}{t_n(\xi)}$
    \item $t_n(\xi)t_m(\xi)=t_m(\xi)t_n(\xi)$
    \item $|t_n(\xi)|^2=1$
\end{itemize

Luego, los $t_n(\xi)$ adecuados son $ t_n(\xi)=e^{-i\phi_n(\xi)}$ con $\phi (\xi)$ real e impar. Luego $\phi (\xi)=nf(\xi)$ para cualquier $f(\xi)$ real e impar, por ejemplo $f(\xi)=\xi$. Quedan los autovalores:

$$t_n(\xi)=e^{-i\xi n}$$

Se dice que el cojunto de autovalores $\lbrace t_n(\xi) \rbrace$ proporcionan una representación para el grupo de operadores de traslación discreta de dimensión d: $\mathcal{T}^d$.

### Consecuencias de la simetría
Dado que $t_n(\xi)$ es periódica de periodo $2\pi$  tomamos el intervalo $-\pi <k<\pi$. Sea $k=\xi/b$ en el intervalo $-\pi/b<k<\pi/b$ buscamos los $t_n(k)$ que sean autoestados de T y H al mismo tiempo (es decir que definan adecuadamente las traslaciones y la energía de las partículas al mismo tiempo).

\smallskip
Sea $U_{E,k}(x)=\braket{x|U(E,k)}$ la función de onda en representacion de posiciones.

$$x=nb+y \hspace{0.2cm} \forall y \in -b\2\leq y \leq b/2$$

$$\midx\rangle=T(n)\midy\rangle; \hspace{0.2cm}\bra{x}=\bra{y}T^+(n)$$
$$\overbrace{\braket{x|U(E,k)}}^{U_{E,k}(x)}=\bra{y}T^+(n)\midU(E,k)\rangle=\bra{y}T(-n)\midU(E,k)\rangle=\braket{y|U(E,k)}e^{iknb}=U_{E,k}(y)e^{ik(x-y)}$$

Lo que acabamos de demostrar, que $e^{-ikx}U(x)=e^{-iky}U(y)$, implica que podemos estudiar una única celda de la red y tendríamos igualmente toda la información de la misma. Se define la función de Bloch como $V_{E,k}(x)=U_{E,k}(x)e^{-ikx}$ , periódica en x de periodo b con k la llamada variable del vector de ondas. La función de Bloch, si recordamos de sólido, nos permite estudiar todo el cristal a partir de uno de sus electrones pues la red posee una simetría de traslación igual a la de la función (al igual que aquí en nuestro ejemplo).
\newpage

Por tanto, usando la función de onda obtenida en la ecuación de Schrödinger del sistema encontraríamos la solución (sin más que introducir una condición de contorno periódica). Para cualquier k del intervalo admitido se puede encontrar un conjunto de autovalores y autofunciones en forma explícita. En general se obtienen niveles de energía discretos (el Ppio. de exclusión de Pauli limitará luego -o no- el número de partículas por nivel).

\smallskip
Este ejemplo también ilustra la relación entre la teoría de representación de grupos y el análisis armónico (siendo el ejemplo del de Fourier un caso partícular). En nuestro ejemplo las funciones de representación son la base de ondas planas de las sries de Fourier, satisfacen:

$$1.- \int ^\pi_{-\pi} d\xi e^{in\xi} e^{im\xi} =2\pi \delta_{m,n}$$
$$2.- \sum_{n=1}^N e^{in\xi}e^{in\xi '}=\delta (\xi-\xi ')$$

Las llamadas relaciones de ortonormalidad y compeltitud. Dada por tanto una función cualquiera $f(\xi)$ con $\xi \in [-\pi,\pi)$ se puede escribir $f(\xi)=\sum_{n=1}^N f_ne^{-in\xi}$ en base de ondas planas con coeficientes $f_n=\frac{1}{2\pi}\int^\pi_{-\pi}d\xi e^{in\xi}f(\xi)$.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYwMDEzMjA0OCwtMTI4NTU0NTU3MF19
-->