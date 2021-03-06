
--------------------

        ████████╗    ██╗  ██╗
        ╚══██╔══╝    ██║  ██║
           ██║       ███████║
           ██║       ╚════██║
           ██║            ██║
           ╚═╝            ╚═╝

--------------------


## Tema 4: Grupos y álgebras de Lie

### 4.1 Elementos básicos sobre espacios topológicos

- Compacidad
- Conexión
	- Camino en S
	- Arco-conexo
	- Simplemente conexo
	- n-veces conexo
	- Eg: $\mathcal{R}^n$ y $\mathcal{R}^2$
- Mapa homeomórfico
	- Continuo
	- Propiedades o invariantes topológicos
- Espacio Hausdorff
	- Axioma de separabilidad
- Carta
- Variedad analítica de dimensión n

### 4.2 Grupo de Lie: definición

- Def: Grupo de Lie
	- Condiciones sobre elementos

### 4.3 Grupos de Lie lineales

- Def: Condiciones sobre un grupo lineal
- Recubridor universal
- Representaciones unitarias del grupo de Lie
- Eg:
	- $GL(n,\mathcal{C})$: grupo general lineal de matrices complejas, de dimensión 2$n^2$.
	- $SL(n, \mathcal{C})$: grupo especial lineal
	-  GL($n,\mathcal{R}$): de dimensión $n^2$.
	- $SL(n,\mathcal{R})$: de dimensión $n^2-1$.
	- $U(n)$: grupo unitario de matrices complejas U tal que $U^+U=UU^+=\mathcal{1}^n$ de dimensión $n^2$ (en principio es subgrupo de GL pero la condición de conmutación nos quita la mitad).
	- SU(n): grupo especial unitario, subgrupo de U(n) que agrupa las matrices con detU=1, de dimensión $n^2-1$ (como el det U es un complejo de fase libre y norma 1 solo pone 1 condición sobre el detU).
	- O(n): grupo ortogonal de matrices reales que cumplen $OO^+=O^+O=\mathcal{1}_n$ de dimensión $\frac{n(n-1)}{2}$.
	- SO(n): grupo ortogonal especia, subgrupo de O(n) con detO=1, de la misma dimensión que O(n).
	- Sp(n): grupo simpléptico, grupo de matrices unitarias (n $\times$ n) con n par.
	- U(l,n-l): grupo pseudo-unitario de matrices complejas U que satisfacen $UgU^+=g$ siendo g una matriz diagonal de unos y menos unos.
	- O(n,l-n): grupo pseudo-ortogonal de matrices reales con $OgO^+=g$ con la misma g, de dimensión $\frac{n(n-1)}{2}$. Es el grupo de Lorentz, la g es una pseudo-métrica.
- Eg:
	- Compactos
	- No Compactos
- Prob:
	- ¿Son $O(n)$ y $U(n)$ grupos conexos?
	- ¿Son $SO(2)\sim U(1)$ y $SU(2)$ simplemente conexos?
	- Justificar por qué $SO(1,1)$ no es compacto
	- ¿Qué grupo es el recubridor universal de $SO(2)$? Buscar el grupo normal de $G$ tal que $S_1 \sim G/H$.
- Medida de integración invariante
	- Th: Integral invariante para grupos de Lie compactos
	- Medida de Lebesgue

### 4.4 Estudio local de un grupo de Lie: álgebras de Lie

- Def: Álgebra de Lie real
	- Def: Corchete de Lie
	- Def:
		- Subálgebra
		- Subálgebra invariante
		- Función exponencial de matrices
			- Props:
				- Fórmula de Campbell-Baker-Hausdorff
- Subgrupo uniparamétrico de un grupo de Lie lineal
- Generadores del álgebra de Lie
- Relación entre álgebras de Lie lineales y grupos de Lie linealees
	- Th: Exponenciación
	- Th: Subrupos uniparamétrico
	- Nota:
	- Eg: Álgebra de Lie real de $SU(n)$
	- Eg: Álgebra de Lie real de $SL(n, \mathbb{R})$
	- Ex: Caracterizar el álgebra de Lie $so(2)$

### 4.5 Representaciones adjuntas de álgebras y grupos de Lie: constantes de estructura

- Representación de un álgebra de Lie
	- Obs: Eqyuvakebcua de reoresentaciones, irreducibilidad, lemas de Schur, Descomposición CB...
	- Th: Representación analítica n-dimensional
- Constantes de estructura
	- Def: Matriz adjunta de $A\in \mathcal{L}$
	- Def: Representación adjunta del álgebra
	- Def: Constantes de estructura
		- Obs:
		- Props:
- Representación de un grupo de Lie lineal
	- Def: Representación adjunta del grupo
		- Obs:
	- Th: Representaciones adjuntas
	- Th: Automorfismo interno del álgebra

### 4.6 Álgebras de Lie simples y semi-simples

- Def: Álgebra de Lie simple
- Def: Álgebra de Lie semi-simple
	- Props:
- Operadores de casimir
	- Th: Conmutación
- Def: Forma de Killing
