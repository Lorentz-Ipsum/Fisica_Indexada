[TOC]

# Bloque I

## Átomos polielectrónicos
$$H = \sum_{i=1}^{N} (\frac{P_i^2}{2m} - \frac{Ze^2}{R_i}) + \sum_{i < j}^{N} \frac{e^2}{R_{ij}} + (efectos relativistas/spinorbita/nucleares)$$
> * Primer sumatorio por Aproximación de Orden 0, campo central:Cada electrón ve un potencial promedio debido al resto de electrones y al núcleo.
>  * Resto de términos por teoría de perturbaciones.

> Solución: Suma para cada electrón $H = \sum H_i$
> $\begin{Bmatrix} \psi(R_1,\dots, R_N) = \psi_1(R_1)\dots \psi_N(R_N)
\\ E = E_1 + \dots + E_N\end{Bmatrix}$

### Esféricas
$$L^2 = -\frac{\hbar^2}{sin^2\theta}[(sin\theta \partial_\theta)^2 + \frac{\partial^2}{\partial \phi^2}]$$
$$\psi(r) = R(r)\Omega(\theta,\phi)$$

$$\boxed{[\frac{P_z^2}{2m} + \frac{L^2}{2mr^2} + V(r)]R(r)\Omega(r) = \mathscr{E}R(r)\Omega(r) }$$

$$L^2\Omega = c \Omega(r) \rightarrow c= \hbar^2 l(l+1)$$
$$L_z Y_{lm}(r) = c Y_{lm}(r) \rightarrow c= \hbar m$$
$$R(r) = \frac{1}{r} P(r)$$

$$\boxed{-\frac{\hbar^2}{2m}\frac{d^2}{dr^2} P_l(r) + [\frac{\hbar^2 l(l+1)}{2mr^2}+V(r)]P_l(r) = \mathscr{E}P_l(r)}$$

$$\boxed{P_l ''+ [2E + \frac{2Z}{r} - \frac{l(l+1)}{r^2}]P_l= 0}$$

$$R_{r\rightarrow 0} \approx r^l, \quad R_{r\rightarrow \infty}\approx e^{-\sqrt{-2E}r}$$

### Unidades atómicas
$$\hbar \rightarrow 1, \quad m \rightarrow 1, \quad e \rightarrow 1$$
> Comportamiento asintótico

### Consideraciones
$$\psi_{n,l,m_l,s,m_s}(r) = \frac{1}{r}P_{n,l}(r)Y_{l,m}(\theta,\phi)\chi_{s,m_s}$$
$$\mathscr{E}_{nl} = -R\frac{Z^2}{n^2}$$
> Degeneración accidental $g = 2n^2$
> Número de ceros $=n-l$

## Campo central. Aspecto típico de los niveles de energía.
> $\begin{Bmatrix} \text{Continuo de energía} & E =p^2/2m
\\ \text{Límite de ionización}
\\ \text{Niveles excitados} &\text{Aproximación de Rydberg:} \mathscr{E}_{nl} \approx -R\frac{(Z-N+1)^2}{(n-\delta_l)^2}
\\ \text{Niveles ocupados} & \text{Aproximación hidrogenoide:} \mathscr{E}_{nl} \approx -R\frac{(Z-\sigma _{nl})^2}{n^2} + \text{Corr Relativista}
\end{Bmatrix}$

> Entre los niveles excitados y ocupados nos basamos en cálculo numérico o datos experimentales.

### Spin
$\chi_{s,m_s}(\dots)\ \text{ó}\ |s\ m_s\rangle$

### Momento Angular
$$J_\pm = J_1 \pm iJ_2$$
$$[J_i,J_j] = i\epsilon_{ijk}J_k \quad [J^2,J_i] =0$$
$$J_\pm |j\ m\rangle = \sqrt{j(j+1)-m(m\pm1)}|j\ m\pm 1\rangle$$
> Combinación lineal de dos momentos angulares independientes $J=J_1+J_2$
$$|j_1\ j_2\ j\ m\rangle = \sum\langle j_1\ m_1\ j_2 \ m_2|j_1 j_2 jm|j_1\ m_1\ j_2\ m_2\rangle$$
#### Coeficientes de Clebsch-Gorban

### Efectos relativistas
$$E^2 =p^2 c^2 + m^2 c^4$$
$$H\approx \frac{P^2}{2m} + V(z) + H_m +H_0 + H_{SO}$$
$$H_m = -\frac{1}{8}\frac{p^4}{m^3 c^2}$$
$$H_0 = -\frac{\hbar^2}{4m^2 c^2}\nabla V\cdot \nabla = -\frac{\hbar^2}{4m^2 c^2}\frac{dV}{dr}\frac{\partial}{\partial r}$$
$$H_{SO} = \frac{1}{2m^2 c^2}\frac{1}{r} \frac{dM}{d r} \mathbf{l}\cdot\mathbf{s}$$
$$E_{SO} = -\mathbf{\mu}\cdot\mathbf{B}$$
$$\mathbf{\mu} = -g_s\frac{|e|}{2mc}k\frac{\mathbf{s}}{\hbar}$$
$$\mathbf{B} = \frac{1}{mecr}\frac{dV}{dr}\mathbf{l}$$

## Teoría de perturbaciones
### I Caso no degenerado
$$\langle \psi_0 | \Delta H | \psi_0 \rangle = \Delta E \\
E= E_0 + \Delta E\\
H_0 |\psi_0 \rangle = E_0 |\psi_0 \rangle$$
### II Caso degenerado
$$\begin{Bmatrix}
H= H_0 + \Delta H\\
| \psi \rangle = \sum \alpha_i | \psi_{0i} \rangle + | \Delta\psi \rangle\\
\end{Bmatrix}$$
$$\Delta H_{ij} = \langle \psi_{0i} | \Delta H | \psi_{0j} \rangle$$
$$\begin{pmatrix} \Delta H_{11} & \cdots & \Delta H_{1g}\\
\vdots  & & \vdots \\
\Delta H_{g1}&\cdots  & \Delta H_{gg} \end{pmatrix}
\begin{pmatrix} \alpha_1\\
\vdots \\
\alpha_g \end{pmatrix} =
\Delta \mathscr{E}\begin{pmatrix} \alpha_1\\
\vdots \\
\alpha_g \end{pmatrix}$$
> Los autovectores son nuevos autoestados.
> Los autovalores son las correccciones de la energía.

## Estructura fina
$$H_m \alpha\ p^4 \quad H_D \alpha\ \frac{1}{Z^2} \frac{d^2}{dr^2} \quad H_{SO} = \frac{1}{r^2}\mathbf{L}\cdot\mathbf{S}$$

$$\boxed{
\mathscr{E}_{nj} = -\frac{Z^2}{2\pi ^2} \{ 1+ \frac{\alpha ^2 Z ^2 }{n} ( \frac{1}{j+1/2} - \frac{3}{4n} ) \}
}$$

### Espectro del Hidrogeno
$$\Delta E =Z^2 R ( 1/n_1^2 - 1/n_2^2)$$
$$R = 109737.3 cm^{-1} \quad \lambda (cm) = 1/\Delta E (cm^{-1} \quad 13.6 eV = 109737.2 cm^{-1}$$
> Reglas de selección:
> $\Delta J = 0,\pm 1 \quad 0 \nrightarrow 0$
> $\Delta l = \pm 1$
> $E = h\nu = \frac{hc}{\lambda}$

> Átomos alcalinos
> $[gas noble]+1e^-\\ J=0 \quad \quad L\ S\ J$
> $E_{nl} \approx -\frac{R}{(n-\delta_l)^2}$

> Átomos alcalinotérreos
> $\boxed{^{2s+1}L_J ,\quad J =|L-1/2|\dots |L+1/2|}$
> $\begin{Bmatrix}
n^o J = 1 \rightarrow Singlete\\
n^o J = 2 \rightarrow Doblete\\
n^o J = 3 \rightarrow Triplete
\end{Bmatrix}$
> $E_{nl} = -R\frac{Z_{ej}^2}{(n-\delta_l)^2} \quad Z_{ef} = 2$

## Rayos X
> Emisión por caida interna de electrones
> El espectro de emisión depente del material no de V.
> Líneas K, L, M (observables con bajo V)

$T = R\frac{(Z-\sigma )^2}{n^2} \quad \begin{pmatrix} \sigma_K \approx 2 \\
\sigma_L \approx 8 \\
\sigma_M \approx 20 \end{pmatrix}$

$$
\left. \begin{array} {  c | c | c | c | }   & { n } & { l } & { j }
\\ \hline K_I & { 1 } & { 0 } & { 1/2 }
\\ \hline L_I & { 2 } & { 0 } & { 1/2 }  
\\ L_{II} & { 2 } & { 1} & { 1/2 }  
\\ L_{III} & { 2 } & { 1 } & { 3/2 }  
\\ \hline M_I & { 3 } & { 0 } & { 1/2 }  
\\ M_{II} & { 3 } & { 1 } & { 1/2 }
\\ M_{III} & { 3 } & { 1 } & { 3/2 }
\\ M_{IV} & { 3 } & { 2 } & { 3/2 }
\\ M_{V} & { 3 } & { 2 } & { 5/2 }  
\\ \end{array} \right.
$$

### Función de onda antisimétrica
> Los electrones son indistinguibles $\rightarrow$ Principio de exclusión de Pauli $\rightarrow$ no puede haber más de un electrón con el mismo estado energético $\rightarrow$ Pueden estar en el mismo lugar pero con espín diferente

Simetría $\rightarrow \psi(r_1\sigma_1,r_2\sigma_2) = \pm \psi(r_2\sigma_2,r_1\sigma_1)$
> $+ \rightarrow$ Simetrico(Bosones, spin entero)
> $- \rightarrow$ Antisimetrico(Fermiones, spin semientero)

Paridad $\rightarrow \psi(r_1\sigma_1,r_2\sigma_2) = \pm \psi(- r_1\sigma_1, -r_2\sigma_2)$
> $+ \rightarrow$ Par
> $- \rightarrow$ Impar

### Determinante de Slater
$\psi(x_1 \dots x_N) =\frac{1}{\sqrt{N}}\begin{vmatrix}\psi_1(x_1) &\dots &\psi_1(x_N) \\
\vdots & & \vdots \\
\psi_N(x_1) & \dots & \psi_N(x_N) \end{vmatrix}$
$\psi_i = R_{nl}Y_{lm}\chi_{ms}$

### Observaciones
>Para un electrón $n,l$:
* $g = 2(2l+1)$ posibles $m_l m_s$
>Para $\nu$ electrones $n,l$:
* $g = \begin{pmatrix}2(2l+1)\\ \nu \end{pmatrix}$ posibles Slater
>Varios electrones $n_1 l_1 ^{\nu_1} n_2 l_2 ^{\nu_2} \dots$:
* $g =\begin{pmatrix}2(2l_1+1)\\ \nu_1 \end{pmatrix}\begin{pmatrix}2(2l_2+1)\\ \nu_2 \end{pmatrix}\dots$

$\begin{pmatrix}n\\ k \end{pmatrix} = \frac{n!}{k!(n-k)!}$

$(m_{l_1}^{m_s}\ m_{l_2}^{m_s}\ \dots)$

$1s^2 2s \quad g =\begin{pmatrix}2\\2 \end{pmatrix}\begin{pmatrix}2\\ 1 \end{pmatrix} = 2$
$(0^+ 0^- 0^+)(0^+ 0^- 0^-)$

$\psi(r_1 \sigma_1,r_2 \sigma_2, r_3 \sigma_3) =\frac{1}{\sqrt{3!}}\begin{vmatrix}
R_{10}(r_1)Y_0^0\chi_{+} &R_{10}(r_2)Y_0^0\chi_{+} & R_{10}(r_3)Y_0^0\chi_{ms} \\
R_{10}(r_1)Y_0^0\chi_{-} & R_{10}(r_2)_0^0\chi_{-} & R_{10}(r_3)Y_0^0\chi_{ms} \\
R_{10}(r_1)Y_0^0\chi_{\pm} & R_{10}(r_2)Y_0^0\chi_{\pm} & R_{10}(r_2)Y_0^0\chi_{ms} \end{vmatrix}$
