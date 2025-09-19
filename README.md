# Iris Species Classifier using k-Nearest Neighbors (k-NN)

## Project Overview
This project provides a comprehensive walkthrough of the k-Nearest Neighbors algorithm, one of the fundamental classifiers in machine learning. The primary goal is to predict the species of an Iris flower (setosa, versicolor, or virginica) based on its sepal and petal measurements.

The project tackles the problem from two perspectives to demonstrate a full-stack understanding:

A practical implementation using the industry-standard scikit-learn library, showcasing a typical data science workflow from exploration to evaluation.

A foundational implementation building the k-NN algorithm entirely from scratch using NumPy, illustrating a deep, first-principles understanding of its inner workings.

## Key Learnings & Skills Demonstrated
This project showcases a range of essential machine learning and data science skills:

Fundamental ML Concepts: A solid understanding of supervised learning, classification, train/test splits for robust evaluation, and the critical importance of feature scaling for distance-based algorithms.

Algorithm Implementation: The ability to implement a classic machine learning algorithm from scratch, including distance metrics, neighbor identification, and voting logic.

Data Science Libraries: Proficient use of the Python data science stack:

Pandas: For efficient data loading and manipulation.

NumPy: For high-performance numerical computation in the from-scratch implementation.

Scikit-learn: For a professional-grade modeling pipeline, including preprocessing and evaluation.

Data Visualization: Exploratory Data Analysis (EDA) using seaborn and matplotlib to create visualizations (like pair plots) that provide insights and validate model choice.

Reproducibility: The project is structured for full reproducibility using a Python virtual environment (uv) and a locked dependencies file (requirements.txt).

## How to Run This Project
To replicate this analysis on your local machine, please follow these steps:

Clone the Repository

```git clone [https://github.com/YOUR_USERNAME/mldm-iris-knn-classifier.git](https://github.com/YOUR_USERNAME/mldm-iris-knn-classifier.git)```
```cd mldm-iris-knn-classifier```

Create and Activate Virtual Environment
This project uses uv for environment management.

### Create the virtual environment
```uv venv```

### Activate the environment
```source .venv/bin/activate```

Install Dependencies
The requirements.txt file contains all necessary packages.

```uv pip install -r requirements.txt```

Launch JupyterLab and Run Notebooks

```jupyter lab```

The analysis is contained in two notebooks. It's recommended to run them in order:

iris-knn-analysis.ipynb: Contains the Exploratory Data Analysis and the benchmark model using scikit-learn.

knn-from-scratch.ipynb: Contains the complete from-scratch implementation and its evaluation.

## Results

Both the from-scratch k-NN implementation and the scikit-learn model achieved an accuracy of 93.33% on the unseen test set. This successful replication validates the correctness of the custom-built algorithm. The detailed classification report shows the model's only confusion lies in the subtle boundary between the versicolor and virginica species, an observation that aligns perfectly with the initial data visualization.
