# Tri-Phase Reasoning Intelligence for Minesweeper Solving (**TRIMS**)

A modular, extensible, and research-oriented framework for novel Minesweeper AI solver named **TRIMS**.

---

## 🧠 Key Features

- Introduces a novel approach for minesweeper solving **TRIMS (This Paper)**

- **10,000** trials for beginner, intermediate and hard difficulties of minesweeper board configurations

- **Designed for Researchers**:
  - Modular codebase for easy extension and experimentation
  - Jupyter notebooks for rapid prototyping and visualization

---

## 🧪 Novel Contribution: TRIMS Solver

**TRIMS** combines:

- Fast deterministic constraint propagation
- Probabilistic reasoning for uncertain moves
- Emergency heuristics for deadlock situations

Designed for robust, high-performance Minesweeper solving and benchmarking.

---

## 🛠️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/MaskofDevil/trims_solver.git
cd trims_solver
pip install -r requirements.txt
```

> Requires: Python 3.8+ and `pip`.

---

## 🚀 Usage

Open `trims.ipynb` in Jupyter Notebook or VS Code and run all cells to run TRIMS and visualize results against other SOTA solvers.

---

## 📦 Requirements

All required Python packages are listed in `requirements.txt`:

```
numpy
matplotlib
python-constraint
pysat
```

Install with:

```bash
pip install -r requirements.txt
```

---

## 📊 Sample Benchmark Results

| Solver               | Beginner | Intermediate | Expert |
|----------------------|----------|--------------|--------|
| TRIMS (This Paper)   | 99.0%    | 94.4%        | 73.1%  |
| PAFG                 | 96.4%    | 86.3%        | 45.6%  |
| PSEQ-D256            | 81.8%    | 78.2%        | 40.1%  |
| PSEQ                 | 81.6%    | 78.1%        | 39.6%  |
| OH                   | 80.2%    | 74.4%        | 38.7%  |
| cSimEnuLoClf         | 80.0%    | 75.6%        | 37.5%  |
| CSP                  | 80.0%    | 44.3%        | 33.9%  |
| CSCSP                | —        | 75.9%        | 32.9%  |
| Pedersen             | 92.5%    | 67.7%        | 25.0%  |

> Benchmarked on Beginner (9×9, 10 mines), Intermediate (16×16, 40 mines), and Expert (16×30, 99 mines) boards.

![alt text](/Img/output.png)

---

## 📂 File Structure

```
trims_solver/
├── Fonts/                    # Custom Fonts
│   ├── lmroman10-bold.otf
│   ├── lmroman10-italic.otf
│   ├── lmroman10-regular.otf
├── Img/                      # Images
│   ├── lmroman10-bold.otf
├── trims.ipynb               # TRIMS solver and benchmarking
├── requirements.txt
├── README.md
```

---

## 📝 Using This Work

If you use this framework or this solver in your research or anywhere, please give proper reference.

---

## 📚 Related Works

* [Richard Kaye: Minesweeper is NP-complete](https://web.mat.bham.ac.uk/R.W.Kaye/minesw/ordmsw.pdf)
* [Loreido Heuristics](https://web.archive.org/web/20060309074150/http://web.mit.edu/sp.268/www/minesweeper.pdf)

---

## 📬 Contact

For academic inquiries or collaboration: **[tuhindhar014@gmail.com](mailto:tuhindhar014@gmail.com)**

