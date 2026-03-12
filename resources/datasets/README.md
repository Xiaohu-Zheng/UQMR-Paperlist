# Datasets

> Benchmark datasets for uncertainty quantification and reliability analysis

## Classical Reliability Test Functions

| Dataset | Description | Variables | Format | Link |
|---------|-------------|-----------|--------|------|
| Cantilever Beam | Classical reliability benchmark | 2 | Python | [Link](https://...) |
| Series System | Series system reliability problem | 2 | Python | [Link](https://...) |
| Performance Function | Performance function benchmark | 2 | Python | [Link](https://...) |
| Highly Nonlinear | Highly nonlinear performance function | 2 | Python | [Link](https://...) |
| Four-Branch | Four-branch series system | 2 | Python | [Link](https://...) |

## Aerospace Structures

| Dataset | Description | Variables | Format | Link |
|---------|-------------|-----------|--------|------|
| Wing Structure | Aircraft wing reliability analysis | 10+ | HDF5 | [Link](https://...) |
| Turbine Blade | Turbine blade reliability data | 20+ | HDF5 | [Link](https://...) |

## Material Properties

| Dataset | Description | Variables | Format | Link |
|---------|-------------|-----------|--------|------|
| Steel Properties | Steel material property variability | 5 | CSV | [Link](https://...) |
| Composite Materials | Composite material uncertainties | 10+ | HDF5 | [Link](https://...) |

## Synthetic Data

| Dataset | Description | Variables | Format | Link |
|---------|-------------|-----------|--------|------|
| High-Dimensional | Synthetic high-dimensional test | 100+ | CSV | [Link](https://...) |
| Multiscale | Multiscale synthetic data | 50+ | HDF5 | [Link](https://...) |

---

## How to Use

```python
# Example: Load dataset using UQMRLib
from uqmrlib.datasets import load_cantilever_beam

problem = load_cantilever_beam()
print(problem.description)
print(f"Variables: {problem.n_vars}")
print(f"True Pf: {problem.true_pf}")
```
