# Magic Squares

The N×N magic square problem, with or without given cells, solved with constraint
propagation and backtracking, simulated annealing and a genetic algorithm.
Backtracking is tested for N = 3–8, 10, 12, 15; SA and the GA also for N = 20.

## Folders

- `constraint_propagation_backtracking/`: Method 1, results `results_alg1.csv`
- `simulated_annealing/`: Method 2, results `results_sa.csv`
- `genetic_algorithm/`: Method 3, results `results_ga.csv`
- `comparison/`: compares the three methods from the CSV files
- `report/`: report source (`main.tex`) and figures

## Setup

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Running

Start `caffeinate -i python -m jupyterlab` from the repository root and run each notebook
from top to bottom (10 s limit per run; times measured on an M1):

1. `constraint_propagation_backtracking.ipynb`
2. `simulated_annealing.ipynb`
3. `genetic_algorithm.ipynb`
4. `comparison.ipynb`

Each notebook ends with correctness checks. Runs close to the 10 s limit can change on
another machine.