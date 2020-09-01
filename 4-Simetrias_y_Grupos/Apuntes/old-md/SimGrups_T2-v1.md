
# Elementos generales de teoría de grupos
## Defininición y ejemplos
Un grupo es un conjunto de elemntos $G=\lbrace g\rbrace$ junto con una ley de composición interna (la llamaremos multiplicación).

$$G\times G\rightarrow G$$
$$(g_1,g_2)\rightarrow g_1g_2 \in G$$

Debe tener las siguientes propiedades:


- Asociativa, $ (g_1g_2)g_3=g_1(g_2g_3)$
- Existencia del elemento unidad, $\exists e / \hspace{0.2cm} eg=g\hspace{0.2cm} \forall g\in G$
- Existencia de inversa, $\exists g^{-1} / \hspace{0.2cm} g^{-1}g=e \hspace{0.2cm} \forall g\in G$
\end{enumerate

Puede probarse facilmente que esas propiedades existen también cuando se multiplica por la derecha en vez de por la izquierda.


Definimos el \textbf{grupo abeliano} como aquel grupo que presenta la "propiedad distributiva", $g_ig_j=g_jg_i \hspace{0.2cm} \forall g_ig_j \in G$.


Definimos el \textbf{orden} como el número de elementos de un grupo, denominado por $|G|$.


El teorema de reordenamiento nos asegura que $gG=\lbrace gg_i\rbrace =G$ pues g es un elemento de G y la multiplicación de elementos de un grupo no nos saca del grupo.

## Ejemplos de grupos

### Grupos finitos
- Los enteros bajo suma de módulo n $\mathcal{Z}_n$ (grupo cíclico de orden n). Si su suma se sale del conjunto se restan tantos $|n|$ como haga falta para que viva en el conjunto. Veamos por ejemplo la tabla de multiplicar del grupo $\mathcal{Z}_3$:

$$\begin{array}{ c | c c c}
+ & 0 & 1 & 2 \\
\hline
0  & 0 & 1 & 2 \\
1 & 1 & 2 & 0 \\
2 & 2 & 0 & 1
\end{array}$$

- Los grupos de invariancia rotacional discreta y de reflexión (grupos puntuales de redes regulares discretas).
- Grupo de permutaciones ($S_n$) de n elementos o grupo simétrico. Tiene orden $n!$. Grupo no abeliano.
\end{itemize

### Grupos infinitos discretos


- Los enteros bajo suma $\mathcal{Z}$.
- Los reales bajo multiplicación.
- Los grupos de traslación en redes regulares discretas.
\end{itemize

### Grupos continuos compactos

- Grupo ortogonal O(n), grupo de matices de orden n (n$\times$n) que satisfacen $O^+(n)=O^{-1}(n)$. Son el grupo de rotaciones y reflexiones en $\mathds{R}^n$.
- Grupo unitario U(n) de matrices n $\times$ n que satisfacen $U^+U=\mathds{1}$.
- SO(n) y SU(n) son subgrupos con det=1 (\textit{ Nota: los grupos con det=-1 no tienen ley de composición interna}).
\end{itemize

### Grupos continuos no compactos


- $\mathds{R}$, $\mathds{Q}$ y $\mathds{C}$ bajo suma y multiplicación (sin el cero).
- El grupo lineal GL(n,$\mathds{K}$) de amtrices n $\times$ n con coeficientes en el cuerpo $\mathds{K}=\mathds{R},\mathds{C}$ y det $\neq$ 0 y su subgrupo, el grupo espacial lineal de las matrices con determinante 1 (SL(n,$\mathds{K}$)).
- El grupo euclídeo de transformaciones del tipo $\Vec{x}\rightarrow O\Vec{x}+\Vec{b}$ con $O\in O(n)$ y $\Vec{b}$ un vector constante (E(n)).
- El grupo de Poincaré (de isometrías del espacio de Minkowski) y el grupo de Lorentz (subgrupo de isometrías que dejan el origen fijo).
\end{itemize

## Subgrupos

Se llama subgrupo al conjunto de elementos $H \subset G$ que es a su vez un grupo con la misma operación interna que G.


$\hspace{0.5cm }$ \textbf{Teorema:} H es subgrupo de G si para cualesquiera 2 elementos de H cumple que $h'h^{-1}\in H$ y $h'h\in H$.

### Definiciones


- Se dice que un subgrupo es \textbf{propio} si es distinto a G y al elemento identidad.
- Definimos el \textbf{centro} de G, Z(G), como el conjunto de elementos que cumplen $h\in G$ / $hg=gh \hspace{0.2cm} \forall g \in G$. Sera no-propio si no es abeliano (pues si no se cumple trivialmente para cualquier subgrupo de G).
\end{itemize

## Clases de conjugación

Un elemento $g_1$ de un grupo G se dice conjugado de otro $g_2$ si existe un $h\in G \hspace{0.2cm} / \hspace{0.1cm} g_1=hg_2h^{-1} \leftrightarrow g_1h=hg_2$.


- Si $g_1$ es conjugado a $g_2$ entonces $g_2$ es conjugado a $g_1$.
- Si $g_1,g_2$ son conjugados a $G_3$ y todos pertenecen al mismo grupo G $g_1$ y $g_2$ también son conjugados entre sí.
\end{itemize

Una \textbf{clase de conjugación} es un conjunto de elementos mutuamente conjugados.

### Popiedades


- Cada $g\in G$ pertenece a alguna clase de conjugación.
- Ningún g puede pertenecer a dos clases distintas.
- La identidad forma una clase consigo misma.
- Si G es abeliano entonces cada $g\in G$ forma una clase consigo misma.
\end{enumerate

## Subgrupos normales
Un subgrupo H de un grupo G es normal (también llamado invariante bajo conjugación) si $ghg^{-1}\in H \hspace{0.2cm} \forall h\in H$ y $\forall g\in G$. Se denota por $H\lhd G$.

$\hspace{0.5cm}$\textbf{Teorema:} $H\subset G$ es un grupo normal de G si H es una unión de clases de conjugación de G.

$$\text{Si} \hspace{0.1cm} N\subset H \subset G \hspace{0.1cm}\text{son subgrupos y} N\lhd G \hspace{0.1cm} \text{entonces}\hspace{0.1cm} N\lhd H $$


- Se dice que un subgrupo es \textbf{simple} si no tiene subgrupos normales propios (excluyendo a la identidad y al propio grupo que son triviales).
- Un grupo es semi simple si no tiene subgrupos normales abelianos propios. Evidentemente, simple implica semi simple.
\end{itemize

## Cosets
Sea $H=\left { h_I\right}$ un subgrupo de G. Se define el coset por la izquierda de H asociado a $g\in H : gH= \left { gh_i\right }$ y el coset por la derecha de H asociado a $g\in H : Hg= \left { h_i g\right }$.


\textbf{Propiedades} (Valen para los cosets por la derecha o por la izquierda):


- gH coincide con H si y solo si $g\in H$.


- Si $g\notin H$ entonces $e\notin gH$ no es subgrupo de G.


- Cada elemento de G pertenece a algún coset.


- Si $g'\in gH$, entonces $g'H=gH$.


- Dos cosets $g_1H, g_2H$ o bien son idénticos o bien son disjuntos.


A partir de esta propiedades se ve que si H es subgrupo de G, entonces G es una unión disjunta de cosets asociados a H.


- Si G es un grupo finito de H es subgrupo de G, el orden de H es divisor del orden de G ($|G|/|H|\in \mathcal{Z}$, Teorema de Lagrange). A esa división se le llama índice y es el número de cosets diferentes de H.

 ## Grupo cociente
 Un subgrupo H de un grupo G es normal ($H\lhd G$) si y solo si los cosets por la derecha H coinciden con los cosets por la izquierda.

 Podemos definir el producto de cosets (por la izquierda) de un subgrupo normal $H\in G$ como:

 $$g_1H
\*g_2H=(g_1\cdot g_2)H; \hspace{0.2cm} g_1,g_2 \in G$$

 No es obvio que $(g_1\cdot g_2)$ sea consistente pues hay elementos de G diferentes para los que sus cosets son los mismos. Necesitamos una definición que nos da la relación de consistencia:

 $$(g_1'g_2')H=(g_1g_2)H$$

 Es decir, si los cosets coinciden debe coincidir también la composición. Por sencillez tomemos $g_1=e$, entonces $eH=H=hH \hspace{0.2cm} \forall h\in H$. Ahora, con el anterior producto $(eg)H=eH
\*gH=hH
\*gH=(hg)H=gg^{-1}hgH$.


 Necesitamos que $g^{-1}hgH=H \leftrightarrow g^{-1}hg\in H \hspace{0.2cm} \forall g \in G$, es decir, H tiene que ser grupo normal. En general si $gH=g'H$ entonces $g'=gH$ con $h\in H$.


 \textbf{Teorema:} el conjunto de cosets (por la izquierda) de un subgrupo normal H de un grupo G forma un grupo respecto a la operación de multiplicación de cosets anteriormente definida por
\*. Este grupo se llama grupo cociente (\textit{factor group}). Se denota por G/H. Si G es finito, el orden del grupo cociente es el índice.

 $$G=\lbrace g_1,...,g_n,g_{n+1},...,g_m\rbrace$$
 $$H=\lbrace g_1,...,g_n\rbrace$$
 $$G/H=\left (\lbrace H,g_{n+1}H,...,g_mH\rbrace,
\*\right )$$

 Nótese que $gH=g'H$ define una relación de equivalencia distinta a la conjugación, podemos pensar en el grupo cociente como el conjunto de esas clases de equivalencia bajo esta relación. Nos sirve para clasificar conjuntos.

 La partición de los elementos del grupo G en costets es única y una "factorización" de G basada en esta partición es natural. Veámoslo como un ejemplo:


 Sea $G=S_3$ y $H=A_3$ del ejemplo anterior. El grupo cociente viene definido por la tabla de multiplicar:
 $$

\begin{array}{ c | c c

\* & $A_3$ & $\tau_1$ $A_3$\\
 \hline
 $A_3$ & $A_3$ & $\tau_1 A_3$ \\

 $\tau_1 A_3$ & $\tau_1 A_3$ & $A_3$
 \end{array}


$$

 Cumple:


- $A_3
\*eA_3=(e\cdot e)A_3$
- $A_3
\*\tau_1A_3=(e\tau_1)A_3$
 \item (\tau_1A_3)
\*(\tau_1 A_3)=(\tau_1 \tau_1)A_3=A_3$
\end{itemize


 El grupo cociente $S_3/A_3= \lbrace A_3, \tau_1 A_3\rbrace $ me da información sobre la paridad de los grupos $S_3$ y $A_3$.

 ## Homomorfismos entre grupos
 Un homomorfismo entre dos grupos G y G' es una aplicación

 $$\phi : \hspace{0.2cm} G \rightarrow G'$$

 $$g\rightarrow \phi(g)$$

 que verifica que $\phi (g\cdot h)=\phi (g)
\*\phi (h)$ respetando la estructura de grupo.


- Un homomorfismo se dice \textbf{fiel} si es inyectivo.

 $$\phi (h)=\phi (g) \hspace{0.2cm} \text{si y solo si g=h}$$


- Un \textbf{isomorfismo} es un homomorfismo biyectivo (inyectivo y suprayectivo). Un mapa uno a uno de G en otro grupo G' del mismo orden que respeta la multiplicación $G\cong G'$.


- Un \textbf{automorfismo} es un isomorfismo de un grupo en sí mismo (es decir cambio de mapa dentro de un mismo grupo).

 ### Propiedades de los homomorfismos

 Sean dos grupos $(G,\cdot)\cong (G',
\*)$ con la identidad bien definida y con homomorfismo entre ellos.


 - $\phi (e_g)=e_{g'}$
 - $\phi (g^{-1})=(\phi (g))^{-1}$

     La imagen de $\phi$ denotada por $\phi (G)$ es la parte de G' alcanzada mediante $\phi$, $\phi (G)=\lbrace g' \in G' \hspace{0.1cm} /\hspace{0.1cm} \exists \hspace{0.1cm} g \in G \hspace{0.1cm}\text{con} \hspace{0.1cm} \phi (g)=g' \rbrace \subset G' $

 - El núcleo de $\phi$, denotado Ker $\phi$ (o $\phi ^{-1}(e_{g'})$) es el subconjunto de G mapeado bajo $\phi$ a la identidad en G'.

     $$Ker\phi = \lbrace g\in G \hspace{0.2cm} / \hspace{0.1cm} \phi (g)=e_{g'}\rbrace$$


     $\phi$ es inyectivo $\leftrightarrow$ Ker $\phi$= $\lbrace e_{g}\rbrace$


      \end{itemize

     $\hspace{0.5cm}$\textbf{Teorema de Caley}: todo grupo de orden n es isomorfo a un subgrupo de $S_n$.




 \textbf{Ejemplo}: Consideremos la aplicación $\phi: \hspace{0.2cm} \mathds{R}\rightarrow S^1=\lbrace z\in \mathds{C}, \hspace{0.2cm} |z|=1 \rbrace ; \hspace{0.2cm} x \longrightarrow \phi (x)=e^{ix}$ que es un homomorfismo de ($\mathds{R},+$) en $S^1$.


 $$a+b \longrightarrow \phi (a+b) =e^{i(a+b)}=e^{ia}\cdot e^{ib}=\phi(a)\phi (b)$$

 Sin embargo, su Ker $\phi =2\pi \mathds{Z}\neq e_g \rightarrow \phi $ no es un isomorfismo.


 \textbf{Ejemplo 2}: veamos un ejemplo de isomorfismo entre grupos, el grupo $S_3$ es isomorfo a $D_3$ (el grupo de simetrías en el plano del triángulo equilátero).


 - Invariante bajo rotaciones de 0º$\rightarrow \hat{e}$, $120º \rightarrow \hat{\sigma}_1$ y $240º\rightarrow \hat{\sigma}_2$. Reflexiones con respecto a los ejes que pasan por sus vértices.

 -  Reflexiones respecto al vértice que pasa por el vértice i-ésimo ($\hat{\tau}_1$).
 \end{itemize

 ### Teoremas

 Sea $\phi : G\rightarrow G'$ un homomorfismo entre grupos, entonces:


\item Ker $\phi$ es un subgrupo normal de G.

\item La imagen de $\phi (G)$ es subgrupo de G'.

\item El grupo cociente $G/Ker\phi$ es isomorfo a $\phi (G)$, con el isomorfismo dado por

$\hat{\phi} : G/Ker\phi \rightarrow \phi (G)$ (los cosets de Ker$\phi$).

 \end{enumerate

 Veamos la demostración de los teoremas en orden.


 Para el \textbf{primero} debemos probar que Ker$\phi$ es subgrupo.


 Consideremos $g,h\in Ker\phi $ , es decir $\phi (g) =\phi (h)=e_{g'}$. Entonces:

 $$\phi (gh^{-1})=\phi (g)\phi (h^{-1})=\phi (g)(\phi(h))^{-1}=e_{g'}e_{g'}^{-1}=e_{g'} \rightarrow gh^{-1} \in Ker \phi $$

 y por tanto Ker $\phi$ \textbf{es subgrupo} de G.


 Para probar que Ker$\phi$ es normal, consideremos cualquier elemento de G, $h\in G$ (no necesariamente en Ker$\phi$); llamemos $g\in Ker \phi$ a cualquier elemento del núcleo. Tenemos:

 $$\phi (hgh^{-1})=\phi(h)\phi (g)\phi (h^{-1})=\phi(h)(\phi(h))^{-1}=e_{g'}\rightarrow hgh^{-1}\in Ker\phi$$


Luego $hKer\phi h^{-1}=Ker \phi \hspace{0.2cm} \forall h\in G$, \textbf{es normal}.


 Vamos con la del \textbf{segundo}.


 Sean $\phi (g),\phi (h)\in  \phi(G)$ entonces:

 $$\phi (g)(\phi(h))^{-1}=\phi (g)\phi (h^{-1})=\phi (gh^{-1})\in \phi (G)\rightarrow \phi (G)$$

es subgrupo.


  Y el \textbf{tercero}.

  Veamos que $\hat{\phi}$ esta bien definido (es decir, no existen elementos de G para los que $gKer\phi =g'Ker\phi$), por tanto, hay que asegurarse de que $\hat{\phi} (gKer\phi)=\hat{\phi}(g'Ker\phi)$, es decir que $\phi(g)=\phi (g')$.


  En efecto si $gKer\phi =g'Ker \phi \rightarrow ker\phi=g^{-1}g'Ker\phi \rightarrow g^{-1} g' \in Ker \phi$. Entonces:

 $$\phi (g')=\phi (gg^-1g'})=\phi (g)\phi (g^{-1}g')=\phi (g)$$

 como queríamos probar.


 Necesitamos ahora probar que es \textbf{homomorfismo}, es decir, debemos probar que respeta el producto en el grupo. Si tomamos el producto de los mapas de dos cosets $\hat{\phi} (gKer\phi)\cdot \hat{\phi} (hKer\phi)=\phi (g)\phi (h)=\phi (gh)=\hat{\phi} (ghKer\phi)$ vemos que efectivamente respeta el producto de cosets.


 Debemos probar también que es \textbf{inyectivo} (su núcleo es la identidad). Sea el coset $gKer\phi \in Ker\hat{\phi} \leftrightarrow \hat{\phi} (gKer\phi)=e_{g'}\rightarrow \phi (g)=e \rightarrow g\in Ker \phi \rightarrow gKer\phi =Ker\phi$, que es el elemento identidad del grupo cociente y por tanto el núcleo es trivial.


 Además debe ser \textbf{suprayectivo}; como el mapa es suprayectivo (o sobreyectivo) por construcción, es decir la imagen es todo $\phi (G)$, entonces lo es. Por lo tanto el grupo cociente es efectivamente un isomorfismo de $\phi (G)$.


 Este teorema proporciona una manera sencilla de ver si un subgrupo es normal, buscando un homomorfismo del cual dicho subgrupo es su núcleo. Se trata además de un criterio exhaustivo ya que para cualquier subgrupo normal $H\lhd G$ el mapa $\uppi : G\rightarrow G/H$;  $g\rightarrow gH$ también es un homomorfismo entre grupos con $Ker\uppi =H$.


 \textbf{Corolario}: un subgrupo $H\subset G$ es normal si y solo si existe un homeomorfismo entre grupos $\phi : G\rightarrow G'$ con $Ker\phi =H$.

 \newpage
 Veamos algunos ejemplos.


 - Para cualquier grupo matricial sobre un cuerpo $\mathds{K}$, el determinante es un homomorfismo a $\mathds{K}^
\*$, el cuerpo sin el cero (las matrices de determinante 0 no tienen inverso y no se podran mapear). El núcleo de este mapa consiste en todas las matrices con determinante 1. Que por el teorema 1 vemos que determinan un subgrupo normal y podemos hablar de un grupo cociente. Por el teorema 3, los grupos cocientes son isomorfos a las respectivas imágenes.

 - Dentro de grupos matriciales vemos, por ejemplo, el grupo general lineal de matrices $GL(n,\mathds{K})$ tiene el grupo $SL(n,\mathds{K}) \lhd GL(n,\mathds{K})$ y su grupo cociente $GL(n,\mathds{K})/SL(n,\mathds{K})\cong \mathds{K}^
\*$.

- También el grupo de matrices unitarias $U(n)$ tiene un subgrupo $SU(n)\lhd U(n)$ tal que su cociente $U(n)/SU(n) \cong S^1 \cong U(1)$.
 \end{itemize

 ## Veamos un ejemplo con algunas cosillas del tema, el grupo $S_3$ de permutaciones con 3 elementos
Sean las siguientes permutaciones:

$$e=\begin{bmatrix
1 & 2 & 3 \\
1 & 2 & 3
\end{bmatrix} \hspace{0.5cm
\tau_1=\begin{bmatrix
1 & 2 & 3 \\
1 & 3 & 2
\end{bmatrix} \hspace{0.5cm
\tau_2=\begin{bmatrix
1 & 2 & 3 \\
3 & 2 & 1
\end{bmatrix} \hspace{0.5cm
\tau_3=\begin{bmatrix
1 & 2 & 3 \\
2 & 1 & 3
\end{bmatrix} \hspace{0.5cm
$$
$$
\sigma_1=\begin{bmatrix
1 & 2 & 3 \\
2 & 3 & 1
\end{bmatrix} \hspace{0.5cm
\sigma_2=\begin{bmatrix
1 & 2 & 3 \\
3 & 1 & 2
\end{bmatrix} \hspace{0.5cm}$$

Sus clases de conjugación son:


 - La identidad.
 - Los ciclios (taus).
 - Los 3-ciclos (sigmas).
 \end{enumerate

 Su tabla de multiplicar:


$$\begin{array}{ c | c c c c c

e & $\tau_1$ & $\tau_2$ & $\tau_3$ & $\sigma_1$ & $\sigma_2$\\
\hline
$\tau_1$ & e & $\sigma_1$ & $\sigma_2$ & $\tau_2$ & $\tau_3$\\

$\tau_2$ & $\sigma_2$ & e & $\sigma_1$ & $\tau_3$ & $\tau_1$\\

$\tau_3$  & $\sigma_1$ & $\sigma_2$ & e & $\tau 1$ & $\tau_2$\\

$\sigma_1$ & $\tau_3$ & $\tau_1$ & $\tau_2$ & $\sigma_2$ & e\\

$\sigma_2$ & $\tau_2$ & $\tau_3$ & $\tau 1$ & e & $\sigma_1$

\end{array}

Tiene dos subgrupos propios, el de los 3 ciclos y el de $\tau_1$ con la unidad:


\begin{bmatrix
e & \sigma_1 & \sigma_2\\
\sigma_1 & \sigma_2 & e \\
\sigma_2 & e & \sigma_1
\end{bmatrix}$\hspace{3cm}$
\begin{bmatrix
e & \tau_1\\
\tau_1 & e
\end{bmatrix


Son grupos abelianos.


Veamos sus clases de conjugación, deben cumplir (para $\sigma_1$):

$$g\sigma_1 g^{-1}=h\in G$$



Con $\sigma_1$ y $\sigma_2$, vemos que forman una clase de conjugación (en este caso subgrupo normal):



$$\sigma_2\sigma_1 \sigma_2^{-1}=\sigma_2 \sigma_2=\sigma_1$$

$$\tau_1\sigma_1 \tau ^{-1}_1=\tau_1\tau_3=\sigma_2 \leftrightarrow \tau_1 \sigma_2 \tau_1 ^{-1}=\sigma_1$$

$$\tau_2\sigma_1 \tau ^{-1}_2=\tau_2\tau_1=\sigma_2 \leftrightarrow \tau_2 \sigma_2 \tau_2 ^{-1}=\sigma_1$$

$$\tau_3\sigma_1 \tau ^{-1}_3=\tau_3\tau_2=\sigma_2 \leftrightarrow \tau_3 \sigma_2 \tau_3 ^{-1}=\sigma_1$$


$$\left \lbrace e \right \rbrace U \left \lbrace \sigma_1, \sigma_2 \right \rbrace=A_3$$

Para $\tau_1$:

$$\tau_2 \tau_1 \tau_2^{-1}=\tau_2\tau_1 \tau_2 =\tau_2 \sigma_1=\tau_3$$

$$\tau_3 \tau_1 \tau_3^{-1}=\tau_3\tau_1 \tau_3 =\tau_3 \sigma_2=\tau_2$$

Que es el grupo $\lbrace \tau_1, \tau_2 , \tau_3 \rbrace$.

Busquemos los cosets de $A_3$, deben cumplir que $gA_3=\lbrace ge, g\sigma_1, g\sigma_2\rbrace$.

$$eA_3=A_3$$

$$\sigma_1 A_3=\lbrace \sigma_1, \sigma_2 , e \rbrace=A_3$$

$$\sigma_2 A_3=\lbrace \sigma_2, e, \sigma_1 \rbrace=A_3$$

Vemos que $gH=H$ si $g\in H$.

$$\tau_1 A_3=\lbrace \tau_1, \tau_2, \tau_3\rbrace$$

$$\tau_2 A_3=\lbrace \tau_2, \tau_3, \tau_1\rbrace$$

$$\tau_3 A_3=\lbrace \tau_3, \tau_1, \tau_2\rbrace$$

Y también comprobamos que $\tau_1 A_3=\tau_2 A_3=\tau_3 A_3$.


 ## Automorfismos internos

 Definimos los automorfismos como

 $$\phi : G \to G$$
 $$Ker \phi \lhd G$$
 $$\phi (G) \hspace{0.1cm} \text{es subgrupo de G'}$$
 $$\exists \hspace{0.1cm} \hat{\phi} \hspace{0.1cm} $$

  El conjunto de automorfismos internos forman grupo y $g \to \phi_g$ es un homomorfismo de grupos $\phi_g \phi_h=\phi_{gh}$ (el producto de mapas es el mapa del producto).

  El núcleo de este homeomorfismo es el conjunto de elementos que conmutan con todos los elementos de G, es decir, su centro Z(G). Esto es consistente con que Z(G)$\lhd$G.


HE LLEGADO TARDE Y AQUI FALTA ALGO IMPORTANTE DE LA DEFINICION DE AUTOMORFISMO.

## Producto de grupos

El \textbf{producto directo} de dos grupos $G_1$ y $G_2$ se define como el conjunto

$$G_1\times G_2=\lbrace (g_1,g_2) \hspace{0.1cm}| \hspace{0.1cm} g_1 \in G_1, \hspace{0.1cm} g_2\in G_2\rbrace$$

que tiene estructura de grupo con respecto a la multiplicación $(g_1,g_2)
\*(g_1'g_2')=(g_1\cdot g_1',g_2\cdot g_2')$. Existe identidad, inverso y el orden del grupo producto es $N_1\times N_2$ siendo los órdenes de $G_1$ y $G_2$ respectivamente (si tienen orden finito).


    - $G_1 \times G_2$ tiene subgrupos normales evidentes tales como $(e_g,G_1)=\lbrace (g_1,e_g) \hspace{0.1cm} | \hspace{0.1cm}g_1 \in G_1 \rbrace \cong G_1$ y $(e_g,G_2)=\lbrace (g_2,e_g) \hspace{0.1cm} | \hspace{0.1cm}g_2 \in G_2 \rbrace \cong G_2$, sugieren también unos homomorfismos naturales:

    $$\pi_1: G_1\times G_2 \to G_1$$
    $$\pi_2 : G_1\times G_2 \to G_2$$

    $(e_g,G_1)$ y $(e_g,G_2)$ conmutan entre sí así que cada elemento de $G_1 \times G_2$ se puede escribir de forma única como $(g_1,g_2)=(g_1,e_{G_1})
\*(g_2,e_{G_2})$.
- Un grupo G' se dice que es grupo producto directo si es isomorfo a algún grupo con esta estructura. Los elementos de G' a priori no necesitan tener una estructura en forma de pares.

\end{itemize

 \textbf{Teorema}: G es un producto directo de sus subgrupos $G_1$,$G_2$ si se cumplen las siguientes condiciones:


 - $G_1$y $G_2$ son subgrupos normales (o equivalentemente, los elementos de uno conmutan con los elementos del otro).
 - $G_1$ y $G_2$ han de ser disjuntos salvo identidad.
 - $G_1$ y $G_2$ generan G, es decir, $G=G_1G_2$ (cada elemento de G se puede escribir como producto de elementos de $G_1$ y $G_2$).
 \end{enumerate

 \textbf{Corolario}: si G es producto directo de dos subgrupos normales $G_1,G_2$ entonces $G/G_1 \cong G_2$ y $G/G_2 \cong G_1$. \textbf{Ojo}, si H es un grupo normal de G y H' es el grupo cociente no significa que $G=H\times H'$.


 \textbf{Ejemplos:


 - U(n)=U(1)$\times$SU(n); cada matriz unitaria se puede escribir como un producto $e^{i\phi}\mathds{1}\cong U(1)$ y una matriz SU(n) y ambas conmutan.
 - O(3)$\cong$ SO(3)$\times G_2$ con $G_2 =\lbrace \mathds{1},-\mathds{1}\rbrace$
 \end{itemize

 ¿Qué ocurre si alguno de los subgrupos no es normal? Un grupo $G^
\*$ se dice que es \textbf{producto semidirecto} si posee dos subgrupos $G_1$ y $G_2$ tales que:


 - $G_1$ es subgrupo normal de G.
 - $G_1 \cap G_2 =\lbrace e\rbrace$ (como antes, disjutos salvo identidad).
 - Cada elemento de $g\in G$ puede escribirse como $g=g_1g_2$.
 \end{enumerate

 $$G^
\*\cong G_1\rtimes G_2 \to \text{Producto semidirecto}$$

 \newpage
 \textbf{Ejemplos}:


 - $S_3$ y $A_3=\lbrace e,\sigma_1, \sigma_2 \rbrace$.

- E(2), grupo de traslaciones afines en el plano, cuyos elementos vienen especificados por una matriz ortogonal O(2) y un vector traslación. Mientras que las traslaciones forman un subgrupo normal. O(2) no es normal pues no es invariante bajo conjugación. Así, $E(2)\cong \mathds{R}^2\rtimes O(2)$.
- Poincaré $\cong \mathds{R}^4 \rtimes$ Lorentz
 \end{itemize



## Ejercicios del tema 2

 $\hspace{0.5cm}$ \textbf{1.} Probar que un grupo finito de orden n (primo) debe ser un grupo cíclico  (generado por a).

 $$C_n=\lbrace a,a^2,...,a^{n-1},a^n=e\rbrace \cong Z_n$$



 Por el teorema de Lagrange el orden de un subgrupo H de un grupo G debe ser divisor de orden n de G. Por otra parte, cada elemento del grupo genera un subgrupo cíclico y llamamos orden del elemento al orden m del subgrupo cíclico que genera. Por el teorema de Lagrange m debe ser divisor de n y como m es primo $m=\lbrace 1,n\rbrace$.

 Si n es primo entonces el orden de los elementos de G ($m_g, \hspace{0.1cm} \forall g\in G$) debe ser n (a excepción de la identidad) y el subgrupo cíclico que generan es el mismo grupo G.



 Deducimos también que dos grupos cualesquiera cuyos órdenes sean el mismo número primo son isomorfos e isomorfos al grupo cíclico de ese orden.

 Nota, definiendo el isomorfismo:

 $$C_n\cong Z_n, \hspace{2cm} \begin{array}{c
 \phi : Z_n \to C_n \\
 m \to \phi (m)=a^m
 \end{array} $$

 $$m_1+m_2 \to \phi(m_1+m_2)=a^{m_1+m_2}=\phi(m_1)\phi (m_2)$$


 $\hspace{0.5cm}$ \textbf{2.} Probar que $G=H_1\times H_2$ implica que $G/H_1\cong H_2$.


 Por ser G producto directo de los otros dos grupos, estos son normales y tiene sentido construir los grupos cociente. $G/H_1$ es grupo con respecto a la multiplicación de cosets. Tenemos que:

 $$G/H_1=\lbrace gH_1\rbrace=\lbrace h_1h_2H_1 \rbrace=\lbrace (h_1H_1)(h_2H_1)\rbrace=\lbrace (e,H_1)(h_2H_1)\rbrace=\lbrace h_2 H_1\rbrace$$

 Concluimos que los cosets de $H_1$ generados por los elementos de $H_2$ son los únicos elementos del grupo cociente $G/H_1$. Esto sugiere la correspondencia natural uno a uno dada por:

 $$ \left . \begin{array}{c
 \phi : H_2 \to G/H_1\\
h_2 \to \phi (h_2)=h_2H_1
 \end{array} \right | G/H_1\cong H_2$$

 Además:

 $$\phi (hh')=hh'H_1=(hH_1)(h'H_1)=\phi (h) \phi (h') \hspace{0.1cm}\forall h,h' \in H_2$$


\textbf{3.} Probar que, salvo isomorfismos, solamente hay dos grupos diferentes de orden 4: el grupo cíclico $C_4$ y el grupo de
reflexiones en el plano $V_4$ (también llamado grupo de Klein). Demostrar también que el grupo de Klein es producto
directo de $C_2$ consigo mismo.


$$C_4=\lbrace  a,a^2,a^3,A^4=e\rbrace$$

$$V_4=\lbrace e,\sigma ,\tau ,\rho \rbrace$$

$$e: \begin{array}{c
     x\to x  \\
     y\to y
\end{array}; \hspace{0.5cm} \sigma : \begin{array}{c
     x\to -x  \\
     y\to y
\end{array}; \hspace{0.5cm} \rho : \begin{array}{c
     x\to x  \\
     y\to -y
\end{array}; \hspace{0.5cm} \tau : \begin{array}{c
     x\to -x  \\
     y\to -y
\end{array}; \hspace{0.5cm}$$


La tabla de $V_4$ es (se ve que es un grupo abeliano):

$$\begin{array}{ c | c c c c}

V_4 & e & \sigma & \tau & \rho \\
\hline
e & e & \sigma & \tau & \rho \\
\sigma & \sigma & e & \rho & \tau \\
\tau & \tau & \rho & e & \sigma \\
\rho & \rho & \tau & \sigma & e
\end{array}  $$


Para demostrar que solo hay estos grupos de orden 4 sabemos que sus elementos generan subgrupos cíclicos. Por el teorema de Lagrange los ementos de G solo pueden ser o de orden 4 o de orden 2 (divisores de 4). Si G tiene al menos un elemento de orden 4 entonces ese elemnto genera $C_4$ y como $C_4 \in G \to G \cong C_4$.

Si G no tiene ningún elemento de orden 4 entonces todos sus elementos son de orden 2, llamémoslos $\lbrace e,\sigma ,\tau ,\rho \rbrace$, con e identidad y los cuadrados de todos iguales a la identidad pues generan $C_2$. Nos falta conocer como pueden ser los productos cruzados. Por ejemplo $\sigma \tau =\rho$ necesariamente, ya que $\sigma \tau \neq e$ pues $\sigma \sigma =e$; $\sigma \tau \neq \sigma$ pues $\tau \neq e$ y $\sigma \tau \neq \tau$ pues $\sigma \neq e$. Ocurre lo mismo con el resto de cruzados lo que implica que solo hay esta tabla (este grupo abeliano) y por tanto solo dos grupos de orden 4; el cíclico y el abeliano.


Para la demostración de que $V_4\cong C_2 \times C_2$, sabemos que $V_4=\mathds{Z}_2 \times \mathds{Z}_2$. Sabemos que $C_2\cong \mathds{Z}_2$ y que son subgrupos normales pues $V_4$ es abeliano. Además, es única (salvo conmutación ya que es abeliano) pues dados los subgrupos normales $\lbrace e, \sigma \rbrace$ y $\lbrace e, \tau \rbrace$ su producto directo genera $V_4$ de forma única (genera $\rho$ únicamente bajo el producto $\tau \sigma$ o $\sigma \tau$ al ser abeliano).


\textbf{4.} Consideremos el grupo diédrico $D_4$, que es el grupo de simetría de un cuadrado. Si situamos el cuadrado en el
plano xy, centrado en el origen de coordenadas y con sus lados paralelos a los ejes de coordenadas, entonces el
grupo consiste en rotaciones en torno al centro y reflexiones con respecto a los ejes vertical, horizontal y diagonales
de pendiente $\pm 1$. Llamemos e a la identidad, g a la rotación de ángulo $\pi/2$ (en sentido antihorario) y h a la reflexión
con respecto a la diagonal y = x. Demuestra que el grupo está generado por g y h y escribe su tabla de multiplicar.



Sean las rotaciones:

$$R=\lbrace  g,g^2,g^3,g^4=e\rbrace$$

$$g: \hspace{0.1cm} \text{giro de} \hspace{0.1cm} \pi/2; \hspace{0.5cm} g^2: \hspace{0.1cm} \text{giro de} \hspace{0.1cm} \pi; \hspace{0.5cm} g^3: \hspace{0.1cm} \text{giro de} \hspace{0.1cm} 3\pi /2; \hspace{0.5cm} g^4 :  \hspace{0.1cm} \text{giro de} \hspace{0.1cm} 2\pi=e$$

Y las reflexiones:

$$H=\lbrace h_1, h_2, h_3, h_4 \rbrace$$

$$h_1: \hspace{0.1cm} y=x; \hspace{0.5cm} h_2: \hspace{0.1cm} y=-x; \hspace{0.5cm} h_3: \hspace{0.1cm} x=0; \hspace{0.5cm} h_4: \hspace{0.1cm} y=0$$

La combinación de R con $h_1$ genera el grupo $D_4=R\times H$, lo vemos en su tabla de multiplicar:

$$
\begin{array}{p{0.7cm}| p{0.7cm}p{0.7cm}p{0.7cm}p{0.7cm}p{0.7cm}p{0.7cm}p{0.7cm}p{0.7cm}}
$D_4$ & e & g & g$^2$ & g$^3$ & h & gh & g$^2$h & g$^3$h \\
\hline
e & e & g & g$^2$ & g$^3$ & h & gh & g$^2$h & g$^3$h \\
g & g & g$^2$ & g$^3$ & e & gh & g$^2$h & g$^3$h & h \\
g$^2$ & g$^2$ & g$^3$ & g & e & g$^2$h & g$^3$h & h & gh \\
g$^3$ & g$^3$ & e & g & g$^2$ & g$^3$h & h & gh & g$^2$h \\
h & h & g$^3$h & g$^2$h & gh & e & g$^3$ & g$^2$ & g \\
gh & gh & h & g$^3$h & g$^2$h & g & e & g$^3$ & g$^2$ \\
g$^2$h & g$^2$h & gh & h & g$^3$h & g$^2$ & g & e & g$^3$\\
g$^3$h & h$^3$h & g$^2$h & gh & h & g$^3$ & g$^2$ & g & e
\end{array}
$$


Que se ve bien como se ha construido la tabla representándolo gráficamente.
