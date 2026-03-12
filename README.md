# UQMR-Paperlist

<div align="center">

**不确定性量化与多尺度可靠性分析论文与资源汇总**

*Uncertainty Quantification & Multiscale Reliability Analysis Paper Collection*

[![GitHub stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMR-Paperlist?style=flat-square)](https://github.com/Xiaohu-Zheng/UQMR-Paperlist/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Xiaohu-Zheng/UQMR-Paperlist?style=flat-square)](https://github.com/Xiaohu-Zheng/UQMR-Paperlist/network/members)
[![License](https://img.shields.io/github/license/Xiaohu-Zheng/UQMR-Paperlist?style=flat-square)](LICENSE)

</div>

---

## 📖 项目简介

本项目系统整理了**不确定性量化与多尺度可靠性分析**领域的学术论文、开源工具、数据集和学习资源，覆盖从数据处理到可靠性设计的完整研究链条。

### 🎯 研究方向体系

本项目按照五大研究方向组织：

```
┌─────────────────────────────────────────────────────────────┐
│                    不确定性量化与多尺度可靠性分析                │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────┐   │
│  │ 1. 数据处理   │───▶│ 2. 集成建模   │───▶│ 3. 多尺度可靠性│   │
│  │   与分析     │    │              │    │              │   │
│  └──────────────┘    └──────────────┘    └──────────────┘   │
│         │                   │                   │            │
│         └───────────┬───────┴───────────────────┘            │
│                     ▼                                        │
│           ┌──────────────────┐                               │
│           │ 4. 不确定性分析   │                               │
│           │     (核心)       │                               │
│           └──────────────────┘                               │
│                     │                                        │
│                     ▼                                        │
│           ┌──────────────────┐                               │
│           │ 5. 不确定性设计   │                               │
│           └──────────────────┘                               │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

---

## 📂 内容导航

### 🔬 五大研究方向

#### [方向 1: 数据处理与分析](resources/1-data-processing/)
**Data Processing and Analysis**

数据预处理、可视化、相关性分析等基础方法

**子方向：**
- 数据预处理方法
- 数据可视化方法
- 数据自/互相关性分析方法

**已集成内容：**
- 📄 论文：数据预处理、数据可视化、相关性分析方法（待补充）
- 🛠️ 工具：pandas, numpy, scipy, matplotlib, seaborn, plotly
- 📊 数据集：Standard UQ benchmarks

---

#### [方向 2: 集成建模](resources/2-integrated-modeling/)
**Integrated Modeling**

统一预测框架构建，整合多种建模方法

**子方向：**
- 基础建模方法
- 模型集成方法
- 基础模型库
- 时序预测方法
- 基于深度学习的物理场建模方法

**已集成内容：**
- 📄 论文：
  - Gaussian Process for UQ (Rasmussen & Williams, 2006)
  - Physics-informed neural networks (Raissi et al., 2019)
  - Deep Polynomial Chaos (Zhang et al., 2021)
  - Neural Network Enhanced PCE (Zheng et al., 2024)
- 🛠️ 工具：
  - 机器学习：scikit-learn, PyTorch, TensorFlow
  - 代理模型：SMT, DeepXDE, Deep-aPCE
  - 时序预测：statsmodels, prophet
- 📊 数据集：Time series benchmarks

---

#### [方向 3: 多尺度可靠性](resources/3-multiscale-reliability/)
**Multiscale Reliability Analysis**

复杂系统在不同时间和空间尺度下的可靠性评估

**子方向：**
- 异常检测方法
- 贝叶斯压缩建模方法
- 故障诊断方法
- 寿命预测方法

**已集成内容：**
- 📄 论文：
  - Anomaly detection: A survey (Chandola et al., 2009)
  - Deep learning for anomaly detection (Pang et al., 2021)
  - Bayesian compression for DL (Louizos et al., 2017)
- 🛠️ 工具：
  - 异常检测：PyOD, Alibi Detect
  - 可靠性分析：OpenSees, FERUM, UQMRLib
- 📊 数据集：
  - NASA Bearing Dataset
  - PHM Challenge

---

#### [方向 4: 不确定性分析](resources/4-uncertainty-analysis/) ⭐ 核心
**Uncertainty Analysis**

不确定性量化与传播的核心方法

**子方向：**
- 不确定性校准
- 深度学习中的不确定性量化（模型不确定性、数据不确定性）
- 不确定性融合方法
- 混沌多项式方法（PCE）

**已集成内容：**
- 📄 论文：
  - **不确定性校准**：On calibration of modern neural networks (Guo et al., 2017)
  - **深度学习UQ**：
    - Dropout as Bayesian approximation (Gal & Ghahramani, 2016)
    - Weight uncertainty in neural networks (Blundell et al., 2015)
    - Deep ensembles for UQ (Lakshminarayanan et al., 2017)
    - Evidential deep learning (Sensoy et al., 2018)
  - **多项式混沌展开**：
    - Polynomial Chaos for UQ (Xiu & Karniadakis, 2002)
    - Sparse PCE (Blatman & Sudret, 2011)
    - Adaptive PCE (Li & Xiu, 2010)
    - Deep learning enhanced adaptive PCE (Zheng et al., 2024)
  - **专题论文集**：[Deep Learning Enhanced PCE](resources/4-uncertainty-analysis/papers/deep-learning-pce.md)
- 🛠️ 工具：
  - UQ框架：UQpy, OpenTURNS, ChaosPy, UQLab, Dakota
  - 深度学习UQ：Uncertainty Toolbox, Bayesian Torch, Blitz
  - 灵敏度分析：SALib
- 📊 数据集：
  - UQ Benchmark Problems
  - NASA UQ Challenge
- 🏷️ 作者核心项目：
  - [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE) - 深度学习增强的自适应PCE
  - [Deep-PCE-NN](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) - PCE神经网络方法
  - [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) - 物理信息深度蒙特卡洛QR

---

#### [方向 5: 不确定性设计](resources/5-uncertainty-design/)
**Uncertainty-Based Design**

可靠性驱动的工程设计优化方法

**子方向：**
- 生成式设计方法
- 生成式鲁棒优化方法
- 生成式可靠性优化方法

**已集成内容：**
- 📄 论文：
  - Generative design: A review (Krish, 2011)
  - Deep generative models for design (Rego et al., 2022)
  - Robust optimization: A survey (Bertsimas et al., 2011)
  - Robust design optimization (Beyer & Sendhoff, 2007)
  - RBDO: A historical perspective (Yao et al., 2019)
- 🛠️ 工具：
  - 优化框架：pyomo, scipy.optimize, NLopt, Dakota
  - RBDO：OpenSees, UQMRLib
  - 生成模型：GPyTorch
- 📊 数据集：Design optimization benchmarks
- 🏷️ 作者项目：[missile-design-optimization](https://github.com/Xiaohu-Zheng/missile-design-optimization)

---

### 📚 共享资源

| 资源 | 描述 | 已集成内容 |
|------|------|-----------|
| [**书籍与教程**](shared/books-tutorials.md) | 经典教材、在线课程、视频教程 | UQ教材、深度学习书籍、在线课程 |
| [**会议与期刊**](shared/conferences-journals.md) | 核心期刊、重要会议、投稿指南 | RESS, JCP, NeurIPS, ICML等 |
| [**研究团队**](shared/research-groups.md) | 全球研究机构与学术社区 | MIT, ETH, NUDT, Sandia等 |

---

## 🔍 快速索引

### 按内容类型

| 类型 | 数量 | 说明 |
|------|------|------|
| 📄 论文 | 30+ | 涵盖五大方向的核心论文 |
| 🛠️ 工具 | 20+ | Python/MATLAB/C++开源工具 |
| 📊 数据集 | 5+ | 标准测试数据集 |
| 📚 书籍 | 6+ | 经典教材与教程 |
| 🎓 会议期刊 | 10+ | 核心发表渠道 |

### 按关键词

| 关键词 | 相关方向 | 已集成论文 |
|--------|----------|-----------|
| 多项式混沌展开 (PCE) | 方向 4 | 5篇 |
| 深度学习不确定性 | 方向 4 | 4篇 |
| 物理信息神经网络 (PINN) | 方向 2 | 2篇 |
| 可靠性优化 (RBDO) | 方向 5 | 3篇 |
| 剩余寿命预测 (RUL) | 方向 3 | 待补充 |
| 异常检测 | 方向 3 | 2篇 |

---

## 🚀 快速开始

### 新手入门

1. 📖 阅读 [方向4: 不确定性分析](resources/4-uncertainty-analysis/) 了解核心概念
2. 🛠️ 使用 [UQpy](https://github.com/SURGroup/UQpy) 或 [ChaosPy](https://github.com/jonathf/chaospy) 开始实践
3. 📚 参考 [书籍与教程](shared/books-tutorials.md) 深入学习

### 研究者

1. 📰 查看 [会议与期刊](shared/conferences-journals.md) 了解发表渠道
2. 🔬 浏览 [研究团队](shared/research-groups.md) 寻找合作机会
3. 🛠️ 探索各方向的开源工具加速研究

---

## 🛠️ 核心开源项目

本项目作者维护的核心开源工具：

| 项目 | 描述 | 方向 | Stars |
|------|------|------|-------|
| [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE) | 深度学习增强的自适应多项式混沌展开 | 方向 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-aPCE?style=flat-square) |
| [Deep-Polynomial-Chaos-Neural-Network-Method](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) | 多项式混沌神经网络方法 | 方向 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method?style=flat-square) |
| [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) | 物理信息深度蒙特卡洛分位数回归 | 方向 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Physics-informed-Deep-MC-QR?style=flat-square) |
| [Binary-Compression-Algorithm](https://github.com/Xiaohu-Zheng/Binary-Compression-Algorithm) | 卫星系统可靠性分析二值压缩算法 | 方向 3 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Binary-Compression-Algorithm?style=flat-square) |
| [UQMRLib](https://github.com/Xiaohu-Zheng/UQMRLib) | AI增强的不确定性量化与多尺度可靠性分析库 | 全方向 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMRLib?style=flat-square) |
| [missile-design-optimization](https://github.com/Xiaohu-Zheng/missile-design-optimization) | 导弹设计优化 | 方向 5 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/missile-design-optimization?style=flat-square) |

---

## 🤝 参与贡献

欢迎参与完善本项目！

### 贡献方式

1. **Fork** 本仓库
2. **添加** 论文、工具或资源到对应方向目录
3. **提交** Pull Request

### 贡献指南

- 论文格式：`| Title | Authors | Year | Venue | Link |`
- 工具格式：`| Tool | Language | Description | Link |`
- 请确保链接有效、分类准确

### 需要补充的内容

| 方向 | 论文 | 工具 | 数据集 |
|------|------|------|--------|
| 方向 1 | ⏳ 待补充 | ✅ 已集成 | ✅ 已集成 |
| 方向 2 | ✅ 已集成 | ✅ 已集成 | ⏳ 待补充 |
| 方向 3 | ✅ 已集成 | ✅ 已集成 | ✅ 已集成 |
| 方向 4 | ✅ 已集成 | ✅ 已集成 | ✅ 已集成 |
| 方向 5 | ✅ 已集成 | ✅ 已集成 | ⏳ 待补充 |

---

## 📝 引用

如果您觉得本项目对您的研究有帮助，欢迎引用：

```bibtex
@misc{uqmr-paperlist,
  author = {Zheng, Xiaohu},
  title = {UQMR-Paperlist: A Curated List of Papers and Resources for Uncertainty Quantification and Multiscale Reliability Analysis},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/Xiaohu-Zheng/UQMR-Paperlist}
}
```

---

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

---

## 📧 联系方式

- **作者**: 小虎哥 (Xiaohu Zheng)
- **研究方向**: 不确定性量化与多尺度可靠性分析
- **GitHub**: [Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

---

<div align="center">

**⭐ 如果本项目对您有帮助，欢迎 Star 支持！**

Made with ❤️ by [Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

</div>