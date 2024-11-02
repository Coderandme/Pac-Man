<h1>Deep Convolutional Q-Learning for Pac-Man</h1>
<br>
This project applies Deep Convolutional Q-Learning (DCQN) to train an agent for playing the classic Pac-Man game. Using reinforcement learning, the model learns to make decisions by maximizing rewards over time, achieving optimal actions based on game states. <br>

**Project Overview**
The notebook demonstrates the use of DCQN, leveraging convolutional neural networks to process visual game frames and predict Q-values for each possible action. By implementing experience replay and training over numerous episodes, the agent learns to navigate the Pac-Man environment efficiently. <br>

**Key Steps**
<li>Environment and Dependencies: Uses OpenAI's Gymnasium for the Pac-Man environment and PyTorch for neural network modeling.</li>

<li>Neural Network Architecture: Constructs a convolutional network to process game frames and output Q-values for actions, optimized to handle complex visual input.</li>

<li>Hyperparameter Initialization: Sets critical parameters like learning rate, batch size, and epsilon for exploration-exploitation balance.</li>

<li>Experience Replay and DCQN Agent: Experience replay allows the agent to learn from past experiences, while the DCQN agent utilizes a neural network to select actions based on predicted Q-values.</li>

<li>Training: The agent undergoes training over thousands of episodes, improving its performance by updating the Q-values based on experience.</li>

<li>Visualization: The model’s performance is visualized by recording and displaying the agent’s gameplay, showing its decision-making and pathing in real-time.</li>
<br>

**Applications**
This approach can be adapted for tasks requiring sequential decision-making in visually rich environments, such as robotics, simulation-based training, and automated gaming agents.
<br>

**Requirements**
Required Python libraries include gymnasium, torch, numpy, imageio, and PIL. These enable environment simulation, model training, and gameplay visualization. <br>

**Summary**
The project showcases an implementation of Deep Convolutional Q-Learning in a game environment, illustrating how the model learns to perform well in a challenging, visual decision-making task.
