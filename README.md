# Paper
Repository Description
This repository contains the source code and dataset for analyzing and forecasting air quality, specifically PM2.5 levels, in Southwestern Morocco. The project utilizes an AIoT platform equipped with low-cost sensors to collect air quality data, which is then transmitted via WiFi/3G for analysis and prediction on a central server.

The main objectives of this study include:

Data Collection and Transmission: Using low-cost sensors to gather air quality data and transmit it in real-time.
Feature Selection: Implementing Minimum Redundancy Maximum Relevance (mRMR) and LightGBM Recursive Feature Elimination (LightGBM-RFE) techniques to identify the most relevant features for PM2.5 prediction.
Model Optimization: Employing Bayesian optimization to fine-tune hyperparameters of various machine learning models.
Model Evaluation: Assessing the performance of different models using metrics such as Root Mean Square Error (RMSE), Mean Absolute Error (MAE), and the coefficient of determination (R²).
The repository provides all necessary scripts and notebooks to replicate the data cleaning, analysis, visualization, and modeling processes used in this study.

Repository Contents
Data Cleaning and Preprocessing: Scripts for cleaning and preparing data, including handling missing values and removing outliers.
Exploratory Data Analysis (EDA): Jupyter notebooks containing detailed exploratory analysis of air quality data.
Visualizations: Scripts using Plotly to create interactive visualizations, including 3D scatter plots and density contours.
Modeling: Implementations of various regression models to predict PM2.5 levels.
Feature Selection: Code for identifying optimal features using mRMR and LightGBM-RFE techniques.
Hyperparameter Optimization: Scripts for Bayesian optimization to fine-tune the hyperparameters of machine learning models.
Results and Reports: Results from analyses and models, with detailed reports on findings from the data.
Dataset: The dataset used for the analysis, including PM2.5 levels, timestamps, and other relevant features.
Instructions
Clone the repository:

bash
Copier le code
git clone https://github.com/abdbekkar/Paper.git
Install dependencies:

bash
Copier le code
pip install -r requirements.txt
Run the Jupyter notebooks:
Launch Jupyter Notebook and open the notebooks to explore the analyses and visualizations.

Environment and Configuration
Python Version: 3.7
Processor: 8th Gen Intel(R) Core(TM) i7
RAM: 16.0 GB
System Type: 64-bit operating system, x64 based processor
Author
Name: Abdellatif Bekkar
Email: abdellatif.bekkar-etu@etu.univh2c.ma
Affiliation: LIM Laboratory, Faculty of Sciences and Technics Hassan II University of Casablanca, Mohammedia, Morocco
Feel free to contact me with any questions or suggestions regarding this project.
