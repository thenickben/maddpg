
### Multi-Agent Particle Environment
# Physical deception multi-agent game

As seen in [here](https://github.com/openai/multiagent-particle-envs) with some coding twists.

### Env description

One adversary (red), N good agents (green), N landmarks (usually N=2). All agents observe position of landmarks and other agents. One landmark is the ‘target landmark’ (colored green). Good agents rewarded based on how close one of them is to the target landmark, but negatively rewarded if the adversary is close to target landmark. Adversary is rewarded based on how close it is to the target, but it doesn’t know which landmark is the target landmark. So good agents have to learn to ‘split up’ and cover all landmarks to deceive the adversary.

### How to use this repo
Clone this repo and go through the notebook maddpg_physical_deception_v1.ipynb

### Results

The notebook provides helper functions to visualize the agents interacting within the environment, as well as their learning curves.

#### Before training


#### After training