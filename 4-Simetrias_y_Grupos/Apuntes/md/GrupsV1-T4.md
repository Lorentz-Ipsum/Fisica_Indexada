<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> 

#  Grupos y álgebras de Lie

Un grupo de Lie combina tres estructuras matemáticas diferentes. Verifica:


    - Los axiomas de grupo.
    - Los elementos de grupo forman un espacio topológico (grupo topológico).
    - Los elementos del grupo forman una variedad analítica.


De este modo vemos que un grupo de Lie puede analizarse de formas diferentes. No los estudiaremos aquí de forma exhaustiva de forma topológica pues los grupos de Lie que se utilizan más en física son los grupos de Lie lineales. Tienen propiedades adicionales que nos permiten analizarlo mediante métodos más sencillos.

### Elementos básicos sobre espacios topológicos

Un espacio topológico S es un conjunto no vacío de elementos llamados puntos para los cuales hay una correlación $\mathds{T}$ de subconjuntos, llamados conjuntos abiertos, que satisfacen:


    - El conjunto vacío $\phi$ y el conjunto S pertenecen a $\mathds{T}$.
    - La unión de conjuntos de $\mathds{T}$ pertenece a $\mathds{T}$.
    - La intersección de un número finito de conjuntos de $\mathds{T}$ pertenece a $\mathds{T}$.
    - La colecció de $\mathds{T}$ se llama topología.
    - Los complementarios a esos conjuntos se llaman conjuntos cerrados.


#### Compacidad

Una familia de conjuntos abiertos de un espacio topológico S es un recubrimiento abierto de S si la unión de sus conjuntos abiertos contiene a S. Si por cada recubrimiento abierto de S siempre hay un recubrimiento finito que contiene a S (es decir, unión de un número finito de abiertos), el espacio topológico S se dice que es compacto. En caso contrario se dice que es no compacto.

#### Conexion

Un espacio topológico es conexo si no es la unión de dos conjuntos abiertos disjuntos no vacíos (que no tiene agujeros). Como consecuencia los únicos subconjuntos de S conexo que son a la vez abiertos y cerrados son solo el vacío y el propio S (si S es conexo).

\smallskip
Un \textbf{camino} en S desde $X_0$ a $X_1$  es un mapa continuo  $\phi: [0,1]\in \mathds{R}\to S$ con $\phi (0)=x_0,\phi (1)=x_1$. Si los puntos son idénticos y los valores del mapa en esos puntos son iguales se dice que el camino es cerrado (\textit{loop}). Dos caminos cerrados son equivalentes u homotópicos si uno puede llebar al otro mediante deformaciones continuas. Todos los loops equivalentes forman una clase de equivalencia.


    - S es \textbf{arco-conexo} si dados dos puntos de S cualesquiera siempre existe un camino con $\phi (0)=x_0$ y $\phi (1)=x_1$.
    
    - S arco-conexo es \textbf{simplemente conexo} si todo camino cerrado se puede encoger a un punto con deformaciones contínuas.
    
    Si hay n clases de equivalencia distintas de caminos cerrados entonces S se dice n-veces conexo.


\textbf{Ejemplos:}


    - Una región X del espacio euclídeo $\mathds{R}^n$ es compacto solo si es finita.
    - El espacio $\mathds{R}^2$ es simplemente conexo, regiones suyas con agujeros no lo son.

 
 #### Mapa homeomórfico
 
 Dados dos espacios topologicos (S,T) y (S',T'), un mapa de S en S' se dice contínuo en S si para todo abierto de S' la imagen inversa del mapa es un abierto de S. Si el mapa $\phi , \phi ^{-1}$ es contínuo entonces esta aplicación es un homeomorfismo y S y S' son homeomorfos.
 
 \smallskip
 Las propiedades topológicas son invariantes bajo homeomorfismos, también llamados invariantes topológicos.
 
 #### Espacio Hausdorff
 
 Un espacio topológico (S,T) es Hausdorff si dos puntos cualquiera de S pertenecen a subconjuntos abiertos de T disjuntos (axioma de separabilidad).
 
 Un espacio localmente euclídeo de dimensión n es un espacio topológico Hausdorff tal que cada uno de sus puntos está contenido en un conjunto abierto que es homeomorfo a un subconjunto de $\mathds{R}^n$.
 
 
 #### Carta
 Sea V un abierto de dicho espacio y $\phi$ un homeomorfismo de V en un subconjunto de $\mathds{R}^n$ entonces para cada punto de V $p\in V$ existe un conjunto de coordenadas ($x_1,x_2,..,x_n$) tal que $\phi (p)= (x_1,x_2,..,x_n) $. El par $(p, \phi)$ se llama \textbf{carta}.
 
 #### Variedad analítica de dimensión n
 
 Consideremos un espacio localmente euclídeo de dimensión n y tal que posee una base numerable (una base de la topología T es un subconjunto $B \in T$ de abiertos tal que cualquier conjunto abierto es unión de elementos de B) y un homeomorfismo de un abierto $V \subset \mathcal{V}$ en un subconjunto de $\mathds{R}^n$.
 
 \smallskip
 Si para cada par de cartas $(V_\alpha , \phi _\alpha)$ y $(V_\beta , \phi _\beta)$ del subgrupo $\mathcal{V}$ con intersección no vacía, el mapa $\phi _\beta \o \phi _\alpha ^{-1}$ es una función analítica, entonces $\mathcal{V}$ es una variedad analítica de dimensión n (como por ejemplo $\mathds{R}^n$).
 
 ### Grupo de Lie, definición.
 
 Un grupo de Lie de dimensión n es un conjunto de elementos que satisfacen las siguientes condiciones:
 
 
- Forman grupo.
- Forman una variedad analítica de dimensión n.
- El mapa $\begin{array}{cc}
    \phi: \hspace{0.2cm} G\times G \to G  \\
(g_1,g_2)\to \phi (g_1g_2)=g_1g_2
\end{array}$ es analítico para todo $g_1,g_2 \in G$.
- Este mapa es también analítico (es infinitamente diferenciable; esta dado localmente por una serie de potencias convergente).
 
 
La característica básica de un grupo de Lie es que tiene un número no contable de elementos dentro de una región $\textit{cercanos}$ a la identidad y la estructura de estos elementos determina esencialmente la estructura del grupo completo.

\smallskip
Los elementos de dicha región estarán parametrizados de manera analítica y debemos tener una noción de distancia.

En el caso de grupos de Lie lineales existe una representación natural que permite una definición de distancia precisa, que permite asegurar que el resto de requerimientos topológicos se verifican.

   ### Grupos de Lie lineales

Un grupo G es un grupo lineal de Lie de dimensión n si satisface las cuatro coniciones siguientes:


   - G posee una representación matricial D que es fiel y de dimensión finita m.
    
    Definimos la distancia entre dos elementos $g,g'\in G$ como:
    
    $$d(g,g')=\sqrt{\sum _{i,j=1}^m |D(g)_{ij}-D(g')_{ij}|^2}$$
    
    y el conjunto de matrices D(g) satisface las condiciones de espacio métrico.
    
    El conjunto $\lbrace g_i\rbrace$ con $g_i \in G$ tal que $d(g_i,e)<\delta$, con $\delta \in \mathds{R}^+$. Se dice que esta en una bola de radio $\delta$ centrada en la identidad e y denotada por $M_s$ que a veces llamaremos entorno de e.
    
    - Existe un real positivo tal que los elementos de $M_s$ se pueden parametrizar (de modo diferente) por n parámetros reales independientes ($x_1,...,x_n$) con e correspondiente a $x_1,...,x_n=0$.
    
    Cada elemento de $M_s$ se corresponde con un único punto de $\mathds{R}^n$ que se corresponde con más de un elemento $g_i\in M_s$.
    
    - Existe un real $\epsilon >0$ tal que cada punto de $\mathds{R}^n$ para el que se cumpla $\sum _{i=1}^n x_1^2 < \epsilon ^2$ se corresponde con algún elemento de $g_i \in M_s$ y la correspondencia es uno a uno.
    
    - Sea $D(g(x_1,...,x_n))$ la matriz de representación del elemento $g(x_1,...,x_n)\in G$. Entonces cada elemento de matriz de D es una función analítica de ($x_1,...,x_n$) para todo punto de $\mathds{R}^n$ que satisfaga la condición anterior.
   


  \textbf{Nota:} Todo grupo de Lie lineal es isomorfo a algún subgrupo del grupo general lineal de matrices de dimensión adecuada.

\smallskip
Cada grupo de Lie lineal se dice \textbf{conexo} si el espacio topológico que forman sus elementos es conexo. Análogamente puede ser simplemente conexo o múltiplemente conexo.

#### Recubridor universal

Si G es un grupo de Lie multiplemente conexo existe un grupo $\Tilde{G}$ simplemente conexo (único salvo isomorfismos) tal que G es isomorfo al grupo cociente $\Tilde{G}/Z(\Tilde{G})) \hspace{0.2cm} \left [ Z(\Tilde{G})=\lbrace h\in \Tilde{ G} | hg=gh  \hspace{0.2cm} \forall g  \in \Tilde{G} \rbrace\right]$ o alguno de sus subgrupos.

$\Tilde{G}$ se llama el recubridor universal de G.

\smallskip
Un grupo de Lie se dice \textbf{compacto} si su espacio topológico es compacto.

#### Representaciones unitarias del grupo de Lie


    - Si G es un grupo de Lie compacto, toda representación de G es equivalente a alguna unitaria.

- Si G es un grupo de Lie compacto toda representación reducible de G es completamente reducible (completamente descomponible).

- Si G es un grupo de Lie no compacto, entonces no posee representaciones unitarias de dimensión finita no triviales.

#### Ejemplos
    
    
   -    $GL(n,\mathds{C})$: grupo general lineal de matrices complejas M con det M$\neq$ 0 de dimensión 2$n^2$.
   
   - $SL(n, \mathds{C})$: grupo especial lineal, subgrupo del general con detM=1 de dimensión 2$n^2$ -2 (pues el determinante da dos restricciones; Re(detM)=1 y Im(detM)=0).
   
   - GL($n,\mathds{R}$): de dimensión $n^2$.
   
   - $SL(n,\mathds{R})$: de dimensión $n^2-1$.
   
   - El grupo $U(n)$: grupo unitario de matrices complejas U tal que $U^+U=UU^+=\mathds{1}^n$ de dimensión $n^2$ (en principio es subgrupo de GL pero la condición de conmutación nos quita la mitad).
   
   - SU(n): grupo especial unitario, subgrupo de U(n) que agrupa las matrices con detU=1, de dimensión $n^2-1$ (como el det U es un complejo de fase libre y norma 1 solo pone 1 condición sobre el detU).
   
   - O(n): grupo ortogonal de matrices reales que cumplen $OO^+=O^+O=\mathds{1}_n$ de dimensión $\frac{n(n-1)}{2}$.
   
   - SO(n): grupo ortogonal especia, subgrupo de O(n) con detO=1, de la misma dimensión que O(n).
   
   - Sp(n): grupo simpléptico, grupo de matrices unitarias (n $\times$ n) con n par. Satisfacen $U^T J U=J$. La matriz J$=\left (\begin{array}{cc}
  0 & \mathds{1}_{n/2} \\
  -\mathds{1}_{n/2} & 0
   \end{array} \right )$ de dimensión $\frac{n(n+1)}{2}$.
   
   - U(l,n-l): grupo pseudo-unitario de matrices complejas U que satisfacen $UgU^+=g$ siendo g una matriz diagonal de unos y menos unos de forma que $g_{kk}=1$ para $1 \leq k \leq l$ y $g_{kk}=-1$ para $ l+1 \leq k \leq n$. LA dimensión es $n^{2}$
   
   - O(n,l-n): grupo pseudo-ortogonal de matrices reales con $OgO^+=g$ con la misma g, de dimensión $\frac{n(n-1)}{2}   $. Es el grupo de Lorentz, la g es una pseudo-métrica.
   
   
  - Compactos: U(n), SU(n), O(n), SO(n), Sp(n).
  
  - No compactos: GL(n), SL(n), U(n,l-n), O(n,l-n.)
   


#### Ejercicio: ¿Son O(n) y U(n) grupos conexos?

O(n) está formado por rotaciones y reflexiones luego no es conexo; sus dos subconjuntos son: rotaciones (subgrupo) y reflexiones (que no es subgrupo pues $(det=-1)^2 \neq -1$). Consiste en dos componentes disjuntas SO(n) (rotaciones) y la componente con det=-1 (reflexiones).

\smallskip
U(n) por otra parte sí es conexo (es decir no es la unión de conjuntos abiertos disjuntos) pues las fases se pueden parametrizar de forma continua para que tome todos los valores complejos unitarios.

\subsubsection{Ejercicio: ¿Son SO(2)$\simeq $
U(1) y SU(2) simplemente conexos?}

Cualquier elemento de SO(2) puede escribirse como $\mathcal{R}= \left ( \begin{array}{cc}
    a &  -b\\
    b & a 
\end{array}\right)$ con $a^2+b^2=1$. Es decir, escrita como variedad diferencial, SO(2) es el círculo unidad. Vemos pues que SO(2) no es simplemente conexo (no se puede reducir el círculo a un punto sin cortarlo).

\bigskip
Ahora para SU(2) tenemos que deben cumplir $|a|^2+|b|^2=1$ siendo ahora a,b $\in \mathds{R}$ y la matriz $\mathcal{R}= \left ( \begin{array}{cc}
    a &  b\\
    -\bar{b} & \bar{a} 
\end{array}\right)$. Así que los U (elementos de SU(2)) pueden identificarse con un punto (x,y,z,w) $\in \mathds{R}^4$ siendo $a=(x,y)$ y $b=(z,w)$. Deberán satisfacer: $x^2 +y^2 + z^2 + w^2=1$ (ecuación de la 3-esfera o hiperesfera de dimensión 4). La 3-esfera es simplemente conexa al ser la generalización de la esfera. Las curvas sobre la esfera pueden '' achicarse '' a un punto sin salirse de la esfera no como con el círculo. Las únicas esferas que son grupos de Lie son la 1-esfera (círculo) y la 3-esfera (por cuestiones de restricciones topológicas).

#### Ejercicio: justificar por qué el grupo SO(1,1) no es compacto

Pista: SO(1,1) es isomorfo a los reales con la operación de suma.

#### Ejercicio: Acabamos de ver que SO(2) $\simeq$ U(1) $\simeq S^1$  no es simplemente conexo. ¿Qué grupo es su recubridor universal? Buscar el grupo normal de G (H) tal que $S^1 \simeq G/H$ (el grupo cociente es el círculo).

Pista: la dimensión de $S^1$ es 1. Su recubridor universal tendrá también dimensión 1.

### Medida de integración invariante

Dada una función definida en G con valores complejos f: $\begin{array}{c}
    G \to \mathds{C}  \\
g \to f(g)
\end{array}$ tenemos que si G es un grupo finito (por el teorema del reordenamiento) podemos escribir:

$$\sum _{g\in G} f(gg')=\sum _{g\in G} f(g)=\sum _{g\in G} f(gg')$$

decimos que la suma es invariante por la izquierda e invariante por la derecha respectivamente.

\smallskip
Además, para grupos de Lie (análogamente a lo que ocurría con los grupos finitos) si f(g)=1 $\forall g \in G$, la suma es finita:

$$\sum _{g \in G} 1 =|G|$$

Para grupos de Lie lineales la suma se puede sustituir por una integral que también va a ser invariante por la izquierda y por la derecha.

$$\int _G f(g)d_lg=\int ^{b_1}_{a_1} dx_1...\int ^{b_n}_{a_n} dx_n f(g(x_1,...,x_n))\sigma _l(x_1,...,x_n)$$

Donde $\sigma _l$ es una función peso que hace que la integral sea invariante por la izquierda. Análogamente se haría para que fuera invariante por la derecha:

$$\int _G f(g)d_rg=\int ^{b_1}_{a_1} dx_1...\int ^{b_n}_{a_n} dx_n f(g(x_1,...,x_n))\sigma _r(x_1,...,x_n)$$

Si multiplico por g' por la izquierda a la primera o por g' por la izquierda a la segunda las integrales no cambian.

$$\int _G f(g'g)d_lg=\int _G f(g)d_lg \hspace{1cm} \int _G f(gg')d_rg=\int _G f(g)d_rg=$$

Esto provoca una restricción en las funciones peso que las hace únicas salvo constante.

\bigskip

    - \textbf{Teorema:} si G es un grupo de Lie compacto entonces podemos asegurar que $\sigma _r=\sigma_l=\sigma$. La integral invariante que define, $\int _G f(g)d g$, es por tanto igual por la izquierda que por la derecha. Además existe (converge) y es finita para toda función f(g) continua. Podemos escoger $\sigma$ (que era única salvo constante) para que $\int _G dg=\int ^{b_1}_{a_1} dx_1...\int ^{b_n}_{a_n} dx_n \sigma (x_1,...,x_n)=1$. La medida así definida la llamamos \textbf{medida de Haar} (única e invariante por izquierda y derecha).
    
    - \textbf{Teorema:} si G es un grupo de Lie no compacto las medidas invariantes por la izquierda y la derecha son infinitas (y por tanto no tiene sentido definir la medida de Haar). Por ejemplo, en el círculo las medidas son:
    
    $$\int ^{2\pi}_0 d\theta f(\theta) \to \int ^{2\pi}_0 d\theta f(\theta +\phi)= \int ^{2\pi + x}_{0+x} d\Tilde{\theta} f(\Tilde{\theta})$$
    
    donde multiplicando por la derecha lo que hacemos es sumar por la derecha. Para que sea medida de Haar basta con normalizarla:
    
    $$\int ^{2\pi}_0 d \theta \frac{1}{2\pi}$$
    
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTA0NTI1OTc5LDE1Njc5OTg4MDYsLTIxMz
M1MTI0NTQsLTExNjc5NzI1MzJdfQ==
-->