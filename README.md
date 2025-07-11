# Minesweeper Solvers & Benchmarking Framework

> A modular, extensible, and research-oriented framework for evaluating classical and novel Minesweeper AI solvers — featuring a new solver: **New**, designed with ...

---

## 🧠 Key Features

- 🧩 **Multiple Solver Strategies**:
  - Constraint Satisfaction Problem (CSP)
  - SAT-Based Reasoning
  - Probabilistic Analytical Fast Guess (PAFG)
  - Loreido Heuristics
  - Pedersen's Statistical Estimator
  - **[NEW]**

- 📊 **Benchmarking System**:
  - 

- ⚙️ **Designed for Researchers**:
  - 

---

## 🧪 Novel Contribution: New Solver+

**NEW** (New Solver) combines:

- 

> Designed for ...

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/minesweeper-solvers.git
cd minesweeper-solvers
make
````

> Requires: `gcc`, `make`, and optionally `minisat` or any compatible SAT solver.

---

## 🚀 Usage

Run the benchmarking tool with default configuration:

```bash
./benchmark -n 1000 -s SAT-APGTS+ -b expert
```

Run a single game visually:

```bash
./play -s PAFG -b intermediate
```

Available solvers:

```bash
./benchmark --list-solvers
```

---

## 📊 Sample Benchmark Results

| Solver         | Win Rate (%) | Guess Rate (%) | Coverage (%) |
| -------------- | ------------ | -------------- | ------------ |
| A           | 62.3         | 18.9           | 93.1         |
| B           | 64.7         | 16.5           | 94.4         |
| C           | 61.5         | 21.2           | 92.3         |
| D           | 66.0         | 15.1           | 95.1         |
| **New**     | **70.5**     | **13.3**       | **96.7**     |

> Benchmarked on 1000 runs of Expert board (16×30, 99 mines).

---

## 📂 File Structure

```
minesweeper/
├── tests/                    # Test results
│   ├── T1.md                 # Result 1
│   ├── T2.md                 # Result 2
│   ├── ...
├── solvers.ipynb             # Solvers notebook (main)
├── test.py                   # Compilation of all solvers
├── requirements.txt
```

---

## 📝 Citing This Work

If you use this framework or this solver in your research, please cite:

```bibtex
@misc{yourlastname2025minesweeper,
  title={title},
  author={Tuhin Dhar},
  year={2025},
  howpublished={GitHub repository},
  note={\url{...}}
}
```

---

## 📚 Related Works

* [Richard Kaye: Minesweeper is NP-complete](https://web.mat.bham.ac.uk/R.W.Kaye/minesw/ordmsw.pdf)
* [Loreido Heuristics](https://web.archive.org/web/20060309074150/http://web.mit.edu/sp.268/www/minesweeper.pdf)
* SAT-based symbolic model counting papers (refer to paper bibliography)

---

## 📬 Contact

For academic inquiries or collaboration: **[tuhindhar014@gmail.com](mailto:tuhindhar014@gmail.com)**

---

## 🛡️ License

This project is licensed under the MIT License. See the `LICENSE` file for details.

