# Vehicle Price Prediction using Machine Learning

### Key Sections:
1. **Project Overview**: Brief summary of what the project is about.
2. **Data**: Explains where the data is from and its key features.
3. **Libraries Used**: Lists the main libraries used.
5. **Project Structure**: Explains the file and folder structure of the project.
7. **Evaluation Metrics**: Explanation of the metrics used to evaluate the model.
8. **Example Results**: A snapshot of the model's performance.
9. **Future Improvements**: Possible directions for future work.
11. **Acknowledgements**: Acknowledgement of data sources, tools, etc.
12. **Author**: Your personal details or GitHub link.

## Project Overview

This project aims to build a machine learning model to predict the average price of vehicles based on various features such as engine size, fuel type, brand, and other vehicle characteristics. The model can be applied to predict the price of a vehicle, which could potentially be used in applications like insurance pricing and market analysis.

### Key Features of the Project:
- **Dataset Acquisition**: The data is sourced from FIPE (Fundação Instituto de Pesquisas Econômicas), a prominent vehicle price reference in Brazil.
- **Data Preprocessing**: Cleaning and transforming the dataset to handle missing values, categorical encoding, and feature scaling.
- **Feature Engineering**: Creating new features like vehicle age and transforming existing ones for improved model performance.
- **Model Building**: Implementing **Random Forest Regressor** for regression tasks.
- **Hyperparameter Tuning**: Using **RandomizedSearchCV** for efficient model optimization.
- **Model Evaluation**: Assessing model performance using metrics such as MAE, MSE, RMSE, and R².
- **Exploratory Data Analysis (EDA)**: Visualizing data distributions and correlations to understand patterns.

---

## Data

The dataset used in this project contains information about cars sold in Brazil. It was collected from **FIPE (Fundação Instituto de Pesquisas Econômicas)**, which provides price benchmarks for vehicles. The dataset includes the following features:

- **Year of Reference**: The year when the car's price was referenced.
- **Model**: The car's model.
- **Brand**: The car's brand (e.g., Ford, Chevrolet, Toyota).
- **Engine Size**: The size of the vehicle's engine in liters.
- **Fuel Type**: Type of fuel the vehicle uses (e.g., gasoline, ethanol, flex).
- **Gear Type**: Transmission type (manual or automatic).
- **Age of Vehicle**: The age of the vehicle in years.
- **Average Price in BRL**: The target variable for the regression model.

You can access the dataset [here](https://www.kaggle.com/datasets/vagnerbessa/average-car-prices-bazil/data).

---

## Libraries Used

This project uses a variety of libraries to preprocess data, build machine learning models, and evaluate results. Key libraries include:

- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization and plotting.
- **Scikit-Learn**: For building and evaluating machine learning models.
- **Kaggle**: For dataset downloading and management.
