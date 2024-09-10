This project is a direct implementation in 'Pytorch' of 'Physics Informed Neural Networks', introduced by Raissi et al. ([2019](https://maziarraissi.github.io/PINNs/)). PINN's are machine learning models based on neural networks which aim to reconstruct PDE and ODE solutions from limited data, usually given by the boundary and initial conditions imposed by the physical constraints of the problem, using the information encoded in the equations the model tries to solve. 

Three main different problems are discussed: Burgers equation with boundary and initial conditions, 2D time-independent Navier Stokes equations (lid driven cavity flow), and direct and indirect problems associated with the 2D time-dependent Navier Stokes equations.

The Burgers problem is used to perform a systematic study on the performance of the method in the same fashion as the original work by Raissi. 

There are 3 main directories in the repository: 'Models_Data_Figures', which contains all the trained models, the data on the exact solutions of the Burgers and time-dependente NS equations (obtained by direct numerical simulation and given in the original work), as well as the figures produced by the code; 'Notebooks', which contains the complete Google colab notebooks, and 'MainResults', which contains the main representations of the solutions predicted by the models.

Raissi, Maziar, Paris Perdikaris, and George E. Karniadakis. ["Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations."](https://www.sciencedirect.com/science/article/abs/pii/S0021999118307125) Journal of Computational Physics 378 (2019): 686-707.
