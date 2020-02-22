
# Garay

Transformación canónica:
$$
\begin{array}{cc}{\dot{q}^{\prime a}=\frac{\partial H^{\prime}}{\partial p_{a}^{\prime}}=0,} & {\dot{p}_{a}^{\prime}=-\frac{\partial H^{\prime}}{\partial q^{\prime a}}=0} \\ {q^{\prime a}(t)=q_{0}^{\prime a},} & {p_{a}^{\prime}(t)=p_{0 a}^{\prime}}\end{array}
$$

Ctes de mov de función generatriz S:
$$
p_{a}=\partial_{a} S, \quad p_{a}^{\prime}=-\partial_{a}^{\prime} S, \quad 0=H^{\prime}=H+\partial_{t} S
$$

Con
$$
{\partial_{a}=\partial / \partial q^{a} \text { y } \partial_{a}^{\prime}=\partial / \partial q^{\prime a}}
$$

Ecuación de Hamilton-Jacobi:
$$
{\qquad H\left(q^{a}, \partial_{a} S, t\right)+\partial_{t} S=0}
$$

Solve for S.

	 Función principal de Hamilton::

Acción de la trayectoria=  F ppal Ham
$$
{S\left(q_{0}, t_{0}, q_{1}, t_{1}\right)=S\left[q_{\text {clis }}(t)\right]}
$$

$$
{S\left(q_{0}, t_{0}, q_{1}, t_{1}\right) =\int_{t_{0}}^{t_{1}} L\left(q_{\text {clis }}(t), \dot{q}_{\text {clis }}(t), t\right) \mathrm{d} t }
$$

$$
{q_{\text {clist }}^{a}\left(t_{0}\right) =q_{0}^{a}, \quad q_{\text {clis }}^{a}\left(t_{1}\right)=q_{1}^{a}}
$$

Derivadas:

$$
{\delta S=\left(p_{a} \delta q^{a}-H \delta t\right)_{b}^{t_{1}}}
$$

$$
{\frac{\partial S}{\partial q_{0}^{a}}=-p_{0 a}, \quad \frac{\partial S}{\partial q_{1}^{a}}=p_{\mathrm{lu}}, \quad \frac{\partial S}{\partial t_{1}}=-H\left(q_{1}, p_{1}, t_{1}\right)}
$$

	Soluciones completas:

Condición:

$$
S(q,\alpha,t) \text{ completa} \iff \operatorname{det}\left(\partial^{2} S / \partial q^{a} \partial \alpha^{b}\right) \neq 0
$$

Solución completa es generatriz de una TC:

$$
p_{a}=\frac{\partial S(q, \alpha, t)}{\partial q^{a}}, \quad \beta_{a}=-\frac{\partial S(q, \alpha, t)}{\partial \alpha^{a}}
$$
