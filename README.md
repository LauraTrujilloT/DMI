# DMI
Research project involving Dzyaloshinskii-Moriya-Interaction (DMI) in magnetic materials using Landau-Lifshitz-Gilbert-Bazily (LLGB) formalism.

## LLGB Formalism: Stationary Analysis
The generalized continuity equation for diffusive spin current has a torque contribution ![eqq](https://latex.codecogs.com/gif.latex?%5Ctextbf%7BT%7D%20%5Csim%20%5Cvec%7B%5Cmu%7D%20%5Ctimes%20%5Ctextbf%7BM%7D) over the magnetization dynamics **M** in a ferromagnet. Such dynamics is described by LLGB equation,


![my eq](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20t%7D%20%3D%20-%20%5Cgamma%20%5Ctextbf%7BM%7D%20%5Ctimes%20%5Ctextbf%7BH%7D_%7Beff%7D%20&plus;%20%5Cfrac%7B%5Calpha%7D%7BM_0%7D%20%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20t%7D%20&plus;%20%5Ctextbf%7BT%7D)


Where ![eq](https://latex.codecogs.com/gif.latex?%5Ctextbf%7BH%7D_%7Beff%7D) is the effective magnetic field given by ![eq2](https://latex.codecogs.com/gif.latex?%5Ctextbf%7BH%7D_%7Beff%7D%20%5Capprox%20%5Ctextbf%7BH%7D_%7B0%7D%20&plus;%202%20J%20%5Cgamma%5E%7B-2%7D%28%5Ckappa%20&plus;%20a_%7Bm%7D%5E%7B2%7D%20%5Cnabla%5E%7B2%7D%29%5Ctextbf%7BM%7D)

The torque contribution is represented by the following equation,


![my equation](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Ctextbf%7BT%7D%20%3D%20%5Cfrac%7Bb_%7Bje%7D%7D%7BM_0%5E2%7D%5Ctextbf%7BM%7D%5Cleft%28%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20z%7D%20%5Cright%29%20-%20%5Cfrac%7Bc_%7Bje%7D%7D%7BM_0%7D%5Ctextbf%7BM%7D%20%5Ctimes%20%5Cfrac%7B%5Cpartial%20%5Ctextbf%7BM%7D%7D%7B%5Cpartial%20z%7D)

where the parameters ![eq3](https://latex.codecogs.com/gif.latex?b_%7Bje%7D%20%3D%20%5Cmu_%7BB%7DJ_%7Be%7D%20/%20eM_0%20D_0) and ![eq4](https://latex.codecogs.com/gif.latex?c_%7Bje%7D%20%3D%20%28%5Ctau_%7Bex%7D%20/%20%5Ctau_%7Bsf%7D%29b_%7Bje%7D) are proportional to de electric current Je.

## Spin Waves: Propagation and Lifetime

As first approach, given a magnetic field such as ![eq5](https://latex.codecogs.com/gif.latex?%5Ctextbf%7Bh%7D%28%5Ctextbf%7Bx%7D%2Ct%29%20%3D%20%28h_%7B0x%7D%5Cexp%5Bi%28q_%7Bx%7Dx&plus;q_%7Bz%7Dz-%5Comega%20t%29%5D%2C0%2CH_%7B0z%7D%29), the system could be written as,


![eq6](https://latex.codecogs.com/gif.latex?L%5E%7B%5Cpm%7D%20m%5E%7B%5Cpm%7D%20%3D%20i%20%5Comega_%7BM%7D%20h%5E%7B%5Cpm%7D) 

with operator L defined by:

 ![eq7](https://latex.codecogs.com/gif.latex?L%5E%7B%5Cpm%7D%20%3D%20%5Cmp%20%281%5Cmp%20%5Calpha%29%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20t%7D%20-%20i%20D%28J%29%5Cnabla%20%5E%7B2%7D%20-%20i%28c_%7Bje%7D%20%5Cpm%20i%20b_%7Bje%7D%29%5Cfrac%7B%5Cpartial%7D%7B%5Cpartial%20z%7D%20&plus;%20i%20%5Comega_H)


The propagator of this equation takes the following form,


![eq8](https://latex.codecogs.com/gif.latex?K_%7B%5Cinfty%7D%5E%7B3D%20%5Cpm%7D%20%28%5Cvec%7Br%7D%2C%5Cvec%7Br%7D%5E%7B%5Cprime%7D%3Bt%29%20%3D%20%5Cfrac%7B1%7D%7B8%20%28%5Cpi%20a_%7B%5Cpm%7D%5E%7B2%7D%20t%29%5E%7B3/2%7D%7D%20%5Cexp%5B-%20%5Cfrac%7BG%5E%7B3D%20%5Cpm%7D%28%5Cvec%7Br%7D%2C%5Cvec%7Br%7D%5E%7B%5Cprime%7D%3Bt%29%7D%7B4%20a_%7B%5Cpm%7D%5E2%20t%7D%5D)
with

![eq9](https://latex.codecogs.com/gif.latex?G%5E%7B3D%20%5Cpm%7D%28%5Cvec%7Br%7D%2C%5Cvec%7Br%7D%5E%7B%5Cprime%7D%3Bt%29%20%3D%20%7C%5Cvec%7Br%7D%20-%20%5Cvec%7Br%7D%5E%7B%5Cprime%7D%7C%5E2%20&plus;%202b_%7B%5Cpm%7D%28z-z%5E%5Cprime%29t%20&plus;%20b_%7B%5Cpm%7D%5E2%20t%5E2%20-%204a_%7B%5Cpm%7D%5E2%20t%5E2%20%5Comega_%7BH%7D%5E%7B%5Cpm%7D) 
