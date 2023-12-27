## Solving Plasma Physics Problems using Deep Neural Networks  
Non-linear Differential Equations (DE) are solved traditionally using Finite-Definite
Iterative method. In this internship, Neural Network (NN) Technique was invoked to find
solutions to DE, by training the relevant weights of the Neurons. I trained the NN for a
certain set of parameters so that I can find solution of any other value of the independent
variable.
As a proof of principle of the above said idea, I have considered a fully nonlinear ordinary
differential equation called the Troesch's problem, often arising in Physics, in particular
Plasma Physics, as a nontrivial case study.
In the first part of the work, I used the traditional Finite Difference Iterative Scheme to find
solution of the problem satisfying the boundary conditions for a set of values of nonlinearity
parameter "mu". This datum is considered as a reference or benchmark.
In the second part, I have developed a NN based solver. I trained the Neurons on a known
set of data points on the "t" axis by invoking SQP minimizer in Python. Having trained the
Neurons, I successfully used the Neurons to obtain solution of the Troesch's problem at any
arbitrary "t" value for a given value of nonlinearity parameter "mu".
The results from my NN based DE solver was then compared with the reference or
benchmark datum and excellent agreement is demonstrated for mu values less than 2.25,
using 4 neurons. In the later part of the project, I also experimented with 10 neurons and
drew out conclusions regarding the existence of multiple roots for the same set of parameters
of MU due to high non-linearity of the differential equation.
In the future, I plan to attempt solutions of partial differential equation with more than one
independent variable. My expectation is that one should be able to construct differential
equation solvers as a "black box" routine in future, for any scientific, engineering or
technological problem based on the NN method demonstrated in my Internship.
