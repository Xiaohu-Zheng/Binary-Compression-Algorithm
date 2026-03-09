# Binary-Compression-Algorithm

[![CI/CD Pipeline](https://github.com/Xiaohu-Zheng/Binary-Compression-Algorithm/workflows/CI/CD%20Pipeline/badge.svg)](https://github.com/Xiaohu-Zheng/Binary-Compression-Algorithm/actions)
[![Python](https://img.shields.io/badge/python-3.8%20%7C%203.9%20%7C%203.10-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![MATLAB](https://img.shields.io/badge/MATLAB-Compatible-orange)](https://www.mathworks.com/)

**Improved Compression Inference Algorithm for Reliability Analysis of Complex Multistate Satellite System**

## 📖 Overview

This repository implements the binary compression algorithm presented in the paper:

> **Improved compression inference algorithm for reliability analysis of complex multistate satellite system based on multilevel Bayesian Network**  
> *Zheng, Xiaohu et al.*

## 🌟 Key Features

- **Binary Compression**: Efficient compression of Bayesian Network structures
- **Multistate System Analysis**: Reliability analysis for complex satellite systems
- **Multilevel Bayesian Network**: Advanced probabilistic modeling
- **Inference Algorithm**: Improved computational efficiency
- **MATLAB Implementation**: Easy-to-use MATLAB scripts

## 🚀 Quick Start

### Prerequisites

- MATLAB R2018a or later
- Statistics and Machine Learning Toolbox

### Installation

```bash
# Clone the repository
git clone https://github.com/Xiaohu-Zheng/Binary-Compression-Algorithm.git
cd Binary-Compression-Algorithm

# Extract the MATLAB files
unzip binary_compression_algorithm.zip
```

### Basic Usage

```matlab
% Navigate to the extracted directory
cd binary_compression_algorithm

% Run the case study
Case_study_Compress_methods
```

## 📁 Project Structure

```
Binary-Compression-Algorithm/
├── binary_compression_algorithm.zip    # Compressed MATLAB files
│   ├── Case_study_Compress_methods.m  # Main case study script
│   ├── improve_AlgorithmB.m           # Improved Algorithm B
│   ├── improve_Inference_B.m          # Inference algorithm
│   ├── improve_compressF_cCPTsys.m    # Compression functions
│   ├── improve_Multi_sys_*.m          # Multi-system analysis
│   ├── F_CPTsys.m                     # CPT system functions
│   ├── Identi_*.m                     # Identification functions
│   └── ... (other utilities)
├── .github/workflows/                  # CI/CD configuration
│   └── ci.yml
├── tests/                              # Test suite
│   └── test_basic.py
├── .gitignore
├── requirements.txt
├── LICENSE                             # MIT License
└── README.md                           # This file
```

## 🔧 Core Algorithms

### 1. Binary Compression Algorithm

```matlab
% Compress the Bayesian Network structure
compressed_net = improve_AlgorithmB(network_structure)
```

### 2. Inference Algorithm

```matlab
% Perform reliability inference
reliability = improve_Inference_B(compressed_net, evidence)
```

### 3. Multi-System Analysis

```matlab
% Analyze multistate satellite systems
system_reliability = improve_Multi_sys_AlgorithmB(system_config)
```

## 📊 Algorithm Description

### Binary Compression

The algorithm compresses Bayesian Network structures by:

1. **Identifying Minimal Cut Sets (MCS)**: Finds critical failure paths
2. **State Dependency Sets (SDS)**: Groups dependent components
3. **CPT Compression**: Compresses Conditional Probability Tables
4. **Multilevel Processing**: Handles hierarchical system structures

### Mathematical Foundation

The compression ratio is defined as:

```
CR = (Original_Size - Compressed_Size) / Original_Size
```

## 🎯 Applications

- **Satellite Systems**: Reliability analysis of multistate components
- **Complex Systems**: Large-scale system reliability assessment
- **Bayesian Networks**: Efficient inference in large networks
- **Risk Analysis**: Probabilistic risk assessment

## 📈 Performance

- **Efficiency**: Reduced computational complexity
- **Scalability**: Handles large-scale systems
- **Accuracy**: Maintains inference accuracy

## 🧪 Examples

### Case Study

```matlab
% Run the complete case study
Case_study_Compress_methods

% This will:
% 1. Load the satellite system configuration
% 2. Apply binary compression
% 3. Perform reliability inference
% 4. Display results and comparisons
```

### Custom Analysis

```matlab
% Define your system structure
system = define_system();

% Apply compression
compressed = improve_AlgorithmB(system);

% Calculate reliability
reliability = improve_Inference_B(compressed);
```

## 📖 Citation

If you use this code in your research, please cite:

```bibtex
@article{Zheng2023BinaryCompression,
   author = {Zheng, Xiaohu and others},
   title = {Improved compression inference algorithm for reliability analysis of complex multistate satellite system based on multilevel Bayesian Network},
   journal = {Journal Name},
   year = {2023}
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- **Author**: Xiaohu Zheng
- **Email**: zhengxiaohu16@nudt.edu.cn
- **GitHub**: [@Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

## 🙏 Acknowledgments

- National University of Defense Technology
- Research collaborators

---

**Star ⭐ this repository if you find it helpful!**
