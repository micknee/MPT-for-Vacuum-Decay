# MPT-for-Vacuum-Decay
Demonstrates use of the Mountain Pass Algorithm for determining field configurations for tunnelling processes with reduced symmetry. Instead of directly solving non-linear PDEs the algorithm uses a modified gradient descent to find the saddle point of the action directly.

MPT_demo.ipynb demonstrates the basic features of the algorithm by starting with an initial guess which does not have an O(4) symmetry and showing that it converges to an O(4) symmetric bubble, as expected from analytic estimates. Outputs figure showing the action converges to a minimum as the gradient descent proceeds, and a comparison of the initial and final configurations which show a convergence to an O(4) symmetric solution

The algorithm was used to find the tunnelling action for phase transitions seeded by monopoles (in arxiv.org/abs/2202.11102) and by domain walls (arxiv.org/abs/2312.06749). See also arxiv.org/abs/2512.10917 for a further application to the domain wall model
