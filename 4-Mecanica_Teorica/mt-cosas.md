<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

A VER SI ESTO SE COMMITEA DE VERDAD


## 1. Mecánica lagrangiana

### 1.1. Dinámica lagrangiana:
Espacio de configuración,
trayectorias y variaciones infinitesimales,
principio variacional,
ecuaciones de Euler-Lagrange,
características de la acción,
ligaduras.

### 1.2. Cantidades conservadas:
Teorema de Noether,
coordenadas cíclicas,
teorema de Noether,
variaciones temporales,
energía,
partícula en un potencial,
invariancia bajo reparametrizaciones temporales,
simetrías gauge.

### 1.3. Dinámica relativista:
Acción: Partículas libres y partículas en un campo electromagnético,
ecuaciones de movimiento,
cantidades conservadas: Cuadrimomento,
momento angular cuadridimensional,
centro de inercia e invariantes de Casimir.


## 2. Mecánica hamiltoniana

### 2.1. Sistemas hamiltonianos:
Transformación de Legendre,
ecuaciones de Hamilton,
espacio de fases,
corchetes de Poisson.

### 2.2. Geometría simpléctica:
Forma simpléctica,
ecuaciones de Hamilton,
flujos hamiltonianos,
flujo de un campo vectorial,
campos vectoriales hamiltonianos,
teorema de Noether,
variedades simplécticas,
teorema de Darboux y reducción por simetría.

### 2.3. Transformaciones canónicas:
Simplectomorfismos,
transformaciones canonoides,
función generatriz y tipos de transformaciones canónicas.

### 2.4. Invariantes:
Teorema de Liouville,
distribuciones estadísticas,
invariante integral de Poincaré,
espacio de fases extendido,
invariante integral de Poincaré-Cartan y cantidades conservadas.


## 3. Integrabilidad

### 3.1. Teoría de Hamilton-Jacobi:
ecuación de Hamilton-Jacobi,
función principal de Hamilton,
soluciones completas,
separación de variables,
hamiltonianos conservados,
coordenadas cíclicas,
variables separables,
teorema de Huygens y analogía óptica,

### 3.2. Teoremas de integrabilidad:
teorema de Liouville,
teorema de Arnold,
variables de acción-ángulo,
movimiento condicionalmente periódico.


## 4. Temas de especialización:

### 4.1. Teoría cláscia de campos

### 4.2. Perturbaciones

### 4.3. Caos

### 4.4. Dinámica de Fluidos


---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---


## Wikipedia
### Mecanica avanzada

$\begin{matrix}
T\mathcal{M} & \to & T^* \mathcal{M} \\
\mathbf{v} & \to & i_\mathbf{v}\omega=\omega(\mathbf{v},\cdot)
\end{matrix}$

$i_\mathbf{v}\omega = \mathrm{d}\hat{H}$

$\mathbf{v}|_ {\phi} =
\begin{bmatrix} \dot{p}_1\\ \dots\\ \dot{p}_N\\ \dot{q}_1\\ \dots\\ \dot{q}_N\\ \end{bmatrix}
\qquad \mathbf{\hat{H}}|_ \phi^T = \begin{bmatrix} \frac{\partial H}{\partial p_1}\\ \dots\\ \frac{\partial H}{\partial p_N}\\ \frac{\partial H}{\partial q_1}\\ \dots\\ \frac{\partial H}{\partial q_N}\\ \end{bmatrix}
\qquad \omega|_ \phi = \begin{bmatrix}
0     & \dots & 0     & -1   & \dots & 0    \\
\dots & \dots & \dots &\dots & \dots & \dots\\
0     & \dots & 0     & 0    & \dots & -1   \\
1     & \dots & 0     & 0    & \dots & 0    \\
\dots & \dots & \dots &\dots & \dots & \dots\\
0     & \dots & 1     & 0    & \dots & 0    \\   \end{bmatrix}$

$i_\mathbf{v}\omega|_ \phi = \mathrm{d}\hat{H}|_\phi \Rightarrow
\begin{bmatrix} \dot{p}_1\\ \dots\\ \dot{p}_N\\ \dot{q}_1\\ \dots\\ \dot{q}_N\\ \end{bmatrix} =
\begin{bmatrix}
  0     & \dots & 0     & -1   & \dots & 0    \\
  \dots & \dots & \dots &\dots & \dots & \dots\\
  0     & \dots & 0     & 0    & \dots & -1   \\
  1     & \dots & 0     & 0    & \dots & 0    \\
  \dots & \dots & \dots &\dots & \dots & \dots\\
  0     & \dots & 1     & 0    & \dots & 0    \end{bmatrix}
\begin{bmatrix}
\frac{\partial H}{\partial q_1}\\ \dots\\ \frac{\partial H}{\partial q_N}\\ \frac{\partial H}{\partial p_1}\\ \dots\\ \frac{\partial H}{\partial p_N} \end{bmatrix}
\Rightarrow \begin{cases}
   \dot{p}_i = -\cfrac{\partial H}{\partial q_i}\\
   \dot{q}_i = +\cfrac{\partial H}{\partial p_i} \end{cases}$


#### Flujo hamiltoniano
La función diferenciable $\hat{H}$ a través de la ecuación {{eqnref|5}} un campo vectorial continuo sobre toda la variedad simpléctica. Las [[Curva integral de un campo vectorial|curvas integrales]] de este campo vectorial son las trayectorias de las partículas a lo largo del espacio fásico. Esas curvas definen una [[foliación]] unidimensional o flujo hamiltoniano sobre la variedad. De hecho para cada intervalo de tiempo ''s'' se puede definir una aplicación:

$U_s(p(t),q(t)) = (p(t+s),q(t+s))\;$

De hecho la anterior aplicación es una [[transformación canónica]] o [[simplectomorfismo]]. El conjunto $\{U_s:\mathcal{M}\to\mathcal{M}| s\in\mathbb{R}\}$ de todas las aplicaciones anteriores constituye un [[grupo uniparamétrico]] de simplectomorfismos. Si consideramos cualquier magnitud física definida como una función diferenciable sobre la variedad simpléctica, su variación a lo largo de una trayectoria, viene dada por la siguiente derivada temporal:

$$\frac{d}{dt} f=\{f,\hat{H}\} = -(i_{\tilde{\omega}(\mathrm{d}H)}\omega)(\mathrm{d}f)$$

Tal como se demuestra más adelante. De hecho en mecánica estadística se usan [[distribución de probabilidad|distribuciones de probabilidad]] sobre el espacio fásico. Fijada una distribución ρ esta en general "evolucionará" con el tiempo según la ley:

$\frac{d\rho}{dt}  = - \{\rho , \hat{H}\}.$

Esta última expresión se llama [[Teorema de Liouville (mecánica hamiltoniana)#Ecuación de Liouville|ecuación de Liouville]], en particular una distribución tal que el corchete de Poisson con el hamiltoniano se anule se llama '''distribución estacionaria'''.

Cada función diferenciable G, sobre la [[variedad simpléctica]] genera una familia uniparamétrica de [[simplectomorfismo]]s y si {G, H}=0, entonces G se conserva y los simplectomorfismos son transformaciones de simetría.

#### Álgebra de Poisson

A su vez el corchete de Poisson se expresa de modo muy simple en términos de la función inversa de $i_{(\cdot)}\omega$ denotada mendiante $\tilde{\omega}$:


$[F,G] = (i_{\tilde{\omega}(\mathrm{d}F)}\omega)(\mathrm{d}G)\;$

Hay otra generalización que podemos hacer. En vez simplemente de mirar el [[álgebra asociativa|álgebra]] de funciones diferenciables sobre una [[variedad simpléctica]], la mecánica hamiltoniana se puede formular como un álgebra de Poisson [[número real|real]] [[unital]] [[Conmutatividad|comutativa]] general.

En esta formulación alternativa un [[estado (análisis funcional)|estado]] es una [[funcional lineal]] [[Continuidad (matemática)|continua]] en el álgebra de Poisson $\mathcal{A}$, equipada de alguna [[espacio topológico|estructura topológica]] conveniente. Las álgebras de Poisson son importantes en el estudio de [[grupo cuántico|grupos cuánticos]]<ref>[http://arxiv.org/PS_cache/q-alg/pdf/9704/9704002v2.pdf introduction to Quantum groups (inglés)]</ref> usados en la [[teoría cuántica de campos]] conforme, algunos modelos de [[cuantización]] de [[espacio-tiempo]], etc.


## Prueba 1
### 2.1. Sistemas hamiltonianos:
Transformación de Legendre, ecuaciones de Hamilton, espacio de fases, corchetes de Poisson.

### 2.2. Geometría simpléctica:
Forma simpléctica, ecuaciones de Hamilton, flujos hamiltonianos, flujo de un campo vectorial, campos vectoriales hamiltonianos, teorema de Noether, variedades simplécticas, teorema de Darboux y reducción por simetría.

### 2.3. Transformaciones canónicas:
Simplectomorfismos, transformaciones canonoides, función generatriz y tipos de transformaciones canónicas.

### 2.4. Invariantes:
Teorema de Liouville, distribuciones estadísticas, invariante integral de Poincaré, espacio de fases extendido, invariante integral de Poincaré-Cartan y cantidades conservadas.


---

>.

---


# Resultados del aprendizaje

Profundizar en los principios y las técnicas fundamentales del formalismo hamiltoniano de los sistemas dinámicos.

# Breve descripción de contenidos

Formulación hamiltoniana de la Mecánica Clásica. Integrabilidad. Perturbaciones. Introducción al caos.

# Conocimientos previos necesarios

Matemáticas de 1o y 2o del Grado en Físicas. Mecánica Clásica del Grado en Físicas.

# Programa de la asignatura

1. Mecánica lagrangiana
1.1. Dinámica lagrangiana: Espacio de configuración, trayectorias y variaciones infinitesimales, principio variacional, ecuaciones de Euler-Lagrange, características de la acción, ligaduras.
1.2. Cantidades conservadas: Teorema de Noether, coordenadas cíclicas, teorema de Noether, variaciones temporales, energía, partícula en un potencial, invariancia bajo reparametrizaciones temporales, simetrías gauge.
1.3. Dinámica relativista: Acción: Partículas libres y partículas en un campo electromagnético, ecuaciones de movimiento, cantidades conservadas: Cuadrimomento, momento angular cuadridimensional, centro de inercia e invariantes de Casimir.

2. Mecánica hamiltoniana
2.1. Sistemas hamiltonianos: Transformación de Legendre, ecuaciones de Hamilton, espacio de fases, corchetes de Poisson.
2.2. Geometría simpléctica: Forma simpléctica, ecuaciones de Hamilton, flujos hamiltonianos, flujo de un campo vectorial, campos vectoriales hamiltonianos, teorema de Noether, variedades simplécticas, teorema de Darboux y reducción por simetría.
2.3. Transformaciones canónicas: Simplectomorfismos, transformaciones canonoides, función generatriz y tipos de transformaciones canónicas.
2.4. Invariantes: Teorema de Liouville, distribuciones estadísticas, invariante integral de Poincaré, espacio de fases extendido, invariante integral de Poincaré-Cartan y cantidades conservadas.

3. Integrabilidad
3.1. Teoría de Hamilton-Jacobi: ecuación de Hamilton-Jacobi, función principal de Hamilton, soluciones completas, separación de variables, hamiltonianos conservados, coordenadas cíclicas, variables separables, teorema de Huygens y analogía óptica,
3.2. Teoremas de integrabilidad: teorema de Liouville, teorema de Arnold, variables de acción-ángulo, movimiento condicionalmente periódico.

4. Temas de especialización:
4.1. Teoría cláscia de campos
4.2. Perturbaciones
4.3. Caos
4.4. Dinámica de Fluidos



# Bibliografía

## Básica
▪ F. R. Gantmájer, Mecánica Analítica, URSS, 2003.
▪ H. Goldstein, C. Poole, J. Safko, Classical Mechanics, Third Edition, Addison Wesley, 2002.
▪ J. V. José, E. J. Saletan, Classical Dynamics, Cambridge University Press, 1998.
▪ L. Meirovitch, Methods of Analytical Dynamics, Dover Publications, 2010.
▪ E. J. Saletan, A. H. Cromer, Theoretical Mechanics, Wiley, 1971.

## Complementaria
▪ V.I.Arnold,MathematicalMethodsofClassicalMechanics,SecondEdition,Springer-Verlag,1989. ▪ A. F. Fasano, S. Marmi, Analytical Mechanics, Oxford University Press, 2006.
▪ A. J. Lichtenberg, M. A. Lieberman, Regular and Chaotic Dynamics, Second Edition, Springer- Verlag, 1992.
▪ F. A. Scheck, Mechanics: From Newton’s Laws to Deterministic Chaos, Fourth Edition, Springer, 2005.


---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---


# Grupo A

# Tutorias
José Alberto Ruiz Cembranos
M,J: 10:30 – 12:00 (+3 no presenciales)
cembra@fis.ucm.es
Despacho 17 3a Pl. Oeste

Hector Villarrubia Rojo
A determinar
hectorvi@ucm.es
Despacho 1 3a Pl. Oeste


## Evaluacion

Dos trabajos:

### Sobre un tema de la lista

> FECHA DE ENTREGA: 29 Nov

Temas:
- Teoria clasica de campos
- Caos


### Estudiar un hamiltoniano

Son 4 ejercicios:

> 1. 24 Oct
> 2. 24 Nov
> 3. 24 Dic
> 4. 24 Ene


---
>.
---


## Dudas que surgen

- El término de segundo orden en la forma derivada de las ecuaciones de EulerLagrange tiene algo que ver con el jacobiano.

---
>.
---


## Problemas
### Problemas propuestos

- [ ] Probar que las Ecs de EulerLagrange son invariantes bajo transformaciones de coordenadas en el espacio de configuracion. Pista: Usar regla de la cadena.
- [ ]

### Problemas propios

- [ ] Hacer la integral por partes que simplifica la variacion de la accion para obtener las ecs EulerLagrange.
- [ ] Derivar forma completa de las ecuaciones de EulerLagrange.
- [ ] Hacer el paso de simplificar la variacion de coordenadas generalizadas hasta llegar a $\delta \dot{q} '^\alpha = \delta \dot{q}^\alpha - \dot{q} ^\alpha \dot{ \delta t } $
- [ ] Hacer la integral por partes que simplifica la variacion de la accion cuando vemos transformaciones temporales.
- [ ] Hacer la integral por partes que simplifica la variacion de la accion cuando vemos transformaciones temporales (CASO GENERAL).

---
>.
---


## To Do

### Importante

- [ ] Enviar mail para cambio de trabajo: Caos
	- [ ] O buscar otros temas posibles: Catastrofes, bifurcaciones, complejidad, 3 cuerpos
	- [ ] O mirar si el tema que me tocó (teoria clásica de campos) vale la pena para hacerlo.
- [ ]

### Extra

- [ ] Buscar Hamiltonianos por ahi a ver si llego a la lista de 13 que quiere ponernos.
- [ ] Repasar jacobianos
- [ ] Repasar rango de Matriz
- [ ] Repasar metodo multiplicadores de Lagrange
- [ ]


---
>.
>.
>.
> Intervalo Publicitario
>.
>.
>.
---

# Temario

## 0. Roadmap



## 1. Mecánica lagrangiana

### 1.1. Dinámica lagrangiana:
Espacio de configuración,
trayectorias y variaciones infinitesimales,
principio variacional,
ecuaciones de Euler-Lagrange,
características de la acción,
ligaduras.

### 1.2. Cantidades conservadas:
Teorema de Noether,
coordenadas cíclicas,
teorema de Noether,
variaciones temporales,
energía,
partícula en un potencial,
invariancia bajo reparametrizaciones temporales,
simetrías gauge.

### 1.3. Dinámica relativista:
Acción: Partículas libres y partículas en un campo electromagnético,
ecuaciones de movimiento,
cantidades conservadas: Cuadrimomento,
momento angular cuadridimensional,
centro de inercia e invariantes de Casimir.


## 2. Mecánica hamiltoniana

### 2.1. Sistemas hamiltonianos:
Transformación de Legendre,
ecuaciones de Hamilton,
espacio de fases,
corchetes de Poisson.

### 2.2. Geometría simpléctica:
Forma simpléctica,
ecuaciones de Hamilton,
flujos hamiltonianos,
flujo de un campo vectorial,
campos vectoriales hamiltonianos,
teorema de Noether,
variedades simplécticas,
teorema de Darboux y reducción por simetría.

### 2.3. Transformaciones canónicas:
Simplectomorfismos,
transformaciones canonoides,
función generatriz y tipos de transformaciones canónicas.

### 2.4. Invariantes:
Teorema de Liouville,
distribuciones estadísticas,
invariante integral de Poincaré,
espacio de fases extendido,
invariante integral de Poincaré-Cartan y cantidades conservadas.


## 3. Integrabilidad

### 3.1. Teoría de Hamilton-Jacobi:
ecuación de Hamilton-Jacobi,
función principal de Hamilton,
soluciones completas,
separación de variables,
hamiltonianos conservados,
coordenadas cíclicas,
variables separables,
teorema de Huygens y analogía óptica,

### 3.2. Teoremas de integrabilidad:
teorema de Liouville,
teorema de Arnold,
variables de acción-ángulo,
movimiento condicionalmente periódico.


## 4. Temas de especialización:

### 4.1. Teoría cláscia de campos

### 4.2. Perturbaciones

### 4.3. Caos

### 4.4. Dinámica de Fluidos



---
>
>
>
>
Intervalo Publicitario
>
>
>
>
---
