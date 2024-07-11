# Q-Learning Algorithm Implementation

## Description
This project implements a Q-learning algorithm to solve a reinforcement learning problem. The algorithm uses a reward matrix and a state transition matrix to learn the optimal actions for each state.

## Project Structure
- `qlearning.py`: The main script containing the Q-learning algorithm.
- `requirements.txt`: A list of dependencies required to run the project.
- `README.md`: This file, providing an overview of the project.

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/q-learning.git
    cd q-learning
    ```

2. **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To run the Q-learning algorithm, execute the `qlearning.py` script:
```bash
python qlearning.py
```

# Configuration
The Q-learning algorithm parameters can be adjusted in the qlearning.py script:

+ gamma: The discount factor.
+ reward: The reward matrix.
+ tran_matrix: The state transition matrix.
+ accion_matrix: The list of possible actions for each state.
+ iterations: The number of learning iterations.
