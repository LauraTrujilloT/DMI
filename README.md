# DMI
Research project involving Dzyaloshinskii-Moriya-Interaction (DMI) in magnetic materials using Landau-Lifshitz-Gilbert-Bazily (LLGB) formalism.

## LLGB Formalism: Stationary Analysis
The generalized continuity equation for diffusive spin current has a torque contribution ![eq](https://latex.codecogs.com/gif.latex?%5Ctextbf%7BT%7D%20%5Csim%20%5Cvec%7B%5Cmu%7D%20%5Ctimes%20%5Ctextbf%7BM%7D) over the magnetization dynamics **M** in a ferromagnet. Such dynamics is described by LLGB equation,


![my eq](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20t%7D%20%3D%20-%20%5Cgamma%20%5Ctextbf%7BM%7D%20%5Ctimes%20%5Ctextbf%7BH%7D_%7Beff%7D%20&plus;%20%5Cfrac%7B%5Calpha%7D%7BM_0%7D%20%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20t%7D%20&plus;%20%5Ctextbf%7BT%7D)


Where ![eq](https://latex.codecogs.com/gif.latex?%5Ctextbf%7BH%7D_%7Beff%7D) is the effective magnetic field given by ![eq2](https://latex.codecogs.com/gif.latex?%5Ctextbf%7BH%7D_%7Beff%7D%20%5Capprox%20%5Ctextbf%7BH%7D_%7B0%7D%20&plus;%202%20J%20%5Cgamma%5E%7B-2%7D%28%5Ckappa%20&plus;%20a_%7Bm%7D%5E%7B2%7D%20%5Cnabla%5E%7B2%7D%29%5Ctextbf%7BM%7D)

The torque contribution is represented by the following equation,


![my equation](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Ctextbf%7BT%7D%20%3D%20%5Cfrac%7Bb_%7Bje%7D%7D%7BM_0%5E2%7D%5Ctextbf%7BM%7D%5Cleft%28%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20z%7D%20%5Cright%29%20-%20%5Cfrac%7Bc_%7Bje%7D%7D%7BM_0%7D%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20z%7D)

where the parameters ![eq3](https://latex.codecogs.com/gif.latex?b_%7Bje%7D%20%3D%20%5Cmu_%7BB%7DJ_%7Be%7D%20/%20eM_0%20D_0) and ![eq4](https://latex.codecogs.com/gif.latex?c_%7Bje%7D%20%3D%20%28%5Ctau_%7Bex%7D%20/%20%5Ctau_%7Bsf%7D%29b_%7Bje%7D) are proportional to de electric current Je.

## Spin Waves: Propagation and Lifetime

As first approach, given a magnetic field such as ![eq5](https://latex.codecogs.com/gif.latex?%5Ctextbf%7Bh%7D%28%5Ctextbf%7Bx%7D%2Ct%29%20%3D%20%28h_%7B0x%7D%5Cexp%5Bi%28q_%7Bx%7Dx&plus;q_%7Bz%7Dz-%5Comega%20t%29%5D%2C0%2CH_%7B0z%7D%29), the system could be written as,


![eq6](https://latex.codecogs.com/gif.latex?L%5E%7B%5Cpm%7D%20m%5E%7B%5Cpm%7D%20%3D%20i%20%5Comega_%7BM%7D%20h%5E%7B%5Cpm%7D) 

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
