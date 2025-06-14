# PBR-BNN for Occupant Detection

This repository contains code and resources related to the implementation of Physics-Based Regularized Bayesian Neural Networks (PBR-BNN) for precise occupant detection in the context of building energy optimization.

![Occupancy](Figures/Research_Framework.png)

## Overview

Accurate occupancy detection is crucial for optimizing building energy management. Challenges arising from limited data, sensor noise, and intricate dynamics often undermine precision. In this project, we propose a two-step approach to address these challenges:

1. **Feature Enhancement**: We incorporate supplementary features derived from building information to enhance data quality and predictive capacity.

2. **Physics-Based Regularization**: A physics-based regularizer is integrated into a Bayesian Neural Network Model, ensuring adherence to constraints and reliable uncertainty estimation, thus elevating prediction precision.

## Usage

### Prerequisites

The replication package requires Python 3.8+ and a bunch of dependencies listed in the `requirements.txt` file. Install the `requirements.txt` before running each notebook.

```
pip install -r requirements.pip
```

## Project Structure

- `dataset`: Utilizing open-access data from an office building experiment encompassing occupancy profiles, electricity consumption, and indoor environmental data [33]. This folder entails all the data required to replicate the notebooks.

- `GUI`: Contains the code for the web application, which can also be accessed at [scis_occupancy](https://scisoccupancy.streamlit.app/) and [Occupant Detector](https://huggingface.co/spaces/Allmen/Occupancy-Detection).
- `Figures`: Contains the images from this research.
- `Notebooks`: Contains all notebook files. Ensure to have install the requirements before usage.
- `saved_model`: Contains saved model for each test cases.

## Algorithms

The algorithms trained and tested on this project include:

- Naïve Bayes
- Gradient Boosting Machine
- Kernelized Support Vector Machine
- Bayesian Neural Network
- PBR-BNN

## Citation

[![DOI](https://img.shields.io/badge/DOI-10.1016/j.jobe.2025.112777-blue.svg)](https://doi.org/10.1016/j.jobe.2025.112777)

**A. Yahaya, A.B. Owolabi, D. Suh**,  
*Enhancing Building Energy through Regularized Bayesian Neural Networks for Precise Occupancy Detection*,  
**Journal of Building Engineering**, 2025.  
[https://doi.org/10.1016/j.jobe.2025.112777](https://doi.org/10.1016/j.jobe.2025.112777)

