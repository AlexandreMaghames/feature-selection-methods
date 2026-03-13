# High-Dimensional Feature Selection by Feature-Wise Kernelized Lasso <!-- omit in toc -->
Final-year project at [ENSAI](https://www.ensai.fr) dedicated to the analysis and reproduction of results from the paper "High-Dimensional Feature Selection by Feature-Wise Kernelized Lasso". The project implements and evaluates this method alongside several comparative feature selection approaches in high-dimensional statistical settings.

## Sommaire <!-- omit in toc -->
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Installation and Repository](#installation-and-repository)
  - [Installation](#installation)
  - [Repository Structure](#repository-structure)
- [Main results](#main-results)
  - [Synthetics datasets](#synthetics-datasets)
  - [Real Word datasets](#real-word-datasets)
- [Contributeurs](#contributeurs)

## Project Overview

High-dimensional datasets, where the number of features greatly exceeds the number of observations, are common in many fields such as:
- genomics
- signal processing
- finance
- machine learning

In such contexts, feature selection becomes essential for:
- improving model interpretability
- reducing overfitting
- decreasing computational complexity

This project studies the **Feature-Wise Kernelized Lasso**, a method designed to perform feature selection in high-dimensional spaces using kernel-based dependency measures.

The implementation aims to reproduce and analyze the results presented in the original research paper.

## Objectives

The main goals of this project are:
- Read, understand and summarize the original paper on the topic
- Implement the Feature-Wise Kernelized Lasso algorithm
- Reproduce experimental results from the original paper on synthetics and real-world datasets
- Compare FW-KLasso with other classical feature selection techniques

## Installation and Repository
### Installation
```bash 
git clone https://github.com/AlexandreMaghames/feature-selection-methods.git
cd feature-selection-methods/
pip install -r requirements.txt
```

### Repository Structure

```
├── data/
│   ├── input/                
│   └── output/           
│
├── notebooks/                
│   ├── exploratory/                # Exploratory data analysis
│   └── experiments/                # Experimental notebooks reproducing results
│
├── src/                            # Source code of the project
│   ├── lib/
│       ├── feature_selection/      # Implementation of FW-KLasso and related methods
│       ├── models/                 # Statistical models and algorithms
│       ├── utils/                  # Utility functions
│       └── config.py               # Configuration parameters
│
├── docs/                     # Documentation (methodology, reports, figures)
│   ├── figures/
│   └── report/
│
├── tests/                    # Unit tests
│
├── requirements.txt          
├── pyproject.toml            
├── LICENSE                   
├── README.md                 
└── .gitignore
```

## Main results 
For more details about results, check the folder ```docs/```, with presentation and report.
### Synthetics datasets 

### Real Word datasets

## Contributeurs
- [LEBOT Marceau](https://github.com/MarceauLB)
- [BRAULT Tom](https://github.com/TomBrault) 
- [MAGHAMES Alexandre](https://github.com/AlexandreMaghames)
