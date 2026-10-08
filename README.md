# AI Lab : 

Jupyter notebooks for the AI512 lab course, with from-scratch Python implementations and built-in self-checks.

## Labs

### Lab 1 — Intelligent Agents ([`lab1_Intelligent_Agents.ipynb`](lab1_Intelligent_Agents.ipynb))
Builds and compares rational agents in a simulated N × M Vacuum World. Covers agent/environment base classes, PEAS and environment-property classification exercises, and four agent types: simple reflex, randomized reflex, model-based reflex, and goal-based (BFS planning). Ends with a benchmark comparing their performance across many random grids.

### Lab 2 — Uninformed Search ([`LAB2_Uninformed_Search.ipynb`](LAB2_Uninformed_Search.ipynb))
Implements the five classic blind-search algorithms from scratch: BFS (queue), DFS (stack), UCS (priority queue), DLS, and IDS. Each is tested on small shared graphs and then compared side by side.

## Getting Started

```bash
git clone https://github.com/hjkanak/Ai_lab.git
cd Ai_lab
pip install jupyter numpy matplotlib
jupyter notebook
```

Run the cells top to bottom. Each section ends with a self-check that prints `PASSED` when the implementation is correct.

## Author

[@hjkanak](https://github.com/hjkanak)
