# Complete Machine Learning & Data Science (Zero to Mastery)

![6-Step ML Framework](./6-step-ml-framework.png)

## Overview
This repository contains my notes, code, and mini-projects from the Udemy course: [Complete Machine Learning and Data Science: Zero to Mastery](https://www.udemy.com/course/complete-machine-learning-and-data-science-zero-to-mastery/).

## Table of Contents
1. [Project Structure](#project-structure)
2. [Getting Started](#getting-started)
3. [Running the Notebooks](#running-the-notebooks)
4. [The 6-Step ML Framework](#the-6-step-ml-framework)
5. [Datasets](#datasets)
6. [Notebook Guide](#notebook-guide)
7. [Troubleshooting](#troubleshooting)

## Project Structure
```
.
├── main.ipynb                         # End-to-end ML project (6-step framework)
├── introduction-to-pandas.ipynb       # Pandas basics and data manipulation
├── car-sales.csv                      # Sample dataset for Pandas exercises
├── heart-disease.csv                  # Heart disease dataset for classification
├── exported_*.csv                     # Example exports from notebooks
└── 6-step-ml-framework.png           # Framework overview
```

## Getting Started

### Prerequisites
- Python 3.8+
- pip or conda
- Jupyter Notebook/Lab

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd first_project_1
   ```

2. Create and activate a virtual environment:
   ```bash
   # Using venv (Windows)
   python -m venv venv
   .\venv\Scripts\activate
   
   # Or using conda
   conda create -n ml-course python=3.8
   conda activate ml-course
   ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   # Or install individually:
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

## Running the Notebooks
1. Start Jupyter Notebook/Lab:
   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

2. Open either:
   - `introduction-to-pandas.ipynb` for data manipulation basics
   - `main.ipynb` for the complete ML workflow

## The 6-Step ML Framework
1. **Problem Definition** - What are we trying to predict or classify?
2. **Data** - Loading, exploring, and preparing the data
3. **Evaluation** - Defining success metrics
4. **Features** - Feature engineering and selection
5. **Modeling** - Training and tuning machine learning models
6. **Experimentation** - Iterating and improving the solution

## Datasets
- `car-sales.csv`: Sample dataset for practicing Pandas operations
- `heart-disease.csv`: Medical dataset for classification tasks

## Notebook Guide
### Introduction to Pandas (`introduction-to-pandas.ipynb`)
- Loading and saving data
- Data exploration and cleaning
- Basic data visualization
- Data manipulation with Pandas

### Main Project (`main.ipynb`)
- Complete ML workflow
- Data preprocessing
- Model training and evaluation
- Hyperparameter tuning
- Results analysis

## Troubleshooting
- **Kernel Issues**: Ensure you've activated the correct environment before starting Jupyter
- **Missing Packages**: Reinstall requirements if packages are missing
- **Plotting**: If plots don't appear, try adding `%matplotlib inline` at the start of your notebook
- **Memory Issues**: For large datasets, consider using `dask` or processing data in chunks

## License
This project is for educational purposes as part of the ZTM Machine Learning & Data Science course.
