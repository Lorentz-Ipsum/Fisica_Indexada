
# Modelo de Ising


# Laboratorio

## 1. Tiempos autocorrelacion

> Tareas:
> Decribir cada programa
> anacor
> autocor
>

### Estimación gráfica

Lo primero que hicimos fue ver el modelo de ising y las simetrias azul rojo.
Luego veíamos como fluctuaba el val medio de M.

Rellenar la tabla de si el sistema termaliza
El sistema termaliza cuando aparecia una magnetizacion != de 0.
Con ls dos algorutmos

### Medida

autocor hasta termalización y luego anacor para sacar los t y las graficas

Guardamos las graficas

Estimar tiempos autocorrelacion

## 2. Valores medios


## 3. Limite termodinamico

> Explicación de lo qe es el LT.
>

Lejos del punto critico los errores son muy grandes, por eso tenemos que coger L pequeños y cerca del pto L grandes.

$$\xi _L(k) \frac {1}{a} $$

Celdas

$N=V=L^D, D=2,3...$ (en altas E hasta D=4)

Configuracion de espines dada $\{{S_i\}}_{i=1...N}=\{S_{(x,y)}\}$

$$H = -J\sum_{<i,j>} S_i S_j -g_L \mu_B B\sum_i S_i$$

<i,j> Primeros vecinos
<<i,j>> Segundos vecinos
...

Orbitales atómicos en cada nodo, decaimiento exponencial -> Solo primeros vecinos

$$U= -\sum_{<i,j>} S_i S_j \quad M=\sum_i S_i$$
$$H = -JU + Mg_L \mu:B B$$

Pero Boltzmann $e^{-H/k_BT}$
$$\frac{-H}{k_BT} = S = \frac{J}{k_BT}U + g_L\frac{\mu_B B}{k_BT}M$$

Simetría distinta en cada término. Para reflexión eje Z: $S_i \rightarrow -S_i$
U Par, M impar

Introducimos constantes de acoplamiento:
$$K=\frac{J}{k_BT} \quad h\frac{\mu_B B}{k_BT}$$

$$\frac{-H}{k_BT} = S = KU + hM$$
$(T,B)\longleftrightarrow(K,h)$ Variables de acoplo

#### Ejercicio
>> Sacar las $\frac{\partial} {\partial K}$ y  $\frac{\partial} {\partial h}$
 $\frac{\partial} {\partial B}$ Fácil
  $\frac{\partial} {\partial T}$ Difícil

# DIA 1 CLASE


nota: Borrar paréntesis de los errores

```bash
# ising2d 8 0.44068068 10 100000 -1
Ising2d: L=8, K=0.440681, iteraciones=10x100000x-1

       E =  1.49247 (0.000872703)
      E2 =  2.31951 (0.00234055)
     |M| = 0.777714 (0.000774767)
      M2 = 0.647594 (0.000889751)
       F = 0.0196023 (9.49079e-05)
    Fnew = 0.0113441 (3.92821e-05)
       C =  5.89021 (0.019037)
   chi_c =  2.73632 (0.0210098)
      xi =  7.39528 (0.0237571)
   xinew =   2.1374 (0.0245588)
     xi' =  95.8742 ( 4.9409)

anacor 200
Tiempos de autocorrelacion (E,M2,F)                   
4.531047 (0.047683)  6.246641 (0.076993)  6.608632 (0.083752)
```

```
# tau:		E,			M2,			F
8		4.531047 0.047683  6.246641 0.076993  6.608632 0.083752
```

---

```
/home/alumnosVMM/Ising/ising2d 8 0.44068068 10 100000 -1
/home/alumnosVMM/Ising/ising2d 16 0.44068068 10 100000 -1
/home/alumnosVMM/Ising/ising2d 32 0.44068068 10 100000 -1
/home/alumnosVMM/Ising/ising2d 64 0.44068068 10 100000 -1
/home/alumnosVMM/Ising/ising2d 128 0.44068068 10 100000 -1
```

Luego lanzamos anacor con un tiempo de autocorrelacion que deberia ser al menos 6 veces

```bash
/home/alumnosVMM/Ising/anacor 200
```
Y copiamos esos datos a tauHB.txt

```
gnuplot /home/alumnosVMM/Ising/autocor.gpt
ps2pdf autocor.ps
```



 Verlo:
```
okular autocor.pdf
```

Renombrar:
```
mv autocor.pdf autocorH8L8.pd
```


## Acabar

Imágenes guardadas

Fichero en Gedit: tauHB.txt

```
# 	L	tau:	E,		   M2,		      F

	8		4.710793 (0.050531)  6.499820 (0.081700)  6.865436 (0.088660)
			4.531047 0.047683  6.246641 0.076993  6.608632 0.083752
	16		14.664284 (0.275885)  26.526568 (0.670360)  28.085230 (0.730241)
	32		
	64		
	128		

```



# DIA 2

# DIA 3

Datos Heat Bath correctos (demasiado precisos incluso):

```bash
# HB

8	4.588009    0.048579	6.373439 	0.079339  	6.744980 	0.086346
16	14.952864   0.284053	27.550271 	0.709496  	29.239083 	0.775656
32	51.809830   0.914203    119.029637  	3.182074	126.052610      3.467743
64	182.407746  6.035868    555.985718      32.114682  	589.956831 	35.102387
128	573.811804  33.671416   2181.442468 	249.574130	2395.801978     287.249682  
```
Datos de Swedsen-Wang:


```bash# SW

8	2.558578 0.020373	  2.518668 0.019904	  1.827451 0.012375
16	3.226741 0.028760	  3.090661 0.026975	  1.984757 0.013983  
32	4.024533 0.019980  	  3.692604 0.017576       2.124110 0.007730
64	4.799739 0.051960	  4.195972 0.042523	  2.265566 0.017010
128	5.805176 0.034506  	  4.818399 0.026131  	  2.412837 0.009338
```

Una vez que los ajustes están bien:

## Ajustes


```plot
plot "tauHB.txt" using 1:2:3 w e
```

Para documentarlo mejor: Comandos

```bash
gedit dibuja_tauHB.gpt
```

Y ese archivo contiene:

Para heat bath tenemos el código:

```gnuplot
reset
set auto
set logs
set xrange [6:140]
set key left
set xlabel "L"
set ylabel "tau HB"
f(x) = A*(x**z)
fit [17:]f(x) "DATA_HB.txt" u 1:2:3 yerr via A, z
p "DATA_HB.txt" u 1:2:3 w e t "Tau HB", f(x) t "ajuste"
```

# El codigo para la grafica bien hecha:

pause -1
set term postscript color solid
set output "ajuste_HB.ps"
# set term qt
rep
```

Para SW:

```gnuplot
reset

set auto
set logs
set xrange [6:140]
set key left
set xlabel "L"
set ylabel "tau SW"

f(x) = A*(x**z)

# con los corchetes restingimos el ajuste a un intervalo de 9 a inft:
# fit [9:*] f(x) "DATA_SW.txt" u 1:2:3 yerr via A, z

fit f(x) "DATA_SW.txt" u 1:2:3 yerr via A, z

p "DATA_SW.txt" u 1:2:3 w e t "Tau SW", f(x) t "ajuste"



# El codigo para la grafica bien hecha:

pause -1
set term postscript color solid
set output "ajuste_SW.ps"
# set term qt
rep
```

### Para Tau_M

HB:

```
fit [17:]f(x) "DATA_HB.txt" u 1:4:5 yerr via A, z
p "DATA_HB.txt" u 1:4:5 w e t "Tau HB", f(x) t "ajuste"
```

SW:

```bash
fit f(x) "DATA_SW.txt" u 1:4:5 yerr via A, z

p "DATA_SW.txt" u 1:4:5 w e t "Tau SW", f(x) t "ajuste"
```

### Para Tau_F

HB
```bash
fit [17:]f(x) "DATA_HB.txt" u 1:6:7 yerr via A, z
p "DATA_HB.txt" u 1:6:7 w e t "Tau HB", f(x) t "ajuste"
```

SW

```bash
fit f(x) "DATA_SW.txt" u 1:6:7 yerr via A, z

p "DATA_SW.txt" u 1:6:7 w e t "Tau SW", f(x) t "ajuste"
```

## Cota inferior
Usamos la regla de Li-Sokal tau<6tau

Final sum of square of residuals = $\chi^2$=gdl = 3.26

Pvalue entre 10 y 90 %. Probabilidad de ajuste peor que el que tenemos

```
ls -ltr
```
$\tau _ {sw}(L)= A_{sw}L^{\epsilon logL} = A_{sw}(1+\epsilon log L + o(\epsilon^2)$

# Límite Termodinámico

Poner un proceso en background:

```bash
cd
mkdiw LT
cd LT
pwd
cp /home/alumnosVMM/Ising/barrido.sh .
gedit barrido.sh
```

Este es el aspecto de barrido.sh:
```bash

```

Es un loop en el tamaño y otro en $T^{-1}$

Lo reescribimos para darle menos prioridad:

```bash
nice -15 /home
```

Ahora lanzamos el proceso de forma que no interfiera con los demás usuarios:

```bash
nohup sh ./barrido.sh &
```

Da un error.
Hacemos

```bash
ps x
```

y comprobamos que todo está bien.



Ferrenber-Swendsen

Histogram Reweightin

DEnsidad espectral



# PREGUNTAS


- ¿Xi, xinew, xi'?
- Como correr algoritmos en cluster?
	-  Para que me vaya cogieno datos para L...
- Tiempo de correlacion es t en llegar a clusters?


---
-





# = ==SUCIO== =

# Fenómenos críticos

# Dia 1

## Diagrama $p/\rho$. Isotermas

![AguaDiagrama](IMG)
-	Eje densidad logarítmica
>-	Energía libre *debe ser convexa*
-	Compresibilidad punto crítico: $\alpha_T = \frac{ \partial \rho } { \partial P } = \infty, \quad \frac { \partial P }{ \partial \rho } = 0$
-	En el punto crítico el sistema *sobrerreaciona*
-	Será interesante describir el sistema desde la fase fría ( por la derecha )
-	Parámetro de órden
	-	$\rho _ { liquido } - \rho _ {vapor} \propto | T - T _ C | ^\beta$
-	Exponente crítico: $\beta$
-	Gran compresibilidad: $\kappa ( T ) = - \frac { 1 } { rho } \frac { d \rho } { d p } \propto \frac { 1 } { | T - T _ C | ^\gamma}$

> Transiciones de fase diferentes pueden ser muy similares.

![Histeresis](IMG)

-	Campo coercitivo se opone a la imanación

### Cómo se produce la transicion liquido - vapor?

Comparemos con el ciclo de histéresis:

Hay una discontinuidad.
: -	Imanación espontánea: $m(H) = -m(-H)$
	$m(H=0^+) = -m(H=0^-)=m_o$
: -	Según se juntan los puntos extremos de la vertical aumenta la pendiente y tenemos algo parecido, tiende a infinito.
: -	Si graficamos $m_o$ para distintas temperaturas la discontinuidad se parece a la de transición. Tiende a cero al acercarse a la temperatura de Curie.
: - Resulta que $\beta$ ( el exponente crítico ) es el mismo que para el agua

-	$T<T_c$:........... $m(T_C,H...$ [^1]
-	$T = T_c : m(T_C,H) \propto H^{ 1/\delta } + ... (\delta = 4)$
-	$T > T_c : m(T_C,H) \propto \chi H + ... (\chi \propto \frac { 1 } { | T - T _ C | ^\gamma})$

[^1]: FALTA T>T_c

Y resulta que $\gamma_{H_2O} = \gamma_{Ni} = \gamma_{Fe}$

> A altas T la curva es reversible, no discontinua. Pero en origen también diverge.
> Histeresis Extrema

## Grandes flutuaciones

Toda la ecuación de estado es universal. A baja $\rho:T-\rho$
![TfrenteRho](IMG)

Cualquier función de respuesta se dispara
-	Ej: Calor específico $C \propto \frac {dE}{ dT }, C \propto \frac {1}{  | T - T _ C | ^\gamma }$
-	$\alpha_{H_2O} = \alpha_{Fe} = 0, C > 0$

Pero no todas las transiciones de fase son iguales
-	Helio superfluido: $\alpha_{He} \approx -0.02 < 0$
-	![HeSuperfluido](IMG)
-	Antes se llamaba punto lambda del helio
-	En esos puntos no es analítico, pero no diverge

___
### Preguntas que surgen:

- ¿Por qué sistemas diferentes se comportan igual?
- ¿Cuando si, cuando no?
- ¿Cuántos exponentes críticos distintos hay? Serán proporcionales a las magnitudes termodinámicas implicadas.

## Opalescencia crítica

[Divergencia de las funciones de respuesta] + [Teoremas de fluctuación-disipación] =
= Grandes fluctuaciones

Distancia espacial de las correlaciones

Miremos la dependencia estadística de las fluctuaciones de densidad:
![VolDiferencial](IMG)
-	En un volumen diferencial ( del tamaño de la distancia de correlación ) la densidad no es constante
-	El parámetro espacial ( $\xi$: Longitud de correlación ) que define la distancia de correlación diverge
![Lambda y Xi](IMG)
-	El índice de refracción será diferente para cada diferencial de volumen, y puede verse macroscópicamente
-	Cuando la escala espacial .... [FALTA](FAIL)
-	Todos los coeficientes críticos dependen de $\xi$

$$(\frac {\lambda} {\xi })^3>>1$$
$$\xi \propto \frac {1}{  | T - T _ C | ^\gamma }$$

## Universalidad
[Buscar y hablar algo sobre esto](FAIL)
## Modelo de Ising

Modelo casi universal

Estudiaremos sólo una transición y lo aprendido se podrá aplicar a muchos casos:
:	Transición ferro - paramagnético
![IsingFerroPara](IMG)
Estudiaremos para un anillo de particulas con momentos magnéticos pero podría ser en una red

Campo de espines $S_x = \pm 1$ interaccionando con $H$ que incluye un campo magnético.

$$ H = -J \sum_{x,y} S_x S_y - g_L \mu_B B \sum_x S_x $$

El primer tñermino es el de intercambio. Producto del principio de exclusión de Pauli.
:	Lo trataremos a primeros vecinos.
:	*Precio de la energía es doble* porque deja un enlace insatisfecho
:	 Tiende a la coherencia

Veremos una transición orden-desorden:
:	Alta T, entropia
:	Baja T, imanación macroscópica
![OrdenDesorden](IMG)

---
#### Prob
>> Para casa: Cuál es el número de micro estados compatibles para la imanación máxima en cero

> M=0: $\begin{pmatrix}N \\ N/2 \end{pmatrix}$
> Aproximación Stirling: $log\begin{pmatrix}N \\ N/2 \end{pmatrix} \sim Nlog2$

Teoría estadística de Campos
:	Leyes de escala
:	Invariantes de escala
:	Fenómenos colectivos

Densidad de entropía: $s = S/N, S\propto log( \# microestados)$

$$P_B(\{S_i\}) = \frac{e^{KU+hM }}{ Z_N(K,h)} $$
$$Z_N(k,h) = \sum_{ \{S_i\}} e^{KU+hM} $$

La suma es a $2N$
La funcion de partición define:
$$Z_N(k,h) =  e^{N \phi_N(K,h)} $$

$\phi_N(K,h) = logZ_N /N$ cantidad de energía libre
:	Se usa porque tiene un limite bien definido

---


---

# Dia 2

## Mas y mejor

Entonces tenemos que:

$$Z_L(k,h) =  e^{ \kappa \sum_{<i,j>}S_i S_j + h\sum_i S_i  }$$

Con $N = L^D, \quad U =\sum_{<i,j>}S_i S_j m,\quad\sum_i S_i = M$ y a la exponencial se la denomina peso de Boltzmann.

El número de sumandos que tenemos aqui es enorme: $2^{L^D}=$Número de configuraciones.

Veremos las simetrías de esta función de partición con un cambio de etiquetas.

$$\begin{array}{c}
S_i =- S_i' \\
...
S_{N=L^D} = -S_N'
\end{array}$$

Resulta que la suma es la misma.

Supongamos una función de un único espín:

$$\sum _{S_i = \pm1}f(S_i)=f(1)+f(-1)$$
$$\sum _{S_i' = \pm1}f(-S_i')=f(-1)+f(1)$$

[^2]
[^2]: Faltan mas sumas

Una es par, la otra impar

### Densidad de imanación

$$Z_L(k,h) =  e^{ \kappa \sum_{<i,j>}S_i S_j + h\sum_i S_i  } = Z_L(k,-h)$$

$$\partial_h \phi_L = <m>_{k,h}$$

Suma sobre probabilidades * Función dinámica = Densidad+

$$<m>_{k,h}= -<m>_{k,-h}$$
$$<m>_{k,h=0}=0$$

No tiene sentido, no podría existir imanes permanentes.

Veamos que ocurre al poner un campo nulo:

![]

El factor de Boltzmann es el mismo para las dos configuraciones (contribuyen con la misma probabilidad), pero la densidad de imanación es opuesta.

### Ruptura espontánea de simetría

Se nos ha colado la hipótesis de que estamos sumando sobre configuraciones (en lugar de hacer desarrollos en serie).
Esto conlleva que:

$$lim_{L\rightarrow \infty}[lim_{h\rightarrow 0}<m>_{L,k,h}] = 0$$

Pero en los experimentos:

$$lim_{h\rightarrow 0^-}[lim_{L\rightarrow \infty}<m>_{L,k,h}] = -m_0(k)$$

Imanación espontánea, el campo no llega a 0.

Tenemos estados exquisitamente equilibrados pero el menor desequilibrio desestabiliza el sistema

$$lim_{h\rightarrow 0^+}[lim_{L\rightarrow \infty}<m>_{L,k,h}] = m_0(k)$$

> Imanes permanentes son metaeestables por contener dominios magnéticos con interacción dipolo-dipolo de órden cúbico.

Sigamos estudiando sistemas con un gran número de spines, pero no tan grandes como el número de Avogadro, de forma que aún tenga sentido definir derivadas:

$$\chi = \frac{1}{N} [<M^2>-<M>^2]$$

Se trata de un teorema de flucutación-disipación.

Una variación es igual a ña dispersión de una variable estocástica (la imanación total).

$$\frac{\partial}{\partial h}[\frac{1}{Z}\frac{1}{N}\frac{\partial Z}{\partial h}]=N[<m^2> - <m>^2]$$

Desviación cuadrática media = Susceptibilidad magnética específica / Número de GdL.

$$\sigma _m^2 = \chi /N$$

La termodinámica sólo se acerca a la física estadística en el límite termodinámico.

Las variables específicas no tienen dispersión según la termodinámica clásica.

Hay un teorema de fluctuación disipación igual para la densidda del gas: Compresibilidad finita implica que la densidad no fluctúa.

## Función de correlación

### Propagador de la función de correlación

$$ \begin{array}{c} C_{ij} = <S_i S_j> - <S_i><S_j>=
\\ = C(S_i - <m>)C(S_j - <m>)
\end{array}$$

Ya que el valor esperado de un spin coincide con el de todos.

> VAlor medio del producto = Producto de valores medios
> Probabilidad condicionada

$$C_{ij}=F(r_i - r_j)$$

¿Cómo tiende a cero?
En la escala de ongitudes de la longitud de correlación

El propagador decae exponencialmente con la escala característica:
$$C(r) \approx e^{-r/\xi}$$

---

$\chi$ es macroscópica. Susceptibilidad. Derivada de la imanación

$C_{ij}$ es microscçopica. Propagador.

Ambos se juntan por el teorema de fluctuación-disipación.

$$ \chi= 1/N[\sum_i \sum_j <S_i S_j> - \sum_i \sum_j<S_i><S_j>]$$

Variable estocástica no es valor medio.

$$M = \sum_i S_i$$

$$<M> = N<m>$$

$$ \chi= 1/N\sum_{ij} C(r_i -r_j)$$

Sumamos sobre todas las parejas, si cambiamos a sumas de todos los vecotres desplazamiento de la red nos quitamos el 1/N.

$$$$

> SUma a cada vector de la red y deahí al vector desplazamento.

Si C(r) fuera suave podríamos considerarlo como una suma de Riemann.

$$

Si un espín está por encima de la media afecta a los de su alrededor: $C_{ij} >0$

Experimentalmente sabemos que cerca del punto crítico, cuando me acerco a $T_c$: $\chi$ crece y crece.

$$

La única forma de que esto diverja exponencialmente de esta forma es que $C_{ij}$ tienda a 0 de forma no integrable.

## Teoría de campos

El propagador se aproxima al de un bosón escalar libre.

Para bosones sin masa el propagador diverge como $1/r^{D-2}$ (función de Laplace)

Con masa tenemos el propagador de Yukawa: $$

En teoría cuántica de campos $m^2$, en mecánica estadística $1/\xi^2$


|Teoría cuántica de campos|Mecánica estadística|
|---|---|
|$r<<\xi$|$r>>\xi$|
|Ecuación Laplace| Propagador de Yukawa

Dos desarrollos asintóticos distintos

- Para $r<<\xi$ tenemos $1/r^{D-2-\eta}$ que es casi como la de un bosón sin masa. $\eta$ se llama dimensión anómala. Implica que no es entera.

- Para $r>>\xi$ no cambia nada. Amplitud A$\frac{e^{-r/\xi}}{r^{D-1/2}}$


# Dia 3
