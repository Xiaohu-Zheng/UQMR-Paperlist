# UQMRsources

<div align="center">

**Uncertainty Quantification & Multiscale Reliability Analysis Resources**

*Papers, Tools, Datasets, and Learning Materials*

[![GitHub stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMRsources?style=flat-square)](https://github.com/Xiaohu-Zheng/UQMRsources/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Xiaohu-Zheng/UQMRsources?style=flat-square)](https://github.com/Xiaohu-Zheng/UQMRsources/network/members)
[![License](https://img.shields.io/github/license/Xiaohu-Zheng/UQMRsources?style=flat-square)](LICENSE)

</div>

---

## 📖 Introduction

This project systematically organizes academic papers, open-source tools, datasets, and learning resources in the field of **Uncertainty Quantification and Multiscale Reliability Analysis**, covering the complete research chain from data processing to reliability-based design.

### 🎯 Research Directions

This project is organized along five research directions:

```
┌─────────────────────────────────────────────────────────────┐
│         Uncertainty Quantification & Multiscale Reliability  │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────┐   │
│  │ 1. Data      │───▶│ 2. Ensemble  │───▶│ 3. Multiscale│   │
│  │ Processing   │    │ Modeling     │    │ Reliability  │   │
│  └──────────────┘    └──────────────┘    └──────────────┘   │
│         │                   │                   │            │
│         └───────────┬───────┴───────────────────┘            │
│                     ▼                                        │
│           ┌──────────────────┐                               │
│           │ 4. Uncertainty   │                               │
│           │ Analysis (Core)  │                               │
│           └──────────────────┘                               │
│                     │                                        │
│                     ▼                                        │
│           ┌──────────────────┐                               │
│           │ 5. Uncertainty-  │                               │
│           │ Based Design     │                               │
│           └──────────────────┘                               │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

---

## 📂 Content Navigation

### 🔬 Five Research Directions

#### [Direction 1: Data Processing and Analysis](resources/1-data-processing/)

Data preprocessing, visualization, and correlation analysis methods

**Sub-directions:**
- Data preprocessing methods
- Data visualization methods
- Auto/cross-correlation analysis methods

**Integrated Content:**
- 📄 Papers: Data preprocessing, visualization, correlation analysis (To be added)
- 🛠️ Tools: pandas, numpy, scipy, matplotlib, seaborn, plotly
- 📊 Datasets: Standard UQ benchmarks

---

#### [Direction 2: Ensemble Modeling](resources/2-ensemble-modeling/)

Unified prediction framework construction, integrating multiple modeling approaches

**Sub-directions:**
- Basic modeling methods
- Model ensemble methods
- Foundation model library
- Time series prediction methods
- Deep learning-based physics field modeling methods

**Integrated Content:**
- 📄 Papers:
  - Gaussian Processes for Machine Learning (Rasmussen & Williams, 2006, MIT Press) - [Book](http://www.gaussianprocess.org/gpml/)
  - Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear PDEs (Raissi et al., 2019, JCP) - [DOI](https://doi.org/10.1016/j.jcp.2018.10.045)
  - Deep Polynomial Chaos: An approximation theory approach (Zhang et al., 2021, JCP) - [DOI](https://doi.org/10.1016/j.jcp.2021.110543)
  - Neural network enhanced polynomial chaos method for uncertainty quantification (Zheng et al., 2024, RESS) - [DOI](https://doi.org/10.1016/j.ress.2024.110123) | [Code](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method)
- 🛠️ Tools:
  - Machine Learning: scikit-learn, PyTorch, TensorFlow
  - Surrogate Models: SMT, DeepXDE, Deep-aPCE
  - Time Series: statsmodels, prophet
- 📊 Datasets: Time series benchmarks

---

#### [Direction 3: Multiscale Reliability](resources/3-multiscale-reliability/)

Reliability assessment of complex systems across different temporal and spatial scales

**Sub-directions:**
- Anomaly detection methods
- Bayesian compression modeling methods
- Fault diagnosis methods
- Remaining useful life prediction methods

**Integrated Content:**
- 📄 Papers:
  - Anomaly detection: A survey (Chandola et al., 2009, ACM Computing Surveys) - [DOI](https://doi.org/10.1145/1541880.1541882)
  - Deep learning for anomaly detection: A review (Pang et al., 2021, TKDE) - [DOI](https://doi.org/10.1109/TKDE.2020.2983386)
  - Bayesian Compression for Deep Learning (Louizos et al., 2017, ICLR) - [arXiv](https://arxiv.org/abs/1705.08665)
- 🛠️ Tools:
  - Anomaly Detection: PyOD, Alibi Detect
  - Reliability Analysis: OpenSees, FERUM, UQMRLib
- 📊 Datasets:
  - NASA Bearing Dataset
  - PHM Challenge

---

#### [Direction 4: Uncertainty Analysis](resources/4-uncertainty-analysis/) ⭐ Core

Core methods for uncertainty quantification and propagation

**Sub-directions:**
- Uncertainty calibration
- Uncertainty quantification in deep learning (model uncertainty, data uncertainty)
- Uncertainty fusion methods
- Polynomial chaos expansion (PCE) methods

**Integrated Content:**
- 📄 Papers:
  - **Uncertainty Calibration:**
    - On Calibration of Modern Neural Networks (Guo et al., 2017, ICML) - [arXiv](https://arxiv.org/abs/1706.04599)
  - **Deep Learning UQ:**
    - Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning (Gal & Ghahramani, 2016, ICML) - [arXiv](https://arxiv.org/abs/1506.02142)
    - Weight Uncertainty in Neural Networks (Blundell et al., 2015, ICML) - [arXiv](https://arxiv.org/abs/1505.05424)
    - Simple and Scalable Predictive Uncertainty Estimation using Deep Ensembles (Lakshminarayanan et al., 2017, NeurIPS) - [arXiv](https://arxiv.org/abs/1612.01474)
    - Evidential Deep Learning to Quantify Classification Uncertainty (Sensoy et al., 2018, NeurIPS) - [arXiv](https://arxiv.org/abs/1806.01768)
  - **Polynomial Chaos Expansion:**
    - The Wiener-Askey Polynomial Chaos for Stochastic Differential Equations (Xiu & Karniadakis, 2002, JCP) - [DOI](https://doi.org/10.1006/jcph.2002.7023)
    - Adaptive sparse polynomial chaos expansion based on least angle regression (Blatman & Sudret, 2011, JCP) - [DOI](https://doi.org/10.1016/j.jcp.2010.11.021)
    - Adaptive polynomial chaos expansion for probability density function approximation (Li & Xiu, 2010, JCP) - [DOI](https://doi.org/10.1016/j.jcp.2010.09.041)
    - Deep learning enhanced adaptive polynomial chaos expansion for uncertainty quantification (Zheng et al., 2024, RESS) - [DOI](https://doi.org/10.1016/j.ress.2024.110456) | [Code](https://github.com/Xiaohu-Zheng/Deep-aPCE)
    - Physics-informed deep Monte Carlo quantile regression for uncertainty quantification (Zheng et al., 2024) - [Code](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR)
  - **Special Collection:** [Deep Learning Enhanced PCE](resources/4-uncertainty-analysis/papers/deep-learning-pce.md)
- 🛠️ Tools:
  - UQ Frameworks: UQpy, OpenTURNS, ChaosPy, UQLab, Dakota
  - Deep Learning UQ: Uncertainty Toolbox, Bayesian Torch, Blitz
  - Sensitivity Analysis: SALib
- 📊 Datasets:
  - UQ Benchmark Problems
  - NASA UQ Challenge
- 🏷️ Author's Core Projects:
  - [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE) - Deep learning enhanced adaptive PCE
  - [Deep-PCE-NN](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) - PCE neural network method
  - [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) - Physics-informed deep Monte Carlo QR

---

#### [Direction 5: Uncertainty-Based Design](resources/5-uncertainty-design/)

Reliability-driven engineering design optimization methods

**Sub-directions:**
- Generative design methods
- Generative robust optimization methods
- Generative reliability-based optimization methods

**Integrated Content:**
- 📄 Papers:
  - A practical generative design method: A review (Krish, 2011, AI EDAM) - [DOI](https://doi.org/10.1017/S0890060411000038)
  - Deep generative models for design: A review (Rego et al., 2022, JMD) - [DOI](https://doi.org/10.1115/1.4053784)
  - Robust optimization: A survey (Bertsimas et al., 2011, Mathematical Programming) - [DOI](https://doi.org/10.1007/s10107-010-0357-9)
  - Robust design optimization: A comprehensive survey (Beyer & Sendhoff, 2007, CMAME) - [DOI](https://doi.org/10.1016/j.cma.2007.05.004)
  - Reliability-based design optimization: A historical perspective (Yao et al., 2019, SMAS) - [DOI](https://doi.org/10.1016/j.ymssp.2018.11.026)
- 🛠️ Tools:
  - Optimization Frameworks: pyomo, scipy.optimize, NLopt, Dakota
  - RBDO: OpenSees, UQMRLib
  - Generative Models: GPyTorch
- 📊 Datasets: Design optimization benchmarks
- 🏷️ Author's Project: [missile-design-optimization](https://github.com/Xiaohu-Zheng/missile-design-optimization)

---

### 📚 Shared Resources

| Resource | Description | Integrated Content |
|----------|-------------|-------------------|
| [**Books & Tutorials**](shared/books-tutorials.md) | Classic textbooks, online courses, video tutorials | UQ textbooks, deep learning books, online courses |
| [**Conferences & Journals**](shared/conferences-journals.md) | Core journals, major conferences, submission guides | RESS, JCP, NeurIPS, ICML, etc. |
| [**Research Groups**](shared/research-groups.md) | Global research institutions and academic communities | MIT, ETH, NUDT, Sandia, etc. |

---

## 🔍 Quick Index

### By Content Type

| Type | Count | Description |
|------|-------|-------------|
| 📄 Papers | 30+ | Core papers covering five directions |
| 🛠️ Tools | 20+ | Python/MATLAB/C++ open-source tools |
| 📊 Datasets | 5+ | Standard benchmark datasets |
| 📚 Books | 6+ | Classic textbooks and tutorials |
| 🎓 Conferences & Journals | 10+ | Core publication venues |

### By Keywords

| Keyword | Related Direction | Integrated Papers |
|---------|-------------------|-------------------|
| Polynomial Chaos Expansion (PCE) | Direction 4 | 5 papers |
| Deep Learning Uncertainty | Direction 4 | 4 papers |
| Physics-Informed Neural Networks (PINN) | Direction 2 | 2 papers |
| Reliability-Based Design Optimization (RBDO) | Direction 5 | 3 papers |
| Remaining Useful Life (RUL) Prediction | Direction 3 | To be added |
| Anomaly Detection | Direction 3 | 2 papers |

---

## 🚀 Quick Start

### For Beginners

1. 📖 Read [Direction 4: Uncertainty Analysis](resources/4-uncertainty-analysis/) to understand core concepts
2. 🛠️ Use [UQpy](https://github.com/SURGroup/UQpy) or [ChaosPy](https://github.com/jonathf/chaospy) to start practicing
3. 📚 Refer to [Books & Tutorials](shared/books-tutorials.md) for in-depth learning

### For Researchers

1. 📰 Check [Conferences & Journals](shared/conferences-journals.md) for publication venues
2. 🔬 Browse [Research Groups](shared/research-groups.md) for collaboration opportunities
3. 🛠️ Explore open-source tools in each direction to accelerate research

---

## 🛠️ Core Open-Source Projects

Core open-source tools maintained by the project author:

| Project | Description | Direction | Stars |
|---------|-------------|-----------|-------|
| [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE) | Deep learning enhanced adaptive polynomial chaos expansion | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-aPCE?style=flat-square) |
| [Deep-Polynomial-Chaos-Neural-Network-Method](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) | Polynomial chaos neural network method | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method?style=flat-square) |
| [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) | Physics-informed deep Monte Carlo quantile regression | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Physics-informed-Deep-MC-QR?style=flat-square) |
| [Binary-Compression-Algorithm](https://github.com/Xiaohu-Zheng/Binary-Compression-Algorithm) | Binary compression algorithm for satellite system reliability analysis | Direction 3 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Binary-Compression-Algorithm?style=flat-square) |
| [UQMRLib](https://github.com/Xiaohu-Zheng/UQMRLib) | AI-enhanced uncertainty quantification and multiscale reliability library | All directions | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMRLib?style=flat-square) |
| [missile-design-optimization](https://github.com/Xiaohu-Zheng/missile-design-optimization) | Missile design optimization | Direction 5 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/missile-design-optimization?style=flat-square) |

---

## 🤝 Contributing

Contributions are welcome!

### How to Contribute

1. **Fork** this repository
2. **Add** papers, tools, or resources to the corresponding direction directory
3. **Submit** a Pull Request

### Contribution Guidelines

- Paper format: `| Full Title | Authors | Year | Venue | Paper Link | Code Link |`
- Tool format: `| Tool | Language | Description | Link |`
- Please ensure links are valid and categorization is accurate

### Content to be Added

| Direction | Papers | Tools | Datasets |
|-----------|--------|-------|----------|
| Direction 1 | ⏳ To be added | ✅ Integrated | ✅ Integrated |
| Direction 2 | ✅ Integrated | ✅ Integrated | ⏳ To be added |
| Direction 3 | ✅ Integrated | ✅ Integrated | ✅ Integrated |
| Direction 4 | ✅ Integrated | ✅ Integrated | ✅ Integrated |
| Direction 5 | ✅ Integrated | ✅ Integrated | ⏳ To be added |

---

## 📝 Citation

If you find this project helpful for your research, please consider citing:

```bibtex
@misc{uqmrsources,
  author = {Zheng, Xiaohu},
  title = {UQMRsources: A Curated Collection of Papers and Resources for Uncertainty Quantification and Multiscale Reliability Analysis},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/Xiaohu-Zheng/UQMRsources}
}
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📧 Contact

- **Author**: Xiaohu Zheng
- **Research Area**: Uncertainty Quantification and Multiscale Reliability Analysis
- **GitHub**: [Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

---

<div align="center">

**⭐ If this project is helpful, please give it a Star!**

Made with ❤️ by [Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

</div>