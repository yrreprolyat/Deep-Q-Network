![](https://media.giphy.com/media/3og0IEKu84Ros9izyU/giphy.gif)


## Description
A project that implements the DQN reinforcement agent that is applied
to a [2d-car-racing environment](https://gym.openai.com/envs/CarRacing-v0) from 
Open AI.For reference, see [Human-level control through deep reinforcement
learning](http://www.davidqiu.com:8888/research/nature14236.pdf)


It takes the agent approximately 3 hours to learn how to drive the vehicle.
The base agent is ignorant of racing and there are no hand-crafted features required.


## Pre-trained agent
The checkpoint provided in the repo used the default parameters
specified in the runner/agent and 150000~ playing steps for learning. The training took about 5h with CPU. The agent sometimes cuts corners but other than that it can drive flawlessly for minutes.

## Reqs
- Python 3.5 or greater
- Tensorflow
- OpenAI Gym 
- scikit-image
- numpy
