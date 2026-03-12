# 方向 4: 不确定性分析

**Uncertainty Analysis**

---

## 📖 概述

不确定性分析是整个研究的核心，专注于量化和传播各类不确定性，为可靠决策提供科学依据。

## 📂 子方向

### 4.1 不确定性校准
模型校准、概率校准、不确定性校准方法

### 4.2 深度学习中的不确定性量化
- 模型不确定性（认知不确定性）
- 数据不确定性（偶然不确定性）
- 贝叶斯神经网络、MC Dropout、深度集成

### 4.3 不确定性融合方法
多源不确定性融合、不确定性传播

### 4.4 混沌多项式方法
多项式混沌展开（PCE）、稀疏PCE、自适应PCE

---

## 📚 相关论文

### 不确定性校准

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| On calibration of modern neural networks | Guo et al. | 2017 | ICML | [arXiv](https://arxiv.org/abs/1706.04599) |
| Temperature scaling for calibration | - | - | - | - |

### 深度学习不确定性量化

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Dropout as Bayesian approximation | Gal & Ghahramani | 2016 | ICML | [arXiv](https://arxiv.org/abs/1506.02142) |
| Weight uncertainty in neural networks | Blundell et al. | 2015 | ICML | [arXiv](https://arxiv.org/abs/1505.05424) |
| Deep ensembles for UQ | Lakshminarayanan et al. | 2017 | NeurIPS | [arXiv](https://arxiv.org/abs/1612.01474) |
| Evidential deep learning | Sensoy et al. | 2018 | NeurIPS | [arXiv](https://arxiv.org/abs/1806.01768) |

### 多项式混沌展开

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Polynomial Chaos for UQ | Xiu & Karniadakis | 2002 | JCP | [DOI](https://doi.org/10.1006/jcph.2002.7023) |
| Sparse PCE | Blatman & Sudret | 2011 | JCP | [DOI](https://doi.org/10.1016/j.jcp.2010.11.021) |
| Adaptive PCE | Li & Xiu | 2010 | JCP | [DOI](https://doi.org/10.1016/j.jcp.2010.09.041) |
| Deep learning enhanced adaptive PCE | Zheng et al. | 2024 | RESS | [GitHub](https://github.com/Xiaohu-Zheng/Deep-aPCE) |
| Physics-informed Deep MC QR | Zheng et al. | 2024 | - | [GitHub](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) |

### 不确定性融合

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Multi-source uncertainty fusion | - | - | - | - |

---

## 🛠️ 相关工具

### 不确定性量化

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| UQpy | Python | Comprehensive UQ library | [GitHub](https://github.com/SURGroup/UQpy) |
| OpenTURNS | Python/C++ | Open-source UQ platform | [GitHub](https://github.com/openturns/openturns) |
| ChaosPy | Python | Polynomial chaos library | [GitHub](https://github.com/jonathf/chaospy) |
| UQLab | MATLAB | MATLAB UQ framework | [Website](https://www.uqlab.com/) |
| Dakota | C++ | Sandia's UQ toolkit | [GitHub](https://github.com/sandialabs/dakota) |

### 深度学习不确定性

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| Uncertainty Toolbox | Python | Uncertainty metrics and viz | [GitHub](https://github.com/uncertainty-toolbox/uncertainty-toolbox) |
| Bayesian Torch | Python | Bayesian neural networks | [GitHub](https://github.com/IntelLabs/bayesian-torch) |
| Blitz | Python | Bayesian layers in PyTorch | [GitHub](https://github.com/piEsposito/blitz-bayesian-deep-learning) |

### 灵敏度分析

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| SALib | Python | Sensitivity Analysis Library | [GitHub](https://github.com/SALib/SALib) |

---

## 📊 相关数据集

| Dataset | Description | Link |
|---------|-------------|------|
| UQ Benchmark Problems | Standard UQ test problems | [UQ World](https://www.uq-world.org/) |
| NASA UQ Challenge | NASA challenge problems | [NASA](https://www.nasa.gov/) |

---

*Last Updated: March 2026*