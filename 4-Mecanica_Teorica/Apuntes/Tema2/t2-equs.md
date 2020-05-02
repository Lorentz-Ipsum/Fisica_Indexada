<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# Sistemas Hamiltonianos

### Coordenadas unificadas

$$
H(\xi^j) = \frac{1}{2m} \xi^{i+3} \xi_{i+3} + \frac{a}{\sqrt{(\xi^1)^2 + (\xi^2)^2}} - b \xi^1 \xi_4
$$

# Flujos hamiltonianos.


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

$$
\mathcal{L}_{\Delta}g = \frac{d}{dt} g =\partial_j f \dot{\xi}^j = \partial_j f \omega^{jk} \partial_k H = \{g,H\}
$$


### Otra forma

$$
i_{X_F} \omega = dF
$$


$$
dF= \frac{\partial F}{\partial q^\alpha} dq^\alpha +  \frac{\partial F}{\partial p_\alpha} dp_\alpha
$$

$$
\phi_s^X = e^{s\mathcal{L}_X}
$$

# Derivada de Lie

$$
\color{green}{\huge X_f = \dot{\gamma} \partial_\alpha f}
$$

1-Forma

$$
\sigma = \sigma_{\alpha} d\xi^\alpha
$$

$$
i_x\sigma = (\sigma, x) = \sigma(x)= \sigma_{\alpha} x^\alpha
$$

$$
df = \partial_\alpha f d\xi^\alpha
$$

2-Forma

$$
\sigma = \sigma_{\alpha\beta}d\xi^\alpha\wedge
d\xi^\beta
$$

$$
i_x\sigma = \sigma_{\alpha\beta} x^\alpha d\xi^\beta
$$

### Transformaciones

$$
x'^\alpha = \frac{d\xi'^\alpha} { d\xi^\beta} x^\beta
$$

$$
\sigma_\alpha = \frac{d\xi^\alpha} { d\xi'^\beta} \sigma_\beta
$$
