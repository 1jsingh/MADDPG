# Multi-Agent Deep Deterministic Policy Gradient
Solving a Physical Deception problem using Multi-Agent Deep Deterministic Policy Gradient approach


## Agent behaviour demo

<img src="model_dir/episode-29996.gif" alt="agent_demo" width="500" height="500">

## Environment Goal

* Blue dots are the "good agents", and the Red dot is an "adversary". 
* All of the agents' goals are to go near the green target. 
* The blue agents know which one is green, but the Red agent is color-blind and does not know which target is green/black! 
* The optimal solution is for the red agent to chase one of the blue agent, and for the blue agents to split up and go toward each of the target.
