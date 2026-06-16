# Awesome-Deep-Q-Networks
## Deep-Q-Networks (DQNs)

Deep-Q-Networks (DQNs) blend reinforcement learning with deep neural networks. They replace traditional Q-tables to solve complex, high-dimensional decision-making problems by interacting with environments and predicting future rewards.

## Top Benchmark Examples

* **Google DeepMind's Atari Agents:** The foundational DQN breakthrough. The agent processes raw screen pixels as input and learns to master classic Atari 2600 games like *Breakout*, *Pong*, and *Space Invaders* at superhuman levels.
* **Agent57:** Developed by Google DeepMind, this algorithm builds directly on traditional DQN architecture. It incorporates short-term memory modeling and distributed training to outperform human benchmarks across all 57 tested Atari games, notably solving environments that require long-term planning.
* **Gymnasium Control Tasks (e.g., CartPole):** A standard baseline example where the DQN learns to balance a pole on a moving cart. The network takes the cart's position, velocity, angle, and angular velocity as numerical inputs to output the best action (move left or right).
* **Double DQN (DDQN):** An enhanced version of the original DQN that mitigates the algorithm's tendency to over-estimate action values. It utilizes two networks—one to select the action and another to evaluate it—improving training stability.
* **Dueling DQN:** A network architecture modification that splits the neural network into two streams: one to estimate the value of the state and another to estimate the advantage of each action. This helps the agent learn which states are inherently good without having to learn the specific effect of every action in that state.

## Core Resources

* **Research Paper:** [Playing Atari with Deep Reinforcement Learning](https://arxiv.org)
* **Code Implementation:** [Google DeepMind DQN Zoo Repository](https://github.com)
