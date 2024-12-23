## Purpose and Benefits

RDDL is a *compact, easily modifiable representation language for discrete time control in dynamic stochastic environments*. 
It's main feature is object-oriented relational (template) specification, which allows easy scaling of model instances from 1 object to 1000's of objects without changing the domain model.

<p align="middle">
<img src="Images/cartpole.gif" width="120" height="120" margin=0/>
<img src="Images/drones.gif" width="120" height="120" margin=0/>
<img src="Images/elevators.gif" width="120" height="120" margin=0/>
<img src="Images/hvac.gif" width="120" height="120" margin=0/>
<img src="Images/intruders.gif" width="120" height="120" margin=0/>
<img src="Images/mountaincar.gif" width="120" height="120" margin=0/>
<img src="Images/pendulum.gif" width="120" height="120" margin=0/>
<img src="Images/pong.gif" width="120" height="120" margin=0/>
<img src="Images/powergen.gif" width="120" height="120" margin=0/>
<img src="Images/quadcopter.gif" width="120" height="120" margin=0/>
<img src="Images/racecar.gif" width="120" height="120" margin=0/>
<img src="Images/reacher.gif" width="120" height="120" margin=0/>
<img src="Images/recsys.gif" width="120" height="120" margin=0/>
<img src="Images/reservoir.gif" width="120" height="120" margin=0/>
<img src="Images/rovers.gif" width="120" height="120" margin=0/>
<img src="Images/traffic.gif" width="120" height="120" margin=0/>
<img src="Images/uav.gif" width="120" height="120" margin=0/>
<img src="Images/wildfire.gif" width="120" height="120" margin=0/>
</p>

This organization hosts a variety of packages designed to help formulate and solve problems that can be described in RDDL:
* [pyRDDLGym](https://github.com/pyrddlgym-project/pyRDDLGym): automatically compiles RDDL description files into an OpenAI gym environment
* [rddlrepository](https://github.com/pyrddlgym-project/rddlrepository): hosts RDDL description files for a diverse (and growing) collection of interesting environments
* A large ecosystem of planners that work (in most cases) out-of-the-box:
    * [pyRDDLGym-jax](https://github.com/pyrddlgym-project/pyRDDLGym-jax): Provides automatic compilation of RDDL domains into JAX and ready-made gradient-based planners
    * [pyRDDLGym-gurobi](https://github.com/pyrddlgym-project/pyRDDLGym-gurobi): Supports compilation and optimization of RDDL domains into Gurobi mixed-integer problems.
    * [pyRDDLGym-prost](https://github.com/pyrddlgym-project/pyRDDLGym-prost): A DockerFile for the PROST (Monte-Carlo Tree Search) planner to interface with pyRDDLGym.
    * [pyRDDLGym-rl](https://github.com/pyrddlgym-project/pyRDDLGym-rl): Trains and evaluates RL agents from popular packages (stable-baselines3, RLlib, etc.) in pyRDDLGym.
    * [pyRDDLGym-symbolic](https://github.com/pyrddlgym-project/pyRDDLGym-symbolic): Supports Dynamic Bayes Net (DBN) extraction and symbolic dynamic programming (SDP).
* [RDDL-IDE](https://github.com/pyrddlgym-project/RDDL-IDE): a (work-in-progress) dedicated graphical IDE designed specifically for RDDL, running in Python (tk).
* [rddl-vs-code](https://github.com/danielbdias/rddl-for-vscode): a Visual Studio Code syntax highlighting present designed specifically for RDDL domains.
