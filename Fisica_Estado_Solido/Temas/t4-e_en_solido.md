# Tema 4 - Electrones en el sólido.
El hamiltoniano que describe el sistema de un sólido cristalino debe simplificarse con ciertas aproximaciones.

## 1. Aproximación adiabática (de Born-Oppenheimer)
Al tener masas distintas, los tiempos característicos de iones y de electrones es muy dispar. En un movimiento de los iones los electrones se irán situando en el estado fundamental (se acoplan al estado instantáneo de los iones).
Por tanto, el hamiltoniano se puede dividir en un $H_{e^-}+H_{iones}$.

Sea la posición de los iones $R_I$, y $\epsilon(R_I)$ su energía:

$$
H_i = - \frac{\hbar^2}{2} \sum_I \frac{\nabla^2_I}{M_I} + \frac{(Ze)^2}{4 \pi \varepsilon_0}\sum_{I<J} \frac{1}{|R_I-R_J|} + \epsilon(R_I)
$$

Ahora aplicamos la aproximación armónica (la variación de la posición de los iones es pequeña). Así la parte electrónica es un potencial para los iones.

> En el caso de los haluros alcalinos $\epsilon(R_I)$ no es relevante, ya que los electrones sólo participan en transferencia.

> En metales los electrones son fundamentales para la cohesión del sólido, $\epsilon(R_I)$ es relevante.

Al deslocalizarse los electrones, más importante es $\epsilon(R_I)$.
Los iones están en los sitios de la red (red fría, cold lattice) para poder explotar sus simetrías.

Si además consideramos las interacciones de un electrón con el resto como un potencial promedio (campo medio, mean field) tenemos que:

$$
H_e = - \frac{\hbar^2}{2m} \sum_i \nabla^2_i + V(r_i) = \sum_i h_i
$$

Donde $V(r_i)$ es el potencial promedio sobre el campo i-ésimo.

Así, encontramos un hamiltoniano que es la suma de iones y electrones, resoluble, dependiente sólo de la posición del electrón i-ésimo (independent electron approximation).

$V(r_i) = V(r_i +R)$ con $R$ un vector de la red es periódico.

$H$ es invariante bajo traslaciones a lo largo de vectores de la red.
Sea el operador traslación $T_{\vec{R}}$, tenemos que $[H,T_{\vec{R}}]=0$, es decir, existen autofunciones comunes.

### Teorema de Bloch
Sea $\psi$ una autofunción de $H$:
$H\psi = \epsilon \psi$
$T_{\vec{R}} \psi = \lambda \psi$
es decir,
$\psi (r + R) = e^{ikR}\psi$ donde $e^{ikR}$ es el operador traslación.

Las exponenciales son un conjunto completo de funciones:
$\psi = \sum_k c_k e^{ikr}$ con $\psi$ cualquier función.

Si fuera periódico: $\psi(r+R) = \psi(r) \Rightarrow e^{ikR}=1 \Rightarrow k = g$
Tiene que ser un vector de la red recíproca.

> Para que tengamos un potencial periódico evitamos supercicies (interfases): 1 periodo del tamaño del cristal:

### Condiciones de contorno periódicas de Born-Von Karmann
$\psi(r + \vec{N}_i \vec{a}_i) = \psi(r)$ (con sumatorio en i a todas las celdas del cristal, $N_i$ recorre las $N$ celdas del cristal)

$\sum_k c_k e^{ik(r + \vec{N}_i \vec{a}_i)} = \sum_k c_k e^{ikr}$

$e^{ik\vec{N}_i \vec{a}_i}=1 \Rightarrow k = \frac{g_i}{N_i}$

$\Rightarrow V(r) = \sum_g V_g e^{igr}$

Tratamos $H$ con la $\psi$ en función de exponenciales:

$- \frac{\hbar^2}{2m} \nabla^2 \sum_k c_k e^{ikr} +  \sum_{k,g} V_g c_k e^{i(k+g)r} = \epsilon \sum_k c_k e^{ikr}$

Hacemos el cambio de variable $k'=k+g$ y queda:

$\sum_k (\frac{\hbar^2 k^2}{2m} \nabla^2 - \epsilon) c_k e^{ikr} +  \sum_{k',g} V_{k'-g} c_{k'-g} e^{ik'r} = 0$

Como las exponenciales forman funciones completas:

$$\Large
c_k (\frac{\hbar^2 k^2}{2m} \nabla^2 - \epsilon) +  \sum_g c_{k-g} V_{g}  = 0
$$

Cada electrón sufre un proceso de scattering. Entra a un potencial cristalino con $k$ y sale con $k-g$.

$$
\psi_k = \sum_g c_{k-g} e^{i(k-g)r} = [\sum_g \epsilon_k e^{-igr}]e^{ikr}
$$

$$
\psi(r+R) = \sum_g c_{k} e^{-igr} e^{ikr} e^{-igR} e^{ikR} = \psi(r) e^{ikR}
$$

Ya que $R$ es vector de la red recíproca $e^{-igR}=1$ y se cumple el teorema de Bloch.

$\psi_k (r)=u_k(r) e^{ikr}$

Con $u_k(r)$ una amplitud con la periodicidad de la red: $u_k(r) = u_k(r+R)$

Así que las funciones de onda son ondas planas donde se mezclan con su reflejada y se forman amplitudes periódicas (Bloch Waves). Estas son periódicas en la red recíproca:

$\psi(k+G) = \sum_g c_{k+G-g} e^{-igr} e^{iGr} e^{ikr}$

$c_{k+G-g} = c_{k-(g'-G)}$ Y $g-G$ es otro vector de la red recíproca que al sumar recorre todos los sitios.

$\psi(k+G) = \sum_{g'} c_{k-g} e^{-ig'r} e^{ikr} = \psi_k (r)$ Periódica en la red recíproca.

Luego:
- La energía es periódica en la RR.
- Podemos elegir la celda de la RR más conveniente para tratar todos los estados electrónicos.

## 2. Modelo de electrones libres. $V=0$
El hamiltoniano se reduce a:

$H = - \frac{\hbar^2}{2m} \nabla^2 \qquad [H,p]=0$

Las autofunciones de $p$ son las de $H$. Como $-i\hbar \nabla \psi = p\psi$ tenemos $\psi = e^{-\frac{p}{i\hbar}}$ ondas planas.

Como $p=\hbar k$ tenemos $\psi = \frac{1}{\sqrt{V}}e^{ikr}$

Sustituimos en la ecuación de Schrödinger:

$H\psi = E\psi \Rightarrow - \frac{\hbar^2}{2m} (iK)^2 \frac{1}{\sqrt{V}}e^{ikr} = E\frac{1}{\sqrt{V}}e^{ikr} \Rightarrow E= \frac{\hbar^2 k^2}{2m}$ para un electrón.

Las superficies de energía constante son esferas de radio $k= \sqrt{\frac{2mE}{\hbar^2}}$.

Si el cristal es cúbico:

$k_i = m \frac{2m}{a_i}\frac{1}{N_i}$ con $m\in \mathcal{Z}, \frac{2\pi}{a_i}=g_i$ y $N_i$ es el número de celdas.

Como $N \gg 1$ pasamos al continuo:

$(\delta k)^3 = \frac{2\pi}{a_1 N_1}\frac{2\pi}{a_2 N_2}\frac{2\pi}{a_3 N_3} =\frac{(2\pi)^3}{N \Omega}=\frac{(2\pi)^3}{V}$

$\Omega = \text{Vol celda}, V= \text{Vol Cristal}$

El número de estados será:

$$
d^3 k \frac{V}{(2\pi)^3}
$$
En otras palabras, el volumen $d^3 k$ por la densidad de estados $\frac{V}{(2\pi)^3}$.

Tenemos $N$ electrones que es (cada uno con degeneración de espín 2):

$$
N = 2\int_0^{k_F} d^3 k \frac{V}{(2\pi)^3} = 2 \frac{V}{(2\pi)^3} \int_0^{k_F} k d^2 k = 2 \frac{V}{(2\pi)^3} \frac{4}{3} \pi k_F^3
$$

$$
\frac{N}{V} = n = \frac{k_F^3}{3 \pi^2} \Rightarrow k_F = (3 \pi^2 n)^{1/3}
$$

$k_F$ nos indica hasta qué nivel está ocupada la red. $k_F \approx 10^{-8} cm^{-1}$

Razonando con energías:

$$
n = \frac{N}{V} = 2 \frac{V}{(2\pi)^3} \int_0^{k_F} k d^2 k = \frac{1}{\pi^2} \int_0^{E_F} dE \frac{2mE}{\hbar^2} \frac{(2m)^{1/2}}{2 \sqrt{E}} = \int_0^{E_F} g(E) dE
$$

Donde hemos usado $k = \frac{\sqrt{2 m E}}{\hbar} \Rightarrow dk = \frac{\sqrt{2m}}{\hbar} \frac{(2m)^{1/2}}{2 \sqrt{E}} dE$ y $g(E)$ es el número de estados por unidad de volumen:

$$
g(E) dE = \frac{(2m)^{3/2}}{2\pi \hbar^3} \sqrt{E}
$$

Así pues, los electrones se apilan hasta la energia de Fermi.

La densidad de estados en el nivel de Fermi es:

$$
g(E_F) dE = \frac{(2m)^{3/2}}{2\pi \hbar^3} \sqrt{E_F}
$$

Y de aquí podemos deducir que $g(E) = g(E_F)\left( \frac{E}{E_F} \right)^{1/2}$, y así $n = \frac{2}{3}g(E_F)\frac{1}{E_F^{1/2}}E_F^{3/2} = \frac{2}{3} g(E_F) E_F$.

Típicamente $E_F \approx 5 - 10 eV$ (apilamiento muy distinto a los modelos clásicos) -> Energía interna muy alta.

### Energía interna a 0 Kelvin
Será la suma de las energías de todos los electrones:

$U_{0K} = \int_0^{E_F}g(E) E dE = g(E_F)\frac{1}{E_F^{1/2}}\frac{2}{5}E_F^{5/2} = \frac{3}{2} n \frac{2}{5} E_F = \frac{3}{5} n E_F$

A 0 Kelvin lleno los niveles hasta $E_F$, donde se corta de forma abrupta.

### Energía interna a $T$ finita
A temperatura finita, como $kT \ll E_F$ los únicos que van a ganar energía son los de las últimas capas (los internos necesitarían energías muy altas).

Ya no habría escalón abrupto, sino que su distribución sería de la forma:

$$
f(E) = \frac{1}{1 + e^{\frac{E-E_F}{kT}}}
$$

(Probabilidad de que un electrón esté en cierto nivel de Energía)

[Gráfica, función de Bloch?]

El calor específico es la medida directa de la densidad de estados en el nivel de Fermi. Ahora la energía interna se modifica:

$U = \int_0^\infty g(E) f(E) dE$

$U_T = \int_0^\infty E g(E) f(E) dE$

$c_V = \frac{\partial U_T}{\partial T}$ es el calor específico, lo que medimos.

$c_V = \int_0^\infty E g(E_F) \frac{\partial f(E)}{\partial T} dE$

$\frac{\partial f(E)}{\partial T} = \frac{1}{( 1 + e^{\frac{E-E_F}{kT}} )^2} e^{\frac{E-E_F}{kT}} \frac{E-E_F}{kT^2}$

Con $g(E) \approx g(E_F)$ ya que $kT \ll E_F$.

Como en un metal $n$ no varía hacemos $\frac{\partial n}{\partial T} E_F = 0$


## 3. Electrones casi libres (NFE)
