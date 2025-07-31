# ❄️ Frozen Lake - Q-Learning Agent  
[![GitHub Repo](https://img.shields.io/badge/GitHub-KhushiShukla%2FFrozenLake-blue?logo=github)](https://github.com/KhushiShukla/FrozenLake)

This project builds a simple **Q-Learning agent** to solve the classic **Frozen Lake** environment from OpenAI Gym.

The lake is slippery. The goal is to reach the frisbee at the goal tile (`G`) without falling into the icy holes (`H`). The agent learns using a **Q-table** by exploring different paths on a 4x4 grid.

---

## 🎯 Environment Layout

- `S`: Start  
- `F`: Frozen, safe  
- `H`: Hole, fall in = lose  
- `G`: Goal, reach = win
   
<pre>
S F F F
F H F H
F F F H
H F F G
</pre>
---

## 🛠️ Technologies

- Python
- NumPy
- OpenAI Gym
- Jupyter Notebook

## 💡 How It Works

- **States**: 16 tiles  
- **Actions**: Up, Down, Left, Right  
- **Learning**: Using Q-values updated with Bellman Equation  
- **Reward**: `+1` if goal is reached, else `0`

---

## 📁 Files Included

- `Frozen_Lake.ipynb` – Main training code  
- `q_table.npy` – Trained Q-table (saved after training)  

---
"Learning to cross frozen lakes, one episode at a time."
