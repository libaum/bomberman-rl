<div align="center">
  <h1>💣 Bomberman RL</h1>

  <p>
    <strong>Deep Reinforcement Learning Agent for Bomberman</strong>
  </p>

  <p>
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Language-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /></a>
    <img src="https://img.shields.io/badge/Framework-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
    <img src="https://img.shields.io/badge/Algorithm-DQN-orange?style=flat-square" alt="DQN" />
  </p>
</div>

## 💡 About

This project implements an autonomous agent capable of playing the classic game **Bomberman**. The primary agent, **Deep Quapsel**, utilizes **Deep Q-Learning (DQN)** to navigate the grid, collect coins, and strategically eliminate opponents.

The framework simulates a full game environment including destructible crates, power-ups, and hostile adversaries.

---

## 🤖 Agents

* **Deep Quapsel:** The main RL-agent trained with a Deep Q-Network and Experience Replay.
* **Rule-Based Agent:** A heuristic agent used as a baseline and training adversary.
* **Coin Collector:** A simple agent focused solely on pathfinding and gathering loot.

---

## 🚀 Usage

### Installation
1.  **Clone the repo**
    ```bash
    git clone https://github.com/libaum/bomberman-rl.git
    ```
2.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

### Running a Match
To watch the agent play against reference agents, run:

```bash
python main.py play --agents deep_quapsel rule_based_agent coin_collector_agent
