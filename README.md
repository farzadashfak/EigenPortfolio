# Eigen Portfolio Construction using PCA

This project demonstrates the construction of eigen portfolios using Principal Component Analysis (PCA). Eigen portfolios are constructed by utilizing the eigenvectors derived from the covariance matrix of asset returns. This technique is often used in finance for portfolio optimization and risk management.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Usage](#usage)
- [Requirements](#requirements)
- [Installation](#installation)
- [Data](#data)
- [Results](#results)
- [License](#license)

## Introduction

Portfolio construction is a crucial aspect of modern finance. Eigen portfolio construction using PCA is a technique that allows us to create portfolios that capture the most significant sources of variance in a given set of financial assets. By focusing on the eigenvectors corresponding to the largest eigenvalues of the covariance matrix, we can create portfolios that are diversified and well-balanced.

## Project Overview

This project consists of the following main steps:

1. **Data Preparation**: Collect historical data for a set of financial assets. Calculate the returns and compute the covariance matrix.
   
2. **PCA Calculation**: Perform PCA on the covariance matrix to obtain the eigenvectors and eigenvalues.
   
3. **Eigen Portfolio Construction**: Select the top eigenvectors corresponding to the largest eigenvalues and use them to construct eigen portfolios.
   
4. **Performance Evaluation**: Evaluate the performance of the eigen portfolios based on various risk and return metrics.
   
5. **Visualization**: Visualize the composition and performance of the eigen portfolios.
