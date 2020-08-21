---
title: Formulario Física Estadística

---

# Formulario de LaWebDeFisica 1

$$
S=k_{B} \ln \Omega(E, V, N)
$$

$$
\begin{array}{c}{\frac{1}{T}=\left(\frac{\partial}{\partial S} E\right)_{V, N}, \quad p=\left(\frac{\partial}{\partial S} V\right)_{E, N}} \\ {\mu=-T\left(\frac{\partial}{\partial S} N\right)_{E, V}}\end{array}
$$

$$
\Omega=\frac{1}{h^{3 N}} \int_{E<H<E+\delta E} \mathrm{d}^{3 N} q \mathrm{d}^{3 N} p
$$

$$
\lambda=\sqrt{\frac{h^{2}}{2 \pi m k_{B} T}}
$$

$$
V_{n}=C_{n} r^{n}, \quad A_{n}=n C_{n} r^{n-1}, \quad \rightarrow C_{n}=\frac{2}{n} \frac{\pi^{n / 2}}{\Gamma(n / 2)}
$$

$$
\text { Gas ideal: } S \approx k_{B} N\left(\ln \frac{V}{N}+\frac{5}{2} \ln \frac{4 m \pi E}{3 h^{2} N}+\frac{3}{2}\right)
$$

---

$$
Z=\sum_{E_{t}} \Omega_{1}\left(E_{r}\right) \mathrm{e}^{-\beta E_{r}}=\sum_{r} \mathrm{e}^{-\beta E_{r}}
$$

$$
F(T, V, N)=U-T S=-k_{B} T \ln Z
$$

$$
\begin{array}{l}{p=-\frac{\partial F}{\partial V} )_{T, N}, \quad S=-\frac{\partial F}{\partial T} )_{V, N}, \quad \mu=\frac{\partial F}{\partial N} )_{T, V}} \\ {C_{v}=\frac{\partial\langle E\rangle}{\partial T} )_{V, N}=T \frac{\partial S}{\partial T} )_{V, N}, \quad\langle E\rangle=-\frac{\partial}{\partial \beta} \ln Z )_{V, N}}\end{array}
$$

$$
(\Delta E)^{2}=\left(\frac{\partial^{2}}{\partial \beta^{2}} \ln Z\right)_{N, V}=-k_{B} T^{2} C_{v}
$$

$$
Z(T, V, N)=\frac{1}{N !} Z_{1}^{N}=\frac{1}{N ! h^{3 N}} \int \mathrm{e}^{-\beta H(p, q)} \mathrm{d}^{3 N} q \mathrm{d}^{3 N} p
$$

$$
Z_{1}(T, V)=\frac{1}{h^{3}} \int \mathrm{e}^{-\beta H(p, q)} \mathrm{d}^{3} q \mathrm{d}^{3} p
$$

$$
\left\langle x_{i} \frac{\partial H}{\partial x_{j}}\right\rangle= k_{B} T \delta_{i j}
$$

$$
H=\sum_{k=1}^{N^{\prime}} \alpha_{k} x_{k}^{\eta} \rightarrow\langle E\rangle=\frac{N^{\prime} k_{B} T}{\eta}
$$

---

$$
\mathcal{Q}(T, \mu, V)=\sum_{N_{s}=0}^{\infty} \sum_{E_{r}} \Omega\left(E_{r}, N_{s}\right) \mathrm{e}^{-\beta E_{r}+\beta \mu N_{s}}
$$

$$
z=\mathrm{e}^{\mu \nu}=\mathrm{e}^{-\alpha} : \quad \mathcal{Q}=\sum_{N_{s}=0}^{\infty} z^{N_{s}} Z\left(T, V, N_{s}\right)
$$

$$
\begin{array}{l}{\mathcal{Q}=\sum_{N_{s}}\left(z Z_{1}(T, V)\right)^{N_{s}}=\frac{1}{1-z Z_{1}}} \\ {\mathcal{Q}=\sum_{N_{\theta}} \frac{1}{N_{s} !}\left(z Z_{1}(T, V)\right)^{N_{s}}=\mathrm{e}^{z Z_{1}}}\end{array}
$$

$$
\langle N\rangle= k_{B} T \frac{\partial}{\partial \mu} \ln \mathcal{Q} )_{T, V}=-\frac{\partial}{\partial \alpha} \ln \mathcal{Q} )_{T, V}=z \frac{\partial}{\partial z} \ln \mathcal{Q} )_{T, V}
$$

$$
(\Delta N)^{2}=k_{B} T \frac{\partial}{\partial \mu}\langle N\rangle )_{T, V}=-\frac{\partial}{\partial \alpha}\langle N\rangle )_{T, V}=\frac{\langle N\rangle^{2}}{\beta V} \kappa_{T}
$$

$$
\begin{array}{c}{\langle U\rangle=-\left(\frac{\partial}{\partial \beta} \ln \mathcal{Q}\right)_{z, V}=k_{B} T^{2}\left(\frac{\partial}{\partial T} \ln \mathcal{Q}\right)_{z, V}} \\ {(\Delta U)^{2}=k_{B} T^{2} C_{v}+\left(\frac{\partial}{\partial\langle N\rangle}\langle E\rangle\right)_{T, V}^{2}(\Delta N)^{2}}\end{array}
$$

$$
\begin{array}{c}{\Xi(T, \nu, V)=-k_{B} T \ln Q \quad, \quad S=-\left(\frac{\partial \Xi}{\partial T}\right)_{V, \mu}} \\ {\Xi(T, \mu, V)=U-T S-\mu N=-p V}\end{array}
$$

---

$$
\text { Vibr. sol. } Z_{1}(\omega, T)=\mathrm{e}^{-\beta \hbar \omega / 2} /\left(1-\mathrm{e}^{-\beta \hbar \omega}\right)
$$

$$
\ln Z=\int_{\omega_{m}}^{\omega_{M}} \mathrm{d} \omega g(\omega)\left(-\beta \omega \hbar / 2-\ln \left(1-\mathrm{e}^{-\beta \hbar \omega}\right)\right)
$$

$$
U=\int_{\omega_{m}}^{\omega_{M}} \mathrm{d} \omega g(\omega)\left(\omega \hbar / 2+\frac{\hbar \omega \mathrm{e}^{-\beta \hbar \omega}}{1-\mathrm{e}^{-\beta \hbar \omega}}\right)
$$

$$
\begin{array}{c}{C_{v}=k_{B} \int_{\omega_{m}}^{\omega M} \mathrm{d} \omega g(\omega)(\beta \hbar \omega)^{2} \frac{\mathrm{e}^{\beta h \omega}}{\left(\mathrm{e}^{\beta \hbar \omega}-1\right)^{2}}} \\ {\int_{\omega_{m}}^{\omega_{M}} \mathrm{d} \omega g(\omega)=d N}\end{array}
$$

$$
\begin{aligned} \text { Einstein } g(\omega) &=3 N \delta\left(\omega-\omega_{E}\right) \\ \text { Debye } p=\frac{h \omega}{2 \pi c}, g(\omega) \mathrm{d} \omega &=\frac{1}{h^{d}} \mathrm{d}^{d} q \mathrm{d}^{d} p, \omega \in\left(0, \omega_{D}\right) \end{aligned}
$$

---

$$
\text { Eq. sólido-vapor } \mathcal{Q}_{v}=\mathrm{e}^{z_{v} Z_{v}^{1}}, \mathcal{Q}_{s}=1 /\left(1-z_{s} Z_{s}^{1}\right)
$$

$$
\begin{array}{c}{\left\langle N_{v}\right\rangle=\frac{Z_{v}^{1}}{Z_{s}^{1}} \quad, \quad N_{s}=N_{T}-N_{v}} \\ {N_{v}\left(T_{c}, V\right)=N_{T}, \quad N_{s}\left(T_{c}, V\right)=0, \quad p V=k_{B} T \frac{Z_{v}^{1}}{Z_{s}^{1}}}\end{array}
$$

---

$$
\begin{array}{l}{\text { Poliatómicas }} \\ {H=\frac{1}{2} m \dot{R}^{2}+\frac{p_{r}^{2}}{2 \mu}+\frac{L^{2}}{2 \mu r^{2}}+V(r), L^{2}=p_{\theta}^{2}+\frac{p_{\varphi}^{2}}{\sin \theta}}\end{array}
$$

$$
\begin{array}{c}{\text { Rot. } H=\frac{L^{2}}{2 I}, \quad I=\mu r_{0}^{2}, \quad \theta_{r}=\frac{\hbar^{2}}{2 I k_{B}}, \quad \varepsilon_{r}=\frac{l(l+1) \hbar^{2}}{2 I}} \\ {g_{l}=2 l+1, \quad Z_{1, r}=\sum_{l}(2 l+1) \mathrm{e}^{-l(l+1) \frac{\theta_{r}}{T}}} \\ {\text { cont. } \theta_{r} \ll T \quad Z_{1, r}=\int_{0}^{\infty} \mathrm{d} l(2 l+1) \mathrm{e}^{-l(l+1) \frac{\theta_{\mathrm{r}}}{T}}=T / \theta_{r}}\end{array}
$$

$$
\begin{array}{l}{\text { Euler-Mc Laurin, } T^{2} C_{v}=N k_{B}\left(1+\frac{1}{45}\left(\frac{\theta_{r}}{T}\right)^{2}+\cdots\right)} \\ {\text { Vibr. } H_{v}=\frac{p_{r}^{2}}{2 \mu}+\frac{1}{\mu} \omega^{2}\left(r-r_{0}\right)^{2}, \quad \theta_{v}=\frac{\hbar \omega}{k_{B}} \approx 10^{3} K}\end{array}
$$

$$
Z_{1, v}=\sum \mathrm{e}^{-\beta \hbar \omega(n+1 / 2)}=\frac{\mathrm{e}^{-\theta_{v} / T}}{1-\mathrm{e}^{-\theta_{v} / T}}
$$

---

$$
\begin{array}{l}{\text { Gas fotones } \varepsilon=c p=\hbar \omega, \omega=k c,(3 \mathrm{D}) g(\omega)=\frac{V \omega^{2}}{\pi^{2} c^{3}}} \\ {\not \exists \mu(=0)}\end{array}
$$

$u(\omega, T)=\frac{\langle n(\omega)\rangle}{V} g(\omega)=\frac{\hbar \omega}{\mathrm{e}^{\beta \hbar \omega}-1} \frac{\omega^{2}}{\pi^{2} c^{3}}$
$u(T)=\frac{\pi^{2}}{15} \frac{k_{B}^{4}}{c^{3} \hbar^{3}} T^{4}=\frac{4}{c} \sigma T^{4}$

