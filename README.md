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

**Sub-directions:** Data preprocessing, visualization, correlation analysis

**Integrated Content:**
- 📄 Papers: 20+ papers from IEEE TNNLS, IEEE TVCG, KDD, JMLR, JCP
- 🛠️ Tools: pandas, numpy, scipy, matplotlib, seaborn, plotly, bokeh, altair, statsmodels, scikit-learn
- 📊 Datasets: UQ benchmarks, UCI ML Repository, Kaggle Datasets

---

#### [Direction 2: Ensemble Modeling](resources/2-ensemble-modeling/)

**Sub-directions:** Basic modeling, model ensemble, foundation models, time series prediction, physics field modeling

**Integrated Content:**
- 📄 Papers: 30+ papers from NeurIPS, ICML, ICLR, AAAI, JCP, CMAME, RESS, NMI, TPAMI
- 🛠️ Tools: PyTorch, TensorFlow, scikit-learn, SMT, DeepXDE, Deep-aPCE, prophet, NeuralForecast
- 📊 Datasets: Monash Time Series Forecasting Archive

---

#### [Direction 3: Multiscale Reliability](resources/3-multiscale-reliability/)

**Sub-directions:** Anomaly detection, Bayesian compression, fault diagnosis, remaining useful life prediction

**Integrated Content:**
- 📄 Papers: 35+ papers from KDD, ICLR, MSSP, RESS, IEEE TIE, IEEE TNNLS, ESWA, IEEE TR
- 🛠️ Tools: PyOD, Alibi Detect, OpenSees, FERUM, UQMRLib
- 📊 Datasets: NASA Bearing, PHM Challenge, C-MAPSS, FEMTO Bearing

---

#### [Direction 4: Uncertainty Analysis](resources/4-uncertainty-analysis/) ⭐ Core

**Sub-directions:** Uncertainty calibration, deep learning UQ, uncertainty fusion, polynomial chaos expansion

**Integrated Content:**
- 📄 Papers: 40+ papers from ICML, NeurIPS, ICLR, UAI, TPAMI, JCP, CMAME, RESS, NMI, CVPR
- 🛠️ Tools: UQpy, OpenTURNS, ChaosPy, UQLab, Dakota, Uncertainty Toolbox, Bayesian Torch, Blitz, SALib
- 📊 Datasets: UQ Benchmark Problems, NASA UQ Challenge
- 🏷️ Author's Projects: [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE), [Deep-PCE-NN](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method), [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR)

---

#### [Direction 5: Uncertainty-Based Design](resources/5-uncertainty-design/)

**Sub-directions:** Generative design, robust optimization, reliability-based optimization (RBDO)

**Integrated Content:**
- 📄 Papers: 28+ papers from CMAME, JCP, RESS, MSSP, Mathematical Programming, JMD
- 🛠️ Tools: pyomo, scipy.optimize, NLopt, Dakota, OpenSees, UQMRLib, GPyTorch, PyTorch Lightning
- 📊 Datasets: Design optimization benchmarks
- 🏷️ Author's Project: [missile-design-optimization](https://github.com/Xiaohu-Zheng/missile-design-optimization)

---

### 📚 Shared Resources

| Resource | Description | Venue Coverage |
|----------|-------------|----------------|
| [**Books & Tutorials**](shared/books-tutorials.md) | Textbooks, courses, tutorials | MIT Press, Springer, SIAM |
| [**Conferences & Journals**](shared/conferences-journals.md) | Core journals and conferences | RESS, JCP, NeurIPS, ICML, etc. |
| [**Research Groups**](shared/research-groups.md) | Global research institutions | MIT, ETH, NUDT, Sandia, etc. |

---

## 🔍 Quick Index

### By Content Type

| Type | Count | Top Venues |
|------|-------|------------|
| 📄 Papers | **150+** | ICML, NeurIPS, ICLR, UAI, CVPR, KDD, AAAI, RESS, MSSP, CMAME, JCP, TPAMI, NMI, IEEE TR, ESWA |
| 🛠️ Tools | 30+ | Python, MATLAB, C++ libraries |
| 📊 Datasets | 10+ | NASA, PHM, UCI, Kaggle |
| 📚 Books | 8+ | MIT Press, Springer, SIAM |

### By Direction

| Direction | Papers | Top Venues |
|-----------|--------|------------|
| Direction 1: Data Processing | 20+ | IEEE TNNLS, IEEE TVCG, KDD, JMLR |
| Direction 2: Ensemble Modeling | 30+ | NeurIPS, ICML, ICLR, JCP, CMAME, NMI |
| Direction 3: Multiscale Reliability | 35+ | KDD, ICLR, MSSP, RESS, IEEE TIE/TNNLS |
| Direction 4: Uncertainty Analysis ⭐ | 40+ | ICML, NeurIPS, ICLR, UAI, TPAMI, JCP |
| Direction 5: Uncertainty-Based Design | 28+ | CMAME, JCP, RESS, MSSP, Math. Prog. |

### By Keywords

| Keyword | Direction | Paper Count |
|---------|-----------|-------------|
| Polynomial Chaos Expansion (PCE) | Direction 4 | 12+ |
| Deep Learning Uncertainty | Direction 4 | 15+ |
| Physics-Informed Neural Networks | Direction 2 | 10+ |
| Reliability-Based Design Optimization | Direction 5 | 10+ |
| Remaining Useful Life (RUL) | Direction 3 | 10+ |
| Anomaly Detection | Direction 3 | 10+ |
| Time Series Forecasting | Direction 2 | 8+ |
| Generative Design | Direction 5 | 9+ |

---

## 🚀 Quick Start

### For Beginners
1. 📖 Read [Direction 4: Uncertainty Analysis](resources/4-uncertainty-analysis/)
2. 🛠️ Use [UQpy](https://github.com/SURGroup/UQpy) or [ChaosPy](https://github.com/jonathf/chaospy)
3. 📚 Refer to [Books & Tutorials](shared/books-tutorials.md)

### For Researchers
1. 📰 Check [Conferences & Journals](shared/conferences-journals.md)
2. 🔬 Browse [Research Groups](shared/research-groups.md)
3. 🛠️ Explore tools in each direction

---

## 🛠️ Author's Core Projects

| Project | Description | Direction | Stars |
|---------|-------------|-----------|-------|
| [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE) | Deep learning enhanced adaptive PCE | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-aPCE?style=flat-square) |
| [Deep-PCE-NN](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) | PCE neural network method | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method?style=flat-square) |
| [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) | Physics-informed deep Monte Carlo QR | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Physics-informed-Deep-MC-QR?style=flat-square) |
| [UQMRLib](https://github.com/Xiaohu-Zheng/UQMRLib) | AI-enhanced UQ library | All directions | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMRLib?style=flat-square) |

---

## 🤝 Contributing

Contributions welcome! Fork → Add → Submit PR

### Paper Format
`| Full Title | Authors | Year | Venue | Paper Link | Code |`

---

## 📝 Citation

```bibtex
@misc{uqmrsources,
  author = {Zheng, Xiaohu},
  title = {UQMRsources: Papers and Resources for UQ and Multiscale Reliability},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/Xiaohu-Zheng/UQMRsources}
}
```

---

## 📧 Contact

- **Author**: Xiaohu Zheng
- **GitHub**: [Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

---

<div align="center">

**⭐ If helpful, please Star!**

</div>