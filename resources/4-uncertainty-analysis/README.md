# Direction 4: Uncertainty Analysis

**Uncertainty Analysis**

---

## 📖 Overview

Uncertainty analysis is the core research direction, focusing on quantifying and propagating various types of uncertainties to provide scientific basis for reliable decision-making.

## 📂 Sub-directions

### 4.1 Uncertainty Calibration
Model calibration, probability calibration, uncertainty calibration methods

### 4.2 Uncertainty Quantification in Deep Learning
- Model uncertainty (epistemic uncertainty)
- Data uncertainty (aleatoric uncertainty)
- Bayesian neural networks, MC Dropout, deep ensembles

### 4.3 Uncertainty Fusion Methods
Multi-source uncertainty fusion, uncertainty propagation

### 4.4 Polynomial Chaos Expansion Methods
Polynomial chaos expansion (PCE), sparse PCE, adaptive PCE

---

## 📚 Related Papers

### Uncertainty Calibration

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| On Calibration of Modern Neural Networks | Guo, C., Pleiss, G., Sun, Y. & Weinberger, K. Q. | 2017 | ICML | [arXiv](https://arxiv.org/abs/1706.04599) | [GitHub](https://github.com/gpleiss/temperature_scaling) |

### Deep Learning Uncertainty Quantification

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning | Gal, Y. & Ghahramani, Z. | 2016 | ICML | [arXiv](https://arxiv.org/abs/1506.02142) | [GitHub](https://github.com/yaringal/DropoutUncertaintyExps) |
| Weight Uncertainty in Neural Networks | Blundell, C., Cornebise, J., Kavukcuoglu, K. & Wierstra, D. | 2015 | ICML | [arXiv](https://arxiv.org/abs/1505.05424) | [GitHub](https://github.com/nitarshan/bayes-by-backprop) |
| Simple and Scalable Predictive Uncertainty Estimation using Deep Ensembles | Lakshminarayanan, B., Pritzel, A. & Blundell, C. | 2017 | NeurIPS | [arXiv](https://arxiv.org/abs/1612.01474) | - |
| Evidential Deep Learning to Quantify Classification Uncertainty | Sensoy, M., Kaplan, L. & Kandemir, M. | 2018 | NeurIPS | [arXiv](https://arxiv.org/abs/1806.01768) | [GitHub](https://github.com/muratsensoy/uncertainty) |

### Polynomial Chaos Expansion

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| The Wiener-Askey Polynomial Chaos for Stochastic Differential Equations | Xiu, D. & Karniadakis, G. E. | 2002 | JCP | [DOI](https://doi.org/10.1006/jcph.2002.7023) | - |
| Adaptive sparse polynomial chaos expansion based on least angle regression | Blatman, G. & Sudret, B. | 2011 | JCP | [DOI](https://doi.org/10.1016/j.jcp.2010.11.021) | - |
| Adaptive polynomial chaos expansion for probability density function approximation | Li, H. & Xiu, D. | 2010 | JCP | [DOI](https://doi.org/10.1016/j.jcp.2010.09.041) | - |
| Deep learning enhanced adaptive polynomial chaos expansion for uncertainty quantification | Zheng, X., Yao, W. & Chen, X. | 2024 | RESS | [DOI](https://doi.org/10.1016/j.ress.2024.110456) | [GitHub](https://github.com/Xiaohu-Zheng/Deep-aPCE) |
| Physics-informed deep Monte Carlo quantile regression for uncertainty quantification | Zheng, X. et al. | 2024 | - | - | [GitHub](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) |

### Uncertainty Fusion

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| - | - | - | - | - | - |

---

## 🛠️ Related Tools

### Uncertainty Quantification

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| UQpy | Python | Comprehensive UQ library | [GitHub](https://github.com/SURGroup/UQpy) |
| OpenTURNS | Python/C++ | Open-source UQ platform | [GitHub](https://github.com/openturns/openturns) |
| ChaosPy | Python | Polynomial chaos library | [GitHub](https://github.com/jonathf/chaospy) |
| UQLab | MATLAB | MATLAB UQ framework | [Website](https://www.uqlab.com/) |
| Dakota | C++ | Sandia's UQ toolkit | [GitHub](https://github.com/sandialabs/dakota) |

### Deep Learning Uncertainty

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| Uncertainty Toolbox | Python | Uncertainty metrics and viz | [GitHub](https://github.com/uncertainty-toolbox/uncertainty-toolbox) |
| Bayesian Torch | Python | Bayesian neural networks | [GitHub](https://github.com/IntelLabs/bayesian-torch) |
| Blitz | Python | Bayesian layers in PyTorch | [GitHub](https://github.com/piEsposito/blitz-bayesian-deep-learning) |

### Sensitivity Analysis

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| SALib | Python | Sensitivity Analysis Library | [GitHub](https://github.com/SALib/SALib) |

---

## 📊 Related Datasets

| Dataset | Description | Link |
|---------|-------------|------|
| UQ Benchmark Problems | Standard UQ test problems | [UQ World](https://www.uq-world.org/) |
| NASA UQ Challenge | NASA challenge problems | [NASA](https://www.nasa.gov/) |

---

## 🏷️ Author's Core Projects

| Project | Description | Link |
|---------|-------------|------|
| Deep-aPCE | Deep learning enhanced adaptive PCE | [GitHub](https://github.com/Xiaohu-Zheng/Deep-aPCE) |
| Deep-PCE-NN | PCE neural network method | [GitHub](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) |
| Physics-informed-Deep-MC-QR | Physics-informed deep Monte Carlo QR | [GitHub](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) |

---

*Last Updated: March 2026*