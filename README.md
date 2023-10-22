# Classification Beyond Balance

![64fafb23-e5d7-473a-b718-7888c7779792](https://github.com/alinemsm/classification-beyond-balance/assets/4826198/bbc5536e-2063-44aa-b14c-7a887bd05a72)

My notes as I attempt to make sense of the literature on handling severely imbalanced classes for prediction in practice.

## Table of Contents

1. [Foundations](#imbalanced-classes)
    1. [Prelude to Foundation: Who needs balance?](#what-is-imbalanced-data)
    2. [Foundation: Establishing prediction goals](#establishing-prediction-goals)
    3. [Second Foundation: Multi-layered approaches](#multi-layered-approaches)
    4. [Foundation's Edge: The importance of the 1's](#importance-of-the-1's)
    5. [Forward the Foundation: The importance of the 0's](#importance-of-the-0's)
2. [Resampling Methods: do they work?](#resampling-methods)
    1. [Undersampling](#undersampling)
    2. [Oversampling](#oversampling)
    3. [Hybrid](#hybrid)
3. [Dimensionality Reduction: how to best capture the 1's?](#dimensionality-reduction)
4. [Algorithms](#algorithms)
5. [Cost Sensitive Learning](#cost-sensitive-learning)
6. [Evaluation Metrics](#evaluation-metrics)
7. [References](#references)