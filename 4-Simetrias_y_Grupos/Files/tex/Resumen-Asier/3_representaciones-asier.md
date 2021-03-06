\section{Representaciones de grupos}
\begin{definicion}
Una \textbf{representación lineal} $D(G)$ de un grupo $G$ es una aplicación que a cada $g\in G$ le asocia un operador invertible que actúa sobre el espacio vectorial (EV) $V$ y preserva la estructura de grupo:
\begin{subequations}
\begin{gather}
D(g\cdot h)= D(g) D(h)\\
D(e)= \mathbb{1}_V\\
D(g^{-1})= \left[D(g)\right]^{-1}
\end{gather}
\end{subequations}

La \textbf{dimensión} de una representación es la dimensión del EV sobre el que actúa. \medskip

Una representación se dice \textbf{fiel} si el homomorfismo es isomorfo. En caso contrario se dice \textbf{degenerada}.
\end{definicion}

\begin{proposicion}
Toda representación no trivial de un grupo simple es fiel.
\end{proposicion}

\begin{proposicion}
Dado un grupo $G$ con un subgrupo normal $H$, cualquier representación de $G/H$ es representación degenerada de G.
\end{proposicion}

\begin{definicion}
Dos representaciones $D(G)$ y $D'(G)$ son equivalentes si existe un \emph{intertwiner} $A$ tal que
\begin{equation}
D'=ADA^{-1}
\end{equation}
\end{definicion}

\begin{flushleft}
\textbf{Representación contragradiente:} $g\mapsto \tilde{D}(g)=\left[D(g)^t\right]^{-1}$
\end{flushleft}


\begin{definicion}
El \textbf{carácter} de $g\in G$ en la representación $D(G)$ es la función
\begin{subequations}
\begin{flalign}
G&\rightarrow \mathbb{C}\\
g&\mapsto \chi(g)=\operatorname{Tr}(D(g))
\end{flalign}
\end{subequations}
\end{definicion}

\begin{itemize}
\item Dos representaciones equivalentes tienen el mismo carácter.
\item El carácter es una función de clase --toma el mismo valor para todos los elementos de una clase de conjugación.
\item $\chi(e)=\operatorname{Tr}\mathbb{1}_V=\dim V=\dim D$
\end{itemize}

\begin{definicion}
$V_1\subset V$ es un \textbf{subespacio invariante} si $D(g)v_1\in V_1\quad \forall g\in G,\ \forall v_1\in V_1$. \medskip

La representación es \textbf{irreducible} si $V$ no tiene ningún subespacio propio invariante bajo $D(G)$. En caso contrario se dice \textbf{reducible}.
\end{definicion}
\begin{definicion}
Una representación reducible es \textbf{descomponible} si $V$ es la suma directa de dos subespacios propios invariantes bajo $D$:
\begin{subequations}
\begin{flalign}
&V=V_1\oplus V_2 \\
&D(G)=D_1(G)\oplus D_2(G)
\end{flalign}
\end{subequations}
con $D_i(G)V_i=D(G)V_i\subset V_i$. \medskip

Una representación descomponible es \textbf{completamente reducible} si se descompone en suma directa de representaciones irreducibles. Matricialmente
\begin{equation}
\mathcal{D}(g)=\begin{pmatrix}
\mathcal{D}_1(g)&&\\
& \mathcal{D}_2(g)&\\
&&\ddots \\
&&& \mathcal{D}_n(g)
\end{pmatrix}\qquad \forall g\in G
\end{equation}
\end{definicion}

\begin{teorema}[Schur-Auerbach]
Toda representación de un grupo finito o compacto sobre un EV con producto escalar es equivalente a una representación unitaria.

\end{teorema}
\begin{teorema}[Maschke]
Toda representación de un grupo finito o compacto es completamente reducible.
\end{teorema}


\begin{lema}[Schur]
Sean $D:G\rightarrow \mathrm{GL}(V)$ y $D':G\rightarrow \mathrm{GL}(V')$ dos representaciones \textbf{irreducibles} entrelazadas por $A:V\rightarrow V'$. Entonces:
\begin{enumerate}[label=\roman*)]
\item Si $\dim D\neq \dim D'$, entonces $A=\mathbb{0}$.
\item Si $\dim D=\dim D'$, entonces bien $A=\mathbb{0}$ o bien $D$ y $D'$ son equivalentes ($A$ es un isomorfismo).
\item Si $D=D'$, esto es $AD(g)=D(g)A\enskip \forall g\in G$, entonces $A=\lambda \mathbb{1}$.
\end{enumerate}
\end{lema}

\begin{proposicion}
Sea $D:G\rightarrow \mathrm{GL}(V)$ una representación de un grupo $G$ finito o compacto. Si los únicos operadores lineales que conmutan con $D(g)\ \forall g\in G$ son múltiplos de la identidad, entonces $D$ es irreducible.
\end{proposicion}

\begin{proposicion}
Una representación de un grupo abeliano es irreducible ssi es unidimensional.
\end{proposicion}

\begin{corolario}
Todas las representaciones de un grupo abeliano finito o compacto son unitarias.
\end{corolario}

\begin{relacion}[Ortonormalidad]
Sea $G$ un grupo finito con representaciones irreducibles inequivalentes $D^{(\rho)}(G)$, de dimensión $\dim D^{(\rho)}\equiv d_\rho < \infty$. Entonces

\begin{equation}
\frac{1}{\abs{G}}\sum_{g\in G} D_{ij}^{(\rho)} (g) \bar{D}_{i'j'}^{(\rho')}(g)=\frac{1}{d_\rho}\delta_{\rho\rho'} \delta_{ii'} \delta_{jj'} \label{relacion_ON_finito}
\end{equation}

Análogamente, si $G$ es un grupo de Lie compacto

\begin{equation}
\frac{1}{v(G)}\int_G \dif\mu (g) D_{ij}^{(\rho)} (g) \bar{D}_{i'j'}^{(\rho')}(g)=\frac{1}{d_\rho}\delta_{\rho\rho'} \delta_{ii'} \delta_{jj'} \label{relacion_ON_compacto}
\end{equation}
con $v(G)=\int_G \dif \mu (g)$.

\end{relacion}

\begin{relacion}[Completitud]
Sea $G$ un grupo finito con representaciones irreducibles inequivalentes $D^{(\rho)}(G)$, de dimensión $d_\rho < \infty$. Entonces

\begin{equation}
\frac{1}{\abs{G}}\sum_{\rho} D_{ij}^{(\rho)} (g) \bar{D}_{ij}^{(\rho)}(g')= \delta_{gg'} \label{relacion_completitud_finito}
\end{equation}

En el caso de un grupo de Lie compacto, se tiene

\begin{equation}
\frac{1}{v(G)}\sum_{\rho} D_{ij}^{(\rho)} (g) \bar{D}_{ij}^{(\rho)}(g')= \delta(g,g') \label{relacion_completitud_compacto}
\end{equation}
con $\int_G \dif \mu(g) \delta (g,g') f(g)=f(g')$.
\end{relacion}

\begin{corolario}
Si $G$ es un grupo finito, el orden del grupo y las dimensiones de las representaciones irreducibles inequivalentes se relacionan de la forma
\begin{equation}
\sum_\rho d_\rho^2=\abs{G} \label{orden_dimensiones_representaciones}
\end{equation}
\end{corolario}

\begin{teorema}[Peter-Weyl]
Cualquier función $f:G\rightarrow \mathbb{C}$ continua o de cuadrado sumable se puede expandir en las funciones $D_{ij}^{(\rho)}(g)$:
\begin{equation}
f(g)=\sum_{g'}\delta_{gg'}f(g')=\sum_\rho\sum_{ij}d_\rho D_{ij}^{(\rho)} (g) \overbrace{\sum_{g'} \frac{1}{\abs{G}} D_i^{(\rho)\dagger}(g')f(g')}^{f_{ij}^\rho}=:	\sum_\rho\sum_{ij}d_\rho D_{ij}^{(\rho)} (g) f_{ij}^\rho
\end{equation}

Por ejemplo, la descomposición de Fourier para $G=S^1\cong U(1)$.
\end{teorema}

\begin{relacion}[Ortogonalidad y completitud con caracteres]
Sea $G$ un grupo finito con representaciones irreducibles inequivalentes $D^{(\rho)}(G)$ de dimensión $d_\rho$ y caracteres $\chi^{(\rho)}(g)$. Entonces
\begin{subequations}
\begin{flalign}
&\frac{1}{\abs{G}}\sum_{g} \chi^{(\rho)}(g)\bar{\chi}^{(\rho')}(g)=\frac{1}{\abs{G}}\sum_{i=1}^m \abs{\mathcal{C}_i} \chi_i^{(\rho)}(g)\bar{\chi}_i^{(\rho')}(g)=\delta_{\rho\rho'}\\
& \frac{1}{\abs{G}} \sum_\rho d_\rho \chi^{(\rho)} (g)\bar{\chi}^{(\rho)}(g')=\frac{1}{\abs{G}} \sum_\rho d_\rho \chi^{(\rho)} (gg^{\prime -1})=\delta_{gg'}\\
&\frac{\left|\mathcal{C}_{i}\right|}{|G|} \sum_{\rho} \chi_{i}^{(\rho)} \bar{\chi}_{j}^{(\rho)}=\delta_{i j}
\end{flalign}
\end{subequations}
donde $m$ es el número de clases de conjugación de $G$, $\abs{\mathcal{C}_i}$ es el número de elementos en la clase $\mathcal{C}_i$ y $\chi_i^{(\rho)}$ es el carácter de la clase $\mathcal{C}_i$ en la representación $(\rho)$. \medskip

En el caso compacto, basta reemplazar $\abs{G}\rightarrow v(G),\quad \sum_G\rightarrow \int_G \dif\mu(g)$ y $\delta_{gg'}\rightarrow \delta(g,g')$.
\end{relacion}

Los caracteres $\chi_i^{(\rho)}$ pueden verse como los componentes de una matriz o tabla, con $\rho=1,\ldots,m$ el índice de fila e $i=1,\ldots,m$ el índice de columna.

\begin{proposicion}
El número de clases de conjugación de un grupo es igual al número de representaciones irreducibles inequivalentes.
\end{proposicion}

\begin{ejemplo}[Tabla de caracteres de $S_3$]

$S_3$ tiene tres clases de conjugación,
\begin{equation*}
\mathcal{C}_1=\{e\},\quad \mathcal{C}_2=\{\tau_1,\tau_2,\tau_3\},\quad \mathcal{C}_3=\{\sigma_1,\sigma_2\}
\end{equation*}
y por tanto tres representaciones irreducibles inequivalentes:

\begin{enumerate}
\item En la representación trivial (unidimensional)
\begin{equation*}
D^{(0)}(g)=1\ \forall g\in S_3\Longrightarrow \chi^{(0)}_i=0,\quad i=1,2,3
\end{equation*}
\item Del grupo cociente $S_3/A_3=\{A_3,\tau_iA_3\}\cong C_2$ se induce la representación paridad (\emph{cf.} ejemplo \ref{ejemplo_permutaciones_pares}):
\begin{equation*}
D^{(1)}(e)=D^{(1)}(\sigma_i)=1,\ D^{(1)}(\tau_i)=-1\Longrightarrow \chi^{(1)}_1=1,\ \chi^{(1)}_2=-1,\ \chi^{(1)}_3=1
\end{equation*}
\item A partir de la expresión \eqref{orden_dimensiones_representaciones} obtenemos la dimensión de la representación que falta: $6=1+1+d_2^2\Rightarrow d_2=2$. Sabemos además que $D^{(2)}(e)=\mathbb{1}_2\Rightarrow \chi^{(2)}_1=2$. De las relaciones de ortonormalidad se tiene
\begin{equation*}
\begin{aligned}
&0=1\cdot 2+3\cdot 1\cdot x+2\cdot 1\cdot y\qquad \rho=0,\ \rho'=2\\
&0=1\cdot 2-3\cdot 1\cdot x+2\cdot 1\cdot y\qquad \rho=1,\ \rho'=2\\
\end{aligned}
\end{equation*}
de donde se obtiene $x=0,\ y=-1$.
\end{enumerate}


\begin{table}[ht]
\centering
\textcolor{blue}{
$\begin{array}{c|c c c}
& \mathcal{C}_1&\mathcal{C}_2&\mathcal{C}_3\\
\hline
\chi^{(0)} & 1 & 1 & 1 \\
\chi^{(1)} & 1 & -1 & 1 \\
\chi^{(2)} & 2 & x & y \\
\end{array}$
\caption{Tabla de caracteres de $S_3$}}
\end{table}
\end{ejemplo}

\begin{flushleft}
\textbf{Propiedades de los caracteres} (para grupos finitos y compactos).
\end{flushleft}
\begin{enumerate}[label=\roman*)]
\item Puesto que cualquier representación es completamente reducible, $D=\bigoplus_\rho m_\rho D^{(\rho)}$, el carácter se puede descomponer como
\begin{equation}
\chi=\sum_\rho m_\rho \chi^{(\rho)},\qquad m_\rho=\frac{1}{\abs{G}}
\sum_i \abs{\mathcal{C}_i}\underbrace{\chi_i}_D \underbrace{\bar{\chi}_i^{(\rho)}}_{D^{(\rho)}}
\end{equation}
\item Una representación es irreducible ssi $\norm{\chi}^2=1$, con $\norm{\chi}^2:=\frac{1}{\abs{G}}\sum_g\abs{\chi(g)}^2=\sum_\rho m_\rho^2$.
\item Dos representaciones de un grupo finito o compacto son equivalentes ssi tienen los mismos caracteres.
\item (Th. de Peter-Weyl) Cualquier función de clase se puede expandir en caracteres irreducibles.
\end{enumerate}

\begin{flushleft}
\textbf{Descomposición de Clebsch-Gordan}. El producto tensorial de representaciones irreducibles es completamente reducible:
\end{flushleft}
\begin{equation}
D^{(\sigma)}\otimes D^{(\tau)}=\bigoplus_\rho m_\rho^{\sigma\tau} D^{\rho}
\end{equation}
donde
\begin{subequations}
\begin{flalign}
&m_\rho^{\sigma\tau}=\frac{1}{\abs{G}}\sum_g\chi^{(\sigma)}(g)\chi^{(\tau)}(g)\bar{\chi}^{(\rho)}(g)=\frac{1}{|G|} \sum_{i}\left|\mathcal{C}_{i}\right| \chi_{i}^{(\sigma)} \chi_{i}^{(\tau)} \bar{\chi}_{i}^{(\rho)}\\%\qquad  \qquad G \text{ finito}\\
&\chi^{(\sigma)} \chi^{(\tau)}=\sum_{\rho} m_{\rho}^{\sigma \tau} \chi^{(\rho)}
% &m_\rho^{\sigma\tau}=\frac{1}{v(G)}\int_G\dif\mu(g)\ \chi^{(\sigma)}(g)\chi^{(\tau)}(g)\bar{\chi}^{(\rho)}(g)\qquad G \text{ compacto}
\end{flalign}
\end{subequations}

\begin{flushleft}
\textbf{Coeficientes de Clebsch-Gordan}. La descomposición de C-G expresa cómo se descomponen las matrices de representación en representaciones irreducibles bajo la acción de un grupo. Los coeficientes de C-G describen cómo se descomponen los vectores del EV de representación.
\end{flushleft}
\begin{subequations}
\begin{flalign}
&v_i^{(\rho)}\otimes v_j^{(\sigma)}=\sum_{\tau,a,k} C_{\rho,i,\sigma,j|\tau,a,k}\ v_k^{\tau_a}\\
&\ket{\rho,i,\sigma,j}=\sum_{\tau,a,k} \braket{\tau,a,k}{\rho,i,\sigma,j}\ \ket{\tau, a, k}
\end{flalign}
\end{subequations}

Satisfacen las relaciones de ortogonalidad y completitud (en una base ortonormal y una representación unitaria):
\begin{subequations}
\begin{flalign}
&\sum_{\tau,a,k}\braket{\tau,a,k}{\rho,i,\sigma,j}\braket{\rho,i',\sigma,j'}{\tau,a,k}=\delta_{ii'}\delta_{jj'}\\
&\sum_{i,j}\braket{\tau,a,k}{\rho,i,\sigma,j}\braket{\rho,i,\sigma,j}{\tau',a',k'}=\delta_{\tau\tau'}\delta_{aa'}\delta_{kk'}
\end{flalign}
\end{subequations}


\begin{definicion}[Conjunto de operadores tensoriales irreducibles]
Sean $D^{(\rho)}$ y $D^{(\sigma)}$ representaciones irreducibles de $G$ sobre los espacios vectoriales con producto escalar $V_\rho$ y $V_\sigma$ respectivamente. Sea $Q:V_\rho\rightarrow V_\sigma$ un operador lineal. El conjunto de tales operadores, $\mathcal{L}(V_\rho,V_\sigma)$ forma un EV de dimensión $d_\rho \cdot d\sigma$. Definimos ahora para cada $g\in G$ un operador $D'(g)$ que actúa en $\mathcal{L}(V_\rho,V_\sigma)$ de la forma:
\begin{equation}
D'(g)Q:=D^{(\sigma)}(g)\ Q\ D^{(\rho)}(g)^{-1}\qquad \forall Q\in \mathcal{L}(V_\rho,V_\sigma)
\end{equation}

Estos operadores forman una representación de $G$ sobre $\mathcal{L}(V_\rho,V_\sigma)$, en general reducible. Supongamos que es completamente reducible, y que $D^{(\tau)}$ es una de las representaciones irreducibles que aparecen en su deducción. Sea $\{Q_1^{(\tau)},\ldots,Q_{d\tau}^{(\tau)}\}$ una base del subespacio de $\mathcal{L}(V_\rho,V_\sigma)$ donde actúa $D^{(\tau)}$. Este conjunto recibe el nombre de \textbf{conjunto de operadores tensoriales irreducibles de la representación} $D^{(\tau)}$ de $G$.
% Entonces
% \begin{equation}
% D'(g) Q_i^{(\tau)}
% \end{equation}
\end{definicion}

\begin{teorema}[Wigner-Eckart]
Sea $G$ un grupo finito o compacto. Sean $D^{(\rho)},\ D^{(\sigma)},\ D^{(\tau)}$ representaciones unitarias irreducibles de $G$, y sean $\left\{v_i^{(\rho)}\right\}_{i=1}^{d_\rho}$ y $\left\{v_i^{(\rho)}\right\}_{j=1}^{d_\sigma}$ bases ortonormales de los EVs sobre los que están definidas $D^{(\rho)}$ y $D^{(\sigma)}$ resp. Finalmente, sea $\left\{Q_k^{(\tau)}\right\}_{k=1}^{d_\tau}$ un conjunto de operadores tensoriales irreducibles de $D^{(\tau)}$. Entonces
\begin{equation}
\left(v_j^{(\sigma)},Q_k^{(\tau)}v_i^{(\rho)}\right)=\sum_{a=1}^{m_{\sigma}^{\rho\tau}} \bar{C}_{\rho,i,\tau,k|\sigma,a,j}\left(\sigma||Q^{(\tau)}||\rho		\right)_a%\qquad \forall i=1,\ldots,d_\rho,\quad \forall j=1\ldots,d_\sigma,\quad \forall k=1,\ldots,d_\tau
\end{equation}
$\forall i=1,\ldots,d_\rho,\quad \forall j=1\ldots,d_\sigma,\quad \forall k=1,\ldots,d_\tau$\medskip

Los <<elementos de matriz reducidos>> $\left(\sigma||Q^{(\tau)}||\rho		\right)_a$ son independientes de $i,j,k$. La dependencia en $i,j,k$ de las cantidades $ \left(v_j^{(\sigma)},Q_k^{(\tau)}v_i^{(\rho)}\right)$ está completamente recogida en los coeficientes de Clebsch-Gordan.
\end{teorema}


\begin{flushleft}
\textbf{Representaciones en espacios funcionales.} Dada una representación de un grupo $G$, $D:G\rightarrow \mathrm{GL}(n\mathbb{C})$, sobre el EV $\mathbb{C}^n$, los vectores $\mathbb{C}^n$ se transforman bajo los elementos de $G$ según
\end{flushleft}

\begin{subequations}
\begin{flalign}
& \vec{x}\longmapsto \vec{x}'=D(g)\ \vec{x}\\
& x^i\longmapsto x^{\prime i}=\sum_j D(g)^i_j\ x_j
\end{flalign}
\end{subequations}
donde $i$ es el índice de fila y $j$ el de columna. \medskip

Si consideramos funciones $f:\mathbb{C}^n\longrightarrow \mathbb{C},\quad
\vec{x}\longmapsto f(\vec{x})$, la transformación de las coordenadas induce una transformación en la función:
\begin{equation}
f'(\vec{x}')=f(\vec{x})\Longrightarrow f'(D(g)\ \vec{x})=f(\vec{x})
\end{equation}
y concluimos que
\begin{equation}
f \mapsto f'\qquad \boxed{f'(\vec{x})=f\left(D(g^{-1})\vec{x}\right)}
\end{equation}
