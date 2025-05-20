# Federico Serrano
## A time to cast away atoms, and a time to gather atoms together
I was in Spokane, Washington when I first heard about the project. [Dr. Qingze Guan](https://physics.wsu.edu/people/faculty/qingze-guan/) and [Dr. Doerte Blume](https://www.ou.edu/cqrt/people/doerte-blume) invited me to a meeting to discuss some results from an experiment devised by [Dr. Peter Engels’ group](https://labs.wsu.edu/engels/). They had been working on a theoretical explanation and were now looking to bring me on board. To be honest, the idea sounded uterly exigent for me so I wasn't excited. In the experiment, two Bose-Einstein condensates were made to collide, and the number of atoms scattered out of the condensates was measured. What caught everyone's attention was that some of these atoms ended up with negative momentum—something that shouldn't happen classically. The only way to explain it is through quantum mechanics: two atoms at rest scattering into equal and opposite momenta, $+\hbar \mathbf{k}$ and $-\hbar \mathbf{k}$. It was a subtle effect, but it was visible. I was right when I mentioned that the idea sounded uterly exigent but that was an underestimation of the cause. We quickly realized it was far more difficult and involved than expected—the more we worked on it, the more questions emerged. Before long, we started casually referring to it as **The Scattering Project**.

Even today, I still don’t have a faithful, simulation-supported description of the experiment—but I can tell what we’ve come to understand so far. The core difficulty lies in the fact that the scattering process sits right at a delicate intersection where two very different types of physics compete. In the early stages of the collision, the behavior is distinctly quantum: the scattered atoms act like a collective excitation of the condensates, well described by [Bogoliubov theory](https://link.springer.com/article/10.1007/BF02745585). But as time goes on, the scattering becomes increasingly localized and lose coherence, so it cannot be described by elementary excitations. Capturing this transition accurately is hard. It calls for beyond-mean-field methods, incorporating finite temperature effects, performing stochastic simulations, and even diagonalizing large matrices to resolve the excitation spectrum. On top of that, the finite size of the BECs adds spatial inhomogeneity, which we try to account for using different types of local density approximations. Moving smoothly between these descriptions—quantum to classical, mean-field to many-body—is precisely what makes the scattering project so tricky, and so intriguing.




The scattering project.
The problem with this project is that involved everything. 

## What crumbles away cannot be destroyed
<p float="center">
  <img src="/exp_optical_lattice.png" width="100" />
  <img src="/gp_optical_lattice.png" width="100" /> 
  <img src="/twa_optical_lattice.png" width="100" />
</p>

