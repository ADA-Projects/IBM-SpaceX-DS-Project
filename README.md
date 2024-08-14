# SpaceX Missile Launch Success Prediction
## Overview
This project is a comprehensive analysis of SpaceX's missile launch data, focusing on the success and failure rates of their missions. Leveraging data science techniques, we explore the factors influencing the outcomes of launches, including payload mass, launch sites, orbit types, and more. Additionally, machine learning models are developed to predict the success probability of future launches based on historical data.

## Project Structure
Data Collection and Cleaning: The project begins with collecting raw data from various sources, including SpaceX's public records and Wikipedia. The data is then cleaned, formatted, and stored in a structured format suitable for analysis.

Exploratory Data Analysis (EDA): In this section, we perform a detailed analysis of the dataset. We examine the distribution of variables, identify trends, and visualize the relationships between different features and the success rate of launches.

Feature Engineering: Key features are extracted and transformed to improve the predictive power of the machine learning models. This includes encoding categorical variables, scaling numerical features, and generating new features from existing data.

Model Development: Multiple machine learning models are implemented to predict the success of future SpaceX launches. These include Logistic Regression, Decision Trees, Support Vector Machines (SVM), and k-Nearest Neighbors (kNN). Hyperparameter tuning is conducted using GridSearchCV to optimize model performance.

Model Evaluation: The models are evaluated using metrics such as accuracy, precision, recall, and F1-score. The best-performing model is selected based on its ability to generalize to unseen data.

Visualization: Interactive maps and charts are created using Folium and Matplotlib/Seaborn to visualize the spatial distribution of launch sites and the success rates across different orbits and locations.

### Getting Started
Prerequisites
Ensure you have the following packages installed:

Python 3.x \
pandas \
numpy \
matplotlib \
seaborn \ 
scikit-learn \ 
folium \
sqlalchemy \
ipython-sql


## Installation
### Clone the repository:

git clone https://github.com/ADA-Projeccts/IBM-SpaceX-DS-Project.git

### Navigate to the project directory:

cd IBM-SpaceX-DS-Project

### Install the required Python packages:

pip install -r requirements.txt

### Running the Project
To reproduce the analysis and model development, execute the Jupyter notebooks in the following order:

000_SpaceX_Final_PP.pdf \
001_SpaceX_Data_Collection_API.ipynb \
002_SpaceX_Web_Scraping.ipynb \
003_SpaceX_Data_Wrangling.ipynb \
004_SpaceX_EDA_SQL.ipynb \
005_SpaceX_EDA_Data_Visualization.ipynb \
006_SpaceX_Interactive_Visual_Analytics_Folium.ipynb \
007_SpaceX_Interactive_Visual_Analytics_Plotly \
008_SpaceX_Predictive_Analytics.ipynb 

The analysis reveals significant insights into the factors influencing the success of SpaceX launches. The machine learning models developed in this project provide a robust mechanism for predicting the likelihood of a successful launch based on historical data.
