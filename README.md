# Airline_Passenger_Satisfaction
Airline Passenger Satisfaction Analysis This repository contains a project that analyzes airline passenger satisfaction using the K-Nearest Neighbors (KNN) algorithm. The project involves exploratory data analysis, data cleaning, and model training to predict passenger satisfaction based on various features.

Table of Contents

Project Overview

Installation

Usage

Data Description

Methodology

Results

Contributing

License
Project Overview
The goal of this project is to classify passenger satisfaction based on various features using the K-Nearest Neighbors algorithm. The project involves:

Importing and exploring the data
Cleaning and preprocessing the data
Implementing the K-Nearest Neighbors algorithm
Evaluating the model's performance
Installation
To run the notebook, ensure you have Python installed along with the following packages:

pandas
numpy
matplotlib
seaborn
scikit-learn
scikit-plot
You can install the required packages using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn scikit-plot
Usage
To use this project:

Clone the repository.
Open the Jupyter notebook airline-passenger-satisfaction-knn.ipynb.
Run the cells sequentially to execute the data analysis and model training.
Data Description
The dataset used for this analysis includes features such as:

Age: The age of the passenger.
Flight Distance: The distance of the flight.
Seat comfort, Inflight wifi service, Food and drink, etc.: Various service-related features rated by passengers.
The target variable is satisfaction, indicating whether a passenger is satisfied or not.

Methodology
The project follows these steps:

Importing Data: Load the training and test datasets.
Exploratory Data Analysis (EDA): Visualize and understand data distributions and correlations.
Data Cleaning: Handle missing values and encode categorical variables.
K-Nearest Neighbors: Implement the KNN algorithm to classify passenger satisfaction.
Choosing a K Value: Determine the optimal number of neighbors (K) for the model.
Evaluation: Evaluate the model using accuracy, classification report, and ROC-AUC score.
Results
The model's performance is evaluated using several metrics, including accuracy, precision, recall, and the ROC-AUC score. The notebook provides detailed plots and reports to understand the model's performance.

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any feature requests or bug fixes.

License
This project is open-source and available under the MIT License.

