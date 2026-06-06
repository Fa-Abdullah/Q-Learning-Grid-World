# Q-Learning Grid World (5x5)

A tabular Q-Learning agent navigating a 5x5 grid to reach the goal while avoiding obstacles.

## Environment

- Grid size: 5x5
- Start: (0, 0)
- Goal: (4, 4)
- Obstacles: (1,1), (2,2), (3,1)
- Actions: Up, Down, Left, Right

## Rewards

- Goal: +10
- Obstacle: -10
- Each step: -1 (encourages shortest path)

## Algorithm

- Q-Learning (off-policy)
- Epsilon-greedy exploration (ε = 0.1)
- Learning rate (α) = 0.1
- Discount factor (γ) = 0.65

## Results

The agent learns the optimal path from start to goal avoiding obstacles.

Grid Map (* is Path, X is Obstacle, G is Goal):


