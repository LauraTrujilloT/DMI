# DMI
Research project involving Dzyaloshinskii-Moriya-Interaction (DMI) in magnetic materials using Landau-Lifshitz-Gilbert-Bazily (LLGB) formalism.

## LLGB Formalism: Stationary Analysis
The generalized continuity equation for diffusive spin current has a torque contribution ($\textbf{T} \sim \vec{\mu} \times \textbf{M}$) over the magnetization dynamics $\textbf{M}$ in a ferromagnet. Such dynamics is described by LLGB equation,


![my eq](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20t%7D%20%3D%20-%20%5Cgamma%20%5Ctextbf%7BM%7D%20%5Ctimes%20%5Ctextbf%7BH%7D_%7Beff%7D%20&plus;%20%5Cfrac%7B%5Calpha%7D%7BM_0%7D%20%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20t%7D%20&plus;%20%5Ctextbf%7BT%7D)


Where $\textbf{H}_{eff}$ is the effective magnetic field given by $\textbf{H}_{eff} \approx \textbf{H}_{0} + 2 J \gamma^{-2}(\kappa + a_{m}^{2} \nabla^{2})\textbf{M}$

The torque contribution is represented by the following equation,


![my equation](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Ctextbf%7BT%7D%20%3D%20%5Cfrac%7Bb_%7Bje%7D%7D%7BM_0%5E2%7D%5Ctextbf%7BM%7D%5Cleft%28%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20z%7D%20%5Cright%29%20-%20%5Cfrac%7Bc_%7Bje%7D%7D%7BM_0%7D%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20z%7D)

where the parameters $b_{je} = \mu_{B}J_{e} / eM_0 D_0$ and $c_{je} = (\tau_{ex} / \tau_{sf})b_{je}$ are proportional to de electric current $J_e$.

## Spin Waves: Propagation and Lifetime

As first approach, given a magnetic field such as $\textbf{h}(\textbf{x},t) = (h_{0x}\exp[i(q_{x}x+q_{z}z-\omega t)],0,H_{0z})$, the system could be written as,

$$
\begin{equation}
 L^{\pm} m^{\pm} = i \omega_{M} h^{\pm}
\end{equation}
$$
with operator $L^{\pm}$ defined by:

$$
\begin{equation}
 L^{\pm} = \mp (1\mp \alpha)\frac{\partial}{\partial t} - i D(J)\nabla ^{2} - i(c_{je} \pm i b_{je})\frac{\partial}{\partial z} + i \omega_H
\end{equation}
$$

The propagator of this equation takes the following form,

$$
\begin{equation}
K_{\infty}^{3D \pm} (\vec{r},\vec{r}^{\prime};t)
= \frac{1}{8 (\pi a_{\pm}^{2} t)^{3/2}} \exp[- \frac{G^{3D \pm}(\vec{r},\vec{r}^{\prime};t)}{4 a_{\pm}^2 t}]
\end{equation}
$$
with
$$
G^{3D \pm}(\vec{r},\vec{r}^{\prime};t) = |\vec{r} - \vec{r}^{\prime}|^2 + 2b_{\pm}(z-z^\prime)t + b_{\pm}^2 t^2 - 4a_{\pm}^2 t^2 \omega_{H}^{\pm}
$$
