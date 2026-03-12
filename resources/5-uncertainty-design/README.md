# 方向 5: 不确定性设计

**Uncertainty-Based Design**

---

## 📖 概述

不确定性设计将不确定性量化方法融入设计优化过程，实现鲁棒性和可靠性驱动的工程设计。

## 📂 子方向

### 5.1 生成式设计方法
生成模型、设计空间探索、拓扑优化

### 5.2 生成式鲁棒优化方法
鲁棒优化、鲁棒设计、不确定性下的优化

### 5.3 生成式可靠性优化方法
可靠性优化、可靠性设计优化（RBDO）

---

## 📚 相关论文

### 生成式设计

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Generative design: A review | Krish | 2011 | AI EDAM | [DOI](https://doi.org/10.1017/S0890060411000038) |
| Deep generative models for design | Rego et al. | 2022 | JMD | [DOI](https://doi.org/10.1115/1.4053784) |

### 鲁棒优化

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Robust optimization: A survey | Bertsimas et al. | 2011 | Math. Prog. | [DOI](https://doi.org/10.1007/s10107-010-0357-9) |
| Robust design optimization | Beyer & Sendhoff | 2007 | CMAME | [DOI](https://doi.org/10.1016/j.cma.2007.05.004) |

### 可靠性优化

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| RBDO: A historical perspective | Yao et al. | 2019 | SMAS | [DOI](https://doi.org/10.1016/j.ymssp.2018.11.026) |
| Missile design optimization | Zheng et al. | - | - | [GitHub](https://github.com/Xiaohu-Zheng/missile-design-optimization) |

---

## 🛠️ 相关工具

### 优化框架

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| pyomo | Python | Optimization modeling | [GitHub](https://github.com/Pyomo/pyomo) |
| scipy.optimize | Python | Optimization algorithms | [SciPy](https://docs.scipy.org/doc/scipy/reference/optimize.html) |
| NLopt | C/Python | Nonlinear optimization | [GitHub](https://github.com/stevengj/nlopt) |
| Dakota | C++ | Optimization + UQ toolkit | [GitHub](https://github.com/sandialabs/dakota) |

### 可靠性设计优化

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| OpenSees | C++ | Reliability analysis + RBDO | [GitHub](https://github.com/OpenSees/OpenSees) |
| UQMRLib | Python | AI-enhanced reliability optimization | [GitHub](https://github.com/Xiaohu-Zheng/UQMRLib) |

### 生成式设计

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| GPyTorch | Python | Gaussian processes | [GitHub](https://github.com/cornellius-gp/gpytorch) |

---

## 📊 相关数据集

| Dataset | Description | Link |
|---------|-------------|------|
| Design optimization benchmarks | Standard RBDO test cases | - |

---

*Last Updated: March 2026*