# Parallel k-NN for Credit Card Transaction Classification

## Description
This project implements a parallelized version of the **k-Nearest Neighbors (k-NN)** algorithm for classifying credit card transactions, using **MPI** (Message Passing Interface) and **pthreads**. The algorithm calculates distances between query samples and training data in parallel, reducing execution time and improving scalability for large datasets. The classification assigns the majority class (fraudulent or non-fraudulent) based on the closest neighbors.

For a detailed explanation of the method and results, please refer to the [research paper](./Optimzed parallel KNN algorithm using MPI and multithreading.docx).

## Features
- Parallel distance computation with **MPI** and **pthreads**
- Scalable and efficient for large datasets
- Predicts credit card transaction classes based on the nearest neighbors
