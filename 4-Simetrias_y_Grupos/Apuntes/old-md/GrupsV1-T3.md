<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> 

# Representación de grupos
### Acciones de grupo
Cuando un grupo actúa sobre un espacio vectorial, se obtiene una representación.

Antes de estudiarlas veamos qué es la acción de un grupo sobre un conjunto genérico X. Las biyecciones de este conjunto X forman un grupo, el grupo simétrico de X o sym(X). Notar que si X es finito y contiene n elementos el grupo de biyecciones es sym(X)=$S_n$.

\smallskip
Una \textbf{acción de grupo} es un homomorfismo de G en sym(X).

$$\begin{array}{c}
G \to sim(X)  \\
g\to gx \hspace{0.1cm} \forall x\in X
\end{array}$$

Se suele escribir como multiplicación por la izquierda en lugar de $f_g(X)$. Automáticamente vemos que se satisface que $(gh)x=g(hx)$ y $ex=x$.

\smallskip
\textbf{Ejemplos}:

\smallskip
Algunos grupos se definen por su acción:


    - El grupo simétrico $S_n$ actúa en el conjunto de n elementos.
    - El grupo euclídeo actúa en el espacio afín $\mathds{R}^n$.
    - El grupo ortogonal actúa en la esfera unidad $S^{n-1}$.
    - Cualquier otro grupo actúa sobre sí mismo de dos maneras: por multiplicación por la izquierda $h\to hg$ (o por la derecha $h \to gh$) o por conjugación $h \to ghg^{-1}$.
    

La acción del grupo presenta varias \textbf{propiedades}:


    - La acción es fiel si el homomorfismo es isomorfismo.
    - La acción es transitiva si $\forall x,y\in X \hspace{0.1cm}\exists \hspace{0.1cm} g\in G \hspace{0.1cm}/ \hspace{0.1cm} gx=y$.
    - La acción es libre si $gx=x \to g=e$.
    - La acción es regular si es transitiva y libre.


\textbf{Definición (1)}: si la accion no es fiel, los elementos de grupo que dejan todos los elementos de X invariantes forman un subgrupo.

$$N= \left \lbrace g \in G, \hspace{0.1cm} gx=x \hspace{0.2cm} \forall x \in X \right \rbrace$$

\textbf{Definición (2)}: fijado un punto $x\in X$ entonces su órbita es el conjunto de imágenes.

$$Gx=\left \lbrace gx \hspace{0.1cm} / g\in G \right \rbrace$$

\textbf{Definición (3)}: inversamente, el estabilizador (o grupo pequeño) es el conjunto de elementos del grupo que dejan X invariante.

$$G_x=\left \lbrace g\in G  \hspace{0.1cm}/ \hspace{0.1cm} gx=x \right \rbrace$$

$\hspace{0.5cm}$ \textbf{Teorema órbita-estabilizador:} Dado un punto x la órbita $Gx$ está en correspondencia uno a uno con el conjunto de cosets por la izquierda del estabilizador.El mapa $gx \hspace{0.1cm}/\hspace{0.1cm} gG_x$ es un isomorfismo $|Gx|=\frac{|G|}{|G_x|}$.

$$gx/gG_x \simeq |Gx| =\frac{|G|}{|G_x|}$$

\newpage
### Representaciones lineales

La multiplicación (o composición) de transformación lineal sobre un espacio vectorial es básicamente una multiplicación de grupo. Un conjunto de trasformaciones lineales invertibles cerrado con respecto a la multiplicación satisface los axiomas de grupo. Tal conjunto forma un grupo de representaciones lineales o grupo de operadores. 

#### Representación de grupo G

Si existe un homomorfismo de un grupo G a un grupo de operadores D(G) en un espacio vectorial V

$$D(G): \hspace{0.1cm} G\to GL(V)$$

decimos que D(G) es una forma de representación lineal de G.


    - La dimensión de la representación es la dimensión del espacio vectorial V (consideramos dim(V)$<\infty$ y $V\in \mathds{C}$ aunque muchos resultados se pueden generalizar a dimensión infinita).
    - Una representación se dice fiel si el homomorfismo es isomorfismo. Si no es fiel es degenerada. Siendo más específicos, una representación lineal de G en el espacio vectorial V es una aplicación de D que a cada elemento de $g\in G$ le asocia un operador invertible: 
    
    $$D(G): \hspace{0.1cm} V \hspace{0.2cm} \to V \hspace{0.1cm}\text{de forma que } \hspace{0.1cm} D(gh)=D(g)D(h)\hspace{0.1cm} \forall g,h \in G$$


#### Terminología
G actúa sobre V (via D). Los elementos de V se transforman bajo la representación de:


    - Representación matricial.
    
    $$V=\mathds{C}^n\to GL(V)=GL(n, \mathds{C})$$
- Representación n-dimensional. 

Equiparamos aplicaciones lineales $A: \hspace{0.1cm} \mathds{C}^n \to  \mathds{C}^n$ con su matriz en la base canónica de $\mathds{C}^n$. La multiplicación de grupo se traduce a multiplicacción matricial.

$$\begin{array}{cc}
D: \hspace{0.1cm}G \to GL(n, \mathds{C}) \\
g\to D(g)_{ji} 
\end{array}$$
    
    Actúa sobre la base $\lbrace \Vec{e}_i\rbrace_{i=1,...,n}$ de $\mathds{C}^n$.


\textbf{Ejemplos}:


    - Todo grupo posee una representación 1-dimensional trivial. Sea $V=\mathds{C}$ y $D(g)=1$, $\forall \hspace{0.1cm} g$; claramente $D(g_1)D(g_2)=1\cdot 1=1=D(g_1g_2)$.
    - Los grupos matriciales $GL(n,\mathds{C})$ y subgrupos de este tienen de forma natural la representación por ellos mismos. Esta represetación se llama representación de definición. 
    - Sea G un grupo de matrices, $V\in \mathds{C}$ y $D(g)=det(g)$ esto define una representación 1-dimensional no trivial ya que $det(g_1)det(g_2)=det(g_1g_2)$.
    - Recordamos que para cualquier real $\xi$ el intervalo $(-\pi, \pi]$ los números $\lbrace e^{-in\xi}; \hspace{0.1cm} n=0,\pm 1, \pm 2... \rbrace$ forman una representación del grupo e traslaciones discretas en una dimensión espacial.


 \smallskip
    \textbf{Ejercicio:} sea $G=S^1 \cong U(1)$ demostrar que la aplicación 
    
    $$\begin{array}{cc}
    D: S^1 \to GL(2,\mathds{C})  \\
    e^{i\theta} \to D(e^{i\theta})= \left (\begin{array}{cc}
 cos \theta   & -sen \theta  \\
 sen \theta   & cos \theta
    \end{array} \right )=R( \theta), \hspace{0.1cm} \theta \in \mathds{R}
    \end{array}$$
    
    es una representación de $S^1$. Lo mismo para:
    
$$\begin{array}{cc}
    D: S^1 \to GL(3,\mathds{C})  \\
    e^{i\theta} \to D(e^{i\theta})= \left (\begin{array}{ccc}
 cos \theta   & -sen \theta  & 0\\
 sen \theta   & cos \theta & 0 \\
 0 & 0 & 1
    \end{array} \right )=R( \theta), \hspace{0.1cm} \theta \in \mathds{R}
    \end{array}$$
    
    
   -    D está bien definida: $e^{i\theta} =e^{i\theta '} \leftrightarrow \theta =\theta ' + 2\pi k \hspace{0.1cm} k\in \mathds{Z} \to R(\theta)=R(\theta ')$.
    

 -  Respeta la estructura de grupo $D(e^{i\theta _1}e^{i\theta _2})=R(\theta _1 +\theta _2)=R(\theta _1)R(\theta _2)^=D(e^{i\theta _1})D(e^{i\theta _2})$.
    
   - Además es una representación fiel pues $D(e^{i\theta _1})=D(e^{i\theta _2})\leftrightarrow \theta _1=\theta _2 +2k\pi \hspace{0.1cm} \forall k\ic \mathds{Z} \leftrightarrow e^{i\theta _1}=e^{i\theta _2}$.
    
    La $3\times 3$ lo cumple también pues cumple todo lo anterior.
    
   
    
    \bigskip
    \textbf{Proposiciones:}
    
    
   - Si el subgrupo normal H de G existe, entonces cualquier representación del grupo cociente también es una representación de G (esta es necesariamente degenerada).
   - Toda representación no trivial de un grupo simple es fiel.
    
    
    \textbf{Ejercicio:} da una representación no trivial de $S_3 / A_3$ y demuestra que es una representación no fiel de $S_3$.
    
    \bigskip
    $S_3/A_0 \simeq C_2=\lbrace e,a \rbrace$ tal que $a^2=1$. Una representación del grupo cociente sería $D(e)=1$, $D(a)=-1$; esto nos genera la tabla de multiplciación:
    
    $$\begin{tabular}[b]{ c | c c }

 & e & a  \\
\hline
e & e & a  \\
a & a  & e  \\

\end{tabular}  $$

$$S_3 = \lbrace e,\sigma _1, \sigma _2 , \tau _1, \tau _2, \tau _3 \rbrace \hspace{0.2cm} A_3=\lbrace e, \sigma _1, \sigma _2 \rbrace \hspace{0.2cm} S_3/A_3 = \lbrace A_3, \tau _1 A_3 \rbrace$$

Es decir,

$$\begin{array}{cc}
    D(e)=1 & D(\tau _1)=-1 \\
   D(\sigma _1)=1  & D(\tau _2)=-1 \\
   D(\sigma _2)=1 & D(\tau _3)=-1
\end{array}$$

Por ello esta representación nos recupera la tabla de multiplicar, porque $\tau _1 \tau _j=\sigma _k$, donde $i,j,k=1,2$. Pero a cada elemento de salida le corresponden varios elementos de entrada, por lo que la representación no es fiel.

### Representación conjugada y contragradiente


    - Si $D:\hspace{0.1cm} G \to GL(n, \mathds{C})$ es una representación matricial de G y la aplicación

$$\begin{array}{cc}
\Bar{D}: \hspace{0.1cm} G \to GL(n \mathds{C})  \\
 g \to \Bar{D}(g)=\overline{D(g)}
\end{array}$$

es también representación de G y se llama compleja conjugada.
- La aplicación 

$$\begin{array}{cc}
    \Tilde{D}: \hspace{0.1cm} G\to GL(n, \mathds{C})  \\
g \to \Tilde{D}(g)=(D(g)^t)^{-1}
\end{array}$$

es también representación de G y se llama representación contragradiente.

    
    ### Equivalencia de representaciones
    Dos representaciones D(G) y D'(G) de un grupo de G en un espacio vectorial V. Son equivalentes si están relacionadas a través de una transformación de similaridad. Es decir, si existe un operador lineal invertible:
    
    $$A: \hspace{0.1cm} V\to AVA^-1$$
    $$D'(G)=AD(G)A^{-1}$$
    
    $\hspace{0.5cm}$ \textbf{Ejemplo:} una representación 1-dimensional solo puede ser equivalente a sí misma pues A conmuta y por tanto $D'(G)=D(G)AA^{-1}=D(G)$.
    
    Lo mismo ocurre con las representaciones de dimensión n cuyas matrices son proporcionales a la matriz unidad de orden n.
    
    #### ¿Cómo podemos decir si dos representaciones son equivalentes o no?
    
    Para contestar habrá que buscar caracterizaciones de la representación que sean invariantes bajo transformaciones de similaridad. Por ejemplo, la traza nos ayuda a definir el carácter de la representación. 
    
    \smallskip
    Definimos el \textbf{carácter de una representación} $\mathcal{X} (g)$ de $g\in G$ en la representación D(G) es la función:
    
    $$\begin{array}{cc}
    \mathcal{X}^D: \hspace{0.1cm} G \to \mathds{C} \\
    g \to \mathcal{X}^D(g)=Tr(D(g))
    \end{array}$$
    
    Debido a la propiedad cíclica de la traza ($Tr(D(g))=Tr(AD'(g)A^{-1})=Tr(D'(g))$), si tengo dos representaciones equivalentes la traza es independiente de la representación.
    
    \smallskip
    \textbf{Propiedades:}
    
    
   - Dos representaciones equivalentes tienen el mismo carácter.
   - El carácter es una función de clase, esto significa que toma el mismo valor para todos los elementos del grupo que viven en la misma clase de conjugación.
   
   $$\mathcal{X}(g)=\mathcal{X}(hgh^{-1})$$
   
   - El carácter de la identidad es la dimensión del espacio.
   
   $$Tr(\mathds{1}_N)=N=dim V$$
    
    
    ### Representaciones reducibles e irreducibles
    
    \textbf{Espacio invariante;} sea $D(G)=\lbrace D(g_1),...,D(g_n) \rbrace$ una representación del grupo G en el espacio vectorial V. Decimos que $V_1 \subset V$ es un subespacio invariante con respecto a la representación D(G) si la representación me deja $V_1$ invariante.
    
    $$\begin{array}{cc}
    D(g)v_1\subset V_1 \hspace{0.5cm} \forall \hspace{0.1cm} g \in G, \hspace{0.1cm} \forall \hspace{0.1cm} v_1\in V_1  \\
    D(G)V_1 \subset V_1
    \end{array}$$
    
    Dos espacios invariantes triviales son el mismo V y $\lbrace \Vec{0}\rbrace \in V$.
    
    
   - Decimos que una representación D(G) en V es irreducible si V no contiene ningún subespacio invariante (no trivial) bajo D(G). En caso contrario es reducible.
   
   \textbf{Ejemplo:} toda representación 1-dimensional es irreducible pues un espacio vectorial de dim=1 no tiene subespacios propios.
   
   - Una representación D(G) reducible es descomponible si V se puede descomponer como suma directa de dos subespacios no triviales (propios) invariantes bajo la acción de la reprsentación.
   
   Si es suma direta se descompone en la suma de un espacio y su complemento ortogonal. Tiene sentido descomponer la representación en dos acciones, cada una sobre uno de estos dos espacios.
   
   $$V=V_1 \oplus V_2\hspace{0.6cm} \forall v \in V, \hspace{0.1cm} v=v_1+v_2 \hspace{0.1cm} \text{de forma única}$$
   
   $$D(G)=D_1(G)\oplus D_2(G) \hspace{0.1cm} \text{con} \hspace{0.1cm} D_i(G) \hspace{0.1cm} \text{restricción de} D(G) \hspace{0.1cm} \text{a} \hspace{0.1cm} V_i$$
   $$D_i(G)V_i=D(G)V_i\subset V_i$$
   
   - Una representación D(G) descomponible es \textbf{completamente reducible} si se descompone en suma directa de representaciones irreducibles.
   
   $$\begin{array}{cc}
   V=V_1 \oplus V_2 \oplus ... V_m  \\
   D= D_1\oplus D_2 \oplus ... D_m
   \end{array} \hspace{0.1cm} \text {con} \hspace{0.1cm} D_1(G)V_i=D(G)Vi \subset V_i \hspace{0.1cm} \forall i=1,...,m$$
   
   Se dice que $D_i(G)$ es irreducible en $V_i$. Matricialmente:
    
    $$D(G)=\left ( \begin{array}{cccc}
   D_1(g) & 0 & 0 & 0  \\
   0 & D_2(g) & 0 & 0 \\
   0 & 0 & ... & 0 \\
   0 & 0 & 0 & D_m(g)
    \end{array} \right ) \hspace{0.1cm} \forall g \in G$$
    
    
    
    \textbf{Ejercicio:} sea G=($\mathds{C},+$) y sea la aplicación $D(z)=\left ( \begin{array}{cc}
   1 & z \\
   0 & 1
    \end{array} \right ) \hspace{0.1cm} \forall z\in \mathds{C}$. Demostrar que D es una representación reducible de G. ¿Es descomponible?
    
    \bigskip
    Será una representación si cumple los siguientes puntos:
    
    
   - La identidad es z=0
   
   $$D(z=0)=\left ( \begin{array}{cc}
  1 &  0\\
  0 & 1
   \end{array} \right )$$
   
   -  ($\mathds{C},+$) el inverso de z es -z (opuesto), se puede comprobar sin más que multiplicar que:
   
   $$D(-z)=(D(z))^{-1}$$
   
   - $D(z_1)D(z_2)=D(z_1+Z_2)$
   
   $$\left ( \begin{array}{cc}
  1 & z_1 \\
  0 & 1
   \end{array}\right)\left ( \begin{array}{cc}
  1 & z_2 \\
  0 & 1
   \end{array}\right)=\left ( \begin{array}{cc}
  1 & z_1 +z_2 \\
  0 & 1
   \end{array}\right)=D(z_1+z_2)$$
    
    
    Por otra parte 
    
    $$D: \hspace{0.1cm} (\mathds{C},+)\to GL(2, \mathds{C}) \to V=\mathds{C_2}=lin \lbrace \Vec{e}_1,\Vec{e}_2\rbrace$$
    
    Es reducible ya que $W= lin \lbrace \left ( \begin{array}{c}
    1  \\
    0 
    \end{array}\right) \rbrace$ es invariante bajo $D(z)\hspace{0.1cm} \forall z \in \mathds{C}$.
    
    $$\left ( \begin{array}{cc}
   1 & z \\
   0 & 1
    \end{array}\right) \left( \begin{array}{c}
    a  \\
    0 
    \end{array}\right)=  \left( \begin{array}{c}
    a  \\
    0 
    \end{array}\right)$$
    
    \smallskip
    Por último, ¿es descomponible? Deben ser invariantes W y su complemento ortogonal $W^\bot =lin \lbrace \Vec{e}_2 \rbrace$.
    
    $$\left ( \begin{array}{cc}
   1 & z \\
   0 & 1
    \end{array}\right) \left( \begin{array}{c}
    0  \\
    1 
    \end{array}\right)=  \left( \begin{array}{c}
    z  \\
    1 
    \end{array}\right) \notin W^\bot \hspace{0.1cm} \text{si} \hspace{0.1cm} z\neq 0$$
    
    
    Por lo que no es descomponible pues no lo es $\forall z$.
    
    \newpage
    #### Suma directa de representaciones
    
    Dadas dos representaciones actuando sobre espacios vectoriales distintos $D_i: \hspace{0.1cm} \to GL(V_i)\hspace{0.1cm} i=1,2$ podemos formar la suma directa $D_1\oplus D_2$ actuando sobre $V_1 \oplus V_2$.
    
    $V_1 \oplus V_2$ se entiende como el espacio de pares ($v_1,v_2$) tal que $v=v_1+v_2 \in V \hspace{0.1cm} \text{con} \hspace{0.1cm} v_i\in V_i$ sobre los que actúan la representación combinada como:
    
    $$(v_1,v_2)\to (D_1(g)v_1,D_2(g)v_2)$$
    
    Esto define una representación (que por construcción es reducible y descomponible pues se construye a partir de dos cosas descompuestas a priori) de mayor dimensión $dim (D_1\oplus D_2)=dim (D_1)+dim (D_2)$.
    
    $$(D_1 \oplus D_2)(g)=\left (\begin{array}{cc}
   D_1(g) & 0 \\
   0 & D_2(g)
    \end{array} \right)$$
    
    Matriz que representa a g en las bases de $V_1$ (fila 1) y $V_2$ (fila 2) respectivamente.
    
    ### Unitariedad 
    
    Dado un espacio vectorial V con producto escalar, una representación de un grupo $D: \hspace{0.1cm} G \to GL(V)$ se denomina \textbf{unitaria} si $D(g)$ es un operador lineal unitario $\forall g \in G$.
    
    $$D(g)D(g)^{+}=D(g)^{+}D(g)=\mathds{1}_{V}, \hspace{0.1cm} \forall g\in G$$
    
    Esto es lo mismo que decir que, tomando el producto escalar de dos vectores es V, el producto escalar no cambia bajo la aplicación de la representación sobre dichos vectores:
    
    $$(u,v)=(D(g)u,D(g)v)\hspace{0.1cm} \forall u,v\in V$$
    
    \smallskip
    Por ejemplo, en el caso $V=\mathds{C}^n: \hspace{0.5cm} D(g)\in U(n), \hspace{0.1cm} \forall g\in G$.
    
    \smallskip
    Las representaciones unitarias son de gran importancia para los físicos a la hora de estudiar simetrías. Por ejemplo, en mecánica cuántica es necesario medir los observables a través de una representación que mantenga los productos escalares invariantes.
    
    \bigskip
    $\hspace{0.5cm}$ \textbf{Propiedad fundamental:} si una representación unitaria es reducible es completamente reducible. 
    
    Sea $W \subset V$ un espacio invariante tal que $D(g)W\subset W, \hspace{0.2cm} \forall g\in G; \hspace{0.3cm} V=W\oplus W^\bot$. Sea $v\in W^\bot$ y $u\in W$, entonces:
    
    $$(u, D(g)v)=(D^+(g)u,v)=(D^{-1}(g)u,v)=(\underbrace{D(g^{-1})u}_{\in W},\underbrace{v}_{\in W^\bot})=0$$
    
    Luego $D(g)v\in W^\bot \to W^\bot$ invariante $\to$ D es descomponible.
    
    \smallskip
    Falta demostrar que es irreducible.
    Si la dimensión de D es 1 entonces es irreducible y por tanto completamente irreducible. Si dimD fuera mayor que 1 se puede demostrar por inducción que $D=D_1\oplusD_2 \oplus ... \oplus D_m$ se puede escribir como suma directa de irreducibles.
    
    \bigskip
    $\hspace{0.5cm}$ \textbf{Teorema de Schur-Auerbach:} toda representación D(g) de un grupo finito G sobre un espacio vectorial V con producto escalar es equivalente a una representación unitaria.
    
    \textit{La demostración del teorema la omito pues llegué tarde a clase}.
    
    
    \bigskip

    $$D'(g)=T^{-1}D(g)T \hspace{0.2cm} \text{Representación equivalente a D(g), unitaria respecto al producto escalar de partida}$$
    
    La demostración del teorema se hace para grupos finitos pues se necesita que la suma de elementos converja. El producto escalar $\bra{-}\ket{-}$ no existe en general. No obstante para grupos de Lie compactos veremos que existe una única medida dg invariante bajo la acción del grupo (a esta medida se le llama medida de Haar). Se puede hacer el cambio suma-integral, siendo esta integral convergente debido a la compacidad del grupo y por tanto la prueba sigue siendo válida.
    
    \newpage
    Para grupos de Lie no compactos, sus representaciones fieles de dimensión finita nunca son unitarias. No obstante, algunos grupos no compactos pueden tener representaciones unitarias con respecto a algún producto escalar no definido positivo.
    
    \smallskip
    
    Por ejemplo, el grupo de Lorentz, cuya representación de definición es finita y unitaria con respecto al producto escalar de Minkowski.
    
    \bigskip
    
    $\hspace{0.5cm}$\textbf{Teorema de Maschke:} todas las representaciones de un grupo finito o un grupo no finito pero compacto son completamente reducibles (pues las unitarias lo son). Basta con estudiar sus representaciones irreducibles.
    
    ### Lemas de Schur (1905)
    
    Antes de los lemas de Schur enunciaremos otro lema:
    
    \smallskip
    Sea $D: G\to GL(V)$ y $D': G \to GL(V')$ dos representaciones de G y sea el operador lineal $A: V\to V'$ que entrelaza ambas representaciones.
    
    $$AD(g)=D'(G)A \hspace{0.2cm} \forall  \hspace{0.1cm} g\in G$$
    
    Los subespacios ker(A) y A(V) son invariantes bajo D(G) y D(G') respectivamente.
    
    \smallskip
    \textbf{Demostración 1:} si $v\in$ ker(A), $A(D(G)v)=D'(G)(Av)=0\longrightarrow D(G)v\in$ ker(A) $\forall  \hspace{0.1cm} g\in G$.
    
    \smallskip
    \textbf{Demostración 2:} si $v'=Av\in A(V)$, $D'(G)v'=D'(G)(Av)=A(D(G)v)\in$ A(V) $\forall g\in V$
    
    #### Lemas de Schur
    
    Sean D y D' las representaciones de antes, representaciones matriciales y, por hipótesis, irreducibles; y el operador A que las entrelaza. Entonces se verifica:
    
    
   - Si la dim(D)$\neq$ dim(D'), entonces A=0 forzosamente (no se pueden entrelazar más allá de la forma trivial). Por eso cuando estudiábamos representaciones equivalentes consideramos que V' era isomorfo a V.
   
   - Si dim(D)=dim(D') entonces o bien A=0 o bien A es un isomorfismo en cuyo caso D es equivalente a D'.
   - Si D=D', es decir, $AD(G)=D(G)A$ $\forall  \hspace{0.1cm} g\in G$ entonces A=$\lambda \mathds{1}$ (multiplo de la identidad). En otras palabras, si D es una representación irreducible de un grupo G y A es un operador que conmuta con todos los operadores D(g) de la representación entonces no nos queda otra más que A sea múltiplo de la identidad.
    
    
    \smallskip
    
    \textbf{Proposición:} sea $D: G\to GL(V)$ una representación de un grupo G que es finito o compacto y supongamos que los únicos operadores lineales de V en V que conmutan con todos los operadores D(g) son los múltiplos de la identidad. Entonces D es irreducible.
    
    \smallskip
    \textbf{Proposición:} una represemtación de un grupo abeliano es irreducible si y solo si es unidimensional.
    
    \smallskip
    \textbf{Corolario:} Todas las representaciones irreducibles de un grupo abeliano finito o compacto son unitarias.
    
    \newpage
    \textbf{Ejercicio:} consideremos el grupo cíclico de tres elementos $C_3$ cuya tabla de multiplicar es:

 $$\begin{tabular}[b]{ c | c c c}

 & e & a & a^2  \\
\hline
e & e & a & a^2 \\
a & a & a^2 & e  \\
a^2 & a^2 & e & a
\end{tabular}  $$    

Una representación de este grupo es $D: C_3\to GL(3, \mathds{C})$:

$$D(e)=\left (\begin{array}{ccc}
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
\end{array} \right )  $$
    
Como no es unidimensional y el grupo es abeliano ha de ser reducible, además por los teoremas de Maschke y los lemas de Schur podemos afirmar que es completamente reducible. Es decir, se puede descomponer en la suma directa de 3 representaciones irreducibles unidimensionales y unitarias.
    

\smallskip
Para ello observamos que los autovalores de D(a) son $\lbrace 1,e^{\frac{2\pi i}{3}}, e^{\frac{4\pi i}{3}}\rbrace$ y que por tanto existe $T\in GL(3,\mathds{C})$ (matriz de cambio de base) que me diagonaliza D(a).
    
    $$D(a)=T\left ( \begin{array}{ccc}
    1 & 0 & 0 \\
    0 & e^{\frac{2\pi i}{3}} & 0 \\
    0 & 0 & e^{\frac{4\pi i}{3}}
    \end{array}\right )T^{-1}$$

Y que también me diagonaliza $D(a^2)$ al ser simplemente el cuadrado de D(a):

$$D(a^2)=T\left ( \begin{array}{ccc}
    1 & 0 & 0 \\
    0 & e^{\frac{2\pi i}{3}} & 0 \\
    0 & 0 & e^{\frac{4\pi i}{3}}
    \end{array}\right )T^{-1} \hspace{0.2cm} T\left ( \begin{array}{ccc}
    1 & 0 & 0 \\
    0 & e^{\frac{2\pi i}{3}} & 0 \\
    0 & 0 & e^{\frac{4\pi i}{3}}
    \end{array}\right )T^{-1}=T\left ( \begin{array}{ccc}
    1 & 0 & 0 \\
    0 & e^{\frac{4\pi i}{3}} & 0 \\
    0 & 0 & e^{\frac{2\pi i}{3}}
    \end{array}\right )T^{-1}$$
    
    \smallskip
    Denotemos por $v_k$ a los autovectores de D(a), $T=(v_0 |v_1 | v_2)$ de modo que $D(a)v_k=e^{\frac{2\pi i k}{3}} v_k$.
    
    \smallskip
    Se tiene que $\mathds{C}^3=V_0\oplus V_1 \oplus V_2$ siendo $V_k=lin\lbrace v_k \rbrace$ invariante bajo D. 
    
    $$D(a)=I_0 \oplus \left ( e^{\frac{2\pi i}{3}}I_1\right) \oplus \left( e^{\frac{4\pi i}{3}}I_2\right) \hspace{0.2cm} \text{con} \hspace{0.1cm} I_k \hspace{0.1cm} \text{la identidad en} \hspace{0.1cm} V_k$$
    
    Este espacio es isomorfo a $D^{(0)}\oplus D^{(1)}\oplus D^{(2)}$ con $D^{(k)}(a^j)=e^{\frac{2\pi jk}{3}}$
    
    \bigskip
    \textbf{Ejercicio:} dada la representación del grupo bidimensional
    
    $$\begin{array}{cc}
    D: S^1 \to DL(2, \mathds{C})  \\
    e^{i\Theta}\to D(e^{i\Theta})= \left (\begin{array}{cc}
  cos \theta  & -sen \theta  \\
  sen \theta  & cos \theta
    \end{array}\right )
    \end{array}$$
    
    encontrar un operador A que conmute con $\mathds{R}(\theta)$ y que no sea la identidad (tal A existe pues D no es irreducible en $V=\mathds{C}$). Encontrar los subespacios de $\mathds{C}^2$ invariantes bajo D y descomponer D en suma directa de representaciones irreducibles.
    
    \bigskip
    
    Pista, los autovectores de un D concreto son autovectores de todos los Ds, es decir son subespacios de todos los Ds.
    
    \bigskip
    Un ejemplo de matriz que conmuta con R($\theta$) es A=$\left (\begin{array}{cc}
   0 & -1 \\
   1 & 0
    \end{array} \right)$
    
    Autovalores de R($\theta$), su polinomio carácterístico es $1-2\lambda +\lambda ^2=0$. Sus autovalores son entonces:
    
    $$\lambda_\pm =e^{\pm i\theta}$$
    
    Sus subespacios propios son W=lin $\left \lbrace \left ( \begin{array}{c}
    1  \\
    \pm i 
    \end{array}\right) \right\rbrace $.  Por ello, P= $ \frac{1}{\sqrt{2}}\left ( \begin{array}{cc}
    1 & 1 \\
    -i & i
    \end{array}\right) $ de modo que:
    
    $$R(\theta)=P\left( \begin{array}{cc}
   e^{i\theta} & 0 \\
   0 & e^{-i\theta}
    \end{array}\right)P^{+} \to D(e^{i\theta})=D_+(e^{i\theta})\oplus D_-(e^{-i\theta})$$
    
    donde $D_+(e^{i\theta})=e^{i\theta}\mathds{1}$ y $D_-(e^{-i\theta})=e^{-i\theta}\mathds{1}$.
    
    ### Relaciones de ortonormalidad y completitud
    
    Sea un grupo finito o compacto y sean $D^{(\rho)}(G)=\lbrace D^{(1)}(G), D^{(2)}(G)\rbrace$ sus representaciones irreducibles inequivalentes (y que podemos tomar unitarias) etiqueadas por el índice discreto $\rho$, con dimensión dim D$^{(\rho)}(G)$=$d_\rho <\infty$.
    
    Sea $D^{(\rho)}(G)$ la matriz en una base ortonormal que representa a $g\in G$ en la representación $D^{(\rho )}(G)$. Estas matrices cumplen la relación de ortonormalidad:
    
    $$\text{G finito:} \hspace{0.3cm} \frac{1}{|G|}\sum _g D_{ij}^\rho (g) \bar{D}_{i'j'}^{\rho '}(g)=\frac{1}{d \rho}\delta _{\rho , \rho '}\delta _{i, i'}\delta _{j,j'}$$
    
    $$\text{G compacto:} \hspace{0.3cm} \frac{1}{v(G)}\int _G d\mu (g) D_{ij}^{(\rho )} (g) \bar{D}_{i'j'}^{ (\rho ')}(g)=\frac{1}{d\rho}\delta _{\rho , \rho '}\delta _{i, i'}\delta _{j,j'}$$
    
    donde v(G) es el volumen del grupo (si este es compacto). Estas relaciones se pueden usar para construir representaciones irreducibles a partir de otras repreentaciones ireducibles conocidas.
    
    \smallskip
    
    \textbf{Ejemplo:} consideremos el grupo de Klein $V_4=C_2 \times C_2$ de elementos $\lbrace e, \rho , \sigma , \tau \rbrace $, que es abeliano con $\sigma ^2 = \rho ^2 = \tau ^2 =e^2 =e$, $\sigma \rho = \tau$ subgrupos normales que nos permiten definir el grupo cociente:
    
    $$V_4/V_\sigma \cong \frac{V_4}{V_\tau}\cong V_4/V_\rho \cong C_2 $$
    
    $$\begin{array}{c}
    V_\sigma =\lbrace e, \sigma \rbrace \cong C_2  \\
    V_\tau = \lbrace e, \tau \rbrace \cong C_2 \\
    V_\rho = \lbrace e, \rho \rbrace  \cong C_2
    \end{array}$$
    
    \smallskip
    Consideramos por ejemplo $V_4/V_\sigma =\lbrace \lbrace e, \sigma \rbrace , \lbrace e, \tau \rbrace \rbrace$.
    \bigskip
    
    Construyamos representaciones irreducibles de $V_\sigma $ y con ellas las de $V_4$. La más fácil es la representación trivial $D^{(1)}=D^{(1)}(e)=1$, $D^{(1)}(\sigma)=1$.
    
    \smallskip
    La relación de ortonormalidad para $\rho =1$ y $\rho '=2$ implica:
    
    $$D^{(1)}(e)D^{(2)}(e)+D^{(1)}(\sigma)D^{(2)}(\sigma)=0 \to D^{2}(e)=1, D^{(2)}(\sigma)=-1$$
    
    Por consiguiente, al ser ambos grupos isomorfos:
    
    $$V_4/V_\sigma =\lbrace eV_\sigma, \tau V_\sigma \rbrace =\lbrace E, \Sigma \rbrace; \hspace{0.5cm} E=\lbrace e, \sigma \rbrace; \Sigma = \lbrace e, \tau \rbrace$$
    
    $$D^{(1)}(E)=1, \hspace{0.2cm} D^{(1)}(\Sigma)=-1, \hspace{0.2cm} D^{(2)}(E)=1, \hspace{0.2cm} D^{(2)}(\Sigma)=-1, \hspace{0.2cm}$$
    
    $$D^{(1)} \hspace{0.1cm} \text{de} \hspace{0.1cm} V_4/V_\sigma \to D^{(1)}(e)=1, D^{(1)}(\rho)=1, D^{(1)}(\tau)=1, D^{(1)}(\sigma)=1$$
    
    $$D^{(2)} \hspace{0.1cm} \text{de} \hspace{0.1cm} V_4/V_\sigma \to D^{(2)}(e)=1, D^{(2)}(\rho)=-1, D^{(2)}(\tau)=-1, D^{(2)}(\sigma)=1$$
    
    Y lo mismo para $V_4/V_\sigma$ y $V_4/V_\tau$.
    
    \newpage
    Se puede ver que estas representaciones para $V_4$ verifican que las relaciones de ortonormalidad son las únicas permitidas por tales relaciones:
    
    $$\begin{tabular}[b]{ c | c c c c }

g/w & e & \sigma & \rho & \tau \\
\hline
1 & 1 & 1 & 1 & 1 \\
2 & 1 & 1 & -1 & -1 \\
3 & 1 & -1 & 1 & -1 \\
4 & 1 & -1 & -1 & 1
\end{tabular}  $$
    
    Las matrices de representación cumplen la siguiente relación de completitud:
    
    $$\text{G finito:} \hspace{0.3cm} \frac{1}{|G|}\sum _\rho d\rho \sum _{ij} \underbrace{D_{ij}^{(\rho)}\bar{D}_{ij}^{(\rho ')}(g')}_{\mathcal{X}^{(\rho)}(gg'^{-1})}=\delta _{\rho, \rho '}$$
    
    Se tiene para grupos finitos, haciendo g=g':
    
    $$\sum _\rho d\rho ^2 =|G|^2$$
    
    Y para grupos compactos:
    
$$\text{G compacto:} \hspace{0.3cm} \frac{1}{v(G)}\sum _\rho d\rho \sum _{ij} \underbrace{D_{ij}^{(\rho)}\bar{D}_{ij}^{(\rho ')}(g')}_{\mathcal{X}^{(\rho)}(gg'^{-1})}=\delta (g,g')$$
    
    donde $\delta (g,g')$ es la delta de Dirac adaptada a la medida de Haar del grupo
    
    $$f(g')=\int _G d\mu (g)\delta (g,g')f(g)$$
    
    Por tanto, esta relación de completitud nos dice que cualquier función $f: G \to \mathds{C}$ continua o de cuadrado sumable (integrable) puede expandirse en funciones $D^{(\rho)}_{ij}(g)$.
    
    \smallskip
    \textbf{Teorema de Peter-Weyl:}
    
    $$f(g)=\sum _{g'}\delta _{g,g'}f(g')=\sum _{\rho,i,j}D_{ij}^{(\rho)}(G)\sum _g \frac{1}{|G|}D_{ij}^{(rho)}^{+}(g')f(g')=\sum _{\rho ,i, j} d\rho D_{ij}^{(\rho)}(g)f_{ij}^{(\rho)}$$
    
    \smallskip
En el caso en el que G=$S^1\cong U(1)$ recuperamos la descomposición de Fourier:

$$\int _G d \mu (G)=\int ^{2\pi}_0 d\theta$$
    
    #### Representaciones de ortonormalidad y completitud con caracteres
    
    Mientras que las matrices de representación dependen de la base escogida los caracteres no lo hacen y además no cambian dentro de la misma clase de conjugación. Por tanto es más útil expresar las relaciones de ortonormalidad y completitud en función de estos caracteres.
   
    $$\text{G finito:} \hspace{0.3cm} \frac{1}{|G|}\sum _g\mathcal{X}^{(\rho)}(g)\mathcal{X}^{(\rho ')}(g)=\delta _{\rho , \rho '}$$
    
    $$\frac{1}{|G|}\sum _{i=1}^m |e_i|\mathcal{X}_i^{(\rho)}(g)\bar{\mathcal{X}}_i^{\rho '}(g')=\delta _{\rho , \rho '}$$
    
    donde m es el numero de clases de conjugación, $|e_i|$ es el número de elementos en la clase $e_i$ y $\mathcal{X}_i^{(\rho)}$ el caracter de la representación.
    
    \textbf{Se tiene que el numero de representaciones irreducibles equivalentes es el número de clases de conjugación.}
    
$$\text{G compacto:} \hspace{0.3cm} \frac{1}{v(G)}\int _G d\mu (g) \mathcal{X}^{(\rho)}(g)\mathcal{X}^{(\rho ')}(g)=\delta _{\rho , \rho '}$$
    
    $$\frac{1}{v(G)}\sum _\rho d\rho \mathcal{X}_i^{(\rho)}\bar{\mathcal{X}}_i^{\rho '}(g')=\delta ({g,g')$$
   
  #### Tabla de caracteres:
  
  \smallskip
  $\mathcal{X}_i^{(\rho)}$ con $\rho $=1,...,m y i=1,...,m puede usarse como una matriz o tabla cuadrada con $\rho$ el índice de la fila e i el de la columna.
  
  \smallskip
  
  \textbf{Ejemplo:} Para grupos abelianos cada elemento del grupo forma una clase por si mismo y todas las representaciones irreducibles son unidimensionales. De este modo, las tablas $D^{(\rho)}(g)$ también son tablas de caracteres.
\smallskip
    
    \textbf{Consecuencias}(de las propiedades de los caracteres):
    
    
   - Debido a que cualquier representación es totalmente reducible, $D= \oplus _\rho m_\rho D^{(\rho)}$, el carácter se puede descomponer según:
   
   $$\mathcal{X}=\sum _{\rho} m_\rho \mathcal{X}^{(\rho)}$$
   
   Las multiplicidades vienen dadas a partir de los caracteres como:
   
   $$m_\rho =\frac{1}{|G|}\sum _i |e_i|\mathcal{X}\bar{\mathcal{X}}_i^{(\rho)}=\frac{1}{v(G)}\int _G d_\mu (g)\mathds{X}(g)\Bar{\mathcal{X}}^{(\rho)}(g)$$
   
   - También es cierto que:
   
   $$||\mathcal{X}||^2=\frac{1}{|G|}\sum _g|\mathcal{X}(g)|^2=\sum _\rho m_\rho ^2$$
   
   y una representación es irreducible si y  solo si  $||\mathcal{X}||^2=1$.
   
   - Dos representaciones de un grupo finito o compacto son equivalentes si y solo si tienen los mismos caracteres.
   
   - \textbf{Peter Weyl}: cualquier función de clase se puede expandir en caracteres irreducibles (una función es de clase si es invariante bajo conjugación).
   
    
    
    ### Producto tensorial de representaciones y coeficientes de Clebsch-Gordan
    
    Un método habitual para construir representaciones irreducibles de un grupo dado consiste en construir el producto tensorial de representaciones conocidas y descomponerlo en irreducibles.
    
    #### Tensores
    
    Dados dos espacios vectoriales $V_1$ y $V_2$ podemos formar su producto directo o producto tensorial $V_1 \otimes V_2$.
    
    Dadas bases $\lbrace v_i\rbrace _{i=1}^{dim V_1}$ y $\lbrace w_j\rbrace _{j=1}^{dim V_2}$ de $V_1$ y $V_2$ respectivamente, entonces una base de $V=V_1 \otimes V_2$ está dada por el conjunto de pares ordenados $\lbrace v_i \otimes W_j \rbrace$ es decir los vectores de V son todas las combinaciones lineales de los elementos de la base de la forma:
    
    $$\sum _{i=1}^{d_1=dim V_1}\sum _{j=1}^{d_2=dimV_2} a^{ij}(v_i\otimes w_j)=a^{ij}(v_i \otimes w_j)$$
    
    donde en el último paso utilizamos el criterio de suma de índices repetidos. Están caracterizados por las componentes:
    
    $$a^{ij}=\left ( \begin{array}{ccc}
   a^{11} & ... & a^{1d_2} \\
   ... & ... & ... \\
   a^{d_11} & ... & a^{d_1d_2}
    \end{array}\right) \hspace{0.2cm} \text{tensor de rango 2 (puede entenderse como una matriz)}$$
    
    \smallskip
    
    Es posible generalizar esta definición para tensores de mayor rango. Claramente:
    \begin{center}
    dimV=dim$V_1 \cdot $ dim $V_2$.
    
    \end{center}
    
    \textbf{Nota:} si agrupamos índices $(i,j)=k$ con k=1,...,$d_1d_2$ podríamos llamar $a^{ij}=a^k$
    
    #### Producto tensorial de operadores
    
    Dados dos operadores $D_1$ y $D_2$ actuando sobre los espacios $V_1$ y $V_2$ respectivamente, podemos definir su producto tensorial actuando sobre $V_1 \otimes V_2$ como:
    
    $$(D_1\otimes D_2)(v\otimes w)=D_1v \otimes D_2w  \hspace{0.1cm} \in V_1 \otimes V_2$$

Usando los elementos de matriz $(D_1)^j_i$, $(D_2)^m_l$ (índices abajo son fila e índices arriba son columna) de estos operadores en sus respectivas bases podemos obtener los elementos de matriz del producto tensorial $D_1 \otimes D_2$ en la base $\lbrace v_i\otimes w_j \rbrace$.

$$(D_1 \otimes D_2)^{nm}_{ij}=(D_1)^j_i (D_2)^m_l$$

La acción de $(D_1\otimes D_2)$ sobre V entonces viene dada por:

$$D_1 \otimes D_2: \hspace{0.2cm} a^{ij} (v_i\otimes w_j) \to ((D_1 \otimes D_2)^{ij}_{nm}a^{nm})v_i\otimes w_j$$
    
    $$a^k \to (D_1\otimes D_2)^ka^N \hspace{0.2cm} \text{Regla usual de transferencia de vectores}$$
    
#### Producto tensorial de representaciones

Sean $D_1$ y $D_2$ representaciones de un grupo G sobre los espacios vectoriales $V_1$ y $V_2$ el producto tensorial $D_1 \otimes D_2$ da lugar a otra representación de G de dimension D= dim $D_1 \cdot$ dim $D_2$.

\smallskip
\textbf{Propiedad:} el carácter en la representación producto tensorial es el producto de los caracteres en cada una de las representaciones de partida.

$$\mathcal{X}_D(g)=\mathcal{X}_{D_1}(g)\mathcal{X}_{D_2}(g)$$

#### Descomposición de Clebsch-Gordan

EL producto tensorial de dos representaciones irreducibles D y D' en general no es irreducible; sí es completamente irreducible (como es el caso para representaciones unitarias). De este modo podemos llevar a cabo la descomposición en suma directa de irreducibles o descomposición de Clebsch-Gordan.  

$$D\otimes D'=\oplus _j D_j$$

siendo $D_j$ representaciones irreducibles y $\oplus _j$ indica suma directa de los j elementos.

\smallskip
Si G es finito o compacto y clasificamos con un índice discreto $\rho$ sus representaciones irreducibles inequivalentes, entonces tendremos:

$$D^{(\sigma)}\otimes D^{(\tau)}=\uplus _\rho m_\rho ^{\sigma \tau} D^{(\rho)}$$

donde $m_\rho ^{\sigma \tau}$ es la multiplicidad de $D^{(\rho)}$ en esta descomposición.

$$m_\rho ^{\sigma \tau} =\frac{1}{|G|} \sum _g \mathcal{X}^{(\sigma)}(g)\mathcal{X}^{(\tau)}\bar{\mathcal{X}}^{(\rho)}(g)$$

$$\mathcal{X}^{(\sigma)}(g)\mathcal{X}^{(\tau)}= \sum _\rho m_\rho ^{\sigma \tau}\mathcal{X}^{(\rho)}$$

$$dimD^{(\sigma)}dim D^{(\tau)}=\sum _\rho m_\rho ^{\sigma \tau} dimD^{(\rho)}$$
    
O bien en vez de la suma a los $g_s$ la integral $\frac{1}{v(G)}\int _G d_\mu (g)$ si el grupo es compacto.

\smallskip
\textbf{Proposición:} la representación trivial aparece en el producto $D_^{(\sigma)}\otimes D^{(\tau)}$ si y solo si $D^{(\tau)}= \bar{D}^{\sigma}$.

\smallskip
\textbf{Ejercicio:} dada la representación irreducible unitaria $D^{(2)}$ de $S_3$, construye $D^{(2)}\otimes D^{(2)}$ y descomponlas en suma directa de representaciones irreducibles (recordar que eran: la identidad, $D^{(0)}$; la paridad $D^{(1)}$ y la que teniamos que contruir para el ejercicio $D^{(2)}$).

$$D^{(2)}\otimes D^{(2)}=m_{(0)}D^{(0)}+m_{(1)}D^{(1)}+m_{(2)}D^{(2)}$$

\textbf{Ejercicio:}
    
    \smallskip
    Tabla de caracteres de $S_3$:
    
    \smallskip
    $S_3$ tiene 3 clases de conjugación: $C_1=\lbrace e \rbrace, C_2= \lbrace \tau _3=(12),\tau _1=(23), \tau _1=(31)\rbrace, C_3=\lbrace \sigma _1=(123),\sigma _2=(321)$. Tiene por tanto tres representaciones irreducibles no equivalentes.
    
    
   - La trivial, que siempre existe $D^{(0)}$ (unidimensional).
   
   $$\mathcal{X}^{(1)}_1=1 \hspace{0.2cm} \mathcal{X}^{(1)}_2=1 \hspace{0.2cm} \mathcal{X}^{(1)}_3=1 \hspace{0.2cm}$$
   
   - $S_3/A_3 \cong C_2$ tiene una representación fiel (asignar a un elemento el 1 y a otro el -1) llamada representación paridad $D^{(1)}$.
   
   $$D^{(1)}(e)=D^{(1)}(\sigma _1)=D^{(1)}(\sigma _2)=1$$
   
   $$D^{(1)}(\tau _1)=D^{(1)}(\tau _2)=D^{(1)}(\tau _3)=-1$$
   
   $$\mathcal{X}^{(1)}_1=1 \hspace{0.2cm}\mathcal{X}^{(1)}_2=-1 \hspace{0.2cm}\mathcal{X}^{(1)}_3=1 \hspace{0.2cm}$$
   
    - Nos falta saber los caracteres de la tercera representaión irreducible $D^{(2)}$. Primero calculamos su dimensión:
    
    $$|G|=\sum  _\rho d_\rho ^2 \to 6=1+1+d_{(2)}^2 \to d^2_{(2)}=4$$
    
    Luego la tercera representación es bidimensional (matrices 2 $\times$ 2).
    
    $$D^{(2)}(e)= \left ( \begin{array}{cc}
  1 1 & 0 \\
   0 & 1
    \end{array} \right); \hspace{0.5cm} \mathcal{X}_1^{(2)}=2$$
    
    No conocemos sin embargo el resto de $D^{(2)}(g)$.
    
    $$\begin{tabular}[b]{ c | c c c  }
 & G_1 & G_2 & G_3 \\
\hline
\mathcal{X}^{(0)} & 1 & 1 & 1 \\
\mathcal{X}^{(1)} & 1 & -1 & 1  \\
\mathcal{X}^{(2)} & 2 & x & y 
\end{tabular}$$
    
    De las relaciones de completitud:
    
    $$\frac{|e_i|}{|G|}\sum _\rho \mathcal{X}_i^{(\rho)}\Bar{\mathcal{X}}_j^{(\rho)}=\delta _{ij}$$
    
    $$0=1\cdot 1+1(-1)+ 2x \to x=0$$
    $$0=1\cdot 1+1\cdot 1 +2y \to y=-1$$
    
    Podrian haberse utilizado las relaciones de ortonormalidad:
    
    $$\frac{1}{|G|}\sum _{i=1}^m |e_i|\mathcal{X}_i^{(\rho)}\mathcal{X}_i^{(\rho ')}=\delta _{\rho , \rho '}$$
    
    $$0=1\cdot 2+3\cdot 1\cdot x+2\cdot 1\cdot y; \hspace{0.3cm} \rho =(0), \rho '=(2)$$
    $$0=1\cdot 2-3\cdot 1\cdot x +2 \cdot 1\cdot y; \hspace{0.3cm} \rho =(1),\rho '=(2)$$
    $$x=0, \hspace{0.2cm} y=-1$$
    
    
    \textbf{Ejercicio:} construir la representación bidimensional irreducible y unitaria de $S_3$.
    
    
    \newpage
    
    #### Coeficientes de Clebsch-Gordan
La descomposición de CG describe como se descomponen las matrices de representación en representaciones irreducibles bajo la acción de un grupo. También es importante saber como se descomponen los vectores del espacio vectorial de representación.

Sea $\lbrace v_\alpha (\sigma)\rbrace^{dim D(\sigma)}_{\alpha =1}$ una base ortonormal de vectores del espacio $V_\tau$ sobre el que actúa $D^{(\sigma)}$. Queremos expandir el producto tensorial

$$V_i^{(\sigma)}\otimes V_J^{(\rho)}=\sum _\tau \sum _k ...V_k^{(\tau)}$$

Como la representación $D^{(\tau)}$ podrá aparecer $m_\tau \rho ^\sigma$ veces introducimos un índice extra $a=1,..., m_\tau \rho ^\sigma$ tal que:

$$V_i^{(\rho)}\otimes V_j^{(\sigma)}=\sum _{\tau , a, k}C_{\rho , i, \sigma, j | \tau, a, k}V_k^{(\tau)}$$
    
En notación Dirac:

$$\ket{\rho, i, ,\sigma , j}\equiv \ket{\rho, i} \otimes \ket{\sigma , j}=\sum _{\tau , a,k}\bra{\tau , a, k}\ket{\rho, i,  \sigma ,j } \ket{\tau , a, k}$$

Los coeficientes de CG se obtienen por identificación:

$$C_{\rho , i, \sigma, j | \tau, a, k}=\sum_{\tau , a,k}\bra{\tau , a, k}\ket{\rho, i,  \sigma ,j } $$


\textbf{Ejercicio:} calcularlos para $D^{(2)}\otimes D^{(2)}$

\smallskip
Si las representaciones son unitarias y las bases se eligen ortonormales, los coeficientes de CG cumplen las relaciones de ortogonalidad y por tanto:


    $$\sum_{\tau , a,k}\bra{\tau , a, k}\ket{\rho, i,  \sigma ,j } \cdot \underbrace{\bra{\rho, i',  \sigma ,j '}}_{\text{Complejo conj}} \ket{\tau , a, k}=\delta _{i,i'}\delta _{j,j'}$$
    
  $$\sum_{\tau , a,k}\bra{\tau , a, k}\ket{\rho, i,  \sigma ,j } \cdot {\bra{\rho, i,  \sigma ,j }}} \ket{\tau ' , a', k'}=\delta _{a,a'}\delta _{\tau,\tau '}\delta _{k, k'}$$
  
  
  Y podemos invertir la relación original
  
  $$\ket{\tau, a, k}=\underbrace{\sum _{ij} \bra{e,i, \sigma , j} \ket{ \tau , a ,k}}_{\text{Coeficiente conj.}} \underbrace{\ket{e,i,\sigma ,j}}_{Prod. espacios}$$
  
 ### Teorema de Wigner-Eckart
  
  
 - \textbf{Conjunto de operadores tensoriales irreducibles.}
 
 Sean $V_\rho$ y $V_\sigma$ espacios vectoriales con producto escalar y $D^{(\rho)}$, $D^{(\sigma)}$ representaciones irreducibles de un grupo G sobre dichos espacios respectivamente. Sea Q: $V_\rho \to V_\sigma$ un operador lineal ( $Q \in L(V_\rho ,C_\sigma)$) de modo que  $Qv\in V_\sigma \hspace{0.2cm} \forall v\in V_\sigma$.
 
 El conjunto de tales operadores forma un espacio vectorial con suma $(Q_1+Q_2)V=Q_1v+Q_2v$, producto escalar complejo $(aQ)v=a(Qv)$ y cero $0v=\Vec{0}$. Si las dimensiones de $V_\sigma, V_\rho$ son $d_\sigma, d_ \rho$, la dimensión de este nuevo espacio L es $d_ \sigma d_\rho$.
 
 Definamos ahora, para cada $g\in G$ un operador D'(g) que actúa en L de la siguiente forma:
 
 $$D'Q=DQD^{-1} \hspace{0.2cm}\forall Q\in L$$
 
 Entonces D' es un operador lineal y dados $g_1, g_2 \in G$ se tiene:
 
 $$D'(g_1)D'(g_2)=D'(g_1g_2); \hspace{0.4cm} (g_1g_2)^{-1}=g_1^{-1}g_2^{-1}$$
 
 Por tanto, el conjunto de operadores D' da lugar a una representación de G sobre el espacio vectorial L, en general reducible.
 
 Supongamos que D'(G) es completamente reducible y que $D^{(\tau)}$ es una representación de las representaciones irreducibles que aparece en su reducción. Sea $\lbrace Q_1,Q_2,...,Q_{d_\tau}\rbrace$ una base del subespacio correspondiente de L donde actúa $D^{(\tau)}$. Entonces:
 
 $$D'Q_i=\sum _{j=1}^{d_\tau} D_{ji}Q_j \hspace{0.2cm} \forall i=1,..., d_\tau$$
 
 y por la definición dada de D':
 
 $$DQ_iD^{-1}=\sum _{j=1}^{d_\tau} D_{ji}Q_j \hspace{0.2cm} \forall i=1,..., d_\tau$$
 
 este conjunto $\lbrace Q_i\rbrace$ de operadores se llama conjunto de operadores tensoriales irreducibles de la representación $D^{(\tau)}$ de G.
  
  
  \smallskip
  \textbf{Teorema de Wigner-Eckart:}

\smallskip
Sea G finito o compacto, sean $D^{(\sigma)}, D^{(\tau)}$ y $D^{(\rho)}$ representaciones unitarias irreducibles de G de dimensiones $d_\sigma,d_\tau, d_\rho$ respectivamente y sean $\lbrace v_i^{\sigma}\rbrace, \lbrace v_i^{\rho}\rbrace $ dos bases ortonormales asociados a sus respectivos espacios $V_\sigma, V_\rho$ sobre los que están definidas estas representaciones unitarias.

Finalmente, sea $\lbrace Q_k^{(\tau)}_{k=1}^{d_\tau}$ un conjunto de operadores irreducibles de $D^{(\tau)}$. Entonces:

$$(V_j^{(\sigma)}, V_k^{(\tau)}, V_i^{(\rho)})=\sum _{a=1}^{m_\sigma ^{\rho \tau}} \bar{C}_{\rho, i, \tau ,k | \sigma , a, j}\cdot (\sigma || Q^{(\tau)}||\rho)_a$$

donde el último término forma un conjunto de $m^{\rho \tau}$ (elementos de matriz reducidos) que son independientes de i,j y k.

Este teorema muestra que la dependencia en estos índices de las cantidades $(V_j^{(\sigma)}, V_k^{(\tau)}, V_i^{(\rho)})$ está completamente recogida en los coeficientes de CG y que la totalidad del conjunto $D_\sigma d_\rho d_\tau$ que forman depende solo de $m^{\rho \tau}_\sigma$ elementos de matriz reducidos.

\smallskip
\textbf{Nota:} se puede generalizar para mucgos grupos no compactos, como grupos de Lie semisimples con representación finita o con representación unitaria de dimensión infinita.
Las reglas de selección atómicas salen de aplicar este teorema al grupo SU(2).

### Representaciones del producto directo de grupos

Sean $D_1(G_1)$ y $D_2 (G_2)$ representaciones de los grupos $G_1, G_2$ respectivamente. El conjunto de operadores $D((g_1,g_2))$ por:

$$D((g_1,g_2))=D_1(g_1)\otimes D_2(g_2)$$

da lugar a una representación del producto directo $G_1\times G_2$ que es unitaria si $D_1(G_1)$ y $D_2(G_2)$ lo son y son fieles si son representaciones irreducibles de $G_1$ y $G_2$ respectivamente entonces D es una representación irreducible de $G_1 \times G_2$. Además, cada representación irreducible de $G_1 \times G_2$ es equivalente a una construida de esta forma.


# Ejercicios T3


    - Dada una representación de un grupo sobre los complejos, los vectores de $\mathds{C}$ que se transforman bajo la acción de D:
    
    $$D: \hspace{0.2cm} G \to GL(n,\mathds{C})$$
    $$\Vec{x}\to \Vec{x}'-D(g)\Vec{x}$$
    
    Si consideramos funciones de $\mathds{C}^n$ en $C$ tales como $f'(\Vec{x})=f(\Vec{x})$ tenemos que $f(D(g)\Vec{x})=f(\Vec{x})$ y concluimos que:
    
    $$f\longrightarrow f'$$
    $$f'(\Vec{x})=f(D^{-1}(g)\Vec{x})[A]$$
    
    Demostrar que este mapa es un homeomorfismo en el espacio de funciones y que por tanto el conjunto de transformaciones [A] forman una representación del grupo sobre dicho espacio.
    
    $$\begin{array}{cc}
    D: \hspace{0.2cm} \Vec{x}\to \Vec{x}'  \\
    D': \hspace{0.2cm} f(\Vec{x})\to f'(\Vec{x})
    \end{array} \hspace{2cm} \text{De forma que} \hspace{0.2cm} f'\equiv D'(f)$$
    
    \smallskip
    $\hspace{1cm}$ Para demostrar que este mapa define una representación del grupo G debemos probar que respeta la estructura de grupo, es decir, que si $g=g''g'$ entonces $f\overset{g}{\longrightarrow} f''$ coincide con la composición de $f \overset{g'}{\longrightarrow} f'$ con $f'\overset{g''}{\longrightarrow}f''$. Tenemos que:
    
    $$f'(\Vec{x})=f(D^{-1}(g),\Vec{x})$$
    $$f''(\Vec{x})=f'(D^{-1}(g), \Vec{x})=f(D^{-1}(g')D^{-1}(g''),\Vec{x
    })=f(D(g''g')^{-1},\Vec{x})=f(D((g)^{-1},\Vec{x})$$
    
    Como queríamos demostrar.
    
    - Consideramos la representación bidimensional irreducible de $S_3 \cong D_3$, denotada anteriormente por $D^{(2)}(S_3)$, y dos vectores en el espacio complejo de dos dimensiones de coordenadas $(x^1,y^1)$ y $(x^2,y^2)$ que se transforman independientemente bajo la acción de la representación D. Esta representación da lugar a una representación de dimensión 4 W($S_3$) dada por la envolvente lineal de los monomios $X^1x^1, x^1y^2,y^1x^2$ y $y^1y^2$. 
    
    
   - Calcular las matrices de representación W(g) siendo g un elemento de $S_3$.
   
   $$f: \hspace{0.2cm} (x^1,x^2)\otimes (y^1,y^2) \to \mathds{C}$$
   $$\hspace{0cm} V_1 \hspace{0.5cm}\otimes \hspace{0.5cm} V_2 $$
   
   Por ejemplo $\tau _3 \tau _1=\sigma _1$, $\sigma _1^{-1}=\sigma _2$, $\tau _1 \sigma _1=\tau _2$.
   
   Partiendo de $D^{(2)}(\tau _1)=\left ( \begin{array}{cc}
 -1  & 0 \\
  0 & 1
   \end{array}\right)$ y $D^{(2)(\tau _3)}=\frac{-1}{2}\left ( \begin{array}{cc}
 -1  & \sqrt{3} \\
  \sqrt{3} & 1
   \end{array}\right)$.
   
   Con estas dos podemos construir $W(\tau _1)$ y $W(\tau _3)$, y con ellas podemos construir todas las demás mediante la tabla de multiplicación:
   
   $$\tau _1: \begin{array}{cc}
  x^1\to -x^1 & x^2\to -x^2  \\
  y^1\to y^1 & y^2 \to y^2
   \end{array}$$
   
   $$x^1x^2\overset{\tau _1}{\to} (x^1x^2)^1=x^1x^2$$
   $$x^1y^2\overset{\tau _1}{\to} (x^1y^2)^1=-x^1y^2$$
   $$y^1x^2\overset{\tau _1}{\to} (y^1x^2)^1=-y^1x^2$$
   $$y^1y^2\overset{\tau _1}{\to} (y^1y^2)^1=y^1y^2$$
   
   $$V=lin\lbrace x^1x^2,x^1y^2,y^1x^2,y^1y^2 \rbrace; \hspace{1cm} f'(\Vec{x})=W(\tau _1)f(\Vec{x})=f(W(\tau _1)^{-1}\Vec{x})$$
   
   Ahora tomando la base ortonormal más sencilla:
   
   $$x^1x^2=\left( \begin{array}{c}
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
   \end{array} \right )$$
   
   Queda la representación:
   
   $$W(\tau _1)=\left (\begin{array}{cccc}
 1  & 0 & 0 & 0 \\
 0  & -1 & 0 & 0 \\
   0 & 0 & -1 & 0 \\
   0 & 0 & 0 & 1
   \end{array} \right)$$
   
   Ahora, para $W(\tau _3)$ tenemos que sigue la siguiente relación:
   
   $$\left ( \begin{array}{c}
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
   \end{array}\right)$$
   
   Por lo que las transformaciones son del estilo:
   
   $$x^1x^2 \overset{\tau _3}{\longrightarrow} (x^1 x^2)^1=\left ( \frac{x^1}{2}-\frac{\sqrt{3}}{2}y^1 \right) \left ( \frac{x^2}{2}-\frac{\sqrt{3}}{2}y^2 \right)$$
   
   Y los elementos de la base se transforman a:
   
   $$(x^1x^2) \longrightarrow (x^1x^2)^1$$
   
   $$\left( \begin{array}{c}
   1  \\
   0 \\
   0 \\
   0
   \end{array} \right )\longrightarrow \frac{1}{2} \left( \begin{array}{c}
   1  \\
   -\sqrt{3} \\
   -\sqrt{3}\\
   3
   \end{array} \right )$$
   
   Repitiendo este procedimiento podemos hallar la transformación para cada elemento de la base de V. Por tanto, es posible hallarnos $W(\tau _3)$ y con ella obtener $W(\tau _2)$, $W(\sigma _1)$ y $W(\sigma _2)$ mediante el producto adecuado de matrices.
   
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MTU3MjI3NTMsLTcxNzcyNjc5NCwtNj
g1MDQwNTgwLC0xNTY1MzUyNTQ2LDk5NzA2NjE3OF19
-->