# 🛍️ Retail Customer Segmentation using K-Means Clustering

Welcome to the Retail Customer Segmentation project! This project aims to group customers of a retail store based on their purchase history using the K-means clustering algorithm. 🎯

## 📋 Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 📌 Introduction

In this project, we implement a K-means clustering algorithm to segment customers of a retail store into different groups. This segmentation helps in understanding customer behavior and can be used to tailor marketing strategies to different customer groups. 📊

## 📂 Dataset

The dataset used in this project is the **Mall Customers** dataset. It contains information about customers including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## 🛠️ Requirements

Make sure you have the following packages installed:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## 💾 Installation

To install the necessary packages, run:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn

## 🚀 Usage

### 1. Set up the environment

First, ensure your environment is set up correctly to avoid memory leak warnings. Set the `OMP_NUM_THREADS` environment variable:

```sh
conda activate datascience
conda env config vars set OMP_NUM_THREADS=1
conda deactivate
conda activate datascience


## 2. Run the script
Download the script from the repository and run it in your Jupyter Notebook or Python environment.

3. Interpret the results
The Elbow Method graph will help you determine the optimal number of clusters for segmenting the customers. 📈

### 🎨 Results
After running the K-means algorithm, you'll have different customer segments. These segments can be visualized and analyzed to understand distinct customer behaviors and preferences.

### 🤝 Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue. Let's make this project better together! 🌟
