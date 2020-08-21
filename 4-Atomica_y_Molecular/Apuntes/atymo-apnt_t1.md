# Dia 1
$$
H = \sigma (\frac{p}{2m}-\frac{2e^2}{r_i})+\sigma\frac{e^2}{r_{ij}} + (FINA/HIPERFINA)
$$
- Con unidades **CGS** el $1/4\pi\epsilon_0$ desaparece
- C.L. de soluciones de H_c también será solucion del sistema.
- Armónicos esféricos

# Dia 2
	Notas generales.....

> Mirar CGS y unidades Planck (y Rydberg)
- a_0 Radio de Bohr = 1 Unidad propia(mas comun) de longitud
- nm 10^-9 = 10 A
- Energía de Hartee/ Rydberg =13,6
- 1 hartree = 2Ry Aunque normalmente Ry tiene unidades de longitud
- t= \hbar / E_h
- E_h = energía de Hartree
- Unidades Rydberg:
	- \hbar = 4\pi\epsilon_0 = e^2/2 = 2m = 1
	- Unidad de energía -> Rydberg
- Schrödinger en 1 dimensión
	- Comportamiento asintótico
	- 2E y 2Z/r tienden a cero cuando r tiende a cero
		- Probabilidad no nula de que el e esté en el origen
	- r a infinito
	- Decae si E-
	- Estado ligado si E+
- Pongamos que buscamos una determinada funcion para P(r) "que se comporte adecuadamente": iteramos en la ecuación diferencial.
- E(ev) = 1240/\lambda(nm)
- **Gráfica de fdo en la energía**
	- Representa numero de modos de una fdo
- Degeneración accidental:
	- Para un n dado hay que sumar para todos los valores posibles de l
	- $\Sigma^{n-l}_{0} (2l+1) = n^2, \Sigma^n_0 = n(n+1)/2$

### Efectos de Masa
-	M reducida
> Hacer calculotes de corrección a_0 ¿Cómo se mide la correción?
> Atomo muónico/ rayos cósmicos..... El muón sustituye a un e.....
	> Se pega a una distancia 200 mas pequeña a la del electrón
	> Si el atomo es pesado el muón estaría dentro del núcleo.
- V\approx Z_{ef}/r ... \sigma_{nl} es la constante de apantallamiento. Depende del orbital.
	- Es debido a los electrones que ya están ligados al núcleo.
	- Depende mayormente de n
	- Coincide aproximadamente con el número de electrones que hay en las capas por debajo.
- V_l (r) correción al eorbial porque el electrón no penetra en el nucleo.
	- n-\delta_l correción efectiva. Más grande para primeros orbitales.
> Fórmula de Rydberg. El resultado se obtiene con $V(r) = -Z/r -c(l)/r^2$



```mermaid
graph TD

cc[Campo Central]
em((efectos masa))
sp((Spin))
rel((Efectos relativistas, fina))
tek(tecnicas de calculo en polielectronicos)
pert(teoria de perturbaciones)
thfe{Thomas Fermi}
hafo{Hartree Fock}
potaut{Potencial Autoconsistente}
alcal[Alcalinos,terreos..]
xray{Rayos X}

apel[Aproximacion Electrostatica]
ls{Terminos LS}
Eij{Matriz de energias}

SO[Spin Orbita]
RS{Aproximacion de Rusell-Saunders}
inter{Tratamiento de acoplamiento intermedio}

Bext[Perturbacion por campos magnéticos]
arbit[Campos arbitrarios]
zee{Efecto Zeeman}
pas{Efecto Paschen-Bach}
rad[Interaccion de atomos con radiacion]
eins{Coeficientes de Einstein}


cc --> em
cc --> sp
cc --> rel
cc --> tek
cc --> alcal
alcal --> xray
tek --> pert
pert --> thfe
pert --> hafo
pert --> potaut

tek --> apel
apel --> ls
apel --> Eij

ls -- Acoplamientos --> SO
SO --> RS
SO --> inter

inter --> Bext
Bext --> arbit
arbit --> zee
arbit --> pas
Bext --> rad
Bext --> eins



```



# 11
# 1 Introduccion a los atomos polielectronicos
## ATOMOS POLIELECTRONICOS
[N =n de e, Z = n atomico, m = masa e]
$$ H = $$
- AProximación básica: Campo central.
	- Cada electrón ve un potencial promedio debido al resto de eletrones y al nucleo
$$ H= $$
- Solución $H_c = $
$$ H_i =
$$
Resuelto cada $H_i\phi_i = E_i\phi_i$ una solucion al $H_c\phi = E\phi$  es:
$$ \phi(r_1
$$
- O cualquier permitacion de las $r_i$, y por linealidad, cualquier C.l. de ellas
## AProximación básica: Campo central.
## Solución $H_c = \Sigma H_i$
## Aproximación de campo central I
### Cuestiones básicas
- Soluciones al problema de un electron
- Efecto de añgunas correciones(relativistas y nucleares
- Ejemplos en que "basta" esta aproximacion
- Funciones de onda en esta aproximación (Determinantes de SLater)
- Determinación de los potenciales V(r)
#### Soluciones al problema de un electron
En mecánica clásica se trata separando $P$.
Aqui tambien pero son operadores.
$$p
$$
Esfericas

Buscamos soluciones que separen en parte radial y orbital

Desarrollando y multiplicando por $2mr$

Problema $L^2$ bien conocido por los matemáticos.
Solución:
$Y_{ml}$ amilia de funciones ortonormales tabuladas.

Con esto uestro problema se reduce a
$$ R(r)
$$
mejora su aspecto con un cambio $R(r)$

Schrödinger en una dimension

Simplificamos convenientemente:
a) Estilo matemático
b) Estilo físico: Cambio de unicades
- Comportamiento asintótico

Soluciones para cualquier E.
Si E<0 sólo algunos valores discretos permitidos
### Resultados:
- Funciones de onda etiquetadas 3+2 "índices" (numeros cuánticos)
- Energía sólo dependiente de dos números cuçanticos
	- Degeneración en los otros
	- Definido por el número de ceros de P(r)
	- El origen de la degeneraciçon en M_p es la simetría esférica y desaparece bajo campos externos (zeeman, cristales)
- Caso particular: Hidrogenoide
	- P_{nl}
	- E_{nl}
	- Degeneración "accidental"
#### Efecto de algunas correciones (relativistas y nucleares
#### Ejemplos en que "basta" esta aproximacion
#### Funciones de onda en esta aproximación (Determinantes de SLater)
#### Determinación de los potenciales V(r)
### Solucion al problema de campo central
#### Buscamos soluciones que separen en parte radial y orbital
#### Schrödinger en una dimension
# 12
# 13		
## Resultados:
### Funciones de onda etiquetadas 3+2 "índices" (numeros cuánticos)
### Energía sólo dependiente de dos números cuçanticos
#### Degeneración en los otros
#### Definido por el número de ceros de P(r)
#### El origen de la degeneraciçon en M_p es la simetría esférica y desaparece bajo campos externos (zeeman, cristales)
### Caso particular: Hidrogenoide
#### P_{nl}
#### E_{nl}
#### Degeneración "accidental"
## Efectos de masa
### Isotopico de masa
#### Trabajando en C.M.
### Atomo muónico
### Positronio
# 14
## =Armónicos esféricos=
# 15
## Aproximación de campo central II
### Aspecto típico de los niveles de energía
#### Fórmula de Rydberg
## Introducción Spin
### Función de ondas de Spin
# 16
## Distribución de probabilidad electrónica
### Segun Phi
### Segun r
### segun theta
## Propiedades comunes a todo momento angular
### Definición
### Autovectores
### Operadores
### Representacion matricial
### Conmutación
#### Combinación
#### Numeros cuanticos
#### Coeficientes cambio de base
##### Propiedades de simetria
#### Combinaciones lineales
# 17
## Efectos Relativistas (Ecuación de Dirac)
### Correcciones Relativistas al campo central
#### Solución de la ecuación de Dirac
#### Energía de un dipolo en un campo magnético
# 18
## Resumen de teoría de perturbaciones
### Caso no degenerado
### Caso degenerado
#### Conclusión
#### Atajo!
## Efectos relativistas en H (Estructura Fina)
### H_0
### H_m y H_D
### H_{SO}
### Juntando todo
# 19
## Espectro del H
### Estructura fina
### Reglas de selección dipolares eléctricas (EI)
## Acoplamiento LS para un solo electrón
### Ejemplo: Obtener explícitamente los casos de l=1
