# Magic Squares

The N×N magic square problem, with or without given cells, solved with constraint
propagation and backtracking, simulated annealing and a genetic algorithm.

## Folders

- `constraint_propagation_backtracking/`: Method 1, results `results_alg1.csv`
- `simulated_annealing/`: Method 2, results `results_sa.csv`
- `genetic_algorithm/`: Method 3, results `results_ga.csv`
- `comparison/`: compares the three methods from the CSV files

## Setup

Python 3.9 or newer:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Running

Start `jupyter lab` from the repository root and run each notebook from top to bottom.
Each notebook reads and writes files in its own folder.

1. `constraint_propagation_backtracking.ipynb`: about 14 min
2. `simulated_annealing.ipynb`: about 8 min
3. `genetic_algorithm.ipynb`: about 9 min
4. `comparison.ipynb`: a few seconds, needs the CSV files from 1–3
