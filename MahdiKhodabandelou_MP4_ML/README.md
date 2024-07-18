# Mini Project 4: Solving the Wumpus World Problem

## Problem 1: Solving the Wumpus World

The Wumpus World problem is a classic AI and reinforcement learning problem involving an agent navigating a grid-based environment to find gold while avoiding pits and a Wumpus. The agent's goal is to find the gold and return to the starting position without falling into pits or being eaten by the Wumpus.

### Environment Details:
- **Grid:** The environment is a grid with various cells that can contain gold, pits, and a Wumpus.
- **Agent Actions:** The agent can move up, down, left, or right.
- **Objectives:**
  - Find the gold.
  - Avoid pits and the Wumpus.
  - Return to the starting position after finding the gold.

### Rewards:
- +1000 for finding gold.
- -1000 for falling into a pit or being eaten by the Wumpus.
- -1 for each step taken.

### Parameters:
- Learning rate: 0.1
- Discount factor: 0.9
- Exploration rate: 1.0 (decays over time)

### Tasks:
1. **Q-Learning Implementation:**
   - Implement the Q-learning algorithm for the Wumpus World problem.
   - Design the agent's policy using Q-learning and Deep Q-learning.
   
2. **Agent Performance Evaluation:**
   - Plot the agent's performance using both Q-learning and Deep Q-learning.
   - Compare the performance of both algorithms over 1000 episodes.
   
3. **Exploration vs. Exploitation:**
   - Explain how the agent balances exploration and exploitation during the learning process.
   - Discuss the impact of the exploration rate on the agent's performance.

4. **Algorithm Comparison:**
   - Compare Q-learning, DQN, and other reinforcement learning algorithms.
   - Analyze which algorithm performs better and why.
   
5. **Policy Design:**
   - Design a policy for the agent using Q-learning and DQN.
   - Evaluate the policy's effectiveness in consistently finding the gold and avoiding the Wumpus.

### Instructions:
- Implement the Q-learning and Deep Q-learning algorithms.
- Train the agent using the designed algorithms.
- Plot the results and compare the performance of the algorithms.
- Analyze the agent's behavior and performance metrics.

### Additional Questions:
1. Design a Q-learning and Deep Q-learning agent for the Wumpus World problem. Explain the design choices and implementation details.
2. Plot the performance of both Q-learning and DQN agents. How does the agent's performance improve over time?
3. Compare the exploration vs. exploitation strategies used in Q-learning and DQN. How does each algorithm balance these strategies?
4. Compare the performance of Q-learning, DQN, and other reinforcement learning algorithms. Which algorithm performs better in the Wumpus World environment?
5. Design a policy for the agent using Q-learning and DQN. Which policy is more effective, and why?

## Problem 2: Deep Q-Learning for Lunar Lander

In this problem, you will design an agent using the Deep Q-Learning method to navigate the Lunar Lander environment. The goal is to design and train an agent that can land the lunar module efficiently and safely. Follow the steps below to implement and analyze the agent's performance.

### Task 1: Understanding the Lunar Lander Environment
- **Description:**
  - Study the Lunar Lander environment and describe its key features. Include details about the state space, action space, and reward system.
  - **Objective:** Understand the dynamics and challenges of the Lunar Lander environment.

### Task 2: Implementing DQN
- **Description:**
  - Implement the Deep Q-Learning (DQN) algorithm for the Lunar Lander environment. Use experience replay and target networks to stabilize training.
  - Train the agent over multiple episodes and monitor its performance using metrics such as average reward and success rate.
  - **Objective:** Train an effective DQN agent for the Lunar Lander environment.

### Task 3: Hyperparameter Tuning
- **Description:**
  - Experiment with different hyperparameters, such as learning rate, batch size, and epsilon decay rate.
  - Analyze the impact of these hyperparameters on the agent's performance and convergence speed.
  - **Objective:** Optimize the DQN agent's performance through hyperparameter tuning.

### Task 4: Performance Evaluation
- **Description:**
  - Evaluate the DQN agent's performance using metrics such as average reward per episode and success rate.
  - Compare the performance of the DQN agent with other baseline algorithms.
  - **Objective:** Assess the effectiveness of the DQN algorithm for the Lunar Lander environment.

### Additional Questions:
1. Describe the Lunar Lander environment, including its state space, action space, and reward system.
2. Implement the DQN algorithm and explain its key components, such as experience replay and target networks.
3. Train the DQN agent and plot its performance over multiple episodes. How does the agent's performance improve over time?
4. Compare the performance of the DQN agent with other reinforcement learning algorithms. Which algorithm performs better and why?
5. Discuss the impact of different hyperparameters on the DQN agent's performance. Which hyperparameters have the most significant effect?

