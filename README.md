# SOC
# 2048 Game AI with n-Tuple Network

This project is an implementation of the classic 2048 game with an AI agent that learns to play using an n-Tuple Network. The AI uses a Lookup Table (LUT) approach to evaluate board states and make decisions based on expected future rewards.

## Project Structure

1. **`game.py`**: Contains the core game logic, including the `Board` class and game mechanics.
2. **`agent.py`**: Defines the `nTupleNewrok` class, which represents the AI agent using an n-Tuple Network.
3. **`main.py`**: Handles the training and execution of the AI agent. Includes functionality to load and save agents. The path of the saved agent is displayed so that U can modify the address of the saved file of the agent in demo.py accordingly.
4. **`demo.py`**: Provides a demonstration of the trained agent playing the game.


