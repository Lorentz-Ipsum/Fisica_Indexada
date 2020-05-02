<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Del tema 1

$$
\begin{aligned}
-\frac{aq_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} + mb^2 q_1 &= m \ddot{q_1}\\
-\frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} + m b^2 q_2 &= m \ddot{q_2} \\
m b^2 q_3 &= m \ddot{q_3}
\end{aligned}
$$

# Sistemas Hamiltonianos


$$
\dot{p}_\alpha = - \frac{\partial H}{\partial q^\alpha} \quad \quad  \dot{q}_\alpha = \frac{\partial H}{\partial p^\alpha}
$$

$$
\begin{aligned}
	\frac{d q^1}{d s}= \dot{q_1} &=  \frac{\partial H}{\partial p^1} = U^1 =  - b q_{1} + \frac{p_{1}}{m} \\
	\frac{d q^2}{d s}= \dot{q_2} &= \frac{\partial H}{\partial p^2} = U^2 = \frac{p_{2}}{m} \\
	\frac{d q^3}{d s}= \dot{q_3} &= \frac{\partial H}{\partial p^3} = U^3 = \frac{p_{3}}{m} \\
\end{aligned}
$$

$$
\begin{aligned}
	 \dot{p_1} &= \frac{ \partial H}{\partial q^1} =  \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} - bp_1 \\
	 \dot{p_2} &= \frac{ \partial H}{\partial q^2} = \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} \\
	 \dot{p_3} &= \frac{ \partial H}{\partial q^3} = 0\\
\end{aligned}
$$


### Corchetes de Poisson

$$
\begin{aligned}
	\left\{j_{\alpha}, f\right\} &=\epsilon_{\alpha \beta \gamma}\left\{^{\beta} p_{\gamma}, f\right\}=\epsilon_{\alpha \beta \gamma} ^{\beta}\left{p_{\gamma}, f \right} +\epsilon_{\alpha \beta \gamma}\left{q^{\beta}, f\right} p_{\gamma}\\ &=\epsilon_{\alpha \beta \gamma}\left[-^{\beta} \frac{\partial f}{\partial ^{\gamma}p_{\gamma} \frac{\partial f}{\partial p_{\beta}}\right]
\end{aligned}
$$

$$
\begin{aligned}
	\left\{j_{\alpha}, H\right\} &=\epsilon_{\alpha \beta \gamma}\left\{q^{\beta} p_{\gamma}, H\right\}=\epsilon_{\alpha \beta \gamma} q^{\beta}\left\{p_{\gamma}, H\right\}+\epsilon_{\alpha \beta \gamma}\left\{q^{\beta}, H\right\} p_{\gamma}
	\\ &=\epsilon_{\alpha \beta \gamma}\left[-q^{\beta} \frac{\partial H}{\partial q^{\gamma}}+p_{\gamma} \frac{\partial H}{\partial p_{\beta}}\right]
	\\ &=\epsilon_{\alpha \beta \gamma}\left[-q^{\beta}\dot{p_\gamma} +p_{\gamma} \dot{q^\beta}\right]
	\end{aligned}
$$

## Geometria simpléctica

### Coordenadas unificadas

$$
H(\xi^i) = \frac{1}{2m} \xi^{j} \xi_{j} + \frac{a}{\sqrt{(\xi^1)^2 + (\xi^2)^2}} - b \xi^1 \xi_4 \quad j = 4, 5, 6.
$$

$$
\begin{aligned}
	\frac{d q^1}{d s}= \dot{q_1} &=  \frac{\partial H}{\partial p^1} = U^1 =  - b q_{1} + \frac{p_{1}}{m} \\
	\frac{d q^2}{d s}= \dot{q_2} &= \frac{\partial H}{\partial p^2} = U^2 = \frac{p_{2}}{m} \\
	\frac{d q^3}{d s}= \dot{q_3} &= \frac{\partial H}{\partial p^3} = U^3 = \frac{p_{3}}{m} \\
\end{aligned}
$$

$$
\begin{aligned}
	 \dot{p_1} &= \frac{ \partial H}{\partial q^1} =  \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}} - bp_1 \\
	 \dot{p_2} &= \frac{ \partial H}{\partial q^2} = \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}} \\
	 \dot{p_3} &= \frac{ \partial H}{\partial q^3} = 0\\
\end{aligned}
$$

$$
X_H = \left( - b q_{1}  + \frac{p_{1}}{m} \right) \frac{\partial}{\partial q^1} +   \frac{p_{2}}{m} \frac{\partial}{\partial q^2}  +  \frac{p_{3}}{m} \frac{\partial}{\partial q^3} + \left( \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}}  -  bp_1 \right) \frac{\partial}{\partial p^1} + \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}}\frac{\partial}{\partial p^2}
$$

---

$$
\begin{aligned}
X_H[q^1] &= \left( - b q_{1}  + \frac{p_{1}}{m} \right)
\\ X_H[q^2] &= \frac{p_{2}}{m}
\\ X_H[q^3] &= \frac{p_{3}}{m}
\end{aligned}
\quad
\begin{aligned}
X_H[p_1] &= \left( \frac{a q_1}{(q_1^2 + q_2^2)^{\frac{3}{2}}}  -  bp_1 \right)
\\ X_H[p_2] &= \frac{aq_2}{(q_1^2 + q_2^2)^{\frac{3}{2}}}
\\ X_H[p_3] &= 0
\end{aligned}
$$


---

### Flujos hamiltonianos.

$$
i_{X_F} \Omega = - df
$$

$$
\omega_{lj} \chi_j^l = -\partial_j f
$$

$$
\chi_f^j = \omega^{jk}\partial_k f
$$

$$
\chi_f = \omega^{jk}\partial_k f \partial_j
$$

Condición:

$$
d i_\chi \Omega = 0
$$

Flujo generatriz:

$$
\phi^{\chi_f} = \phi^f
$$

$$
\phi^f = exp\{ s(\mathcal{L}_{\chi_f} + \partial_s )\}
$$

$$
\mathcal{L}_{\chi_f}g = \chi_f g = \omega^{jk}\partial_k f \partial_j g = \{g,f \} = - \mathcal{L}_{\chi_g}f
$$

### Curvas Integrales

$H$ determina unívocamente a $\Delta$ a través de la 1-forma $dH$ y la ecuación $i_\Delta \omega = -dH$.

La derivada de Lie a lo largo del vector dinámico $\Delta$ da la evolución de g:

$$
\mathcal{L}_{\Delta}g = \frac{d}{dt} g =\partial_j f \dot{\xi}^j = \partial_j f \omega^{jk} \partial_k H = \{g,H\}
$$

1. Construir $\Delta_H$:

$$
\begin{aligned}
	 \Delta_H \Omega &= -dH \\
	 \Delta_H &= \omega^{jk} \partial_k H \partial_j
\end{aligned}
$$

2. Encontrar curvas integrales $\gamma_H$:

$$
\dot{\gamma}_H =\Delta_H = \frac{d\gamma_H}{dt}
$$

### Otra forma

$$.
i_{X_F} \omega = dF
.$$


$$
dF= \frac{\partial F}{\partial q^\alpha} dq^\alpha +  \frac{\partial F}{\partial p_\alpha} dp_\alpha
$$

$$
\phi_s^X = e^{s\mathcal{L}_X}
$$

### Teorema de Darboux

Existe una carta local en la que:

$$
\Omega = dp_\alpha \wedge dq^\alpha = \frac{1}{2} \omega_{ij} d\xi ^i \wedge d\xi^j
$$

1. Elegir una variable dinámica $g$.
2. Encontar $f$ tal que $\{f, g \} = 1$

$$
\Omega = dg \wedge df+ \Omega | _{\mathcal{L}_g}
$$

Con $\Omega | _{\mathcal{L}_g}$ una restricción en la variedad a $g$ constante y $\mathcal{L}_g$ una variedad de dimensión $2n-2$

## Transformaciones canónicas


## Invariantes



# Links

[ | Integral invariant - Encyclopedia of Mathematics](https://www.encyclopediaofmath.org/index.php/Integral_invariant)

[ | 13798.pdf](http://diposit.ub.edu/dspace/bitstream/2445/24549/1/13798.pdf)

[ | Poincaré Invariants](https://farside.ph.utexas.edu/teaching/plasma/lectures1/node19.html)

[ | corchetes de poisson - Google Search](https://www.google.com/search?client=firefox-b-d&q=corchetes+de+poisson)

[ | Poisson bracket - Wikipedia](https://en.wikipedia.org/wiki/Poisson_bracket)

[ | Corchete de Poisson - Wikipedia, la enciclopedia libre](https://es.wikipedia.org/wiki/Corchete_de_Poisson)

[ | List of LaTeX mathematical symbols - OeisWiki](https://oeis.org/wiki/List_of_LaTeX_mathematical_symbols)

[ | Corchete de Poisson - Wikipedia, la enciclopedia libre](https://es.wikipedia.org/wiki/Corchete_de_Poisson)

[ | transformaciones canónicas - Google Search](https://www.google.com/search?client=firefox-b-d&q=transformaciones+can%C3%B3nicas)

[ | Transformación canónica - Wikipedia, la enciclopedia libre](https://es.wikipedia.org/wiki/Transformaci%C3%B3n_can%C3%B3nica)

[ | Transformaciones infinitesimales](http://delta.cs.cinvestav.mx/~mcintosh/comun/pb/node5.html)

[ | Transformaciones canónicas](http://delta.cs.cinvestav.mx/~mcintosh/comun/pb/node4.html)

https://macul.ciencias.uchile.cl/alejo/clases/2019_mechanics/capitulo_5.pdf
