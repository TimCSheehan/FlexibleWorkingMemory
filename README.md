# FlexibleWorkingMemory
Simplified code for the paper "A Flexible Model of Working Memory" Bouchacourt and Buschman, 2019.
This code is written in Python and is using the Brian2 spiking network simulator (https://brian2.readthedocs.io/en/stable/) so you will need brian2 and brian2tools to use it.

run_a_trial.py is calling FlexibleWM.py. A dictionnary is provided for the parameters taking different value from default (e.g. if you want to change the simulation time). 

To run multiple simulations over multiple networks on a cluster, you can use the python multiprocessing package. If you plan to use it we can push the script. In general, it is better to use multiple arrays with slurm instead.
If you are interested in seeing the script of specific paper analyses, or of the 2D surface or Hopfield-like sensory networks, please email us and we will push it.



