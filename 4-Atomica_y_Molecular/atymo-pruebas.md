# 71
# estructura molecular
Para un sistema de átomos aparecen términos extra en el hamiltoniano.
> Ignorando efectos relativistas el hamiltoniano molecular es:
> $ecuacion 25.1-1 weissbluth p551$
> Así planteado el problema es intratable
> normalmente no sera posible hacer una descripción tan exacta como en átomos.

Ya no podemos considerar que el electrón orbita en torno a un centro, sino alrededor de dos.
No se puede hacer tratamiento analítico ni para la molécula más sencilla: $H_2$
La aproximación base para tratar moléculas es:

## Aproximación de Born-Oppenheimer
> La masa del núcleo es mucho mayor que la de los electrones (y con las velocidades ocurre al revés).
> $M_\alpha << m$

* Podemos describir el movimiento de los electrones como si los núcleos estuvieran fijos
* Podemos tratar el movimiento de los núcleos como si los electrones contribuyeron como una nube.

> * Movimiento electronico:
> $eq 25.1-4 5 6 weissbluth$ [1]
> * Movimiento nuclear:
> $eq$ [2]

Hemos desacoplado el movimiento de cada parte, pero siguen complementándose a partir de $\Epsilon_{R_\alpha, n}$

Hemos asumido que las funciones de onda se pueden factorizar como $\Psy_{n, \nu}$
> La función de onda molecular completa es:
> $\Psi$

Nuestra descripción será incompleta, parcial. Debido a que los números cuánticos pueden tomar sus propios valores la notación que venimos usando puede dar lugar a repeticiones de niveles.
> No puedes conocer todos los números cuánticos que describen un nivel energético, sólo puedes conocer parcialmente el estado.


### Observaciones
> 1. Resulta una aproximación excelente.
> Sólo en algunos casos de movimiento nuclear muy rápido se notan pequeños efectos de desacople entre movimiento nuclear y electrónico.
> 2. un planteamiento más matemático del problema consiste en buscar soluciones para el hamiltoniano completo probando con C. L. de soluciones [1]:
> $\Psi$
> el resultado es [2] tras despreciar $|\nabla_R \Phi_R(r) |$ frente a $|\nabla_RF(R) |$.

Good
2. El estado total sería mezcla de estados nucleares, con F nu coeficientes.

# 72

## Aplicación a Moléculas Diatómicas
Sdr centro de masas.
Se reduce el problema de 6+6 gdl a 3:
> Distancia internuclear y ángulos theta y phi que indican la dirección de la molécula
> R:Movimiento vibración al. Theta: ángulo respecto al eje. Phi(no importa) :simetría cilindrica

Para el movimiento electrónico se tiene:
$$
Que sólo depende de r_i gracias a la aproximación BO.
Para cada valor de R la solución a esta ecuacion serán unas funciones\phi_R n con energías Er, n

Para los núcleos resulta la ec. SCHRODINGER DE UNA partícula de masa \mu en un potencial central.m!
$$
Toca resolver la ec de schro en aproximación de campo central.
> Esto. En general no es aplicable a cualquier molécula. Sólo a aquellas en que 9999999

E_n (R) central y dependiente del estado de la nube electrónica. En algunos casos no no presentará un mínimo.
El aspecto general es 99999999.

Para los núcleos (problema de campo central) conocemos la forma de las soluciones.

$F_n (\mathbf{R}) = \frac{1}{R} \mathscr{F} _{\nu, I} ^n (R) Y_{J, M_J} (\theta, \phi)$

Parte radial + Armónico esférico
> La J es la suma del momento angular electrónica y nuclear.

Con ello la ecuacion queda:
$[-\frac{\hbar^2}{


### Observaciones

1. El potencial E_n que incluye comportamiento repulsivo es suma

# 73

## I Movimiento nuclear en moléculas Diatómicas (Rotación-Vibracion)
Para un potencial "típico" del problema nuclear reducido, una buena aproximación se obtiene considerando las cercanías de R_0, la anchura del pozo, su profundidad etc...
1. Tomando un desarrollo de Taylor (sin tener en cuenta terminó centrífugo) obtenemos en orden 0 y 1 la aproximación armónica. Podemos definir una constante K elástica. Los niveles de energía seran equidistantes, caracterizados por un número v.
$E_v =\dots$

2. Evaluando el término centrífugo en torno a R_0 podemos tratarlo como una pequeña contribución a la energía en el desarrollo de Taylor.
$E_r=$
$\mu R_0^2 =I_0$ momento de inercia.
Definimos la constante B, constante rotación al. Que nos indica la separación de energía entre niveles rotación ales para cada nivel en orden 0.

Con todo, una solución bastante aproximada resulta:
$E_{n, \nu, J} =$

Cerca del límite de ionización esto suele fallar, habrá que tomar otras aproximaciones.

Hay varios modelos para potenciales centrales.
Uno que va bastante bien con este comportamiento es el *potencial de Morse*.
$V(R) =D_e[1-e^{-\alpha(R-R_0)}]^2$

D_e valor mínimo del potencial.

Podemos relacionar las constantes del potencial de morse con las de la serie de Taylor: K, \omega_0,....


### Anarmonicidad
Corrección anarminica


### Observaciones
1. El primer nivel rotación al no tiene energía nula. D_e="energía disociación"
D_0 = D_e - hbar omega} {2}
2.

# 74
## Distorsión centrífuga
Si describimos la molécula como dos masas unidas por un muelle, y girando...
La posición de equilibrio será proporcional a la velocidad de giro.

Así, el término centrífugo lo que hace es desplazar el potencial a una distancia mayor. (y deformarlo)

Así, los términos del desarrollo de Taylor dependerán de J.
Con los primeros términos obretenemos
$E_{n, v, J} = - D_e + parte armónica +acoplamientorotacional+correccionderotorrigido$
Y todos los coeficientes a y b que acompañan a dichos términos de la serie pueden dejarse en términos de los coeficientes de morse.

Los términos son:
* D_e =ekectrones
* armónico+anarmonico
* orden 0 rotacional
* distorsión centrífuga.
Dependiendo del estado vibraciónal la separación de los niveles rptacionales irá cambiando, por eso hay un término de acople.
La segunda correccion(a rotor rígido) viene de la deformación que sufre la molécula.

[En la tabla vemos algunos valores para algunas moléculas. La distancia de equilibrio va a ser del orden de unidades atómicas. En el caso de HCl (una molécula muy grande y otra pequeña) va como una media). El \alpha nos dice la separación del pozo de energía, de ahí podemos deducir cosas del estado.]
[en la segunda tabla...
A partir de la energía de disociación podemos sacar la De del potencial de morse. Y con la distancia entre niveles rptacionales hw podemos sacar la constante rotación al B. De ahi con la masa reducida podemos deducir la distancia de equilibrio.
La última columna es el momento dipolar. Para moléculas homonucleares la simetría lo anula. ]


# 75
### Repaso de algunos resultados.
Buscamos operadores que conmuten con el hamiltoniano. De esta forma estamos buscando cantidades conservadas.
#### Simetrias
> En mecánica cuántica las simetrías del Hamiltoniano (invarianza bajo ciertas transformaciones) tienen consecuencias inmediatas importantes. El que H sea invariante baja o cierta operación $A$ conlleva:
> * Si $\phi$ es autoestado de $H \Rightarrow A\phi$ también debe serlo (y con la misma energia) (cuando $A\phi \neq \phi$ ello supone una degeneración).
> * $[A, H] =0 \Rightarrow$ H y A tienen auto funciones comunes.
> *

## II. Estructura electrónica en moléculas diatomicas
### Consideraciones de simetria
Lz valdría para sutoestados.

Consideraciones de simetria

Notacion para niveles moleculares Sigma Pi... Valen para estado electrónico de orbitales moleculares. En realidad la l de los electrones no se conserva pero como la energía depende de la configuración electrónica podemos considerarlo cantidad conservada.

Otra consideración de simetria es una reflexión en el eje de simetria de la molécula.
> Reflexión $A_x$ (o cualquier otro plano que contenga eje z)

Será otro operador bueno para describir el estado.
> Equivale a un cambio de sentido de giro en torno al eje Z: $L_z A= - A L_z$.
> * Si $\Lambda\neq 0$:
> * Si $\Lambda=0$:

Los estados con \lambda \neq 0 existirán dos estados independientes que sean c. L. De ml +1 y ml - 1. Tendrán distinta energía así que estados con lambda neq 0 serán degenerados.
Por otro lado, estados tipo sigma ($\Lambda =0$, sin giro neto de los electrones) esta transformación A sobre un estado sigma:
* Decuelve la misma funcion
* devuelve la función cambiada de signo
A\Psi_\Sigma
A^2 =I
A\Psi = \pm \Psi
Así que tenemos estados $\Sigma^h y \Sigma^-$.
En principio tienen energías distintas, y para moléculas hetero nucleares nos dara un nuevo número cuántico.

> En caso homonucleares ($H_2,O_2,\dots$)
> Simetria de inversión respecto al origen $\mathbf{R} \leftrightarrow - \mathbf{r}$

Equivalente a una transformación de paridad.

> Función de onda deben ser simetricas ("g") $\Psi^g(-\mathbf{r}) =\Psi^g(\mathbf{r})$ o antisimetricas ("u") $\Psi^u(-\mathbf{r}) =-\Psi^u(\mathbf{r})$

> Como consecuencia, las funciones de onda electrónicas pueden clasificarse:
> $\Sigma_g^+$, $\Sigma_g^+$, $\Sigma_g^+$, $\Sigma_g^+$, $\Sigma_g^+$, $\Sigma_g^+$, $\Sigma_g^+$, $\Delta_g$, $\Delta_u$...

Tenemos otra vez funciones pares o impares, pero para no liarla los llamamos en alemán; gerade=par, ungerade=impar.

Podremos definir una base de autoestados de A:
$|\Pi, M_L=\pm 1 > \rightarrow |\Pi^+> |\Pi^->$
Igual para Sigma

## repaso

Orbitales moleculares.
Como construirlos?
Potencial bicentral

### método de Rayleigh reitz.
Tratamiento variación al con funciones prueba.

Buscamos valores extremos de valor medio de H.
Que coeficientes c_j Dan mínima energía?

Al buscar valores extremos obtenemos ecuaciones de Rayleigh reitz:
$det |H_{ij} - \Epsilon S_{ij} =0$
$\Sigma_i c_i(Hij)... =0$

Guardan cierta similitud con ecuacion autovectores solución de....

Resolver ecuacion secular(diagonaliza)
$$|Hij - EI|=0$$

Estamos suponiendo que los núcleos están fijos, la fdo se refiere a los electrones (orbital molecular)


# 76
.
## MOLÉCULA H2+

la energía de la ecuacion de schrodinger ya incluye el movimiento de los núcleos.

El estado del electrón será combinación de los orbitales 1s de cada atomo.
> Consideremos un tratamiento variación al con funciones prueba c l de orbitales atómicos (CLOA) $\Psi 1s$
> ....

No depende de los ángulos.
$Y00=1/\sqrt{2\pi}$
>$\Psi ra rb$

Método de Rayleigh reitz.:
Aplicamos las fdo prueba al método.

> Saa = Sbb.
> ...
> integral de solapamiento
> Haa 1 e en arimi H + autoestadi de H. Es como integral de solapamiento centrada en cada atomo. El término 1/rb guarda similitud con una integral directa(ciulomb)
> Hab
>
![enter image description here](https://lh3.googleusercontent.com/hQlbq4PGFl-idP1KOgC1-xq5AjZlY7jUQwXG1pP4HaUdoxsWVqIwIpTcazfWI7hIvmKE6BJJalLu "Imagen escaneada")


## H2+ resultados del tratamiento de Rayleigh reitz

Determinante......

Se puede comprobar
> + se asocia a c l donde los dos coefs son iguales y de mismo signo.
> - se asocia a la c l antisimetrica...


Sabiendo la e presión analítica de dichas integrales podemos representar directamente que es lo que sale [gráfica E+ y E-] la gráfica es el potencial efectivo.

E+ tiene pozo, orbital enlazante.
E- no daría lugar a una molécula estable.




# 77
