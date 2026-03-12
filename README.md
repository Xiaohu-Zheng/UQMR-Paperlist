# UQMR-Paperlist

[![GitHub stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMR-Paperlist.svg)](https://github.com/Xiaohu-Zheng/UQMR-Paperlist/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Xiaohu-Zheng/UQMR-Paperlist.svg?color=blue)](https://github.com/Xiaohu-Zheng/UQMR-Paperlist/network)
[![License](https://img.shields.io/github/license/Xiaohu-Zheng/UQMR-Paperlist.svg?color=blue)](https://github.com/Xiaohu-Zheng/UQMR-Paperlist/blob/main/LICENSE)
[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

**Uncertainty Quantification and Multiscale Reliability Analysis: A curated list of papers, datasets, toolboxes, and resources**

**不确定量化与多尺度可靠性分析：精选论文、数据集、工具库与资源列表**

---

## 📖 Introduction

Uncertainty Quantification (UQ) and Multiscale Reliability Analysis are critical research fields in engineering and scientific computing. They aim to quantify and propagate uncertainties through complex systems, enabling reliable predictions and decision-making under uncertainty.

**This repository collects**:

- 📚 Books & Academic Papers
- 🎓 Online Courses and Videos
- 📊 Benchmark Datasets
- 🛠️ Open-source Libraries & Toolkits
- 🏆 Key Conferences & Journals

**More items will be added to the repository**. Please feel free to suggest other key resources by opening an issue report or submitting a pull request.

---

## 📑 Table of Contents

* [1. Books & Tutorials](#1-books--tutorials)
* [2. Courses & Videos](#2-courses--videos)
* [3. Toolbox & Datasets](#3-toolbox--datasets)
  * [3.1. Uncertainty Quantification](#31-uncertainty-quantification)
  * [3.2. Reliability Analysis](#32-reliability-analysis)
  * [3.3. Multiscale Methods](#33-multiscale-methods)
  * [3.4. Surrogate Models](#34-surrogate-models)
  * [3.5. Sensitivity Analysis](#35-sensitivity-analysis)
  * [3.6. Datasets](#36-datasets)
* [4. Papers](#4-papers)
  * [4.1. Polynomial Chaos Expansion](#41-polynomial-chaos-expansion)
  * [4.2. Deep Learning for UQ](#42-deep-learning-for-uq)
  * [4.3. Physics-Informed Neural Networks](#43-physics-informed-neural-networks)
  * [4.4. Multiscale Reliability](#44-multiscale-reliability)
  * [4.5. Surrogate Modeling](#45-surrogate-modeling)
  * [4.6. Overview & Survey Papers](#46-overview--survey-papers)
* [5. Key Conferences & Journals](#5-key-conferences--journals)
* [6. Research Groups](#6-research-groups)

---

## 1. Books & Tutorials

### Books

| Title | Authors | Year | Link |
|-------|---------|------|------|
| Uncertainty Quantification: Theory, Computation, and Applications | Smith, R.C. | 2014 | [Link](https://www.siam.org/publications/book/357) |
| Polynomial Chaos Methods for Hyperbolic Problems | Wan, X. & Karniadakis, G.E. | 2019 | [Link](https://www.springer.com/gp/book/9783030245496) |
| Reliability Engineering: Theory and Practice | Birolini, A. | 2017 | [Link](https://www.springer.com/gp/book/9783662530533) |
| Risk and Reliability Analysis: Theory and Applications | Modarres, M. | 2016 | [Link](https://www.crcpress.com/Risk-and-Reliability-Analysis-Theory-and-Applications/Modarres/p/book/9781498756553) |

### Tutorials

- [UQPy: Uncertainty Quantification Python](https://github.com/SURGroup/UQpy) - Comprehensive UQ tutorial and library
- [OpenTURNs: Uncertainty treatment](https://www.openturns.org/) - Open-source UQ platform with extensive documentation

---

## 2. Courses & Videos

- [MIT 16.90: Computational Methods in Aerospace Engineering](https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2006/) - Includes UQ modules
- [ICERM: Uncertainty Quantification](https://icerm.brown.edu/programs/ri/) - Research workshops and tutorials

---

## 3. Toolbox & Datasets

### 3.1. Uncertainty Quantification

| Library | Language | Description | Stars |
|---------|----------|-------------|-------|
| [UQpy](https://github.com/SURGroup/UQpy) | Python | Comprehensive UQ library | [![Stars](https://img.shields.io/github/stars/SURGroup/UQpy)](https://github.com/SURGroup/UQpy) |
| [OpenTURNS](https://github.com/openturns/openturns) | Python/C++ | Open-source UQ platform | [![Stars](https://img.shields.io/github/stars/openturns/openturns)](https://github.com/openturns/openturns) |
| [UQLab](https://www.uqlab.com/) | MATLAB | MATLAB-based UQ framework | - |
| [ChaosPy](https://github.com/jonathf/chaospy) | Python | Polynomial chaos and uncertainty quantification | [![Stars](https://img.shields.io/github/stars/jonathf/chaospy)](https://github.com/jonathf/chaospy) |
| [dakota](https://github.com/sandialabs/dakota) | C++ | Sandia's UQ toolkit | [![Stars](https://img.shields.io/github/stars/sandialabs/dakota)](https://github.com/sandialabs/dakota) |

### 3.2. Reliability Analysis

| Library | Language | Description | Stars |
|---------|----------|-------------|-------|
| [OpenSees](https://github.com/OpenSees/OpenSees) | C++ | Open-source earthquake engineering framework with reliability modules | [![Stars](https://img.shields.io/github/stars/OpenSees/OpenSees)](https://github.com/OpenSees/OpenSees) |
| [FERUM](https://github.com/ferum-software/FERUM) | MATLAB | Finite Element Reliability Using MATLAB | - |
| [UQMRLib](https://github.com/Xiaohu-Zheng/UQMRLib) | Python | AI-enhanced UQ & Multiscale Reliability Library | [![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMRLib)](https://github.com/Xiaohu-Zheng/UQMRLib) |

### 3.3. Multiscale Methods

| Library | Language | Description | Stars |
|---------|----------|-------------|-------|
| [FE2](https://github.com/dodoho/FE2) | Python | Computational homogenization | [![Stars](https://img.shields.io/github/stars/dodoho/FE2)](https://github.com/dodoho/FE2) |

### 3.4. Surrogate Models

| Library | Language | Description | Stars |
|---------|----------|-------------|-------|
| [SMT](https://github.com/SMTorg/smt) | Python | Surrogate Modeling Toolbox | [![Stars](https://img.shields.io/github/stars/SMTorg/smt)](https://github.com/SMTorg/smt) |
| [SurrogateMod](https://github.com/PatriaGovae/SurrogateMod) | Python | Modular surrogate modeling | - |

### 3.5. Sensitivity Analysis

| Library | Language | Description | Stars |
|---------|----------|-------------|-------|
| [SALib](https://github.com/SALib/SALib) | Python | Sensitivity Analysis Library | [![Stars](https://img.shields.io/github/stars/SALib/SALib)](https://github.com/SALib/SALib) |
| [sensitivity](https://github.com/betoolab/sensitivity) | Python | Global sensitivity analysis | [![Stars](https://img.shields.io/github/stars/betoolab/sensitivity)](https://github.com/betoolab/sensitivity) |

### 3.6. Datasets

- [UQ Benchmark Problems](https://www.uq-world.org/) - Standard UQ test problems
- [NASA UQ Challenge](https://www.nasa.gov/) - NASA UQ challenge problems

---

## 4. Papers

### 4.1. Polynomial Chaos Expansion

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Adaptive polynomial chaos method for reliability analysis | Li, X. et al. | 2023 | RESS | [Link]() |
| Deep learning enhanced adaptive PCE | Zheng, X. | 2024 | RESS | [Link]() |

### 4.2. Deep Learning for UQ

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Deep Polynomial Chaos Neural Network | Zheng, X. | 2024 | - | [GitHub](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) |

### 4.3. Physics-Informed Neural Networks

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Physics-informed Deep MC QR | Zheng, X. | 2024 | - | [GitHub](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) |

### 4.4. Multiscale Reliability

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Multiscale reliability analysis methods | - | - | - | - |

### 4.5. Surrogate Modeling

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| Kriging-based reliability analysis | Bichon, B.J. | 2008 | RESS | [Link]() |

### 4.6. Overview & Survey Papers

| Title | Authors | Year | Venue | Link |
|-------|---------|------|-------|------|
| A comprehensive review of uncertainty quantification | Smith, R.C. | 2014 | SIAM | [Link]() |

---

## 5. Key Conferences & Journals

### Conferences

- **ICASP** - International Conference on Applications of Statistics and Probability
- **ICOSSAR** - International Conference on Structural Safety and Reliability
- **IFIP WG 7.5** - Working Conference on Reliability and Optimization of Structural Systems
- **SIAM UQ** - SIAM Conference on Uncertainty Quantification

### Journals

- **Reliability Engineering & System Safety (RESS)** - Elsevier [Q1]
- **Structural Safety** - Elsevier [Q1]
- **Journal of Computational Physics** - Elsevier [Q1]
- **Computer Methods in Applied Mechanics and Engineering** - Elsevier [Q1]
- **Probabilistic Engineering Mechanics** - Elsevier [Q2]
- **International Journal for Uncertainty Quantification** - IJUQ

---

## 6. Research Groups

- [USC FORTIS Lab](https://github.com/USC-FORTIS) - University of Southern California
- [SUR Group](https://github.com/SURGroup) - Risk & Safety Uncertainty Quantification
- [Sandia National Labs](https://www.sandia.gov/) - Dakota development team
- [TU Delft](https://www.tudelft.nl/) - Structural Reliability Group

---

## 📧 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/NewResource`)
3. Commit your changes (`git commit -m 'Add some resource'`)
4. Push to the branch (`git push origin feature/NewResource`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📮 Contact

- **Xiaohu Zheng (小虎哥)** - [GitHub](https://github.com/Xiaohu-Zheng)
- **Research Area**: Uncertainty Quantification & Multiscale Reliability Analysis

---

## 🙏 Acknowledgments

This repository is inspired by [anomaly-detection-resources](https://github.com/yzhao062/anomaly-detection-resources) by [yzhao062](https://github.com/yzhao062).

---

*Last Updated: March 2026*

*Star ⭐ this repository if you find it helpful!*
