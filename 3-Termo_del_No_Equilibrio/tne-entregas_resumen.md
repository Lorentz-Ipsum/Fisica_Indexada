<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# TNE- Resumen de las Entregas 2019/2020

# Entrega 1: Principios de Producción de Entropía Minima y Máxima
## Artículo 1: Mínima producción
### Resumen corto
> - El teorema de Prigogine se aplica a sistemas abiertos fuera del equilibrio en estado estacionario (o cerca del estado esstacionario).
> - La formulación integral intenta generalizar el principio a una gama más amplia de procesos, pero falla excepto para casos muy específicos.

### 1. Introducción
- La entropía ha sido relegada a ser una cantidad que describe el progreso de los procesos disipativos fuera del equilibrio.
- Dos investigadores: R. Clausius e I. Prigogine.
- Prigogine propone su teorema: Mínima producción de entropía.
  - Se aplica a procesos de no equilibrio abiertos y lineales en estado estacionario y cuando se puede asumir que estamos en equilibrio local.
- Principalmente, dos opiniones contrapuestas sobre el principio:
  - Describe la mayoría de procesos de no equilibrio.
  - El principio es de débil aplicación y es difícil generalizar principios entrópicos universales.

### 2. Formulación Local
- Enunciado:
  - Condiciones:
    - $J_i = \sum_k L_{ik} X_k$
    - $L_{ik} = L_{ki}$
    - Las fuerzas termodinámicas $X_i$ se mantienen constantes.
    - La producción de entropía del sistema es mínima.
  - Teorema:
    - Entonces, el sistema está en estado estacionario.
- Demostración:
  - $\sigma = \sum_i X_i j_i$
  - Como los flujos son constantes, el sistema es estacionario.
- Formulación inversa:
  - Si estamos en estado estacionario, la producción de entropía es mínima.
- Consideraciones:
  1. Fuerzas termodinámicas libres se ajustan mutuamente para llevar al sistema al estado con mínima disipación.
       - Si sólo hay una fuerza, y es distinta de cero, no se puede usar el principio.
       - Ejemplo eléctrico.
  2. Los coeficientes cinéticos deben ser independientes de las fuerzas y flujos termodinámicos, pero pueden depender, por ejemplo, de la concentración y la temperatura.
       - El principio es aplicable sólo a sistemas donde la dependencia entre fuerzas y flujos es **lineal**.
  3. El principio es válido, ¿pero es útil? La información necesaria para aplicarlo debe ser tan completa que la solución usando otros métodos suele ser más sencilla.
  4. Permite formular un criterio de evolución, $\sigma$ juega el papel de un potencial termodinámico.

### 3. Formulación integral
- Para extender el principio a una clase más amplia de procesos.

#### 3.1 Distintas formas de demostración
- Transporte de calor en sólidos.
  - Sólo una fuerza (el gradiente de temperatura), pero parece que el principio se mantiene.
  - Por tanto, debe haber diferencia entre la formulación local y la integral.
- En cada paper Prigogine daba argumentos ligeramente distintos para relacionar ambos principios.
- Introdujo la producción de entropía con pesos, si bien es difícil discernir cuándo un sistema tiene la estandar o la pesada.
- Resulta que en la formulación integral añade una condición nueva respecto a la local: el gradiente de temperaturas debe ser pequeño.
- No se prueba que para el caso integral sea el mínimo de producción de entropía (y no un extremo) el que da la distribución estacionaria, ni viceversa.

#### 3.2 ¿Se cumple el principio integral?
- Dependencia en la temperatura del coeficiente de conductividad térmica: $\lambda = \lambda_0 T^n$
  - $n = 0$
  - $n = -2$
- Transporte de calor:
  - $\frac{\partial T}{\partial t} = a \frac{\partial}{\partial x} \left( T^n \frac{\partial T}{\partial x} \right)$
  - Condiciones: $T(0, t) = T_0$, $T(l, t) = \gamma T_0$, $T(x, 0) = \xi (x)$
  - Cambio a magnitudes adimensionales $\theta, \chi, \tau$, $\psi (x,0)$
    - Obtenemos unas soluciones estacionarias (ecuación diferencial):
      - $\theta_{st} = [(\gamma^{n+1} -1) \chi + 1]^{1/(n+1)}$ si $n \neq -1$
      - $\theta_{st} = \gamma^\chi$ si $n = -1$
  - Producción de entropía adimensional $\Sigma_{st}$
  - Aplicamos Euler-Lagrange para obtener extremos.
    - Resolvemos, obtenemos otras soluciones:
      - $\theta_{st} = [(\gamma^{n/2} -1) \chi + 1]^{2/n}$ si $n \neq 0$
      - $\theta_{st} = \gamma^\chi$ si $n = 0$
  - Estas soluciones coinciden sólo en los dos casos estudiados por Prigogine.
- ¿Y el problema inverso? Campo estacionario de $T$ -> Minima producción de entropía.
  - Pequeña perturbación $\Delta(x, t)$ en e $\theta(\chi, \tau)$ produce una entropía $\Sigma_p$. Si es mucho más grande que $\Sigma_{st}$ el estado estacionario se caracteriza por la producción mínima.
  - Calculotes
  - Soluciones para $n \neq -1$ y $n = -1$
  - Discusión para $n = -2$:
    - Que la producción sea máxima o mínima depende del signo de la perturbación espacial inicial $(\pm | \delta (\chi) |)$
    - Mencionado por Prigogine en sus pruebas.
- Conclusiones:
  - No hay completa evidencia de que la distribución estacinaria de temperaturas corresponda al mínimo de producción de entropía.
  - El campo de temperatura en estado estacionario se puede obtener a partir de la mínima producción de entropís sólo en los casos $n = -2, 0$, en el segundo (más útil para aplicaciones) sólo puede hacerse para gradientes pequeños de temperatura. El enunciado inverso es incorrecto, para el estado estacionario la producción de entropía puede ser máxima o mínima.

### 4. Conclusiones
- El principio local es correcto.
  - Sólo válido si hay dos o más fuerzas, alguna de las cuales es constante.
  - Los coeficientes kinéticos no deben depender de fuerzas o flujos.
  - Mínimo de entropía implica estado estacionario y viceversa.
- La generalización de forma integral del principio es errónea.
  - Incluso si se introducen condiciones adicionales.
  - Inválido en ambas direcciones.
  - Interesante estudiar el caso $n = -2$.

## Artículo 2: Máxima producción
### Resumen corto
> - Aunque menos conocido que el principio de Prigogine, MEPP prueba ser más útil y aplicable.
> -

### 0. Introducción
- El principio de máxima producción de entropía (MEPP) se conoce mucho menos que el de mínima.
- Características principales en relación a los otros dos enunciados sobre la entropía:
  1. La segunda ley de la termodinámica: Para un proceso adiabático la entropía del estado final es igual o mayor que la del estado inicial.
    - MEPP es una consideración adicional: La producción de entropía no sólo es positiva, tiende a un máximo.
    - Así, tenemos información adicional sobre la tasa de movimiento del sistema.
    - Dentro de la interpretación estadística de la termodinámica, MEPP puede verse como una generalización de la formulación de Clausios-Boltzmann-Gibbs de la segunda ley.
  2. El principio de mínima producción de entropía.
    - Su relación con MEPP es complicada. Distintas ligaduras y parámetros.
    - No son opuestos, sino aplicables a distintos estados de la evolución de un sistema.
    - Prigogine propuso ejemplos en que un sistema se comporta de forma opuesta a su principio (p. ej. efecto Benard).
    - MEPP es el que más posibilidades tiene de ser un principio universal para los sistemas del no equilibrio.
- La literatura sobre el tema es fragmentada.
- Capitulos:
  - 1 y 2: Base termodinámica y estadística del principio.
  - 3: Aplicaciones de MEPP.
- El artículo se centra particularmente en criterios de evolución de sistemas relacionados con su entropía.

### 1. MEPP en termodinámica no equilibrio
#### 1.1. Fundamentos de la termodinámica del no equilibrio lineal
- Primera y segunda ley de termodinámica.
- Equilibrio local, dos tiempos característicos. Variación de entropía.
- Formulación de Onsager: Fuerzas y flujos lineales. (Fuerzas relativamente pequeñas)
- Principio variacional de Onsager: Los flujos maximizan $[\sigma(X_i, J_k) - \phi (J_i, J_k)]$
  - Deducción de la formulación a partir del principio variacional.
  - Formulación alternativa del principio variacional en términos de fuerzas (Gyarmati).
- Principio (Teorema) de Prigogine (local)
  - Es un corolario del principio de Onsager-Gyarmati
- Hay otras formulaciones variacionales para la termodinámica del no equilibrio.
- Razones para usar el formalismo de la termodinámica del no equilibrio lineal:
  1. Se puede resolver el sistema de ecuaciones.
  2. Se pueden describir flujos cruzados.
  3. Se puede obtener información adicional de los coeficientes cinéticos.
  4. También obtenemos información de cantidades que toman valores extremos en los estados de no equilibrio (p.ej. la entropía).
- La termodinámica del no equilibrio es muy útil en sus aplicaciones, sin embargo se desarrolló lentamente.
- A veces la condición de que las fuerzas termodinámicas sean pequeñas es demasiado fuerte. Por ello no puede describir muchos problemas encontrados hoy en día.

#### 1.2. Review crítico del enfoque de Ziegler
##### 1.2.1. Formulación del principio de Ziegler
- Trabajamos en el espacio de los flujos $\{J_k\}$. Conocemos la producción de entropía en este espacio. QUeremos encontrar $X_k$. Estamos en equilibrio local.
- MEPP de Ziegler:
  - > Si $X_i$ está establecida, $J_i$, que satisface $\sigma (J_i) = \sum_i X_i J_i$, maximiza la producción de entropía.
  - Similar al teorema de teoría de elasticidad llamado principio de máxima tasa de disipación de energía mecánica o de Mises.
  - Básicamente Ziegler extendió dicho principio a toda la termodinámica del no equilibrio.
  - En sistemas aislados MEPP ilustra el hecho de que se tiende al estado de máxima entropía por el camino más corto.
- MEPP matemáticamente:
  - $\delta_j \left[ \sigma(J_k) - \mu \left( \sigma(J_k - \sum_i X_i J_i) \right) \right]$
  - Con $\mu$ un multiplicador de Lagrange.
  - También puede formularse en el espacio de las fuerzas, sustituyendo $X_i$ por $J_i$.
  - Interpretación geométrica:
    - $\sigma(J_k)$ es una superficie, intersecada por el plano $\sum_i X_i J_i$, los flujos que la maximizan son los elegidos en la linea de intersección.
  - Expresión explícita de la fuerza termodinámica.
    - Llega a las condiciones de ortogonalidad (la fuerza $X_i$ correspondiente al flujo $J_i$ es ortogonal a la superficie $\sigma(J_i)=cte$).
    - Cuando dichas condiciones tienen sólo una solución, sólo hay un punto extremo, correpondiente al máximo de producción de entropía).
    - De forma general, la condición de ortogonalidad determina todos los puntos extremos, y el principio variacional escoge aquel en que la producción de entropía es mayor.

##### 1.2.2. Algunos argumentos a favor del principio de Ziegler
- Expandimos en serie la producción de entropía.
  - Pasos matemáticos chungos.
  - Llega a otra forma de expresar las condiciones de ortogonalidad.
- Demostración de la transición de la condición de ortogonalidad al principio variacional.
- Una producción de entropía de la forma (1.25) corresponde a las ecuaciones (1.5) y (1.6) de la termodinámica lineal de Onsager.
- > Las relaciones principales de la termodinámica del no equilibrio lineal se pueden deducir del principio de Ziegler si $\sigma$ es una función homogénea de grado 2.

##### 1.2.3. Deducción de las relaciones de Onsager a partir del principio de Ziegler
- Demostración de que el principio de Onsager puede obtenerse a partir del principio de Ziegler para el caso lineal.
  - Pasos matemáticos.

##### 1.2.4. MEPP y la segunda ley de la termodinámica
- Exclusivamente la interpretación termodinámica de la entropía y su producción.
- Si el principio de máxima producción de entropía se postula *ab initio*, la segunda ley de la termodinámica se puede obtener como corolario.
  - Utiliza la interpretación geométrica para demostrarlo.
  - Ocurre incluso si no asumimos convexidad y unicidad.

##### 1.2.5. Sobre la posible "paradoja" al usar el enfoque variacional
- Ejemplo: Dos fuerzas y dos flujos.
  - Relaciones de ortonormalidad, aparece una discrepancia, que si igualamos a cero, podemos determinar la condición en que las fuerzas se determinan únicamente por la producción de entropía:
    - $X_2(J_1,J_2)\frac{\partial \sigma (J_1, J_2)}{\partial J_1}  = X_1(J_1,J_2)\frac{\partial \sigma (J_1, J_2)}{\partial J_2}$
  - En ese caso, las condiciones de ortogonalidad y las fuerzas son iguales.
  - Para la función cuadrática de producción de entropía (1.25), si se cumplen las relaciones de reciprocidad de Onsager, (1.38) se cumple.

##### 1.2.6. Relación entre el principio de máxima producción de entropía de Ziegler y el principio de mínima producción de entropía de Prigogine
- La termodinámica lineal y no-lineal se pueden deducir del principio de Ziegler.
- El principio de Prigogine es válido para procesos estacionarios en presencia de fuerzas libres. Es menos aplicable que el de Ziegler.
- Hay cierta jerarquía de procesos, consideremos un sistema con producción de entropía en función de los flujos conocida:
  - Si se asignan fuerzas(flujos) termodinámicas, el sistema evoluciona de acuerdo al principio de Ziegler para que la producción de entropía sea máxima.
  - Si el sistema llega a un estado de no equilibrio estacionario débil, y algunas fuerzas(flujos) se dejan libres, el sistema reajustará dichas fuerzas y flujos para que lleguen al estado de mínima producción de entropía.
- Es decir, si el tiempo es corto, el sistema maximiza la producción de entropía para fuerzas fijas, si el tiempo es largo, cambia las fuerzas libres para llegar al mínimo.

#### 1.3. Breve conclusión
- Ziegler quería llegar a la base deductiva de la termodinámica del no equilibrio, tanto para casos lineales como no lineales.
- Comparado con otras formulaciones variacionales, la de Ziegler es más simple.

### 2. MEPP en física estadística del no equilibrio
