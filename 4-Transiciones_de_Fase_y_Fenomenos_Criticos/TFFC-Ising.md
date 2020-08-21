
# Clases de teoría

## Modelo de Ising

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











# Laboratorio de computación

## 1. Tiempos de autocorrelación


nota: Borrar errores

```
ising2d 8 0.44068068 10 100000 -1

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
> Tiempos de autocorrelacion (E,M2,F)
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


```
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

## 2. Valores medios



## 3. Límite termo
