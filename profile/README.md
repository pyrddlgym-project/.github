## Purpose and Benefits

RDDL is a *compact, easily modifiable representation language for discrete time control in dynamic stochastic environments*. 
It's main feature is object-oriented relational (template) specification, which allows easy scaling of model instances from 1 object to 1000's of objects without changing the domain model.

This organization hosts a variety of packages designed to help formulate and solve problems that can be described in RDDL:
* [pyRDDLGym](https://github.com/pyrddlgym-project/pyRDDLGym): automatically compiles RDDL description files into an OpenAI gym environment
* [rddlrepository](https://github.com/pyrddlgym-project/rddlrepository): hosts RDDL description files for a diverse (and growing) collection of interesting environments
* A large ecosystem of planners that work (in most cases) out-of-the-box:
    * [pyRDDLGym-jax](https://github.com/pyrddlgym-project/pyRDDLGym-jax): Supports autodiff of RDDL domains through JAX compilation, and provides ready-made gradient-based planners.
    * [pyRDDLGym-gurobi](https://github.com/pyrddlgym-project/pyRDDLGym-gurobi): Supports compilation and optimization of RDDL domains into Gurobi mixed-integer problems.
    * [pyRDDLGym-prost](https://github.com/pyrddlgym-project/pyRDDLGym-prost): A DockerFile for the PROST (Monte-Carlo Tree Search) planner to interface with pyRDDLGym.
    * [pyRDDLGym-rl](https://github.com/pyrddlgym-project/pyRDDLGym-rl): Allows RL agents from popular packages (stable-baselines3, RLlib, etc.) to be trained and evaluated in pyRDDLGym.
    * [pyRDDLGym-symbolic](https://github.com/pyrddlgym-project/pyRDDLGym-symbolic): Supports symbolic regression-based planning.
* [RDDL-IDE](https://github.com/pyrddlgym-project/RDDL-IDE): a (work-in-progress) dedicated graphical IDE designed specifically for RDDL, that runs purely on Python (tk).
