
# MOBGA-AOS: Multi-Objective Binary Genetic Algorithm with Adaptive Operator Selection

## Introduction
MOBGA-AOS is an implementation of the multi-objective binary genetic algorithm integrating an adaptive operator selection mechanism proposed in the paper "Adaptive Crossover Operator Based Multi-Objective Binary Genetic Algorithm for Feature Selection in Classification". This project is designed to address feature selection challenges in classification tasks by effectively reducing feature dimensions while maintaining or improving classification accuracy.

## Features
- **Adaptive Operator Selection**: Dynamically selects the most effective crossover operator based on evolutionary performance, optimizing the genetic algorithm's efficiency and effectiveness.
- **Multi-Objective Optimization**: Simultaneously optimizes for both the number of features and the classification accuracy, providing a balanced approach to feature selection.
- **Extensive Testing Across Datasets**: Validated on ten diverse datasets, demonstrating robustness and versatility in various application scenarios.

## Installation
To set up this project locally, clone the repository and install the required dependencies.

```bash
git clone https://github.com/youneskazemi/MOBGA-AOS.git
cd MOBGA-AOS
pip install -r requirements.txt
```

## Usage
To run the algorithm with default parameters on your dataset, use the following command:

```bash
python mobga-aos.py --input your_dataset.csv
```

Replace `your_dataset.csv` with the path to your dataset file.

## Contributing
Contributions to the MOBGA-AOS project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## Citation
If you use this implementation for academic research, please cite the paper as follows:

```
Yu Xue, Haokai Zhu, Jiayu Liang, Adam Słowik, "Adaptive Crossover Operator Based Multi-Objective Binary Genetic Algorithm for Feature Selection in Classification", Knowledge-Based Systems, 2021.
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
