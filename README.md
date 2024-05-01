# ML_Project55-DecisionTrees_WeatherDataClassification

### Decision Trees Weather Data Classification
### Overview

This project focuses on classifying weather data into high humidity vs. non-high humidity days using decision tree-based classification techniques. The dataset used for this project contains daily weather data collected from a weather station located in San Diego, California, over a period of three years. The objective is to predict whether a day will have high humidity based on morning weather measurements.

### Project Structure
#### The project follows the below structure:
##### Data Preparation: 
The weather data is loaded from a CSV file (daily_weather.csv).

Data cleaning is performed to remove irrelevant columns and null values.

##### Data Description:
The dataset contains various weather-related variables such as air pressure, temperature, wind speed, and humidity.

Each row represents weather measurements for a separate day.

##### Data Binarization:
The target variable relative_humidity_3pm is binarized to represent high humidity (1) or non-high humidity (0) days.
##### Feature Selection:
Morning weather measurements (e.g., air pressure, temperature, wind speed) are selected as features to predict humidity at 3pm.
##### Model Training:
The dataset is split into training and testing sets.

A decision tree classifier is trained on the training data.
##### Model Evaluation:
The trained model is evaluated on the testing data to measure its accuracy.
##### Accuracy Measurement:
The accuracy score of the classifier is calculated to assess its performance.

### How to Run
Clone Repository: Clone this repository to your local machine.

Install Dependencies: Ensure all dependencies mentioned in the requirements.txt file are installed.

Download Dataset: Download the weather dataset file (daily_weather.csv) and place it in the project directory.

Run Notebook: Open and run the decision_trees_weather_classification.ipynb notebook using Jupyter Notebook or any compatible platform.

Review Results: After running the notebook, review the model's accuracy score and predictions.

### Notes
Experiment with different hyperparameters for the decision tree classifier to optimize model performance.

Visualize the decision tree to gain insights into how the model makes predictions.

Customize the code and parameters as per your requirements and resources.

Feel free to reach out for any questions or assistance.

### Acknowledgements
This project utilizes daily weather data collected from a weather station located in San Diego, California.

The dataset is sourced from an undisclosed weather data provider.

Special thanks to the scikit-learn library for providing efficient machine learning algorithms and tools.
