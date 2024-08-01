# Airline_Passenger_Satisfaction
Airline Passenger Satisfaction Analysis This repository contains a project that analyzes airline passenger satisfaction using the K-Nearest Neighbors (KNN) algorithm. The project involves exploratory data analysis, data cleaning, and model training to predict passenger satisfaction based on various features.


This repository contains a Jupyter notebook that applies the K-Nearest Neighbors (KNN) algorithm to analyze and predict airline passenger satisfaction based on various service and demographic features.

## Table of Contents
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project explores how well the K-Nearest Neighbors (KNN) algorithm can classify airline passengers as 'satisfied' or 'dissatisfied' based on their feedback on various aspects of their flight experience. The analysis includes data cleaning, exploratory data analysis, model building, and performance evaluation.

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/Nirmal0214/Airline-Passenger-Satisfaction.git
   ```
2. Navigate to the project directory:
   ```
   cd Airline-Passenger-Satisfaction
   ```
3. Install required Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the notebook:
1. Open Jupyter Notebook or JupyterLab.
2. Navigate to the notebook `airline-passenger-satisfaction-knn.ipynb`.
3. Execute the notebook cells sequentially to view the analysis and results.

## Data Description

The dataset includes the following features:
- Age
- Flight Distance
- Inflight wifi service
- Departure/Arrival time convenient
- Ease of Online booking
- Gate location
- Food and drink
- Online boarding
- Seat comfort
- Inflight entertainment
- On-board service
- Leg room service
- Baggage handling
- Check-in service
- Inflight service
- Cleanliness
- Departure Delay in Minutes
- Arrival Delay in Minutes

The target variable is `satisfaction`.

## Methodology

The project follows these steps:
1. Data Importing
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Model Training using K-Nearest Neighbors
5. Model Evaluation and Optimization

## Results

The effectiveness of the KNN model is assessed using accuracy, precision, recall, F1-score, and ROC-AUC score. Detailed results and analysis are provided within the notebook.

