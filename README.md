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

---

```
## 📚 Citation

This project uses the [VizDoom](https://vizdoom.cs.put.edu.pl/) environment for reinforcement learning research.

> M. Wydmuch, M. Kempka, and W. Jaśkowski,  
> **"ViZDoom Competitions: Playing Doom from Pixels,"**  
> *IEEE Transactions on Games*, vol. 11, no. 3, pp. 248–259, 2019.  
> [arXiv:1809.03470](https://arxiv.org/abs/1809.03470)  
> DOI: [10.1109/TG.2018.2877047](https://doi.org/10.1109/TG.2018.2877047)

---

### BibTeX
```bibtex
@article{Wydmuch2019ViZdoom,
  author  = {Marek Wydmuch and Micha{\l} Kempka and Wojciech Ja\'skowski},
  title   = {{ViZDoom} {C}ompetitions: {P}laying {D}oom from {P}ixels},
  journal = {IEEE Transactions on Games},
  year    = {2019},
  volume  = {11},
  number  = {3},
  pages   = {248--259},
  doi     = {10.1109/TG.2018.2877047},
  note    = {The 2022 IEEE Transactions on Games Outstanding Paper Award}
}




