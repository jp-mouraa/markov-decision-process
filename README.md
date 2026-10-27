# markov-decision-process
An MDP comprises a set of world states, a
set of actions under the agent’s control, a transition model describing the probability of transitioning
to a new state when taking an action in the current state, and an objective function, e.g., maximizing
the sum of rewards obtained over a sequence of time steps.

## Requirements
```bash
conda create -n mdps python=3.13
conda activate mdps
pip install -r requirements.txt
```

## Types of MDPs
### Single-agent
- MDP
- POMDP

### Multi-agent
- DEC-MDP
- DEC-POMDP
- POSG (Partially Observable Stochastic Games)
