# Predictive-Housing-Price-Analysis
"Unlock property value trends in Boston &amp; Perth with UrbanNestValue. Dive into predictive models for housing markets. From ridge regression to neural networks, explore the art of price prediction."

# House Price Prediction Project

Welcome to the Predictive-Housing-Price-Analysis repository! This project focuses on predicting house prices using the Boston and Perth datasets. The repository contains various code files that implement different predictive models and analyses. Below, you'll find a detailed guide to the contents of this repository.

## Datasets

The project utilizes two datasets: the Boston dataset and the Perth dataset.

1. **Boston Dataset** (Imported from scikit-learn):
   - This dataset contains information about various features related to housing in the Boston area.
   - The dataset is imported directly from the scikit-learn library and used for analysis.
   
2. **Perth Dataset** (Imported from Kaggle, stored in 'Datasets' folder):
   - This dataset comprises housing-related data specific to the Perth region.
   - The dataset is available in the 'Datasets' folder of this repository.

## Code Files

The repository contains a collection of code files that perform different analyses and modeling approaches on the datasets. Each code file is an IPython Notebook (.ipynb) executed in a sequential manner.

1. **Ridge Regression from Scratch**:
   - Implementation of ridge regression from scratch using the Boston dataset.
   - Provides insights into the inner workings of ridge regression.
   
2. **Comparative Analysis using 7 Models**:
   - This notebook presents a comprehensive comparative analysis of various predictive models on both the Boston and Perth datasets.
   - The following models are included:
     - Ridge Regression (Implemented from scratch)
     - SGD Boost
     - XGBoost
     - Decision Tree
     - Support Vector Regression (SVR) with different kernel functions
     - Random Forest
     - Neural Network Model

## SVR Kernel Study

In the SVR model analysis, a study was conducted to determine the best-performing kernel function for the Perth dataset. The following kernel functions were tested: Sigmoid, Linear, Poly, and RBF. Despite the various options, the Random Forest model exhibited the best performance among all.

## Repository Structure

The structure of the repository is as follows:

```
House-Price-Prediction-Project/
│
├── Datasets/
│   ├── perth_dataset.csv
│
├── Ridge_Regression_from_Scratch.ipynb
├── Comparative_Analysis_7_Models.ipynb
│
├── README.md
```

## Getting Started

To start exploring this project, follow these steps:

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook files (`.ipynb`) using Jupyter Notebook or Jupyter Lab.
3. Run the cells in the notebooks sequentially to see the analyses and modeling results.

Please note that the `.ipynb` files are organized in a way that ensures the analysis and code execution flow smoothly.

Feel free to reach out if you have any questions or need further assistance.

Happy coding and predicting house prices! 🏡📈

— Onkar Sudrik
