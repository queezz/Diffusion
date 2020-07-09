# Diffusion solver notebooks

| notebook                                         | Description                                                  |
| ------------------------------------------------ | ------------------------------------------------------------ |
| [Diffusion](./Diffusion.ipynb)                   | Given incident flux, calculates permeated flux.              |
| [Diffusion_explicit](./Diffusion_explicit.ipynb) | Explicit stencil. Incident flux -> permeated. Slow.          |
| [Diffusion-copy1](./Diffusion-Copy1.ipynb)       | Crank-Nicolson Stencil explained.                            |
| [Diffusion-Copy2](./Diffusion-Copy2.ipynb)       | `numpy.linalg.solve` as solver. Save as `Diffusion`?         |
| [Diffusion](./Diffusion.ipynb)                   | `numpy.linalg.solve` as solver                               |
| [DifEq](./DifEq.ipynb)                           | Plots of one exponent and one parabola. I forgot why I made this. |
| [Diffusion_explicit](./Diffusion_explicit.ipynb) | Explicit solution of PDE. Plots: downstream flux, concentration profile. |
| [Dimensionless](./Dimensionless.ipynb)           | `scipy.linalg.solve`, dimensionless flux? Somewhat slow.     |
| [wavefit_tests](./wavefit_tests.ipynb)           | Dev for incident flux fit using my `BE`I think it is Crank-Nicolson Method. |
| [Simple_test](./Simple_test.ipynb)               | Three methods: forward, backward Euler, and Crank-Nicolson. Boundary: constant, zero. |
| [Stencils](./Stencils.ipynb)                     | Explicit central difference stencil                          |
| [Try_new_mesh](./Try_new_mesh.ipynb)             | Some "new mesh". Uses `numpy.linalg.solve`.                  |
| [CompareData-test](./CompareData-test.ipynb)     | I think I compared data from python calculation with TMAP7, or something like that. |

