# Car Fuel Efficiency Prediction
# Project Overview
This project develops a Multiple Linear Regression model to predict highway fuel efficiency (Highway MPG) using selected numerical features from the cars.csv dataset. Implemented in Python (Colab), the project involves essential preprocessing steps, outlier removal, feature selection, and performance evaluation.

# Dataset: cars.csv
The dataset includes various car specifications such as engine type, fuel efficiency, and dimensions. 
The target variable for prediction is:Fuel Information.Highway mpg (Highway fuel efficiency)

# Selected Features
The final features chosen for the model are:

Engine Information.Engine Statistics.Horsepower:-Measures the engine's power output, indicating how quickly work can be performed.
Engine Information.Engine Statistics.Torque:-Represents the engine's rotational force, influencing acceleration and towing capacity.
Dimensions.Height:-The vertical measurement from the vehicle's base to its highest point, affecting aerodynamics and interior space.
Dimensions.Length:-The total length of the vehicle from the front to the rear. Longer vehicles may offer more interior space but can also impact handling and fuel consumption.
Dimensions.Width:-The total width of the vehicle from side to side. A wider car may have better stability but increased air resistance, which can affect fuel efficiency.
Engine Information.Number of Forward Gears:-The number of forward gear ratios in the vehicle’s transmission. More gears can improve fuel efficiency and performance by optimizing power delivery.
Engine Information.Hybrid:- Indicates whether the vehicle is a hybrid (combining a gasoline engine with an electric motor) or not. Hybrid vehicles generally offer better fuel efficiency.
Engine Information.Driveline:-The drivetrain configuration of the vehicle, such as Front-Wheel Drive (FWD), Rear-Wheel Drive (RWD), or All-Wheel Drive (AWD). This affects traction, handling, and fuel consumption.
Engine Information.Transmission:-The type of transmission in the vehicle, such as Manual, Automatic, or Continuously Variable Transmission (CVT). Transmission type influences driving experience, fuel efficiency, and performance.

# Model Development
The project follows these key steps:

1. Data Preprocessing
Handling missing values, duplicates, and categorical variables
2. Feature Selection
Selecting relevant features based on correlation analysis and VIF scores
3. Model Training & Evaluation
Applying Multiple Linear Regression to the selected features after preprocessing
Evaluating performance using Mean Squared Error (MSE) and R-squared (R²)
4. Comparison & Results
Assessing the impact of feature selection and outlier removal on model accuracy and efficiency.
5. Plotting

# Files included
cars.csv – The dataset containing car specifications.
PA_Project1.ipynb – Jupyter Notebook with full preprocessing, feature selection, model training, and evaluation.
README.md – This file containing the project documentation.

# Conclusion
This project highlights the importance of feature selection and outlier removal in improving model performance. The final model delivers a more accurate and interpretable prediction of fuel efficiency using the most relevant car characteristics.
