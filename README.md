# grid-world-q-learning
Optimal Agent Behavior in Grid-World Environment Using Q-Learning

The code is designed for a single agent in a square grid world of size n to learn a simple transport task. The agent's task is to pick up the item at location A and deliver it to a fixed target location B. A is not known in advance, ie. it varies each time the agent needs to solve the task. B is the bottom right corner of the grid at coordinates (n,n). The coordinates of A are part of the state information that the agent receives.

The agent starts at a random location. When it reaches location A it automatically picks up the item, when it reaches location B it automatically discharges the item. At this point, it has completed its task.

The agent is allowed to observe its own location, the location of A and whether it carries an item. The task the agent learns is to pick up the load at A and deliver it to B, taking as few steps as possible regardless of its (random) starting position.
