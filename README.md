# doomRL-vizdoom_RL

This is a learning project exploring how a reinforcement learning (RL) model can play classic video games like DOOM (1993).

This project turns a **neural network** into one.  
Using **Deep Reinforcement Learning**, the agent learns to play *DOOM* from raw pixels —  
seeing, shooting purely through experience, not instructions.

Built with **PyTorch**, **VizDoom**, and the **REINFORCE** policy gradient algorithm,  
This project explores how classic game environments can train intelligent behavior  
through **trial, error, and backpropagation**.

---

## TL;DR
> A CNN-based REINFORCE agent trained to play the classic DOOM environment  
> using raw image frames and policy gradient optimization.

---

## Quick Overview

| Aspect | Description |
|--------|-------------|
| **Game Engine** | VizDoom (based on DOOM 1993) |
| **Learning Algorithm** | REINFORCE (Monte Carlo Policy Gradient) |
| **Neural Network** | 2-layer CNN + Linear Policy Head |
| **Input** | 160×120 RGB Frames |
| **Output** | Probabilistic Actions: Move Left / Move Right / Shoot |
| **Framework** | PyTorch |

---

## ⚙️ Installation

Clone this repository:
```bash
git clone https://github.com/Ab-2k/doomRL.git
