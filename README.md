#  [Stochastic price model simulation with CRR parameterization](https://costargc.github.io/Project_ISYE6420/)

#### Rodrigo  Da  Costa <br> Georgia Institute of Technology, Atlanta, GA 30332

## Abstract

As part of ISYE6420 as an introduction to Bayesian Statistical Inference and applications, in this paper we define a state 
<img src="https://render.githubusercontent.com/render/math?math=\eta = \left\{ t,\sigma,r,S_{0} \right\}">. For this state, we apply a stochastic dynamic following the CRR parameterization rules with a specific case where <img src="https://render.githubusercontent.com/render/math?math=S_{0}=1">, <img src="https://render.githubusercontent.com/render/math?math=\sigma=0.3">, <img src="https://render.githubusercontent.com/render/math?math=r=0.05">. 
  
With the model, we ran 1000 simulations where each simulation had <img src="https://render.githubusercontent.com/render/math?math=n=10000"> (number of trials) within the state.  As a core results we were able to calculate giving a target price (<img src="https://render.githubusercontent.com/render/math?math=K= 1.5">). That the probability <img src="https://render.githubusercontent.com/render/math?math=S_{f}> K"> is 0.084 and that for our case (large number of trials), we show that the binomial to normal distribution approximation is acceptable and that for <img src="https://render.githubusercontent.com/render/math?math=t=1"> we obtain <img src="https://render.githubusercontent.com/render/math?math=\mu_{dist.}=1.03"> and <img src="https://render.githubusercontent.com/render/math?math=\sigma_{dist.} = 0.32">. We also identified that <img src="https://render.githubusercontent.com/render/math?math=\sigma_{dist.}"> evolves with time getting larger behaving as a diffusion coefficient. 


- [PDF link](https://costargc.github.io/Project_ISYE6420/Project_ISYE6420.pdf)
- [Python notebook](https://costargc.github.io/Project_ISYE6420/Project_ISYE6420.html)
