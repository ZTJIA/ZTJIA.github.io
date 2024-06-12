# Autonomous Navigation for Robots in Crowd with Graph Representation and Active Learning
## Zhongtian Jia, Zhengzhou University

### Experimental Display
Below are additional demonstrations of the experiments mentioned in the paper. We will place the demonstrations using the GNN+AL method on the left for comparison, while those using the RL+AL method will be placed on the right. The demonstrations using only the GNN method exhibit similar results to those using the RL+AL method, so they will not be shown here intentionally.
#### 1. Single robot
<video src="/video/1-避免打扰.mp4" autoplay loop controls width="400" height="300"></video>
<video src="/video/1-打扰.mp4" autoplay loop controls width="400" height="300"></video>
<p>In this environment, there is interaction between humans and the laptop. The GNN+AL method can perfectly avoid intervening in the interaction, while the RL+AL method is more prone to intervene in the interaction.</p>

#### 2. Two robots
<video src="/video/2-不打扰.mp4" autoplay loop controls width="400" height="300"></video>
<video src="/video/2-打扰.mp4" autoplay loop controls width="400" height="300"></video>
<p>In the scenario with two robots, the GNN+AL method finds a more suitable path, while the RL+AL method results in collisions.</p>

#### 3. Multiple robots
<video src="/video/4-不打扰.mp4" autoplay loop controls width="400" height="300"></video>
<video src="/video/4-打扰.mp4" autoplay loop controls width="400" height="300"></video>
<p>In this environment, there is interaction between humans. In the scenario with multiple robots, the GNN+AL method still demonstrates avoidance of interactions. Meanwhile, the RL+AL method still tends to intervene in interactions more readily.</p>
