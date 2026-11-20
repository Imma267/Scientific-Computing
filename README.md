# Scientific-Computing.
A collection of Python exercises exploring numerical methods and scientific computing concepts through practical, real-world examples.

The repository progresses from NumPy fundamentals and linear algebra to differentiation, integration, optimization, differential equations, and Monte Carlo simulation. Each topic is organized into a numbered directory containing a standalone Python script.
## Requirements

- Python 3
- NumPy
- Matplotlib
- SciPy
- Pandas (used where applicable)
# Topics covered
| Topic | Example | Concepts |
|---|---|---|
| [NumPy fundamentals](Heartrate.py) | Heart-rate analysis | Arrays, statistics, filtering |
| [Vectorization](RMS%20for%20audio) | Audio RMS calculation | Efficient array operations |
| [Floating-point arithmetic](FPA.py) | Numerical error exercises | Precision and floating-point behavior |
| [Matrix algebra](dronenavigation.py) | Drone navigation | Matrix and vector operations |
| [Systems of linear equations](calorieplanning.py) | Calorie planning | Solving linear systems |
| [Gaussian elimination and LU decomposition](loadcases.py) | Structural load cases | Direct linear methods |
| [Iterative linear systems](pressure.py) | Pressure calculations | Iterative solvers |
| [Eigenvalues and eigenvectors](resonanceanalysis.py) | Resonance analysis | Spectral matrix analysis |
| [Bisection and fixed-point methods](break_even%20analysis.py) | Break-even analysis | Root finding |
| [Newton-Raphson and secant methods](circuit_analysis.py) | Circuit analysis | Open root-finding methods |
| [Polynomial and nonlinear equations](robotnavigation.py) | Robot navigation | Polynomial and nonlinear roots |
| [Interpolation](waypointselevation.py) | Waypoint elevations | Intermediate value estimation |
| [Curve fitting](bacterialgrowth.py) | Bacterial growth | Approximation and fitting |
| [Numerical differentiation](vehicletesttrack.py) | Vehicle test track | Derivative approximation |
| [Numerical integration](plasmadrugconcentration.py) | Plasma drug concentration | Trapezoidal and Simpson integration |
| [Euler's method](iodine-131decay.py) | Iodine-131 decay | Numerical solutions of ODEs |
| [Numerical solutions of ODEs](predator-preydynamics.py) | Predator-prey dynamics | Multi-variable differential equations |
| [Numerical optimization](productsratio.py) | Product ratio optimization | Finding optimal values |
| [Monte Carlo methods](constructionrisk.py) | Construction risk | Random sampling and probability estimates |

Install the dependencies:

```bash
python -m pip install numpy matplotlib scipy pandas
```


## Getting Started

Clone the repository:

```bash
git clone https://github.com/Imma267/Scientific-Computing..git
cd Scientific-Computing.
```

Run an example:

```bash
python "1.NumPy/Heartrate.py"
```


Scripts with Matplotlib visualizations open a graphical window. Console-based examples print their numerical results in the terminal.

## Example

The NumPy heart-rate example calculates the mean, minimum, maximum, and readings above 100 bpm:

```bash
python "1.NumPy/Heartrate.py"
```

END.
