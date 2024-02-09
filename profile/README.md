## Purpose and Benefits

* Describe your environment in RDDL ([web-based intro](https://ataitler.github.io/IPPC2023/pyrddlgym_rddl_tutorial.html)), ([full tutorial](https://github.com/ataitler/pyRDDLGym?tab=readme-ov-file#tutorial)), ([language spec](https://pyrddlgym.readthedocs.io/en/latest/rddl.html)) and use it with your existing workflow for OpenAI gym environments
* Compact, easily modifiable representation language for discrete time control in dynamic stochastic environments
    * e.g., [a few lines of RDDL](https://github.com/ataitler/pyRDDLGym/blob/main/pyRDDLGym/Examples/CartPole/Continuous/domain.rddl#L61) for CartPole vs. [200 lines in direct Python for Gym](https://github.com/openai/gym/blob/master/gym/envs/classic_control/cartpole.py#L130)
* Object-oriented relational (template) specification allows easy scaling of model instances from 1 object to 1000's of objects without changing the domain model
    * e.g., [Wildfire](https://ataitler.github.io/IPPC2023/pyrddlgym_rddl_tutorial.html), [Reservoir Control](https://colab.research.google.com/drive/19O-vgPsEX7t32cqV0bABmAdRaSWSMa4g?usp=sharing)
* Out-of-the-box planners 
    * [JaxPlan](https://pyrddlgym.readthedocs.io/en/latest/jax.html): Planning through autodifferentiation
    * [GurobiPlan](https://pyrddlgym.readthedocs.io/en/latest/gurobi.html): Planning through mixed discrete-continuous optimization
    * [PROST](https://pyrddlgym.readthedocs.io/en/latest/prost.html): Monte Carlo Tree Search (MCTS)
    * [Stable Baselines RL (DQN, PPO, etc.)](https://pyrddlgym.readthedocs.io/en/latest/sb.html): Popular Reinforcement Learning (RL) algorithms
    * [Symbolic Dynamic Programming](https://github.com/ataitler/pyRDDLGym/tree/sdp/pyRDDLGym/Solvers/SDP): Exact Symbolic Regression-based planning
* Customizable [visualization](https://pyrddlgym.readthedocs.io/en/latest/start.html#visualization) and [recording](https://pyrddlgym.readthedocs.io/en/latest/start.html#recording-movies) tools facilitate domain debugging and plan interpretation
    * e.g., a student course project [visualizing Jax plans](https://github.com/CowboyTime/CISC813-Project-USV-Nav/blob/main/CISC813%20Gifs/V2_5Moving_2.gif) in a [sailing domain](https://github.com/CowboyTime/CISC813-Project-USV-Nav/blob/main/Version2/USV_obstacle_nav_v2_Domain.rddl)
* Compiler tools to extract [Dynamic Bayesian Networks (DBNs)](https://ataitler.github.io/IPPC2023/dbn.html) and [Extended Algebraic Decision Diagrams (XADDs)](https://ataitler.github.io/IPPC2023/xadd.html) for symbolic analysis of causal dependencies and transition distributions
* Runs out-of-the-box in [Python](https://github.com/ataitler/pyRDDLGym?tab=readme-ov-file#installation) or within [Colab](https://colab.research.google.com/drive/19O-vgPsEX7t32cqV0bABmAdRaSWSMa4g?usp=sharing)
